# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/models/backbones/adapter_modules.py

Prompts

```
['build a SpatialPriorModule to extract multi-scale image features at 8s, 16s, and 32s strides', 'create an InteractionBlock that injects image features into transformer tokens using deformable attention', 'test the Extractor module to extract features from transformer tokens via MSDeformAttn and ConvFFN', 'refactor the Injector module to adjust deformable attention injection with learnable gamma scaling', 'review the ConvFFN class that combines linear layers with depthwise convolution for feed-forward processing', 'apply stochastic depth dropout to a PyTorch tensor during training with configurable drop probability', 'create a DropPath nn.Module that drops residual paths with a given probability during training', 'test the drop_path function by passing a tensor with drop_prob 0.5 in training mode', 'test the DropPath module by creating an instance with drop_prob 0.3 and forwarding a tensor', 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth', 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build an Mlp feed-forward layer with configurable hidden features, activation, and dropout for transformer blocks', 'create a SwiGLUFFN gated feed-forward network with SiLU activation and 8-aligned hidden dimensions', 'review the WindowedAttention class that applies self-attention over fixed-size spatial windows with padding', 'build a ViTAdapter backbone with deformable attention and spatial prior module for multi-scale segmentation', 'create a ViTAdapter instance with freeze_vit=True to freeze the base Vision Transformer weights', 'run the ViTAdapter forward pass to extract four multi-scale feature maps from an input image tensor', 'review the ViTAdapter interaction blocks that combine Vision Transformer features with CNN spatial priors via deformable attention', 'refactor the ViTAdapter to toggle use_cls for including or excluding the classification token in interactions']
```

Usage

```
{'build_SpatialPriorModule': 'build a SpatialPriorModule to extract multi-scale image features at 8s, 16s, and 32s strides', 'create_InteractionBlock': 'create an InteractionBlock that injects image features into transformer tokens using deformable attention', 'test_Extractor': 'test the Extractor module to extract features from transformer tokens via MSDeformAttn and ConvFFN', 'refactor_Injector': 'refactor the Injector module to adjust deformable attention injection with learnable gamma scaling', 'review_ConvFFN': 'review the ConvFFN class that combines linear layers with depthwise convolution for feed-forward processing'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/models/backbones/drop_path.py

Prompts

```
['build a SpatialPriorModule to extract multi-scale image features at 8s, 16s, and 32s strides', 'create an InteractionBlock that injects image features into transformer tokens using deformable attention', 'test the Extractor module to extract features from transformer tokens via MSDeformAttn and ConvFFN', 'refactor the Injector module to adjust deformable attention injection with learnable gamma scaling', 'review the ConvFFN class that combines linear layers with depthwise convolution for feed-forward processing', 'apply stochastic depth dropout to a PyTorch tensor during training with configurable drop probability', 'create a DropPath nn.Module that drops residual paths with a given probability during training', 'test the drop_path function by passing a tensor with drop_prob 0.5 in training mode', 'test the DropPath module by creating an instance with drop_prob 0.3 and forwarding a tensor', 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth', 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build an Mlp feed-forward layer with configurable hidden features, activation, and dropout for transformer blocks', 'create a SwiGLUFFN gated feed-forward network with SiLU activation and 8-aligned hidden dimensions', 'review the WindowedAttention class that applies self-attention over fixed-size spatial windows with padding', 'build a ViTAdapter backbone with deformable attention and spatial prior module for multi-scale segmentation', 'create a ViTAdapter instance with freeze_vit=True to freeze the base Vision Transformer weights', 'run the ViTAdapter forward pass to extract four multi-scale feature maps from an input image tensor', 'review the ViTAdapter interaction blocks that combine Vision Transformer features with CNN spatial priors via deformable attention', 'refactor the ViTAdapter to toggle use_cls for including or excluding the classification token in interactions']
```

Usage

```
{'use_drop_path_function': 'apply stochastic depth dropout to a PyTorch tensor during training with configurable drop probability', 'use_DropPath_module': 'create a DropPath nn.Module that drops residual paths with a given probability during training', 'test_drop_path_function': 'test the drop_path function by passing a tensor with drop_prob 0.5 in training mode', 'test_DropPath_module': 'test the DropPath module by creating an instance with drop_prob 0.3 and forwarding a tensor', 'review_drop_path_implementation': 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/models/backbones/vit.py

Prompts

```
['build a SpatialPriorModule to extract multi-scale image features at 8s, 16s, and 32s strides', 'create an InteractionBlock that injects image features into transformer tokens using deformable attention', 'test the Extractor module to extract features from transformer tokens via MSDeformAttn and ConvFFN', 'refactor the Injector module to adjust deformable attention injection with learnable gamma scaling', 'review the ConvFFN class that combines linear layers with depthwise convolution for feed-forward processing', 'apply stochastic depth dropout to a PyTorch tensor during training with configurable drop probability', 'create a DropPath nn.Module that drops residual paths with a given probability during training', 'test the drop_path function by passing a tensor with drop_prob 0.5 in training mode', 'test the DropPath module by creating an instance with drop_prob 0.3 and forwarding a tensor', 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth', 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build an Mlp feed-forward layer with configurable hidden features, activation, and dropout for transformer blocks', 'create a SwiGLUFFN gated feed-forward network with SiLU activation and 8-aligned hidden dimensions', 'review the WindowedAttention class that applies self-attention over fixed-size spatial windows with padding', 'build a ViTAdapter backbone with deformable attention and spatial prior module for multi-scale segmentation', 'create a ViTAdapter instance with freeze_vit=True to freeze the base Vision Transformer weights', 'run the ViTAdapter forward pass to extract four multi-scale feature maps from an input image tensor', 'review the ViTAdapter interaction blocks that combine Vision Transformer features with CNN spatial priors via deformable attention', 'refactor the ViTAdapter to toggle use_cls for including or excluding the classification token in interactions']
```

Usage

```
{'build_vit_backbone': 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create_patch_embed': 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build_mlp_layer': 'build an Mlp feed-forward layer with configurable hidden features, activation, and dropout for transformer blocks', 'create_swiglu_ffn': 'create a SwiGLUFFN gated feed-forward network with SiLU activation and 8-aligned hidden dimensions', 'review_windowed_attention': 'review the WindowedAttention class that applies self-attention over fixed-size spatial windows with padding'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/models/backbones/vit_adapter.py

Prompts

```
['build a SpatialPriorModule to extract multi-scale image features at 8s, 16s, and 32s strides', 'create an InteractionBlock that injects image features into transformer tokens using deformable attention', 'test the Extractor module to extract features from transformer tokens via MSDeformAttn and ConvFFN', 'refactor the Injector module to adjust deformable attention injection with learnable gamma scaling', 'review the ConvFFN class that combines linear layers with depthwise convolution for feed-forward processing', 'apply stochastic depth dropout to a PyTorch tensor during training with configurable drop probability', 'create a DropPath nn.Module that drops residual paths with a given probability during training', 'test the drop_path function by passing a tensor with drop_prob 0.5 in training mode', 'test the DropPath module by creating an instance with drop_prob 0.3 and forwarding a tensor', 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth', 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build an Mlp feed-forward layer with configurable hidden features, activation, and dropout for transformer blocks', 'create a SwiGLUFFN gated feed-forward network with SiLU activation and 8-aligned hidden dimensions', 'review the WindowedAttention class that applies self-attention over fixed-size spatial windows with padding', 'build a ViTAdapter backbone with deformable attention and spatial prior module for multi-scale segmentation', 'create a ViTAdapter instance with freeze_vit=True to freeze the base Vision Transformer weights', 'run the ViTAdapter forward pass to extract four multi-scale feature maps from an input image tensor', 'review the ViTAdapter interaction blocks that combine Vision Transformer features with CNN spatial priors via deformable attention', 'refactor the ViTAdapter to toggle use_cls for including or excluding the classification token in interactions']
```

Usage

```
{'build_ViTAdapter_backbone': 'build a ViTAdapter backbone with deformable attention and spatial prior module for multi-scale segmentation', 'create_ViTAdapter_with_frozen_vit': 'create a ViTAdapter instance with freeze_vit=True to freeze the base Vision Transformer weights', 'run_ViTAdapter_forward_multi_scale': 'run the ViTAdapter forward pass to extract four multi-scale feature maps from an input image tensor', 'review_ViTAdapter_interaction_blocks': 'review the ViTAdapter interaction blocks that combine Vision Transformer features with CNN spatial priors via deformable attention', 'refactor_ViTAdapter_cls_token_handling': 'refactor the ViTAdapter to toggle use_cls for including or excluding the classification token in interactions'}
```


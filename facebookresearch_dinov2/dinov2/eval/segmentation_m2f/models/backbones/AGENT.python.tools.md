# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/models/backbones/adapter_modules.py

Prompts

```
['build a SpatialPriorModule to extract multi-scale CNN features from an input image tensor', 'create an InteractionBlock that injects image features into tokens and extracts updated context features', 'create an InteractionBlockWithCls that processes tokens with a cls token alongside image feature injection', 'build an Extractor module with MSDeformAttn and ConvFFN to extract features from multi-scale spatial inputs', 'build an Injector module with MSDeformAttn to inject multi-scale image features into query tokens', 'build a PyTorch module that applies stochastic depth drop path regularization to tensor inputs', 'create a function that randomly drops entire sample paths with configurable drop probability during training', 'test the DropPath nn.Module class by passing tensors through it with various drop probabilities', 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth', 'refactor the DropPath class to support custom tensor dimensions beyond standard 2D ConvNets', 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build an Mlp feed-forward layer with configurable hidden dimension, activation, and dropout for transformer blocks', 'create a SwiGLUFFN gated feed-forward network layer with SiLU activation and 8-byte alignment', 'resize position embeddings using bicubic interpolation to match new input image shapes', 'build a ViTAdapter backbone with deformable attention for multi-scale semantic segmentation', 'create a ViTAdapter instance with freeze_vit=True to freeze the base ViT weights', 'run the ViTAdapter forward pass on an image tensor to get multi-scale feature maps', 'review the ViTAdapter interaction_indexes parameter to configure which ViT blocks interact with conv features', 'test the ViTAdapter with use_cls=True to include class tokens in the interaction blocks']
```

Usage

```
{'build_SpatialPriorModule': 'build a SpatialPriorModule to extract multi-scale CNN features from an input image tensor', 'create_InteractionBlock': 'create an InteractionBlock that injects image features into tokens and extracts updated context features', 'create_InteractionBlockWithCls': 'create an InteractionBlockWithCls that processes tokens with a cls token alongside image feature injection', 'build_Extractor': 'build an Extractor module with MSDeformAttn and ConvFFN to extract features from multi-scale spatial inputs', 'build_Injector': 'build an Injector module with MSDeformAttn to inject multi-scale image features into query tokens'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/models/backbones/drop_path.py

Prompts

```
['build a SpatialPriorModule to extract multi-scale CNN features from an input image tensor', 'create an InteractionBlock that injects image features into tokens and extracts updated context features', 'create an InteractionBlockWithCls that processes tokens with a cls token alongside image feature injection', 'build an Extractor module with MSDeformAttn and ConvFFN to extract features from multi-scale spatial inputs', 'build an Injector module with MSDeformAttn to inject multi-scale image features into query tokens', 'build a PyTorch module that applies stochastic depth drop path regularization to tensor inputs', 'create a function that randomly drops entire sample paths with configurable drop probability during training', 'test the DropPath nn.Module class by passing tensors through it with various drop probabilities', 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth', 'refactor the DropPath class to support custom tensor dimensions beyond standard 2D ConvNets', 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build an Mlp feed-forward layer with configurable hidden dimension, activation, and dropout for transformer blocks', 'create a SwiGLUFFN gated feed-forward network layer with SiLU activation and 8-byte alignment', 'resize position embeddings using bicubic interpolation to match new input image shapes', 'build a ViTAdapter backbone with deformable attention for multi-scale semantic segmentation', 'create a ViTAdapter instance with freeze_vit=True to freeze the base ViT weights', 'run the ViTAdapter forward pass on an image tensor to get multi-scale feature maps', 'review the ViTAdapter interaction_indexes parameter to configure which ViT blocks interact with conv features', 'test the ViTAdapter with use_cls=True to include class tokens in the interaction blocks']
```

Usage

```
{'build_drop_path_layer': 'build a PyTorch module that applies stochastic depth drop path regularization to tensor inputs', 'create_drop_path_function': 'create a function that randomly drops entire sample paths with configurable drop probability during training', 'test_DropPath_class': 'test the DropPath nn.Module class by passing tensors through it with various drop probabilities', 'review_drop_path_implementation': 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth', 'refactor_DropPath_for_custom_dims': 'refactor the DropPath class to support custom tensor dimensions beyond standard 2D ConvNets'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/models/backbones/vit.py

Prompts

```
['build a SpatialPriorModule to extract multi-scale CNN features from an input image tensor', 'create an InteractionBlock that injects image features into tokens and extracts updated context features', 'create an InteractionBlockWithCls that processes tokens with a cls token alongside image feature injection', 'build an Extractor module with MSDeformAttn and ConvFFN to extract features from multi-scale spatial inputs', 'build an Injector module with MSDeformAttn to inject multi-scale image features into query tokens', 'build a PyTorch module that applies stochastic depth drop path regularization to tensor inputs', 'create a function that randomly drops entire sample paths with configurable drop probability during training', 'test the DropPath nn.Module class by passing tensors through it with various drop probabilities', 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth', 'refactor the DropPath class to support custom tensor dimensions beyond standard 2D ConvNets', 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build an Mlp feed-forward layer with configurable hidden dimension, activation, and dropout for transformer blocks', 'create a SwiGLUFFN gated feed-forward network layer with SiLU activation and 8-byte alignment', 'resize position embeddings using bicubic interpolation to match new input image shapes', 'build a ViTAdapter backbone with deformable attention for multi-scale semantic segmentation', 'create a ViTAdapter instance with freeze_vit=True to freeze the base ViT weights', 'run the ViTAdapter forward pass on an image tensor to get multi-scale feature maps', 'review the ViTAdapter interaction_indexes parameter to configure which ViT blocks interact with conv features', 'test the ViTAdapter with use_cls=True to include class tokens in the interaction blocks']
```

Usage

```
{'build_vit_backbone': 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create_patch_embed': 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build_mlp_layer': 'build an Mlp feed-forward layer with configurable hidden dimension, activation, and dropout for transformer blocks', 'create_swiglu_ffn': 'create a SwiGLUFFN gated feed-forward network layer with SiLU activation and 8-byte alignment', 'resize_pos_embed': 'resize position embeddings using bicubic interpolation to match new input image shapes'}
```

## File: facebookresearch_dinov2/dinov2/eval/segmentation_m2f/models/backbones/vit_adapter.py

Prompts

```
['build a SpatialPriorModule to extract multi-scale CNN features from an input image tensor', 'create an InteractionBlock that injects image features into tokens and extracts updated context features', 'create an InteractionBlockWithCls that processes tokens with a cls token alongside image feature injection', 'build an Extractor module with MSDeformAttn and ConvFFN to extract features from multi-scale spatial inputs', 'build an Injector module with MSDeformAttn to inject multi-scale image features into query tokens', 'build a PyTorch module that applies stochastic depth drop path regularization to tensor inputs', 'create a function that randomly drops entire sample paths with configurable drop probability during training', 'test the DropPath nn.Module class by passing tensors through it with various drop probabilities', 'review the drop_path function to understand how it uses Bernoulli sampling for stochastic depth', 'refactor the DropPath class to support custom tensor dimensions beyond standard 2D ConvNets', 'build a TIMMVisionTransformer backbone with configurable depth, heads, and windowed attention for segmentation', 'create a PatchEmbed module to convert 2D images into flattened patch embeddings with normalization', 'build an Mlp feed-forward layer with configurable hidden dimension, activation, and dropout for transformer blocks', 'create a SwiGLUFFN gated feed-forward network layer with SiLU activation and 8-byte alignment', 'resize position embeddings using bicubic interpolation to match new input image shapes', 'build a ViTAdapter backbone with deformable attention for multi-scale semantic segmentation', 'create a ViTAdapter instance with freeze_vit=True to freeze the base ViT weights', 'run the ViTAdapter forward pass on an image tensor to get multi-scale feature maps', 'review the ViTAdapter interaction_indexes parameter to configure which ViT blocks interact with conv features', 'test the ViTAdapter with use_cls=True to include class tokens in the interaction blocks']
```

Usage

```
{'build_vit_adapter_backbone': 'build a ViTAdapter backbone with deformable attention for multi-scale semantic segmentation', 'create_vit_adapter_with_frozen_vit': 'create a ViTAdapter instance with freeze_vit=True to freeze the base ViT weights', 'run_vit_adapter_forward': 'run the ViTAdapter forward pass on an image tensor to get multi-scale feature maps', 'review_interaction_indexes_config': 'review the ViTAdapter interaction_indexes parameter to configure which ViT blocks interact with conv features', 'test_vit_adapter_cls_token': 'test the ViTAdapter with use_cls=True to include class tokens in the interaction blocks'}
```


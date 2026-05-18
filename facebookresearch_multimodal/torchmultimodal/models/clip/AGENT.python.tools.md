# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/models/clip/image_encoder.py

Prompts

```
['build a CLIP ViT encoder with configurable patch size, width, heads, and layers for image encoding', 'build a modified ResNet for CLIP with attention pooling and anti-aliasing strided convolutions', 'build a 2D attention pooling layer with QKV projections for spatial feature aggregation', 'build a ResNet bottleneck block with avgpool downsampling for CLIP ResNet stages', 'review the CLIP ViT encoder forward pass that patches images and extracts the CLS token embedding', 'build a CLIP model with custom encoder_a and encoder_b modules for contrastive pretraining', 'create a ViT-B/16 CLIP model with pretrained weights for image-text embeddings', 'create a ViT-L/14 CLIP model with pretrained weights for image-text embeddings', 'create a ResNet-50 CLIP model with pretrained weights for image-text embeddings', 'run the CLIP forward pass with image and text tensors to get normalized embeddings', 'build a CLIP text encoder with configurable embedding dimension, context length, and transformer heads', 'create a forward pass through CLIPTextEncoder to encode text tokens into projected embeddings', 'test the CLIPTextEncoder initialize_parameters method to verify token and positional embedding initialization', 'review the CLIPTextEncoder build_attention_mask method that generates a causal attention mask tensor', 'refactor the CLIPTextEncoder forward method to return the full hidden state instead of projected embeddings']
```

Usage

```
{'build_CLIPViTEncoder': 'build a CLIP ViT encoder with configurable patch size, width, heads, and layers for image encoding', 'build_ResNetForCLIP': 'build a modified ResNet for CLIP with attention pooling and anti-aliasing strided convolutions', 'build_AttentionPool2d': 'build a 2D attention pooling layer with QKV projections for spatial feature aggregation', 'build_ResNetForCLIPBottleneck': 'build a ResNet bottleneck block with avgpool downsampling for CLIP ResNet stages', 'review_CLIPViTEncoder_forward': 'review the CLIP ViT encoder forward pass that patches images and extracts the CLS token embedding'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/clip/model.py

Prompts

```
['build a CLIP ViT encoder with configurable patch size, width, heads, and layers for image encoding', 'build a modified ResNet for CLIP with attention pooling and anti-aliasing strided convolutions', 'build a 2D attention pooling layer with QKV projections for spatial feature aggregation', 'build a ResNet bottleneck block with avgpool downsampling for CLIP ResNet stages', 'review the CLIP ViT encoder forward pass that patches images and extracts the CLS token embedding', 'build a CLIP model with custom encoder_a and encoder_b modules for contrastive pretraining', 'create a ViT-B/16 CLIP model with pretrained weights for image-text embeddings', 'create a ViT-L/14 CLIP model with pretrained weights for image-text embeddings', 'create a ResNet-50 CLIP model with pretrained weights for image-text embeddings', 'run the CLIP forward pass with image and text tensors to get normalized embeddings', 'build a CLIP text encoder with configurable embedding dimension, context length, and transformer heads', 'create a forward pass through CLIPTextEncoder to encode text tokens into projected embeddings', 'test the CLIPTextEncoder initialize_parameters method to verify token and positional embedding initialization', 'review the CLIPTextEncoder build_attention_mask method that generates a causal attention mask tensor', 'refactor the CLIPTextEncoder forward method to return the full hidden state instead of projected embeddings']
```

Usage

```
{'build_CLIP_model': 'build a CLIP model with custom encoder_a and encoder_b modules for contrastive pretraining', 'create_clip_vit_b16': 'create a ViT-B/16 CLIP model with pretrained weights for image-text embeddings', 'create_clip_vit_l14': 'create a ViT-L/14 CLIP model with pretrained weights for image-text embeddings', 'create_clip_rn50': 'create a ResNet-50 CLIP model with pretrained weights for image-text embeddings', 'run_CLIP_forward': 'run the CLIP forward pass with image and text tensors to get normalized embeddings'}
```

## File: facebookresearch_multimodal/torchmultimodal/models/clip/text_encoder.py

Prompts

```
['build a CLIP ViT encoder with configurable patch size, width, heads, and layers for image encoding', 'build a modified ResNet for CLIP with attention pooling and anti-aliasing strided convolutions', 'build a 2D attention pooling layer with QKV projections for spatial feature aggregation', 'build a ResNet bottleneck block with avgpool downsampling for CLIP ResNet stages', 'review the CLIP ViT encoder forward pass that patches images and extracts the CLS token embedding', 'build a CLIP model with custom encoder_a and encoder_b modules for contrastive pretraining', 'create a ViT-B/16 CLIP model with pretrained weights for image-text embeddings', 'create a ViT-L/14 CLIP model with pretrained weights for image-text embeddings', 'create a ResNet-50 CLIP model with pretrained weights for image-text embeddings', 'run the CLIP forward pass with image and text tensors to get normalized embeddings', 'build a CLIP text encoder with configurable embedding dimension, context length, and transformer heads', 'create a forward pass through CLIPTextEncoder to encode text tokens into projected embeddings', 'test the CLIPTextEncoder initialize_parameters method to verify token and positional embedding initialization', 'review the CLIPTextEncoder build_attention_mask method that generates a causal attention mask tensor', 'refactor the CLIPTextEncoder forward method to return the full hidden state instead of projected embeddings']
```

Usage

```
{'build_CLIPTextEncoder': 'build a CLIP text encoder with configurable embedding dimension, context length, and transformer heads', 'create_CLIPTextEncoder_forward': 'create a forward pass through CLIPTextEncoder to encode text tokens into projected embeddings', 'test_CLIPTextEncoder_initialize_parameters': 'test the CLIPTextEncoder initialize_parameters method to verify token and positional embedding initialization', 'review_CLIPTextEncoder_build_attention_mask': 'review the CLIPTextEncoder build_attention_mask method that generates a causal attention mask tensor', 'refactor_CLIPTextEncoder_forward_hidden_state': 'refactor the CLIPTextEncoder forward method to return the full hidden state instead of projected embeddings'}
```


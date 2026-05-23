# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/models/backbones/dinov3.py

Prompts

```
['build a Dinov3Backbone instance with a specified ViT model name and config object', 'encode an RGB image tensor through the Dinov3Backbone forward pass to get patch embeddings', 'get the layer-wise depth and total layer count for a given parameter name in the encoder', 'review the Dinov3Backbone forward method to understand how it extracts intermediate ViT layers', 'test the get_layer_depth method with various parameter names like cls_token, patch_embed, and blocks', 'build a ViT transformer backbone model with configurable depth, heads, and embed dimensions', 'build a ViT backbone model with Flash Attention enabled for faster training', 'create a ViT-B, ViT-L, or ViT-H variant using the vit_b, vit_l, or vit factory functions', 'freeze specific stages or attention and FFN modules in the ViT backbone for fine-tuning', 'compute and resize absolute positional embeddings for different input image resolutions']
```

Usage

```
{'build_dinov3_backbone': 'build a Dinov3Backbone instance with a specified ViT model name and config object', 'encode_image_with_dinov3': 'encode an RGB image tensor through the Dinov3Backbone forward pass to get patch embeddings', 'get_layer_depth_for_param': 'get the layer-wise depth and total layer count for a given parameter name in the encoder', 'review_dinov3_forward': 'review the Dinov3Backbone forward method to understand how it extracts intermediate ViT layers', 'test_get_layer_depth': 'test the get_layer_depth method with various parameter names like cls_token, patch_embed, and blocks'}
```

## File: facebookresearch_sam-3d-body/sam_3d_body/models/backbones/vit.py

Prompts

```
['build a Dinov3Backbone instance with a specified ViT model name and config object', 'encode an RGB image tensor through the Dinov3Backbone forward pass to get patch embeddings', 'get the layer-wise depth and total layer count for a given parameter name in the encoder', 'review the Dinov3Backbone forward method to understand how it extracts intermediate ViT layers', 'test the get_layer_depth method with various parameter names like cls_token, patch_embed, and blocks', 'build a ViT transformer backbone model with configurable depth, heads, and embed dimensions', 'build a ViT backbone model with Flash Attention enabled for faster training', 'create a ViT-B, ViT-L, or ViT-H variant using the vit_b, vit_l, or vit factory functions', 'freeze specific stages or attention and FFN modules in the ViT backbone for fine-tuning', 'compute and resize absolute positional embeddings for different input image resolutions']
```

Usage

```
{'build_ViT_backbone': 'build a ViT transformer backbone model with configurable depth, heads, and embed dimensions', 'build_ViT_with_flash_attn': 'build a ViT backbone model with Flash Attention enabled for faster training', 'create_vit_variant': 'create a ViT-B, ViT-L, or ViT-H variant using the vit_b, vit_l, or vit factory functions', 'freeze_ViT_stages': 'freeze specific stages or attention and FFN modules in the ViT backbone for fine-tuning', 'compute_absolute_pos_embed': 'compute and resize absolute positional embeddings for different input image resolutions'}
```


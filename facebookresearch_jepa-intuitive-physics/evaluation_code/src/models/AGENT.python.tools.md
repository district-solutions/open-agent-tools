# Agent Python Tools

- repo: facebookresearch/jepa-intuitive-physics
- repo_uri: https://github.com/facebookresearch/jepa-intuitive-physics

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/models/predictor.py

Prompts

```
['build a VisionTransformerPredictor model with configurable embed_dim, depth, and num_heads for masked prediction', 'create a ViT predictor model using vit_predictor factory with custom kwargs like embed_dim and depth', 'run forward pass on context and target tokens with mask indices through the predictor', 'review the diffusion method that applies noise scheduling and LayerNorm to target tokens', 'test mask token initialization with configurable num_mask_tokens and zero_init_mask_tokens settings', 'build a ViT-B vision transformer model with 768 embed dim and 12 layers', 'build a ViT-L vision transformer model with 1024 embed dim and 24 layers', 'build a ViT-H vision transformer model with 1280 embed dim and 32 layers', 'build a vision transformer model with rotary positional embeddings enabled', 'run a forward pass through the VisionTransformer with optional token masking']
```

Usage

```
{'build_VisionTransformerPredictor': 'build a VisionTransformerPredictor model with configurable embed_dim, depth, and num_heads for masked prediction', 'create_vit_predictor': 'create a ViT predictor model using vit_predictor factory with custom kwargs like embed_dim and depth', 'run_forward_prediction': 'run forward pass on context and target tokens with mask indices through the predictor', 'review_diffusion_noising': 'review the diffusion method that applies noise scheduling and LayerNorm to target tokens', 'test_mask_token_initialization': 'test mask token initialization with configurable num_mask_tokens and zero_init_mask_tokens settings'}
```

## File: facebookresearch_jepa-intuitive-physics/evaluation_code/src/models/vision_transformer.py

Prompts

```
['build a VisionTransformerPredictor model with configurable embed_dim, depth, and num_heads for masked prediction', 'create a ViT predictor model using vit_predictor factory with custom kwargs like embed_dim and depth', 'run forward pass on context and target tokens with mask indices through the predictor', 'review the diffusion method that applies noise scheduling and LayerNorm to target tokens', 'test mask token initialization with configurable num_mask_tokens and zero_init_mask_tokens settings', 'build a ViT-B vision transformer model with 768 embed dim and 12 layers', 'build a ViT-L vision transformer model with 1024 embed dim and 24 layers', 'build a ViT-H vision transformer model with 1280 embed dim and 32 layers', 'build a vision transformer model with rotary positional embeddings enabled', 'run a forward pass through the VisionTransformer with optional token masking']
```

Usage

```
{'build_vit_base_model': 'build a ViT-B vision transformer model with 768 embed dim and 12 layers', 'build_vit_large_model': 'build a ViT-L vision transformer model with 1024 embed dim and 24 layers', 'build_vit_huge_model': 'build a ViT-H vision transformer model with 1280 embed dim and 32 layers', 'build_vit_with_rope': 'build a vision transformer model with rotary positional embeddings enabled', 'run_vit_forward': 'run a forward pass through the VisionTransformer with optional token masking'}
```


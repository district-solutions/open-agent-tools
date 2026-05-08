# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/src/models/attentive_pooler.py

Prompts

```
['create an AttentivePooler module with learnable query tokens and cross-attention to pool sequence embeddings', 'create an AttentiveClassifier that pools sequence embeddings then classifies into num_classes categories', 'build an AttentivePooler with multiple self-attention blocks by setting depth greater than one', 'review the AttentivePooler cross-attention block configuration with configurable num_heads and mlp_ratio', 'test the AttentivePooler weight initialization using trunc_normal_ and rescaled block scaling', 'build a VisionTransformerPredictor model with configurable embed_dim, depth, and num_heads for masked image modeling', 'run the vit_predictor factory function to create a VisionTransformerPredictor with default LayerNorm and mlp_ratio settings', 'test the diffusion method to apply noise scheduling and normalize features on predictor target tokens', 'review the forward method that concatenates context and target tokens then predicts masked patches through attention blocks', 'refactor the _init_pos_embed method to support custom 2D or 3D sincos positional embeddings for image or video input', 'build a VisionTransformer model with custom embed_dim, depth, and num_heads for image or video input', 'run a forward pass through a VisionTransformer with optional patch token masks applied', 'create a vit_base VisionTransformer with 768 embed dim, 12 layers, and 12 attention heads', 'create a vit_large VisionTransformer with 1024 embed dim, 24 layers, and 16 attention heads', 'interpolate positional embeddings in a VisionTransformer to match different input image or video sizes']
```

Usage

```
{'create_attentive_pooler': 'create an AttentivePooler module with learnable query tokens and cross-attention to pool sequence embeddings', 'create_attentive_classifier': 'create an AttentiveClassifier that pools sequence embeddings then classifies into num_classes categories', 'build_pooler_with_depth': 'build an AttentivePooler with multiple self-attention blocks by setting depth greater than one', 'review_cross_attention_block': 'review the AttentivePooler cross-attention block configuration with configurable num_heads and mlp_ratio', 'test_init_weights': 'test the AttentivePooler weight initialization using trunc_normal_ and rescaled block scaling'}
```

## File: facebookresearch_jepa/src/models/predictor.py

Prompts

```
['create an AttentivePooler module with learnable query tokens and cross-attention to pool sequence embeddings', 'create an AttentiveClassifier that pools sequence embeddings then classifies into num_classes categories', 'build an AttentivePooler with multiple self-attention blocks by setting depth greater than one', 'review the AttentivePooler cross-attention block configuration with configurable num_heads and mlp_ratio', 'test the AttentivePooler weight initialization using trunc_normal_ and rescaled block scaling', 'build a VisionTransformerPredictor model with configurable embed_dim, depth, and num_heads for masked image modeling', 'run the vit_predictor factory function to create a VisionTransformerPredictor with default LayerNorm and mlp_ratio settings', 'test the diffusion method to apply noise scheduling and normalize features on predictor target tokens', 'review the forward method that concatenates context and target tokens then predicts masked patches through attention blocks', 'refactor the _init_pos_embed method to support custom 2D or 3D sincos positional embeddings for image or video input', 'build a VisionTransformer model with custom embed_dim, depth, and num_heads for image or video input', 'run a forward pass through a VisionTransformer with optional patch token masks applied', 'create a vit_base VisionTransformer with 768 embed dim, 12 layers, and 12 attention heads', 'create a vit_large VisionTransformer with 1024 embed dim, 24 layers, and 16 attention heads', 'interpolate positional embeddings in a VisionTransformer to match different input image or video sizes']
```

Usage

```
{'build_VisionTransformerPredictor': 'build a VisionTransformerPredictor model with configurable embed_dim, depth, and num_heads for masked image modeling', 'run_vit_predictor_factory': 'run the vit_predictor factory function to create a VisionTransformerPredictor with default LayerNorm and mlp_ratio settings', 'test_diffusion_noise': 'test the diffusion method to apply noise scheduling and normalize features on predictor target tokens', 'review_forward_masked_prediction': 'review the forward method that concatenates context and target tokens then predicts masked patches through attention blocks', 'refactor_init_pos_embed': 'refactor the _init_pos_embed method to support custom 2D or 3D sincos positional embeddings for image or video input'}
```

## File: facebookresearch_jepa/src/models/vision_transformer.py

Prompts

```
['create an AttentivePooler module with learnable query tokens and cross-attention to pool sequence embeddings', 'create an AttentiveClassifier that pools sequence embeddings then classifies into num_classes categories', 'build an AttentivePooler with multiple self-attention blocks by setting depth greater than one', 'review the AttentivePooler cross-attention block configuration with configurable num_heads and mlp_ratio', 'test the AttentivePooler weight initialization using trunc_normal_ and rescaled block scaling', 'build a VisionTransformerPredictor model with configurable embed_dim, depth, and num_heads for masked image modeling', 'run the vit_predictor factory function to create a VisionTransformerPredictor with default LayerNorm and mlp_ratio settings', 'test the diffusion method to apply noise scheduling and normalize features on predictor target tokens', 'review the forward method that concatenates context and target tokens then predicts masked patches through attention blocks', 'refactor the _init_pos_embed method to support custom 2D or 3D sincos positional embeddings for image or video input', 'build a VisionTransformer model with custom embed_dim, depth, and num_heads for image or video input', 'run a forward pass through a VisionTransformer with optional patch token masks applied', 'create a vit_base VisionTransformer with 768 embed dim, 12 layers, and 12 attention heads', 'create a vit_large VisionTransformer with 1024 embed dim, 24 layers, and 16 attention heads', 'interpolate positional embeddings in a VisionTransformer to match different input image or video sizes']
```

Usage

```
{'build_vision_transformer': 'build a VisionTransformer model with custom embed_dim, depth, and num_heads for image or video input', 'run_vit_forward_pass': 'run a forward pass through a VisionTransformer with optional patch token masks applied', 'create_vit_base_model': 'create a vit_base VisionTransformer with 768 embed dim, 12 layers, and 12 attention heads', 'create_vit_large_model': 'create a vit_large VisionTransformer with 1024 embed dim, 24 layers, and 16 attention heads', 'interpolate_pos_encoding': 'interpolate positional embeddings in a VisionTransformer to match different input image or video sizes'}
```


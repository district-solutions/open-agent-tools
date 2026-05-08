# Agent Python Tools

- repo: facebookresearch/r-mae
- repo_uri: https://github.com/facebookresearch/r-mae

## File: facebookresearch_r-mae/pretrain/module/layers.py

Prompts

```
['build a PatchEmbed module to convert 2D images into flattened patch embeddings for a vision transformer', 'create a multi-head self-attention layer with optional relative position bias and attention masking support', 'create a transformer encoder block with self-attention, MLP, layer norm, and stochastic depth drop path', 'create a transformer decoder block with self-attention, cross-attention to encoder memory, and MLP feed-forward', 'create a decoder block that expands decoder tokens with projected encoder memory via additive expansion', 'build a MaskedAutoencoderViT model using build_mae with a config dict specifying arch and params', 'run the forward_encoder method on image tensors with a specified mask ratio for masked patch encoding', 'run the forward_decoder method to reconstruct masked patches from encoder latent representations', 'test the random_masking method to verify per-sample patch masking with configurable mask ratio', 'review the forward_loss method that computes normalized pixel-wise MAE loss on masked patches', 'build a RegionQueryRMAE model from an omegaconf config with rmae_base_patch16 or rmae_large_patch16 arch', 'create a RegionMaskedAutoencoderViT with custom mask ratio, region loss weight, and region sample type', 'run per-sample random masking on a sequence tensor with optional region-aware masking and shuffle ids', 'forward pass the region decoder to predict region patches from region latent and memory cross-attention', 'compute combined MAE and region binary cross-entropy loss with configurable loss weights and mask weighting']
```

Usage

```
{'build_PatchEmbed': 'build a PatchEmbed module to convert 2D images into flattened patch embeddings for a vision transformer', 'create_Attention': 'create a multi-head self-attention layer with optional relative position bias and attention masking support', 'create_Block': 'create a transformer encoder block with self-attention, MLP, layer norm, and stochastic depth drop path', 'create_DecoderBlock': 'create a transformer decoder block with self-attention, cross-attention to encoder memory, and MLP feed-forward', 'create_DecoderBlockWithExpansion': 'create a decoder block that expands decoder tokens with projected encoder memory via additive expansion'}
```

## File: facebookresearch_r-mae/pretrain/module/mae.py

Prompts

```
['build a PatchEmbed module to convert 2D images into flattened patch embeddings for a vision transformer', 'create a multi-head self-attention layer with optional relative position bias and attention masking support', 'create a transformer encoder block with self-attention, MLP, layer norm, and stochastic depth drop path', 'create a transformer decoder block with self-attention, cross-attention to encoder memory, and MLP feed-forward', 'create a decoder block that expands decoder tokens with projected encoder memory via additive expansion', 'build a MaskedAutoencoderViT model using build_mae with a config dict specifying arch and params', 'run the forward_encoder method on image tensors with a specified mask ratio for masked patch encoding', 'run the forward_decoder method to reconstruct masked patches from encoder latent representations', 'test the random_masking method to verify per-sample patch masking with configurable mask ratio', 'review the forward_loss method that computes normalized pixel-wise MAE loss on masked patches', 'build a RegionQueryRMAE model from an omegaconf config with rmae_base_patch16 or rmae_large_patch16 arch', 'create a RegionMaskedAutoencoderViT with custom mask ratio, region loss weight, and region sample type', 'run per-sample random masking on a sequence tensor with optional region-aware masking and shuffle ids', 'forward pass the region decoder to predict region patches from region latent and memory cross-attention', 'compute combined MAE and region binary cross-entropy loss with configurable loss weights and mask weighting']
```

Usage

```
{'build_mae_model': 'build a MaskedAutoencoderViT model using build_mae with a config dict specifying arch and params', 'run_forward_encoder': 'run the forward_encoder method on image tensors with a specified mask ratio for masked patch encoding', 'run_forward_decoder': 'run the forward_decoder method to reconstruct masked patches from encoder latent representations', 'test_random_masking': 'test the random_masking method to verify per-sample patch masking with configurable mask ratio', 'review_forward_loss': 'review the forward_loss method that computes normalized pixel-wise MAE loss on masked patches'}
```

## File: facebookresearch_r-mae/pretrain/module/rmae.py

Prompts

```
['build a PatchEmbed module to convert 2D images into flattened patch embeddings for a vision transformer', 'create a multi-head self-attention layer with optional relative position bias and attention masking support', 'create a transformer encoder block with self-attention, MLP, layer norm, and stochastic depth drop path', 'create a transformer decoder block with self-attention, cross-attention to encoder memory, and MLP feed-forward', 'create a decoder block that expands decoder tokens with projected encoder memory via additive expansion', 'build a MaskedAutoencoderViT model using build_mae with a config dict specifying arch and params', 'run the forward_encoder method on image tensors with a specified mask ratio for masked patch encoding', 'run the forward_decoder method to reconstruct masked patches from encoder latent representations', 'test the random_masking method to verify per-sample patch masking with configurable mask ratio', 'review the forward_loss method that computes normalized pixel-wise MAE loss on masked patches', 'build a RegionQueryRMAE model from an omegaconf config with rmae_base_patch16 or rmae_large_patch16 arch', 'create a RegionMaskedAutoencoderViT with custom mask ratio, region loss weight, and region sample type', 'run per-sample random masking on a sequence tensor with optional region-aware masking and shuffle ids', 'forward pass the region decoder to predict region patches from region latent and memory cross-attention', 'compute combined MAE and region binary cross-entropy loss with configurable loss weights and mask weighting']
```

Usage

```
{'build_rmae_model': 'build a RegionQueryRMAE model from an omegaconf config with rmae_base_patch16 or rmae_large_patch16 arch', 'create_region_masked_autoencoder': 'create a RegionMaskedAutoencoderViT with custom mask ratio, region loss weight, and region sample type', 'run_random_masking': 'run per-sample random masking on a sequence tensor with optional region-aware masking and shuffle ids', 'forward_region_decoder': 'forward pass the region decoder to predict region patches from region latent and memory cross-attention', 'forward_loss': 'compute combined MAE and region binary cross-entropy loss with configurable loss weights and mask weighting'}
```


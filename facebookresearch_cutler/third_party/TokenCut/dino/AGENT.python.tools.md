# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/third_party/TokenCut/dino/utils.py

Prompts

```
['load pretrained DINO weights from a local checkpoint file or remote URL into a PyTorch model', 'load pretrained linear classifier weights for a DINO model from a remote URL by model name', 'build a cosine annealing schedule with optional warmup for learning rate or weight decay over training epochs', 'create a GaussianBlur augmentation callable that randomly applies Gaussian blur to a PIL image with configurable probability', 'create a Solarization augmentation callable that randomly applies solarization to a PIL image with configurable probability', 'build a ViT-B/16 VisionTransformer model with 768 embed dim and 12 transformer blocks', 'build a DINOHead MLP projection head with bottleneck dimension for self-supervised learning', 'get the last layer self-attention weights from a VisionTransformer given an input image tensor', 'get intermediate feature representations from the last N blocks of a VisionTransformer model', 'build a DropPath stochastic depth module to randomly drop residual paths during training']
```

Usage

```
{'load_pretrained_weights': 'load pretrained DINO weights from a local checkpoint file or remote URL into a PyTorch model', 'load_pretrained_linear_weights': 'load pretrained linear classifier weights for a DINO model from a remote URL by model name', 'cosine_scheduler': 'build a cosine annealing schedule with optional warmup for learning rate or weight decay over training epochs', 'GaussianBlur': 'create a GaussianBlur augmentation callable that randomly applies Gaussian blur to a PIL image with configurable probability', 'Solarization': 'create a Solarization augmentation callable that randomly applies solarization to a PIL image with configurable probability'}
```

## File: facebookresearch_cutler/third_party/TokenCut/dino/vision_transformer.py

Prompts

```
['load pretrained DINO weights from a local checkpoint file or remote URL into a PyTorch model', 'load pretrained linear classifier weights for a DINO model from a remote URL by model name', 'build a cosine annealing schedule with optional warmup for learning rate or weight decay over training epochs', 'create a GaussianBlur augmentation callable that randomly applies Gaussian blur to a PIL image with configurable probability', 'create a Solarization augmentation callable that randomly applies solarization to a PIL image with configurable probability', 'build a ViT-B/16 VisionTransformer model with 768 embed dim and 12 transformer blocks', 'build a DINOHead MLP projection head with bottleneck dimension for self-supervised learning', 'get the last layer self-attention weights from a VisionTransformer given an input image tensor', 'get intermediate feature representations from the last N blocks of a VisionTransformer model', 'build a DropPath stochastic depth module to randomly drop residual paths during training']
```

Usage

```
{'build_vit_base_model': 'build a ViT-B/16 VisionTransformer model with 768 embed dim and 12 transformer blocks', 'build_dino_head': 'build a DINOHead MLP projection head with bottleneck dimension for self-supervised learning', 'get_last_selfattention': 'get the last layer self-attention weights from a VisionTransformer given an input image tensor', 'get_intermediate_layers': 'get intermediate feature representations from the last N blocks of a VisionTransformer model', 'build_drop_path_module': 'build a DropPath stochastic depth module to randomly drop residual paths during training'}
```


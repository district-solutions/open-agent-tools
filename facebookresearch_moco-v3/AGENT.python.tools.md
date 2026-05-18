# Agent Python Tools

- repo: facebookresearch/moco-v3
- repo_uri: https://github.com/facebookresearch/moco-v3

## File: facebookresearch_moco-v3/main_lincls.py

Prompts

```
['run linear classification training on ImageNet using a MoCo pretrained checkpoint with cosine LR decay', 'evaluate a MoCo pretrained model on the ImageNet validation set with frozen backbone weights', 'run distributed multi-GPU linear classification training using PyTorch DDP with NCCL backend', 'resume linear classifier training from a saved checkpoint file and continue from the last epoch', 'run a sanity check to verify frozen backbone weights were not modified during linear classifier training', 'run MoCo self-supervised pre-training on ImageNet with distributed data parallel across multiple GPUs', 'run MoCo pre-training using ViT architecture with configurable stop-grad on first conv layer', 'resume MoCo training from a saved checkpoint file with optimizer and scaler state', 'adjust the optimizer learning rate using a warmup then half-cycle cosine decay schedule', 'adjust the MoCo momentum encoder update coefficient with a half-cycle cosine schedule', 'build a ViT-Small MoCo model with 384-dim embeddings and 12 transformer blocks', 'build a ViT-Base MoCo model with 768-dim embeddings and 12 transformer blocks', 'build a ViT-Small model using ConvStem embedding layer instead of patch embedding', 'build a ViT-Base model using ConvStem embedding layer instead of patch embedding', 'review the VisionTransformerMoCo class and its 2D sin-cos position embedding initialization']
```

Usage

```
{'run_linear_classification_training': 'run linear classification training on ImageNet using a MoCo pretrained checkpoint with cosine LR decay', 'evaluate_pretrained_model': 'evaluate a MoCo pretrained model on the ImageNet validation set with frozen backbone weights', 'run_distributed_training': 'run distributed multi-GPU linear classification training using PyTorch DDP with NCCL backend', 'resume_checkpoint_training': 'resume linear classifier training from a saved checkpoint file and continue from the last epoch', 'run_sanity_check': 'run a sanity check to verify frozen backbone weights were not modified during linear classifier training'}
```

## File: facebookresearch_moco-v3/main_moco.py

Prompts

```
['run linear classification training on ImageNet using a MoCo pretrained checkpoint with cosine LR decay', 'evaluate a MoCo pretrained model on the ImageNet validation set with frozen backbone weights', 'run distributed multi-GPU linear classification training using PyTorch DDP with NCCL backend', 'resume linear classifier training from a saved checkpoint file and continue from the last epoch', 'run a sanity check to verify frozen backbone weights were not modified during linear classifier training', 'run MoCo self-supervised pre-training on ImageNet with distributed data parallel across multiple GPUs', 'run MoCo pre-training using ViT architecture with configurable stop-grad on first conv layer', 'resume MoCo training from a saved checkpoint file with optimizer and scaler state', 'adjust the optimizer learning rate using a warmup then half-cycle cosine decay schedule', 'adjust the MoCo momentum encoder update coefficient with a half-cycle cosine schedule', 'build a ViT-Small MoCo model with 384-dim embeddings and 12 transformer blocks', 'build a ViT-Base MoCo model with 768-dim embeddings and 12 transformer blocks', 'build a ViT-Small model using ConvStem embedding layer instead of patch embedding', 'build a ViT-Base model using ConvStem embedding layer instead of patch embedding', 'review the VisionTransformerMoCo class and its 2D sin-cos position embedding initialization']
```

Usage

```
{'run_moco_pretraining': 'run MoCo self-supervised pre-training on ImageNet with distributed data parallel across multiple GPUs', 'run_moco_vit_pretraining': 'run MoCo pre-training using ViT architecture with configurable stop-grad on first conv layer', 'resume_moco_checkpoint': 'resume MoCo training from a saved checkpoint file with optimizer and scaler state', 'adjust_learning_rate_cosine': 'adjust the optimizer learning rate using a warmup then half-cycle cosine decay schedule', 'adjust_moco_momentum_cosine': 'adjust the MoCo momentum encoder update coefficient with a half-cycle cosine schedule'}
```

## File: facebookresearch_moco-v3/vits.py

Prompts

```
['run linear classification training on ImageNet using a MoCo pretrained checkpoint with cosine LR decay', 'evaluate a MoCo pretrained model on the ImageNet validation set with frozen backbone weights', 'run distributed multi-GPU linear classification training using PyTorch DDP with NCCL backend', 'resume linear classifier training from a saved checkpoint file and continue from the last epoch', 'run a sanity check to verify frozen backbone weights were not modified during linear classifier training', 'run MoCo self-supervised pre-training on ImageNet with distributed data parallel across multiple GPUs', 'run MoCo pre-training using ViT architecture with configurable stop-grad on first conv layer', 'resume MoCo training from a saved checkpoint file with optimizer and scaler state', 'adjust the optimizer learning rate using a warmup then half-cycle cosine decay schedule', 'adjust the MoCo momentum encoder update coefficient with a half-cycle cosine schedule', 'build a ViT-Small MoCo model with 384-dim embeddings and 12 transformer blocks', 'build a ViT-Base MoCo model with 768-dim embeddings and 12 transformer blocks', 'build a ViT-Small model using ConvStem embedding layer instead of patch embedding', 'build a ViT-Base model using ConvStem embedding layer instead of patch embedding', 'review the VisionTransformerMoCo class and its 2D sin-cos position embedding initialization']
```

Usage

```
{'build_vit_small_model': 'build a ViT-Small MoCo model with 384-dim embeddings and 12 transformer blocks', 'build_vit_base_model': 'build a ViT-Base MoCo model with 768-dim embeddings and 12 transformer blocks', 'build_vit_conv_small_model': 'build a ViT-Small model using ConvStem embedding layer instead of patch embedding', 'build_vit_conv_base_model': 'build a ViT-Base model using ConvStem embedding layer instead of patch embedding', 'review_VisionTransformerMoCo_class': 'review the VisionTransformerMoCo class and its 2D sin-cos position embedding initialization'}
```


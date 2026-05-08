# Agent Python Tools

- repo: facebookresearch/ijepa
- repo_uri: https://github.com/facebookresearch/ijepa

## File: facebookresearch_ijepa/src/helper.py

Prompts

```
['init a ViT encoder and predictor model with configurable patch size, crop size, and embedding dimensions', 'init an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for encoder and predictor', 'load a checkpoint file to restore encoder, predictor, target encoder, optimizer, and scaler state', 'review the load_checkpoint function exception handling that logs errors and resets epoch to zero', 'refactor the init_model weight initialization to use a different truncation normal standard deviation', 'run the iJEPa model training loop with distributed data parallel on ImageNet-1K', 'build a masked image training pipeline using multi-block mask collator and context-target masking', 'create a checkpoint saving function that stores encoder, predictor, target encoder, and optimizer state', 'refactor the momentum scheduler to update target encoder weights with exponential moving average', 'review the distributed training setup with DDP wrapping and SLURM-based device visibility', 'create a composed image transform pipeline with random crop, flip, color jitter, and normalization', 'build a GaussianBlur transform class that applies random-radius blur to PIL images with configurable probability', 'create a color distortion transform using ColorJitter and RandomGrayscale with configurable strength', 'test the make_transforms function by applying it to a PIL image and verifying tensor output shape', 'review the GaussianBlur class __call__ method to understand how it applies probabilistic blur with random radius']
```

Usage

```
{'init_model_ViT_encoder_predictor': 'init a ViT encoder and predictor model with configurable patch size, crop size, and embedding dimensions', 'init_opt_AdamW_schedulers': 'init an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for encoder and predictor', 'load_checkpoint_resume_training': 'load a checkpoint file to restore encoder, predictor, target encoder, optimizer, and scaler state', 'review_load_checkpoint_error_handling': 'review the load_checkpoint function exception handling that logs errors and resets epoch to zero', 'refactor_init_model_weight_initialization': 'refactor the init_model weight initialization to use a different truncation normal standard deviation'}
```

## File: facebookresearch_ijepa/src/train.py

Prompts

```
['init a ViT encoder and predictor model with configurable patch size, crop size, and embedding dimensions', 'init an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for encoder and predictor', 'load a checkpoint file to restore encoder, predictor, target encoder, optimizer, and scaler state', 'review the load_checkpoint function exception handling that logs errors and resets epoch to zero', 'refactor the init_model weight initialization to use a different truncation normal standard deviation', 'run the iJEPa model training loop with distributed data parallel on ImageNet-1K', 'build a masked image training pipeline using multi-block mask collator and context-target masking', 'create a checkpoint saving function that stores encoder, predictor, target encoder, and optimizer state', 'refactor the momentum scheduler to update target encoder weights with exponential moving average', 'review the distributed training setup with DDP wrapping and SLURM-based device visibility', 'create a composed image transform pipeline with random crop, flip, color jitter, and normalization', 'build a GaussianBlur transform class that applies random-radius blur to PIL images with configurable probability', 'create a color distortion transform using ColorJitter and RandomGrayscale with configurable strength', 'test the make_transforms function by applying it to a PIL image and verifying tensor output shape', 'review the GaussianBlur class __call__ method to understand how it applies probabilistic blur with random radius']
```

Usage

```
{'run_iJEPa_training': 'run the iJEPa model training loop with distributed data parallel on ImageNet-1K', 'build_masked_training_pipeline': 'build a masked image training pipeline using multi-block mask collator and context-target masking', 'create_checkpoint_saving': 'create a checkpoint saving function that stores encoder, predictor, target encoder, and optimizer state', 'refactor_momentum_scheduler': 'refactor the momentum scheduler to update target encoder weights with exponential moving average', 'review_distributed_training_setup': 'review the distributed training setup with DDP wrapping and SLURM-based device visibility'}
```

## File: facebookresearch_ijepa/src/transforms.py

Prompts

```
['init a ViT encoder and predictor model with configurable patch size, crop size, and embedding dimensions', 'init an AdamW optimizer with warmup cosine LR schedule and cosine weight decay schedule for encoder and predictor', 'load a checkpoint file to restore encoder, predictor, target encoder, optimizer, and scaler state', 'review the load_checkpoint function exception handling that logs errors and resets epoch to zero', 'refactor the init_model weight initialization to use a different truncation normal standard deviation', 'run the iJEPa model training loop with distributed data parallel on ImageNet-1K', 'build a masked image training pipeline using multi-block mask collator and context-target masking', 'create a checkpoint saving function that stores encoder, predictor, target encoder, and optimizer state', 'refactor the momentum scheduler to update target encoder weights with exponential moving average', 'review the distributed training setup with DDP wrapping and SLURM-based device visibility', 'create a composed image transform pipeline with random crop, flip, color jitter, and normalization', 'build a GaussianBlur transform class that applies random-radius blur to PIL images with configurable probability', 'create a color distortion transform using ColorJitter and RandomGrayscale with configurable strength', 'test the make_transforms function by applying it to a PIL image and verifying tensor output shape', 'review the GaussianBlur class __call__ method to understand how it applies probabilistic blur with random radius']
```

Usage

```
{'create_transforms_for_augmentation': 'create a composed image transform pipeline with random crop, flip, color jitter, and normalization', 'build_gaussian_blur_transform': 'build a GaussianBlur transform class that applies random-radius blur to PIL images with configurable probability', 'create_color_distortion_pipeline': 'create a color distortion transform using ColorJitter and RandomGrayscale with configurable strength', 'test_make_transforms': 'test the make_transforms function by applying it to a PIL image and verifying tensor output shape', 'review_gaussian_blur_call': 'review the GaussianBlur class __call__ method to understand how it applies probabilistic blur with random radius'}
```


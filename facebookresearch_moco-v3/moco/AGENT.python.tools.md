# Agent Python Tools

- repo: facebookresearch/moco-v3
- repo_uri: https://github.com/facebookresearch/moco-v3

## File: facebookresearch_moco-v3/moco/builder.py

Prompts

```
['build a MoCo ResNet model with a base encoder, momentum encoder, and projector MLPs', 'build a MoCo Vision Transformer model with 3-layer projectors and 2-layer predictor MLPs', 'run the MoCo forward pass with two image views and a momentum coefficient to get contrastive loss', 'test the MoCo contrastive loss function that normalizes features and computes cross-entropy with gathered targets', 'review the concat_all_gather utility that performs distributed all_gather and concatenates tensors across GPUs', 'create a LARS optimizer instance with custom learning rate, weight decay, momentum, and trust coefficient', 'run a single optimization step using the LARS optimizer to update model parameters with adaptive local learning rates', 'review the LARS optimizer trust coefficient logic that scales updates based on parameter and gradient norms', 'refactor the LARS optimizer to apply weight decay only to parameters with more than one dimension', 'summarize the LARS optimizer momentum buffer initialization and update mechanism for parameter state tracking']
```

Usage

```
{'build_moco_resnet_model': 'build a MoCo ResNet model with a base encoder, momentum encoder, and projector MLPs', 'build_moco_vit_model': 'build a MoCo Vision Transformer model with 3-layer projectors and 2-layer predictor MLPs', 'run_moco_forward_pass': 'run the MoCo forward pass with two image views and a momentum coefficient to get contrastive loss', 'test_contrastive_loss': 'test the MoCo contrastive loss function that normalizes features and computes cross-entropy with gathered targets', 'review_concat_all_gather': 'review the concat_all_gather utility that performs distributed all_gather and concatenates tensors across GPUs'}
```

## File: facebookresearch_moco-v3/moco/optimizer.py

Prompts

```
['build a MoCo ResNet model with a base encoder, momentum encoder, and projector MLPs', 'build a MoCo Vision Transformer model with 3-layer projectors and 2-layer predictor MLPs', 'run the MoCo forward pass with two image views and a momentum coefficient to get contrastive loss', 'test the MoCo contrastive loss function that normalizes features and computes cross-entropy with gathered targets', 'review the concat_all_gather utility that performs distributed all_gather and concatenates tensors across GPUs', 'create a LARS optimizer instance with custom learning rate, weight decay, momentum, and trust coefficient', 'run a single optimization step using the LARS optimizer to update model parameters with adaptive local learning rates', 'review the LARS optimizer trust coefficient logic that scales updates based on parameter and gradient norms', 'refactor the LARS optimizer to apply weight decay only to parameters with more than one dimension', 'summarize the LARS optimizer momentum buffer initialization and update mechanism for parameter state tracking']
```

Usage

```
{'create_LARS_optimizer': 'create a LARS optimizer instance with custom learning rate, weight decay, momentum, and trust coefficient', 'run_LARS_step': 'run a single optimization step using the LARS optimizer to update model parameters with adaptive local learning rates', 'review_LARS_trust_coefficient': 'review the LARS optimizer trust coefficient logic that scales updates based on parameter and gradient norms', 'refactor_LARS_weight_decay': 'refactor the LARS optimizer to apply weight decay only to parameters with more than one dimension', 'summarize_LARS_momentum': 'summarize the LARS optimizer momentum buffer initialization and update mechanism for parameter state tracking'}
```


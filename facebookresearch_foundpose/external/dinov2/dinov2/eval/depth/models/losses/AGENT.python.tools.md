# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/depth/models/losses/gradientloss.py

Prompts

```
['build a GradientLoss module to compute multi-scale gradient loss between predicted and ground truth depth maps', 'create a GradientLoss instance with valid_mask filtering to ignore invalid ground truth depth values', 'test the gradientloss method by passing input and target tensors and verifying multi-scale gradient computation', 'refactor the GradientLoss class to add a max_depth threshold for filtering invalid ground truth values', 'review the GradientLoss forward method and how it applies loss_weight to the computed gradient loss', 'create a SigLoss instance with valid_mask and loss_weight for monocular depth estimation training', 'run the SigLoss forward pass with predicted and ground truth depth tensors to compute loss', 'test the SigLoss warmup stage by enabling warm_up and setting warm_iter to 100', 'review the SigLoss sigloss method that computes log-space variance and mean-based loss', 'refactor the SigLoss valid_mask logic to filter ground truth depth values beyond max_depth']
```

Usage

```
{'build_gradient_loss_module': 'build a GradientLoss module to compute multi-scale gradient loss between predicted and ground truth depth maps', 'create_gradient_loss_with_masking': 'create a GradientLoss instance with valid_mask filtering to ignore invalid ground truth depth values', 'test_gradientloss_method': 'test the gradientloss method by passing input and target tensors and verifying multi-scale gradient computation', 'refactor_gradient_loss_max_depth': 'refactor the GradientLoss class to add a max_depth threshold for filtering invalid ground truth values', 'review_gradient_loss_forward': 'review the GradientLoss forward method and how it applies loss_weight to the computed gradient loss'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/depth/models/losses/sigloss.py

Prompts

```
['build a GradientLoss module to compute multi-scale gradient loss between predicted and ground truth depth maps', 'create a GradientLoss instance with valid_mask filtering to ignore invalid ground truth depth values', 'test the gradientloss method by passing input and target tensors and verifying multi-scale gradient computation', 'refactor the GradientLoss class to add a max_depth threshold for filtering invalid ground truth values', 'review the GradientLoss forward method and how it applies loss_weight to the computed gradient loss', 'create a SigLoss instance with valid_mask and loss_weight for monocular depth estimation training', 'run the SigLoss forward pass with predicted and ground truth depth tensors to compute loss', 'test the SigLoss warmup stage by enabling warm_up and setting warm_iter to 100', 'review the SigLoss sigloss method that computes log-space variance and mean-based loss', 'refactor the SigLoss valid_mask logic to filter ground truth depth values beyond max_depth']
```

Usage

```
{'create_sigloss_for_depth_estimation': 'create a SigLoss instance with valid_mask and loss_weight for monocular depth estimation training', 'run_sigloss_forward': 'run the SigLoss forward pass with predicted and ground truth depth tensors to compute loss', 'test_sigloss_warmup': 'test the SigLoss warmup stage by enabling warm_up and setting warm_iter to 100', 'review_sigloss_sigloss_method': 'review the SigLoss sigloss method that computes log-space variance and mean-based loss', 'refactor_sigloss_max_depth_filtering': 'refactor the SigLoss valid_mask logic to filter ground truth depth values beyond max_depth'}
```


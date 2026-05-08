# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former/modeling/criterion.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth target masks for segmentation', 'compute the sigmoid cross entropy loss between predicted logits and binary target masks', 'calculate uncertainty scores from logit predictions using L1 distance from zero for point sampling', 'create a SetCriterion module to compute Hungarian assignment and loss for MaskFormer segmentation models', 'run the SetCriterion forward pass to compute classification and mask losses against ground truth targets', 'create a HungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for mask matching', 'run the HungarianMatcher forward pass to match predicted masks against ground truth targets', 'compute the batch dice loss between predicted and target mask tensors for segmentation matching', 'compute the batch sigmoid cross entropy loss between predicted and target mask tensors', 'review the memory efficient forward method that performs 1-to-1 matching using LSAP optimization']
```

Usage

```
{'compute_dice_loss': 'compute the DICE loss between predicted masks and ground truth target masks for segmentation', 'compute_sigmoid_ce_loss': 'compute the sigmoid cross entropy loss between predicted logits and binary target masks', 'calculate_uncertainty': 'calculate uncertainty scores from logit predictions using L1 distance from zero for point sampling', 'create_set_criterion': 'create a SetCriterion module to compute Hungarian assignment and loss for MaskFormer segmentation models', 'run_set_criterion_forward': 'run the SetCriterion forward pass to compute classification and mask losses against ground truth targets'}
```

## File: facebookresearch_mask2former/mask2former/modeling/matcher.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth target masks for segmentation', 'compute the sigmoid cross entropy loss between predicted logits and binary target masks', 'calculate uncertainty scores from logit predictions using L1 distance from zero for point sampling', 'create a SetCriterion module to compute Hungarian assignment and loss for MaskFormer segmentation models', 'run the SetCriterion forward pass to compute classification and mask losses against ground truth targets', 'create a HungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for mask matching', 'run the HungarianMatcher forward pass to match predicted masks against ground truth targets', 'compute the batch dice loss between predicted and target mask tensors for segmentation matching', 'compute the batch sigmoid cross entropy loss between predicted and target mask tensors', 'review the memory efficient forward method that performs 1-to-1 matching using LSAP optimization']
```

Usage

```
{'create_HungarianMatcher': 'create a HungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for mask matching', 'run_HungarianMatcher_forward': 'run the HungarianMatcher forward pass to match predicted masks against ground truth targets', 'compute_batch_dice_loss': 'compute the batch dice loss between predicted and target mask tensors for segmentation matching', 'compute_batch_sigmoid_ce_loss': 'compute the batch sigmoid cross entropy loss between predicted and target mask tensors', 'review_HungarianMatcher_memory_efficient_forward': 'review the memory efficient forward method that performs 1-to-1 matching using LSAP optimization'}
```


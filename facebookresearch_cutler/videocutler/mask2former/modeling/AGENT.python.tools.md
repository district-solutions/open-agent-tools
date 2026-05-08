# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former/modeling/criterion.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth target masks', 'compute the sigmoid cross entropy loss between predicted logits and binary target masks', 'calculate uncertainty scores from logit predictions using L1 distance from zero', 'create a SetCriterion module to compute Hungarian assignment and loss for MaskFormer models', 'run the SetCriterion forward pass to compute classification and mask losses for model outputs', 'build a HungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for mask matching', 'run the HungarianMatcher forward pass to match predicted masks against ground truth targets', 'create a batch dice loss computation between predicted and target mask tensors with a threshold', 'create a batch sigmoid cross-entropy loss computation between predicted and target mask tensors', 'review the memory efficient forward method that uses point sampling and LSAP for bipartite matching']
```

Usage

```
{'compute_dice_loss': 'compute the DICE loss between predicted masks and ground truth target masks', 'compute_sigmoid_ce_loss': 'compute the sigmoid cross entropy loss between predicted logits and binary target masks', 'calculate_uncertainty': 'calculate uncertainty scores from logit predictions using L1 distance from zero', 'create_setcriterion': 'create a SetCriterion module to compute Hungarian assignment and loss for MaskFormer models', 'run_setcriterion_forward': 'run the SetCriterion forward pass to compute classification and mask losses for model outputs'}
```

## File: facebookresearch_cutler/videocutler/mask2former/modeling/matcher.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth target masks', 'compute the sigmoid cross entropy loss between predicted logits and binary target masks', 'calculate uncertainty scores from logit predictions using L1 distance from zero', 'create a SetCriterion module to compute Hungarian assignment and loss for MaskFormer models', 'run the SetCriterion forward pass to compute classification and mask losses for model outputs', 'build a HungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for mask matching', 'run the HungarianMatcher forward pass to match predicted masks against ground truth targets', 'create a batch dice loss computation between predicted and target mask tensors with a threshold', 'create a batch sigmoid cross-entropy loss computation between predicted and target mask tensors', 'review the memory efficient forward method that uses point sampling and LSAP for bipartite matching']
```

Usage

```
{'build_HungarianMatcher': 'build a HungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for mask matching', 'run_HungarianMatcher_forward': 'run the HungarianMatcher forward pass to match predicted masks against ground truth targets', 'create_batch_dice_loss': 'create a batch dice loss computation between predicted and target mask tensors with a threshold', 'create_batch_sigmoid_ce_loss': 'create a batch sigmoid cross-entropy loss computation between predicted and target mask tensors', 'review_HungarianMatcher_memory_efficient_forward': 'review the memory efficient forward method that uses point sampling and LSAP for bipartite matching'}
```


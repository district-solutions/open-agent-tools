# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former_video/modeling/criterion.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth target masks', 'compute the sigmoid cross entropy loss between predicted logits and binary target masks', 'calculate uncertainty scores from logit predictions using L1 distance from zero', 'create a VideoSetCriterion module to compute classification and mask losses for video segmentation', 'compute all requested losses including auxiliary losses for video mask prediction outputs', 'build a VideoHungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for bipartite matching', 'run the VideoHungarianMatcher forward pass to match predicted masks and logits against ground truth targets', 'create a batch dice loss computation between predicted and target mask tensors for segmentation matching', 'create a batch sigmoid cross-entropy loss between predicted and target mask tensors for cost computation', 'review the memory efficient forward method that uses point sampling and linear sum assignment for matching']
```

Usage

```
{'compute_dice_loss': 'compute the DICE loss between predicted masks and ground truth target masks', 'compute_sigmoid_ce_loss': 'compute the sigmoid cross entropy loss between predicted logits and binary target masks', 'calculate_uncertainty': 'calculate uncertainty scores from logit predictions using L1 distance from zero', 'create_video_set_criterion': 'create a VideoSetCriterion module to compute classification and mask losses for video segmentation', 'compute_video_segmentation_losses': 'compute all requested losses including auxiliary losses for video mask prediction outputs'}
```

## File: facebookresearch_mask2former/mask2former_video/modeling/matcher.py

Prompts

```
['compute the DICE loss between predicted masks and ground truth target masks', 'compute the sigmoid cross entropy loss between predicted logits and binary target masks', 'calculate uncertainty scores from logit predictions using L1 distance from zero', 'create a VideoSetCriterion module to compute classification and mask losses for video segmentation', 'compute all requested losses including auxiliary losses for video mask prediction outputs', 'build a VideoHungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for bipartite matching', 'run the VideoHungarianMatcher forward pass to match predicted masks and logits against ground truth targets', 'create a batch dice loss computation between predicted and target mask tensors for segmentation matching', 'create a batch sigmoid cross-entropy loss between predicted and target mask tensors for cost computation', 'review the memory efficient forward method that uses point sampling and linear sum assignment for matching']
```

Usage

```
{'build_VideoHungarianMatcher': 'build a VideoHungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for bipartite matching', 'run_VideoHungarianMatcher_forward': 'run the VideoHungarianMatcher forward pass to match predicted masks and logits against ground truth targets', 'create_batch_dice_loss': 'create a batch dice loss computation between predicted and target mask tensors for segmentation matching', 'create_batch_sigmoid_ce_loss': 'create a batch sigmoid cross-entropy loss between predicted and target mask tensors for cost computation', 'review_VideoHungarianMatcher_memory_efficient_forward': 'review the memory efficient forward method that uses point sampling and linear sum assignment for matching'}
```


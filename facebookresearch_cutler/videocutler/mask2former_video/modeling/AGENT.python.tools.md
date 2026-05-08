# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former_video/modeling/criterion.py

Prompts

```
['compute the DICE loss between predicted masks and target binary masks using dice_loss', 'compute the sigmoid cross entropy loss between predicted logits and target masks using sigmoid_ce_loss', 'calculate uncertainty scores from logit predictions using L1 distance from zero with calculate_uncertainty', 'create a VideoSetCriterion module to compute classification and mask losses for video segmentation models', 'compute all segmentation losses including CE, dice, and mask losses by calling VideoSetCriterion forward method', 'build a VideoHungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for bipartite matching', 'run the VideoHungarianMatcher forward pass to match predicted masks and logits against ground truth targets', 'create a batch dice loss computation between predicted and target mask tensors for segmentation matching', 'create a batch sigmoid cross-entropy loss computation between predicted and target mask tensors', 'review the memory_efficient_forward method that uses random point sampling and LSAP for efficient video mask matching']
```

Usage

```
{'compute_dice_loss': 'compute the DICE loss between predicted masks and target binary masks using dice_loss', 'compute_sigmoid_ce_loss': 'compute the sigmoid cross entropy loss between predicted logits and target masks using sigmoid_ce_loss', 'calculate_uncertainty': 'calculate uncertainty scores from logit predictions using L1 distance from zero with calculate_uncertainty', 'create_video_set_criterion': 'create a VideoSetCriterion module to compute classification and mask losses for video segmentation models', 'compute_video_segmentation_losses': 'compute all segmentation losses including CE, dice, and mask losses by calling VideoSetCriterion forward method'}
```

## File: facebookresearch_cutler/videocutler/mask2former_video/modeling/matcher.py

Prompts

```
['compute the DICE loss between predicted masks and target binary masks using dice_loss', 'compute the sigmoid cross entropy loss between predicted logits and target masks using sigmoid_ce_loss', 'calculate uncertainty scores from logit predictions using L1 distance from zero with calculate_uncertainty', 'create a VideoSetCriterion module to compute classification and mask losses for video segmentation models', 'compute all segmentation losses including CE, dice, and mask losses by calling VideoSetCriterion forward method', 'build a VideoHungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for bipartite matching', 'run the VideoHungarianMatcher forward pass to match predicted masks and logits against ground truth targets', 'create a batch dice loss computation between predicted and target mask tensors for segmentation matching', 'create a batch sigmoid cross-entropy loss computation between predicted and target mask tensors', 'review the memory_efficient_forward method that uses random point sampling and LSAP for efficient video mask matching']
```

Usage

```
{'build_VideoHungarianMatcher': 'build a VideoHungarianMatcher instance with custom cost_class, cost_mask, and cost_dice weights for bipartite matching', 'run_VideoHungarianMatcher_forward': 'run the VideoHungarianMatcher forward pass to match predicted masks and logits against ground truth targets', 'create_batch_dice_loss': 'create a batch dice loss computation between predicted and target mask tensors for segmentation matching', 'create_batch_sigmoid_ce_loss': 'create a batch sigmoid cross-entropy loss computation between predicted and target mask tensors', 'review_VideoHungarianMatcher_memory_efficient_forward': 'review the memory_efficient_forward method that uses random point sampling and LSAP for efficient video mask matching'}
```


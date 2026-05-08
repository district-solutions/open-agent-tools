# Agent Python Tools

- repo: facebookresearch/ov-seg
- repo_uri: https://github.com/facebookresearch/ov-seg

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/criterion.py

Prompts

```
['compute the DICE loss between predicted masks and target binary masks for segmentation', 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma parameters', 'create a SetCriterion module with a matcher, weight dict, and loss types for MaskFormer training', 'compute the classification cross-entropy loss between predicted logits and target class labels', 'compute combined focal and dice losses between predicted masks and ground truth segmentation masks', 'create a HungarianMatcher instance with custom cost weights for class, mask, and dice loss', 'run the HungarianMatcher forward pass to match predictions to ground truth targets', 'compute the batch DICE loss between predicted masks and target binary masks', 'compute the batch sigmoid focal loss between predicted masks and target masks with alpha and gamma', 'review the memory efficient forward matching logic that uses linear sum assignment for bipartite matching']
```

Usage

```
{'compute_dice_loss': 'compute the DICE loss between predicted masks and target binary masks for segmentation', 'compute_sigmoid_focal_loss': 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma parameters', 'create_set_criterion': 'create a SetCriterion module with a matcher, weight dict, and loss types for MaskFormer training', 'compute_label_loss': 'compute the classification cross-entropy loss between predicted logits and target class labels', 'compute_mask_loss': 'compute combined focal and dice losses between predicted masks and ground truth segmentation masks'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/matcher.py

Prompts

```
['compute the DICE loss between predicted masks and target binary masks for segmentation', 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma parameters', 'create a SetCriterion module with a matcher, weight dict, and loss types for MaskFormer training', 'compute the classification cross-entropy loss between predicted logits and target class labels', 'compute combined focal and dice losses between predicted masks and ground truth segmentation masks', 'create a HungarianMatcher instance with custom cost weights for class, mask, and dice loss', 'run the HungarianMatcher forward pass to match predictions to ground truth targets', 'compute the batch DICE loss between predicted masks and target binary masks', 'compute the batch sigmoid focal loss between predicted masks and target masks with alpha and gamma', 'review the memory efficient forward matching logic that uses linear sum assignment for bipartite matching']
```

Usage

```
{'create_HungarianMatcher': 'create a HungarianMatcher instance with custom cost weights for class, mask, and dice loss', 'run_HungarianMatcher_forward': 'run the HungarianMatcher forward pass to match predictions to ground truth targets', 'compute_batch_dice_loss': 'compute the batch DICE loss between predicted masks and target binary masks', 'compute_batch_sigmoid_focal_loss': 'compute the batch sigmoid focal loss between predicted masks and target masks with alpha and gamma', 'review_HungarianMatcher_memory_efficient_forward': 'review the memory efficient forward matching logic that uses linear sum assignment for bipartite matching'}
```


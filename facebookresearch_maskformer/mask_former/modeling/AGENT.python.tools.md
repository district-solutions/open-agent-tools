# Agent Python Tools

- repo: facebookresearch/maskformer
- repo_uri: https://github.com/facebookresearch/maskformer

## File: facebookresearch_maskformer/mask_former/modeling/criterion.py

Prompts

```
['compute the DICE loss between predicted masks and target binary masks for segmentation', 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma parameters', 'create a SetCriterion module with a matcher, weight dict, and loss types for MaskFormer training', 'compute the classification cross-entropy loss between predicted logits and target class labels', 'compute the combined focal and dice loss between predicted masks and target segmentation masks', 'create a HungarianMatcher instance with custom cost weights for classification, mask, and dice costs', 'run the HungarianMatcher forward pass to match predicted masks against ground truth targets', 'compute the batch dice loss between predicted mask logits and binary target masks', 'compute the batch sigmoid focal loss between predicted mask logits and binary target masks', 'review the memory efficient forward method that performs LSAP matching per batch element']
```

Usage

```
{'compute_dice_loss': 'compute the DICE loss between predicted masks and target binary masks for segmentation', 'compute_sigmoid_focal_loss': 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma parameters', 'create_setcriterion': 'create a SetCriterion module with a matcher, weight dict, and loss types for MaskFormer training', 'compute_loss_labels': 'compute the classification cross-entropy loss between predicted logits and target class labels', 'compute_loss_masks': 'compute the combined focal and dice loss between predicted masks and target segmentation masks'}
```

## File: facebookresearch_maskformer/mask_former/modeling/matcher.py

Prompts

```
['compute the DICE loss between predicted masks and target binary masks for segmentation', 'compute the sigmoid focal loss for dense detection with configurable alpha and gamma parameters', 'create a SetCriterion module with a matcher, weight dict, and loss types for MaskFormer training', 'compute the classification cross-entropy loss between predicted logits and target class labels', 'compute the combined focal and dice loss between predicted masks and target segmentation masks', 'create a HungarianMatcher instance with custom cost weights for classification, mask, and dice costs', 'run the HungarianMatcher forward pass to match predicted masks against ground truth targets', 'compute the batch dice loss between predicted mask logits and binary target masks', 'compute the batch sigmoid focal loss between predicted mask logits and binary target masks', 'review the memory efficient forward method that performs LSAP matching per batch element']
```

Usage

```
{'create_hungarian_matcher': 'create a HungarianMatcher instance with custom cost weights for classification, mask, and dice costs', 'run_hungarian_matcher_forward': 'run the HungarianMatcher forward pass to match predicted masks against ground truth targets', 'compute_batch_dice_loss': 'compute the batch dice loss between predicted mask logits and binary target masks', 'compute_batch_sigmoid_focal_loss': 'compute the batch sigmoid focal loss between predicted mask logits and binary target masks', 'review_hungarianmatcher_memory_efficient_forward': 'review the memory efficient forward method that performs LSAP matching per batch element'}
```


# Agent Python Tools

- repo: facebookresearch/sam3
- repo_uri: https://github.com/facebookresearch/sam3

## File: facebookresearch_sam3/sam3/train/loss/loss_fns.py

Prompts

```
['build a dice loss function for segmentation masks with GPU OOM fallback to CPU', 'create a sigmoid focal loss with triton acceleration and alpha/gamma weighting for class imbalance', 'test the IABCEMdetr class for classification loss with presence scores, padded queries, and weak loss modes', 'review the Masks class that computes sampled focal loss and dice loss for instance segmentation masks', 'summarize the SemanticSegCriterion class for semantic segmentation with focal loss and presence head support', 'sample feature map values at normalized point coordinates using bilinear interpolation', 'sample uncertain points from logits using an uncertainty function with oversampling and importance sampling', 'calculate uncertainty scores as L1 distance from zero for class-agnostic predicted mask logits', 'test the point_sample function with feature tensors and normalized 2D point coordinates', 'review get_uncertain_point_coords_with_randomness for sampling mask prediction points by uncertainty', 'create a Sam3LossWrapper instance with loss functions, matchers, and normalization settings for SAM3 training', 'compute the total loss for SAM3 find stages by iterating over outputs and targets with auxiliary and first-stage losses', 'create a DummyLoss module that returns zero as a placeholder for evaluation', 'run the Sam3LossWrapper forward pass to aggregate losses across all find stages with optional semantic segmentation loss', 'normalize the number of valid target boxes for loss scaling using global, local, or none normalization modes', 'run a memory-efficient sigmoid focal loss with sum reduction using SigmoidFocalLossReduced.autograd.Function for scalar loss output', 'compute the numerically stable inner forward focal loss with alpha and gamma modulation via _inner_focal_loss_fwd', 'compute the gradient of the focal loss with respect to inputs via _inner_focal_loss_bwd for backpropagation', 'launch Triton forward and backward kernels for sigmoid focal loss with configurable BLOCK_SIZE grid execution']
```

Usage

```
{'build_dice_loss': 'build a dice loss function for segmentation masks with GPU OOM fallback to CPU', 'create_sigmoid_focal_loss': 'create a sigmoid focal loss with triton acceleration and alpha/gamma weighting for class imbalance', 'test_IABCEMdetr': 'test the IABCEMdetr class for classification loss with presence scores, padded queries, and weak loss modes', 'review_Masks_criterion': 'review the Masks class that computes sampled focal loss and dice loss for instance segmentation masks', 'summarize_SemanticSegCriterion': 'summarize the SemanticSegCriterion class for semantic segmentation with focal loss and presence head support'}
```

## File: facebookresearch_sam3/sam3/train/loss/mask_sampling.py

Prompts

```
['build a dice loss function for segmentation masks with GPU OOM fallback to CPU', 'create a sigmoid focal loss with triton acceleration and alpha/gamma weighting for class imbalance', 'test the IABCEMdetr class for classification loss with presence scores, padded queries, and weak loss modes', 'review the Masks class that computes sampled focal loss and dice loss for instance segmentation masks', 'summarize the SemanticSegCriterion class for semantic segmentation with focal loss and presence head support', 'sample feature map values at normalized point coordinates using bilinear interpolation', 'sample uncertain points from logits using an uncertainty function with oversampling and importance sampling', 'calculate uncertainty scores as L1 distance from zero for class-agnostic predicted mask logits', 'test the point_sample function with feature tensors and normalized 2D point coordinates', 'review get_uncertain_point_coords_with_randomness for sampling mask prediction points by uncertainty', 'create a Sam3LossWrapper instance with loss functions, matchers, and normalization settings for SAM3 training', 'compute the total loss for SAM3 find stages by iterating over outputs and targets with auxiliary and first-stage losses', 'create a DummyLoss module that returns zero as a placeholder for evaluation', 'run the Sam3LossWrapper forward pass to aggregate losses across all find stages with optional semantic segmentation loss', 'normalize the number of valid target boxes for loss scaling using global, local, or none normalization modes', 'run a memory-efficient sigmoid focal loss with sum reduction using SigmoidFocalLossReduced.autograd.Function for scalar loss output', 'compute the numerically stable inner forward focal loss with alpha and gamma modulation via _inner_focal_loss_fwd', 'compute the gradient of the focal loss with respect to inputs via _inner_focal_loss_bwd for backpropagation', 'launch Triton forward and backward kernels for sigmoid focal loss with configurable BLOCK_SIZE grid execution']
```

Usage

```
{'build_point_sample': 'sample feature map values at normalized point coordinates using bilinear interpolation', 'create_uncertain_point_coords': 'sample uncertain points from logits using an uncertainty function with oversampling and importance sampling', 'calculate_mask_uncertainty': 'calculate uncertainty scores as L1 distance from zero for class-agnostic predicted mask logits', 'test_point_sample': 'test the point_sample function with feature tensors and normalized 2D point coordinates', 'review_uncertain_point_coords': 'review get_uncertain_point_coords_with_randomness for sampling mask prediction points by uncertainty'}
```

## File: facebookresearch_sam3/sam3/train/loss/sam3_loss.py

Prompts

```
['build a dice loss function for segmentation masks with GPU OOM fallback to CPU', 'create a sigmoid focal loss with triton acceleration and alpha/gamma weighting for class imbalance', 'test the IABCEMdetr class for classification loss with presence scores, padded queries, and weak loss modes', 'review the Masks class that computes sampled focal loss and dice loss for instance segmentation masks', 'summarize the SemanticSegCriterion class for semantic segmentation with focal loss and presence head support', 'sample feature map values at normalized point coordinates using bilinear interpolation', 'sample uncertain points from logits using an uncertainty function with oversampling and importance sampling', 'calculate uncertainty scores as L1 distance from zero for class-agnostic predicted mask logits', 'test the point_sample function with feature tensors and normalized 2D point coordinates', 'review get_uncertain_point_coords_with_randomness for sampling mask prediction points by uncertainty', 'create a Sam3LossWrapper instance with loss functions, matchers, and normalization settings for SAM3 training', 'compute the total loss for SAM3 find stages by iterating over outputs and targets with auxiliary and first-stage losses', 'create a DummyLoss module that returns zero as a placeholder for evaluation', 'run the Sam3LossWrapper forward pass to aggregate losses across all find stages with optional semantic segmentation loss', 'normalize the number of valid target boxes for loss scaling using global, local, or none normalization modes', 'run a memory-efficient sigmoid focal loss with sum reduction using SigmoidFocalLossReduced.autograd.Function for scalar loss output', 'compute the numerically stable inner forward focal loss with alpha and gamma modulation via _inner_focal_loss_fwd', 'compute the gradient of the focal loss with respect to inputs via _inner_focal_loss_bwd for backpropagation', 'launch Triton forward and backward kernels for sigmoid focal loss with configurable BLOCK_SIZE grid execution']
```

Usage

```
{'create_Sam3LossWrapper': 'create a Sam3LossWrapper instance with loss functions, matchers, and normalization settings for SAM3 training', 'compute_Sam3LossWrapper_loss': 'compute the total loss for SAM3 find stages by iterating over outputs and targets with auxiliary and first-stage losses', 'create_DummyLoss': 'create a DummyLoss module that returns zero as a placeholder for evaluation', 'run_Sam3LossWrapper_forward': 'run the Sam3LossWrapper forward pass to aggregate losses across all find stages with optional semantic segmentation loss', 'normalize_Sam3LossWrapper_boxes': 'normalize the number of valid target boxes for loss scaling using global, local, or none normalization modes'}
```

## File: facebookresearch_sam3/sam3/train/loss/sigmoid_focal_loss.py

Prompts

```
['build a dice loss function for segmentation masks with GPU OOM fallback to CPU', 'create a sigmoid focal loss with triton acceleration and alpha/gamma weighting for class imbalance', 'test the IABCEMdetr class for classification loss with presence scores, padded queries, and weak loss modes', 'review the Masks class that computes sampled focal loss and dice loss for instance segmentation masks', 'summarize the SemanticSegCriterion class for semantic segmentation with focal loss and presence head support', 'sample feature map values at normalized point coordinates using bilinear interpolation', 'sample uncertain points from logits using an uncertainty function with oversampling and importance sampling', 'calculate uncertainty scores as L1 distance from zero for class-agnostic predicted mask logits', 'test the point_sample function with feature tensors and normalized 2D point coordinates', 'review get_uncertain_point_coords_with_randomness for sampling mask prediction points by uncertainty', 'create a Sam3LossWrapper instance with loss functions, matchers, and normalization settings for SAM3 training', 'compute the total loss for SAM3 find stages by iterating over outputs and targets with auxiliary and first-stage losses', 'create a DummyLoss module that returns zero as a placeholder for evaluation', 'run the Sam3LossWrapper forward pass to aggregate losses across all find stages with optional semantic segmentation loss', 'normalize the number of valid target boxes for loss scaling using global, local, or none normalization modes', 'run a memory-efficient sigmoid focal loss with sum reduction using SigmoidFocalLossReduced.autograd.Function for scalar loss output', 'compute the numerically stable inner forward focal loss with alpha and gamma modulation via _inner_focal_loss_fwd', 'compute the gradient of the focal loss with respect to inputs via _inner_focal_loss_bwd for backpropagation', 'launch Triton forward and backward kernels for sigmoid focal loss with configurable BLOCK_SIZE grid execution']
```

Usage

```
{'create_sigmoid_focal_loss': 'create a Triton-accelerated sigmoid focal loss using SigmoidFocalLoss.autograd.Function for element-wise per-element loss output', 'run_sigmoid_focal_loss_reduce': 'run a memory-efficient sigmoid focal loss with sum reduction using SigmoidFocalLossReduced.autograd.Function for scalar loss output', 'compute_inner_focal_loss_fwd': 'compute the numerically stable inner forward focal loss with alpha and gamma modulation via _inner_focal_loss_fwd', 'compute_inner_focal_loss_bwd': 'compute the gradient of the focal loss with respect to inputs via _inner_focal_loss_bwd for backpropagation', 'launch_focal_loss_kernels': 'launch Triton forward and backward kernels for sigmoid focal loss with configurable BLOCK_SIZE grid execution'}
```


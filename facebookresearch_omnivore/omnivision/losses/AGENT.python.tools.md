# Agent Python Tools

- repo: facebookresearch/omnivore
- repo_uri: https://github.com/facebookresearch/omnivore

## File: facebookresearch_omnivore/omnivision/losses/cross_entropy_multiple_output_single_target.py

Prompts

```
['create a SmoothCrossEntropy loss that handles smoothed labels and single-target labels', 'build a CrossEntropyMultipleOutputSingleTargetLoss to compute summed cross-entropy across multiple output tensors', 'test the CrossEntropyMultipleOutputSingleTargetLoss forward pass with a custom temperature scaling factor', 'review the SmoothCrossEntropy forward method to understand how label smoothing is applied via log_softmax', 'refactor the CrossEntropyMultipleOutputSingleTargetLoss to enable L2 normalization on prediction tensors before loss computation', 'create an MAELoss instance with patch size 16 and pixel normalization enabled', 'compute the masked autoencoder loss between predicted patches, mask, and original image', 'run the core forward pass computing MAE loss from model output and VisionMaskSample', 'patchify an image tensor into non-overlapping patches using configurable patch size', 'configure MAELoss to normalize pixel values per RGB channel like VideoMAE', 'create a ScaledLoss wrapping any loss function with a configurable scale factor', 'build a ScaledLoss that wraps BCELoss with a scale of 2.0 for weighted binary cross entropy', 'test the ScaledLoss forward pass by verifying the scaled output matches loss_fn output times scale', 'refactor the ScaledLoss class to support dynamic scale adjustment during training', 'review the ScaledLoss __init__ to confirm it stores loss_fn and scale as instance attributes']
```

Usage

```
{'create_smooth_cross_entropy': 'create a SmoothCrossEntropy loss that handles smoothed labels and single-target labels', 'build_multi_output_loss': 'build a CrossEntropyMultipleOutputSingleTargetLoss to compute summed cross-entropy across multiple output tensors', 'test_loss_with_temperature': 'test the CrossEntropyMultipleOutputSingleTargetLoss forward pass with a custom temperature scaling factor', 'review_loss_label_smoothing': 'review the SmoothCrossEntropy forward method to understand how label smoothing is applied via log_softmax', 'refactor_loss_normalize_output': 'refactor the CrossEntropyMultipleOutputSingleTargetLoss to enable L2 normalization on prediction tensors before loss computation'}
```

## File: facebookresearch_omnivore/omnivision/losses/mae_loss.py

Prompts

```
['create a SmoothCrossEntropy loss that handles smoothed labels and single-target labels', 'build a CrossEntropyMultipleOutputSingleTargetLoss to compute summed cross-entropy across multiple output tensors', 'test the CrossEntropyMultipleOutputSingleTargetLoss forward pass with a custom temperature scaling factor', 'review the SmoothCrossEntropy forward method to understand how label smoothing is applied via log_softmax', 'refactor the CrossEntropyMultipleOutputSingleTargetLoss to enable L2 normalization on prediction tensors before loss computation', 'create an MAELoss instance with patch size 16 and pixel normalization enabled', 'compute the masked autoencoder loss between predicted patches, mask, and original image', 'run the core forward pass computing MAE loss from model output and VisionMaskSample', 'patchify an image tensor into non-overlapping patches using configurable patch size', 'configure MAELoss to normalize pixel values per RGB channel like VideoMAE', 'create a ScaledLoss wrapping any loss function with a configurable scale factor', 'build a ScaledLoss that wraps BCELoss with a scale of 2.0 for weighted binary cross entropy', 'test the ScaledLoss forward pass by verifying the scaled output matches loss_fn output times scale', 'refactor the ScaledLoss class to support dynamic scale adjustment during training', 'review the ScaledLoss __init__ to confirm it stores loss_fn and scale as instance attributes']
```

Usage

```
{'create_MAELoss_instance': 'create an MAELoss instance with patch size 16 and pixel normalization enabled', 'compute_mae_loss': 'compute the masked autoencoder loss between predicted patches, mask, and original image', 'core_forward': 'run the core forward pass computing MAE loss from model output and VisionMaskSample', 'patchify_images': 'patchify an image tensor into non-overlapping patches using configurable patch size', 'configure_MAELoss_per_channel': 'configure MAELoss to normalize pixel values per RGB channel like VideoMAE'}
```

## File: facebookresearch_omnivore/omnivision/losses/scaled_loss.py

Prompts

```
['create a SmoothCrossEntropy loss that handles smoothed labels and single-target labels', 'build a CrossEntropyMultipleOutputSingleTargetLoss to compute summed cross-entropy across multiple output tensors', 'test the CrossEntropyMultipleOutputSingleTargetLoss forward pass with a custom temperature scaling factor', 'review the SmoothCrossEntropy forward method to understand how label smoothing is applied via log_softmax', 'refactor the CrossEntropyMultipleOutputSingleTargetLoss to enable L2 normalization on prediction tensors before loss computation', 'create an MAELoss instance with patch size 16 and pixel normalization enabled', 'compute the masked autoencoder loss between predicted patches, mask, and original image', 'run the core forward pass computing MAE loss from model output and VisionMaskSample', 'patchify an image tensor into non-overlapping patches using configurable patch size', 'configure MAELoss to normalize pixel values per RGB channel like VideoMAE', 'create a ScaledLoss wrapping any loss function with a configurable scale factor', 'build a ScaledLoss that wraps BCELoss with a scale of 2.0 for weighted binary cross entropy', 'test the ScaledLoss forward pass by verifying the scaled output matches loss_fn output times scale', 'refactor the ScaledLoss class to support dynamic scale adjustment during training', 'review the ScaledLoss __init__ to confirm it stores loss_fn and scale as instance attributes']
```

Usage

```
{'create_scaled_loss': 'create a ScaledLoss wrapping any loss function with a configurable scale factor', 'build_scaled_bce_loss': 'build a ScaledLoss that wraps BCELoss with a scale of 2.0 for weighted binary cross entropy', 'test_scaled_loss_forward': 'test the ScaledLoss forward pass by verifying the scaled output matches loss_fn output times scale', 'refactor_scaled_loss': 'refactor the ScaledLoss class to support dynamic scale adjustment during training', 'review_scaled_loss_init': 'review the ScaledLoss __init__ to confirm it stores loss_fn and scale as instance attributes'}
```


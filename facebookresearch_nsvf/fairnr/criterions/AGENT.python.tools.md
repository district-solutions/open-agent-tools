# Agent Python Tools

- repo: facebookresearch/nsvf
- repo_uri: https://github.com/facebookresearch/nsvf

## File: facebookresearch_nsvf/fairnr/criterions/perceptual_loss.py

Prompts

```
['build a VGGPerceptualLoss module with default settings using pretrained VGG16 features for perceptual loss computation', 'build a VGGPerceptualLoss module with resize enabled to bilinearly interpolate inputs to 224x224 before computing loss', 'run the forward pass of VGGPerceptualLoss on input and target tensors to compute MSE loss across VGG feature blocks', 'test VGGPerceptualLoss forward pass with different level values to control how many VGG feature blocks contribute to loss', 'review the VGGPerceptualLoss class to verify all pretrained VGG16 parameters have requires_grad set to False', 'build a rendering loss criterion with color, depth, alpha, VGG, and eikonal loss weights', 'create a subclass of RenderingCriterion that overrides compute_loss for custom rendering loss computation', 'test the SRNLossCriterion compute_loss method with sample data containing colors, depths, and alpha masks', 'review the RenderingCriterion forward method to understand hierarchical loss computation and logging output generation', 'refactor the SRNLossCriterion depth weight decay logic to use a safer parsing method instead of eval', 'compute the L2 RGB loss between predicted and ground truth RGB values with optional masking', 'compute the L1 RGB loss between predicted and ground truth RGB values using absolute difference', 'compute the squared depth loss between predicted and ground truth depth values with optional masking', 'compute the summed RGB loss across all pixels instead of the mean for batch aggregation', 'compute the summed depth loss across all pixels instead of the mean for batch aggregation']
```

Usage

```
{'build_VGGPerceptualLoss_default': 'build a VGGPerceptualLoss module with default settings using pretrained VGG16 features for perceptual loss computation', 'build_VGGPerceptualLoss_resize': 'build a VGGPerceptualLoss module with resize enabled to bilinearly interpolate inputs to 224x224 before computing loss', 'run_VGGPerceptualLoss_forward': 'run the forward pass of VGGPerceptualLoss on input and target tensors to compute MSE loss across VGG feature blocks', 'test_VGGPerceptualLoss_level': 'test VGGPerceptualLoss forward pass with different level values to control how many VGG feature blocks contribute to loss', 'review_VGGPerceptualLoss_grad_freeze': 'review the VGGPerceptualLoss class to verify all pretrained VGG16 parameters have requires_grad set to False'}
```

## File: facebookresearch_nsvf/fairnr/criterions/rendering_loss.py

Prompts

```
['build a VGGPerceptualLoss module with default settings using pretrained VGG16 features for perceptual loss computation', 'build a VGGPerceptualLoss module with resize enabled to bilinearly interpolate inputs to 224x224 before computing loss', 'run the forward pass of VGGPerceptualLoss on input and target tensors to compute MSE loss across VGG feature blocks', 'test VGGPerceptualLoss forward pass with different level values to control how many VGG feature blocks contribute to loss', 'review the VGGPerceptualLoss class to verify all pretrained VGG16 parameters have requires_grad set to False', 'build a rendering loss criterion with color, depth, alpha, VGG, and eikonal loss weights', 'create a subclass of RenderingCriterion that overrides compute_loss for custom rendering loss computation', 'test the SRNLossCriterion compute_loss method with sample data containing colors, depths, and alpha masks', 'review the RenderingCriterion forward method to understand hierarchical loss computation and logging output generation', 'refactor the SRNLossCriterion depth weight decay logic to use a safer parsing method instead of eval', 'compute the L2 RGB loss between predicted and ground truth RGB values with optional masking', 'compute the L1 RGB loss between predicted and ground truth RGB values using absolute difference', 'compute the squared depth loss between predicted and ground truth depth values with optional masking', 'compute the summed RGB loss across all pixels instead of the mean for batch aggregation', 'compute the summed depth loss across all pixels instead of the mean for batch aggregation']
```

Usage

```
{'build_SRNLossCriterion': 'build a rendering loss criterion with color, depth, alpha, VGG, and eikonal loss weights', 'create_RenderingCriterion_subclass': 'create a subclass of RenderingCriterion that overrides compute_loss for custom rendering loss computation', 'test_SRNLossCriterion_compute_loss': 'test the SRNLossCriterion compute_loss method with sample data containing colors, depths, and alpha masks', 'review_RenderingCriterion_forward': 'review the RenderingCriterion forward method to understand hierarchical loss computation and logging output generation', 'refactor_SRNLossCriterion_depth_weight_decay': 'refactor the SRNLossCriterion depth weight decay logic to use a safer parsing method instead of eval'}
```

## File: facebookresearch_nsvf/fairnr/criterions/utils.py

Prompts

```
['build a VGGPerceptualLoss module with default settings using pretrained VGG16 features for perceptual loss computation', 'build a VGGPerceptualLoss module with resize enabled to bilinearly interpolate inputs to 224x224 before computing loss', 'run the forward pass of VGGPerceptualLoss on input and target tensors to compute MSE loss across VGG feature blocks', 'test VGGPerceptualLoss forward pass with different level values to control how many VGG feature blocks contribute to loss', 'review the VGGPerceptualLoss class to verify all pretrained VGG16 parameters have requires_grad set to False', 'build a rendering loss criterion with color, depth, alpha, VGG, and eikonal loss weights', 'create a subclass of RenderingCriterion that overrides compute_loss for custom rendering loss computation', 'test the SRNLossCriterion compute_loss method with sample data containing colors, depths, and alpha masks', 'review the RenderingCriterion forward method to understand hierarchical loss computation and logging output generation', 'refactor the SRNLossCriterion depth weight decay logic to use a safer parsing method instead of eval', 'compute the L2 RGB loss between predicted and ground truth RGB values with optional masking', 'compute the L1 RGB loss between predicted and ground truth RGB values using absolute difference', 'compute the squared depth loss between predicted and ground truth depth values with optional masking', 'compute the summed RGB loss across all pixels instead of the mean for batch aggregation', 'compute the summed depth loss across all pixels instead of the mean for batch aggregation']
```

Usage

```
{'compute_rgb_loss_l2': 'compute the L2 RGB loss between predicted and ground truth RGB values with optional masking', 'compute_rgb_loss_l1': 'compute the L1 RGB loss between predicted and ground truth RGB values using absolute difference', 'compute_depth_loss': 'compute the squared depth loss between predicted and ground truth depth values with optional masking', 'compute_rgb_loss_sum': 'compute the summed RGB loss across all pixels instead of the mean for batch aggregation', 'compute_depth_loss_sum': 'compute the summed depth loss across all pixels instead of the mean for batch aggregation'}
```


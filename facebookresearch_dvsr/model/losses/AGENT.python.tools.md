# Agent Python Tools

- repo: facebookresearch/dvsr
- repo_uri: https://github.com/facebookresearch/dvsr

## File: facebookresearch_dvsr/model/losses/pixelwise_loss.py

Prompts

```
['build a PyTorch module that computes L1 loss between predicted and target tensors with configurable reduction', 'build a PyTorch module that computes MSE loss between predicted and target tensors with configurable reduction', 'build a PyTorch module that computes Charbonnier loss as a differentiable variant of L1 loss', 'build a PyTorch module that computes masked total variation loss using horizontal and vertical gradients', 'test the l1_loss function that returns element-wise L1 loss between two tensors', 'reduce a PyTorch loss tensor using mean, sum, or none reduction strategy', 'apply element-wise weight to a loss tensor and reduce with mean or sum', 'compute sample-wise mean of a weighted loss tensor across spatial dimensions', 'create a masked version of an element-wise loss function with weight and reduction support', 'decorate an L1 loss function with the masked_loss decorator to support masking and reduction']
```

Usage

```
{'build_L1Loss_module': 'build a PyTorch module that computes L1 loss between predicted and target tensors with configurable reduction', 'build_MSELoss_module': 'build a PyTorch module that computes MSE loss between predicted and target tensors with configurable reduction', 'build_CharbonnierLoss_module': 'build a PyTorch module that computes Charbonnier loss as a differentiable variant of L1 loss', 'build_MaskedTVLoss_module': 'build a PyTorch module that computes masked total variation loss using horizontal and vertical gradients', 'test_l1_loss_function': 'test the l1_loss function that returns element-wise L1 loss between two tensors'}
```

## File: facebookresearch_dvsr/model/losses/utils.py

Prompts

```
['build a PyTorch module that computes L1 loss between predicted and target tensors with configurable reduction', 'build a PyTorch module that computes MSE loss between predicted and target tensors with configurable reduction', 'build a PyTorch module that computes Charbonnier loss as a differentiable variant of L1 loss', 'build a PyTorch module that computes masked total variation loss using horizontal and vertical gradients', 'test the l1_loss function that returns element-wise L1 loss between two tensors', 'reduce a PyTorch loss tensor using mean, sum, or none reduction strategy', 'apply element-wise weight to a loss tensor and reduce with mean or sum', 'compute sample-wise mean of a weighted loss tensor across spatial dimensions', 'create a masked version of an element-wise loss function with weight and reduction support', 'decorate an L1 loss function with the masked_loss decorator to support masking and reduction']
```

Usage

```
{'reduce_loss_tensor': 'reduce a PyTorch loss tensor using mean, sum, or none reduction strategy', 'mask_reduce_loss_with_weight': 'apply element-wise weight to a loss tensor and reduce with mean or sum', 'mask_reduce_loss_sample_wise': 'compute sample-wise mean of a weighted loss tensor across spatial dimensions', 'create_masked_loss_decorator': 'create a masked version of an element-wise loss function with weight and reduction support', 'use_masked_loss_l1': 'decorate an L1 loss function with the masked_loss decorator to support masking and reduction'}
```


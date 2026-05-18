# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/modules/losses/diffusion_hybrid_loss.py

Prompts

```
['build a DiffusionHybridLoss module combining MSE and VLB loss for training diffusion model variance', 'create a DiffusionHybridLoss with a custom lambda weight for VLB loss balancing', 'run the forward pass of DiffusionHybridLoss with input target mean log_variance x0 xt and t tensors', 'review the DiffusionHybridLoss constructor to configure schedule simple_loss and lambda parameters', 'test that DiffusionHybridLoss correctly combines simple MSE loss with weighted VLB loss output', 'create a VLBLoss instance with a DiscreteGaussianSchedule to compute variational lower bound loss for diffusion models', 'run the VLBLoss forward pass with predicted mean, log variance, target data, corrupted data, and timestep tensors', 'compute the discretized Gaussian log likelihood for pixel values using mean and log scale tensors', 'calculate the KL divergence between two normal distributions given their means and log variances', 'approximate the standard normal cumulative distribution function using a tanh-based formula for diffusion loss computation']
```

Usage

```
{'build_diffusion_hybrid_loss': 'build a DiffusionHybridLoss module combining MSE and VLB loss for training diffusion model variance', 'create_hybrid_loss_with_custom_lambda': 'create a DiffusionHybridLoss with a custom lambda weight for VLB loss balancing', 'run_hybrid_loss_forward': 'run the forward pass of DiffusionHybridLoss with input target mean log_variance x0 xt and t tensors', 'review_diffusion_hybrid_loss_init': 'review the DiffusionHybridLoss constructor to configure schedule simple_loss and lambda parameters', 'test_vlb_loss_integration': 'test that DiffusionHybridLoss correctly combines simple MSE loss with weighted VLB loss output'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/modules/losses/vlb_loss.py

Prompts

```
['build a DiffusionHybridLoss module combining MSE and VLB loss for training diffusion model variance', 'create a DiffusionHybridLoss with a custom lambda weight for VLB loss balancing', 'run the forward pass of DiffusionHybridLoss with input target mean log_variance x0 xt and t tensors', 'review the DiffusionHybridLoss constructor to configure schedule simple_loss and lambda parameters', 'test that DiffusionHybridLoss correctly combines simple MSE loss with weighted VLB loss output', 'create a VLBLoss instance with a DiscreteGaussianSchedule to compute variational lower bound loss for diffusion models', 'run the VLBLoss forward pass with predicted mean, log variance, target data, corrupted data, and timestep tensors', 'compute the discretized Gaussian log likelihood for pixel values using mean and log scale tensors', 'calculate the KL divergence between two normal distributions given their means and log variances', 'approximate the standard normal cumulative distribution function using a tanh-based formula for diffusion loss computation']
```

Usage

```
{'create_vlb_loss_module': 'create a VLBLoss instance with a DiscreteGaussianSchedule to compute variational lower bound loss for diffusion models', 'run_vlb_loss_forward': 'run the VLBLoss forward pass with predicted mean, log variance, target data, corrupted data, and timestep tensors', 'compute_discretized_gaussian_log_likelihood': 'compute the discretized Gaussian log likelihood for pixel values using mean and log scale tensors', 'calculate_normal_kl_divergence': 'calculate the KL divergence between two normal distributions given their means and log variances', 'approximate_standard_normal_cdf': 'approximate the standard normal cumulative distribution function using a tanh-based formula for diffusion loss computation'}
```


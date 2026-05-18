# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/neuralcompression/loss_fn/_normfix_lpips.py

Prompts

```
['build a NormFixLPIPS loss function that computes perceptual similarity between two image tensors with stable gradients', 'create a function that normalizes a tensor by its L2 norm per channel with epsilon protection against division by zero', 'test the NormFixLPIPS forward pass by computing the perceptual difference between two input image tensors', 'review the NormFixLPIPS train method that forces the underlying LPIPS network to stay in eval mode', 'refactor the normalize_tensor function to use a different epsilon value for numerical stability', 'create a TargetRateConfig instance with target_bpp, target_factors, target_steps, lam_levels, lam2_factors, and lam2_steps', 'review the TargetRateConfig constructor validation that steps list length must be one less than factors list', 'access the target_bpp property to retrieve the target bits-per-pixel rate from a TargetRateConfig', 'access the lam_levels property to retrieve the lambda coding cost tuple from a TargetRateConfig', 'access the target_steps property to retrieve training step intervals from a TargetRateConfig']
```

Usage

```
{'build_normfix_lpips_loss': 'build a NormFixLPIPS loss function that computes perceptual similarity between two image tensors with stable gradients', 'create_normalize_tensor': 'create a function that normalizes a tensor by its L2 norm per channel with epsilon protection against division by zero', 'test_normfix_lpips_forward': 'test the NormFixLPIPS forward pass by computing the perceptual difference between two input image tensors', 'review_normfix_lpips_train': 'review the NormFixLPIPS train method that forces the underlying LPIPS network to stay in eval mode', 'refactor_normalize_tensor_eps': 'refactor the normalize_tensor function to use a different epsilon value for numerical stability'}
```

## File: facebookresearch_neuralcompression/neuralcompression/loss_fn/_target_rate_config.py

Prompts

```
['build a NormFixLPIPS loss function that computes perceptual similarity between two image tensors with stable gradients', 'create a function that normalizes a tensor by its L2 norm per channel with epsilon protection against division by zero', 'test the NormFixLPIPS forward pass by computing the perceptual difference between two input image tensors', 'review the NormFixLPIPS train method that forces the underlying LPIPS network to stay in eval mode', 'refactor the normalize_tensor function to use a different epsilon value for numerical stability', 'create a TargetRateConfig instance with target_bpp, target_factors, target_steps, lam_levels, lam2_factors, and lam2_steps', 'review the TargetRateConfig constructor validation that steps list length must be one less than factors list', 'access the target_bpp property to retrieve the target bits-per-pixel rate from a TargetRateConfig', 'access the lam_levels property to retrieve the lambda coding cost tuple from a TargetRateConfig', 'access the target_steps property to retrieve training step intervals from a TargetRateConfig']
```

Usage

```
{'create_TargetRateConfig': 'create a TargetRateConfig instance with target_bpp, target_factors, target_steps, lam_levels, lam2_factors, and lam2_steps', 'review_TargetRateConfig_validation': 'review the TargetRateConfig constructor validation that steps list length must be one less than factors list', 'access_target_bpp_property': 'access the target_bpp property to retrieve the target bits-per-pixel rate from a TargetRateConfig', 'access_lam_levels_property': 'access the lam_levels property to retrieve the lambda coding cost tuple from a TargetRateConfig', 'access_target_steps_property': 'access the target_steps property to retrieve training step intervals from a TargetRateConfig'}
```


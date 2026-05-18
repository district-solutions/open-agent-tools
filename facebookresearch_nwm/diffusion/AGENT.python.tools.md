# Agent Python Tools

- repo: facebookresearch/nwm
- repo_uri: https://github.com/facebookresearch/nwm

## File: facebookresearch_nwm/diffusion/diffusion_utils.py

Prompts

```
['compute the KL divergence between two Gaussian distributions using mean and log-variance tensors', 'approximate the cumulative distribution function of a standard normal distribution for a tensor of values', 'compute the log-likelihood of a continuous Gaussian distribution given target values, means, and log scales', 'compute the log-likelihood of a discretized Gaussian distribution for image values in the range [-1, 1]', 'review the diffusion utility functions for Gaussian KL divergence, CDF approximation, and log-likelihood computations', 'create a GaussianDiffusion instance with betas, model_mean_type, model_var_type, and loss_type parameters', 'generate denoised samples from a diffusion model using p_sample_loop with a given shape and model', 'generate denoised samples from a diffusion model using the faster DDIM sampling method with eta control', 'compute training losses for a diffusion model at a given timestep using training_losses method', 'compute a beta schedule array using get_named_beta_schedule with a schedule name and number of timesteps', 'build a SpacedDiffusion process that skips steps in a base GaussianDiffusion using selected timesteps', 'create a set of diffusion timesteps from section counts or a ddimN stride string', 'test space_timesteps with a ddimN string to get DDIM-style integer-strided timesteps', 'review SpacedDiffusion p_mean_variance which wraps the model before computing mean and variance', 'refactor SpacedDiffusion training_losses to wrap the model with timestep mapping before computing losses', 'create a UniformSampler or LossSecondMomentResampler from a diffusion object using the sampler name string', 'sample weighted timestep indices for a batch using the ScheduleSampler sample method with importance sampling', 'get uniform weights across all diffusion timesteps using the UniformSampler weights method', 'update timestep resampling weights based on loss history using the LossSecondMomentResampler update_with_all_losses method', 'synchronize timestep and loss data across distributed ranks using the LossAwareSampler update_with_local_losses method']
```

Usage

```
{'compute_normal_kl_divergence': 'compute the KL divergence between two Gaussian distributions using mean and log-variance tensors', 'approximate_standard_normal_cdf': 'approximate the cumulative distribution function of a standard normal distribution for a tensor of values', 'compute_continuous_gaussian_log_likelihood': 'compute the log-likelihood of a continuous Gaussian distribution given target values, means, and log scales', 'compute_discretized_gaussian_log_likelihood': 'compute the log-likelihood of a discretized Gaussian distribution for image values in the range [-1, 1]', 'review_diffusion_utils': 'review the diffusion utility functions for Gaussian KL divergence, CDF approximation, and log-likelihood computations'}
```

## File: facebookresearch_nwm/diffusion/gaussian_diffusion.py

Prompts

```
['compute the KL divergence between two Gaussian distributions using mean and log-variance tensors', 'approximate the cumulative distribution function of a standard normal distribution for a tensor of values', 'compute the log-likelihood of a continuous Gaussian distribution given target values, means, and log scales', 'compute the log-likelihood of a discretized Gaussian distribution for image values in the range [-1, 1]', 'review the diffusion utility functions for Gaussian KL divergence, CDF approximation, and log-likelihood computations', 'create a GaussianDiffusion instance with betas, model_mean_type, model_var_type, and loss_type parameters', 'generate denoised samples from a diffusion model using p_sample_loop with a given shape and model', 'generate denoised samples from a diffusion model using the faster DDIM sampling method with eta control', 'compute training losses for a diffusion model at a given timestep using training_losses method', 'compute a beta schedule array using get_named_beta_schedule with a schedule name and number of timesteps', 'build a SpacedDiffusion process that skips steps in a base GaussianDiffusion using selected timesteps', 'create a set of diffusion timesteps from section counts or a ddimN stride string', 'test space_timesteps with a ddimN string to get DDIM-style integer-strided timesteps', 'review SpacedDiffusion p_mean_variance which wraps the model before computing mean and variance', 'refactor SpacedDiffusion training_losses to wrap the model with timestep mapping before computing losses', 'create a UniformSampler or LossSecondMomentResampler from a diffusion object using the sampler name string', 'sample weighted timestep indices for a batch using the ScheduleSampler sample method with importance sampling', 'get uniform weights across all diffusion timesteps using the UniformSampler weights method', 'update timestep resampling weights based on loss history using the LossSecondMomentResampler update_with_all_losses method', 'synchronize timestep and loss data across distributed ranks using the LossAwareSampler update_with_local_losses method']
```

Usage

```
{'create_gaussiandiffusion': 'create a GaussianDiffusion instance with betas, model_mean_type, model_var_type, and loss_type parameters', 'generate_samples_p_sample_loop': 'generate denoised samples from a diffusion model using p_sample_loop with a given shape and model', 'generate_samples_ddim_sample_loop': 'generate denoised samples from a diffusion model using the faster DDIM sampling method with eta control', 'compute_training_losses': 'compute training losses for a diffusion model at a given timestep using training_losses method', 'compute_beta_schedule': 'compute a beta schedule array using get_named_beta_schedule with a schedule name and number of timesteps'}
```

## File: facebookresearch_nwm/diffusion/respace.py

Prompts

```
['compute the KL divergence between two Gaussian distributions using mean and log-variance tensors', 'approximate the cumulative distribution function of a standard normal distribution for a tensor of values', 'compute the log-likelihood of a continuous Gaussian distribution given target values, means, and log scales', 'compute the log-likelihood of a discretized Gaussian distribution for image values in the range [-1, 1]', 'review the diffusion utility functions for Gaussian KL divergence, CDF approximation, and log-likelihood computations', 'create a GaussianDiffusion instance with betas, model_mean_type, model_var_type, and loss_type parameters', 'generate denoised samples from a diffusion model using p_sample_loop with a given shape and model', 'generate denoised samples from a diffusion model using the faster DDIM sampling method with eta control', 'compute training losses for a diffusion model at a given timestep using training_losses method', 'compute a beta schedule array using get_named_beta_schedule with a schedule name and number of timesteps', 'build a SpacedDiffusion process that skips steps in a base GaussianDiffusion using selected timesteps', 'create a set of diffusion timesteps from section counts or a ddimN stride string', 'test space_timesteps with a ddimN string to get DDIM-style integer-strided timesteps', 'review SpacedDiffusion p_mean_variance which wraps the model before computing mean and variance', 'refactor SpacedDiffusion training_losses to wrap the model with timestep mapping before computing losses', 'create a UniformSampler or LossSecondMomentResampler from a diffusion object using the sampler name string', 'sample weighted timestep indices for a batch using the ScheduleSampler sample method with importance sampling', 'get uniform weights across all diffusion timesteps using the UniformSampler weights method', 'update timestep resampling weights based on loss history using the LossSecondMomentResampler update_with_all_losses method', 'synchronize timestep and loss data across distributed ranks using the LossAwareSampler update_with_local_losses method']
```

Usage

```
{'build_spaced_diffusion': 'build a SpacedDiffusion process that skips steps in a base GaussianDiffusion using selected timesteps', 'create_space_timesteps': 'create a set of diffusion timesteps from section counts or a ddimN stride string', 'test_space_timesteps_ddim': 'test space_timesteps with a ddimN string to get DDIM-style integer-strided timesteps', 'review_SpacedDiffusion_p_mean_variance': 'review SpacedDiffusion p_mean_variance which wraps the model before computing mean and variance', 'refactor_SpacedDiffusion_training_losses': 'refactor SpacedDiffusion training_losses to wrap the model with timestep mapping before computing losses'}
```

## File: facebookresearch_nwm/diffusion/timestep_sampler.py

Prompts

```
['compute the KL divergence between two Gaussian distributions using mean and log-variance tensors', 'approximate the cumulative distribution function of a standard normal distribution for a tensor of values', 'compute the log-likelihood of a continuous Gaussian distribution given target values, means, and log scales', 'compute the log-likelihood of a discretized Gaussian distribution for image values in the range [-1, 1]', 'review the diffusion utility functions for Gaussian KL divergence, CDF approximation, and log-likelihood computations', 'create a GaussianDiffusion instance with betas, model_mean_type, model_var_type, and loss_type parameters', 'generate denoised samples from a diffusion model using p_sample_loop with a given shape and model', 'generate denoised samples from a diffusion model using the faster DDIM sampling method with eta control', 'compute training losses for a diffusion model at a given timestep using training_losses method', 'compute a beta schedule array using get_named_beta_schedule with a schedule name and number of timesteps', 'build a SpacedDiffusion process that skips steps in a base GaussianDiffusion using selected timesteps', 'create a set of diffusion timesteps from section counts or a ddimN stride string', 'test space_timesteps with a ddimN string to get DDIM-style integer-strided timesteps', 'review SpacedDiffusion p_mean_variance which wraps the model before computing mean and variance', 'refactor SpacedDiffusion training_losses to wrap the model with timestep mapping before computing losses', 'create a UniformSampler or LossSecondMomentResampler from a diffusion object using the sampler name string', 'sample weighted timestep indices for a batch using the ScheduleSampler sample method with importance sampling', 'get uniform weights across all diffusion timesteps using the UniformSampler weights method', 'update timestep resampling weights based on loss history using the LossSecondMomentResampler update_with_all_losses method', 'synchronize timestep and loss data across distributed ranks using the LossAwareSampler update_with_local_losses method']
```

Usage

```
{'create_named_schedule_sampler': 'create a UniformSampler or LossSecondMomentResampler from a diffusion object using the sampler name string', 'sample_timesteps_with_ScheduleSampler': 'sample weighted timestep indices for a batch using the ScheduleSampler sample method with importance sampling', 'get_weights_from_UniformSampler': 'get uniform weights across all diffusion timesteps using the UniformSampler weights method', 'update_loss_weights_with_LossSecondMomentResampler': 'update timestep resampling weights based on loss history using the LossSecondMomentResampler update_with_all_losses method', 'synchronize_losses_across_ranks': 'synchronize timestep and loss data across distributed ranks using the LossAwareSampler update_with_local_losses method'}
```


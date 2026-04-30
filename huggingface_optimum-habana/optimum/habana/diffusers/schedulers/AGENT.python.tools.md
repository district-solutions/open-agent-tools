# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/diffusers/schedulers/scheduling_ddim.py

Prompts

```
['create a GaudiDDIMScheduler instance optimized for Gaudi with custom beta schedule and prediction type', 'run a single DDIM denoising step using the GaudiDDIMScheduler to get the previous sample', 'add Gaussian noise to original samples at specified timesteps using the GaudiDDIMScheduler', 'reset the timestep-dependent parameters in GaudiDDIMScheduler to reinitialize alpha and variance lists', 'roll the time-dependent parameter tensors in GaudiDDIMScheduler to advance to the next timestep', 'create a GaudiEulerAncestralDiscreteScheduler instance with custom beta_start, beta_end, and prediction_type for HPU-optimized diffusion', 'reset the timestep-dependent sigma parameters in a GaudiEulerAncestralDiscreteScheduler to prepare for a new denoising run', 'get the current sigma, sigma_up, and sigma_down parameters for a given timestep in the Euler ancestral scheduler', 'scale a diffusion model input sample by sigma using the GaudiEulerAncestralDiscreteScheduler before calling step', 'perform one denoising step with the GaudiEulerAncestralDiscreteScheduler to predict the previous sample from model output and noise', 'create a GaudiEulerDiscreteScheduler instance with custom beta schedule and prediction type for HPU-optimized diffusion', 'get the current sigma and next sigma values from a GaudiEulerDiscreteScheduler for the active step index', 'roll the sigma parameter tensors forward by one step in a GaudiEulerDiscreteScheduler to advance timesteps', 'step a GaudiEulerDiscreteScheduler to predict the denoised sample from model output and current timestep', 'create a GaudiFlowMatchEulerDiscreteScheduler instance for use with Gaudi lazy mode diffusion pipelines', 'use the index_for_timestep method to find the position of a timestep in the schedule', 'override the base FlowMatchEulerDiscreteScheduler with the Gaudi-specific version for lazy mode support', "get the index of a given timestep within the scheduler's timesteps array", 'handle Gaudi lazy mode by using the custom index_for_timestep override in the scheduler']
```

Usage

```
{'create_gaudi_ddim_scheduler': 'create a GaudiDDIMScheduler instance optimized for Gaudi with custom beta schedule and prediction type', 'run_ddim_step': 'run a single DDIM denoising step using the GaudiDDIMScheduler to get the previous sample', 'add_noise_to_samples': 'add Gaussian noise to original samples at specified timesteps using the GaudiDDIMScheduler', 'reset_timestep_params': 'reset the timestep-dependent parameters in GaudiDDIMScheduler to reinitialize alpha and variance lists', 'roll_scheduler_params': 'roll the time-dependent parameter tensors in GaudiDDIMScheduler to advance to the next timestep'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/schedulers/scheduling_euler_ancestral_discrete.py

Prompts

```
['create a GaudiDDIMScheduler instance optimized for Gaudi with custom beta schedule and prediction type', 'run a single DDIM denoising step using the GaudiDDIMScheduler to get the previous sample', 'add Gaussian noise to original samples at specified timesteps using the GaudiDDIMScheduler', 'reset the timestep-dependent parameters in GaudiDDIMScheduler to reinitialize alpha and variance lists', 'roll the time-dependent parameter tensors in GaudiDDIMScheduler to advance to the next timestep', 'create a GaudiEulerAncestralDiscreteScheduler instance with custom beta_start, beta_end, and prediction_type for HPU-optimized diffusion', 'reset the timestep-dependent sigma parameters in a GaudiEulerAncestralDiscreteScheduler to prepare for a new denoising run', 'get the current sigma, sigma_up, and sigma_down parameters for a given timestep in the Euler ancestral scheduler', 'scale a diffusion model input sample by sigma using the GaudiEulerAncestralDiscreteScheduler before calling step', 'perform one denoising step with the GaudiEulerAncestralDiscreteScheduler to predict the previous sample from model output and noise', 'create a GaudiEulerDiscreteScheduler instance with custom beta schedule and prediction type for HPU-optimized diffusion', 'get the current sigma and next sigma values from a GaudiEulerDiscreteScheduler for the active step index', 'roll the sigma parameter tensors forward by one step in a GaudiEulerDiscreteScheduler to advance timesteps', 'step a GaudiEulerDiscreteScheduler to predict the denoised sample from model output and current timestep', 'create a GaudiFlowMatchEulerDiscreteScheduler instance for use with Gaudi lazy mode diffusion pipelines', 'use the index_for_timestep method to find the position of a timestep in the schedule', 'override the base FlowMatchEulerDiscreteScheduler with the Gaudi-specific version for lazy mode support', "get the index of a given timestep within the scheduler's timesteps array", 'handle Gaudi lazy mode by using the custom index_for_timestep override in the scheduler']
```

Usage

```
{'create_gaudi_euler_ancestral_scheduler': 'create a GaudiEulerAncestralDiscreteScheduler instance with custom beta_start, beta_end, and prediction_type for HPU-optimized diffusion', 'reset_timestep_dependent_params': 'reset the timestep-dependent sigma parameters in a GaudiEulerAncestralDiscreteScheduler to prepare for a new denoising run', 'get_params_sigma_values': 'get the current sigma, sigma_up, and sigma_down parameters for a given timestep in the Euler ancestral scheduler', 'scale_model_input': 'scale a diffusion model input sample by sigma using the GaudiEulerAncestralDiscreteScheduler before calling step', 'step_denoising': 'perform one denoising step with the GaudiEulerAncestralDiscreteScheduler to predict the previous sample from model output and noise'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/schedulers/scheduling_euler_discrete.py

Prompts

```
['create a GaudiDDIMScheduler instance optimized for Gaudi with custom beta schedule and prediction type', 'run a single DDIM denoising step using the GaudiDDIMScheduler to get the previous sample', 'add Gaussian noise to original samples at specified timesteps using the GaudiDDIMScheduler', 'reset the timestep-dependent parameters in GaudiDDIMScheduler to reinitialize alpha and variance lists', 'roll the time-dependent parameter tensors in GaudiDDIMScheduler to advance to the next timestep', 'create a GaudiEulerAncestralDiscreteScheduler instance with custom beta_start, beta_end, and prediction_type for HPU-optimized diffusion', 'reset the timestep-dependent sigma parameters in a GaudiEulerAncestralDiscreteScheduler to prepare for a new denoising run', 'get the current sigma, sigma_up, and sigma_down parameters for a given timestep in the Euler ancestral scheduler', 'scale a diffusion model input sample by sigma using the GaudiEulerAncestralDiscreteScheduler before calling step', 'perform one denoising step with the GaudiEulerAncestralDiscreteScheduler to predict the previous sample from model output and noise', 'create a GaudiEulerDiscreteScheduler instance with custom beta schedule and prediction type for HPU-optimized diffusion', 'get the current sigma and next sigma values from a GaudiEulerDiscreteScheduler for the active step index', 'roll the sigma parameter tensors forward by one step in a GaudiEulerDiscreteScheduler to advance timesteps', 'step a GaudiEulerDiscreteScheduler to predict the denoised sample from model output and current timestep', 'create a GaudiFlowMatchEulerDiscreteScheduler instance for use with Gaudi lazy mode diffusion pipelines', 'use the index_for_timestep method to find the position of a timestep in the schedule', 'override the base FlowMatchEulerDiscreteScheduler with the Gaudi-specific version for lazy mode support', "get the index of a given timestep within the scheduler's timesteps array", 'handle Gaudi lazy mode by using the custom index_for_timestep override in the scheduler']
```

Usage

```
{'create_gaudi_euler_scheduler': 'create a GaudiEulerDiscreteScheduler instance with custom beta schedule and prediction type for HPU-optimized diffusion', 'reset_timestep_dependent_params': 'reset the timestep-dependent sigma parameters in a GaudiEulerDiscreteScheduler to clear cached sigma lists', 'get_params_sigma': 'get the current sigma and next sigma values from a GaudiEulerDiscreteScheduler for the active step index', 'roll_params_sigma': 'roll the sigma parameter tensors forward by one step in a GaudiEulerDiscreteScheduler to advance timesteps', 'step_denoise_sample': 'step a GaudiEulerDiscreteScheduler to predict the denoised sample from model output and current timestep'}
```

## File: huggingface_optimum-habana/optimum/habana/diffusers/schedulers/scheduling_flow_mactch_euler_discrete.py

Prompts

```
['create a GaudiDDIMScheduler instance optimized for Gaudi with custom beta schedule and prediction type', 'run a single DDIM denoising step using the GaudiDDIMScheduler to get the previous sample', 'add Gaussian noise to original samples at specified timesteps using the GaudiDDIMScheduler', 'reset the timestep-dependent parameters in GaudiDDIMScheduler to reinitialize alpha and variance lists', 'roll the time-dependent parameter tensors in GaudiDDIMScheduler to advance to the next timestep', 'create a GaudiEulerAncestralDiscreteScheduler instance with custom beta_start, beta_end, and prediction_type for HPU-optimized diffusion', 'reset the timestep-dependent sigma parameters in a GaudiEulerAncestralDiscreteScheduler to prepare for a new denoising run', 'get the current sigma, sigma_up, and sigma_down parameters for a given timestep in the Euler ancestral scheduler', 'scale a diffusion model input sample by sigma using the GaudiEulerAncestralDiscreteScheduler before calling step', 'perform one denoising step with the GaudiEulerAncestralDiscreteScheduler to predict the previous sample from model output and noise', 'create a GaudiEulerDiscreteScheduler instance with custom beta schedule and prediction type for HPU-optimized diffusion', 'get the current sigma and next sigma values from a GaudiEulerDiscreteScheduler for the active step index', 'roll the sigma parameter tensors forward by one step in a GaudiEulerDiscreteScheduler to advance timesteps', 'step a GaudiEulerDiscreteScheduler to predict the denoised sample from model output and current timestep', 'create a GaudiFlowMatchEulerDiscreteScheduler instance for use with Gaudi lazy mode diffusion pipelines', 'use the index_for_timestep method to find the position of a timestep in the schedule', 'override the base FlowMatchEulerDiscreteScheduler with the Gaudi-specific version for lazy mode support', "get the index of a given timestep within the scheduler's timesteps array", 'handle Gaudi lazy mode by using the custom index_for_timestep override in the scheduler']
```

Usage

```
{'create_gaudi_flow_match_scheduler': 'create a GaudiFlowMatchEulerDiscreteScheduler instance for use with Gaudi lazy mode diffusion pipelines', 'use_index_for_timestep': 'use the index_for_timestep method to find the position of a timestep in the schedule', 'override_flow_match_scheduler': 'override the base FlowMatchEulerDiscreteScheduler with the Gaudi-specific version for lazy mode support', 'get_timestep_index': "get the index of a given timestep within the scheduler's timesteps array", 'handle_gaudi_lazy_mode': 'handle Gaudi lazy mode by using the custom index_for_timestep override in the scheduler'}
```


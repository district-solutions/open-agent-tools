# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/samplers/ddim.py

Prompts

```
['build a DDIModule with a model, schedule, and predictor for fast denoising diffusion sampling', 'create a function to denoise corrupted data by one diffusion step using DDIModule remove_noise', 'run the DDIModule generator to iteratively yield denoised tensors across eval steps', 'test the DDIModule forward pass in training mode with a timestep and conditional inputs', 'review the DDIModule eta parameter and its effect on stochastic noise scaling in Equation 12', 'build a DDPModule wrapping a neural network with a DiscreteGaussianSchedule and Predictor for denoising diffusion', 'create a forward pass on DDPModule in training mode with timestep and conditional inputs', 'run DDPModule forward in eval mode to sample from the full diffusion schedule', 'test the predict_parameters method to compute mean and log_variance for a diffusion step', 'review the remove_noise method that denoises corrupted data by one diffusion step', 'build a diffusion sampler that applies the learned denoising function via forward pass', 'create a generator that steps through each denoising step for a diffusion model', 'test the Sampler forward method with corrupted data and optional timestep inputs', 'review the Sampler Protocol class and its abstract generator and forward methods', 'refactor the Sampler to customize eval_steps tensor for denoising iterations']
```

Usage

```
{'build_ddi_module': 'build a DDIModule with a model, schedule, and predictor for fast denoising diffusion sampling', 'create_remove_noise': 'create a function to denoise corrupted data by one diffusion step using DDIModule remove_noise', 'run_generator': 'run the DDIModule generator to iteratively yield denoised tensors across eval steps', 'test_forward': 'test the DDIModule forward pass in training mode with a timestep and conditional inputs', 'review_ddi_module_eta': 'review the DDIModule eta parameter and its effect on stochastic noise scaling in Equation 12'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/samplers/ddpm.py

Prompts

```
['build a DDIModule with a model, schedule, and predictor for fast denoising diffusion sampling', 'create a function to denoise corrupted data by one diffusion step using DDIModule remove_noise', 'run the DDIModule generator to iteratively yield denoised tensors across eval steps', 'test the DDIModule forward pass in training mode with a timestep and conditional inputs', 'review the DDIModule eta parameter and its effect on stochastic noise scaling in Equation 12', 'build a DDPModule wrapping a neural network with a DiscreteGaussianSchedule and Predictor for denoising diffusion', 'create a forward pass on DDPModule in training mode with timestep and conditional inputs', 'run DDPModule forward in eval mode to sample from the full diffusion schedule', 'test the predict_parameters method to compute mean and log_variance for a diffusion step', 'review the remove_noise method that denoises corrupted data by one diffusion step', 'build a diffusion sampler that applies the learned denoising function via forward pass', 'create a generator that steps through each denoising step for a diffusion model', 'test the Sampler forward method with corrupted data and optional timestep inputs', 'review the Sampler Protocol class and its abstract generator and forward methods', 'refactor the Sampler to customize eval_steps tensor for denoising iterations']
```

Usage

```
{'build_DDPMModule': 'build a DDPModule wrapping a neural network with a DiscreteGaussianSchedule and Predictor for denoising diffusion', 'create_DDPMModule_forward_training': 'create a forward pass on DDPModule in training mode with timestep and conditional inputs', 'run_DDPMModule_forward_sampling': 'run DDPModule forward in eval mode to sample from the full diffusion schedule', 'test_DDPMModule_predict_parameters': 'test the predict_parameters method to compute mean and log_variance for a diffusion step', 'review_DDPMModule_remove_noise': 'review the remove_noise method that denoises corrupted data by one diffusion step'}
```

## File: facebookresearch_multimodal/torchmultimodal/diffusion_labs/samplers/sampler.py

Prompts

```
['build a DDIModule with a model, schedule, and predictor for fast denoising diffusion sampling', 'create a function to denoise corrupted data by one diffusion step using DDIModule remove_noise', 'run the DDIModule generator to iteratively yield denoised tensors across eval steps', 'test the DDIModule forward pass in training mode with a timestep and conditional inputs', 'review the DDIModule eta parameter and its effect on stochastic noise scaling in Equation 12', 'build a DDPModule wrapping a neural network with a DiscreteGaussianSchedule and Predictor for denoising diffusion', 'create a forward pass on DDPModule in training mode with timestep and conditional inputs', 'run DDPModule forward in eval mode to sample from the full diffusion schedule', 'test the predict_parameters method to compute mean and log_variance for a diffusion step', 'review the remove_noise method that denoises corrupted data by one diffusion step', 'build a diffusion sampler that applies the learned denoising function via forward pass', 'create a generator that steps through each denoising step for a diffusion model', 'test the Sampler forward method with corrupted data and optional timestep inputs', 'review the Sampler Protocol class and its abstract generator and forward methods', 'refactor the Sampler to customize eval_steps tensor for denoising iterations']
```

Usage

```
{'build_sampler_forward': 'build a diffusion sampler that applies the learned denoising function via forward pass', 'create_sampler_generator': 'create a generator that steps through each denoising step for a diffusion model', 'test_sampler_forward': 'test the Sampler forward method with corrupted data and optional timestep inputs', 'review_sampler_protocol': 'review the Sampler Protocol class and its abstract generator and forward methods', 'refactor_sampler_eval_steps': 'refactor the Sampler to customize eval_steps tensor for denoising iterations'}
```


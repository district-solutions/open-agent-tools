# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/models/diffusion/dpm_solver/dpm_solver.py

Prompts

```
['create a NoiseScheduleVP for discrete-time diffusion models using betas or alphas_cumprod tensors', 'build a model wrapper function for noise prediction with classifier-free guidance support', 'sample from a diffusion model using DPM_Solver with singlestep or multistep methods', 'run the adaptive step size DPM-Solver with configurable absolute and relative tolerances', 'review the DPM_Solver singlestep or multistep update methods for first, second, or third order solvers', 'build a DPMSolverSampler instance from a diffusion model to prepare DPM-Solver sampling', 'sample images using DPMSolverSampler with classifier-free guidance and conditioning tokens', 'register the model alphas_cumprod as a CUDA tensor buffer on the sampler', 'review the DPMSolverSampler sample method for multistep DPM-Solver image generation', 'refactor the DPMSolverSampler to customize unconditional guidance scale and conditioning']
```

Usage

```
{'create_noise_schedule_vp': 'create a NoiseScheduleVP for discrete-time diffusion models using betas or alphas_cumprod tensors', 'build_model_wrapper': 'build a model wrapper function for noise prediction with classifier-free guidance support', 'sample_dpm_solver': 'sample from a diffusion model using DPM_Solver with singlestep or multistep methods', 'run_dpm_solver_adaptive': 'run the adaptive step size DPM-Solver with configurable absolute and relative tolerances', 'review_dpm_solver_update': 'review the DPM_Solver singlestep or multistep update methods for first, second, or third order solvers'}
```

## File: facebookresearch_metaseq/third_party/stable-diffusion/ldm/models/diffusion/dpm_solver/sampler.py

Prompts

```
['create a NoiseScheduleVP for discrete-time diffusion models using betas or alphas_cumprod tensors', 'build a model wrapper function for noise prediction with classifier-free guidance support', 'sample from a diffusion model using DPM_Solver with singlestep or multistep methods', 'run the adaptive step size DPM-Solver with configurable absolute and relative tolerances', 'review the DPM_Solver singlestep or multistep update methods for first, second, or third order solvers', 'build a DPMSolverSampler instance from a diffusion model to prepare DPM-Solver sampling', 'sample images using DPMSolverSampler with classifier-free guidance and conditioning tokens', 'register the model alphas_cumprod as a CUDA tensor buffer on the sampler', 'review the DPMSolverSampler sample method for multistep DPM-Solver image generation', 'refactor the DPMSolverSampler to customize unconditional guidance scale and conditioning']
```

Usage

```
{'build_dpm_solver_sampler': 'build a DPMSolverSampler instance from a diffusion model to prepare DPM-Solver sampling', 'sample_with_conditioning': 'sample images using DPMSolverSampler with classifier-free guidance and conditioning tokens', 'register_buffer_alphas': 'register the model alphas_cumprod as a CUDA tensor buffer on the sampler', 'review_dpmsolversampler_sample': 'review the DPMSolverSampler sample method for multistep DPM-Solver image generation', 'refactor_dpmsolversampler_guidance': 'refactor the DPMSolverSampler to customize unconditional guidance scale and conditioning'}
```


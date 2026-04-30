# Agent Python Tools

- repo: OpenBMB/VoxCPM
- repo_uri: https://github.com/OpenBMB/VoxCPM

## File: OpenBMB_VoxCPM/src/voxcpm/modules/locdit/local_dit.py

Prompts

```
['create a SinusoidalPosEmb module with even dimension for diffusion timestep encoding', 'build a TimestepEmbedding layer with linear projections and SiLU activation for time embedding', 'test the VoxCPMLocDiT forward pass with input tensors, timestep, and condition tensors', 'refactor the VoxCPMLocDiT model to use a different config or channel dimension', 'review the VoxCPMLocDiT diffusion model with Transformer backbone architecture', 'create a local diffusion transformer model with MiniCPM4 backbone for voxel generation', 'review the SinusoidalPosEmb forward method for generating positional encodings from scalar timesteps', 'create a CfmConfig instance with solver, t_scheduler, and cfg rate parameters for CFM inference', 'build a UnifiedCFM module with in_channels, CfmConfig params, and VoxCPMLocDiT estimator for diffusion sampling', 'run UnifiedCFM forward inference with mu tensor, timestep count, patch size, and conditioning tensor', 'test UnifiedCFM compute_loss to calculate training loss with optional target mask and adaptive weighting', 'summarize UnifiedCFM solve_euler method that performs Euler integration with classifier-free guidance']
```

Usage

```
{'create_SinusoidalPosEmb': 'create a SinusoidalPosEmb module with even dimension for diffusion timestep encoding', 'build_TimestepEmbedding': 'build a TimestepEmbedding layer with linear projections and SiLU activation for time embedding', 'test_VoxCPMLocDiT_forward': 'test the VoxCPMLocDiT forward pass with input tensors, timestep, and condition tensors', 'refactor_VoxCPMLocDiT': 'refactor the VoxCPMLocDiT model to use a different config or channel dimension', 'review_VoxCPMLocDiT': 'review the VoxCPMLocDiT diffusion model with Transformer backbone architecture'}
```

## File: OpenBMB_VoxCPM/src/voxcpm/modules/locdit/local_dit_v2.py

Prompts

```
['create a SinusoidalPosEmb module with even dimension for diffusion timestep encoding', 'build a TimestepEmbedding layer with linear projections and SiLU activation for time embedding', 'test the VoxCPMLocDiT forward pass with input tensors, timestep, and condition tensors', 'refactor the VoxCPMLocDiT model to use a different config or channel dimension', 'review the VoxCPMLocDiT diffusion model with Transformer backbone architecture', 'create a local diffusion transformer model with MiniCPM4 backbone for voxel generation', 'review the SinusoidalPosEmb forward method for generating positional encodings from scalar timesteps', 'create a CfmConfig instance with solver, t_scheduler, and cfg rate parameters for CFM inference', 'build a UnifiedCFM module with in_channels, CfmConfig params, and VoxCPMLocDiT estimator for diffusion sampling', 'run UnifiedCFM forward inference with mu tensor, timestep count, patch size, and conditioning tensor', 'test UnifiedCFM compute_loss to calculate training loss with optional target mask and adaptive weighting', 'summarize UnifiedCFM solve_euler method that performs Euler integration with classifier-free guidance']
```

Usage

```
{'create_SinusoidalPosEmb': 'create a sinusoidal positional embedding module for diffusion timestep encoding', 'build_TimestepEmbedding': 'build a two-layer timestep embedding MLP with SiLU activation', 'create_VoxCPMLocDiT': 'create a local diffusion transformer model with MiniCPM4 backbone for voxel generation', 'test_VoxCPMLocDiT_forward': 'test the VoxCPMLocDiT forward pass with input tensor, hidden embedding, timestep, condition, and delta time', 'review_SinusoidalPosEmb_forward': 'review the SinusoidalPosEmb forward method for generating positional encodings from scalar timesteps'}
```

## File: OpenBMB_VoxCPM/src/voxcpm/modules/locdit/unified_cfm.py

Prompts

```
['create a SinusoidalPosEmb module with even dimension for diffusion timestep encoding', 'build a TimestepEmbedding layer with linear projections and SiLU activation for time embedding', 'test the VoxCPMLocDiT forward pass with input tensors, timestep, and condition tensors', 'refactor the VoxCPMLocDiT model to use a different config or channel dimension', 'review the VoxCPMLocDiT diffusion model with Transformer backbone architecture', 'create a local diffusion transformer model with MiniCPM4 backbone for voxel generation', 'review the SinusoidalPosEmb forward method for generating positional encodings from scalar timesteps', 'create a CfmConfig instance with solver, t_scheduler, and cfg rate parameters for CFM inference', 'build a UnifiedCFM module with in_channels, CfmConfig params, and VoxCPMLocDiT estimator for diffusion sampling', 'run UnifiedCFM forward inference with mu tensor, timestep count, patch size, and conditioning tensor', 'test UnifiedCFM compute_loss to calculate training loss with optional target mask and adaptive weighting', 'summarize UnifiedCFM solve_euler method that performs Euler integration with classifier-free guidance']
```

Usage

```
{'create_CfmConfig': 'create a CfmConfig instance with solver, t_scheduler, and cfg rate parameters for CFM inference', 'build_UnifiedCFM': 'build a UnifiedCFM module with in_channels, CfmConfig params, and VoxCPMLocDiT estimator for diffusion sampling', 'run_UnifiedCFM_forward': 'run UnifiedCFM forward inference with mu tensor, timestep count, patch size, and conditioning tensor', 'test_UnifiedCFM_compute_loss': 'test UnifiedCFM compute_loss to calculate training loss with optional target mask and adaptive weighting', 'summarize_UnifiedCFM_solve_euler': 'summarize UnifiedCFM solve_euler method that performs Euler integration with classifier-free guidance'}
```


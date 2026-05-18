# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/projects/bits_back_diffusion/bits_back_diffusion/codec.py

Prompts

```
['create a DiffusionModel wrapping a PyTorch denoising model and GaussianDiffusion for hierarchical latent variable inference', 'encode discrete data using BitsBackCodec by pushing quantized data through the BB-ANS arithmetic coding pipeline', 'decode data from a BitsBackCodec message by popping discrete values through the BB-ANS arithmetic coding pipeline', 'quantize floating point data arrays to integer values for lossless arithmetic coding with BitsBackCodec', 'build a craystack codec for diagonal Gaussian data discretized with uniform bins and extended boundary bins', 'create a SpacedDiffusion object with configurable steps, noise schedule, and timestep respacing for diffusion models', 'create a subset of diffusion timesteps from section counts or DDIM/VLB respacing strategies', 'parse the training step number from a model or EMA checkpoint filename', 'create a Plotly figure showing mean, standard deviation, and range of data over training steps', 'set up a diffusion model experiment with model, diffusion process, and dataloader for training or evaluation']
```

Usage

```
{'create_DiffusionModel': 'create a DiffusionModel wrapping a PyTorch denoising model and GaussianDiffusion for hierarchical latent variable inference', 'encode_BitsBackCodec': 'encode discrete data using BitsBackCodec by pushing quantized data through the BB-ANS arithmetic coding pipeline', 'decode_BitsBackCodec': 'decode data from a BitsBackCodec message by popping discrete values through the BB-ANS arithmetic coding pipeline', 'quantize_BitsBackCodec': 'quantize floating point data arrays to integer values for lossless arithmetic coding with BitsBackCodec', 'build_diag_gaussian_unif_bins': 'build a craystack codec for diagonal Gaussian data discretized with uniform bins and extended boundary bins'}
```

## File: facebookresearch_neuralcompression/projects/bits_back_diffusion/bits_back_diffusion/script_util.py

Prompts

```
['create a DiffusionModel wrapping a PyTorch denoising model and GaussianDiffusion for hierarchical latent variable inference', 'encode discrete data using BitsBackCodec by pushing quantized data through the BB-ANS arithmetic coding pipeline', 'decode data from a BitsBackCodec message by popping discrete values through the BB-ANS arithmetic coding pipeline', 'quantize floating point data arrays to integer values for lossless arithmetic coding with BitsBackCodec', 'build a craystack codec for diagonal Gaussian data discretized with uniform bins and extended boundary bins', 'create a SpacedDiffusion object with configurable steps, noise schedule, and timestep respacing for diffusion models', 'create a subset of diffusion timesteps from section counts or DDIM/VLB respacing strategies', 'parse the training step number from a model or EMA checkpoint filename', 'create a Plotly figure showing mean, standard deviation, and range of data over training steps', 'set up a diffusion model experiment with model, diffusion process, and dataloader for training or evaluation']
```

Usage

```
{'create_gaussian_diffusion': 'create a SpacedDiffusion object with configurable steps, noise schedule, and timestep respacing for diffusion models', 'space_timesteps': 'create a subset of diffusion timesteps from section counts or DDIM/VLB respacing strategies', 'parse_resume_step_from_filename': 'parse the training step number from a model or EMA checkpoint filename', 'plot_evolution': 'create a Plotly figure showing mean, standard deviation, and range of data over training steps', 'setup': 'set up a diffusion model experiment with model, diffusion process, and dataloader for training or evaluation'}
```


# Agent Python Tools

- repo: facebookresearch/4dgt
- repo_uri: https://github.com/facebookresearch/4dgt

## File: facebookresearch_4dgt/tlod/models/blocks.py

Prompts

```
['build a PyTorch MLP with configurable depth, hidden dim, activation layer, and weight normalization', 'create an LlamaRMSNorm layer equivalent to T5LayerNorm for normalizing hidden states in a transformer model', 'create a RotaryPositionEmbedding module that applies sinusoidal rotation to transformer query and key tensors', 'create a RotaryPositionEmbedding3D module that applies rotary position embeddings along depth, height, and width axes', 'create a SelfAttentionBlock with attention, MLP, layer norm, and optional rotary position embedding for transformer architectures', 'build a GaussianModel from config with an image encoder and renderer module', 'run the GaussianModel forward pass with input images, timestamps, intrinsics, and extrinsics', 'render 3D Gaussian splatting parameters into images using camera intrinsics and extrinsics', 'create a GaussianModelConfig with image encoder and renderer configuration dictionaries', 'build a GaussianModelModule instance from config kwargs or pretrained checkpoint', 'convert a covariance tensor to diffusion time step dt using a marginal threshold', 'convert a diffusion time step dt back to its corresponding covariance tensor', 'convert a spatial radius value to its equivalent Gaussian sigma using a cutoff threshold', 'convert a Gaussian sigma value back to its equivalent spatial radius using a cutoff threshold', "review the geometry module's four diffusion parameter conversion functions for correctness and edge cases", 'zero initialize all parameters of a PyTorch nn.Module and return the module', 'initialize a PyTorch tensor with a truncated normal distribution between bounds a and b', 'review the zero_module function that zeros all parameters of a given PyTorch module', 'review the trunc_normal_ function that initializes tensors with a truncated normal distribution', 'summarize the PyTorch utility functions for module zero initialization and truncated normal tensor initialization']
```

Usage

```
{'build_pytorch_mlp': 'build a PyTorch MLP with configurable depth, hidden dim, activation layer, and weight normalization', 'create_LlamaRMSNorm': 'create an LlamaRMSNorm layer equivalent to T5LayerNorm for normalizing hidden states in a transformer model', 'create_RotaryPositionEmbedding': 'create a RotaryPositionEmbedding module that applies sinusoidal rotation to transformer query and key tensors', 'create_RotaryPositionEmbedding3D': 'create a RotaryPositionEmbedding3D module that applies rotary position embeddings along depth, height, and width axes', 'create_SelfAttentionBlock': 'create a SelfAttentionBlock with attention, MLP, layer norm, and optional rotary position embedding for transformer architectures'}
```

## File: facebookresearch_4dgt/tlod/models/gaussian_model.py

Prompts

```
['build a PyTorch MLP with configurable depth, hidden dim, activation layer, and weight normalization', 'create an LlamaRMSNorm layer equivalent to T5LayerNorm for normalizing hidden states in a transformer model', 'create a RotaryPositionEmbedding module that applies sinusoidal rotation to transformer query and key tensors', 'create a RotaryPositionEmbedding3D module that applies rotary position embeddings along depth, height, and width axes', 'create a SelfAttentionBlock with attention, MLP, layer norm, and optional rotary position embedding for transformer architectures', 'build a GaussianModel from config with an image encoder and renderer module', 'run the GaussianModel forward pass with input images, timestamps, intrinsics, and extrinsics', 'render 3D Gaussian splatting parameters into images using camera intrinsics and extrinsics', 'create a GaussianModelConfig with image encoder and renderer configuration dictionaries', 'build a GaussianModelModule instance from config kwargs or pretrained checkpoint', 'convert a covariance tensor to diffusion time step dt using a marginal threshold', 'convert a diffusion time step dt back to its corresponding covariance tensor', 'convert a spatial radius value to its equivalent Gaussian sigma using a cutoff threshold', 'convert a Gaussian sigma value back to its equivalent spatial radius using a cutoff threshold', "review the geometry module's four diffusion parameter conversion functions for correctness and edge cases", 'zero initialize all parameters of a PyTorch nn.Module and return the module', 'initialize a PyTorch tensor with a truncated normal distribution between bounds a and b', 'review the zero_module function that zeros all parameters of a given PyTorch module', 'review the trunc_normal_ function that initializes tensors with a truncated normal distribution', 'summarize the PyTorch utility functions for module zero initialization and truncated normal tensor initialization']
```

Usage

```
{'build_gaussian_model': 'build a GaussianModel from config with an image encoder and renderer module', 'run_gaussian_model_forward': 'run the GaussianModel forward pass with input images, timestamps, intrinsics, and extrinsics', 'render_gaussian_parameters': 'render 3D Gaussian splatting parameters into images using camera intrinsics and extrinsics', 'create_gaussian_model_config': 'create a GaussianModelConfig with image encoder and renderer configuration dictionaries', 'build_gaussian_model_module': 'build a GaussianModelModule instance from config kwargs or pretrained checkpoint'}
```

## File: facebookresearch_4dgt/tlod/models/geometry.py

Prompts

```
['build a PyTorch MLP with configurable depth, hidden dim, activation layer, and weight normalization', 'create an LlamaRMSNorm layer equivalent to T5LayerNorm for normalizing hidden states in a transformer model', 'create a RotaryPositionEmbedding module that applies sinusoidal rotation to transformer query and key tensors', 'create a RotaryPositionEmbedding3D module that applies rotary position embeddings along depth, height, and width axes', 'create a SelfAttentionBlock with attention, MLP, layer norm, and optional rotary position embedding for transformer architectures', 'build a GaussianModel from config with an image encoder and renderer module', 'run the GaussianModel forward pass with input images, timestamps, intrinsics, and extrinsics', 'render 3D Gaussian splatting parameters into images using camera intrinsics and extrinsics', 'create a GaussianModelConfig with image encoder and renderer configuration dictionaries', 'build a GaussianModelModule instance from config kwargs or pretrained checkpoint', 'convert a covariance tensor to diffusion time step dt using a marginal threshold', 'convert a diffusion time step dt back to its corresponding covariance tensor', 'convert a spatial radius value to its equivalent Gaussian sigma using a cutoff threshold', 'convert a Gaussian sigma value back to its equivalent spatial radius using a cutoff threshold', "review the geometry module's four diffusion parameter conversion functions for correctness and edge cases", 'zero initialize all parameters of a PyTorch nn.Module and return the module', 'initialize a PyTorch tensor with a truncated normal distribution between bounds a and b', 'review the zero_module function that zeros all parameters of a given PyTorch module', 'review the trunc_normal_ function that initializes tensors with a truncated normal distribution', 'summarize the PyTorch utility functions for module zero initialization and truncated normal tensor initialization']
```

Usage

```
{'convert_cov_t_to_dt': 'convert a covariance tensor to diffusion time step dt using a marginal threshold', 'convert_dt_to_cov_t': 'convert a diffusion time step dt back to its corresponding covariance tensor', 'convert_radius_to_sigma': 'convert a spatial radius value to its equivalent Gaussian sigma using a cutoff threshold', 'convert_sigma_to_radius': 'convert a Gaussian sigma value back to its equivalent spatial radius using a cutoff threshold', 'review_geometry_conversions': "review the geometry module's four diffusion parameter conversion functions for correctness and edge cases"}
```

## File: facebookresearch_4dgt/tlod/models/utils.py

Prompts

```
['build a PyTorch MLP with configurable depth, hidden dim, activation layer, and weight normalization', 'create an LlamaRMSNorm layer equivalent to T5LayerNorm for normalizing hidden states in a transformer model', 'create a RotaryPositionEmbedding module that applies sinusoidal rotation to transformer query and key tensors', 'create a RotaryPositionEmbedding3D module that applies rotary position embeddings along depth, height, and width axes', 'create a SelfAttentionBlock with attention, MLP, layer norm, and optional rotary position embedding for transformer architectures', 'build a GaussianModel from config with an image encoder and renderer module', 'run the GaussianModel forward pass with input images, timestamps, intrinsics, and extrinsics', 'render 3D Gaussian splatting parameters into images using camera intrinsics and extrinsics', 'create a GaussianModelConfig with image encoder and renderer configuration dictionaries', 'build a GaussianModelModule instance from config kwargs or pretrained checkpoint', 'convert a covariance tensor to diffusion time step dt using a marginal threshold', 'convert a diffusion time step dt back to its corresponding covariance tensor', 'convert a spatial radius value to its equivalent Gaussian sigma using a cutoff threshold', 'convert a Gaussian sigma value back to its equivalent spatial radius using a cutoff threshold', "review the geometry module's four diffusion parameter conversion functions for correctness and edge cases", 'zero initialize all parameters of a PyTorch nn.Module and return the module', 'initialize a PyTorch tensor with a truncated normal distribution between bounds a and b', 'review the zero_module function that zeros all parameters of a given PyTorch module', 'review the trunc_normal_ function that initializes tensors with a truncated normal distribution', 'summarize the PyTorch utility functions for module zero initialization and truncated normal tensor initialization']
```

Usage

```
{'zero_module': 'zero initialize all parameters of a PyTorch nn.Module and return the module', 'trunc_normal_': 'initialize a PyTorch tensor with a truncated normal distribution between bounds a and b', 'review_zero_module': 'review the zero_module function that zeros all parameters of a given PyTorch module', 'review_trunc_normal_': 'review the trunc_normal_ function that initializes tensors with a truncated normal distribution', 'summarize_utils': 'summarize the PyTorch utility functions for module zero initialization and truncated normal tensor initialization'}
```


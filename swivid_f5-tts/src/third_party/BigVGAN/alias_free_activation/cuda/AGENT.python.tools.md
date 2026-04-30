# Agent Python Tools

- repo: swivid/f5-tts
- repo_uri: https://github.com/swivid/f5-tts

## File: swivid_f5-tts/src/third_party/BigVGAN/alias_free_activation/cuda/activation1d.py

Prompts

```
['create an Activation1d module with activation function, upsampling ratio, and downsampling ratio', 'use FusedAntiAliasActivation with input tensors, up/down filters, and alpha/beta parameters', 'configure Activation1d to use fused CUDA kernel for upsampling, activation, and downsampling', 'configure Activation1d to use PyTorch-based upsampling, activation, and downsampling without fused kernel', 'handle Snake activation parameters using alpha data for both alpha and beta in Activation1d', 'build the anti-alias activation CUDA extension kernel using PyTorch cpp_extension', 'run the load function to compile and return the anti-alias activation CUDA module', 'test the _get_cuda_bare_metal_version function to query nvcc for the installed CUDA version', 'review the load function that compiles fused anti-alias activation CUDA kernels', 'summarize the load function that builds and loads the BigVGAN anti-alias activation CUDA extension']
```

Usage

```
{'create_Activation1d': 'create an Activation1d module with activation function, upsampling ratio, and downsampling ratio', 'use_FusedAntiAliasActivation': 'use FusedAntiAliasActivation with input tensors, up/down filters, and alpha/beta parameters', 'configure_Activation1d_fused': 'configure Activation1d to use fused CUDA kernel for upsampling, activation, and downsampling', 'configure_Activation1d_unfused': 'configure Activation1d to use PyTorch-based upsampling, activation, and downsampling without fused kernel', 'handle_Snake_activation': 'handle Snake activation parameters using alpha data for both alpha and beta in Activation1d'}
```

## File: swivid_f5-tts/src/third_party/BigVGAN/alias_free_activation/cuda/load.py

Prompts

```
['create an Activation1d module with activation function, upsampling ratio, and downsampling ratio', 'use FusedAntiAliasActivation with input tensors, up/down filters, and alpha/beta parameters', 'configure Activation1d to use fused CUDA kernel for upsampling, activation, and downsampling', 'configure Activation1d to use PyTorch-based upsampling, activation, and downsampling without fused kernel', 'handle Snake activation parameters using alpha data for both alpha and beta in Activation1d', 'build the anti-alias activation CUDA extension kernel using PyTorch cpp_extension', 'run the load function to compile and return the anti-alias activation CUDA module', 'test the _get_cuda_bare_metal_version function to query nvcc for the installed CUDA version', 'review the load function that compiles fused anti-alias activation CUDA kernels', 'summarize the load function that builds and loads the BigVGAN anti-alias activation CUDA extension']
```

Usage

```
{'build_anti_alias_activation_cuda': 'build the anti-alias activation CUDA extension kernel using PyTorch cpp_extension', 'run_load_cuda_extension': 'run the load function to compile and return the anti-alias activation CUDA module', 'test_get_cuda_bare_metal_version': 'test the _get_cuda_bare_metal_version function to query nvcc for the installed CUDA version', 'review_load_cuda_extension': 'review the load function that compiles fused anti-alias activation CUDA kernels', 'summarize_load_cuda_extension': 'summarize the load function that builds and loads the BigVGAN anti-alias activation CUDA extension'}
```


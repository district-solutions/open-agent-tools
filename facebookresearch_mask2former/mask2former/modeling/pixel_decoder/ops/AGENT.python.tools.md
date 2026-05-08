# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former/modeling/pixel_decoder/ops/setup.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension module from source C++ and CUDA files', 'run the setup.py to install the MultiScaleDeformableAttention package with torch and torchvision requirements', 'test the get_extensions function to verify CUDA extension is configured when CUDA is available', 'review the get_extensions function to understand how it discovers and configures C++ and CUDA source files', 'refactor the get_extensions function to gracefully fall back to CPU-only build when CUDA is unavailable', 'test the MSDeformAttnFunction forward pass using double precision tensors and compare with PyTorch reference', 'test the MSDeformAttnFunction forward pass using float precision tensors and compare with PyTorch reference', 'test the MSDeformAttnFunction numerical gradients for value, sampling locations, and attention weights', 'review the ms_deform_attn_core_pytorch function used as a reference implementation for multi-scale deformable attention', 'review the MSDeformAttnFunction CUDA autograd function for multi-scale deformable attention computation']
```

Usage

```
{'build_extension_multiscale_deformable_attention': 'build the MultiScaleDeformableAttention CUDA extension module from source C++ and CUDA files', 'run_setup_install': 'run the setup.py to install the MultiScaleDeformableAttention package with torch and torchvision requirements', 'test_get_extensions_cuda': 'test the get_extensions function to verify CUDA extension is configured when CUDA is available', 'review_get_extensions': 'review the get_extensions function to understand how it discovers and configures C++ and CUDA source files', 'refactor_get_extensions_cpu_fallback': 'refactor the get_extensions function to gracefully fall back to CPU-only build when CUDA is unavailable'}
```

## File: facebookresearch_mask2former/mask2former/modeling/pixel_decoder/ops/test.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension module from source C++ and CUDA files', 'run the setup.py to install the MultiScaleDeformableAttention package with torch and torchvision requirements', 'test the get_extensions function to verify CUDA extension is configured when CUDA is available', 'review the get_extensions function to understand how it discovers and configures C++ and CUDA source files', 'refactor the get_extensions function to gracefully fall back to CPU-only build when CUDA is unavailable', 'test the MSDeformAttnFunction forward pass using double precision tensors and compare with PyTorch reference', 'test the MSDeformAttnFunction forward pass using float precision tensors and compare with PyTorch reference', 'test the MSDeformAttnFunction numerical gradients for value, sampling locations, and attention weights', 'review the ms_deform_attn_core_pytorch function used as a reference implementation for multi-scale deformable attention', 'review the MSDeformAttnFunction CUDA autograd function for multi-scale deformable attention computation']
```

Usage

```
{'test_ms_deform_attn_forward_double': 'test the MSDeformAttnFunction forward pass using double precision tensors and compare with PyTorch reference', 'test_ms_deform_attn_forward_float': 'test the MSDeformAttnFunction forward pass using float precision tensors and compare with PyTorch reference', 'test_ms_deform_attn_gradient_numerical': 'test the MSDeformAttnFunction numerical gradients for value, sampling locations, and attention weights', 'review_ms_deform_attn_pytorch_core': 'review the ms_deform_attn_core_pytorch function used as a reference implementation for multi-scale deformable attention', 'review_ms_deform_attn_cuda_function': 'review the MSDeformAttnFunction CUDA autograd function for multi-scale deformable attention computation'}
```


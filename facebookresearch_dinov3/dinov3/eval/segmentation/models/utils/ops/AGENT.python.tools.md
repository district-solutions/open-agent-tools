# Agent Python Tools

- repo: facebookresearch/dinov3
- repo_uri: https://github.com/facebookresearch/dinov3

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/utils/ops/setup.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension using python setup.py build_ext --inplace', 'install the MultiScaleDeformableAttention PyTorch CUDA extension via pip install -e .', 'call get_extensions() to discover and configure CPU and CUDA source files for the extension', 'review the setup.py configuration for the MultiScaleDeformableAttention CUDA extension build', 'refactor the nvcc extra compile args in get_extensions to add or remove CUDA flags', 'test the MSDeformAttnFunction forward pass using double precision and compare with PyTorch reference implementation', 'test the MSDeformAttnFunction forward pass using float precision and compare with PyTorch reference implementation', 'test the MSDeformAttnFunction numerical gradients for value, sampling locations, and attention weights', 'run all MSDeformAttnFunction forward and gradient tests across multiple channel configurations', 'review the ms_deform_attn_core_pytorch reference implementation used for validating CUDA output correctness']
```

Usage

```
{'build_cuda_extension': 'build the MultiScaleDeformableAttention CUDA extension using python setup.py build_ext --inplace', 'install_extension': 'install the MultiScaleDeformableAttention PyTorch CUDA extension via pip install -e .', 'get_extensions': 'call get_extensions() to discover and configure CPU and CUDA source files for the extension', 'review_setup_config': 'review the setup.py configuration for the MultiScaleDeformableAttention CUDA extension build', 'refactor_cuda_compile_args': 'refactor the nvcc extra compile args in get_extensions to add or remove CUDA flags'}
```

## File: facebookresearch_dinov3/dinov3/eval/segmentation/models/utils/ops/test.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension using python setup.py build_ext --inplace', 'install the MultiScaleDeformableAttention PyTorch CUDA extension via pip install -e .', 'call get_extensions() to discover and configure CPU and CUDA source files for the extension', 'review the setup.py configuration for the MultiScaleDeformableAttention CUDA extension build', 'refactor the nvcc extra compile args in get_extensions to add or remove CUDA flags', 'test the MSDeformAttnFunction forward pass using double precision and compare with PyTorch reference implementation', 'test the MSDeformAttnFunction forward pass using float precision and compare with PyTorch reference implementation', 'test the MSDeformAttnFunction numerical gradients for value, sampling locations, and attention weights', 'run all MSDeformAttnFunction forward and gradient tests across multiple channel configurations', 'review the ms_deform_attn_core_pytorch reference implementation used for validating CUDA output correctness']
```

Usage

```
{'test_ms_deform_attn_forward_double': 'test the MSDeformAttnFunction forward pass using double precision and compare with PyTorch reference implementation', 'test_ms_deform_attn_forward_float': 'test the MSDeformAttnFunction forward pass using float precision and compare with PyTorch reference implementation', 'test_ms_deform_attn_gradient_numerical': 'test the MSDeformAttnFunction numerical gradients for value, sampling locations, and attention weights', 'run_ms_deform_attn_tests': 'run all MSDeformAttnFunction forward and gradient tests across multiple channel configurations', 'review_ms_deform_attn_pytorch_core': 'review the ms_deform_attn_core_pytorch reference implementation used for validating CUDA output correctness'}
```


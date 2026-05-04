# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/third_party/Deformable-DETR/models/ops/setup.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension by running pip install from the setup.py directory', 'run get_extensions to discover and configure CPU and CUDA source files for the extension build', 'review the get_extensions function to understand how it conditionally compiles CUDA vs CPU sources', 'refactor the setup.py to support CPU-only builds when CUDA is not available', 'test the extension build process by running python setup.py build_ext --inplace', 'test the CUDA and PyTorch double precision forward pass equality for multi-scale deformable attention', 'test the CUDA and PyTorch float precision forward pass equality for multi-scale deformable attention', 'test the numerical gradient correctness of MSDeformAttnFunction across various channel dimensions', 'run all multi-scale deformable attention forward and gradient validation tests', 'review the MSDeformAttnFunction CUDA implementation against the PyTorch reference implementation']
```

Usage

```
{'build_cuda_extension': 'build the MultiScaleDeformableAttention CUDA extension by running pip install from the setup.py directory', 'run_get_extensions': 'run get_extensions to discover and configure CPU and CUDA source files for the extension build', 'review_get_extensions': 'review the get_extensions function to understand how it conditionally compiles CUDA vs CPU sources', 'refactor_setup': 'refactor the setup.py to support CPU-only builds when CUDA is not available', 'test_extension_build': 'test the extension build process by running python setup.py build_ext --inplace'}
```

## File: facebookresearch_detic/third_party/Deformable-DETR/models/ops/test.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension by running pip install from the setup.py directory', 'run get_extensions to discover and configure CPU and CUDA source files for the extension build', 'review the get_extensions function to understand how it conditionally compiles CUDA vs CPU sources', 'refactor the setup.py to support CPU-only builds when CUDA is not available', 'test the extension build process by running python setup.py build_ext --inplace', 'test the CUDA and PyTorch double precision forward pass equality for multi-scale deformable attention', 'test the CUDA and PyTorch float precision forward pass equality for multi-scale deformable attention', 'test the numerical gradient correctness of MSDeformAttnFunction across various channel dimensions', 'run all multi-scale deformable attention forward and gradient validation tests', 'review the MSDeformAttnFunction CUDA implementation against the PyTorch reference implementation']
```

Usage

```
{'test_ms_deform_attn_forward_double': 'test the CUDA and PyTorch double precision forward pass equality for multi-scale deformable attention', 'test_ms_deform_attn_forward_float': 'test the CUDA and PyTorch float precision forward pass equality for multi-scale deformable attention', 'test_ms_deform_attn_gradient_numerical': 'test the numerical gradient correctness of MSDeformAttnFunction across various channel dimensions', 'run_ms_deform_attn_tests': 'run all multi-scale deformable attention forward and gradient validation tests', 'review_ms_deform_attn_function': 'review the MSDeformAttnFunction CUDA implementation against the PyTorch reference implementation'}
```


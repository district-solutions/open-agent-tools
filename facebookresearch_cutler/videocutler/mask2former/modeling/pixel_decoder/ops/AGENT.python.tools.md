# Agent Python Tools

- repo: facebookresearch/cutler
- repo_uri: https://github.com/facebookresearch/cutler

## File: facebookresearch_cutler/videocutler/mask2former/modeling/pixel_decoder/ops/setup.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension module using python setup.py install', 'review the get_extensions function that detects CUDA availability and configures compile args', 'test the setup.py to verify CUDA extension builds with FORCE_CUDA environment variable', 'refactor get_extensions to support CPU-only builds without requiring CUDA runtime', 'summarize the setup.py configuration for the MultiScaleDeformableAttention PyTorch C++ extension', 'test the CUDA and PyTorch double-precision forward pass equality for multi-scale deformable attention', 'test the CUDA and PyTorch float-precision forward pass equality for multi-scale deformable attention', 'test numerical gradient correctness for multi-scale deformable attention across various channel dimensions', 'review the MSDeformAttnFunction CUDA implementation and its PyTorch fallback for correctness', 'run all multi-scale deformable attention forward and gradient tests end to end']
```

Usage

```
{'build_extension': 'build the MultiScaleDeformableAttention CUDA extension module using python setup.py install', 'review_get_extensions': 'review the get_extensions function that detects CUDA availability and configures compile args', 'test_cuda_extension': 'test the setup.py to verify CUDA extension builds with FORCE_CUDA environment variable', 'refactor_get_extensions': 'refactor get_extensions to support CPU-only builds without requiring CUDA runtime', 'summarize_setup': 'summarize the setup.py configuration for the MultiScaleDeformableAttention PyTorch C++ extension'}
```

## File: facebookresearch_cutler/videocutler/mask2former/modeling/pixel_decoder/ops/test.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension module using python setup.py install', 'review the get_extensions function that detects CUDA availability and configures compile args', 'test the setup.py to verify CUDA extension builds with FORCE_CUDA environment variable', 'refactor get_extensions to support CPU-only builds without requiring CUDA runtime', 'summarize the setup.py configuration for the MultiScaleDeformableAttention PyTorch C++ extension', 'test the CUDA and PyTorch double-precision forward pass equality for multi-scale deformable attention', 'test the CUDA and PyTorch float-precision forward pass equality for multi-scale deformable attention', 'test numerical gradient correctness for multi-scale deformable attention across various channel dimensions', 'review the MSDeformAttnFunction CUDA implementation and its PyTorch fallback for correctness', 'run all multi-scale deformable attention forward and gradient tests end to end']
```

Usage

```
{'test_ms_deform_attn_forward_double': 'test the CUDA and PyTorch double-precision forward pass equality for multi-scale deformable attention', 'test_ms_deform_attn_forward_float': 'test the CUDA and PyTorch float-precision forward pass equality for multi-scale deformable attention', 'test_ms_deform_attn_gradient_numerical': 'test numerical gradient correctness for multi-scale deformable attention across various channel dimensions', 'review_ms_deform_attn_function': 'review the MSDeformAttnFunction CUDA implementation and its PyTorch fallback for correctness', 'run_ms_deform_attn_tests': 'run all multi-scale deformable attention forward and gradient tests end to end'}
```


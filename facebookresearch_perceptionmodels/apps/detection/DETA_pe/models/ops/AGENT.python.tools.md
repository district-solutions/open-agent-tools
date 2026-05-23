# Agent Python Tools

- repo: facebookresearch/perceptionmodels
- repo_uri: https://github.com/facebookresearch/perception_models

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/models/ops/setup.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension by running python setup.py install with CUDA available', 'run python setup.py install to compile and install the MultiScaleDeformableAttention PyTorch extension module', 'call get_extensions to return a list of CUDA extension modules for MultiScaleDeformableAttention', 'review the get_extensions function that detects CUDA availability and configures compile arguments', 'refactor get_extensions to support CPU-only builds instead of raising NotImplementedError when CUDA is unavailable', 'test the CUDA and PyTorch forward pass outputs match using double precision tensors', 'test the CUDA and PyTorch forward pass outputs match using float precision tensors', 'test numerical gradient correctness for MSDeformAttnFunction with configurable channel dimensions', 'review the MSDeformAttnFunction CUDA implementation against the pure PyTorch reference implementation', 'run all forward pass and gradient numerical tests for multi-scale deformable attention']
```

Usage

```
{'build_cuda_extension': 'build the MultiScaleDeformableAttention CUDA extension by running python setup.py install with CUDA available', 'run_setup_install': 'run python setup.py install to compile and install the MultiScaleDeformableAttention PyTorch extension module', 'get_extensions_function': 'call get_extensions to return a list of CUDA extension modules for MultiScaleDeformableAttention', 'review_get_extensions': 'review the get_extensions function that detects CUDA availability and configures compile arguments', 'refactor_get_extensions': 'refactor get_extensions to support CPU-only builds instead of raising NotImplementedError when CUDA is unavailable'}
```

## File: facebookresearch_perceptionmodels/apps/detection/DETA_pe/models/ops/test.py

Prompts

```
['build the MultiScaleDeformableAttention CUDA extension by running python setup.py install with CUDA available', 'run python setup.py install to compile and install the MultiScaleDeformableAttention PyTorch extension module', 'call get_extensions to return a list of CUDA extension modules for MultiScaleDeformableAttention', 'review the get_extensions function that detects CUDA availability and configures compile arguments', 'refactor get_extensions to support CPU-only builds instead of raising NotImplementedError when CUDA is unavailable', 'test the CUDA and PyTorch forward pass outputs match using double precision tensors', 'test the CUDA and PyTorch forward pass outputs match using float precision tensors', 'test numerical gradient correctness for MSDeformAttnFunction with configurable channel dimensions', 'review the MSDeformAttnFunction CUDA implementation against the pure PyTorch reference implementation', 'run all forward pass and gradient numerical tests for multi-scale deformable attention']
```

Usage

```
{'test_ms_deform_attn_forward_double': 'test the CUDA and PyTorch forward pass outputs match using double precision tensors', 'test_ms_deform_attn_forward_float': 'test the CUDA and PyTorch forward pass outputs match using float precision tensors', 'test_ms_deform_attn_gradients': 'test numerical gradient correctness for MSDeformAttnFunction with configurable channel dimensions', 'review_ms_deform_attn_function': 'review the MSDeformAttnFunction CUDA implementation against the pure PyTorch reference implementation', 'run_deformable_attn_tests': 'run all forward pass and gradient numerical tests for multi-scale deformable attention'}
```


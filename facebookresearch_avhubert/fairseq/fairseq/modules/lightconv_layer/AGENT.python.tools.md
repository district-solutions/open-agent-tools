# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/modules/lightconv_layer/cuda_function_gen.py

Prompts

```
['run gen_forward to generate the lightconv_cuda_forward.cu CUDA source file', 'run gen_backward to generate the lightconv_cuda_backward.cu CUDA source file', 'run the main entry point to generate both forward and backward CUDA files', 'review gen_forward to understand how it generates templated CUDA kernel dispatch code', 'review gen_backward to understand how it generates weight gradient computation kernels', 'build a LightconvLayer module with configurable kernel size, num heads, and weight softmax for sequence modeling', 'create a custom PyTorch autograd Function wrapping lightconv CUDA forward and backward kernels', 'test the LightconvLayer forward pass with and without incremental state for training and inference modes', 'review the LightconvLayer incremental state management methods for buffer get, set, and reorder operations', 'refactor the LightconvLayer reset_parameters method to use Xavier uniform initialization for weights and constant zero for bias']
```

Usage

```
{'run_gen_forward': 'run gen_forward to generate the lightconv_cuda_forward.cu CUDA source file', 'run_gen_backward': 'run gen_backward to generate the lightconv_cuda_backward.cu CUDA source file', 'run_cuda_function_gen_main': 'run the main entry point to generate both forward and backward CUDA files', 'review_gen_forward': 'review gen_forward to understand how it generates templated CUDA kernel dispatch code', 'review_gen_backward': 'review gen_backward to understand how it generates weight gradient computation kernels'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/modules/lightconv_layer/lightconv_layer.py

Prompts

```
['run gen_forward to generate the lightconv_cuda_forward.cu CUDA source file', 'run gen_backward to generate the lightconv_cuda_backward.cu CUDA source file', 'run the main entry point to generate both forward and backward CUDA files', 'review gen_forward to understand how it generates templated CUDA kernel dispatch code', 'review gen_backward to understand how it generates weight gradient computation kernels', 'build a LightconvLayer module with configurable kernel size, num heads, and weight softmax for sequence modeling', 'create a custom PyTorch autograd Function wrapping lightconv CUDA forward and backward kernels', 'test the LightconvLayer forward pass with and without incremental state for training and inference modes', 'review the LightconvLayer incremental state management methods for buffer get, set, and reorder operations', 'refactor the LightconvLayer reset_parameters method to use Xavier uniform initialization for weights and constant zero for bias']
```

Usage

```
{'build_lightconv_layer': 'build a LightconvLayer module with configurable kernel size, num heads, and weight softmax for sequence modeling', 'create_lightconv_function': 'create a custom PyTorch autograd Function wrapping lightconv CUDA forward and backward kernels', 'test_lightconv_forward': 'test the LightconvLayer forward pass with and without incremental state for training and inference modes', 'review_lightconv_incremental_state': 'review the LightconvLayer incremental state management methods for buffer get, set, and reorder operations', 'refactor_lightconv_weight_init': 'refactor the LightconvLayer reset_parameters method to use Xavier uniform initialization for weights and constant zero for bias'}
```


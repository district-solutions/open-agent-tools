# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/lightconv_layer/cuda_function_gen.py

Prompts

```
['generate CUDA source code for the lightconv forward pass kernel dispatch', 'generate CUDA source code for the lightconv backward pass gradient kernels', 'run the main entry point to generate both forward and backward CUDA source files', 'review the gen_forward function that generates templated CUDA forward kernel dispatch code', 'review the gen_backward function that generates templated CUDA backward gradient kernel dispatch code', 'build a LightconvLayer module with configurable kernel size, num heads, and weight softmax for sequence modeling', 'create a custom autograd Function that wraps lightconv CUDA forward and backward kernels for training', 'test the LightconvLayer forward pass with and without incremental state for training versus inference modes', 'review the LightconvLayer incremental state management methods for buffer get, set, and reorder operations', 'refactor the LightconvLayer reset_parameters method to use Xavier uniform initialization for weights and constant zero for bias']
```

Usage

```
{'gen_forward_cuda_source': 'generate CUDA source code for the lightconv forward pass kernel dispatch', 'gen_backward_cuda_source': 'generate CUDA source code for the lightconv backward pass gradient kernels', 'run_cuda_codegen': 'run the main entry point to generate both forward and backward CUDA source files', 'review_gen_forward': 'review the gen_forward function that generates templated CUDA forward kernel dispatch code', 'review_gen_backward': 'review the gen_backward function that generates templated CUDA backward gradient kernel dispatch code'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/lightconv_layer/lightconv_layer.py

Prompts

```
['generate CUDA source code for the lightconv forward pass kernel dispatch', 'generate CUDA source code for the lightconv backward pass gradient kernels', 'run the main entry point to generate both forward and backward CUDA source files', 'review the gen_forward function that generates templated CUDA forward kernel dispatch code', 'review the gen_backward function that generates templated CUDA backward gradient kernel dispatch code', 'build a LightconvLayer module with configurable kernel size, num heads, and weight softmax for sequence modeling', 'create a custom autograd Function that wraps lightconv CUDA forward and backward kernels for training', 'test the LightconvLayer forward pass with and without incremental state for training versus inference modes', 'review the LightconvLayer incremental state management methods for buffer get, set, and reorder operations', 'refactor the LightconvLayer reset_parameters method to use Xavier uniform initialization for weights and constant zero for bias']
```

Usage

```
{'build_lightconv_layer': 'build a LightconvLayer module with configurable kernel size, num heads, and weight softmax for sequence modeling', 'create_lightconv_function': 'create a custom autograd Function that wraps lightconv CUDA forward and backward kernels for training', 'test_lightconv_forward': 'test the LightconvLayer forward pass with and without incremental state for training versus inference modes', 'review_lightconv_incremental_state': 'review the LightconvLayer incremental state management methods for buffer get, set, and reorder operations', 'refactor_lightconv_weight_init': 'refactor the LightconvLayer reset_parameters method to use Xavier uniform initialization for weights and constant zero for bias'}
```


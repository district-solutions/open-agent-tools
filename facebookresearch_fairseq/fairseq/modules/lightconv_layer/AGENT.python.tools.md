# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/modules/lightconv_layer/cuda_function_gen.py

Prompts

```
['generate the lightconv CUDA forward pass source file with templated kernel dispatch logic', 'generate the lightconv CUDA backward pass source file with gradient kernel dispatch logic', 'run the module to generate both lightconv CUDA forward and backward source files', 'review the gen_forward function to understand how it templates kernel size and sequence length cases', 'review the gen_backward function to understand threshold and memory constraints for kernel selection', 'create a LightconvLayer module with configurable kernel size, num heads, and weight softmax', 'run the LightconvLayer forward pass on input tensor x with optional incremental state', 'build a custom autograd Function for light convolution using the lightconv CUDA kernel', 'test the LightconvLayer incremental decoding path with input buffer management and batch reordering', 'review the LightconvLayer reset_parameters method that initializes weights with Xavier uniform and bias to zero']
```

Usage

```
{'gen_forward_cuda': 'generate the lightconv CUDA forward pass source file with templated kernel dispatch logic', 'gen_backward_cuda': 'generate the lightconv CUDA backward pass source file with gradient kernel dispatch logic', 'run_gen_both': 'run the module to generate both lightconv CUDA forward and backward source files', 'review_gen_forward': 'review the gen_forward function to understand how it templates kernel size and sequence length cases', 'review_gen_backward': 'review the gen_backward function to understand threshold and memory constraints for kernel selection'}
```

## File: facebookresearch_fairseq/fairseq/modules/lightconv_layer/lightconv_layer.py

Prompts

```
['generate the lightconv CUDA forward pass source file with templated kernel dispatch logic', 'generate the lightconv CUDA backward pass source file with gradient kernel dispatch logic', 'run the module to generate both lightconv CUDA forward and backward source files', 'review the gen_forward function to understand how it templates kernel size and sequence length cases', 'review the gen_backward function to understand threshold and memory constraints for kernel selection', 'create a LightconvLayer module with configurable kernel size, num heads, and weight softmax', 'run the LightconvLayer forward pass on input tensor x with optional incremental state', 'build a custom autograd Function for light convolution using the lightconv CUDA kernel', 'test the LightconvLayer incremental decoding path with input buffer management and batch reordering', 'review the LightconvLayer reset_parameters method that initializes weights with Xavier uniform and bias to zero']
```

Usage

```
{'create_lightconv_layer': 'create a LightconvLayer module with configurable kernel size, num heads, and weight softmax', 'run_lightconv_forward': 'run the LightconvLayer forward pass on input tensor x with optional incremental state', 'build_lightconv_function': 'build a custom autograd Function for light convolution using the lightconv CUDA kernel', 'test_lightconv_incremental': 'test the LightconvLayer incremental decoding path with input buffer management and batch reordering', 'review_lightconv_reset_parameters': 'review the LightconvLayer reset_parameters method that initializes weights with Xavier uniform and bias to zero'}
```


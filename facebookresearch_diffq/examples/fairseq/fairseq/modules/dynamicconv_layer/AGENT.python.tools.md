# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/dynamicconv_layer/cuda_function_gen.py

Prompts

```
['generate CUDA source code for the dynamic convolution forward pass kernel', 'generate CUDA source code for the dynamic convolution backward pass kernel', 'run the Python script to generate both forward and backward CUDA source files', 'review the gen_forward function to see which kernel sizes and block sizes are supported', 'review the gen_backward function to understand sequence length thresholds and block size selection', 'build a DynamicconvLayer module with configurable kernel size, num_heads, and weight_softmax for dynamic convolution', 'create a dynamicconvFunction autograd Function that wraps CUDA forward and backward passes for dynamic convolution', 'test the _forward_unfolded method of DynamicconvLayer using input tensor, incremental_state, and query parameters', 'test the _forward_expanded method of DynamicconvLayer that turns convolution filters into band matrices for matrix multiplication', 'review the DynamicconvLayer reset_parameters method that initializes weight_linear with Xavier uniform and conv_bias with zeros']
```

Usage

```
{'gen_forward_cuda_source': 'generate CUDA source code for the dynamic convolution forward pass kernel', 'gen_backward_cuda_source': 'generate CUDA source code for the dynamic convolution backward pass kernel', 'run_cuda_code_gen': 'run the Python script to generate both forward and backward CUDA source files', 'review_gen_forward_kernels': 'review the gen_forward function to see which kernel sizes and block sizes are supported', 'review_gen_backward_thresholds': 'review the gen_backward function to understand sequence length thresholds and block size selection'}
```

## File: facebookresearch_diffq/examples/fairseq/fairseq/modules/dynamicconv_layer/dynamicconv_layer.py

Prompts

```
['generate CUDA source code for the dynamic convolution forward pass kernel', 'generate CUDA source code for the dynamic convolution backward pass kernel', 'run the Python script to generate both forward and backward CUDA source files', 'review the gen_forward function to see which kernel sizes and block sizes are supported', 'review the gen_backward function to understand sequence length thresholds and block size selection', 'build a DynamicconvLayer module with configurable kernel size, num_heads, and weight_softmax for dynamic convolution', 'create a dynamicconvFunction autograd Function that wraps CUDA forward and backward passes for dynamic convolution', 'test the _forward_unfolded method of DynamicconvLayer using input tensor, incremental_state, and query parameters', 'test the _forward_expanded method of DynamicconvLayer that turns convolution filters into band matrices for matrix multiplication', 'review the DynamicconvLayer reset_parameters method that initializes weight_linear with Xavier uniform and conv_bias with zeros']
```

Usage

```
{'build_dynamicconv_layer': 'build a DynamicconvLayer module with configurable kernel size, num_heads, and weight_softmax for dynamic convolution', 'create_dynamicconv_function': 'create a dynamicconvFunction autograd Function that wraps CUDA forward and backward passes for dynamic convolution', 'test_dynamicconv_forward_unfolded': 'test the _forward_unfolded method of DynamicconvLayer using input tensor, incremental_state, and query parameters', 'test_dynamicconv_forward_expanded': 'test the _forward_expanded method of DynamicconvLayer that turns convolution filters into band matrices for matrix multiplication', 'review_dynamicconv_reset_parameters': 'review the DynamicconvLayer reset_parameters method that initializes weight_linear with Xavier uniform and conv_bias with zeros'}
```


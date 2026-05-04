# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/fairseq/modules/dynamicconv_layer/cuda_function_gen.py

Prompts

```
['run the python module to generate dynamicconv CUDA forward and backward source files', 'generate the dynamicconv CUDA forward pass kernel source file with switch-case dispatch for filter sizes', 'generate the dynamicconv CUDA backward pass kernel source file with sequence-length-aware dispatch logic', 'review the gen_forward function that generates CUDA forward kernel code for dynamic convolution layers', 'review the gen_backward function that generates CUDA backward kernel code with chunking for long sequences', 'build a DynamicconvLayer module with configurable kernel size, num_heads, and weight_softmax for dynamic convolution', 'create a dynamicconvFunction autograd Function that wraps CUDA forward and backward passes for dynamic convolution', 'run the _forward_unfolded method to perform conventional convolution by unfolding input with a shifting window', 'run the _forward_expanded method to turn convolution filters into band matrices and do matrix multiplication', 'reset DynamicconvLayer parameters using xavier_uniform initialization for weight_linear and constant init for conv_bias']
```

Usage

```
{'run_cuda_function_gen': 'run the python module to generate dynamicconv CUDA forward and backward source files', 'gen_forward_cuda': 'generate the dynamicconv CUDA forward pass kernel source file with switch-case dispatch for filter sizes', 'gen_backward_cuda': 'generate the dynamicconv CUDA backward pass kernel source file with sequence-length-aware dispatch logic', 'review_gen_forward': 'review the gen_forward function that generates CUDA forward kernel code for dynamic convolution layers', 'review_gen_backward': 'review the gen_backward function that generates CUDA backward kernel code with chunking for long sequences'}
```

## File: facebookresearch_avhubert/fairseq/fairseq/modules/dynamicconv_layer/dynamicconv_layer.py

Prompts

```
['run the python module to generate dynamicconv CUDA forward and backward source files', 'generate the dynamicconv CUDA forward pass kernel source file with switch-case dispatch for filter sizes', 'generate the dynamicconv CUDA backward pass kernel source file with sequence-length-aware dispatch logic', 'review the gen_forward function that generates CUDA forward kernel code for dynamic convolution layers', 'review the gen_backward function that generates CUDA backward kernel code with chunking for long sequences', 'build a DynamicconvLayer module with configurable kernel size, num_heads, and weight_softmax for dynamic convolution', 'create a dynamicconvFunction autograd Function that wraps CUDA forward and backward passes for dynamic convolution', 'run the _forward_unfolded method to perform conventional convolution by unfolding input with a shifting window', 'run the _forward_expanded method to turn convolution filters into band matrices and do matrix multiplication', 'reset DynamicconvLayer parameters using xavier_uniform initialization for weight_linear and constant init for conv_bias']
```

Usage

```
{'build_dynamicconv_layer': 'build a DynamicconvLayer module with configurable kernel size, num_heads, and weight_softmax for dynamic convolution', 'create_dynamicconv_function': 'create a dynamicconvFunction autograd Function that wraps CUDA forward and backward passes for dynamic convolution', 'run_dynamicconv_forward_unfolded': 'run the _forward_unfolded method to perform conventional convolution by unfolding input with a shifting window', 'run_dynamicconv_forward_expanded': 'run the _forward_expanded method to turn convolution filters into band matrices and do matrix multiplication', 'reset_dynamicconv_parameters': 'reset DynamicconvLayer parameters using xavier_uniform initialization for weight_linear and constant init for conv_bias'}
```


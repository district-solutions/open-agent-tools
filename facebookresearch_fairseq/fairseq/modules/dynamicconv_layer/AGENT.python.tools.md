# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/modules/dynamicconv_layer/cuda_function_gen.py

Prompts

```
['run gen_forward to generate the dynamicconv_cuda_forward.cu CUDA source file', 'run gen_backward to generate the dynamicconv_cuda_backward.cu CUDA source file', 'run the module as main to generate both forward and backward CUDA files', 'review gen_forward to understand kernel size and block size selection logic', 'review gen_backward to understand sequence length thresholds and chunking logic', 'build a DynamicconvLayer module with configurable kernel size, num_heads, and weight_softmax for dynamic convolution', 'run the DynamicconvLayer forward pass with input tensor x and optional incremental_state for inference', 'create a custom autograd Function for dynamic convolution using the dynamicconv_cuda forward and backward kernels', 'test the _forward_unfolded method that performs conventional convolution by unfolding input with a shifting window', 'review the _forward_expanded method that turns convolution filters into band matrices for matrix multiplication']
```

Usage

```
{'run_gen_forward': 'run gen_forward to generate the dynamicconv_cuda_forward.cu CUDA source file', 'run_gen_backward': 'run gen_backward to generate the dynamicconv_cuda_backward.cu CUDA source file', 'run_cuda_code_gen': 'run the module as main to generate both forward and backward CUDA files', 'review_gen_forward': 'review gen_forward to understand kernel size and block size selection logic', 'review_gen_backward': 'review gen_backward to understand sequence length thresholds and chunking logic'}
```

## File: facebookresearch_fairseq/fairseq/modules/dynamicconv_layer/dynamicconv_layer.py

Prompts

```
['run gen_forward to generate the dynamicconv_cuda_forward.cu CUDA source file', 'run gen_backward to generate the dynamicconv_cuda_backward.cu CUDA source file', 'run the module as main to generate both forward and backward CUDA files', 'review gen_forward to understand kernel size and block size selection logic', 'review gen_backward to understand sequence length thresholds and chunking logic', 'build a DynamicconvLayer module with configurable kernel size, num_heads, and weight_softmax for dynamic convolution', 'run the DynamicconvLayer forward pass with input tensor x and optional incremental_state for inference', 'create a custom autograd Function for dynamic convolution using the dynamicconv_cuda forward and backward kernels', 'test the _forward_unfolded method that performs conventional convolution by unfolding input with a shifting window', 'review the _forward_expanded method that turns convolution filters into band matrices for matrix multiplication']
```

Usage

```
{'build_dynamicconv_layer': 'build a DynamicconvLayer module with configurable kernel size, num_heads, and weight_softmax for dynamic convolution', 'run_dynamicconv_forward': 'run the DynamicconvLayer forward pass with input tensor x and optional incremental_state for inference', 'create_dynamicconv_function': 'create a custom autograd Function for dynamic convolution using the dynamicconv_cuda forward and backward kernels', 'test_dynamicconv_unfolded': 'test the _forward_unfolded method that performs conventional convolution by unfolding input with a shifting window', 'review_dynamicconv_expanded': 'review the _forward_expanded method that turns convolution filters into band matrices for matrix multiplication'}
```


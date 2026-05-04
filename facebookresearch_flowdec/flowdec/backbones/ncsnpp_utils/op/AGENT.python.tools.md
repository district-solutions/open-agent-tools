# Agent Python Tools

- repo: facebookresearch/flowdec
- repo_uri: https://github.com/facebookresearch/flowdec

## File: facebookresearch_flowdec/flowdec/backbones/ncsnpp_utils/op/fused_act.py

Prompts

```
['build a PyTorch module that applies fused LeakyReLU with bias and scaling on GPU tensors', 'create a function that applies fused LeakyReLU activation with bias, negative slope, and scale parameters', 'test the custom autograd Function that performs fused bias and LeakyReLU activation on GPU', 'review the backward pass autograd Function that computes gradients for fused LeakyReLU with bias', 'summarize the CPU fallback path that uses standard F.leaky_relu when GPU fused kernel is unavailable', 'build a PyTorch module that upsamples, filters, and downsamples a 2D tensor using the upfirdn2d function with a custom kernel', 'create a function that runs the pure PyTorch CPU implementation of upfirdn2d for inference without CUDA dependencies', 'test the UpFirDn2d custom autograd Function forward and backward passes on GPU tensors with various up and down factors', 'review the UpFirDn2dBackward class to understand how gradients are computed through the upsample-filter-downsample operation', 'summarize the upfirdn2d_op CUDA C++ extension module that loads upfirdn2d.cpp and upfirdn2d_kernel.cu sources']
```

Usage

```
{'build_fused_leaky_relu_module': 'build a PyTorch module that applies fused LeakyReLU with bias and scaling on GPU tensors', 'create_fused_leaky_relu_function': 'create a function that applies fused LeakyReLU activation with bias, negative slope, and scale parameters', 'test_FusedLeakyReLUFunction': 'test the custom autograd Function that performs fused bias and LeakyReLU activation on GPU', 'review_FusedLeakyReLUFunctionBackward': 'review the backward pass autograd Function that computes gradients for fused LeakyReLU with bias', 'summarize_fused_leaky_relu_cpu_fallback': 'summarize the CPU fallback path that uses standard F.leaky_relu when GPU fused kernel is unavailable'}
```

## File: facebookresearch_flowdec/flowdec/backbones/ncsnpp_utils/op/upfirdn2d.py

Prompts

```
['build a PyTorch module that applies fused LeakyReLU with bias and scaling on GPU tensors', 'create a function that applies fused LeakyReLU activation with bias, negative slope, and scale parameters', 'test the custom autograd Function that performs fused bias and LeakyReLU activation on GPU', 'review the backward pass autograd Function that computes gradients for fused LeakyReLU with bias', 'summarize the CPU fallback path that uses standard F.leaky_relu when GPU fused kernel is unavailable', 'build a PyTorch module that upsamples, filters, and downsamples a 2D tensor using the upfirdn2d function with a custom kernel', 'create a function that runs the pure PyTorch CPU implementation of upfirdn2d for inference without CUDA dependencies', 'test the UpFirDn2d custom autograd Function forward and backward passes on GPU tensors with various up and down factors', 'review the UpFirDn2dBackward class to understand how gradients are computed through the upsample-filter-downsample operation', 'summarize the upfirdn2d_op CUDA C++ extension module that loads upfirdn2d.cpp and upfirdn2d_kernel.cu sources']
```

Usage

```
{'build_upfirdn2d_upsample_filter_downsample': 'build a PyTorch module that upsamples, filters, and downsamples a 2D tensor using the upfirdn2d function with a custom kernel', 'create_upfirdn2d_native_cpu_inference': 'create a function that runs the pure PyTorch CPU implementation of upfirdn2d for inference without CUDA dependencies', 'test_UpFirDn2d_autograd_function': 'test the UpFirDn2d custom autograd Function forward and backward passes on GPU tensors with various up and down factors', 'review_UpFirDn2dBackward_gradient_computation': 'review the UpFirDn2dBackward class to understand how gradients are computed through the upsample-filter-downsample operation', 'summarize_upfirdn2d_op_cpp_extension': 'summarize the upfirdn2d_op CUDA C++ extension module that loads upfirdn2d.cpp and upfirdn2d_kernel.cu sources'}
```


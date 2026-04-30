# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/backends/_nnapi/prepare.py

Prompts

```
['convert a PyTorch model to an NNAPI-compiled TorchScript module for Android inference', 'process a PyTorch model into serialized NNAPI representation with weight and memory format metadata', 'create a Torch Module that wraps NNAPI compilation with lazy init and memory format conversion', 'run an NNAPI-wrapped module forward with automatic lazy initialization and input/output format adjustment', 'configure NNAPI compilation preference for low power, fast single answer, or sustained speed', 'serialize a TorchScript module to NNAPI format with input tensors and optional config', 'build NNAPI convolution operations from PyTorch JIT graph nodes including bias and transpose support', 'convert a PyTorch quantized tensor to an NNAPI operand with scale and zero point parameters', 'build NNAPI fully connected operations from PyTorch addmm or linear JIT nodes with optional bias', 'test NNAPI pooling operation translation from PyTorch avg_pool2d and max_pool2d JIT nodes']
```

Usage

```
{'convert_model_to_nnapi': 'convert a PyTorch model to an NNAPI-compiled TorchScript module for Android inference', 'process_for_nnapi': 'process a PyTorch model into serialized NNAPI representation with weight and memory format metadata', 'create_NnapiModule': 'create a Torch Module that wraps NNAPI compilation with lazy init and memory format conversion', 'run_NnapiModule_forward': 'run an NNAPI-wrapped module forward with automatic lazy initialization and input/output format adjustment', 'use_compilation_preference': 'configure NNAPI compilation preference for low power, fast single answer, or sustained speed'}
```

## File: pytorch_pytorch/torch/backends/_nnapi/serializer.py

Prompts

```
['convert a PyTorch model to an NNAPI-compiled TorchScript module for Android inference', 'process a PyTorch model into serialized NNAPI representation with weight and memory format metadata', 'create a Torch Module that wraps NNAPI compilation with lazy init and memory format conversion', 'run an NNAPI-wrapped module forward with automatic lazy initialization and input/output format adjustment', 'configure NNAPI compilation preference for low power, fast single answer, or sustained speed', 'serialize a TorchScript module to NNAPI format with input tensors and optional config', 'build NNAPI convolution operations from PyTorch JIT graph nodes including bias and transpose support', 'convert a PyTorch quantized tensor to an NNAPI operand with scale and zero point parameters', 'build NNAPI fully connected operations from PyTorch addmm or linear JIT nodes with optional bias', 'test NNAPI pooling operation translation from PyTorch avg_pool2d and max_pool2d JIT nodes']
```

Usage

```
{'serialize_nnapi_model': 'serialize a TorchScript module to NNAPI format with input tensors and optional config', 'build_nnapi_conv2d_graph': 'build NNAPI convolution operations from PyTorch JIT graph nodes including bias and transpose support', 'convert_quantized_tensor_operand': 'convert a PyTorch quantized tensor to an NNAPI operand with scale and zero point parameters', 'build_nnapi_fully_connected_op': 'build NNAPI fully connected operations from PyTorch addmm or linear JIT nodes with optional bias', 'test_nnapi_pooling_operations': 'test NNAPI pooling operation translation from PyTorch avg_pool2d and max_pool2d JIT nodes'}
```


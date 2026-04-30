# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/nn/qat/modules/conv.py

Prompts

```
['create a QAT Conv1d module with fake quantization for weight using a qconfig', 'create a QAT Conv2d module with fake quantization for weight using a qconfig', 'create a QAT Conv3d module with fake quantization for weight using a qconfig', 'convert a float Conv1d/Conv2d/Conv3d module to a QAT module using from_float', 'convert a QAT Conv module back to a floating point module using to_float', 'create a quantization aware training Embedding module with fake quantize weight for training', 'create a quantization aware training EmbeddingBag module with fake quantize weight for training', 'convert a float torch.nn.Embedding module to a QAT Embedding module using from_float', 'convert a float torch.nn.EmbeddingBag module to a QAT EmbeddingBag module using from_float', 'convert a QAT Embedding module back to a float torch.nn.Embedding module using to_float', 'create a QAT Linear module with fake quantize for weight using a provided qconfig', 'build a QAT Linear module from an existing float nn.Linear module with qconfig attached', 'test the QAT Linear forward pass with fake quantized weight and optional bias', 'refactor a QAT Linear module back to a standard float nn.Linear module by detaching parameters', 'review the from_float class method that converts float modules to QAT modules with parametrization support']
```

Usage

```
{'create_qat_conv1d': 'create a QAT Conv1d module with fake quantization for weight using a qconfig', 'create_qat_conv2d': 'create a QAT Conv2d module with fake quantization for weight using a qconfig', 'create_qat_conv3d': 'create a QAT Conv3d module with fake quantization for weight using a qconfig', 'convert_float_to_qat': 'convert a float Conv1d/Conv2d/Conv3d module to a QAT module using from_float', 'convert_qat_to_float': 'convert a QAT Conv module back to a floating point module using to_float'}
```

## File: pytorch_pytorch/torch/ao/nn/qat/modules/embedding_ops.py

Prompts

```
['create a QAT Conv1d module with fake quantization for weight using a qconfig', 'create a QAT Conv2d module with fake quantization for weight using a qconfig', 'create a QAT Conv3d module with fake quantization for weight using a qconfig', 'convert a float Conv1d/Conv2d/Conv3d module to a QAT module using from_float', 'convert a QAT Conv module back to a floating point module using to_float', 'create a quantization aware training Embedding module with fake quantize weight for training', 'create a quantization aware training EmbeddingBag module with fake quantize weight for training', 'convert a float torch.nn.Embedding module to a QAT Embedding module using from_float', 'convert a float torch.nn.EmbeddingBag module to a QAT EmbeddingBag module using from_float', 'convert a QAT Embedding module back to a float torch.nn.Embedding module using to_float', 'create a QAT Linear module with fake quantize for weight using a provided qconfig', 'build a QAT Linear module from an existing float nn.Linear module with qconfig attached', 'test the QAT Linear forward pass with fake quantized weight and optional bias', 'refactor a QAT Linear module back to a standard float nn.Linear module by detaching parameters', 'review the from_float class method that converts float modules to QAT modules with parametrization support']
```

Usage

```
{'create_qat_embedding': 'create a quantization aware training Embedding module with fake quantize weight for training', 'create_qat_embedding_bag': 'create a quantization aware training EmbeddingBag module with fake quantize weight for training', 'convert_float_to_qat_embedding': 'convert a float torch.nn.Embedding module to a QAT Embedding module using from_float', 'convert_float_to_qat_embedding_bag': 'convert a float torch.nn.EmbeddingBag module to a QAT EmbeddingBag module using from_float', 'convert_qat_to_float_embedding': 'convert a QAT Embedding module back to a float torch.nn.Embedding module using to_float'}
```

## File: pytorch_pytorch/torch/ao/nn/qat/modules/linear.py

Prompts

```
['create a QAT Conv1d module with fake quantization for weight using a qconfig', 'create a QAT Conv2d module with fake quantization for weight using a qconfig', 'create a QAT Conv3d module with fake quantization for weight using a qconfig', 'convert a float Conv1d/Conv2d/Conv3d module to a QAT module using from_float', 'convert a QAT Conv module back to a floating point module using to_float', 'create a quantization aware training Embedding module with fake quantize weight for training', 'create a quantization aware training EmbeddingBag module with fake quantize weight for training', 'convert a float torch.nn.Embedding module to a QAT Embedding module using from_float', 'convert a float torch.nn.EmbeddingBag module to a QAT EmbeddingBag module using from_float', 'convert a QAT Embedding module back to a float torch.nn.Embedding module using to_float', 'create a QAT Linear module with fake quantize for weight using a provided qconfig', 'build a QAT Linear module from an existing float nn.Linear module with qconfig attached', 'test the QAT Linear forward pass with fake quantized weight and optional bias', 'refactor a QAT Linear module back to a standard float nn.Linear module by detaching parameters', 'review the from_float class method that converts float modules to QAT modules with parametrization support']
```

Usage

```
{'create_qat_linear': 'create a QAT Linear module with fake quantize for weight using a provided qconfig', 'build_from_float_linear': 'build a QAT Linear module from an existing float nn.Linear module with qconfig attached', 'test_linear_forward': 'test the QAT Linear forward pass with fake quantized weight and optional bias', 'refactor_to_float': 'refactor a QAT Linear module back to a standard float nn.Linear module by detaching parameters', 'review_from_float_method': 'review the from_float class method that converts float modules to QAT modules with parametrization support'}
```


# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/nn/quantized/dynamic/modules/conv.py

Prompts

```
['create a dynamically quantized 1D convolution module with floating point inputs and outputs', 'create a dynamically quantized 2D convolution module with configurable kernel size and stride', 'create a dynamically quantized 3D convolution module for volumetric data processing', 'create a dynamically quantized 1D transposed convolution module for upsampling', 'create a dynamically quantized 2D transposed convolution module for image upscaling', 'create a dynamic quantized linear module with floating point inputs and outputs using specified in and out features', 'build a forward pass for a dynamic quantized linear layer that runs quantized matrix multiplication on input tensors', 'create a dynamic quantized linear module from a float torch.nn.Linear module with a defined qconfig', 'create a dynamic quantized linear module from a reference quantized module preserving weight and bias', 'test the dynamic quantized linear module forward pass with floating point tensor inputs and verify output shape', 'create a dynamic quantized LSTM module from a float nn.LSTM with qconfig for 8-bit quantization', 'create a dynamic quantized GRU module from a float nn.GRU with qconfig for 8-bit quantization', 'quantize an RNNCell, LSTMCell, or GRUCell module using dynamic quantization with qint8 dtype', 'convert a float LSTM or GRU module to dynamic quantized version using the from_float class method', 'run forward pass on a dynamic quantized LSTM or GRU with PackedSequence input for variable-length sequences']
```

Usage

```
{'create_DynamicQuantizedConv1d': 'create a dynamically quantized 1D convolution module with floating point inputs and outputs', 'create_DynamicQuantizedConv2d': 'create a dynamically quantized 2D convolution module with configurable kernel size and stride', 'create_DynamicQuantizedConv3d': 'create a dynamically quantized 3D convolution module for volumetric data processing', 'create_DynamicQuantizedConvTranspose1d': 'create a dynamically quantized 1D transposed convolution module for upsampling', 'create_DynamicQuantizedConvTranspose2d': 'create a dynamically quantized 2D transposed convolution module for image upscaling'}
```

## File: pytorch_pytorch/torch/ao/nn/quantized/dynamic/modules/linear.py

Prompts

```
['create a dynamically quantized 1D convolution module with floating point inputs and outputs', 'create a dynamically quantized 2D convolution module with configurable kernel size and stride', 'create a dynamically quantized 3D convolution module for volumetric data processing', 'create a dynamically quantized 1D transposed convolution module for upsampling', 'create a dynamically quantized 2D transposed convolution module for image upscaling', 'create a dynamic quantized linear module with floating point inputs and outputs using specified in and out features', 'build a forward pass for a dynamic quantized linear layer that runs quantized matrix multiplication on input tensors', 'create a dynamic quantized linear module from a float torch.nn.Linear module with a defined qconfig', 'create a dynamic quantized linear module from a reference quantized module preserving weight and bias', 'test the dynamic quantized linear module forward pass with floating point tensor inputs and verify output shape', 'create a dynamic quantized LSTM module from a float nn.LSTM with qconfig for 8-bit quantization', 'create a dynamic quantized GRU module from a float nn.GRU with qconfig for 8-bit quantization', 'quantize an RNNCell, LSTMCell, or GRUCell module using dynamic quantization with qint8 dtype', 'convert a float LSTM or GRU module to dynamic quantized version using the from_float class method', 'run forward pass on a dynamic quantized LSTM or GRU with PackedSequence input for variable-length sequences']
```

Usage

```
{'create_dynamic_quantized_linear': 'create a dynamic quantized linear module with floating point inputs and outputs using specified in and out features', 'build_quantized_linear_forward': 'build a forward pass for a dynamic quantized linear layer that runs quantized matrix multiplication on input tensors', 'create_from_float_module': 'create a dynamic quantized linear module from a float torch.nn.Linear module with a defined qconfig', 'create_from_reference_module': 'create a dynamic quantized linear module from a reference quantized module preserving weight and bias', 'test_dynamic_quantized_linear': 'test the dynamic quantized linear module forward pass with floating point tensor inputs and verify output shape'}
```

## File: pytorch_pytorch/torch/ao/nn/quantized/dynamic/modules/rnn.py

Prompts

```
['create a dynamically quantized 1D convolution module with floating point inputs and outputs', 'create a dynamically quantized 2D convolution module with configurable kernel size and stride', 'create a dynamically quantized 3D convolution module for volumetric data processing', 'create a dynamically quantized 1D transposed convolution module for upsampling', 'create a dynamically quantized 2D transposed convolution module for image upscaling', 'create a dynamic quantized linear module with floating point inputs and outputs using specified in and out features', 'build a forward pass for a dynamic quantized linear layer that runs quantized matrix multiplication on input tensors', 'create a dynamic quantized linear module from a float torch.nn.Linear module with a defined qconfig', 'create a dynamic quantized linear module from a reference quantized module preserving weight and bias', 'test the dynamic quantized linear module forward pass with floating point tensor inputs and verify output shape', 'create a dynamic quantized LSTM module from a float nn.LSTM with qconfig for 8-bit quantization', 'create a dynamic quantized GRU module from a float nn.GRU with qconfig for 8-bit quantization', 'quantize an RNNCell, LSTMCell, or GRUCell module using dynamic quantization with qint8 dtype', 'convert a float LSTM or GRU module to dynamic quantized version using the from_float class method', 'run forward pass on a dynamic quantized LSTM or GRU with PackedSequence input for variable-length sequences']
```

Usage

```
{'create_dynamic_quantized_lstm': 'create a dynamic quantized LSTM module from a float nn.LSTM with qconfig for 8-bit quantization', 'create_dynamic_quantized_gru': 'create a dynamic quantized GRU module from a float nn.GRU with qconfig for 8-bit quantization', 'quantize_rnn_cell': 'quantize an RNNCell, LSTMCell, or GRUCell module using dynamic quantization with qint8 dtype', 'convert_from_float': 'convert a float LSTM or GRU module to dynamic quantized version using the from_float class method', 'run_forward_packed': 'run forward pass on a dynamic quantized LSTM or GRU with PackedSequence input for variable-length sequences'}
```


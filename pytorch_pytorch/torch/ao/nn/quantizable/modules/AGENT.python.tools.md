# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/nn/quantizable/modules/activation.py

Prompts

```
['create a quantizable MultiheadAttention module with specified embed_dim and num_heads for post-training quantization', 'convert a float MultiheadAttention module to a quantizable observed module using from_float', 'dequantize a quantized MultiheadAttention module back to float using the dequantize method', 'run forward pass on a quantizable MultiheadAttention with query, key, and value tensors', 'prepare a quantizable MultiheadAttention module for quantization with quantization stubs and observers', 'create a quantizable LSTM cell with specified input and hidden dimensions for sequence processing', 'build a multi-layer quantizable LSTM with bidirectional support and configurable batch-first mode', 'convert a float PyTorch LSTM module to a quantizable LSTM using from_float with qconfig', 'create an LSTM cell from existing weight and bias tensors using from_params factory method', 'forward pass through a quantizable LSTM with optional hidden and cell states for sequence modeling']
```

Usage

```
{'create_quantizable_multihead_attention': 'create a quantizable MultiheadAttention module with specified embed_dim and num_heads for post-training quantization', 'convert_float_to_quantizable_mha': 'convert a float MultiheadAttention module to a quantizable observed module using from_float', 'dequantize_quantized_mha': 'dequantize a quantized MultiheadAttention module back to float using the dequantize method', 'run_quantizable_mha_forward': 'run forward pass on a quantizable MultiheadAttention with query, key, and value tensors', 'prepare_mha_for_quantization': 'prepare a quantizable MultiheadAttention module for quantization with quantization stubs and observers'}
```

## File: pytorch_pytorch/torch/ao/nn/quantizable/modules/rnn.py

Prompts

```
['create a quantizable MultiheadAttention module with specified embed_dim and num_heads for post-training quantization', 'convert a float MultiheadAttention module to a quantizable observed module using from_float', 'dequantize a quantized MultiheadAttention module back to float using the dequantize method', 'run forward pass on a quantizable MultiheadAttention with query, key, and value tensors', 'prepare a quantizable MultiheadAttention module for quantization with quantization stubs and observers', 'create a quantizable LSTM cell with specified input and hidden dimensions for sequence processing', 'build a multi-layer quantizable LSTM with bidirectional support and configurable batch-first mode', 'convert a float PyTorch LSTM module to a quantizable LSTM using from_float with qconfig', 'create an LSTM cell from existing weight and bias tensors using from_params factory method', 'forward pass through a quantizable LSTM with optional hidden and cell states for sequence modeling']
```

Usage

```
{'create_lstm_cell': 'create a quantizable LSTM cell with specified input and hidden dimensions for sequence processing', 'build_quantizable_lstm': 'build a multi-layer quantizable LSTM with bidirectional support and configurable batch-first mode', 'convert_float_lstm_to_quantizable': 'convert a float PyTorch LSTM module to a quantizable LSTM using from_float with qconfig', 'create_lstm_cell_from_weights': 'create an LSTM cell from existing weight and bias tensors using from_params factory method', 'forward_quantizable_lstm': 'forward pass through a quantizable LSTM with optional hidden and cell states for sequence modeling'}
```


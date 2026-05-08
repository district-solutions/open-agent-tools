# Agent Python Tools

- repo: facebookresearch/llm-qat
- repo_uri: https://github.com/facebookresearch/llm-qat

## File: facebookresearch_llm-qat/models/modeling_llama_quant.py

Prompts

```
['build a quantized LlamaForCausalLM model from a LlamaConfig with w_bits and a_bits for weight and activation quantization', 'build a quantized LlamaForSequenceClassification model with a linear classification head on top of the Llama decoder', 'create a LlamaModel decoder with KV cache quantization using SymQuantizer and configurable kv_bits from config', 'review the LlamaAttention class that uses QuantizeLinear for q, k, v, o projections with configurable w_bits and a_bits', 'review the LlamaMLP class with QuantizeLinear gate, up, and down projections using config-driven w_bits and a_bits quantization', 'create a SymQuantizer autograd function to perform uniform symmetric quantization on a PyTorch tensor', 'create an AsymQuantizer autograd function to perform min-max asymmetric quantization on a PyTorch tensor', 'build a QuantizeLinear layer that quantizes both weights and activations with configurable bit widths', 'test the SymQuantizer forward and backward pass with a sample tensor and clip values', 'refactor the QuantizeLinear class to support custom bit widths for weights and activations']
```

Usage

```
{'build_quantized_llama_causal_lm': 'build a quantized LlamaForCausalLM model from a LlamaConfig with w_bits and a_bits for weight and activation quantization', 'build_quantized_llama_sequence_classifier': 'build a quantized LlamaForSequenceClassification model with a linear classification head on top of the Llama decoder', 'create_llama_decoder_with_kv_quantization': 'create a LlamaModel decoder with KV cache quantization using SymQuantizer and configurable kv_bits from config', 'review_llamaattention_quantized_projections': 'review the LlamaAttention class that uses QuantizeLinear for q, k, v, o projections with configurable w_bits and a_bits', 'review_llamamlp_quantized_layers': 'review the LlamaMLP class with QuantizeLinear gate, up, and down projections using config-driven w_bits and a_bits quantization'}
```

## File: facebookresearch_llm-qat/models/utils_quant.py

Prompts

```
['build a quantized LlamaForCausalLM model from a LlamaConfig with w_bits and a_bits for weight and activation quantization', 'build a quantized LlamaForSequenceClassification model with a linear classification head on top of the Llama decoder', 'create a LlamaModel decoder with KV cache quantization using SymQuantizer and configurable kv_bits from config', 'review the LlamaAttention class that uses QuantizeLinear for q, k, v, o projections with configurable w_bits and a_bits', 'review the LlamaMLP class with QuantizeLinear gate, up, and down projections using config-driven w_bits and a_bits quantization', 'create a SymQuantizer autograd function to perform uniform symmetric quantization on a PyTorch tensor', 'create an AsymQuantizer autograd function to perform min-max asymmetric quantization on a PyTorch tensor', 'build a QuantizeLinear layer that quantizes both weights and activations with configurable bit widths', 'test the SymQuantizer forward and backward pass with a sample tensor and clip values', 'refactor the QuantizeLinear class to support custom bit widths for weights and activations']
```

Usage

```
{'create_symmetric_quantizer': 'create a SymQuantizer autograd function to perform uniform symmetric quantization on a PyTorch tensor', 'create_asymmetric_quantizer': 'create an AsymQuantizer autograd function to perform min-max asymmetric quantization on a PyTorch tensor', 'build_quantize_linear_layer': 'build a QuantizeLinear layer that quantizes both weights and activations with configurable bit widths', 'test_symquantizer_forward_backward': 'test the SymQuantizer forward and backward pass with a sample tensor and clip values', 'refactor_quantize_linear_bits': 'refactor the QuantizeLinear class to support custom bit widths for weights and activations'}
```


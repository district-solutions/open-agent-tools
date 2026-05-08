# Agent Python Tools

- repo: facebookresearch/paretoq
- repo_uri: https://github.com/facebookresearch/paretoq

## File: facebookresearch_paretoq/models/modeling_llama_quant.py

Prompts

```
['build a quantized LlamaForCausalLM model from a config with w_bits quantization on attention and MLP layers', 'create a forward pass through LlamaModel with input_ids, attention_mask, and past_key_values for inference', 'test the LlamaAttention forward method with rotary position embeddings and KV cache updates', 'review the LlamaMLP class to understand how QuantizeLinear is used for gate, up, and down projections', 'refactor LlamaForSequenceClassification to add a custom pooling strategy on top of the quantized LlamaModel', 'create a learned step-size quantization autograd function for binary, ternary, or low-bit weight quantization', 'create a stretched elastic quantization autograd function for 0-bit or 2-bit weight quantization', 'build a quantized linear layer that applies LSQ or stretched elastic quantization on weights', 'review the LsqBinaryTernaryExtension backward pass gradient computation for alpha and input tensors', 'test the QuantizeLinear forward pass with different w_bits values to verify quantization behavior']
```

Usage

```
{'build_quantized_llama_causal_lm': 'build a quantized LlamaForCausalLM model from a config with w_bits quantization on attention and MLP layers', 'create_llama_model_forward_pass': 'create a forward pass through LlamaModel with input_ids, attention_mask, and past_key_values for inference', 'test_quantized_attention_layer': 'test the LlamaAttention forward method with rotary position embeddings and KV cache updates', 'review_quantized_mlp_gating': 'review the LlamaMLP class to understand how QuantizeLinear is used for gate, up, and down projections', 'refactor_llama_for_sequence_classification': 'refactor LlamaForSequenceClassification to add a custom pooling strategy on top of the quantized LlamaModel'}
```

## File: facebookresearch_paretoq/models/utils_quant.py

Prompts

```
['build a quantized LlamaForCausalLM model from a config with w_bits quantization on attention and MLP layers', 'create a forward pass through LlamaModel with input_ids, attention_mask, and past_key_values for inference', 'test the LlamaAttention forward method with rotary position embeddings and KV cache updates', 'review the LlamaMLP class to understand how QuantizeLinear is used for gate, up, and down projections', 'refactor LlamaForSequenceClassification to add a custom pooling strategy on top of the quantized LlamaModel', 'create a learned step-size quantization autograd function for binary, ternary, or low-bit weight quantization', 'create a stretched elastic quantization autograd function for 0-bit or 2-bit weight quantization', 'build a quantized linear layer that applies LSQ or stretched elastic quantization on weights', 'review the LsqBinaryTernaryExtension backward pass gradient computation for alpha and input tensors', 'test the QuantizeLinear forward pass with different w_bits values to verify quantization behavior']
```

Usage

```
{'create_lsq_quantization': 'create a learned step-size quantization autograd function for binary, ternary, or low-bit weight quantization', 'create_stretched_elastic_quant': 'create a stretched elastic quantization autograd function for 0-bit or 2-bit weight quantization', 'build_quantize_linear_layer': 'build a quantized linear layer that applies LSQ or stretched elastic quantization on weights', 'review_lsq_backward_grad': 'review the LsqBinaryTernaryExtension backward pass gradient computation for alpha and input tensors', 'test_quantize_linear_forward': 'test the QuantizeLinear forward pass with different w_bits values to verify quantization behavior'}
```


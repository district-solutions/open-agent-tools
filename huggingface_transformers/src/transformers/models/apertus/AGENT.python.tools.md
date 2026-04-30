# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/apertus/modeling_apertus.py

Prompts

```
['create an ApertusForCausalLM model for autoregressive text generation with causal language modeling', 'build an ApertusModel transformer encoder with embedding layers, decoder layers, and RMS normalization', 'run multi-headed attention with GQA, rotary embeddings, and configurable attention backends in ApertusAttention', 'test an ApertusDecoderLayer with pre-norm attention and MLP residual connections', 'review the ApertusRMSNorm layer that normalizes hidden states using root mean square with learned weights', 'create an ApertusConfig with custom vocab_size, hidden_size, and num_hidden_layers for a transformer model', 'test the ApertusAttention forward pass with query/key norms, rotary embeddings, and attention mask', 'review the ApertusDecoderLayer pre-norm architecture with attention_layernorm and feedforward_layernorm']
```

Usage

```
{'create_apertus_causal_lm': 'create an ApertusForCausalLM model for autoregressive text generation with causal language modeling', 'build_apertus_model': 'build an ApertusModel transformer encoder with embedding layers, decoder layers, and RMS normalization', 'run_apertus_attention': 'run multi-headed attention with GQA, rotary embeddings, and configurable attention backends in ApertusAttention', 'test_apertus_decoder_layer': 'test an ApertusDecoderLayer with pre-norm attention and MLP residual connections', 'review_apertus_rms_norm': 'review the ApertusRMSNorm layer that normalizes hidden states using root mean square with learned weights'}
```

## File: huggingface_transformers/src/transformers/models/apertus/modular_apertus.py

Prompts

```
['create an ApertusForCausalLM model for autoregressive text generation with causal language modeling', 'build an ApertusModel transformer encoder with embedding layers, decoder layers, and RMS normalization', 'run multi-headed attention with GQA, rotary embeddings, and configurable attention backends in ApertusAttention', 'test an ApertusDecoderLayer with pre-norm attention and MLP residual connections', 'review the ApertusRMSNorm layer that normalizes hidden states using root mean square with learned weights', 'create an ApertusConfig with custom vocab_size, hidden_size, and num_hidden_layers for a transformer model', 'test the ApertusAttention forward pass with query/key norms, rotary embeddings, and attention mask', 'review the ApertusDecoderLayer pre-norm architecture with attention_layernorm and feedforward_layernorm']
```

Usage

```
{'create_apertus_config': 'create an ApertusConfig with custom vocab_size, hidden_size, and num_hidden_layers for a transformer model', 'build_apertus_model': 'build an ApertusModel from an ApertusConfig for a causal language model with GQA and rope parameters', 'create_apertus_causal_lm': 'create an ApertusForCausalLM model initialized from the swiss-ai/Apertus-8B-Instruct-2509 checkpoint for text generation', 'test_apertus_attention': 'test the ApertusAttention forward pass with query/key norms, rotary embeddings, and attention mask', 'review_apertus_decoder_layer': 'review the ApertusDecoderLayer pre-norm architecture with attention_layernorm and feedforward_layernorm'}
```


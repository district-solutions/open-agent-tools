# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/cwm/configuration_cwm.py

Prompts

```
['create a CwmConfig instance with default cwm-7b model settings', 'build a CwmModel from a CwmConfig configuration object', 'validate that CwmConfig hidden size is a multiple of attention heads', 'customize CwmConfig with custom vocab size, hidden size, and layer count', 'inspect the base_model_tp_plan tensor parallel distribution strategy', 'create a CwmForCausalLM model for text generation from a pretrained config', 'build a CwmModel forward pass with input embeddings, attention masks, and rotary embeddings', 'test the CwmAttention multi-headed attention layer with sliding window support', 'run a CwmDecoderLayer with residual connections, RMSNorm, and MLP feedforward', 'summarize how CwmRotaryEmbedding computes cos and sin position embeddings for queries and keys', 'create a CwmConfig instance with custom vocab_size, hidden_size, and num_hidden_layers for the CWM model', 'build a CwmModel from a CwmConfig with sliding window and full attention layer types', 'build a CwmForCausalLM model from a CwmConfig for autoregressive token generation', 'run CwmModel forward pass with input_ids, attention_mask, and past_key_values for inference', 'review CwmAttention with QKV projections and sliding window causal masking support']
```

Usage

```
{'create_cwm_configuration': 'create a CwmConfig instance with default cwm-7b model settings', 'build_cwm_model_from_config': 'build a CwmModel from a CwmConfig configuration object', 'validate_cwm_architecture': 'validate that CwmConfig hidden size is a multiple of attention heads', 'customize_cwm_config_params': 'customize CwmConfig with custom vocab size, hidden size, and layer count', 'inspect_cwm_tensor_parallel_plan': 'inspect the base_model_tp_plan tensor parallel distribution strategy'}
```

## File: huggingface_transformers/src/transformers/models/cwm/modeling_cwm.py

Prompts

```
['create a CwmConfig instance with default cwm-7b model settings', 'build a CwmModel from a CwmConfig configuration object', 'validate that CwmConfig hidden size is a multiple of attention heads', 'customize CwmConfig with custom vocab size, hidden size, and layer count', 'inspect the base_model_tp_plan tensor parallel distribution strategy', 'create a CwmForCausalLM model for text generation from a pretrained config', 'build a CwmModel forward pass with input embeddings, attention masks, and rotary embeddings', 'test the CwmAttention multi-headed attention layer with sliding window support', 'run a CwmDecoderLayer with residual connections, RMSNorm, and MLP feedforward', 'summarize how CwmRotaryEmbedding computes cos and sin position embeddings for queries and keys', 'create a CwmConfig instance with custom vocab_size, hidden_size, and num_hidden_layers for the CWM model', 'build a CwmModel from a CwmConfig with sliding window and full attention layer types', 'build a CwmForCausalLM model from a CwmConfig for autoregressive token generation', 'run CwmModel forward pass with input_ids, attention_mask, and past_key_values for inference', 'review CwmAttention with QKV projections and sliding window causal masking support']
```

Usage

```
{'create_cwm_for_causal_lm': 'create a CwmForCausalLM model for text generation from a pretrained config', 'build_cwm_model_forward': 'build a CwmModel forward pass with input embeddings, attention masks, and rotary embeddings', 'test_cwm_attention_layer': 'test the CwmAttention multi-headed attention layer with sliding window support', 'run_cwm_decoder_layer': 'run a CwmDecoderLayer with residual connections, RMSNorm, and MLP feedforward', 'summarize_cwm_rotary_embedding': 'summarize how CwmRotaryEmbedding computes cos and sin position embeddings for queries and keys'}
```

## File: huggingface_transformers/src/transformers/models/cwm/modular_cwm.py

Prompts

```
['create a CwmConfig instance with default cwm-7b model settings', 'build a CwmModel from a CwmConfig configuration object', 'validate that CwmConfig hidden size is a multiple of attention heads', 'customize CwmConfig with custom vocab size, hidden size, and layer count', 'inspect the base_model_tp_plan tensor parallel distribution strategy', 'create a CwmForCausalLM model for text generation from a pretrained config', 'build a CwmModel forward pass with input embeddings, attention masks, and rotary embeddings', 'test the CwmAttention multi-headed attention layer with sliding window support', 'run a CwmDecoderLayer with residual connections, RMSNorm, and MLP feedforward', 'summarize how CwmRotaryEmbedding computes cos and sin position embeddings for queries and keys', 'create a CwmConfig instance with custom vocab_size, hidden_size, and num_hidden_layers for the CWM model', 'build a CwmModel from a CwmConfig with sliding window and full attention layer types', 'build a CwmForCausalLM model from a CwmConfig for autoregressive token generation', 'run CwmModel forward pass with input_ids, attention_mask, and past_key_values for inference', 'review CwmAttention with QKV projections and sliding window causal masking support']
```

Usage

```
{'create_CwmConfig': 'create a CwmConfig instance with custom vocab_size, hidden_size, and num_hidden_layers for the CWM model', 'build_CwmModel': 'build a CwmModel from a CwmConfig with sliding window and full attention layer types', 'build_CwmForCausalLM': 'build a CwmForCausalLM model from a CwmConfig for autoregressive token generation', 'run_CwmModel_forward': 'run CwmModel forward pass with input_ids, attention_mask, and past_key_values for inference', 'review_CwmAttention': 'review CwmAttention with QKV projections and sliding window causal masking support'}
```


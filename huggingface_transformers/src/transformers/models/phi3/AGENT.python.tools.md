# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/phi3/configuration_phi3.py

Prompts

```
['create a Phi3Config instance from a pretrained model checkpoint like microsoft/Phi-3-mini-4k-instruct', 'build a Phi3Config with custom rope_parameters including rope_theta and partial_rotary_factor', 'validate the rope_parameters configuration of a Phi3Config instance for correct structure and values', 'convert rope_scaling parameters to a standardized dictionary in Phi3Config', 'initialize a Phi3Model from a Phi3Config instance with default architecture settings', 'create a Phi3ForCausalLM model for autoregressive text generation with past key value caching', 'build a Phi3Model forward pass that computes hidden states with rotary embeddings and causal masking', 'test the Phi3Attention module with grouped multi-query attention and rotary position embeddings', 'review the Phi3DecoderLayer with residual connections, RMSNorm, and configurable dropout', 'summarize the Phi3MLP gated feed-forward network that splits gate and up projections', 'build a Phi-3 causal language model using Phi3ForCausalLM for text generation with rotary position embeddings', 'create a Phi3Attention module with grouped query attention and causal masking for transformer layers', 'run a Phi3DecoderLayer with multi-head attention, gated MLP, and residual dropout connections', 'test the Phi3MLP feed-forward network with gate-up-down projection and activation function', 'review the apply_rotary_pos_emb function that applies rotary position embedding to query and key tensors']
```

Usage

```
{'create_Phi3Config': 'create a Phi3Config instance from a pretrained model checkpoint like microsoft/Phi-3-mini-4k-instruct', 'build_Phi3Config_with_rope_params': 'build a Phi3Config with custom rope_parameters including rope_theta and partial_rotary_factor', 'validate_Phi3Config_rope_parameters': 'validate the rope_parameters configuration of a Phi3Config instance for correct structure and values', 'convert_Phi3Config_rope_params': 'convert rope_scaling parameters to a standardized dictionary in Phi3Config', 'initialize_Phi3Config_model': 'initialize a Phi3Model from a Phi3Config instance with default architecture settings'}
```

## File: huggingface_transformers/src/transformers/models/phi3/modeling_phi3.py

Prompts

```
['create a Phi3Config instance from a pretrained model checkpoint like microsoft/Phi-3-mini-4k-instruct', 'build a Phi3Config with custom rope_parameters including rope_theta and partial_rotary_factor', 'validate the rope_parameters configuration of a Phi3Config instance for correct structure and values', 'convert rope_scaling parameters to a standardized dictionary in Phi3Config', 'initialize a Phi3Model from a Phi3Config instance with default architecture settings', 'create a Phi3ForCausalLM model for autoregressive text generation with past key value caching', 'build a Phi3Model forward pass that computes hidden states with rotary embeddings and causal masking', 'test the Phi3Attention module with grouped multi-query attention and rotary position embeddings', 'review the Phi3DecoderLayer with residual connections, RMSNorm, and configurable dropout', 'summarize the Phi3MLP gated feed-forward network that splits gate and up projections', 'build a Phi-3 causal language model using Phi3ForCausalLM for text generation with rotary position embeddings', 'create a Phi3Attention module with grouped query attention and causal masking for transformer layers', 'run a Phi3DecoderLayer with multi-head attention, gated MLP, and residual dropout connections', 'test the Phi3MLP feed-forward network with gate-up-down projection and activation function', 'review the apply_rotary_pos_emb function that applies rotary position embedding to query and key tensors']
```

Usage

```
{'create_phi3_causal_lm': 'create a Phi3ForCausalLM model for autoregressive text generation with past key value caching', 'build_phi3_model_forward': 'build a Phi3Model forward pass that computes hidden states with rotary embeddings and causal masking', 'test_phi3_attention_layer': 'test the Phi3Attention module with grouped multi-query attention and rotary position embeddings', 'review_phi3_decoder_layer': 'review the Phi3DecoderLayer with residual connections, RMSNorm, and configurable dropout', 'summarize_phi3_mlp_gated': 'summarize the Phi3MLP gated feed-forward network that splits gate and up projections'}
```

## File: huggingface_transformers/src/transformers/models/phi3/modular_phi3.py

Prompts

```
['create a Phi3Config instance from a pretrained model checkpoint like microsoft/Phi-3-mini-4k-instruct', 'build a Phi3Config with custom rope_parameters including rope_theta and partial_rotary_factor', 'validate the rope_parameters configuration of a Phi3Config instance for correct structure and values', 'convert rope_scaling parameters to a standardized dictionary in Phi3Config', 'initialize a Phi3Model from a Phi3Config instance with default architecture settings', 'create a Phi3ForCausalLM model for autoregressive text generation with past key value caching', 'build a Phi3Model forward pass that computes hidden states with rotary embeddings and causal masking', 'test the Phi3Attention module with grouped multi-query attention and rotary position embeddings', 'review the Phi3DecoderLayer with residual connections, RMSNorm, and configurable dropout', 'summarize the Phi3MLP gated feed-forward network that splits gate and up projections', 'build a Phi-3 causal language model using Phi3ForCausalLM for text generation with rotary position embeddings', 'create a Phi3Attention module with grouped query attention and causal masking for transformer layers', 'run a Phi3DecoderLayer with multi-head attention, gated MLP, and residual dropout connections', 'test the Phi3MLP feed-forward network with gate-up-down projection and activation function', 'review the apply_rotary_pos_emb function that applies rotary position embedding to query and key tensors']
```

Usage

```
{'build_phi3_causal_lm': 'build a Phi-3 causal language model using Phi3ForCausalLM for text generation with rotary position embeddings', 'create_phi3_attention': 'create a Phi3Attention module with grouped query attention and causal masking for transformer layers', 'run_phi3_decoder_layer': 'run a Phi3DecoderLayer with multi-head attention, gated MLP, and residual dropout connections', 'test_phi3_mlp': 'test the Phi3MLP feed-forward network with gate-up-down projection and activation function', 'review_apply_rotary_pos_emb': 'review the apply_rotary_pos_emb function that applies rotary position embedding to query and key tensors'}
```


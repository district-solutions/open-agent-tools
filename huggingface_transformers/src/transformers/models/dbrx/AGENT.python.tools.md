# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/dbrx/configuration_dbrx.py

Prompts

```
['create a DbrxConfig instance to configure the DBRX transformer model with custom n_layers, d_model, n_heads, and vocab_size', 'create a DbrxAttentionConfig instance to configure attention layers with attn_pdrop, clip_qkv, and kv_n_heads parameters', 'create a DbrxFFNConfig instance to configure feedforward layers with moe_num_experts, moe_top_k, and ffn_hidden_size parameters', 'validate a DbrxConfig instance by calling validate_architecture to check that tie_word_embeddings is not enabled', 'build a DbrxModel instance by instantiating DbrxConfig with n_layers, d_model, n_heads, and vocab_size, then passing it to DbrxModel', 'build a DbrxForCausalLM model with DbrxConfig for autoregressive text generation', 'create a DbrxModel forward pass that computes hidden states with rotary embeddings and causal masking', 'test the DbrxFFN MoE routing that selects top-k experts and applies load-balancing loss', 'refactor DbrxAttention to support flash attention, SDPA, and eager attention backends via ALL_ATTENTION_FUNCTIONS', 'review the load_balancing_loss_func that penalizes unbalanced expert routing in Switch Transformer style', 'create a DBRX causal language model with MoE experts and rotary embeddings for text generation', 'build a DBRX transformer model with stacked DbrxBlocks, attention, and MoE feed-forward layers', 'run DBRX multi-head attention with QKV projection, RoPE embeddings, and past key-value caching', 'test the DBRX MoE feed-forward network with router-based token-to-expert routing and top-k selection', 'review the DBRX mixture-of-experts module with parallel expert GLU computation and index-add aggregation']
```

Usage

```
{'create_DbrxConfig': 'create a DbrxConfig instance to configure the DBRX transformer model with custom n_layers, d_model, n_heads, and vocab_size', 'create_DbrxAttentionConfig': 'create a DbrxAttentionConfig instance to configure attention layers with attn_pdrop, clip_qkv, and kv_n_heads parameters', 'create_DbrxFFNConfig': 'create a DbrxFFNConfig instance to configure feedforward layers with moe_num_experts, moe_top_k, and ffn_hidden_size parameters', 'validate_DbrxConfig': 'validate a DbrxConfig instance by calling validate_architecture to check that tie_word_embeddings is not enabled', 'build_DbrxModel_from_config': 'build a DbrxModel instance by instantiating DbrxConfig with n_layers, d_model, n_heads, and vocab_size, then passing it to DbrxModel'}
```

## File: huggingface_transformers/src/transformers/models/dbrx/modeling_dbrx.py

Prompts

```
['create a DbrxConfig instance to configure the DBRX transformer model with custom n_layers, d_model, n_heads, and vocab_size', 'create a DbrxAttentionConfig instance to configure attention layers with attn_pdrop, clip_qkv, and kv_n_heads parameters', 'create a DbrxFFNConfig instance to configure feedforward layers with moe_num_experts, moe_top_k, and ffn_hidden_size parameters', 'validate a DbrxConfig instance by calling validate_architecture to check that tie_word_embeddings is not enabled', 'build a DbrxModel instance by instantiating DbrxConfig with n_layers, d_model, n_heads, and vocab_size, then passing it to DbrxModel', 'build a DbrxForCausalLM model with DbrxConfig for autoregressive text generation', 'create a DbrxModel forward pass that computes hidden states with rotary embeddings and causal masking', 'test the DbrxFFN MoE routing that selects top-k experts and applies load-balancing loss', 'refactor DbrxAttention to support flash attention, SDPA, and eager attention backends via ALL_ATTENTION_FUNCTIONS', 'review the load_balancing_loss_func that penalizes unbalanced expert routing in Switch Transformer style', 'create a DBRX causal language model with MoE experts and rotary embeddings for text generation', 'build a DBRX transformer model with stacked DbrxBlocks, attention, and MoE feed-forward layers', 'run DBRX multi-head attention with QKV projection, RoPE embeddings, and past key-value caching', 'test the DBRX MoE feed-forward network with router-based token-to-expert routing and top-k selection', 'review the DBRX mixture-of-experts module with parallel expert GLU computation and index-add aggregation']
```

Usage

```
{'build_dbrx_causal_lm': 'build a DbrxForCausalLM model with DbrxConfig for autoregressive text generation', 'create_dbrx_model_forward': 'create a DbrxModel forward pass that computes hidden states with rotary embeddings and causal masking', 'test_moe_routing': 'test the DbrxFFN MoE routing that selects top-k experts and applies load-balancing loss', 'refactor_attention_backend': 'refactor DbrxAttention to support flash attention, SDPA, and eager attention backends via ALL_ATTENTION_FUNCTIONS', 'review_load_balancing_loss': 'review the load_balancing_loss_func that penalizes unbalanced expert routing in Switch Transformer style'}
```

## File: huggingface_transformers/src/transformers/models/dbrx/modular_dbrx.py

Prompts

```
['create a DbrxConfig instance to configure the DBRX transformer model with custom n_layers, d_model, n_heads, and vocab_size', 'create a DbrxAttentionConfig instance to configure attention layers with attn_pdrop, clip_qkv, and kv_n_heads parameters', 'create a DbrxFFNConfig instance to configure feedforward layers with moe_num_experts, moe_top_k, and ffn_hidden_size parameters', 'validate a DbrxConfig instance by calling validate_architecture to check that tie_word_embeddings is not enabled', 'build a DbrxModel instance by instantiating DbrxConfig with n_layers, d_model, n_heads, and vocab_size, then passing it to DbrxModel', 'build a DbrxForCausalLM model with DbrxConfig for autoregressive text generation', 'create a DbrxModel forward pass that computes hidden states with rotary embeddings and causal masking', 'test the DbrxFFN MoE routing that selects top-k experts and applies load-balancing loss', 'refactor DbrxAttention to support flash attention, SDPA, and eager attention backends via ALL_ATTENTION_FUNCTIONS', 'review the load_balancing_loss_func that penalizes unbalanced expert routing in Switch Transformer style', 'create a DBRX causal language model with MoE experts and rotary embeddings for text generation', 'build a DBRX transformer model with stacked DbrxBlocks, attention, and MoE feed-forward layers', 'run DBRX multi-head attention with QKV projection, RoPE embeddings, and past key-value caching', 'test the DBRX MoE feed-forward network with router-based token-to-expert routing and top-k selection', 'review the DBRX mixture-of-experts module with parallel expert GLU computation and index-add aggregation']
```

Usage

```
{'create_DbrxForCausalLM': 'create a DBRX causal language model with MoE experts and rotary embeddings for text generation', 'build_DbrxModel': 'build a DBRX transformer model with stacked DbrxBlocks, attention, and MoE feed-forward layers', 'run_DbrxAttention': 'run DBRX multi-head attention with QKV projection, RoPE embeddings, and past key-value caching', 'test_DbrxFFN': 'test the DBRX MoE feed-forward network with router-based token-to-expert routing and top-k selection', 'review_DbrxExperts': 'review the DBRX mixture-of-experts module with parallel expert GLU computation and index-add aggregation'}
```


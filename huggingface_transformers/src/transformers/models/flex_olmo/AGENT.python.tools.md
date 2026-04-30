# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/flex_olmo/modeling_flex_olmo.py

Prompts

```
['create a FlexOlmoForCausalLM model from config and generate text from a prompt', 'build a FlexOlmoModel encoder with embedding, rotary embeddings, and sparse MoE decoder layers', 'test the FlexOlmoSparseMoeBlock with top-k expert routing and load balancing loss', 'run FlexOlmoAttention with query, key, value projections, RMS norm, and rotary position embeddings', 'summarize the load_balancing_loss_func that computes auxiliary loss for unbalanced expert routing', 'create a FlexOlmoConfig with custom vocab size, hidden size, and number of experts for MoE architecture', 'build a FlexOlmoModel from a FlexOlmoConfig for dense and sparse MoE transformer inference', 'run FlexOlmoForCausalLM for autoregressive token generation with MoE routing and past key value caching', 'configure a FlexOlmoDecoderLayer with post-attention and post-feedforward layer norm for residual connections', 'setup FlexOlmoSparseMoeBlock with FlexOlmoTopKRouter for top-k expert selection during forward pass']
```

Usage

```
{'create_flex_olmo_causal_lm': 'create a FlexOlmoForCausalLM model from config and generate text from a prompt', 'build_flex_olmo_encoder': 'build a FlexOlmoModel encoder with embedding, rotary embeddings, and sparse MoE decoder layers', 'test_sparse_moe_routing': 'test the FlexOlmoSparseMoeBlock with top-k expert routing and load balancing loss', 'run_attention_forward': 'run FlexOlmoAttention with query, key, value projections, RMS norm, and rotary position embeddings', 'summarize_load_balancing_loss': 'summarize the load_balancing_loss_func that computes auxiliary loss for unbalanced expert routing'}
```

## File: huggingface_transformers/src/transformers/models/flex_olmo/modular_flex_olmo.py

Prompts

```
['create a FlexOlmoForCausalLM model from config and generate text from a prompt', 'build a FlexOlmoModel encoder with embedding, rotary embeddings, and sparse MoE decoder layers', 'test the FlexOlmoSparseMoeBlock with top-k expert routing and load balancing loss', 'run FlexOlmoAttention with query, key, value projections, RMS norm, and rotary position embeddings', 'summarize the load_balancing_loss_func that computes auxiliary loss for unbalanced expert routing', 'create a FlexOlmoConfig with custom vocab size, hidden size, and number of experts for MoE architecture', 'build a FlexOlmoModel from a FlexOlmoConfig for dense and sparse MoE transformer inference', 'run FlexOlmoForCausalLM for autoregressive token generation with MoE routing and past key value caching', 'configure a FlexOlmoDecoderLayer with post-attention and post-feedforward layer norm for residual connections', 'setup FlexOlmoSparseMoeBlock with FlexOlmoTopKRouter for top-k expert selection during forward pass']
```

Usage

```
{'create_flexolmo_config': 'create a FlexOlmoConfig with custom vocab size, hidden size, and number of experts for MoE architecture', 'build_flexolmo_model': 'build a FlexOlmoModel from a FlexOlmoConfig for dense and sparse MoE transformer inference', 'run_flexolmo_causal_lm': 'run FlexOlmoForCausalLM for autoregressive token generation with MoE routing and past key value caching', 'configure_flexolmo_decoder': 'configure a FlexOlmoDecoderLayer with post-attention and post-feedforward layer norm for residual connections', 'setup_flexolmo_moe_routing': 'setup FlexOlmoSparseMoeBlock with FlexOlmoTopKRouter for top-k expert selection during forward pass'}
```


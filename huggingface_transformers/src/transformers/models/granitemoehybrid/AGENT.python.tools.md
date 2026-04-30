# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/granitemoehybrid/configuration_granitemoehybrid.py

Prompts

```
['create a GraniteMoeHybridConfig instance with custom model parameters', 'configure MoE settings including num_local_experts, num_experts_per_tok, and router_aux_loss_coef', 'set embedding_multiplier, logits_scaling, residual_multiplier, and attention_multiplier on the config', 'configure Mamba hybrid parameters including mamba_n_heads, mamba_d_state, mamba_d_head, and mamba_chunk_size', 'validate the Mamba head dimensions and layer architecture of the GraniteMoeHybridConfig', 'create a GraniteMoeHybridForCausalLM model for autoregressive text generation with MoE routing', 'build a GraniteMoeHybridModel that combines attention and Mamba layers with sparse MoE experts', 'run a GraniteMoeHybridMambaLayer forward pass with selective state space computation and CUDA kernel fallback', 'test the GraniteMoeHybridTopKGating router that selects top-k experts per token with softmax gating', 'summarize the load_balancing_loss_func that computes auxiliary load balancing loss for MoE expert routing', 'run a GraniteMoeHybridAttention forward pass with rotary embeddings and KV cache support', 'test a GraniteMoeHybridDecoderLayer forward pass with conditional attention or Mamba routing']
```

Usage

```
{'create_config_granitemoehybrid': 'create a GraniteMoeHybridConfig instance with custom model parameters', 'configure_moe_experts': 'configure MoE settings including num_local_experts, num_experts_per_tok, and router_aux_loss_coef', 'set_scaling_multipliers': 'set embedding_multiplier, logits_scaling, residual_multiplier, and attention_multiplier on the config', 'configure_mamba_parameters': 'configure Mamba hybrid parameters including mamba_n_heads, mamba_d_state, mamba_d_head, and mamba_chunk_size', 'validate_architecture': 'validate the Mamba head dimensions and layer architecture of the GraniteMoeHybridConfig'}
```

## File: huggingface_transformers/src/transformers/models/granitemoehybrid/modeling_granitemoehybrid.py

Prompts

```
['create a GraniteMoeHybridConfig instance with custom model parameters', 'configure MoE settings including num_local_experts, num_experts_per_tok, and router_aux_loss_coef', 'set embedding_multiplier, logits_scaling, residual_multiplier, and attention_multiplier on the config', 'configure Mamba hybrid parameters including mamba_n_heads, mamba_d_state, mamba_d_head, and mamba_chunk_size', 'validate the Mamba head dimensions and layer architecture of the GraniteMoeHybridConfig', 'create a GraniteMoeHybridForCausalLM model for autoregressive text generation with MoE routing', 'build a GraniteMoeHybridModel that combines attention and Mamba layers with sparse MoE experts', 'run a GraniteMoeHybridMambaLayer forward pass with selective state space computation and CUDA kernel fallback', 'test the GraniteMoeHybridTopKGating router that selects top-k experts per token with softmax gating', 'summarize the load_balancing_loss_func that computes auxiliary load balancing loss for MoE expert routing', 'run a GraniteMoeHybridAttention forward pass with rotary embeddings and KV cache support', 'test a GraniteMoeHybridDecoderLayer forward pass with conditional attention or Mamba routing']
```

Usage

```
{'create_granitemoehybrid_causal_lm': 'create a GraniteMoeHybridForCausalLM model for autoregressive text generation with MoE routing', 'build_granitemoehybrid_model': 'build a GraniteMoeHybridModel that combines attention and Mamba layers with sparse MoE experts', 'run_mamba_layer_forward': 'run a GraniteMoeHybridMambaLayer forward pass with selective state space computation and CUDA kernel fallback', 'test_topk_gating_router': 'test the GraniteMoeHybridTopKGating router that selects top-k experts per token with softmax gating', 'summarize_load_balancing_loss': 'summarize the load_balancing_loss_func that computes auxiliary load balancing loss for MoE expert routing'}
```

## File: huggingface_transformers/src/transformers/models/granitemoehybrid/modular_granitemoehybrid.py

Prompts

```
['create a GraniteMoeHybridConfig instance with custom model parameters', 'configure MoE settings including num_local_experts, num_experts_per_tok, and router_aux_loss_coef', 'set embedding_multiplier, logits_scaling, residual_multiplier, and attention_multiplier on the config', 'configure Mamba hybrid parameters including mamba_n_heads, mamba_d_state, mamba_d_head, and mamba_chunk_size', 'validate the Mamba head dimensions and layer architecture of the GraniteMoeHybridConfig', 'create a GraniteMoeHybridForCausalLM model for autoregressive text generation with MoE routing', 'build a GraniteMoeHybridModel that combines attention and Mamba layers with sparse MoE experts', 'run a GraniteMoeHybridMambaLayer forward pass with selective state space computation and CUDA kernel fallback', 'test the GraniteMoeHybridTopKGating router that selects top-k experts per token with softmax gating', 'summarize the load_balancing_loss_func that computes auxiliary load balancing loss for MoE expert routing', 'run a GraniteMoeHybridAttention forward pass with rotary embeddings and KV cache support', 'test a GraniteMoeHybridDecoderLayer forward pass with conditional attention or Mamba routing']
```

Usage

```
{'create_granitemoehybrid_causal_lm': 'create a GraniteMoeHybridForCausalLM model for autoregressive text generation with mixed attention and Mamba layers', 'build_granitemoehybrid_model': 'build a GraniteMoeHybridModel that combines attention and Mamba layers with sparse MoE experts', 'run_attention_forward': 'run a GraniteMoeHybridAttention forward pass with rotary embeddings and KV cache support', 'run_mamba_layer_forward': 'run a GraniteMoeHybridMambaLayer forward pass with selective state space computation', 'test_decoder_layer_forward': 'test a GraniteMoeHybridDecoderLayer forward pass with conditional attention or Mamba routing'}
```


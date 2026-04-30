# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/hy_v3/modeling_hy_v3.py

Prompts

```
['create a HYV3ForCausalLM model with a HYV3Config for autoregressive text generation', 'build a forward pass through HYV3Model with input_ids, attention_mask, and position_ids', 'test HYV3Attention with rotary position embeddings and causal masking for multi-head attention', 'refactor HYV3MoE to route tokens through sparse experts with top-k gating and shared experts', 'review HYV3DecoderLayer with self-attention, MoE or MLP feed-forward, and residual connections', 'create an HYV3Config instance with custom model parameters like num_hidden_layers and num_experts', 'build an HYV3ForCausalLM model from an HYV3Config for autoregressive language generation', 'test the HYV3MoE forward pass with hidden states and optional fp32 combine', 'review the HYV3TopKRouter forward method that applies router_scaling_factor to top-k expert weights', 'summarize the HYV3DecoderLayer that combines HYV3Attention and HYV3MoE or HYV3MLP']
```

Usage

```
{'create_hyv3_causal_lm_model': 'create a HYV3ForCausalLM model with a HYV3Config for autoregressive text generation', 'build_hyv3_model_forward_pass': 'build a forward pass through HYV3Model with input_ids, attention_mask, and position_ids', 'test_hyv3_attention_with_rope': 'test HYV3Attention with rotary position embeddings and causal masking for multi-head attention', 'refactor_hyv3_moe_layer': 'refactor HYV3MoE to route tokens through sparse experts with top-k gating and shared experts', 'review_hyv3_decoder_layer': 'review HYV3DecoderLayer with self-attention, MoE or MLP feed-forward, and residual connections'}
```

## File: huggingface_transformers/src/transformers/models/hy_v3/modular_hy_v3.py

Prompts

```
['create a HYV3ForCausalLM model with a HYV3Config for autoregressive text generation', 'build a forward pass through HYV3Model with input_ids, attention_mask, and position_ids', 'test HYV3Attention with rotary position embeddings and causal masking for multi-head attention', 'refactor HYV3MoE to route tokens through sparse experts with top-k gating and shared experts', 'review HYV3DecoderLayer with self-attention, MoE or MLP feed-forward, and residual connections', 'create an HYV3Config instance with custom model parameters like num_hidden_layers and num_experts', 'build an HYV3ForCausalLM model from an HYV3Config for autoregressive language generation', 'test the HYV3MoE forward pass with hidden states and optional fp32 combine', 'review the HYV3TopKRouter forward method that applies router_scaling_factor to top-k expert weights', 'summarize the HYV3DecoderLayer that combines HYV3Attention and HYV3MoE or HYV3MLP']
```

Usage

```
{'create_config_hyv3': 'create an HYV3Config instance with custom model parameters like num_hidden_layers and num_experts', 'build_model_hyv3': 'build an HYV3ForCausalLM model from an HYV3Config for autoregressive language generation', 'test_moe_forward': 'test the HYV3MoE forward pass with hidden states and optional fp32 combine', 'review_topk_router': 'review the HYV3TopKRouter forward method that applies router_scaling_factor to top-k expert weights', 'summarize_decoder_layer': 'summarize the HYV3DecoderLayer that combines HYV3Attention and HYV3MoE or HYV3MLP'}
```


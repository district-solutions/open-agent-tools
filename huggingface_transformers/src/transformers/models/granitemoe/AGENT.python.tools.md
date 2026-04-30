# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/granitemoe/modeling_granitemoe.py

Prompts

```
['create a GraniteMoeForCausalLM model for autoregressive text generation with sparsely gated MoE', 'build a GraniteMoeModel with embedding tokens, rotary embeddings, and MoE decoder layers', 'test the GraniteMoeMoE forward pass with top-k expert routing and parallel expert computation', 'review the GraniteMoeAttention class with grouped query attention and rotary position embeddings', 'summarize the load_balancing_loss_func that computes auxiliary load balancing loss for MoE expert routing', 'refactor the GraniteMoeDecoderLayer to use residual multiplier scaling instead of default Mixtral scaling']
```

Usage

```
{'create_granitemoe_causal_lm': 'create a GraniteMoeForCausalLM model for autoregressive text generation with sparsely gated MoE', 'build_granitemoe_model': 'build a GraniteMoeModel with embedding tokens, rotary embeddings, and MoE decoder layers', 'test_granitemoe_moe_forward': 'test the GraniteMoeMoE forward pass with top-k expert routing and parallel expert computation', 'review_granitemoe_attention': 'review the GraniteMoeAttention class with grouped query attention and rotary position embeddings', 'summarize_load_balancing_loss': 'summarize the load_balancing_loss_func that computes auxiliary load balancing loss for MoE expert routing'}
```

## File: huggingface_transformers/src/transformers/models/granitemoe/modular_granitemoe.py

Prompts

```
['create a GraniteMoeForCausalLM model for autoregressive text generation with sparsely gated MoE', 'build a GraniteMoeModel with embedding tokens, rotary embeddings, and MoE decoder layers', 'test the GraniteMoeMoE forward pass with top-k expert routing and parallel expert computation', 'review the GraniteMoeAttention class with grouped query attention and rotary position embeddings', 'summarize the load_balancing_loss_func that computes auxiliary load balancing loss for MoE expert routing', 'refactor the GraniteMoeDecoderLayer to use residual multiplier scaling instead of default Mixtral scaling']
```

Usage

```
{'create_granitemoe_causal_lm': 'create a GraniteMoeForCausalLM model for autoregressive text generation with sparsely gated MoE', 'build_granitemoe_model': 'build a GraniteMoeModel encoder with sparsely gated mixture-of-experts decoder layers', 'test_granitemoe_moe_forward': 'test the GraniteMoeMoE forward pass with top-k expert routing and parallel expert computation', 'refactor_granitemoe_decoder': 'refactor the GraniteMoeDecoderLayer to use residual multiplier scaling instead of default Mixtral scaling', 'review_granitemoe_attention': 'review the GraniteMoeAttention class that extends LlamaAttention with configurable attention multiplier'}
```


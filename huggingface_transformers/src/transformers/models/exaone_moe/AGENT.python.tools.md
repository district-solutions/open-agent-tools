# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/exaone_moe/modeling_exaone_moe.py

Prompts

```
['build an ExaoneMoeForCausalLM model from config for autoregressive text generation', 'create an ExaoneMoeModel with embedding layers, decoder layers, RMSNorm, and rotary embeddings', 'run ExaoneMoeAttention with query key value projections, QK normalization, and rotary position embeddings', 'test ExaoneMoeSparseMoEBlock token routing to top-k experts with group masking and shared MLP', 'review ExaoneMoeDecoderLayer self-attention and MoE/MLP residual blocks with input and post-attention layer norms', 'create an ExaoneMoeConfig with MoE settings like num_experts, num_experts_per_tok, and sliding_window_pattern', 'build an ExaoneMoeModel using ExaoneMoeConfig for a mixture-of-experts transformer architecture', 'create an ExaoneMoeForCausalLM for causal language modeling with sparse MoE layers', 'initialize ExaoneMoeTopkRouter and ExaoneMoeExperts weights using _init_weights with normal and zero initialization', 'run text generation on ExaoneMoeForCausalLM with chat template inputs and max_new_tokens']
```

Usage

```
{'build_exaone_moe_causal_lm': 'build an ExaoneMoeForCausalLM model from config for autoregressive text generation', 'create_exaone_moe_model': 'create an ExaoneMoeModel with embedding layers, decoder layers, RMSNorm, and rotary embeddings', 'run_exaone_moe_attention': 'run ExaoneMoeAttention with query key value projections, QK normalization, and rotary position embeddings', 'test_exaone_moe_sparse_moe_block': 'test ExaoneMoeSparseMoEBlock token routing to top-k experts with group masking and shared MLP', 'review_exaone_moe_decoder_layer': 'review ExaoneMoeDecoderLayer self-attention and MoE/MLP residual blocks with input and post-attention layer norms'}
```

## File: huggingface_transformers/src/transformers/models/exaone_moe/modular_exaone_moe.py

Prompts

```
['build an ExaoneMoeForCausalLM model from config for autoregressive text generation', 'create an ExaoneMoeModel with embedding layers, decoder layers, RMSNorm, and rotary embeddings', 'run ExaoneMoeAttention with query key value projections, QK normalization, and rotary position embeddings', 'test ExaoneMoeSparseMoEBlock token routing to top-k experts with group masking and shared MLP', 'review ExaoneMoeDecoderLayer self-attention and MoE/MLP residual blocks with input and post-attention layer norms', 'create an ExaoneMoeConfig with MoE settings like num_experts, num_experts_per_tok, and sliding_window_pattern', 'build an ExaoneMoeModel using ExaoneMoeConfig for a mixture-of-experts transformer architecture', 'create an ExaoneMoeForCausalLM for causal language modeling with sparse MoE layers', 'initialize ExaoneMoeTopkRouter and ExaoneMoeExperts weights using _init_weights with normal and zero initialization', 'run text generation on ExaoneMoeForCausalLM with chat template inputs and max_new_tokens']
```

Usage

```
{'create_exaone_moe_config': 'create an ExaoneMoeConfig with MoE settings like num_experts, num_experts_per_tok, and sliding_window_pattern', 'build_exaone_moe_model': 'build an ExaoneMoeModel using ExaoneMoeConfig for a mixture-of-experts transformer architecture', 'create_causal_lm_model': 'create an ExaoneMoeForCausalLM for causal language modeling with sparse MoE layers', 'initialize_exaone_moe_weights': 'initialize ExaoneMoeTopkRouter and ExaoneMoeExperts weights using _init_weights with normal and zero initialization', 'run_exaone_moe_generation': 'run text generation on ExaoneMoeForCausalLM with chat template inputs and max_new_tokens'}
```


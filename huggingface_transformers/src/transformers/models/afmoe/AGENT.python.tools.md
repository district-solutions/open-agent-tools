# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/afmoe/modeling_afmoe.py

Prompts

```
['build an AfmoeForCausalLM model with a config for autoregressive text generation using token-choice MoE routing', 'create an AfmoeModel forward pass that computes hidden states with sliding window and full attention layers', 'test the AfmoeSparseMoeBlock module that combines shared experts with top-K routed experts', 'review the AfmoeAttention module with Q/K normalization, gating, and optional sliding window attention', 'summarize the AfmoeDecoderLayer with dual normalization around self-attention and MoE feed-forward network', 'create an AfmoeModel transformer decoder with AfmoeConfig containing hidden layers and embedding tokens', 'run a forward pass on AfmoeModel with input_ids, attention_mask, and past_key_values for causal language modeling', 'test the AfmoeSparseMoeBlock MoE routing with token-choice top-K expert selection and shared experts', 'review the AfmoeDecoderLayer with dual normalization around self-attention and MoE or dense FFN blocks']
```

Usage

```
{'build_afmoe_causal_lm': 'build an AfmoeForCausalLM model with a config for autoregressive text generation using token-choice MoE routing', 'create_afmoe_model_forward': 'create an AfmoeModel forward pass that computes hidden states with sliding window and full attention layers', 'test_afmoe_sparse_moe_block': 'test the AfmoeSparseMoeBlock module that combines shared experts with top-K routed experts', 'review_afmoe_attention': 'review the AfmoeAttention module with Q/K normalization, gating, and optional sliding window attention', 'summarize_afmoe_decoder_layer': 'summarize the AfmoeDecoderLayer with dual normalization around self-attention and MoE feed-forward network'}
```

## File: huggingface_transformers/src/transformers/models/afmoe/modular_afmoe.py

Prompts

```
['build an AfmoeForCausalLM model with a config for autoregressive text generation using token-choice MoE routing', 'create an AfmoeModel forward pass that computes hidden states with sliding window and full attention layers', 'test the AfmoeSparseMoeBlock module that combines shared experts with top-K routed experts', 'review the AfmoeAttention module with Q/K normalization, gating, and optional sliding window attention', 'summarize the AfmoeDecoderLayer with dual normalization around self-attention and MoE feed-forward network', 'create an AfmoeModel transformer decoder with AfmoeConfig containing hidden layers and embedding tokens', 'run a forward pass on AfmoeModel with input_ids, attention_mask, and past_key_values for causal language modeling', 'test the AfmoeSparseMoeBlock MoE routing with token-choice top-K expert selection and shared experts', 'review the AfmoeDecoderLayer with dual normalization around self-attention and MoE or dense FFN blocks']
```

Usage

```
{'build_afmoe_causal_lm': 'build an AfmoeForCausalLM model with AfmoeConfig for autoregressive token generation', 'create_afmoe_model': 'create an AfmoeModel transformer decoder with AfmoeConfig containing hidden layers and embedding tokens', 'run_afmoe_forward_pass': 'run a forward pass on AfmoeModel with input_ids, attention_mask, and past_key_values for causal language modeling', 'test_afmoe_moe_routing': 'test the AfmoeSparseMoeBlock MoE routing with token-choice top-K expert selection and shared experts', 'review_afmoe_decoder_layer': 'review the AfmoeDecoderLayer with dual normalization around self-attention and MoE or dense FFN blocks'}
```


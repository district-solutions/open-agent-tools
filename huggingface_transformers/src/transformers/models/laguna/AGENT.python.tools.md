# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/laguna/configuration_laguna.py

Prompts

```
['create a LagunaConfig instance with default hyperparameters for the Laguna MoE transformer model', 'create a LagunaConfig with custom num_hidden_layers and per-layer attention head counts', 'create a LagunaConfig with custom num_experts and moe_intermediate_size for the mixture of experts', 'validate a LagunaConfig by calling validate_architecture to check layer and head count consistency', 'review the LagunaConfig __post_init__ method that sets default layer_types and rope_parameters', 'build a LagunaForCausalLM model from a config for causal language modeling with mixture of experts', 'generate text using a LagunaForCausalLM model with generation mixin and past key values cache', 'create a LagunaModel base model that returns MoE outputs with past key values', 'compute the auxiliary load balancing loss for MoE expert routing using load_balancing_loss_func', 'apply rotary position embeddings to query and key tensors using apply_rotary_pos_emb', 'create a LagunaConfig with custom num_attention_heads_per_layer and mlp_layer_types for a 40-layer MoE model', 'build a LagunaModel from a LagunaConfig to run forward passes on tokenized input sequences', 'run LagunaForCausalLM forward pass with input_ids and labels to compute causal language modeling loss', 'review the LagunaSparseMoeBlock forward method to understand how shared and routed experts are combined with scaling', 'test the LagunaTopKRouter forward method to verify sigmoid routing scores and top-k expert selection with softcapping']
```

Usage

```
{'create_laguna_config_default': 'create a LagunaConfig instance with default hyperparameters for the Laguna MoE transformer model', 'create_laguna_config_custom_layers': 'create a LagunaConfig with custom num_hidden_layers and per-layer attention head counts', 'create_laguna_config_moe_settings': 'create a LagunaConfig with custom num_experts and moe_intermediate_size for the mixture of experts', 'validate_laguna_config_architecture': 'validate a LagunaConfig by calling validate_architecture to check layer and head count consistency', 'review_laguna_config_post_init': 'review the LagunaConfig __post_init__ method that sets default layer_types and rope_parameters'}
```

## File: huggingface_transformers/src/transformers/models/laguna/modeling_laguna.py

Prompts

```
['create a LagunaConfig instance with default hyperparameters for the Laguna MoE transformer model', 'create a LagunaConfig with custom num_hidden_layers and per-layer attention head counts', 'create a LagunaConfig with custom num_experts and moe_intermediate_size for the mixture of experts', 'validate a LagunaConfig by calling validate_architecture to check layer and head count consistency', 'review the LagunaConfig __post_init__ method that sets default layer_types and rope_parameters', 'build a LagunaForCausalLM model from a config for causal language modeling with mixture of experts', 'generate text using a LagunaForCausalLM model with generation mixin and past key values cache', 'create a LagunaModel base model that returns MoE outputs with past key values', 'compute the auxiliary load balancing loss for MoE expert routing using load_balancing_loss_func', 'apply rotary position embeddings to query and key tensors using apply_rotary_pos_emb', 'create a LagunaConfig with custom num_attention_heads_per_layer and mlp_layer_types for a 40-layer MoE model', 'build a LagunaModel from a LagunaConfig to run forward passes on tokenized input sequences', 'run LagunaForCausalLM forward pass with input_ids and labels to compute causal language modeling loss', 'review the LagunaSparseMoeBlock forward method to understand how shared and routed experts are combined with scaling', 'test the LagunaTopKRouter forward method to verify sigmoid routing scores and top-k expert selection with softcapping']
```

Usage

```
{'build_causal_lm_model': 'build a LagunaForCausalLM model from a config for causal language modeling with mixture of experts', 'generate_text_with_laguna': 'generate text using a LagunaForCausalLM model with generation mixin and past key values cache', 'create_moe_base_model': 'create a LagunaModel base model that returns MoE outputs with past key values', 'compute_load_balancing_loss': 'compute the auxiliary load balancing loss for MoE expert routing using load_balancing_loss_func', 'apply_rotary_position_embedding': 'apply rotary position embeddings to query and key tensors using apply_rotary_pos_emb'}
```

## File: huggingface_transformers/src/transformers/models/laguna/modular_laguna.py

Prompts

```
['create a LagunaConfig instance with default hyperparameters for the Laguna MoE transformer model', 'create a LagunaConfig with custom num_hidden_layers and per-layer attention head counts', 'create a LagunaConfig with custom num_experts and moe_intermediate_size for the mixture of experts', 'validate a LagunaConfig by calling validate_architecture to check layer and head count consistency', 'review the LagunaConfig __post_init__ method that sets default layer_types and rope_parameters', 'build a LagunaForCausalLM model from a config for causal language modeling with mixture of experts', 'generate text using a LagunaForCausalLM model with generation mixin and past key values cache', 'create a LagunaModel base model that returns MoE outputs with past key values', 'compute the auxiliary load balancing loss for MoE expert routing using load_balancing_loss_func', 'apply rotary position embeddings to query and key tensors using apply_rotary_pos_emb', 'create a LagunaConfig with custom num_attention_heads_per_layer and mlp_layer_types for a 40-layer MoE model', 'build a LagunaModel from a LagunaConfig to run forward passes on tokenized input sequences', 'run LagunaForCausalLM forward pass with input_ids and labels to compute causal language modeling loss', 'review the LagunaSparseMoeBlock forward method to understand how shared and routed experts are combined with scaling', 'test the LagunaTopKRouter forward method to verify sigmoid routing scores and top-k expert selection with softcapping']
```

Usage

```
{'create_laguna_config': 'create a LagunaConfig with custom num_attention_heads_per_layer and mlp_layer_types for a 40-layer MoE model', 'build_laguna_model': 'build a LagunaModel from a LagunaConfig to run forward passes on tokenized input sequences', 'run_laguna_for_causal_lm': 'run LagunaForCausalLM forward pass with input_ids and labels to compute causal language modeling loss', 'review_laguna_sparse_moe_block': 'review the LagunaSparseMoeBlock forward method to understand how shared and routed experts are combined with scaling', 'test_laguna_topk_router': 'test the LagunaTopKRouter forward method to verify sigmoid routing scores and top-k expert selection with softcapping'}
```


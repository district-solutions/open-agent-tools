# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/phimoe/configuration_phimoe.py

Prompts

```
['create a PhimoeConfig instance for the Phi-3.5-MoE model with default hyperparameters', 'load a PhimoeConfig from the microsoft/Phi-3.5-MoE-instruct checkpoint using from_pretrained', 'build a PhimoeModel instance from a PhimoeConfig configuration object', 'validate the rope_parameters field in PhimoeConfig ensuring short_mscale and long_mscale are numbers', 'configure MoE-specific parameters including num_experts_per_tok, num_local_experts, and router_aux_loss_coef', 'create a PhimoeForCausalLM model for autoregressive text generation with MoE architecture', 'build a PhimoeModel encoder with sparse mixture-of-experts and rotary position embeddings', 'run sparse expert routing with top-k selection and Gumbel-based training-time sampling', 'test the auxiliary load balancing loss function for MoE expert distribution', 'review the PhimoeSparseMoeBlock with block-sparse expert computation and router', 'test a PhimoeForSequenceClassification model for text classification with MoE layers']
```

Usage

```
{'create_phimoe_config': 'create a PhimoeConfig instance for the Phi-3.5-MoE model with default hyperparameters', 'load_phimoe_config': 'load a PhimoeConfig from the microsoft/Phi-3.5-MoE-instruct checkpoint using from_pretrained', 'build_phimoe_model': 'build a PhimoeModel instance from a PhimoeConfig configuration object', 'validate_rope_parameters': 'validate the rope_parameters field in PhimoeConfig ensuring short_mscale and long_mscale are numbers', 'configure_moe_experts': 'configure MoE-specific parameters including num_experts_per_tok, num_local_experts, and router_aux_loss_coef'}
```

## File: huggingface_transformers/src/transformers/models/phimoe/modeling_phimoe.py

Prompts

```
['create a PhimoeConfig instance for the Phi-3.5-MoE model with default hyperparameters', 'load a PhimoeConfig from the microsoft/Phi-3.5-MoE-instruct checkpoint using from_pretrained', 'build a PhimoeModel instance from a PhimoeConfig configuration object', 'validate the rope_parameters field in PhimoeConfig ensuring short_mscale and long_mscale are numbers', 'configure MoE-specific parameters including num_experts_per_tok, num_local_experts, and router_aux_loss_coef', 'create a PhimoeForCausalLM model for autoregressive text generation with MoE architecture', 'build a PhimoeModel encoder with sparse mixture-of-experts and rotary position embeddings', 'run sparse expert routing with top-k selection and Gumbel-based training-time sampling', 'test the auxiliary load balancing loss function for MoE expert distribution', 'review the PhimoeSparseMoeBlock with block-sparse expert computation and router', 'test a PhimoeForSequenceClassification model for text classification with MoE layers']
```

Usage

```
{'create_phimoe_causal_lm': 'create a PhimoeForCausalLM model for autoregressive text generation with MoE architecture', 'build_phimoe_encoder': 'build a PhimoeModel encoder with sparse mixture-of-experts and rotary position embeddings', 'run_expert_routing': 'run sparse expert routing with top-k selection and Gumbel-based training-time sampling', 'test_load_balancing_loss': 'test the auxiliary load balancing loss function for MoE expert distribution', 'review_sparse_moe_block': 'review the PhimoeSparseMoeBlock with block-sparse expert computation and router'}
```

## File: huggingface_transformers/src/transformers/models/phimoe/modular_phimoe.py

Prompts

```
['create a PhimoeConfig instance for the Phi-3.5-MoE model with default hyperparameters', 'load a PhimoeConfig from the microsoft/Phi-3.5-MoE-instruct checkpoint using from_pretrained', 'build a PhimoeModel instance from a PhimoeConfig configuration object', 'validate the rope_parameters field in PhimoeConfig ensuring short_mscale and long_mscale are numbers', 'configure MoE-specific parameters including num_experts_per_tok, num_local_experts, and router_aux_loss_coef', 'create a PhimoeForCausalLM model for autoregressive text generation with MoE architecture', 'build a PhimoeModel encoder with sparse mixture-of-experts and rotary position embeddings', 'run sparse expert routing with top-k selection and Gumbel-based training-time sampling', 'test the auxiliary load balancing loss function for MoE expert distribution', 'review the PhimoeSparseMoeBlock with block-sparse expert computation and router', 'test a PhimoeForSequenceClassification model for text classification with MoE layers']
```

Usage

```
{'create_phimoe_causal_lm': 'create a PhimoeForCausalLM model for autoregressive text generation with sparse MoE architecture', 'build_phimoe_model': 'build a PhimoeModel encoder with sparse mixture-of-experts and custom rotary embeddings', 'run_expert_routing': 'run sparse expert routing with top-k selection and Gumbel-based training-time sampling', 'test_sequence_classification': 'test a PhimoeForSequenceClassification model for text classification with MoE layers', 'review_sparse_moe_block': 'review the PhimoeSparseMoeBlock with block-sparse expert computation and router'}
```


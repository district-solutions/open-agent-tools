# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/jetmoe/configuration_jetmoe.py

Prompts

```
['create a JetMoeConfig instance with custom model parameters like vocab_size and hidden_size', 'build a JetMoe model configuration from JetMoeConfig and initialize a model from it', 'access the model configuration from an initialized JetMoeModel instance', 'validate a JetMoeConfig to ensure num_experts_per_tok is less than or equal to num_local_experts', 'initialize a JetMoeConfig with default JetMoe 4B style parameters', 'create a JetMoeForCausalLM model for autoregressive text generation with sparsely gated mixture of experts', 'build a JetMoeModel encoder-decoder with MoE decoder layers and rotary position embeddings', 'run inference with JetMoeForCausalLM using input_ids, attention_mask, and past_key_values for caching', 'test the JetMoeMoE layer with top-k gating, parallel experts, and load balancing loss', 'review the JetMoeMoA attention layer with sparsely gated mixture of attention experts and query routing', 'build a JetMoeForCausalLM model from a JetMoeConfig for autoregressive text generation with MoE routing', 'create a JetMoeModel with embedding tokens, decoder layers, and RMS norm for MoE-based sequence modeling', 'run a forward pass on JetMoeForCausalLM with input IDs, attention mask, and optional labels for loss computation']
```

Usage

```
{'create_JetMoeConfig': 'create a JetMoeConfig instance with custom model parameters like vocab_size and hidden_size', 'build_JetMoeModel_config': 'build a JetMoe model configuration from JetMoeConfig and initialize a model from it', 'access_model_configuration': 'access the model configuration from an initialized JetMoeModel instance', 'validate_JetMoeConfig_architecture': 'validate a JetMoeConfig to ensure num_experts_per_tok is less than or equal to num_local_experts', 'initialize_JetMoeConfig_defaults': 'initialize a JetMoeConfig with default JetMoe 4B style parameters'}
```

## File: huggingface_transformers/src/transformers/models/jetmoe/modeling_jetmoe.py

Prompts

```
['create a JetMoeConfig instance with custom model parameters like vocab_size and hidden_size', 'build a JetMoe model configuration from JetMoeConfig and initialize a model from it', 'access the model configuration from an initialized JetMoeModel instance', 'validate a JetMoeConfig to ensure num_experts_per_tok is less than or equal to num_local_experts', 'initialize a JetMoeConfig with default JetMoe 4B style parameters', 'create a JetMoeForCausalLM model for autoregressive text generation with sparsely gated mixture of experts', 'build a JetMoeModel encoder-decoder with MoE decoder layers and rotary position embeddings', 'run inference with JetMoeForCausalLM using input_ids, attention_mask, and past_key_values for caching', 'test the JetMoeMoE layer with top-k gating, parallel experts, and load balancing loss', 'review the JetMoeMoA attention layer with sparsely gated mixture of attention experts and query routing', 'build a JetMoeForCausalLM model from a JetMoeConfig for autoregressive text generation with MoE routing', 'create a JetMoeModel with embedding tokens, decoder layers, and RMS norm for MoE-based sequence modeling', 'run a forward pass on JetMoeForCausalLM with input IDs, attention mask, and optional labels for loss computation']
```

Usage

```
{'create_jetmoe_causal_lm': 'create a JetMoeForCausalLM model for autoregressive text generation with sparsely gated mixture of experts', 'build_jetmoe_model': 'build a JetMoeModel encoder-decoder with MoE decoder layers and rotary position embeddings', 'run_jetmoe_inference': 'run inference with JetMoeForCausalLM using input_ids, attention_mask, and past_key_values for caching', 'test_jetmoe_moe_layer': 'test the JetMoeMoE layer with top-k gating, parallel experts, and load balancing loss', 'review_jetmoe_attention': 'review the JetMoeMoA attention layer with sparsely gated mixture of attention experts and query routing'}
```

## File: huggingface_transformers/src/transformers/models/jetmoe/modular_jetmoe.py

Prompts

```
['create a JetMoeConfig instance with custom model parameters like vocab_size and hidden_size', 'build a JetMoe model configuration from JetMoeConfig and initialize a model from it', 'access the model configuration from an initialized JetMoeModel instance', 'validate a JetMoeConfig to ensure num_experts_per_tok is less than or equal to num_local_experts', 'initialize a JetMoeConfig with default JetMoe 4B style parameters', 'create a JetMoeForCausalLM model for autoregressive text generation with sparsely gated mixture of experts', 'build a JetMoeModel encoder-decoder with MoE decoder layers and rotary position embeddings', 'run inference with JetMoeForCausalLM using input_ids, attention_mask, and past_key_values for caching', 'test the JetMoeMoE layer with top-k gating, parallel experts, and load balancing loss', 'review the JetMoeMoA attention layer with sparsely gated mixture of attention experts and query routing', 'build a JetMoeForCausalLM model from a JetMoeConfig for autoregressive text generation with MoE routing', 'create a JetMoeModel with embedding tokens, decoder layers, and RMS norm for MoE-based sequence modeling', 'run a forward pass on JetMoeForCausalLM with input IDs, attention mask, and optional labels for loss computation']
```

Usage

```
{'build_jetmoe_causal_lm': 'build a JetMoeForCausalLM model from a JetMoeConfig for autoregressive text generation with MoE routing', 'create_jetmoe_model': 'create a JetMoeModel with embedding tokens, decoder layers, and RMS norm for MoE-based sequence modeling', 'run_jetmoe_forward': 'run a forward pass on JetMoeForCausalLM with input IDs, attention mask, and optional labels for loss computation', 'test_jetmoe_moe_layer': 'test the JetMoeMoE layer with parallel experts, top-k gating, and sparsely gated mixture-of-experts forward pass', 'review_jetmoe_attention': 'review the JetMoeMoA attention module with sparsely gated mixture-of-experts for multi-headed query projections'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/jamba/configuration_jamba.py

Prompts

```
['create a JambaConfig instance with custom model hyperparameters for initialization', 'build the layer type sequence (attention or mamba) for each transformer layer in a Jamba model', 'test the JambaConfig architecture validation for attention and expert layer period/offset constraints', 'review the JambaConfig properties layers_block_type, layer_types, and layers_num_experts', 'summarize the JambaConfig configuration fields and their default values for model initialization', 'create a JambaForCausalLM model for autoregressive text generation with Mamba and attention layers', 'build a JambaModel with mixed attention and Mamba decoder layers for sequence modeling', 'test the JambaMambaMixer forward pass with CUDA kernels or slow fallback for state space sequence processing', 'refactor JambaSparseMoeBlock to route tokens to top-k experts using block-sparse MoE operations', 'run load balancing loss computation on router logits to penalize unbalanced expert routing', 'build a JambaForCausalLM model for autoregressive text generation with hybrid Mamba-attention layers', 'create a JambaModel encoder with configurable mix of attention and Mamba decoder layers', 'build a JambaForSequenceClassification model for sequence-level classification tasks', 'run the JambaMambaMixer state space module with fast CUDA kernels or slow PyTorch fallback', 'configure the JambaSparseMoeBlock router to route tokens to top-k experts with load balancing']
```

Usage

```
{'create_jamba_config': 'create a JambaConfig instance with custom model hyperparameters for initialization', 'build_jamba_layer_types': 'build the layer type sequence (attention or mamba) for each transformer layer in a Jamba model', 'test_jamba_validation': 'test the JambaConfig architecture validation for attention and expert layer period/offset constraints', 'review_jamba_properties': 'review the JambaConfig properties layers_block_type, layer_types, and layers_num_experts', 'summarize_jamba_config': 'summarize the JambaConfig configuration fields and their default values for model initialization'}
```

## File: huggingface_transformers/src/transformers/models/jamba/modeling_jamba.py

Prompts

```
['create a JambaConfig instance with custom model hyperparameters for initialization', 'build the layer type sequence (attention or mamba) for each transformer layer in a Jamba model', 'test the JambaConfig architecture validation for attention and expert layer period/offset constraints', 'review the JambaConfig properties layers_block_type, layer_types, and layers_num_experts', 'summarize the JambaConfig configuration fields and their default values for model initialization', 'create a JambaForCausalLM model for autoregressive text generation with Mamba and attention layers', 'build a JambaModel with mixed attention and Mamba decoder layers for sequence modeling', 'test the JambaMambaMixer forward pass with CUDA kernels or slow fallback for state space sequence processing', 'refactor JambaSparseMoeBlock to route tokens to top-k experts using block-sparse MoE operations', 'run load balancing loss computation on router logits to penalize unbalanced expert routing', 'build a JambaForCausalLM model for autoregressive text generation with hybrid Mamba-attention layers', 'create a JambaModel encoder with configurable mix of attention and Mamba decoder layers', 'build a JambaForSequenceClassification model for sequence-level classification tasks', 'run the JambaMambaMixer state space module with fast CUDA kernels or slow PyTorch fallback', 'configure the JambaSparseMoeBlock router to route tokens to top-k experts with load balancing']
```

Usage

```
{'create_jamba_causal_lm': 'create a JambaForCausalLM model for autoregressive text generation with Mamba and attention layers', 'build_jamba_model': 'build a JambaModel with mixed attention and Mamba decoder layers for sequence modeling', 'test_jamba_mamba_mixer': 'test the JambaMambaMixer forward pass with CUDA kernels or slow fallback for state space sequence processing', 'refactor_jamba_experts': 'refactor JambaSparseMoeBlock to route tokens to top-k experts using block-sparse MoE operations', 'run_jamba_load_balancing': 'run load balancing loss computation on router logits to penalize unbalanced expert routing'}
```

## File: huggingface_transformers/src/transformers/models/jamba/modular_jamba.py

Prompts

```
['create a JambaConfig instance with custom model hyperparameters for initialization', 'build the layer type sequence (attention or mamba) for each transformer layer in a Jamba model', 'test the JambaConfig architecture validation for attention and expert layer period/offset constraints', 'review the JambaConfig properties layers_block_type, layer_types, and layers_num_experts', 'summarize the JambaConfig configuration fields and their default values for model initialization', 'create a JambaForCausalLM model for autoregressive text generation with Mamba and attention layers', 'build a JambaModel with mixed attention and Mamba decoder layers for sequence modeling', 'test the JambaMambaMixer forward pass with CUDA kernels or slow fallback for state space sequence processing', 'refactor JambaSparseMoeBlock to route tokens to top-k experts using block-sparse MoE operations', 'run load balancing loss computation on router logits to penalize unbalanced expert routing', 'build a JambaForCausalLM model for autoregressive text generation with hybrid Mamba-attention layers', 'create a JambaModel encoder with configurable mix of attention and Mamba decoder layers', 'build a JambaForSequenceClassification model for sequence-level classification tasks', 'run the JambaMambaMixer state space module with fast CUDA kernels or slow PyTorch fallback', 'configure the JambaSparseMoeBlock router to route tokens to top-k experts with load balancing']
```

Usage

```
{'build_jamba_causal_lm': 'build a JambaForCausalLM model for autoregressive text generation with hybrid Mamba-attention layers', 'create_jamba_model': 'create a JambaModel encoder with configurable mix of attention and Mamba decoder layers', 'build_jamba_sequence_classifier': 'build a JambaForSequenceClassification model for sequence-level classification tasks', 'run_jamba_mamba_mixer': 'run the JambaMambaMixer state space module with fast CUDA kernels or slow PyTorch fallback', 'configure_jamba_moe_routing': 'configure the JambaSparseMoeBlock router to route tokens to top-k experts with load balancing'}
```


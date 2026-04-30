# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/nemotron_h/configuration_nemotron_h.py

Prompts

```
['create a NemotronHConfig instance with custom hidden_size, vocab_size, and layers_block_type settings', 'build a NemotronHModel from a NemotronHConfig with custom num_hidden_layers and mamba parameters', 'validate the layers_block_type list contains only valid types: mamba, attention, or moe', "convert a hybrid_override_pattern string like 'M*E*' to a layers_block_type list of layer strings", 'convert a layers_block_type list back to a compact pattern string using M, E, and * symbols', 'create a NemotronHModel instance from a NemotronHConfig for inference or fine-tuning', 'build a NemotronHForCausalLM model with language modeling head for text generation', 'run a forward pass through NemotronHModel with input_ids and optional past_key_values for caching', 'test text generation with NemotronHForCausalLM using generate method with past_key_values caching', 'review the NemotronHMamba2Mixer class implementing selective state space SSM mixing for transformer blocks', 'create a mixture-of-experts module with non-gated MLP experts and latent projection in NemotronHMoE', 'initialize NemotronH model weights including Mamba A_log, D, dt_bias, and expert up/down projections', 'review the NemotronHBlock mixer routing between mamba, attention, and moe block types with pre-norm residual connections']
```

Usage

```
{'create_nemotronh_config': 'create a NemotronHConfig instance with custom hidden_size, vocab_size, and layers_block_type settings', 'build_nemotronh_model': 'build a NemotronHModel from a NemotronHConfig with custom num_hidden_layers and mamba parameters', 'validate_layers_block_type': 'validate the layers_block_type list contains only valid types: mamba, attention, or moe', 'convert_pattern_to_list': "convert a hybrid_override_pattern string like 'M*E*' to a layers_block_type list of layer strings", 'convert_list_to_pattern': 'convert a layers_block_type list back to a compact pattern string using M, E, and * symbols'}
```

## File: huggingface_transformers/src/transformers/models/nemotron_h/modeling_nemotron_h.py

Prompts

```
['create a NemotronHConfig instance with custom hidden_size, vocab_size, and layers_block_type settings', 'build a NemotronHModel from a NemotronHConfig with custom num_hidden_layers and mamba parameters', 'validate the layers_block_type list contains only valid types: mamba, attention, or moe', "convert a hybrid_override_pattern string like 'M*E*' to a layers_block_type list of layer strings", 'convert a layers_block_type list back to a compact pattern string using M, E, and * symbols', 'create a NemotronHModel instance from a NemotronHConfig for inference or fine-tuning', 'build a NemotronHForCausalLM model with language modeling head for text generation', 'run a forward pass through NemotronHModel with input_ids and optional past_key_values for caching', 'test text generation with NemotronHForCausalLM using generate method with past_key_values caching', 'review the NemotronHMamba2Mixer class implementing selective state space SSM mixing for transformer blocks', 'create a mixture-of-experts module with non-gated MLP experts and latent projection in NemotronHMoE', 'initialize NemotronH model weights including Mamba A_log, D, dt_bias, and expert up/down projections', 'review the NemotronHBlock mixer routing between mamba, attention, and moe block types with pre-norm residual connections']
```

Usage

```
{'create_nemotronh_model': 'create a NemotronHModel instance from a NemotronHConfig for inference or fine-tuning', 'build_nemotronh_causal_lm': 'build a NemotronHForCausalLM model with language modeling head for text generation', 'run_nemotronh_forward_pass': 'run a forward pass through NemotronHModel with input_ids and optional past_key_values for caching', 'test_nemotronh_generation': 'test text generation with NemotronHForCausalLM using generate method with past_key_values caching', 'review_nemotronh_mixer': 'review the NemotronHMamba2Mixer class implementing selective state space SSM mixing for transformer blocks'}
```

## File: huggingface_transformers/src/transformers/models/nemotron_h/modular_nemotron_h.py

Prompts

```
['create a NemotronHConfig instance with custom hidden_size, vocab_size, and layers_block_type settings', 'build a NemotronHModel from a NemotronHConfig with custom num_hidden_layers and mamba parameters', 'validate the layers_block_type list contains only valid types: mamba, attention, or moe', "convert a hybrid_override_pattern string like 'M*E*' to a layers_block_type list of layer strings", 'convert a layers_block_type list back to a compact pattern string using M, E, and * symbols', 'create a NemotronHModel instance from a NemotronHConfig for inference or fine-tuning', 'build a NemotronHForCausalLM model with language modeling head for text generation', 'run a forward pass through NemotronHModel with input_ids and optional past_key_values for caching', 'test text generation with NemotronHForCausalLM using generate method with past_key_values caching', 'review the NemotronHMamba2Mixer class implementing selective state space SSM mixing for transformer blocks', 'create a mixture-of-experts module with non-gated MLP experts and latent projection in NemotronHMoE', 'initialize NemotronH model weights including Mamba A_log, D, dt_bias, and expert up/down projections', 'review the NemotronHBlock mixer routing between mamba, attention, and moe block types with pre-norm residual connections']
```

Usage

```
{'build_nemotronh_model': 'build a NemotronH causal language model with MoE, Mamba, and attention blocks using NemotronHForCausalLM', 'create_nemotronh_moe_module': 'create a mixture-of-experts module with non-gated MLP experts and latent projection in NemotronHMoE', 'run_nemotronh_forward_pass': 'run a forward pass through NemotronHModel with input_ids, attention_mask, and past_key_values cache', 'initialize_nemotronh_weights': 'initialize NemotronH model weights including Mamba A_log, D, dt_bias, and expert up/down projections', 'review_nemotronh_block': 'review the NemotronHBlock mixer routing between mamba, attention, and moe block types with pre-norm residual connections'}
```


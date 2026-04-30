# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mamba2/configuration_mamba2.py

Prompts

```
['create a Mamba2Config instance with custom hidden_size, num_hidden_layers, and vocab_size parameters', 'build a Mamba2Model using a Mamba2Config instance to initialize model weights', 'validate a Mamba2Config to ensure hidden_size * expand equals num_heads * head_dim', 'initialize Mamba2Config with time_step_rank set to auto to compute hidden_size / 16', 'access Mamba2Config.layer_types property to get a list of mamba layer types for all hidden layers', 'convert a Mamba2 SSM checkpoint to HuggingFace transformers format with specified precision and output directory', 'load a state dictionary from a safetensors checkpoint file and strip the model prefix from keys', 'load a state dictionary from a PyTorch checkpoint file on CPU with weights_only mode', 'convert a Mamba2 SSM config dictionary to a HuggingFace Mamba2Config with padded vocab size', 'load and save a tokenizer for codestral or mamba_ssm model types to the output directory', 'create a Mamba2ForCausalLM model with Mamba2Config for autoregressive text generation', 'build a Mamba2Model with embeddings, mixer blocks, and RMSNorm for sequence modeling', 'run the Mamba2Mixer forward pass with hidden states, cache params, and attention mask for SSM computation', 'test Mamba2ForCausalLM generation with input_ids, cache_params, and attention_mask for next-token prediction', 'review the Mamba2PreTrainedModel _init_weights method for initializing mixer, linear, and norm layer weights']
```

Usage

```
{'create_mamba2_config': 'create a Mamba2Config instance with custom hidden_size, num_hidden_layers, and vocab_size parameters', 'build_mamba2_model_from_config': 'build a Mamba2Model using a Mamba2Config instance to initialize model weights', 'validate_mamba2_config': 'validate a Mamba2Config to ensure hidden_size * expand equals num_heads * head_dim', 'initialize_mamba2_time_step_rank': 'initialize Mamba2Config with time_step_rank set to auto to compute hidden_size / 16', 'access_mamba2_layer_types': 'access Mamba2Config.layer_types property to get a list of mamba layer types for all hidden layers'}
```

## File: huggingface_transformers/src/transformers/models/mamba2/convert_mamba2_ssm_checkpoint_to_pytorch.py

Prompts

```
['create a Mamba2Config instance with custom hidden_size, num_hidden_layers, and vocab_size parameters', 'build a Mamba2Model using a Mamba2Config instance to initialize model weights', 'validate a Mamba2Config to ensure hidden_size * expand equals num_heads * head_dim', 'initialize Mamba2Config with time_step_rank set to auto to compute hidden_size / 16', 'access Mamba2Config.layer_types property to get a list of mamba layer types for all hidden layers', 'convert a Mamba2 SSM checkpoint to HuggingFace transformers format with specified precision and output directory', 'load a state dictionary from a safetensors checkpoint file and strip the model prefix from keys', 'load a state dictionary from a PyTorch checkpoint file on CPU with weights_only mode', 'convert a Mamba2 SSM config dictionary to a HuggingFace Mamba2Config with padded vocab size', 'load and save a tokenizer for codestral or mamba_ssm model types to the output directory', 'create a Mamba2ForCausalLM model with Mamba2Config for autoregressive text generation', 'build a Mamba2Model with embeddings, mixer blocks, and RMSNorm for sequence modeling', 'run the Mamba2Mixer forward pass with hidden states, cache params, and attention mask for SSM computation', 'test Mamba2ForCausalLM generation with input_ids, cache_params, and attention_mask for next-token prediction', 'review the Mamba2PreTrainedModel _init_weights method for initializing mixer, linear, and norm layer weights']
```

Usage

```
{'convert_mamba2_checkpoint_file_to_huggingface_model_file': 'convert a Mamba2 SSM checkpoint to HuggingFace transformers format with specified precision and output directory', 'load_state_dict_from_safetensors': 'load a state dictionary from a safetensors checkpoint file and strip the model prefix from keys', 'load_state_dict_from_torch': 'load a state dictionary from a PyTorch checkpoint file on CPU with weights_only mode', 'convert_ssm_config_to_hf_config': 'convert a Mamba2 SSM config dictionary to a HuggingFace Mamba2Config with padded vocab size', 'load_and_save_tokenizer': 'load and save a tokenizer for codestral or mamba_ssm model types to the output directory'}
```

## File: huggingface_transformers/src/transformers/models/mamba2/modeling_mamba2.py

Prompts

```
['create a Mamba2Config instance with custom hidden_size, num_hidden_layers, and vocab_size parameters', 'build a Mamba2Model using a Mamba2Config instance to initialize model weights', 'validate a Mamba2Config to ensure hidden_size * expand equals num_heads * head_dim', 'initialize Mamba2Config with time_step_rank set to auto to compute hidden_size / 16', 'access Mamba2Config.layer_types property to get a list of mamba layer types for all hidden layers', 'convert a Mamba2 SSM checkpoint to HuggingFace transformers format with specified precision and output directory', 'load a state dictionary from a safetensors checkpoint file and strip the model prefix from keys', 'load a state dictionary from a PyTorch checkpoint file on CPU with weights_only mode', 'convert a Mamba2 SSM config dictionary to a HuggingFace Mamba2Config with padded vocab size', 'load and save a tokenizer for codestral or mamba_ssm model types to the output directory', 'create a Mamba2ForCausalLM model with Mamba2Config for autoregressive text generation', 'build a Mamba2Model with embeddings, mixer blocks, and RMSNorm for sequence modeling', 'run the Mamba2Mixer forward pass with hidden states, cache params, and attention mask for SSM computation', 'test Mamba2ForCausalLM generation with input_ids, cache_params, and attention_mask for next-token prediction', 'review the Mamba2PreTrainedModel _init_weights method for initializing mixer, linear, and norm layer weights']
```

Usage

```
{'create_mamba2_causal_lm': 'create a Mamba2ForCausalLM model with Mamba2Config for autoregressive text generation', 'build_mamba2_model': 'build a Mamba2Model with embeddings, mixer blocks, and RMSNorm for sequence modeling', 'run_mamba2_mixer_forward': 'run the Mamba2Mixer forward pass with hidden states, cache params, and attention mask for SSM computation', 'test_mamba2_generation': 'test Mamba2ForCausalLM generation with input_ids, cache_params, and attention_mask for next-token prediction', 'review_mamba2_weight_init': 'review the Mamba2PreTrainedModel _init_weights method for initializing mixer, linear, and norm layer weights'}
```


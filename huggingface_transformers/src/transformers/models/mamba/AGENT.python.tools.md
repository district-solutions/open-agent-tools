# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mamba/configuration_mamba.py

Prompts

```
['create a MambaConfig instance with custom hidden_size, num_hidden_layers, and expand parameters', 'build a MambaModel using a MambaConfig instance with custom configuration values', 'access the MambaModel configuration via model.config after model initialization', 'get the layer_types property that returns a list of mamba layer names for each hidden layer', 'configure the time_step_rank parameter to auto-compute or set a specific rank value', 'convert a mamba_ssm checkpoint file and config JSON to a HuggingFace MambaForCausalLM model saved to disk', 'validate a converted HuggingFace Mamba model produces the same logits as the original mamba_ssm model', 'convert a mamba_ssm MambaConfig object to a HuggingFace MambaConfig with matching dimensions', 'convert a mamba_ssm state dict and config dict into a HuggingFace MambaForCausalLM model and tokenizer', 'run the mamba_ssm to HuggingFace model conversion CLI with input checkpoint, config JSON, and output directory arguments', 'create a MambaForCausalLM model for autoregressive next-token prediction with language modeling head', 'build a MambaModel transformer with embedding layers and MambaBlock layers for sequence modeling', 'run a forward pass through the MambaModel with input IDs, attention mask, and optional cache for generation', 'test the MambaMixer module that computes selective state space parameters and contextualized states', 'review the MambaForCausalLM generation capabilities including cache management and prepare_inputs_for_generation']
```

Usage

```
{'create_MambaConfig': 'create a MambaConfig instance with custom hidden_size, num_hidden_layers, and expand parameters', 'build_MambaModel_from_config': 'build a MambaModel using a MambaConfig instance with custom configuration values', 'access_model_config': 'access the MambaModel configuration via model.config after model initialization', 'get_layer_types': 'get the layer_types property that returns a list of mamba layer names for each hidden layer', 'configure_time_step_rank': 'configure the time_step_rank parameter to auto-compute or set a specific rank value'}
```

## File: huggingface_transformers/src/transformers/models/mamba/convert_mamba_ssm_checkpoint_to_pytorch.py

Prompts

```
['create a MambaConfig instance with custom hidden_size, num_hidden_layers, and expand parameters', 'build a MambaModel using a MambaConfig instance with custom configuration values', 'access the MambaModel configuration via model.config after model initialization', 'get the layer_types property that returns a list of mamba layer names for each hidden layer', 'configure the time_step_rank parameter to auto-compute or set a specific rank value', 'convert a mamba_ssm checkpoint file and config JSON to a HuggingFace MambaForCausalLM model saved to disk', 'validate a converted HuggingFace Mamba model produces the same logits as the original mamba_ssm model', 'convert a mamba_ssm MambaConfig object to a HuggingFace MambaConfig with matching dimensions', 'convert a mamba_ssm state dict and config dict into a HuggingFace MambaForCausalLM model and tokenizer', 'run the mamba_ssm to HuggingFace model conversion CLI with input checkpoint, config JSON, and output directory arguments', 'create a MambaForCausalLM model for autoregressive next-token prediction with language modeling head', 'build a MambaModel transformer with embedding layers and MambaBlock layers for sequence modeling', 'run a forward pass through the MambaModel with input IDs, attention mask, and optional cache for generation', 'test the MambaMixer module that computes selective state space parameters and contextualized states', 'review the MambaForCausalLM generation capabilities including cache management and prepare_inputs_for_generation']
```

Usage

```
{'convert_mamba_checkpoint_to_hf': 'convert a mamba_ssm checkpoint file and config JSON to a HuggingFace MambaForCausalLM model saved to disk', 'validate_converted_model': 'validate a converted HuggingFace Mamba model produces the same logits as the original mamba_ssm model', 'convert_ssm_config_to_hf_config': 'convert a mamba_ssm MambaConfig object to a HuggingFace MambaConfig with matching dimensions', 'convert_mamba_ssm_checkpoint_to_hf_model': 'convert a mamba_ssm state dict and config dict into a HuggingFace MambaForCausalLM model and tokenizer', 'run_conversion_cli': 'run the mamba_ssm to HuggingFace model conversion CLI with input checkpoint, config JSON, and output directory arguments'}
```

## File: huggingface_transformers/src/transformers/models/mamba/modeling_mamba.py

Prompts

```
['create a MambaConfig instance with custom hidden_size, num_hidden_layers, and expand parameters', 'build a MambaModel using a MambaConfig instance with custom configuration values', 'access the MambaModel configuration via model.config after model initialization', 'get the layer_types property that returns a list of mamba layer names for each hidden layer', 'configure the time_step_rank parameter to auto-compute or set a specific rank value', 'convert a mamba_ssm checkpoint file and config JSON to a HuggingFace MambaForCausalLM model saved to disk', 'validate a converted HuggingFace Mamba model produces the same logits as the original mamba_ssm model', 'convert a mamba_ssm MambaConfig object to a HuggingFace MambaConfig with matching dimensions', 'convert a mamba_ssm state dict and config dict into a HuggingFace MambaForCausalLM model and tokenizer', 'run the mamba_ssm to HuggingFace model conversion CLI with input checkpoint, config JSON, and output directory arguments', 'create a MambaForCausalLM model for autoregressive next-token prediction with language modeling head', 'build a MambaModel transformer with embedding layers and MambaBlock layers for sequence modeling', 'run a forward pass through the MambaModel with input IDs, attention mask, and optional cache for generation', 'test the MambaMixer module that computes selective state space parameters and contextualized states', 'review the MambaForCausalLM generation capabilities including cache management and prepare_inputs_for_generation']
```

Usage

```
{'create_mamba_causal_lm': 'create a MambaForCausalLM model for autoregressive next-token prediction with language modeling head', 'build_mamba_model': 'build a MambaModel transformer with embedding layers and MambaBlock layers for sequence modeling', 'run_mamba_forward_pass': 'run a forward pass through the MambaModel with input IDs, attention mask, and optional cache for generation', 'test_mamba_mixer_ssm': 'test the MambaMixer module that computes selective state space parameters and contextualized states', 'review_mamba_generation': 'review the MambaForCausalLM generation capabilities including cache management and prepare_inputs_for_generation'}
```


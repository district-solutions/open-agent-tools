# Agent Python Tools

- repo: facebookresearch/physicslm4
- repo_uri: https://github.com/facebookresearch/physicslm4

## File: facebookresearch_physicslm4/lingua_modified/huggingface/canon_helper.py

Prompts

```
['create a cached ShortConvolution layer with configurable hidden size, kernel size, and activation function', 'create a canon convolution module from a config object with bias, kernel, and residual settings', 'apply canon convolution to hidden states with optional cache, layer index, and attention mask', 'review the ShortConvolution forward method that handles causal 1D convolution with mask and cache support', 'review the ShortConvolution step method for single token autoregressive decoding with conv state update', 'load a pretrained GatedDeltaNet model from lingua consolidated.pth weights and params.json config', 'build a GatedDeltaNetCanonConfig from a YAML args object with model hyperparameters', 'load a lingua framework state dict into a HuggingFace GatedDeltaNet model', 'run a forward pass through the GatedDeltaNet attention layer with chunk or fused recurrent mode', 'run a forward pass through a single GDN block with attention, MLP, and canon layers', 'build a GLACanonConfig from a YAML args object for GLA5 model variants with canon layers', 'load Lingua checkpoint state dict into a GLACanonForCausalLM model and map key prefixes', 'load a pretrained GLACanonForCausalLM model from a HuggingFace repo or local path with custom variant', 'run a forward pass through GLACanonForCausalLM with input IDs, attention mask, and optional labels', 'run a forward pass through a single GLABlock with residual connections, attention, and MLP layers', 'build a Mamba2CanonConfig from a YAML args object using build_config_from_yaml static method', 'load a pretrained Mamba2CanonForCausalLM model from a lingua checkpoint path using from_pretrained', 'load a lingua state dict into a Mamba2CanonForCausalLM model using load_from_lingua_state', 'run a forward pass through Mamba2CanonForCausalLM with input_ids and optional cache_params for generation', 'review the Mamba2CanonMixer class to understand selective state space parameter computation and CUDA kernel forwarding']
```

Usage

```
{'create_canon_layer': 'create a cached ShortConvolution layer with configurable hidden size, kernel size, and activation function', 'create_canon_from_config': 'create a canon convolution module from a config object with bias, kernel, and residual settings', 'apply_canon_to_hidden_states': 'apply canon convolution to hidden states with optional cache, layer index, and attention mask', 'review_ShortConvolution_forward': 'review the ShortConvolution forward method that handles causal 1D convolution with mask and cache support', 'review_ShortConvolution_step': 'review the ShortConvolution step method for single token autoregressive decoding with conv state update'}
```

## File: facebookresearch_physicslm4/lingua_modified/huggingface/modeling_gated_deltanet_canon.py

Prompts

```
['create a cached ShortConvolution layer with configurable hidden size, kernel size, and activation function', 'create a canon convolution module from a config object with bias, kernel, and residual settings', 'apply canon convolution to hidden states with optional cache, layer index, and attention mask', 'review the ShortConvolution forward method that handles causal 1D convolution with mask and cache support', 'review the ShortConvolution step method for single token autoregressive decoding with conv state update', 'load a pretrained GatedDeltaNet model from lingua consolidated.pth weights and params.json config', 'build a GatedDeltaNetCanonConfig from a YAML args object with model hyperparameters', 'load a lingua framework state dict into a HuggingFace GatedDeltaNet model', 'run a forward pass through the GatedDeltaNet attention layer with chunk or fused recurrent mode', 'run a forward pass through a single GDN block with attention, MLP, and canon layers', 'build a GLACanonConfig from a YAML args object for GLA5 model variants with canon layers', 'load Lingua checkpoint state dict into a GLACanonForCausalLM model and map key prefixes', 'load a pretrained GLACanonForCausalLM model from a HuggingFace repo or local path with custom variant', 'run a forward pass through GLACanonForCausalLM with input IDs, attention mask, and optional labels', 'run a forward pass through a single GLABlock with residual connections, attention, and MLP layers', 'build a Mamba2CanonConfig from a YAML args object using build_config_from_yaml static method', 'load a pretrained Mamba2CanonForCausalLM model from a lingua checkpoint path using from_pretrained', 'load a lingua state dict into a Mamba2CanonForCausalLM model using load_from_lingua_state', 'run a forward pass through Mamba2CanonForCausalLM with input_ids and optional cache_params for generation', 'review the Mamba2CanonMixer class to understand selective state space parameter computation and CUDA kernel forwarding']
```

Usage

```
{'from_pretrained_GatedDeltaNetCanonForCausalLM': 'load a pretrained GatedDeltaNet model from lingua consolidated.pth weights and params.json config', 'build_config_from_yaml_GatedDeltaNetCanonForCausalLM': 'build a GatedDeltaNetCanonConfig from a YAML args object with model hyperparameters', 'load_from_lingua_state_GatedDeltaNetCanonForCausalLM': 'load a lingua framework state dict into a HuggingFace GatedDeltaNet model', 'forward_GatedDeltaNetCanon': 'run a forward pass through the GatedDeltaNet attention layer with chunk or fused recurrent mode', 'forward_GatedDeltaNetCanonBlock': 'run a forward pass through a single GDN block with attention, MLP, and canon layers'}
```

## File: facebookresearch_physicslm4/lingua_modified/huggingface/modeling_gla_canon.py

Prompts

```
['create a cached ShortConvolution layer with configurable hidden size, kernel size, and activation function', 'create a canon convolution module from a config object with bias, kernel, and residual settings', 'apply canon convolution to hidden states with optional cache, layer index, and attention mask', 'review the ShortConvolution forward method that handles causal 1D convolution with mask and cache support', 'review the ShortConvolution step method for single token autoregressive decoding with conv state update', 'load a pretrained GatedDeltaNet model from lingua consolidated.pth weights and params.json config', 'build a GatedDeltaNetCanonConfig from a YAML args object with model hyperparameters', 'load a lingua framework state dict into a HuggingFace GatedDeltaNet model', 'run a forward pass through the GatedDeltaNet attention layer with chunk or fused recurrent mode', 'run a forward pass through a single GDN block with attention, MLP, and canon layers', 'build a GLACanonConfig from a YAML args object for GLA5 model variants with canon layers', 'load Lingua checkpoint state dict into a GLACanonForCausalLM model and map key prefixes', 'load a pretrained GLACanonForCausalLM model from a HuggingFace repo or local path with custom variant', 'run a forward pass through GLACanonForCausalLM with input IDs, attention mask, and optional labels', 'run a forward pass through a single GLABlock with residual connections, attention, and MLP layers', 'build a Mamba2CanonConfig from a YAML args object using build_config_from_yaml static method', 'load a pretrained Mamba2CanonForCausalLM model from a lingua checkpoint path using from_pretrained', 'load a lingua state dict into a Mamba2CanonForCausalLM model using load_from_lingua_state', 'run a forward pass through Mamba2CanonForCausalLM with input_ids and optional cache_params for generation', 'review the Mamba2CanonMixer class to understand selective state space parameter computation and CUDA kernel forwarding']
```

Usage

```
{'build_GLA5_config_from_yaml': 'build a GLACanonConfig from a YAML args object for GLA5 model variants with canon layers', 'load_from_lingua_state': 'load Lingua checkpoint state dict into a GLACanonForCausalLM model and map key prefixes', 'from_pretrained_GLA_canon': 'load a pretrained GLACanonForCausalLM model from a HuggingFace repo or local path with custom variant', 'forward_GLA_canon_causal_lm': 'run a forward pass through GLACanonForCausalLM with input IDs, attention mask, and optional labels', 'forward_GLA_block': 'run a forward pass through a single GLABlock with residual connections, attention, and MLP layers'}
```

## File: facebookresearch_physicslm4/lingua_modified/huggingface/modeling_mamba2_canon.py

Prompts

```
['create a cached ShortConvolution layer with configurable hidden size, kernel size, and activation function', 'create a canon convolution module from a config object with bias, kernel, and residual settings', 'apply canon convolution to hidden states with optional cache, layer index, and attention mask', 'review the ShortConvolution forward method that handles causal 1D convolution with mask and cache support', 'review the ShortConvolution step method for single token autoregressive decoding with conv state update', 'load a pretrained GatedDeltaNet model from lingua consolidated.pth weights and params.json config', 'build a GatedDeltaNetCanonConfig from a YAML args object with model hyperparameters', 'load a lingua framework state dict into a HuggingFace GatedDeltaNet model', 'run a forward pass through the GatedDeltaNet attention layer with chunk or fused recurrent mode', 'run a forward pass through a single GDN block with attention, MLP, and canon layers', 'build a GLACanonConfig from a YAML args object for GLA5 model variants with canon layers', 'load Lingua checkpoint state dict into a GLACanonForCausalLM model and map key prefixes', 'load a pretrained GLACanonForCausalLM model from a HuggingFace repo or local path with custom variant', 'run a forward pass through GLACanonForCausalLM with input IDs, attention mask, and optional labels', 'run a forward pass through a single GLABlock with residual connections, attention, and MLP layers', 'build a Mamba2CanonConfig from a YAML args object using build_config_from_yaml static method', 'load a pretrained Mamba2CanonForCausalLM model from a lingua checkpoint path using from_pretrained', 'load a lingua state dict into a Mamba2CanonForCausalLM model using load_from_lingua_state', 'run a forward pass through Mamba2CanonForCausalLM with input_ids and optional cache_params for generation', 'review the Mamba2CanonMixer class to understand selective state space parameter computation and CUDA kernel forwarding']
```

Usage

```
{'build_mamba2_canon_config': 'build a Mamba2CanonConfig from a YAML args object using build_config_from_yaml static method', 'load_mamba2_from_pretrained': 'load a pretrained Mamba2CanonForCausalLM model from a lingua checkpoint path using from_pretrained', 'load_lingua_state_dict': 'load a lingua state dict into a Mamba2CanonForCausalLM model using load_from_lingua_state', 'run_mamba2_causal_lm_forward': 'run a forward pass through Mamba2CanonForCausalLM with input_ids and optional cache_params for generation', 'review_mamba2_canon_mixer': 'review the Mamba2CanonMixer class to understand selective state space parameter computation and CUDA kernel forwarding'}
```


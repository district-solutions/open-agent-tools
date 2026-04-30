# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/falcon_mamba/configuration_falcon_mamba.py

Prompts

```
['create a FalconMambaConfig instance with custom hidden_size, num_hidden_layers, and vocab_size', 'initialize a FalconMambaModel from a FalconMambaConfig with random weights', 'configure the mixer RMS norm epsilon value for B, C and dt states in FalconMambaConfig', 'set time step rank, scale, min, max, and init scheme parameters in FalconMambaConfig', 'get the layer types list for all hidden layers in a FalconMambaConfig instance', 'build a FalconMambaForCausalLM model for autoregressive text generation with cache support', 'create a FalconMambaModel transformer with embeddings and stacked mixer blocks', 'run the FalconMambaMixer selective state-space layer with cuda kernels or slow fallback', 'test the FalconMambaBlock residual connection with RMSNorm and mixer forward pass', 'review the FalconMambaPreTrainedModel weight initialization and gradient checkpointing support', 'build a FalconMambaModel with stacked mixer blocks and RMSNorm', 'run a FalconMambaForCausalLM model for autoregressive text generation', 'test the FalconMambaMixer forward pass with CUDA kernel fast path', 'review the rms_forward utility function for RMS normalization']
```

Usage

```
{'create_falcon_mamba_config': 'create a FalconMambaConfig instance with custom hidden_size, num_hidden_layers, and vocab_size', 'initialize_falcon_mamba_model': 'initialize a FalconMambaModel from a FalconMambaConfig with random weights', 'configure_mixer_rms_norm': 'configure the mixer RMS norm epsilon value for B, C and dt states in FalconMambaConfig', 'set_time_step_parameters': 'set time step rank, scale, min, max, and init scheme parameters in FalconMambaConfig', 'get_layer_types': 'get the layer types list for all hidden layers in a FalconMambaConfig instance'}
```

## File: huggingface_transformers/src/transformers/models/falcon_mamba/modeling_falcon_mamba.py

Prompts

```
['create a FalconMambaConfig instance with custom hidden_size, num_hidden_layers, and vocab_size', 'initialize a FalconMambaModel from a FalconMambaConfig with random weights', 'configure the mixer RMS norm epsilon value for B, C and dt states in FalconMambaConfig', 'set time step rank, scale, min, max, and init scheme parameters in FalconMambaConfig', 'get the layer types list for all hidden layers in a FalconMambaConfig instance', 'build a FalconMambaForCausalLM model for autoregressive text generation with cache support', 'create a FalconMambaModel transformer with embeddings and stacked mixer blocks', 'run the FalconMambaMixer selective state-space layer with cuda kernels or slow fallback', 'test the FalconMambaBlock residual connection with RMSNorm and mixer forward pass', 'review the FalconMambaPreTrainedModel weight initialization and gradient checkpointing support', 'build a FalconMambaModel with stacked mixer blocks and RMSNorm', 'run a FalconMambaForCausalLM model for autoregressive text generation', 'test the FalconMambaMixer forward pass with CUDA kernel fast path', 'review the rms_forward utility function for RMS normalization']
```

Usage

```
{'build_falcon_mamba_causal_lm': 'build a FalconMambaForCausalLM model for autoregressive text generation with cache support', 'create_falcon_mamba_model': 'create a FalconMambaModel transformer with embeddings and stacked mixer blocks', 'run_falcon_mamba_mixer': 'run the FalconMambaMixer selective state-space layer with cuda kernels or slow fallback', 'test_falcon_mamba_block': 'test the FalconMambaBlock residual connection with RMSNorm and mixer forward pass', 'review_falcon_mamba_pretrained_model': 'review the FalconMambaPreTrainedModel weight initialization and gradient checkpointing support'}
```

## File: huggingface_transformers/src/transformers/models/falcon_mamba/modular_falcon_mamba.py

Prompts

```
['create a FalconMambaConfig instance with custom hidden_size, num_hidden_layers, and vocab_size', 'initialize a FalconMambaModel from a FalconMambaConfig with random weights', 'configure the mixer RMS norm epsilon value for B, C and dt states in FalconMambaConfig', 'set time step rank, scale, min, max, and init scheme parameters in FalconMambaConfig', 'get the layer types list for all hidden layers in a FalconMambaConfig instance', 'build a FalconMambaForCausalLM model for autoregressive text generation with cache support', 'create a FalconMambaModel transformer with embeddings and stacked mixer blocks', 'run the FalconMambaMixer selective state-space layer with cuda kernels or slow fallback', 'test the FalconMambaBlock residual connection with RMSNorm and mixer forward pass', 'review the FalconMambaPreTrainedModel weight initialization and gradient checkpointing support', 'build a FalconMambaModel with stacked mixer blocks and RMSNorm', 'run a FalconMambaForCausalLM model for autoregressive text generation', 'test the FalconMambaMixer forward pass with CUDA kernel fast path', 'review the rms_forward utility function for RMS normalization']
```

Usage

```
{'create_falcon_mamba_config': 'create a FalconMambaConfig with custom expand factor and conv kernel size', 'build_falcon_mamba_model': 'build a FalconMambaModel with stacked mixer blocks and RMSNorm', 'run_falcon_mamba_causal_lm': 'run a FalconMambaForCausalLM model for autoregressive text generation', 'test_falcon_mamba_mixer': 'test the FalconMambaMixer forward pass with CUDA kernel fast path', 'review_rms_forward': 'review the rms_forward utility function for RMS normalization'}
```


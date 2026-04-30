# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/falcon_h1/configuration_falcon_h1.py

Prompts

```
['create a FalconH1Config instance with vocab_size, hidden_size, attention heads, and SSM parameters for model initialization', 'build a FalconH1Config with default values for mamba_d_head auto-resolution, multipliers, and key_value_heads', 'test the FalconH1Config.validate_architecture method to verify mamba head dimensions match intermediate size', 'review the FalconH1Config.__post_init__ method that resolves defaults for multipliers, time_step_limit, and key_value_heads', 'summarize the FalconH1Config.layers_block_type property that returns a list of hybrid layer types for all decoder layers', 'convert a mamba_ssm checkpoint directory into HuggingFace FalconH1 format and save to output path', 'build a FalconH1Config from a pretrained mamba_ssm model config with expanded intermediate size', 'map mamba_ssm state dict keys to HuggingFace FalconH1 naming convention using conversion mapping', 'split a combined attn_proj weight tensor into separate q_proj, k_proj, and v_proj tensors', 'run the checkpoint conversion script from command line with input and output directory arguments', 'create a FalconH1ForCausalLM model for autoregressive text generation with past key value caching', 'build a FalconH1Model encoder with embedding tokens, rotary embeddings, and decoder layers', 'run the FalconH1Mixer SSM component with cuda kernels or naive torch forward for sequence modeling', 'test the FalconH1Attention multi-headed attention with rotary position embeddings and kv caching', 'review the FalconH1DecoderLayer combining mixer, attention, and MLP with residual connections and RMSNorm', 'create a FalconH1Model instance from a FalconH1Config for autoregressive language modeling', 'build a FalconH1ForCausalLM model with configurable hidden size, attention heads, and SSM parameters', 'run a forward pass through the FalconH1Model with input_ids, attention_mask, and past_key_values for caching', 'test a FalconH1DecoderLayer with mixed attention and Mamba mixer components and residual connections', 'review the FalconH1Mixer forward method that supports both CUDA kernel fast path and naive PyTorch SSM implementation']
```

Usage

```
{'create_falcon_h1_config': 'create a FalconH1Config instance with vocab_size, hidden_size, attention heads, and SSM parameters for model initialization', 'build_falcon_h1_config_defaults': 'build a FalconH1Config with default values for mamba_d_head auto-resolution, multipliers, and key_value_heads', 'test_falcon_h1_validate_architecture': 'test the FalconH1Config.validate_architecture method to verify mamba head dimensions match intermediate size', 'review_falcon_h1_config_post_init': 'review the FalconH1Config.__post_init__ method that resolves defaults for multipliers, time_step_limit, and key_value_heads', 'summarize_falcon_h1_config_layers_block_type': 'summarize the FalconH1Config.layers_block_type property that returns a list of hybrid layer types for all decoder layers'}
```

## File: huggingface_transformers/src/transformers/models/falcon_h1/convert_mamba_ssm_checkpoint.py

Prompts

```
['create a FalconH1Config instance with vocab_size, hidden_size, attention heads, and SSM parameters for model initialization', 'build a FalconH1Config with default values for mamba_d_head auto-resolution, multipliers, and key_value_heads', 'test the FalconH1Config.validate_architecture method to verify mamba head dimensions match intermediate size', 'review the FalconH1Config.__post_init__ method that resolves defaults for multipliers, time_step_limit, and key_value_heads', 'summarize the FalconH1Config.layers_block_type property that returns a list of hybrid layer types for all decoder layers', 'convert a mamba_ssm checkpoint directory into HuggingFace FalconH1 format and save to output path', 'build a FalconH1Config from a pretrained mamba_ssm model config with expanded intermediate size', 'map mamba_ssm state dict keys to HuggingFace FalconH1 naming convention using conversion mapping', 'split a combined attn_proj weight tensor into separate q_proj, k_proj, and v_proj tensors', 'run the checkpoint conversion script from command line with input and output directory arguments', 'create a FalconH1ForCausalLM model for autoregressive text generation with past key value caching', 'build a FalconH1Model encoder with embedding tokens, rotary embeddings, and decoder layers', 'run the FalconH1Mixer SSM component with cuda kernels or naive torch forward for sequence modeling', 'test the FalconH1Attention multi-headed attention with rotary position embeddings and kv caching', 'review the FalconH1DecoderLayer combining mixer, attention, and MLP with residual connections and RMSNorm', 'create a FalconH1Model instance from a FalconH1Config for autoregressive language modeling', 'build a FalconH1ForCausalLM model with configurable hidden size, attention heads, and SSM parameters', 'run a forward pass through the FalconH1Model with input_ids, attention_mask, and past_key_values for caching', 'test a FalconH1DecoderLayer with mixed attention and Mamba mixer components and residual connections', 'review the FalconH1Mixer forward method that supports both CUDA kernel fast path and naive PyTorch SSM implementation']
```

Usage

```
{'convert_mamba_ssm_checkpoint': 'convert a mamba_ssm checkpoint directory into HuggingFace FalconH1 format and save to output path', 'build_falcon_h1_config_from_mamba': 'build a FalconH1Config from a pretrained mamba_ssm model config with expanded intermediate size', 'map_mamba_ssm_state_dict_to_hf': 'map mamba_ssm state dict keys to HuggingFace FalconH1 naming convention using conversion mapping', 'split_attention_proj_weights': 'split a combined attn_proj weight tensor into separate q_proj, k_proj, and v_proj tensors', 'run_checkpoint_conversion_cli': 'run the checkpoint conversion script from command line with input and output directory arguments'}
```

## File: huggingface_transformers/src/transformers/models/falcon_h1/modeling_falcon_h1.py

Prompts

```
['create a FalconH1Config instance with vocab_size, hidden_size, attention heads, and SSM parameters for model initialization', 'build a FalconH1Config with default values for mamba_d_head auto-resolution, multipliers, and key_value_heads', 'test the FalconH1Config.validate_architecture method to verify mamba head dimensions match intermediate size', 'review the FalconH1Config.__post_init__ method that resolves defaults for multipliers, time_step_limit, and key_value_heads', 'summarize the FalconH1Config.layers_block_type property that returns a list of hybrid layer types for all decoder layers', 'convert a mamba_ssm checkpoint directory into HuggingFace FalconH1 format and save to output path', 'build a FalconH1Config from a pretrained mamba_ssm model config with expanded intermediate size', 'map mamba_ssm state dict keys to HuggingFace FalconH1 naming convention using conversion mapping', 'split a combined attn_proj weight tensor into separate q_proj, k_proj, and v_proj tensors', 'run the checkpoint conversion script from command line with input and output directory arguments', 'create a FalconH1ForCausalLM model for autoregressive text generation with past key value caching', 'build a FalconH1Model encoder with embedding tokens, rotary embeddings, and decoder layers', 'run the FalconH1Mixer SSM component with cuda kernels or naive torch forward for sequence modeling', 'test the FalconH1Attention multi-headed attention with rotary position embeddings and kv caching', 'review the FalconH1DecoderLayer combining mixer, attention, and MLP with residual connections and RMSNorm', 'create a FalconH1Model instance from a FalconH1Config for autoregressive language modeling', 'build a FalconH1ForCausalLM model with configurable hidden size, attention heads, and SSM parameters', 'run a forward pass through the FalconH1Model with input_ids, attention_mask, and past_key_values for caching', 'test a FalconH1DecoderLayer with mixed attention and Mamba mixer components and residual connections', 'review the FalconH1Mixer forward method that supports both CUDA kernel fast path and naive PyTorch SSM implementation']
```

Usage

```
{'create_falcon_h1_causal_lm': 'create a FalconH1ForCausalLM model for autoregressive text generation with past key value caching', 'build_falcon_h1_encoder': 'build a FalconH1Model encoder with embedding tokens, rotary embeddings, and decoder layers', 'run_falcon_h1_mixer': 'run the FalconH1Mixer SSM component with cuda kernels or naive torch forward for sequence modeling', 'test_falcon_h1_attention': 'test the FalconH1Attention multi-headed attention with rotary position embeddings and kv caching', 'review_falcon_h1_decoder': 'review the FalconH1DecoderLayer combining mixer, attention, and MLP with residual connections and RMSNorm'}
```

## File: huggingface_transformers/src/transformers/models/falcon_h1/modular_falcon_h1.py

Prompts

```
['create a FalconH1Config instance with vocab_size, hidden_size, attention heads, and SSM parameters for model initialization', 'build a FalconH1Config with default values for mamba_d_head auto-resolution, multipliers, and key_value_heads', 'test the FalconH1Config.validate_architecture method to verify mamba head dimensions match intermediate size', 'review the FalconH1Config.__post_init__ method that resolves defaults for multipliers, time_step_limit, and key_value_heads', 'summarize the FalconH1Config.layers_block_type property that returns a list of hybrid layer types for all decoder layers', 'convert a mamba_ssm checkpoint directory into HuggingFace FalconH1 format and save to output path', 'build a FalconH1Config from a pretrained mamba_ssm model config with expanded intermediate size', 'map mamba_ssm state dict keys to HuggingFace FalconH1 naming convention using conversion mapping', 'split a combined attn_proj weight tensor into separate q_proj, k_proj, and v_proj tensors', 'run the checkpoint conversion script from command line with input and output directory arguments', 'create a FalconH1ForCausalLM model for autoregressive text generation with past key value caching', 'build a FalconH1Model encoder with embedding tokens, rotary embeddings, and decoder layers', 'run the FalconH1Mixer SSM component with cuda kernels or naive torch forward for sequence modeling', 'test the FalconH1Attention multi-headed attention with rotary position embeddings and kv caching', 'review the FalconH1DecoderLayer combining mixer, attention, and MLP with residual connections and RMSNorm', 'create a FalconH1Model instance from a FalconH1Config for autoregressive language modeling', 'build a FalconH1ForCausalLM model with configurable hidden size, attention heads, and SSM parameters', 'run a forward pass through the FalconH1Model with input_ids, attention_mask, and past_key_values for caching', 'test a FalconH1DecoderLayer with mixed attention and Mamba mixer components and residual connections', 'review the FalconH1Mixer forward method that supports both CUDA kernel fast path and naive PyTorch SSM implementation']
```

Usage

```
{'create_falcon_h1_model': 'create a FalconH1Model instance from a FalconH1Config for autoregressive language modeling', 'build_falcon_h1_causal_lm': 'build a FalconH1ForCausalLM model with configurable hidden size, attention heads, and SSM parameters', 'run_falcon_h1_forward_pass': 'run a forward pass through the FalconH1Model with input_ids, attention_mask, and past_key_values for caching', 'test_falcon_h1_decoder_layer': 'test a FalconH1DecoderLayer with mixed attention and Mamba mixer components and residual connections', 'review_falcon_h1_mixer_forward': 'review the FalconH1Mixer forward method that supports both CUDA kernel fast path and naive PyTorch SSM implementation'}
```


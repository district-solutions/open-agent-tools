# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/bamba/configuration_bamba.py

Prompts

```
['create a BambaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build a BambaConfig and call validate_architecture to check mamba dimension consistency', 'test the BambaConfig layers_block_type property to determine attention vs mamba layer types', 'review the BambaConfig __post_init__ method for backward compatibility and auto dimension resolution', 'summarize the BambaConfig class as a hybrid mamba2 architecture configuration with SwiGLU', 'run the CLI to convert a mamba_ssm checkpoint directory to a HuggingFace Bamba model', 'convert a state dict from mamba_ssm format to HuggingFace Bamba format by renaming keys and splitting tensors', 'convert a mamba_ssm config dictionary into a HuggingFace BambaConfig object', 'convert a mamba_ssm checkpoint file to a HuggingFace Bamba model with config and safetensors', 'save a sharded state dict into multiple safetensor files with an index JSON', 'create a BambaForCausalLM model with BambaConfig for autoregressive text generation', 'build a BambaModel with mixed mamba and attention decoder layers for efficient sequence modeling', 'run the BambaMixer forward pass using selective state space SSM kernels for convolution and scan', 'test the BambaAttention module with rotary position embeddings and multi-head attention', 'review the BambaDecoderLayer that combines RMSNorm, residual connections, and mamba or attention blocks', 'build a Bamba causal language model with mixed Mamba and attention layers for efficient sequence modeling', 'create a BambaModel forward pass that processes input tokens through mixed Mamba-attention decoder layers with caching', 'run the BambaMixer cuda_kernels_forward path using optimized mamba-ssm and causal-conv1d kernels for GPU inference', 'test a BambaDecoderLayer with configurable layer_type switching between mamba mixer and attention blocks', 'review the BambaForCausalLM class with z-loss support and logits_to_keep for efficient next-token generation']
```

Usage

```
{'create_BambaConfig': 'create a BambaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build_BambaConfig_validate': 'build a BambaConfig and call validate_architecture to check mamba dimension consistency', 'test_BambaConfig_layers_block_type': 'test the BambaConfig layers_block_type property to determine attention vs mamba layer types', 'review_BambaConfig_post_init': 'review the BambaConfig __post_init__ method for backward compatibility and auto dimension resolution', 'summarize_BambaConfig': 'summarize the BambaConfig class as a hybrid mamba2 architecture configuration with SwiGLU'}
```

## File: huggingface_transformers/src/transformers/models/bamba/convert_mamba_ssm_checkpoint.py

Prompts

```
['create a BambaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build a BambaConfig and call validate_architecture to check mamba dimension consistency', 'test the BambaConfig layers_block_type property to determine attention vs mamba layer types', 'review the BambaConfig __post_init__ method for backward compatibility and auto dimension resolution', 'summarize the BambaConfig class as a hybrid mamba2 architecture configuration with SwiGLU', 'run the CLI to convert a mamba_ssm checkpoint directory to a HuggingFace Bamba model', 'convert a state dict from mamba_ssm format to HuggingFace Bamba format by renaming keys and splitting tensors', 'convert a mamba_ssm config dictionary into a HuggingFace BambaConfig object', 'convert a mamba_ssm checkpoint file to a HuggingFace Bamba model with config and safetensors', 'save a sharded state dict into multiple safetensor files with an index JSON', 'create a BambaForCausalLM model with BambaConfig for autoregressive text generation', 'build a BambaModel with mixed mamba and attention decoder layers for efficient sequence modeling', 'run the BambaMixer forward pass using selective state space SSM kernels for convolution and scan', 'test the BambaAttention module with rotary position embeddings and multi-head attention', 'review the BambaDecoderLayer that combines RMSNorm, residual connections, and mamba or attention blocks', 'build a Bamba causal language model with mixed Mamba and attention layers for efficient sequence modeling', 'create a BambaModel forward pass that processes input tokens through mixed Mamba-attention decoder layers with caching', 'run the BambaMixer cuda_kernels_forward path using optimized mamba-ssm and causal-conv1d kernels for GPU inference', 'test a BambaDecoderLayer with configurable layer_type switching between mamba mixer and attention blocks', 'review the BambaForCausalLM class with z-loss support and logits_to_keep for efficient next-token generation']
```

Usage

```
{'convert_mamba_ssm_checkpoint_cli': 'run the CLI to convert a mamba_ssm checkpoint directory to a HuggingFace Bamba model', 'convert_state_dict_from_mamba_ssm': 'convert a state dict from mamba_ssm format to HuggingFace Bamba format by renaming keys and splitting tensors', 'convert_ssm_config_to_hf_config': 'convert a mamba_ssm config dictionary into a HuggingFace BambaConfig object', 'convert_mamba_ssm_checkpoint_file_to_huggingface_model_file': 'convert a mamba_ssm checkpoint file to a HuggingFace Bamba model with config and safetensors', 'save_sharded_safetensors': 'save a sharded state dict into multiple safetensor files with an index JSON'}
```

## File: huggingface_transformers/src/transformers/models/bamba/modeling_bamba.py

Prompts

```
['create a BambaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build a BambaConfig and call validate_architecture to check mamba dimension consistency', 'test the BambaConfig layers_block_type property to determine attention vs mamba layer types', 'review the BambaConfig __post_init__ method for backward compatibility and auto dimension resolution', 'summarize the BambaConfig class as a hybrid mamba2 architecture configuration with SwiGLU', 'run the CLI to convert a mamba_ssm checkpoint directory to a HuggingFace Bamba model', 'convert a state dict from mamba_ssm format to HuggingFace Bamba format by renaming keys and splitting tensors', 'convert a mamba_ssm config dictionary into a HuggingFace BambaConfig object', 'convert a mamba_ssm checkpoint file to a HuggingFace Bamba model with config and safetensors', 'save a sharded state dict into multiple safetensor files with an index JSON', 'create a BambaForCausalLM model with BambaConfig for autoregressive text generation', 'build a BambaModel with mixed mamba and attention decoder layers for efficient sequence modeling', 'run the BambaMixer forward pass using selective state space SSM kernels for convolution and scan', 'test the BambaAttention module with rotary position embeddings and multi-head attention', 'review the BambaDecoderLayer that combines RMSNorm, residual connections, and mamba or attention blocks', 'build a Bamba causal language model with mixed Mamba and attention layers for efficient sequence modeling', 'create a BambaModel forward pass that processes input tokens through mixed Mamba-attention decoder layers with caching', 'run the BambaMixer cuda_kernels_forward path using optimized mamba-ssm and causal-conv1d kernels for GPU inference', 'test a BambaDecoderLayer with configurable layer_type switching between mamba mixer and attention blocks', 'review the BambaForCausalLM class with z-loss support and logits_to_keep for efficient next-token generation']
```

Usage

```
{'create_bamba_causal_lm': 'create a BambaForCausalLM model with BambaConfig for autoregressive text generation', 'build_bamba_model': 'build a BambaModel with mixed mamba and attention decoder layers for efficient sequence modeling', 'run_bamba_mixer_ssm': 'run the BambaMixer forward pass using selective state space SSM kernels for convolution and scan', 'test_bamba_attention': 'test the BambaAttention module with rotary position embeddings and multi-head attention', 'review_bamba_decoder_layer': 'review the BambaDecoderLayer that combines RMSNorm, residual connections, and mamba or attention blocks'}
```

## File: huggingface_transformers/src/transformers/models/bamba/modular_bamba.py

Prompts

```
['create a BambaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build a BambaConfig and call validate_architecture to check mamba dimension consistency', 'test the BambaConfig layers_block_type property to determine attention vs mamba layer types', 'review the BambaConfig __post_init__ method for backward compatibility and auto dimension resolution', 'summarize the BambaConfig class as a hybrid mamba2 architecture configuration with SwiGLU', 'run the CLI to convert a mamba_ssm checkpoint directory to a HuggingFace Bamba model', 'convert a state dict from mamba_ssm format to HuggingFace Bamba format by renaming keys and splitting tensors', 'convert a mamba_ssm config dictionary into a HuggingFace BambaConfig object', 'convert a mamba_ssm checkpoint file to a HuggingFace Bamba model with config and safetensors', 'save a sharded state dict into multiple safetensor files with an index JSON', 'create a BambaForCausalLM model with BambaConfig for autoregressive text generation', 'build a BambaModel with mixed mamba and attention decoder layers for efficient sequence modeling', 'run the BambaMixer forward pass using selective state space SSM kernels for convolution and scan', 'test the BambaAttention module with rotary position embeddings and multi-head attention', 'review the BambaDecoderLayer that combines RMSNorm, residual connections, and mamba or attention blocks', 'build a Bamba causal language model with mixed Mamba and attention layers for efficient sequence modeling', 'create a BambaModel forward pass that processes input tokens through mixed Mamba-attention decoder layers with caching', 'run the BambaMixer cuda_kernels_forward path using optimized mamba-ssm and causal-conv1d kernels for GPU inference', 'test a BambaDecoderLayer with configurable layer_type switching between mamba mixer and attention blocks', 'review the BambaForCausalLM class with z-loss support and logits_to_keep for efficient next-token generation']
```

Usage

```
{'build_bamba_causal_lm': 'build a Bamba causal language model with mixed Mamba and attention layers for efficient sequence modeling', 'create_bamba_model_forward': 'create a BambaModel forward pass that processes input tokens through mixed Mamba-attention decoder layers with caching', 'run_bamba_mixer_cuda': 'run the BambaMixer cuda_kernels_forward path using optimized mamba-ssm and causal-conv1d kernels for GPU inference', 'test_bamba_decoder_layer': 'test a BambaDecoderLayer with configurable layer_type switching between mamba mixer and attention blocks', 'review_bamba_for_causal_lm': 'review the BambaForCausalLM class with z-loss support and logits_to_keep for efficient next-token generation'}
```


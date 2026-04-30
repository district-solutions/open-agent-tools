# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/zamba/configuration_zamba.py

Prompts

```
['create a ZambaConfig instance with custom hidden_size, num_hidden_layers, and vocab_size', 'build a ZambaConfig from pretrained checkpoint Zyphra/Zamba-7B-v1 with default architecture settings', 'test the ZambaConfig validate_architecture method to verify mamba_expand and n_mamba_heads divisibility', 'review the ZambaConfig __post_init__ method that computes attention_head_dim and layers_block_type', 'summarize how ZambaConfig._layers_block_type generates alternating mamba and hybrid layer sequences', 'create a ZambaForCausalLM model for autoregressive text generation from pretrained weights', 'create a ZambaForSequenceClassification model for text classification with configurable number of labels', 'build a forward pass through the ZambaModel transformer with input_ids and attention_mask', 'run the ZambaMambaMixer SSM module with fast CUDA kernels or slow PyTorch fallback for state space modeling', 'review the ZambaHybridLayer that combines shared transformer and Mamba decoder blocks in hybrid architecture']
```

Usage

```
{'create_zamba_config': 'create a ZambaConfig instance with custom hidden_size, num_hidden_layers, and vocab_size', 'build_zamba_config_from_pretrained': 'build a ZambaConfig from pretrained checkpoint Zyphra/Zamba-7B-v1 with default architecture settings', 'test_zamba_config_validation': 'test the ZambaConfig validate_architecture method to verify mamba_expand and n_mamba_heads divisibility', 'review_zamba_config_post_init': 'review the ZambaConfig __post_init__ method that computes attention_head_dim and layers_block_type', 'summarize_zamba_config_layers': 'summarize how ZambaConfig._layers_block_type generates alternating mamba and hybrid layer sequences'}
```

## File: huggingface_transformers/src/transformers/models/zamba/modeling_zamba.py

Prompts

```
['create a ZambaConfig instance with custom hidden_size, num_hidden_layers, and vocab_size', 'build a ZambaConfig from pretrained checkpoint Zyphra/Zamba-7B-v1 with default architecture settings', 'test the ZambaConfig validate_architecture method to verify mamba_expand and n_mamba_heads divisibility', 'review the ZambaConfig __post_init__ method that computes attention_head_dim and layers_block_type', 'summarize how ZambaConfig._layers_block_type generates alternating mamba and hybrid layer sequences', 'create a ZambaForCausalLM model for autoregressive text generation from pretrained weights', 'create a ZambaForSequenceClassification model for text classification with configurable number of labels', 'build a forward pass through the ZambaModel transformer with input_ids and attention_mask', 'run the ZambaMambaMixer SSM module with fast CUDA kernels or slow PyTorch fallback for state space modeling', 'review the ZambaHybridLayer that combines shared transformer and Mamba decoder blocks in hybrid architecture']
```

Usage

```
{'create_zamba_causal_lm': 'create a ZambaForCausalLM model for autoregressive text generation from pretrained weights', 'create_zamba_sequence_classifier': 'create a ZambaForSequenceClassification model for text classification with configurable number of labels', 'build_zamba_model_forward': 'build a forward pass through the ZambaModel transformer with input_ids and attention_mask', 'run_zamba_mamba_mixer': 'run the ZambaMambaMixer SSM module with fast CUDA kernels or slow PyTorch fallback for state space modeling', 'review_zamba_hybrid_layer': 'review the ZambaHybridLayer that combines shared transformer and Mamba decoder blocks in hybrid architecture'}
```


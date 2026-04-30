# Agent Python Tools

- repo: vllm-project/llm-compressor
- repo_uri: https://github.com/vllm-project/llm-compressor

## File: vllm-project_llm-compressor/src/llmcompressor/modeling/deepseekv32/config.py

Prompts

```
['create a ModelConfig instance with default hyperparameters for the deepseek_v32 model', 'create a ModelConfig instance with custom moe and mla hyperparameters for deepseek_v32', 'create a ModelConfig instance configured for fp8 dtype and custom sequence length', 'create a ModelConfig instance with YARN rotary embedding scaling factors for extended context', 'summarize the ModelConfig class attributes including moe, mla, yarn, and index hyperparameters', 'run the bf16_index function to compute ReLU-weighted index scores between query and key tensors using einsum', 'create a DeepSeek V3.2 causal language model with MLA attention and MoE feed-forward layers', 'build a Transformer model with parallel embedding, RMSNorm, rotary embeddings, and stacked MoE blocks', 'run Multi-Head Latent Attention with indexer-based sparse token selection for efficient decoding', 'build a Mixture-of-Experts module with gating, expert selection, and shared experts for sparse computation', 'test rotary positional embedding application with precomputed complex frequency tensors']
```

Usage

```
{'create_config_deepseekv32': 'create a ModelConfig instance with default hyperparameters for the deepseek_v32 model', 'create_config_custom_params': 'create a ModelConfig instance with custom moe and mla hyperparameters for deepseek_v32', 'create_config_fp8_dtype': 'create a ModelConfig instance configured for fp8 dtype and custom sequence length', 'create_config_yarn_ext': 'create a ModelConfig instance with YARN rotary embedding scaling factors for extended context', 'summarize_model_config': 'summarize the ModelConfig class attributes including moe, mla, yarn, and index hyperparameters'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modeling/deepseekv32/kernel.py

Prompts

```
['create a ModelConfig instance with default hyperparameters for the deepseek_v32 model', 'create a ModelConfig instance with custom moe and mla hyperparameters for deepseek_v32', 'create a ModelConfig instance configured for fp8 dtype and custom sequence length', 'create a ModelConfig instance with YARN rotary embedding scaling factors for extended context', 'summarize the ModelConfig class attributes including moe, mla, yarn, and index hyperparameters', 'run the bf16_index function to compute ReLU-weighted index scores between query and key tensors using einsum', 'create a DeepSeek V3.2 causal language model with MLA attention and MoE feed-forward layers', 'build a Transformer model with parallel embedding, RMSNorm, rotary embeddings, and stacked MoE blocks', 'run Multi-Head Latent Attention with indexer-based sparse token selection for efficient decoding', 'build a Mixture-of-Experts module with gating, expert selection, and shared experts for sparse computation', 'test rotary positional embedding application with precomputed complex frequency tensors']
```

Usage

```
{'run_bf16_index': 'run the bf16_index function to compute ReLU-weighted index scores between query and key tensors using einsum'}
```

## File: vllm-project_llm-compressor/src/llmcompressor/modeling/deepseekv32/model.py

Prompts

```
['create a ModelConfig instance with default hyperparameters for the deepseek_v32 model', 'create a ModelConfig instance with custom moe and mla hyperparameters for deepseek_v32', 'create a ModelConfig instance configured for fp8 dtype and custom sequence length', 'create a ModelConfig instance with YARN rotary embedding scaling factors for extended context', 'summarize the ModelConfig class attributes including moe, mla, yarn, and index hyperparameters', 'run the bf16_index function to compute ReLU-weighted index scores between query and key tensors using einsum', 'create a DeepSeek V3.2 causal language model with MLA attention and MoE feed-forward layers', 'build a Transformer model with parallel embedding, RMSNorm, rotary embeddings, and stacked MoE blocks', 'run Multi-Head Latent Attention with indexer-based sparse token selection for efficient decoding', 'build a Mixture-of-Experts module with gating, expert selection, and shared experts for sparse computation', 'test rotary positional embedding application with precomputed complex frequency tensors']
```

Usage

```
{'create_model_deepseek_v32_causal_lm': 'create a DeepSeek V3.2 causal language model with MLA attention and MoE feed-forward layers', 'build_transformer_deepseek_v32': 'build a Transformer model with parallel embedding, RMSNorm, rotary embeddings, and stacked MoE blocks', 'run_mla_attention_with_indexer': 'run Multi-Head Latent Attention with indexer-based sparse token selection for efficient decoding', 'build_moe_expert_routing': 'build a Mixture-of-Experts module with gating, expert selection, and shared experts for sparse computation', 'test_rotary_positional_embeddings': 'test rotary positional embedding application with precomputed complex frequency tensors'}
```


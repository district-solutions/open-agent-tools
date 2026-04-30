# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/llama/configuration_llama.py

Prompts

```
['create a LlamaConfig instance with custom model parameters for initializing a LLaMA model', 'initialize a LlamaConfig with default llama-7b style configuration values', 'validate the LlamaConfig architecture ensuring hidden size is a multiple of attention heads', 'configure LlamaConfig with separate num_key_value_heads for grouped query attention', 'set rope_parameters on LlamaConfig for custom rotary embedding configuration', 'run the CLI script to convert Llama model weights from original format to HuggingFace Transformers format', 'build a HuggingFace Llama model by converting original Llama checkpoint weights to HF format with sharded or unsharded loading', 'convert a Llama SentencePiece or TikToken tokenizer to HuggingFace PreTrainedTokenizerFast format with special tokens and chat templates', 'create a Llama3Converter tokenizer instance that extends TikTokenConverter with Llama-3 special tokens and chat template support', 'summarize the write_model function that loads Llama checkpoint shards, permutes attention weights, and saves as HuggingFace PyTorch model', 'create a LlamaForCausalLM model for autoregressive text generation with configurable layers and attention heads', 'build a LlamaDecoderLayer with self-attention, MLP, and residual connections for transformer inference', 'test the LlamaAttention class with multi-head attention, RoPE embeddings, and KV-cache support', 'review the LlamaRotaryEmbedding class that computes rotary position embeddings for query and key tensors', 'summarize the LlamaMLP class implementing gated linear unit feed-forward network with gate and up projections']
```

Usage

```
{'create_LlamaConfig': 'create a LlamaConfig instance with custom model parameters for initializing a LLaMA model', 'initialize_LlamaConfig_defaults': 'initialize a LlamaConfig with default llama-7b style configuration values', 'validate_LlamaConfig_architecture': 'validate the LlamaConfig architecture ensuring hidden size is a multiple of attention heads', 'configure_LlamaConfig_KV_heads': 'configure LlamaConfig with separate num_key_value_heads for grouped query attention', 'set_LlamaConfig_rope_parameters': 'set rope_parameters on LlamaConfig for custom rotary embedding configuration'}
```

## File: huggingface_transformers/src/transformers/models/llama/convert_llama_weights_to_hf.py

Prompts

```
['create a LlamaConfig instance with custom model parameters for initializing a LLaMA model', 'initialize a LlamaConfig with default llama-7b style configuration values', 'validate the LlamaConfig architecture ensuring hidden size is a multiple of attention heads', 'configure LlamaConfig with separate num_key_value_heads for grouped query attention', 'set rope_parameters on LlamaConfig for custom rotary embedding configuration', 'run the CLI script to convert Llama model weights from original format to HuggingFace Transformers format', 'build a HuggingFace Llama model by converting original Llama checkpoint weights to HF format with sharded or unsharded loading', 'convert a Llama SentencePiece or TikToken tokenizer to HuggingFace PreTrainedTokenizerFast format with special tokens and chat templates', 'create a Llama3Converter tokenizer instance that extends TikTokenConverter with Llama-3 special tokens and chat template support', 'summarize the write_model function that loads Llama checkpoint shards, permutes attention weights, and saves as HuggingFace PyTorch model', 'create a LlamaForCausalLM model for autoregressive text generation with configurable layers and attention heads', 'build a LlamaDecoderLayer with self-attention, MLP, and residual connections for transformer inference', 'test the LlamaAttention class with multi-head attention, RoPE embeddings, and KV-cache support', 'review the LlamaRotaryEmbedding class that computes rotary position embeddings for query and key tensors', 'summarize the LlamaMLP class implementing gated linear unit feed-forward network with gate and up projections']
```

Usage

```
{'run_convert_llama_weights_cli': 'run the CLI script to convert Llama model weights from original format to HuggingFace Transformers format', 'build_model_with_write_model': 'build a HuggingFace Llama model by converting original Llama checkpoint weights to HF format with sharded or unsharded loading', 'convert_tokenizer_with_write_tokenizer': 'convert a Llama SentencePiece or TikToken tokenizer to HuggingFace PreTrainedTokenizerFast format with special tokens and chat templates', 'create_llama3_converter': 'create a Llama3Converter tokenizer instance that extends TikTokenConverter with Llama-3 special tokens and chat template support', 'summarize_write_model': 'summarize the write_model function that loads Llama checkpoint shards, permutes attention weights, and saves as HuggingFace PyTorch model'}
```

## File: huggingface_transformers/src/transformers/models/llama/modeling_llama.py

Prompts

```
['create a LlamaConfig instance with custom model parameters for initializing a LLaMA model', 'initialize a LlamaConfig with default llama-7b style configuration values', 'validate the LlamaConfig architecture ensuring hidden size is a multiple of attention heads', 'configure LlamaConfig with separate num_key_value_heads for grouped query attention', 'set rope_parameters on LlamaConfig for custom rotary embedding configuration', 'run the CLI script to convert Llama model weights from original format to HuggingFace Transformers format', 'build a HuggingFace Llama model by converting original Llama checkpoint weights to HF format with sharded or unsharded loading', 'convert a Llama SentencePiece or TikToken tokenizer to HuggingFace PreTrainedTokenizerFast format with special tokens and chat templates', 'create a Llama3Converter tokenizer instance that extends TikTokenConverter with Llama-3 special tokens and chat template support', 'summarize the write_model function that loads Llama checkpoint shards, permutes attention weights, and saves as HuggingFace PyTorch model', 'create a LlamaForCausalLM model for autoregressive text generation with configurable layers and attention heads', 'build a LlamaDecoderLayer with self-attention, MLP, and residual connections for transformer inference', 'test the LlamaAttention class with multi-head attention, RoPE embeddings, and KV-cache support', 'review the LlamaRotaryEmbedding class that computes rotary position embeddings for query and key tensors', 'summarize the LlamaMLP class implementing gated linear unit feed-forward network with gate and up projections']
```

Usage

```
{'create_llama_for_causal_lm': 'create a LlamaForCausalLM model for autoregressive text generation with configurable layers and attention heads', 'build_llama_decoder_layer': 'build a LlamaDecoderLayer with self-attention, MLP, and residual connections for transformer inference', 'test_llama_attention': 'test the LlamaAttention class with multi-head attention, RoPE embeddings, and KV-cache support', 'review_llama_rotary_embedding': 'review the LlamaRotaryEmbedding class that computes rotary position embeddings for query and key tensors', 'summarize_llama_mlp': 'summarize the LlamaMLP class implementing gated linear unit feed-forward network with gate and up projections'}
```


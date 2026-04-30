# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/nanochat/convert_nanochat_checkpoints.py

Prompts

```
['convert a NanoChat model checkpoint from original format to HuggingFace format using input and output directories', 'convert NanoChat model weights from original checkpoint to HuggingFace format with automatic key-value head inference', 'convert a NanoChat tokenizer from pickle or JSON format to HuggingFace tokenizer format', 'run a quick generation test on a converted NanoChat model with a given prompt to verify correctness', 'load a NanoChatConfig from meta_*.json or config.json in a checkpoint directory with parameter mapping', 'create a NanoChatForCausalLM model with config for text generation using HuggingFace Transformers', 'build a NanoChatModel with embedding tokens, decoder layers, RMS norm and rotary embeddings', 'test the NanoChatAttention class with multi-head attention, GQA, query key value projections and RMS norm', 'run text generation with NanoChatForCausalLM using tokenizer apply_chat_template and model generate', 'review the NanoChatDecoderLayer with input layernorm, self attention, post attention layernorm and MLP residual connections', 'build a causal language model using NanoChatForCausalLM to generate text from chat conversations', 'create a NanoChatModel base model with RMSNorm, rotary embeddings, and decoder layers for forward inference', 'test the NanoChatAttention module that applies RoPE then layer normalization before attention computation', 'review the NanoChatDecoderLayer class with input and post-attention RMS normalization layers', 'summarize the NanoChatMLP feedforward network with bias-less fc1 and fc2 linear projections']
```

Usage

```
{'convert_nanochat_checkpoint': 'convert a NanoChat model checkpoint from original format to HuggingFace format using input and output directories', 'write_model_convert': 'convert NanoChat model weights from original checkpoint to HuggingFace format with automatic key-value head inference', 'write_tokenizer_convert': 'convert a NanoChat tokenizer from pickle or JSON format to HuggingFace tokenizer format', 'run_test_generation': 'run a quick generation test on a converted NanoChat model with a given prompt to verify correctness', 'load_config_from_checkpoint': 'load a NanoChatConfig from meta_*.json or config.json in a checkpoint directory with parameter mapping'}
```

## File: huggingface_transformers/src/transformers/models/nanochat/modeling_nanochat.py

Prompts

```
['convert a NanoChat model checkpoint from original format to HuggingFace format using input and output directories', 'convert NanoChat model weights from original checkpoint to HuggingFace format with automatic key-value head inference', 'convert a NanoChat tokenizer from pickle or JSON format to HuggingFace tokenizer format', 'run a quick generation test on a converted NanoChat model with a given prompt to verify correctness', 'load a NanoChatConfig from meta_*.json or config.json in a checkpoint directory with parameter mapping', 'create a NanoChatForCausalLM model with config for text generation using HuggingFace Transformers', 'build a NanoChatModel with embedding tokens, decoder layers, RMS norm and rotary embeddings', 'test the NanoChatAttention class with multi-head attention, GQA, query key value projections and RMS norm', 'run text generation with NanoChatForCausalLM using tokenizer apply_chat_template and model generate', 'review the NanoChatDecoderLayer with input layernorm, self attention, post attention layernorm and MLP residual connections', 'build a causal language model using NanoChatForCausalLM to generate text from chat conversations', 'create a NanoChatModel base model with RMSNorm, rotary embeddings, and decoder layers for forward inference', 'test the NanoChatAttention module that applies RoPE then layer normalization before attention computation', 'review the NanoChatDecoderLayer class with input and post-attention RMS normalization layers', 'summarize the NanoChatMLP feedforward network with bias-less fc1 and fc2 linear projections']
```

Usage

```
{'create_nanochat_causal_lm': 'create a NanoChatForCausalLM model with config for text generation using HuggingFace Transformers', 'build_nanochat_model': 'build a NanoChatModel with embedding tokens, decoder layers, RMS norm and rotary embeddings', 'test_nanochat_attention': 'test the NanoChatAttention class with multi-head attention, GQA, query key value projections and RMS norm', 'run_nanochat_generate': 'run text generation with NanoChatForCausalLM using tokenizer apply_chat_template and model generate', 'review_nanochat_decoder_layer': 'review the NanoChatDecoderLayer with input layernorm, self attention, post attention layernorm and MLP residual connections'}
```

## File: huggingface_transformers/src/transformers/models/nanochat/modular_nanochat.py

Prompts

```
['convert a NanoChat model checkpoint from original format to HuggingFace format using input and output directories', 'convert NanoChat model weights from original checkpoint to HuggingFace format with automatic key-value head inference', 'convert a NanoChat tokenizer from pickle or JSON format to HuggingFace tokenizer format', 'run a quick generation test on a converted NanoChat model with a given prompt to verify correctness', 'load a NanoChatConfig from meta_*.json or config.json in a checkpoint directory with parameter mapping', 'create a NanoChatForCausalLM model with config for text generation using HuggingFace Transformers', 'build a NanoChatModel with embedding tokens, decoder layers, RMS norm and rotary embeddings', 'test the NanoChatAttention class with multi-head attention, GQA, query key value projections and RMS norm', 'run text generation with NanoChatForCausalLM using tokenizer apply_chat_template and model generate', 'review the NanoChatDecoderLayer with input layernorm, self attention, post attention layernorm and MLP residual connections', 'build a causal language model using NanoChatForCausalLM to generate text from chat conversations', 'create a NanoChatModel base model with RMSNorm, rotary embeddings, and decoder layers for forward inference', 'test the NanoChatAttention module that applies RoPE then layer normalization before attention computation', 'review the NanoChatDecoderLayer class with input and post-attention RMS normalization layers', 'summarize the NanoChatMLP feedforward network with bias-less fc1 and fc2 linear projections']
```

Usage

```
{'build_NanoChatForCausalLM': 'build a causal language model using NanoChatForCausalLM to generate text from chat conversations', 'create_NanoChatModel': 'create a NanoChatModel base model with RMSNorm, rotary embeddings, and decoder layers for forward inference', 'test_NanoChatAttention': 'test the NanoChatAttention module that applies RoPE then layer normalization before attention computation', 'review_NanoChatDecoderLayer': 'review the NanoChatDecoderLayer class with input and post-attention RMS normalization layers', 'summarize_NanoChatMLP': 'summarize the NanoChatMLP feedforward network with bias-less fc1 and fc2 linear projections'}
```


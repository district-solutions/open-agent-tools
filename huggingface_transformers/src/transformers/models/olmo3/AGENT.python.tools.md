# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/olmo3/convert_olmo3_weights_to_hf.py

Prompts

```
['convert OLMo 3 model weights from EleutherAI format to HuggingFace transformers format using argparse CLI', 'build a HuggingFace Olmo3ForCausalLM model from distributed checkpoint weights and config', 'load OLMo 3 model weights from a distributed checkpoint folder using RemoteFileSystemReader', 'write OLMo 3 model weights and tokenizer to HuggingFace transformers model format', 'read OLMo 3 configuration JSON from the input checkpoint directory', 'create an Olmo3ForCausalLM model from a configuration and generate text from a prompt', 'build an Olmo3Model with embedding, attention, and MLP layers for forward pass inference', 'test the Olmo3Attention module with query, key, value projections and rotary position embeddings', 'review the Olmo3DecoderLayer class with self-attention, MLP, and residual connection blocks', 'summarize the Olmo3RotaryEmbedding class that computes cosine and sine position embeddings', 'create an Olmo3Config instance with custom model parameters like hidden size and number of layers', 'run Olmo3ForCausalLM for autoregressive text generation with past key value caching']
```

Usage

```
{'convert_olmo3_weights_to_hf': 'convert OLMo 3 model weights from EleutherAI format to HuggingFace transformers format using argparse CLI', 'build_olmo3_model_from_checkpoint': 'build a HuggingFace Olmo3ForCausalLM model from distributed checkpoint weights and config', 'load_olmo3_distributed_checkpoint': 'load OLMo 3 model weights from a distributed checkpoint folder using RemoteFileSystemReader', 'write_olmo3_model_to_hf_format': 'write OLMo 3 model weights and tokenizer to HuggingFace transformers model format', 'read_olmo3_config_json': 'read OLMo 3 configuration JSON from the input checkpoint directory'}
```

## File: huggingface_transformers/src/transformers/models/olmo3/modeling_olmo3.py

Prompts

```
['convert OLMo 3 model weights from EleutherAI format to HuggingFace transformers format using argparse CLI', 'build a HuggingFace Olmo3ForCausalLM model from distributed checkpoint weights and config', 'load OLMo 3 model weights from a distributed checkpoint folder using RemoteFileSystemReader', 'write OLMo 3 model weights and tokenizer to HuggingFace transformers model format', 'read OLMo 3 configuration JSON from the input checkpoint directory', 'create an Olmo3ForCausalLM model from a configuration and generate text from a prompt', 'build an Olmo3Model with embedding, attention, and MLP layers for forward pass inference', 'test the Olmo3Attention module with query, key, value projections and rotary position embeddings', 'review the Olmo3DecoderLayer class with self-attention, MLP, and residual connection blocks', 'summarize the Olmo3RotaryEmbedding class that computes cosine and sine position embeddings', 'create an Olmo3Config instance with custom model parameters like hidden size and number of layers', 'run Olmo3ForCausalLM for autoregressive text generation with past key value caching']
```

Usage

```
{'create_olmo3_causal_lm': 'create an Olmo3ForCausalLM model from a configuration and generate text from a prompt', 'build_olmo3_model': 'build an Olmo3Model with embedding, attention, and MLP layers for forward pass inference', 'test_olmo3_attention': 'test the Olmo3Attention module with query, key, value projections and rotary position embeddings', 'review_olmo3_decoder_layer': 'review the Olmo3DecoderLayer class with self-attention, MLP, and residual connection blocks', 'summarize_olmo3_rope': 'summarize the Olmo3RotaryEmbedding class that computes cosine and sine position embeddings'}
```

## File: huggingface_transformers/src/transformers/models/olmo3/modular_olmo3.py

Prompts

```
['convert OLMo 3 model weights from EleutherAI format to HuggingFace transformers format using argparse CLI', 'build a HuggingFace Olmo3ForCausalLM model from distributed checkpoint weights and config', 'load OLMo 3 model weights from a distributed checkpoint folder using RemoteFileSystemReader', 'write OLMo 3 model weights and tokenizer to HuggingFace transformers model format', 'read OLMo 3 configuration JSON from the input checkpoint directory', 'create an Olmo3ForCausalLM model from a configuration and generate text from a prompt', 'build an Olmo3Model with embedding, attention, and MLP layers for forward pass inference', 'test the Olmo3Attention module with query, key, value projections and rotary position embeddings', 'review the Olmo3DecoderLayer class with self-attention, MLP, and residual connection blocks', 'summarize the Olmo3RotaryEmbedding class that computes cosine and sine position embeddings', 'create an Olmo3Config instance with custom model parameters like hidden size and number of layers', 'run Olmo3ForCausalLM for autoregressive text generation with past key value caching']
```

Usage

```
{'create_olmo3_config': 'create an Olmo3Config instance with custom model parameters like hidden size and number of layers', 'build_olmo3_model': 'build an Olmo3Model from an Olmo3Config with sliding window attention across decoder layers', 'run_olmo3_causal_lm': 'run Olmo3ForCausalLM for autoregressive text generation with past key value caching', 'test_olmo3_attention': 'test Olmo3Attention with sliding window or full attention modes per layer configuration', 'review_olmo3_decoder_layer': 'review Olmo3DecoderLayer that composes sliding window and full attention transformer blocks'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/ministral3/convert_ministral3_weights_to_hf.py

Prompts

```
['convert Ministral3 model weights from original format to HuggingFace transformers format', 'convert a Ministral3 state dict from original format to HuggingFace format with ROPE permutation', 'convert Ministral3 original config dictionary to HuggingFace Ministral3Config or Mistral3Config', 'convert and write Ministral3 model weights from input directory to HuggingFace output directory', 'convert and write Ministral3 tokenizer and image processor to HuggingFace output directory', 'build a Ministral3ForCausalLM model for autoregressive text generation with past key values caching', 'create a Ministral3Model transformer encoder with rotary embeddings and sliding window attention', 'run Ministral3Attention multi-headed attention with GQA, RoPE embeddings, and configurable scaling', 'test Ministral3DecoderLayer with pre-norm residuals, MLP, and RMSNorm layers', 'review Ministral3RotaryEmbedding with dynamic RoPE initialization and position-aware scaling', 'create a Ministral3ForCausalLM model for autoregressive text generation with RoPE scaling', 'build a Ministral3Attention module with Llama-4-style attention scaling and rotary position embeddings', 'test the Ministral3ForSequenceClassification head for sequence-level prediction tasks', 'run the Ministral3ForTokenClassification head for token-level labeling tasks']
```

Usage

```
{'convert_ministral3_weights_to_hf': 'convert Ministral3 model weights from original format to HuggingFace transformers format', 'convert_state_dict': 'convert a Ministral3 state dict from original format to HuggingFace format with ROPE permutation', 'convert_config': 'convert Ministral3 original config dictionary to HuggingFace Ministral3Config or Mistral3Config', 'convert_and_write_model': 'convert and write Ministral3 model weights from input directory to HuggingFace output directory', 'convert_and_write_processor_and_tokenizer': 'convert and write Ministral3 tokenizer and image processor to HuggingFace output directory'}
```

## File: huggingface_transformers/src/transformers/models/ministral3/modeling_ministral3.py

Prompts

```
['convert Ministral3 model weights from original format to HuggingFace transformers format', 'convert a Ministral3 state dict from original format to HuggingFace format with ROPE permutation', 'convert Ministral3 original config dictionary to HuggingFace Ministral3Config or Mistral3Config', 'convert and write Ministral3 model weights from input directory to HuggingFace output directory', 'convert and write Ministral3 tokenizer and image processor to HuggingFace output directory', 'build a Ministral3ForCausalLM model for autoregressive text generation with past key values caching', 'create a Ministral3Model transformer encoder with rotary embeddings and sliding window attention', 'run Ministral3Attention multi-headed attention with GQA, RoPE embeddings, and configurable scaling', 'test Ministral3DecoderLayer with pre-norm residuals, MLP, and RMSNorm layers', 'review Ministral3RotaryEmbedding with dynamic RoPE initialization and position-aware scaling', 'create a Ministral3ForCausalLM model for autoregressive text generation with RoPE scaling', 'build a Ministral3Attention module with Llama-4-style attention scaling and rotary position embeddings', 'test the Ministral3ForSequenceClassification head for sequence-level prediction tasks', 'run the Ministral3ForTokenClassification head for token-level labeling tasks']
```

Usage

```
{'build_ministral3_causal_lm': 'build a Ministral3ForCausalLM model for autoregressive text generation with past key values caching', 'create_ministral3_model': 'create a Ministral3Model transformer encoder with rotary embeddings and sliding window attention', 'run_ministral3_attention': 'run Ministral3Attention multi-headed attention with GQA, RoPE embeddings, and configurable scaling', 'test_ministral3_decoder_layer': 'test Ministral3DecoderLayer with pre-norm residuals, MLP, and RMSNorm layers', 'review_ministral3_rope_embedding': 'review Ministral3RotaryEmbedding with dynamic RoPE initialization and position-aware scaling'}
```

## File: huggingface_transformers/src/transformers/models/ministral3/modular_ministral3.py

Prompts

```
['convert Ministral3 model weights from original format to HuggingFace transformers format', 'convert a Ministral3 state dict from original format to HuggingFace format with ROPE permutation', 'convert Ministral3 original config dictionary to HuggingFace Ministral3Config or Mistral3Config', 'convert and write Ministral3 model weights from input directory to HuggingFace output directory', 'convert and write Ministral3 tokenizer and image processor to HuggingFace output directory', 'build a Ministral3ForCausalLM model for autoregressive text generation with past key values caching', 'create a Ministral3Model transformer encoder with rotary embeddings and sliding window attention', 'run Ministral3Attention multi-headed attention with GQA, RoPE embeddings, and configurable scaling', 'test Ministral3DecoderLayer with pre-norm residuals, MLP, and RMSNorm layers', 'review Ministral3RotaryEmbedding with dynamic RoPE initialization and position-aware scaling', 'create a Ministral3ForCausalLM model for autoregressive text generation with RoPE scaling', 'build a Ministral3Attention module with Llama-4-style attention scaling and rotary position embeddings', 'test the Ministral3ForSequenceClassification head for sequence-level prediction tasks', 'run the Ministral3ForTokenClassification head for token-level labeling tasks']
```

Usage

```
{'create_ministral3_causal_lm': 'create a Ministral3ForCausalLM model for autoregressive text generation with RoPE scaling', 'build_ministral3_attention': 'build a Ministral3Attention module with Llama-4-style attention scaling and rotary position embeddings', 'create_ministral3_model': 'create a Ministral3Model decoder using Mistral-based layers with sliding window attention', 'test_ministral3_classification': 'test the Ministral3ForSequenceClassification head for sequence-level prediction tasks', 'run_ministral3_token_classification': 'run the Ministral3ForTokenClassification head for token-level labeling tasks'}
```


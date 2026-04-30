# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/gemma2/configuration_gemma2.py

Prompts

```
['create a Gemma2Config instance with custom model hyperparameters like hidden_size and num_hidden_layers', 'build a Gemma2 model using a Gemma2Config instance to initialize model architecture', 'validate a Gemma2Config instance to ensure hidden_size is a multiple of num_attention_heads', 'initialize Gemma2Config layer_types to alternate between sliding_attention and full_attention per layer', 'access the Gemma2Config from a loaded Gemma2Model instance via model.config', 'convert Gemma2 model weights from checkpoint format to HuggingFace Transformers format', 'run the conversion script to convert Gemma2 9B weights to HuggingFace format', 'run the conversion script to convert Gemma2 27B weights to HuggingFace format', 'convert Gemma2 SentencePiece tokenizer to HuggingFace GemmaTokenizer format', 'push converted Gemma2 model and tokenizer to HuggingFace Hub', 'create a Gemma2ForCausalLM model with a Gemma2Config for autoregressive text generation', 'build a Gemma2Model forward pass with input_ids, attention_mask, and past_key_values for inference', 'test the Gemma2Attention multi-headed attention with sliding window and softcap support', 'refactor the Gemma2DecoderLayer to support gradient checkpointing and dual layernorm architecture', 'summarize the Gemma2RotaryEmbedding RoPE implementation with dynamic scaling and default rope types', 'build a Gemma2Model from a Gemma2Config to initialize the transformer encoder layers', 'run a Gemma2ForCausalLM model to generate text autoregressively from input tokens', 'review the Gemma2DecoderLayer architecture with dual layernorms and residual connections']
```

Usage

```
{'create_gemma2_config': 'create a Gemma2Config instance with custom model hyperparameters like hidden_size and num_hidden_layers', 'build_gemma2_model_from_config': 'build a Gemma2 model using a Gemma2Config instance to initialize model architecture', 'validate_gemma2_config': 'validate a Gemma2Config instance to ensure hidden_size is a multiple of num_attention_heads', 'initialize_gemma2_layer_types': 'initialize Gemma2Config layer_types to alternate between sliding_attention and full_attention per layer', 'access_gemma2_config_from_model': 'access the Gemma2Config from a loaded Gemma2Model instance via model.config'}
```

## File: huggingface_transformers/src/transformers/models/gemma2/convert_gemma2_weights_to_hf.py

Prompts

```
['create a Gemma2Config instance with custom model hyperparameters like hidden_size and num_hidden_layers', 'build a Gemma2 model using a Gemma2Config instance to initialize model architecture', 'validate a Gemma2Config instance to ensure hidden_size is a multiple of num_attention_heads', 'initialize Gemma2Config layer_types to alternate between sliding_attention and full_attention per layer', 'access the Gemma2Config from a loaded Gemma2Model instance via model.config', 'convert Gemma2 model weights from checkpoint format to HuggingFace Transformers format', 'run the conversion script to convert Gemma2 9B weights to HuggingFace format', 'run the conversion script to convert Gemma2 27B weights to HuggingFace format', 'convert Gemma2 SentencePiece tokenizer to HuggingFace GemmaTokenizer format', 'push converted Gemma2 model and tokenizer to HuggingFace Hub', 'create a Gemma2ForCausalLM model with a Gemma2Config for autoregressive text generation', 'build a Gemma2Model forward pass with input_ids, attention_mask, and past_key_values for inference', 'test the Gemma2Attention multi-headed attention with sliding window and softcap support', 'refactor the Gemma2DecoderLayer to support gradient checkpointing and dual layernorm architecture', 'summarize the Gemma2RotaryEmbedding RoPE implementation with dynamic scaling and default rope types', 'build a Gemma2Model from a Gemma2Config to initialize the transformer encoder layers', 'run a Gemma2ForCausalLM model to generate text autoregressively from input tokens', 'review the Gemma2DecoderLayer architecture with dual layernorms and residual connections']
```

Usage

```
{'convert_gemma2_weights_to_hf': 'convert Gemma2 model weights from checkpoint format to HuggingFace Transformers format', 'run_gemma2_9b_conversion': 'run the conversion script to convert Gemma2 9B weights to HuggingFace format', 'run_gemma2_27b_conversion': 'run the conversion script to convert Gemma2 27B weights to HuggingFace format', 'convert_gemma2_tokenizer': 'convert Gemma2 SentencePiece tokenizer to HuggingFace GemmaTokenizer format', 'push_gemma2_model_to_hub': 'push converted Gemma2 model and tokenizer to HuggingFace Hub'}
```

## File: huggingface_transformers/src/transformers/models/gemma2/modeling_gemma2.py

Prompts

```
['create a Gemma2Config instance with custom model hyperparameters like hidden_size and num_hidden_layers', 'build a Gemma2 model using a Gemma2Config instance to initialize model architecture', 'validate a Gemma2Config instance to ensure hidden_size is a multiple of num_attention_heads', 'initialize Gemma2Config layer_types to alternate between sliding_attention and full_attention per layer', 'access the Gemma2Config from a loaded Gemma2Model instance via model.config', 'convert Gemma2 model weights from checkpoint format to HuggingFace Transformers format', 'run the conversion script to convert Gemma2 9B weights to HuggingFace format', 'run the conversion script to convert Gemma2 27B weights to HuggingFace format', 'convert Gemma2 SentencePiece tokenizer to HuggingFace GemmaTokenizer format', 'push converted Gemma2 model and tokenizer to HuggingFace Hub', 'create a Gemma2ForCausalLM model with a Gemma2Config for autoregressive text generation', 'build a Gemma2Model forward pass with input_ids, attention_mask, and past_key_values for inference', 'test the Gemma2Attention multi-headed attention with sliding window and softcap support', 'refactor the Gemma2DecoderLayer to support gradient checkpointing and dual layernorm architecture', 'summarize the Gemma2RotaryEmbedding RoPE implementation with dynamic scaling and default rope types', 'build a Gemma2Model from a Gemma2Config to initialize the transformer encoder layers', 'run a Gemma2ForCausalLM model to generate text autoregressively from input tokens', 'review the Gemma2DecoderLayer architecture with dual layernorms and residual connections']
```

Usage

```
{'create_gemma2_causal_lm': 'create a Gemma2ForCausalLM model with a Gemma2Config for autoregressive text generation', 'build_gemma2_model_forward': 'build a Gemma2Model forward pass with input_ids, attention_mask, and past_key_values for inference', 'test_gemma2_attention': 'test the Gemma2Attention multi-headed attention with sliding window and softcap support', 'refactor_gemma2_decoder': 'refactor the Gemma2DecoderLayer to support gradient checkpointing and dual layernorm architecture', 'summarize_gemma2_rope': 'summarize the Gemma2RotaryEmbedding RoPE implementation with dynamic scaling and default rope types'}
```

## File: huggingface_transformers/src/transformers/models/gemma2/modular_gemma2.py

Prompts

```
['create a Gemma2Config instance with custom model hyperparameters like hidden_size and num_hidden_layers', 'build a Gemma2 model using a Gemma2Config instance to initialize model architecture', 'validate a Gemma2Config instance to ensure hidden_size is a multiple of num_attention_heads', 'initialize Gemma2Config layer_types to alternate between sliding_attention and full_attention per layer', 'access the Gemma2Config from a loaded Gemma2Model instance via model.config', 'convert Gemma2 model weights from checkpoint format to HuggingFace Transformers format', 'run the conversion script to convert Gemma2 9B weights to HuggingFace format', 'run the conversion script to convert Gemma2 27B weights to HuggingFace format', 'convert Gemma2 SentencePiece tokenizer to HuggingFace GemmaTokenizer format', 'push converted Gemma2 model and tokenizer to HuggingFace Hub', 'create a Gemma2ForCausalLM model with a Gemma2Config for autoregressive text generation', 'build a Gemma2Model forward pass with input_ids, attention_mask, and past_key_values for inference', 'test the Gemma2Attention multi-headed attention with sliding window and softcap support', 'refactor the Gemma2DecoderLayer to support gradient checkpointing and dual layernorm architecture', 'summarize the Gemma2RotaryEmbedding RoPE implementation with dynamic scaling and default rope types', 'build a Gemma2Model from a Gemma2Config to initialize the transformer encoder layers', 'run a Gemma2ForCausalLM model to generate text autoregressively from input tokens', 'review the Gemma2DecoderLayer architecture with dual layernorms and residual connections']
```

Usage

```
{'create_gemma2_config': 'create a Gemma2Config instance with custom model parameters like hidden_size and num_layers', 'build_gemma2_model': 'build a Gemma2Model from a Gemma2Config to initialize the transformer encoder layers', 'run_gemma2_causal_lm': 'run a Gemma2ForCausalLM model to generate text autoregressively from input tokens', 'test_gemma2_attention': 'test the Gemma2Attention forward pass with sliding window and softcapping behavior', 'review_gemma2_decoder_layer': 'review the Gemma2DecoderLayer architecture with dual layernorms and residual connections'}
```


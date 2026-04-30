# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/gpt_neox_japanese/configuration_gpt_neox_japanese.py

Prompts

```
['create a GPTNeoXJapaneseConfig instance with default Japanese model settings', 'initialize a GPTNeoXJapaneseModel with a GPTNeoXJapaneseConfig configuration object', 'convert rotary position embedding parameters to a standardized dictionary in GPTNeoXJapaneseConfig', 'configure GPTNeoXJapaneseConfig with custom vocab_size, hidden_size, and num_hidden_layers', 'access the model configuration from a GPTNeoXJapaneseModel instance via model.config', 'create a GPTNeoXJapaneseForCausalLM model for Japanese language next-token prediction with causal masking', 'run inference with GPTNeoXJapaneseModel to encode Japanese text and produce last hidden states', 'build GPTNeoXJapaneseAttention with fused QKV projection, rotary embeddings, and causal self-attention', 'test GPTNeoXJapaneseRotaryEmbedding forward pass to compute rotary position cos and sin factors', 'review GPTNeoXJapaneseLayer with input layernorm, attention, bias dropout add, MLP, and post-attention layernorm', 'create a GPTNeoXJapaneseTokenizer instance with vocab and emoji files for Japanese text tokenization', 'build Japanese text tokenization using GPTNeoXJapaneseTokenizer to encode text into subword token IDs', 'test SubWordJapaneseTokenizer.convert_id_to_token to decode token IDs back into Japanese text', 'summarize load_vocab_and_emoji function that loads vocabulary and emoji mappings from files', 'review GPTNeoXJapaneseTokenizer.save_vocabulary to save vocab and emoji files to a directory']
```

Usage

```
{'create_GPTNeoXJapaneseConfig': 'create a GPTNeoXJapaneseConfig instance with default Japanese model settings', 'init_model_GPTNeoXJapaneseConfig': 'initialize a GPTNeoXJapaneseModel with a GPTNeoXJapaneseConfig configuration object', 'convert_rope_params_GPTNeoXJapaneseConfig': 'convert rotary position embedding parameters to a standardized dictionary in GPTNeoXJapaneseConfig', 'configure_GPTNeoXJapaneseConfig': 'configure GPTNeoXJapaneseConfig with custom vocab_size, hidden_size, and num_hidden_layers', 'access_model_config': 'access the model configuration from a GPTNeoXJapaneseModel instance via model.config'}
```

## File: huggingface_transformers/src/transformers/models/gpt_neox_japanese/modeling_gpt_neox_japanese.py

Prompts

```
['create a GPTNeoXJapaneseConfig instance with default Japanese model settings', 'initialize a GPTNeoXJapaneseModel with a GPTNeoXJapaneseConfig configuration object', 'convert rotary position embedding parameters to a standardized dictionary in GPTNeoXJapaneseConfig', 'configure GPTNeoXJapaneseConfig with custom vocab_size, hidden_size, and num_hidden_layers', 'access the model configuration from a GPTNeoXJapaneseModel instance via model.config', 'create a GPTNeoXJapaneseForCausalLM model for Japanese language next-token prediction with causal masking', 'run inference with GPTNeoXJapaneseModel to encode Japanese text and produce last hidden states', 'build GPTNeoXJapaneseAttention with fused QKV projection, rotary embeddings, and causal self-attention', 'test GPTNeoXJapaneseRotaryEmbedding forward pass to compute rotary position cos and sin factors', 'review GPTNeoXJapaneseLayer with input layernorm, attention, bias dropout add, MLP, and post-attention layernorm', 'create a GPTNeoXJapaneseTokenizer instance with vocab and emoji files for Japanese text tokenization', 'build Japanese text tokenization using GPTNeoXJapaneseTokenizer to encode text into subword token IDs', 'test SubWordJapaneseTokenizer.convert_id_to_token to decode token IDs back into Japanese text', 'summarize load_vocab_and_emoji function that loads vocabulary and emoji mappings from files', 'review GPTNeoXJapaneseTokenizer.save_vocabulary to save vocab and emoji files to a directory']
```

Usage

```
{'create_gpt_neox_japanese_causal_lm': 'create a GPTNeoXJapaneseForCausalLM model for Japanese language next-token prediction with causal masking', 'run_gpt_neox_japanese_inference': 'run inference with GPTNeoXJapaneseModel to encode Japanese text and produce last hidden states', 'build_gpt_neox_japanese_attention': 'build GPTNeoXJapaneseAttention with fused QKV projection, rotary embeddings, and causal self-attention', 'test_gpt_neox_japanese_rotary_embedding': 'test GPTNeoXJapaneseRotaryEmbedding forward pass to compute rotary position cos and sin factors', 'review_gpt_neox_japanese_layer': 'review GPTNeoXJapaneseLayer with input layernorm, attention, bias dropout add, MLP, and post-attention layernorm'}
```

## File: huggingface_transformers/src/transformers/models/gpt_neox_japanese/tokenization_gpt_neox_japanese.py

Prompts

```
['create a GPTNeoXJapaneseConfig instance with default Japanese model settings', 'initialize a GPTNeoXJapaneseModel with a GPTNeoXJapaneseConfig configuration object', 'convert rotary position embedding parameters to a standardized dictionary in GPTNeoXJapaneseConfig', 'configure GPTNeoXJapaneseConfig with custom vocab_size, hidden_size, and num_hidden_layers', 'access the model configuration from a GPTNeoXJapaneseModel instance via model.config', 'create a GPTNeoXJapaneseForCausalLM model for Japanese language next-token prediction with causal masking', 'run inference with GPTNeoXJapaneseModel to encode Japanese text and produce last hidden states', 'build GPTNeoXJapaneseAttention with fused QKV projection, rotary embeddings, and causal self-attention', 'test GPTNeoXJapaneseRotaryEmbedding forward pass to compute rotary position cos and sin factors', 'review GPTNeoXJapaneseLayer with input layernorm, attention, bias dropout add, MLP, and post-attention layernorm', 'create a GPTNeoXJapaneseTokenizer instance with vocab and emoji files for Japanese text tokenization', 'build Japanese text tokenization using GPTNeoXJapaneseTokenizer to encode text into subword token IDs', 'test SubWordJapaneseTokenizer.convert_id_to_token to decode token IDs back into Japanese text', 'summarize load_vocab_and_emoji function that loads vocabulary and emoji mappings from files', 'review GPTNeoXJapaneseTokenizer.save_vocabulary to save vocab and emoji files to a directory']
```

Usage

```
{'create_GPTNeoXJapaneseTokenizer': 'create a GPTNeoXJapaneseTokenizer instance with vocab and emoji files for Japanese text tokenization', 'build_tokenizer_tokenize': 'build Japanese text tokenization using GPTNeoXJapaneseTokenizer to encode text into subword token IDs', 'test_convert_id_to_token': 'test SubWordJapaneseTokenizer.convert_id_to_token to decode token IDs back into Japanese text', 'summarize_load_vocab_and_emoji': 'summarize load_vocab_and_emoji function that loads vocabulary and emoji mappings from files', 'review_GPTNeoXJapaneseTokenizer_save_vocabulary': 'review GPTNeoXJapaneseTokenizer.save_vocabulary to save vocab and emoji files to a directory'}
```


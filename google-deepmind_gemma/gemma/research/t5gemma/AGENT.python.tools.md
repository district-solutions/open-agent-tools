# Agent Python Tools

- repo: google-deepmind/gemma
- repo_uri: https://github.com/google-deepmind/gemma

## File: google-deepmind_gemma/gemma/research/t5gemma/config.py

Prompts

```
['build a decoder-only Gemma2 transformer config using GemmaPreset.GEMMA2_2B.config()', 'build a T5Gemma encoder-decoder config using T5GemmaPreset.GEMMA2_2B_2B.config property', 'create a custom Gemma transformer config via GemmaPreset.make_config with layer and dimension args', 'download a T5Gemma checkpoint from Kaggle using T5GemmaPreset.get_checkpoint_from_kaggle with ckpt and pretrain type', 'get the Gemma2 tokenizer via T5GemmaPreset.tokenizer property for text tokenization', 'build a Gemma transformer model with cross-attention support using TransformerConfig and the Transformer module', 'create an Attention module with configurable heads, RoPE embeddings, and optional sliding window or cross-attention', 'create a Block transformer layer with self-attention, optional cross-attention, and feed-forward sublayers', 'run get_sliding_mask to compute a sliding attention mask with optional bidirectional windowing', 'initialize a KV cache for attention layers using Attention.init_cache with batch size and sequence length', 'create a Sampler instance and call sample to generate text from a prompt using a T5Gemma model', 'build a TopkSampling method with custom temperature and k values to sample next tokens from logits', 'run Sampler sample with return_state true to get SamplerOutput containing predicted tokens and logits', 'create a function that masks token IDs after EOS tokens with padding IDs in a batch of tokens', 'build a function that merges a new KV cache into an existing cache updating k and v arrays', 'build a T5Gemma encoder-decoder transformer using T5GemmaConfig with encoder and decoder configs', 'run the T5Gemma encoder to compute activations from input tokens with bidirectional attention', 'run the T5Gemma decoder to compute activations using causal and cross attention masks', 'create a causal attention mask from a 2D input mask using jnp tril', 'create a cross attention mask from encoder and decoder input masks']
```

Usage

```
{'build_gemma_decoder_config': 'build a decoder-only Gemma2 transformer config using GemmaPreset.GEMMA2_2B.config()', 'build_t5gemma_encoder_decoder_config': 'build a T5Gemma encoder-decoder config using T5GemmaPreset.GEMMA2_2B_2B.config property', 'create_custom_gemma_config': 'create a custom Gemma transformer config via GemmaPreset.make_config with layer and dimension args', 'download_t5gemma_checkpoint': 'download a T5Gemma checkpoint from Kaggle using T5GemmaPreset.get_checkpoint_from_kaggle with ckpt and pretrain type', 'get_gemma_tokenizer': 'get the Gemma2 tokenizer via T5GemmaPreset.tokenizer property for text tokenization'}
```

## File: google-deepmind_gemma/gemma/research/t5gemma/modules.py

Prompts

```
['build a decoder-only Gemma2 transformer config using GemmaPreset.GEMMA2_2B.config()', 'build a T5Gemma encoder-decoder config using T5GemmaPreset.GEMMA2_2B_2B.config property', 'create a custom Gemma transformer config via GemmaPreset.make_config with layer and dimension args', 'download a T5Gemma checkpoint from Kaggle using T5GemmaPreset.get_checkpoint_from_kaggle with ckpt and pretrain type', 'get the Gemma2 tokenizer via T5GemmaPreset.tokenizer property for text tokenization', 'build a Gemma transformer model with cross-attention support using TransformerConfig and the Transformer module', 'create an Attention module with configurable heads, RoPE embeddings, and optional sliding window or cross-attention', 'create a Block transformer layer with self-attention, optional cross-attention, and feed-forward sublayers', 'run get_sliding_mask to compute a sliding attention mask with optional bidirectional windowing', 'initialize a KV cache for attention layers using Attention.init_cache with batch size and sequence length', 'create a Sampler instance and call sample to generate text from a prompt using a T5Gemma model', 'build a TopkSampling method with custom temperature and k values to sample next tokens from logits', 'run Sampler sample with return_state true to get SamplerOutput containing predicted tokens and logits', 'create a function that masks token IDs after EOS tokens with padding IDs in a batch of tokens', 'build a function that merges a new KV cache into an existing cache updating k and v arrays', 'build a T5Gemma encoder-decoder transformer using T5GemmaConfig with encoder and decoder configs', 'run the T5Gemma encoder to compute activations from input tokens with bidirectional attention', 'run the T5Gemma decoder to compute activations using causal and cross attention masks', 'create a causal attention mask from a 2D input mask using jnp tril', 'create a cross attention mask from encoder and decoder input masks']
```

Usage

```
{'build_transformer_with_cross_attention': 'build a Gemma transformer model with cross-attention support using TransformerConfig and the Transformer module', 'create_attention_module': 'create an Attention module with configurable heads, RoPE embeddings, and optional sliding window or cross-attention', 'create_transformer_block': 'create a Block transformer layer with self-attention, optional cross-attention, and feed-forward sublayers', 'run_sliding_window_mask': 'run get_sliding_mask to compute a sliding attention mask with optional bidirectional windowing', 'init_attention_cache': 'initialize a KV cache for attention layers using Attention.init_cache with batch size and sequence length'}
```

## File: google-deepmind_gemma/gemma/research/t5gemma/sampling.py

Prompts

```
['build a decoder-only Gemma2 transformer config using GemmaPreset.GEMMA2_2B.config()', 'build a T5Gemma encoder-decoder config using T5GemmaPreset.GEMMA2_2B_2B.config property', 'create a custom Gemma transformer config via GemmaPreset.make_config with layer and dimension args', 'download a T5Gemma checkpoint from Kaggle using T5GemmaPreset.get_checkpoint_from_kaggle with ckpt and pretrain type', 'get the Gemma2 tokenizer via T5GemmaPreset.tokenizer property for text tokenization', 'build a Gemma transformer model with cross-attention support using TransformerConfig and the Transformer module', 'create an Attention module with configurable heads, RoPE embeddings, and optional sliding window or cross-attention', 'create a Block transformer layer with self-attention, optional cross-attention, and feed-forward sublayers', 'run get_sliding_mask to compute a sliding attention mask with optional bidirectional windowing', 'initialize a KV cache for attention layers using Attention.init_cache with batch size and sequence length', 'create a Sampler instance and call sample to generate text from a prompt using a T5Gemma model', 'build a TopkSampling method with custom temperature and k values to sample next tokens from logits', 'run Sampler sample with return_state true to get SamplerOutput containing predicted tokens and logits', 'create a function that masks token IDs after EOS tokens with padding IDs in a batch of tokens', 'build a function that merges a new KV cache into an existing cache updating k and v arrays', 'build a T5Gemma encoder-decoder transformer using T5GemmaConfig with encoder and decoder configs', 'run the T5Gemma encoder to compute activations from input tokens with bidirectional attention', 'run the T5Gemma decoder to compute activations using causal and cross attention masks', 'create a causal attention mask from a 2D input mask using jnp tril', 'create a cross attention mask from encoder and decoder input masks']
```

Usage

```
{'sample_text_with_sampler': 'create a Sampler instance and call sample to generate text from a prompt using a T5Gemma model', 'sample_with_topk_sampling': 'build a TopkSampling method with custom temperature and k values to sample next tokens from logits', 'sample_with_return_state': 'run Sampler sample with return_state true to get SamplerOutput containing predicted tokens and logits', 'mask_tokens_after_end_tokens': 'create a function that masks token IDs after EOS tokens with padding IDs in a batch of tokens', 'merge_initial_cache': 'build a function that merges a new KV cache into an existing cache updating k and v arrays'}
```

## File: google-deepmind_gemma/gemma/research/t5gemma/t5gemma.py

Prompts

```
['build a decoder-only Gemma2 transformer config using GemmaPreset.GEMMA2_2B.config()', 'build a T5Gemma encoder-decoder config using T5GemmaPreset.GEMMA2_2B_2B.config property', 'create a custom Gemma transformer config via GemmaPreset.make_config with layer and dimension args', 'download a T5Gemma checkpoint from Kaggle using T5GemmaPreset.get_checkpoint_from_kaggle with ckpt and pretrain type', 'get the Gemma2 tokenizer via T5GemmaPreset.tokenizer property for text tokenization', 'build a Gemma transformer model with cross-attention support using TransformerConfig and the Transformer module', 'create an Attention module with configurable heads, RoPE embeddings, and optional sliding window or cross-attention', 'create a Block transformer layer with self-attention, optional cross-attention, and feed-forward sublayers', 'run get_sliding_mask to compute a sliding attention mask with optional bidirectional windowing', 'initialize a KV cache for attention layers using Attention.init_cache with batch size and sequence length', 'create a Sampler instance and call sample to generate text from a prompt using a T5Gemma model', 'build a TopkSampling method with custom temperature and k values to sample next tokens from logits', 'run Sampler sample with return_state true to get SamplerOutput containing predicted tokens and logits', 'create a function that masks token IDs after EOS tokens with padding IDs in a batch of tokens', 'build a function that merges a new KV cache into an existing cache updating k and v arrays', 'build a T5Gemma encoder-decoder transformer using T5GemmaConfig with encoder and decoder configs', 'run the T5Gemma encoder to compute activations from input tokens with bidirectional attention', 'run the T5Gemma decoder to compute activations using causal and cross attention masks', 'create a causal attention mask from a 2D input mask using jnp tril', 'create a cross attention mask from encoder and decoder input masks']
```

Usage

```
{'build_T5Gemma_transformer': 'build a T5Gemma encoder-decoder transformer using T5GemmaConfig with encoder and decoder configs', 'run_compute_encoder_activations': 'run the T5Gemma encoder to compute activations from input tokens with bidirectional attention', 'run_compute_decoder_activations': 'run the T5Gemma decoder to compute activations using causal and cross attention masks', 'create_causal_attn_mask': 'create a causal attention mask from a 2D input mask using jnp tril', 'create_cross_attn_mask': 'create a cross attention mask from encoder and decoder input masks'}
```


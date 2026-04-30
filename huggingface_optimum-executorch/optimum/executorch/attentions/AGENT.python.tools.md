# Agent Python Tools

- repo: huggingface/optimum-executorch
- repo_uri: https://github.com/huggingface/optimum-executorch

## File: huggingface_optimum-executorch/optimum/executorch/attentions/custom_kv_cache.py

Prompts

```
['create an ETCustomStaticCache instance with a model config, batch size, and device for ExecutorTorch inference', 'update the ETCustomStaticCache with new key and value states for a given layer index', 'create an ETCustomHybridCache instance with sliding window and global layer support for ExecutorTorch', 'update the ETCustomHybridCache with new key and value states using CustomKVCache or CustomRingKVCache', 'replace all KV caches in a torch module with ETCustomStaticCache or ETCustomHybridCache in place', 'run custom SDPA attention forward pass with start position for ExecuTorch LLM inference', 'run the SDPA mask passthrough function to skip attention mask creation for ExecuTorch export', 'run the ring KV cache custom SDPA factory to get a forward function for sliding window attention', 'review the custom SDPA forward function that handles causal and sliding window attention modes', 'review the ring KV cache SDPA factory that creates causal masks for ring buffer attention', 'create a WhisperCrossAttention module with embed_dim, num_heads, dropout, and layer_idx parameters', 'run cross attention forward pass with hidden_states, key_value_states, and EncoderDecoderCache', 'review the WhisperCrossAttention forward method that uses torch.cond for traceable cache branching', 'refactor the WhisperCrossAttention to use cached key-value states via executorch update_cross_attn_cache', 'summarize the WhisperCrossAttention class that implements export-friendly multi-headed cross attention for Whisper']
```

Usage

```
{'create_ETCustomStaticCache': 'create an ETCustomStaticCache instance with a model config, batch size, and device for ExecutorTorch inference', 'update_ETCustomStaticCache': 'update the ETCustomStaticCache with new key and value states for a given layer index', 'create_ETCustomHybridCache': 'create an ETCustomHybridCache instance with sliding window and global layer support for ExecutorTorch', 'update_ETCustomHybridCache': 'update the ETCustomHybridCache with new key and value states using CustomKVCache or CustomRingKVCache', 'replace_with_et_custom_kv_cache': 'replace all KV caches in a torch module with ETCustomStaticCache or ETCustomHybridCache in place'}
```

## File: huggingface_optimum-executorch/optimum/executorch/attentions/custom_sdpa.py

Prompts

```
['create an ETCustomStaticCache instance with a model config, batch size, and device for ExecutorTorch inference', 'update the ETCustomStaticCache with new key and value states for a given layer index', 'create an ETCustomHybridCache instance with sliding window and global layer support for ExecutorTorch', 'update the ETCustomHybridCache with new key and value states using CustomKVCache or CustomRingKVCache', 'replace all KV caches in a torch module with ETCustomStaticCache or ETCustomHybridCache in place', 'run custom SDPA attention forward pass with start position for ExecuTorch LLM inference', 'run the SDPA mask passthrough function to skip attention mask creation for ExecuTorch export', 'run the ring KV cache custom SDPA factory to get a forward function for sliding window attention', 'review the custom SDPA forward function that handles causal and sliding window attention modes', 'review the ring KV cache SDPA factory that creates causal masks for ring buffer attention', 'create a WhisperCrossAttention module with embed_dim, num_heads, dropout, and layer_idx parameters', 'run cross attention forward pass with hidden_states, key_value_states, and EncoderDecoderCache', 'review the WhisperCrossAttention forward method that uses torch.cond for traceable cache branching', 'refactor the WhisperCrossAttention to use cached key-value states via executorch update_cross_attn_cache', 'summarize the WhisperCrossAttention class that implements export-friendly multi-headed cross attention for Whisper']
```

Usage

```
{'run_custom_sdpa_with_start_pos': 'run custom SDPA attention forward pass with start position for ExecuTorch LLM inference', 'run_sdpa_mask_passthrough': 'run the SDPA mask passthrough function to skip attention mask creation for ExecuTorch export', 'run_get_custom_sdpa_for_ring_kv_cache': 'run the ring KV cache custom SDPA factory to get a forward function for sliding window attention', 'review_custom_sdpa_with_start_pos_forward': 'review the custom SDPA forward function that handles causal and sliding window attention modes', 'review_get_custom_sdpa_for_ring_kv_cache': 'review the ring KV cache SDPA factory that creates causal masks for ring buffer attention'}
```

## File: huggingface_optimum-executorch/optimum/executorch/attentions/whisper_attention.py

Prompts

```
['create an ETCustomStaticCache instance with a model config, batch size, and device for ExecutorTorch inference', 'update the ETCustomStaticCache with new key and value states for a given layer index', 'create an ETCustomHybridCache instance with sliding window and global layer support for ExecutorTorch', 'update the ETCustomHybridCache with new key and value states using CustomKVCache or CustomRingKVCache', 'replace all KV caches in a torch module with ETCustomStaticCache or ETCustomHybridCache in place', 'run custom SDPA attention forward pass with start position for ExecuTorch LLM inference', 'run the SDPA mask passthrough function to skip attention mask creation for ExecuTorch export', 'run the ring KV cache custom SDPA factory to get a forward function for sliding window attention', 'review the custom SDPA forward function that handles causal and sliding window attention modes', 'review the ring KV cache SDPA factory that creates causal masks for ring buffer attention', 'create a WhisperCrossAttention module with embed_dim, num_heads, dropout, and layer_idx parameters', 'run cross attention forward pass with hidden_states, key_value_states, and EncoderDecoderCache', 'review the WhisperCrossAttention forward method that uses torch.cond for traceable cache branching', 'refactor the WhisperCrossAttention to use cached key-value states via executorch update_cross_attn_cache', 'summarize the WhisperCrossAttention class that implements export-friendly multi-headed cross attention for Whisper']
```

Usage

```
{'init_WhisperCrossAttention': 'create a WhisperCrossAttention module with embed_dim, num_heads, dropout, and layer_idx parameters', 'forward_WhisperCrossAttention': 'run cross attention forward pass with hidden_states, key_value_states, and EncoderDecoderCache', 'review_WhisperCrossAttention_torch_cond': 'review the WhisperCrossAttention forward method that uses torch.cond for traceable cache branching', 'refactor_WhisperCrossAttention_cache': 'refactor the WhisperCrossAttention to use cached key-value states via executorch update_cross_attn_cache', 'summarize_WhisperCrossAttention': 'summarize the WhisperCrossAttention class that implements export-friendly multi-headed cross attention for Whisper'}
```


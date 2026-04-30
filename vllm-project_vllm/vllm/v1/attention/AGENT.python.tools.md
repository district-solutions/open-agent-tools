# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/attention/backend.py

Prompts

```
['build an attention backend class that validates head size, dtype, block size, and compute capability support', 'create CommonAttentionMetadata with query start locations, sequence lengths, block tables, and slot mappings for a batch', 'test an attention backend for supported head sizes, dtypes, kv cache dtypes, block sizes, and attention types', 'build an AttentionMetadataBuilder that constructs per-layer attention metadata with CUDA graph and batch reorder support', 'subclass an AttentionBackend dynamically with a custom builder class or attribute overrides', 'build an attention backend selector using get_attn_backend with head_size, dtype, kv_cache_dtype, and optional MLA flags', 'create an AttentionSelectorConfig NamedTuple with head_size, dtype, kv_cache_dtype, block_size, and attention feature flags', 'test get_mamba_attn_backend by passing a valid mamba_type string from MAMBA_TYPE_TO_BACKEND_MAP', 'refactor _cached_get_attn_backend to lazily import current_platform and set the required KV cache layout', 'review get_attn_backend to validate kv_cache_dtype against CacheDType and resolve the correct AttentionBackend class']
```

Usage

```
{'build_attention_backend': 'build an attention backend class that validates head size, dtype, block size, and compute capability support', 'create_attention_metadata': 'create CommonAttentionMetadata with query start locations, sequence lengths, block tables, and slot mappings for a batch', 'test_attention_backend_supports': 'test an attention backend for supported head sizes, dtypes, kv cache dtypes, block sizes, and attention types', 'build_attention_metadata_builder': 'build an AttentionMetadataBuilder that constructs per-layer attention metadata with CUDA graph and batch reorder support', 'subclass_attention_backend': 'subclass an AttentionBackend dynamically with a custom builder class or attribute overrides'}
```

## File: vllm-project_vllm/vllm/v1/attention/selector.py

Prompts

```
['build an attention backend class that validates head size, dtype, block size, and compute capability support', 'create CommonAttentionMetadata with query start locations, sequence lengths, block tables, and slot mappings for a batch', 'test an attention backend for supported head sizes, dtypes, kv cache dtypes, block sizes, and attention types', 'build an AttentionMetadataBuilder that constructs per-layer attention metadata with CUDA graph and batch reorder support', 'subclass an AttentionBackend dynamically with a custom builder class or attribute overrides', 'build an attention backend selector using get_attn_backend with head_size, dtype, kv_cache_dtype, and optional MLA flags', 'create an AttentionSelectorConfig NamedTuple with head_size, dtype, kv_cache_dtype, block_size, and attention feature flags', 'test get_mamba_attn_backend by passing a valid mamba_type string from MAMBA_TYPE_TO_BACKEND_MAP', 'refactor _cached_get_attn_backend to lazily import current_platform and set the required KV cache layout', 'review get_attn_backend to validate kv_cache_dtype against CacheDType and resolve the correct AttentionBackend class']
```

Usage

```
{'build_get_attn_backend': 'build an attention backend selector using get_attn_backend with head_size, dtype, kv_cache_dtype, and optional MLA flags', 'create_AttentionSelectorConfig': 'create an AttentionSelectorConfig NamedTuple with head_size, dtype, kv_cache_dtype, block_size, and attention feature flags', 'test_get_mamba_attn_backend': 'test get_mamba_attn_backend by passing a valid mamba_type string from MAMBA_TYPE_TO_BACKEND_MAP', 'refactor__cached_get_attn_backend': 'refactor _cached_get_attn_backend to lazily import current_platform and set the required KV cache layout', 'review_get_attn_backend': 'review get_attn_backend to validate kv_cache_dtype against CacheDType and resolve the correct AttentionBackend class'}
```


# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/transformers/models/modeling_all_models.py

Prompts

```
['create a KVCache module to allocate and update key-value cache tensors for HPU inference', 'update the KVCache with new key-value tensors using index-based or concatenation strategies', 'apply the HPU fused rotary positional embedding to query and key tensors for transformers', 'invert and extend an encoder attention mask tensor for HPU-compatible mixed precision computation', 'create a ScopedLinearAllReduce module to split DeepSpeed LinearAllReduce into forward, all_reduce, and post steps']
```

Usage

```
{'create_kv_cache': 'create a KVCache module to allocate and update key-value cache tensors for HPU inference', 'update_kv_cache': 'update the KVCache with new key-value tensors using index-based or concatenation strategies', 'apply_fused_rope': 'apply the HPU fused rotary positional embedding to query and key tensors for transformers', 'invert_attention_mask': 'invert and extend an encoder attention mask tensor for HPU-compatible mixed precision computation', 'scoped_linear_all_reduce': 'create a ScopedLinearAllReduce module to split DeepSpeed LinearAllReduce into forward, all_reduce, and post steps'}
```


# Agent Python Tools

- repo: tanishqkumar/ssd
- repo_uri: https://github.com/tanishqkumar/ssd

## File: tanishqkumar_ssd/ssd/utils/async_helpers/async_spec_helpers.py

Prompts

```
['compute the megaspec lookahead length given MQ_LEN and speculative K', 'build flat glue decode input ids tensor from draft tokens and recovery tokens', 'get forked recovery token indices from logits using cache hit status and fan-out config', 'apply sampler_x rescaling to top-F probabilities and renormalize the distribution', 'test the async_spec_helpers module for speculative decoding utility functions', 'build a function that concatenates multiple torch tensors into a single flat int64 payload', 'test sending multiple int64 tensors as one fused payload via NCCL distributed send', 'test receiving a fused int64 payload of known length via NCCL distributed recv', 'refactor the concat_int64 function to handle mixed dtype tensors with None values', 'review the send_int64 function and its usage with torch.distributed groups', 'test KV cache block consistency across fork groups using branch block table and kv cache tensors', 'review glue decode logits against out logits with cache hit filtering and tolerance-based mismatch detection', 'test that logits are identical across all F branches for each (b, k) pair and distinct across different (b, k) pairs', 'build a conditioning tensor from kv cache and block table given a context length with full and partial block handling', 'test forked recovery token extraction from logits for speculative decoding with async fan out branches']
```

Usage

```
{'compute_megaspec_lookahead': 'compute the megaspec lookahead length given MQ_LEN and speculative K', 'build_glue_decode_input_ids': 'build flat glue decode input ids tensor from draft tokens and recovery tokens', 'get_forked_recovery_tokens_from_logits': 'get forked recovery token indices from logits using cache hit status and fan-out config', 'apply_sampler_x_rescaling': 'apply sampler_x rescaling to top-F probabilities and renormalize the distribution', 'test_async_spec_helpers': 'test the async_spec_helpers module for speculative decoding utility functions'}
```

## File: tanishqkumar_ssd/ssd/utils/async_helpers/nccl_pack.py

Prompts

```
['compute the megaspec lookahead length given MQ_LEN and speculative K', 'build flat glue decode input ids tensor from draft tokens and recovery tokens', 'get forked recovery token indices from logits using cache hit status and fan-out config', 'apply sampler_x rescaling to top-F probabilities and renormalize the distribution', 'test the async_spec_helpers module for speculative decoding utility functions', 'build a function that concatenates multiple torch tensors into a single flat int64 payload', 'test sending multiple int64 tensors as one fused payload via NCCL distributed send', 'test receiving a fused int64 payload of known length via NCCL distributed recv', 'refactor the concat_int64 function to handle mixed dtype tensors with None values', 'review the send_int64 function and its usage with torch.distributed groups', 'test KV cache block consistency across fork groups using branch block table and kv cache tensors', 'review glue decode logits against out logits with cache hit filtering and tolerance-based mismatch detection', 'test that logits are identical across all F branches for each (b, k) pair and distinct across different (b, k) pairs', 'build a conditioning tensor from kv cache and block table given a context length with full and partial block handling', 'test forked recovery token extraction from logits for speculative decoding with async fan out branches']
```

Usage

```
{'build_concat_int64': 'build a function that concatenates multiple torch tensors into a single flat int64 payload', 'test_send_int64': 'test sending multiple int64 tensors as one fused payload via NCCL distributed send', 'test_recv_int64': 'test receiving a fused int64 payload of known length via NCCL distributed recv', 'refactor_concat_int64': 'refactor the concat_int64 function to handle mixed dtype tensors with None values', 'review_send_int64': 'review the send_int64 function and its usage with torch.distributed groups'}
```

## File: tanishqkumar_ssd/ssd/utils/async_helpers/tests.py

Prompts

```
['compute the megaspec lookahead length given MQ_LEN and speculative K', 'build flat glue decode input ids tensor from draft tokens and recovery tokens', 'get forked recovery token indices from logits using cache hit status and fan-out config', 'apply sampler_x rescaling to top-F probabilities and renormalize the distribution', 'test the async_spec_helpers module for speculative decoding utility functions', 'build a function that concatenates multiple torch tensors into a single flat int64 payload', 'test sending multiple int64 tensors as one fused payload via NCCL distributed send', 'test receiving a fused int64 payload of known length via NCCL distributed recv', 'refactor the concat_int64 function to handle mixed dtype tensors with None values', 'review the send_int64 function and its usage with torch.distributed groups', 'test KV cache block consistency across fork groups using branch block table and kv cache tensors', 'review glue decode logits against out logits with cache hit filtering and tolerance-based mismatch detection', 'test that logits are identical across all F branches for each (b, k) pair and distinct across different (b, k) pairs', 'build a conditioning tensor from kv cache and block table given a context length with full and partial block handling', 'test forked recovery token extraction from logits for speculative decoding with async fan out branches']
```

Usage

```
{'test_prepare_last_consistency_test': 'test KV cache block consistency across fork groups using branch block table and kv cache tensors', 'review_logits_out_glue_decode_sanity_test': 'review glue decode logits against out logits with cache hit filtering and tolerance-based mismatch detection', 'test_logits_alignment_sanity_test': 'test that logits are identical across all F branches for each (b, k) pair and distinct across different (b, k) pairs', 'build_get_conditioning_tensor_test': 'build a conditioning tensor from kv cache and block table given a context length with full and partial block handling', 'test_get_forked_recovery_tokens_from_logits': 'test forked recovery token extraction from logits for speculative decoding with async fan out branches'}
```


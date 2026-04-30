# Agent Python Tools

- repo: tanishqkumar/ssd
- repo_uri: https://github.com/tanishqkumar/ssd

## File: tanishqkumar_ssd/ssd/engine/helpers/cudagraph_helpers.py

Prompts

```
['run the CUDA graph for speculative verify step with input ids, positions, and graph vars', 'run the CUDA graph for decode step with optional hidden states for EAGLE draft models', 'run the FI tree decode CUDA graph with precomputed KV metadata and packed attention masks', 'capture CUDA graphs for decode with power-of-two bucket sizing for large batch sizes', 'capture CUDA graphs for FI tree decode with fake plan setup and logits computation', 'build a causal attention mask for SSD decoding using get_custom_mask with context lengths, step, K, and cache hits', 'create an iteration-specific attention mask tensor given prefix length, K, and F parameters', 'run flat_blocks_after_cat to concatenate variable-length prefix blocks with a constant block into a flat boolean tensor', 'create a vectorized causal mask for batch sizes greater than 8 using hit/miss glue mask fixup', 'create a cached causal mask using precomputed glue, diagonal, and ones components for batch sizes up to 8', 'build a prefill payload with input ids, eagle activations, device, max blocks, and draft block tables', 'create decode tensors from sequences with block size, draft flag, verify mode, and k parameter', 'build padded block tables tensor from sequences with optional draft flag', 'create prefill tensors from sequences with block size, draft flag, and skip first token option', 'test decode tensor preparation for normal decoding and verify paths with k parameter', 'create a SpeculateResult dataclass with speculation tokens, logits, and optional cache hits', 'create a VerifyResult dataclass with new suffixes, recovery tokens, and optional eagle actions', 'implement the SpeculatorBase prefill method to generate speculative tokens from sequences', 'implement the SpeculatorBase speculate method to produce speculation results given sequences', 'implement the VerifierBase verify method to validate speculative tokens against the target model']
```

Usage

```
{'run_verify_cudagraph': 'run the CUDA graph for speculative verify step with input ids, positions, and graph vars', 'run_decode_cudagraph': 'run the CUDA graph for decode step with optional hidden states for EAGLE draft models', 'run_fi_tree_decode_cudagraph': 'run the FI tree decode CUDA graph with precomputed KV metadata and packed attention masks', 'capture_cudagraph': 'capture CUDA graphs for decode with power-of-two bucket sizing for large batch sizes', 'capture_fi_tree_decode_cudagraph': 'capture CUDA graphs for FI tree decode with fake plan setup and logits computation'}
```

## File: tanishqkumar_ssd/ssd/engine/helpers/mask_helpers.py

Prompts

```
['run the CUDA graph for speculative verify step with input ids, positions, and graph vars', 'run the CUDA graph for decode step with optional hidden states for EAGLE draft models', 'run the FI tree decode CUDA graph with precomputed KV metadata and packed attention masks', 'capture CUDA graphs for decode with power-of-two bucket sizing for large batch sizes', 'capture CUDA graphs for FI tree decode with fake plan setup and logits computation', 'build a causal attention mask for SSD decoding using get_custom_mask with context lengths, step, K, and cache hits', 'create an iteration-specific attention mask tensor given prefix length, K, and F parameters', 'run flat_blocks_after_cat to concatenate variable-length prefix blocks with a constant block into a flat boolean tensor', 'create a vectorized causal mask for batch sizes greater than 8 using hit/miss glue mask fixup', 'create a cached causal mask using precomputed glue, diagonal, and ones components for batch sizes up to 8', 'build a prefill payload with input ids, eagle activations, device, max blocks, and draft block tables', 'create decode tensors from sequences with block size, draft flag, verify mode, and k parameter', 'build padded block tables tensor from sequences with optional draft flag', 'create prefill tensors from sequences with block size, draft flag, and skip first token option', 'test decode tensor preparation for normal decoding and verify paths with k parameter', 'create a SpeculateResult dataclass with speculation tokens, logits, and optional cache hits', 'create a VerifyResult dataclass with new suffixes, recovery tokens, and optional eagle actions', 'implement the SpeculatorBase prefill method to generate speculative tokens from sequences', 'implement the SpeculatorBase speculate method to produce speculation results given sequences', 'implement the VerifierBase verify method to validate speculative tokens against the target model']
```

Usage

```
{'build_get_custom_mask': 'build a causal attention mask for SSD decoding using get_custom_mask with context lengths, step, K, and cache hits', 'create_get_mask_iter_i': 'create an iteration-specific attention mask tensor given prefix length, K, and F parameters', 'run_flat_blocks_after_cat': 'run flat_blocks_after_cat to concatenate variable-length prefix blocks with a constant block into a flat boolean tensor', 'create_get_custom_mask_vectorized': 'create a vectorized causal mask for batch sizes greater than 8 using hit/miss glue mask fixup', 'create_get_custom_mask_cached': 'create a cached causal mask using precomputed glue, diagonal, and ones components for batch sizes up to 8'}
```

## File: tanishqkumar_ssd/ssd/engine/helpers/runner_helpers.py

Prompts

```
['run the CUDA graph for speculative verify step with input ids, positions, and graph vars', 'run the CUDA graph for decode step with optional hidden states for EAGLE draft models', 'run the FI tree decode CUDA graph with precomputed KV metadata and packed attention masks', 'capture CUDA graphs for decode with power-of-two bucket sizing for large batch sizes', 'capture CUDA graphs for FI tree decode with fake plan setup and logits computation', 'build a causal attention mask for SSD decoding using get_custom_mask with context lengths, step, K, and cache hits', 'create an iteration-specific attention mask tensor given prefix length, K, and F parameters', 'run flat_blocks_after_cat to concatenate variable-length prefix blocks with a constant block into a flat boolean tensor', 'create a vectorized causal mask for batch sizes greater than 8 using hit/miss glue mask fixup', 'create a cached causal mask using precomputed glue, diagonal, and ones components for batch sizes up to 8', 'build a prefill payload with input ids, eagle activations, device, max blocks, and draft block tables', 'create decode tensors from sequences with block size, draft flag, verify mode, and k parameter', 'build padded block tables tensor from sequences with optional draft flag', 'create prefill tensors from sequences with block size, draft flag, and skip first token option', 'test decode tensor preparation for normal decoding and verify paths with k parameter', 'create a SpeculateResult dataclass with speculation tokens, logits, and optional cache hits', 'create a VerifyResult dataclass with new suffixes, recovery tokens, and optional eagle actions', 'implement the SpeculatorBase prefill method to generate speculative tokens from sequences', 'implement the SpeculatorBase speculate method to produce speculation results given sequences', 'implement the VerifierBase verify method to validate speculative tokens against the target model']
```

Usage

```
{'build_prepare_prefill_payload': 'build a prefill payload with input ids, eagle activations, device, max blocks, and draft block tables', 'create_prepare_decode_tensors_from_seqs': 'create decode tensors from sequences with block size, draft flag, verify mode, and k parameter', 'build_prepare_block_tables_from_seqs': 'build padded block tables tensor from sequences with optional draft flag', 'create_prepare_prefill_tensors_from_seqs': 'create prefill tensors from sequences with block size, draft flag, and skip first token option', 'test_prepare_decode_tensors_from_seqs': 'test decode tensor preparation for normal decoding and verify paths with k parameter'}
```

## File: tanishqkumar_ssd/ssd/engine/helpers/speculate_types.py

Prompts

```
['run the CUDA graph for speculative verify step with input ids, positions, and graph vars', 'run the CUDA graph for decode step with optional hidden states for EAGLE draft models', 'run the FI tree decode CUDA graph with precomputed KV metadata and packed attention masks', 'capture CUDA graphs for decode with power-of-two bucket sizing for large batch sizes', 'capture CUDA graphs for FI tree decode with fake plan setup and logits computation', 'build a causal attention mask for SSD decoding using get_custom_mask with context lengths, step, K, and cache hits', 'create an iteration-specific attention mask tensor given prefix length, K, and F parameters', 'run flat_blocks_after_cat to concatenate variable-length prefix blocks with a constant block into a flat boolean tensor', 'create a vectorized causal mask for batch sizes greater than 8 using hit/miss glue mask fixup', 'create a cached causal mask using precomputed glue, diagonal, and ones components for batch sizes up to 8', 'build a prefill payload with input ids, eagle activations, device, max blocks, and draft block tables', 'create decode tensors from sequences with block size, draft flag, verify mode, and k parameter', 'build padded block tables tensor from sequences with optional draft flag', 'create prefill tensors from sequences with block size, draft flag, and skip first token option', 'test decode tensor preparation for normal decoding and verify paths with k parameter', 'create a SpeculateResult dataclass with speculation tokens, logits, and optional cache hits', 'create a VerifyResult dataclass with new suffixes, recovery tokens, and optional eagle actions', 'implement the SpeculatorBase prefill method to generate speculative tokens from sequences', 'implement the SpeculatorBase speculate method to produce speculation results given sequences', 'implement the VerifierBase verify method to validate speculative tokens against the target model']
```

Usage

```
{'create_SpeculateResult': 'create a SpeculateResult dataclass with speculation tokens, logits, and optional cache hits', 'create_VerifyResult': 'create a VerifyResult dataclass with new suffixes, recovery tokens, and optional eagle actions', 'implement_SpeculatorBase_prefill': 'implement the SpeculatorBase prefill method to generate speculative tokens from sequences', 'implement_SpeculatorBase_speculate': 'implement the SpeculatorBase speculate method to produce speculation results given sequences', 'implement_VerifierBase_verify': 'implement the VerifierBase verify method to validate speculative tokens against the target model'}
```


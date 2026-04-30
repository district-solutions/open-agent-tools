# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/test/attention/test_flashattn_backend.py

Prompts

```
['test the FlashAttentionBackend with extend and decode forward modes against TorchNativeAttnBackend reference', 'test draft_decode_set_expand_metadata for updating cache seqlens and page table during speculative decoding', 'test draft_decode_set_expand_metadata with multiple batch sizes and varying last page lengths', 'test FlashAttentionBackend forward extend with context parallel size greater than 1', 'test FlashAttentionBackend with page size greater than 1 for KV cache block allocation', 'test FlashAttentionBackend MLA forward extend and decode modes against TorchNativeAttnBackend reference', 'test the FlashAttentionBackend forward extend with MLA KV cache and rope compression', 'test the FlashAttentionBackend forward decode with cached prefix tokens in MLA mode', 'test FlashAttentionBackend forward extend with prefix tokens using MLA KV cache', 'test setting up MLA KV cache buffers with nope and rope components for RadixAttention layer', 'test the prefix chunk KV index computation with various batch sizes and prefix lens configurations', 'create a mock forward batch with configurable max chunk capacity for unit testing', 'create a mock request-to-token pool with integer-mapped token indices for testing', 'check KV indices computed by the triton kernel against a reference implementation', 'prepare chunked prefix cache info including starts, seq lengths, and KV indices for a forward batch', 'test the TRTLLMMLA backend class with decode and prefill output matching', 'build rotary embedding wrapper using config and rope scaling parameters', 'compare TRTLLM and reference attention outputs with configurable tolerance', 'create a forward batch with sequence lengths and KV pool for decode mode', 'test TRTLLM MLA metadata initialization and block KV indices structure', 'test pad and unpad draft extend Triton kernels for query and output tensors']
```

Usage

```
{'test_flashattn_backend': 'test the FlashAttentionBackend with extend and decode forward modes against TorchNativeAttnBackend reference', 'test_draft_decode_set_expand_metadata': 'test draft_decode_set_expand_metadata for updating cache seqlens and page table during speculative decoding', 'test_draft_decode_set_expand_metadata_multi_batch': 'test draft_decode_set_expand_metadata with multiple batch sizes and varying last page lengths', 'test_flashattn_backend_cp': 'test FlashAttentionBackend forward extend with context parallel size greater than 1', 'test_flashattn_backend_page_size': 'test FlashAttentionBackend with page size greater than 1 for KV cache block allocation'}
```

## File: sgl-project_sglang/python/sglang/test/attention/test_flashattn_mla_backend.py

Prompts

```
['test the FlashAttentionBackend with extend and decode forward modes against TorchNativeAttnBackend reference', 'test draft_decode_set_expand_metadata for updating cache seqlens and page table during speculative decoding', 'test draft_decode_set_expand_metadata with multiple batch sizes and varying last page lengths', 'test FlashAttentionBackend forward extend with context parallel size greater than 1', 'test FlashAttentionBackend with page size greater than 1 for KV cache block allocation', 'test FlashAttentionBackend MLA forward extend and decode modes against TorchNativeAttnBackend reference', 'test the FlashAttentionBackend forward extend with MLA KV cache and rope compression', 'test the FlashAttentionBackend forward decode with cached prefix tokens in MLA mode', 'test FlashAttentionBackend forward extend with prefix tokens using MLA KV cache', 'test setting up MLA KV cache buffers with nope and rope components for RadixAttention layer', 'test the prefix chunk KV index computation with various batch sizes and prefix lens configurations', 'create a mock forward batch with configurable max chunk capacity for unit testing', 'create a mock request-to-token pool with integer-mapped token indices for testing', 'check KV indices computed by the triton kernel against a reference implementation', 'prepare chunked prefix cache info including starts, seq lengths, and KV indices for a forward batch', 'test the TRTLLMMLA backend class with decode and prefill output matching', 'build rotary embedding wrapper using config and rope scaling parameters', 'compare TRTLLM and reference attention outputs with configurable tolerance', 'create a forward batch with sequence lengths and KV pool for decode mode', 'test TRTLLM MLA metadata initialization and block KV indices structure', 'test pad and unpad draft extend Triton kernels for query and output tensors']
```

Usage

```
{'test_flashattn_mla_backend': 'test FlashAttentionBackend MLA forward extend and decode modes against TorchNativeAttnBackend reference', 'test_forward_extend_mla': 'test the FlashAttentionBackend forward extend with MLA KV cache and rope compression', 'test_forward_decode_mla': 'test the FlashAttentionBackend forward decode with cached prefix tokens in MLA mode', 'test_forward_extend_with_prefix_mla': 'test FlashAttentionBackend forward extend with prefix tokens using MLA KV cache', 'test_mla_kv_cache_setup': 'test setting up MLA KV cache buffers with nope and rope components for RadixAttention layer'}
```

## File: sgl-project_sglang/python/sglang/test/attention/test_prefix_chunk_info.py

Prompts

```
['test the FlashAttentionBackend with extend and decode forward modes against TorchNativeAttnBackend reference', 'test draft_decode_set_expand_metadata for updating cache seqlens and page table during speculative decoding', 'test draft_decode_set_expand_metadata with multiple batch sizes and varying last page lengths', 'test FlashAttentionBackend forward extend with context parallel size greater than 1', 'test FlashAttentionBackend with page size greater than 1 for KV cache block allocation', 'test FlashAttentionBackend MLA forward extend and decode modes against TorchNativeAttnBackend reference', 'test the FlashAttentionBackend forward extend with MLA KV cache and rope compression', 'test the FlashAttentionBackend forward decode with cached prefix tokens in MLA mode', 'test FlashAttentionBackend forward extend with prefix tokens using MLA KV cache', 'test setting up MLA KV cache buffers with nope and rope components for RadixAttention layer', 'test the prefix chunk KV index computation with various batch sizes and prefix lens configurations', 'create a mock forward batch with configurable max chunk capacity for unit testing', 'create a mock request-to-token pool with integer-mapped token indices for testing', 'check KV indices computed by the triton kernel against a reference implementation', 'prepare chunked prefix cache info including starts, seq lengths, and KV indices for a forward batch', 'test the TRTLLMMLA backend class with decode and prefill output matching', 'build rotary embedding wrapper using config and rope scaling parameters', 'compare TRTLLM and reference attention outputs with configurable tolerance', 'create a forward batch with sequence lengths and KV pool for decode mode', 'test TRTLLM MLA metadata initialization and block KV indices structure', 'test pad and unpad draft extend Triton kernels for query and output tensors']
```

Usage

```
{'test_prefix_chunk_info': 'test the prefix chunk KV index computation with various batch sizes and prefix lens configurations', 'create_mock_forward_batch': 'create a mock forward batch with configurable max chunk capacity for unit testing', 'create_mock_req_to_token_pool': 'create a mock request-to-token pool with integer-mapped token indices for testing', 'check_kv_indices': 'check KV indices computed by the triton kernel against a reference implementation', 'prepare_chunked_prefix_cache_info': 'prepare chunked prefix cache info including starts, seq lengths, and KV indices for a forward batch'}
```

## File: sgl-project_sglang/python/sglang/test/attention/test_trtllm_mla_backend.py

Prompts

```
['test the FlashAttentionBackend with extend and decode forward modes against TorchNativeAttnBackend reference', 'test draft_decode_set_expand_metadata for updating cache seqlens and page table during speculative decoding', 'test draft_decode_set_expand_metadata with multiple batch sizes and varying last page lengths', 'test FlashAttentionBackend forward extend with context parallel size greater than 1', 'test FlashAttentionBackend with page size greater than 1 for KV cache block allocation', 'test FlashAttentionBackend MLA forward extend and decode modes against TorchNativeAttnBackend reference', 'test the FlashAttentionBackend forward extend with MLA KV cache and rope compression', 'test the FlashAttentionBackend forward decode with cached prefix tokens in MLA mode', 'test FlashAttentionBackend forward extend with prefix tokens using MLA KV cache', 'test setting up MLA KV cache buffers with nope and rope components for RadixAttention layer', 'test the prefix chunk KV index computation with various batch sizes and prefix lens configurations', 'create a mock forward batch with configurable max chunk capacity for unit testing', 'create a mock request-to-token pool with integer-mapped token indices for testing', 'check KV indices computed by the triton kernel against a reference implementation', 'prepare chunked prefix cache info including starts, seq lengths, and KV indices for a forward batch', 'test the TRTLLMMLA backend class with decode and prefill output matching', 'build rotary embedding wrapper using config and rope scaling parameters', 'compare TRTLLM and reference attention outputs with configurable tolerance', 'create a forward batch with sequence lengths and KV pool for decode mode', 'test TRTLLM MLA metadata initialization and block KV indices structure', 'test pad and unpad draft extend Triton kernels for query and output tensors']
```

Usage

```
{'test_TRTLLMMLA_backend': 'test the TRTLLMMLA backend class with decode and prefill output matching', 'build_rotary_emb': 'build rotary embedding wrapper using config and rope scaling parameters', 'compare_outputs': 'compare TRTLLM and reference attention outputs with configurable tolerance', 'create_forward_batch': 'create a forward batch with sequence lengths and KV pool for decode mode', 'test_metadata_initialization': 'test TRTLLM MLA metadata initialization and block KV indices structure', 'test_draft_extend_padding_kernels': 'test pad and unpad draft extend Triton kernels for query and output tensors'}
```


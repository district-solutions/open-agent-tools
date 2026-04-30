# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/allocator_npu.py

Prompts

```
['create an NPUPagedTokenToKVPoolAllocator instance for NPU-based KV cache page allocation', 'build token-to-KV-page mapping for extend phase allocation using prefix and sequence lengths on NPU', 'build token-to-KV-page mapping for decode phase allocation using sequence lengths on NPU', 'test freeing allocated KV cache pages by passing a tensor of free indices to the allocator', 'review the NPUPagedTokenToKVPoolAllocator class and its page allocation strategies for NPU devices', 'create a cache management operation to prefetch matmul weights using NPU streams and torch_npu prefetch', 'run the CMO stream wait to synchronize the current NPU stream after prefetch operations complete', 'build a getter for the global CMO stream used to prefetch tensor weights on NPU hardware', 'refactor the CMO stream setter to configure the global stream for NPU prefetch operations', 'test the prepare_weight_cache function with a list of weight tensors and a prefetch handle', 'create an NPUMHATokenToKVPool instance for MHA KV cache on Ascend NPU devices', 'build an NPUMLATokenToKVPool instance for MLA KV cache on Ascend NPU devices', 'test the set_kv_buffer method to write key and value tensors into NPU KV cache buffers', 'review the get_contiguous_buf_infos method for retrieving contiguous buffer metadata in disagg scenarios', 'summarize the set_index_k_buffer method for writing index key tensors into MLA NPU KV cache', 'initialize the NPU backend for Ascend hardware by calling init_npu_backend once', 'test set_default_server_args to configure attention backend and memory defaults for NPU', 'build a function to cast tensors to NPU FRACTAL_NZ format for optimal Ascend performance', 'test _is_nz_aligned to verify tensor alignment requirements for FRACTAL_NZ format', 'build a function to process shared expert computations on NPU using async stream execution']
```

Usage

```
{'create_NPUPagedTokenToKVPoolAllocator': 'create an NPUPagedTokenToKVPoolAllocator instance for NPU-based KV cache page allocation', 'build_alloc_extend': 'build token-to-KV-page mapping for extend phase allocation using prefix and sequence lengths on NPU', 'build_alloc_decode': 'build token-to-KV-page mapping for decode phase allocation using sequence lengths on NPU', 'test_free': 'test freeing allocated KV cache pages by passing a tensor of free indices to the allocator', 'review_NPUPagedTokenToKVPoolAllocator': 'review the NPUPagedTokenToKVPoolAllocator class and its page allocation strategies for NPU devices'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/cmo.py

Prompts

```
['create an NPUPagedTokenToKVPoolAllocator instance for NPU-based KV cache page allocation', 'build token-to-KV-page mapping for extend phase allocation using prefix and sequence lengths on NPU', 'build token-to-KV-page mapping for decode phase allocation using sequence lengths on NPU', 'test freeing allocated KV cache pages by passing a tensor of free indices to the allocator', 'review the NPUPagedTokenToKVPoolAllocator class and its page allocation strategies for NPU devices', 'create a cache management operation to prefetch matmul weights using NPU streams and torch_npu prefetch', 'run the CMO stream wait to synchronize the current NPU stream after prefetch operations complete', 'build a getter for the global CMO stream used to prefetch tensor weights on NPU hardware', 'refactor the CMO stream setter to configure the global stream for NPU prefetch operations', 'test the prepare_weight_cache function with a list of weight tensors and a prefetch handle', 'create an NPUMHATokenToKVPool instance for MHA KV cache on Ascend NPU devices', 'build an NPUMLATokenToKVPool instance for MLA KV cache on Ascend NPU devices', 'test the set_kv_buffer method to write key and value tensors into NPU KV cache buffers', 'review the get_contiguous_buf_infos method for retrieving contiguous buffer metadata in disagg scenarios', 'summarize the set_index_k_buffer method for writing index key tensors into MLA NPU KV cache', 'initialize the NPU backend for Ascend hardware by calling init_npu_backend once', 'test set_default_server_args to configure attention backend and memory defaults for NPU', 'build a function to cast tensors to NPU FRACTAL_NZ format for optimal Ascend performance', 'test _is_nz_aligned to verify tensor alignment requirements for FRACTAL_NZ format', 'build a function to process shared expert computations on NPU using async stream execution']
```

Usage

```
{'create_prepare_weight_cache': 'create a cache management operation to prefetch matmul weights using NPU streams and torch_npu prefetch', 'run_wait_cmo_stream': 'run the CMO stream wait to synchronize the current NPU stream after prefetch operations complete', 'build_get_cmo_stream': 'build a getter for the global CMO stream used to prefetch tensor weights on NPU hardware', 'refactor_set_cmo_stream': 'refactor the CMO stream setter to configure the global stream for NPU prefetch operations', 'test_prepare_weight_cache': 'test the prepare_weight_cache function with a list of weight tensors and a prefetch handle'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/memory_pool_npu.py

Prompts

```
['create an NPUPagedTokenToKVPoolAllocator instance for NPU-based KV cache page allocation', 'build token-to-KV-page mapping for extend phase allocation using prefix and sequence lengths on NPU', 'build token-to-KV-page mapping for decode phase allocation using sequence lengths on NPU', 'test freeing allocated KV cache pages by passing a tensor of free indices to the allocator', 'review the NPUPagedTokenToKVPoolAllocator class and its page allocation strategies for NPU devices', 'create a cache management operation to prefetch matmul weights using NPU streams and torch_npu prefetch', 'run the CMO stream wait to synchronize the current NPU stream after prefetch operations complete', 'build a getter for the global CMO stream used to prefetch tensor weights on NPU hardware', 'refactor the CMO stream setter to configure the global stream for NPU prefetch operations', 'test the prepare_weight_cache function with a list of weight tensors and a prefetch handle', 'create an NPUMHATokenToKVPool instance for MHA KV cache on Ascend NPU devices', 'build an NPUMLATokenToKVPool instance for MLA KV cache on Ascend NPU devices', 'test the set_kv_buffer method to write key and value tensors into NPU KV cache buffers', 'review the get_contiguous_buf_infos method for retrieving contiguous buffer metadata in disagg scenarios', 'summarize the set_index_k_buffer method for writing index key tensors into MLA NPU KV cache', 'initialize the NPU backend for Ascend hardware by calling init_npu_backend once', 'test set_default_server_args to configure attention backend and memory defaults for NPU', 'build a function to cast tensors to NPU FRACTAL_NZ format for optimal Ascend performance', 'test _is_nz_aligned to verify tensor alignment requirements for FRACTAL_NZ format', 'build a function to process shared expert computations on NPU using async stream execution']
```

Usage

```
{'create_NPUMHATokenToKVPool': 'create an NPUMHATokenToKVPool instance for MHA KV cache on Ascend NPU devices', 'build_NPUMLATokenToKVPool': 'build an NPUMLATokenToKVPool instance for MLA KV cache on Ascend NPU devices', 'test_set_kv_buffer': 'test the set_kv_buffer method to write key and value tensors into NPU KV cache buffers', 'review_get_contiguous_buf_infos': 'review the get_contiguous_buf_infos method for retrieving contiguous buffer metadata in disagg scenarios', 'summarize_set_index_k_buffer': 'summarize the set_index_k_buffer method for writing index key tensors into MLA NPU KV cache'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/utils.py

Prompts

```
['create an NPUPagedTokenToKVPoolAllocator instance for NPU-based KV cache page allocation', 'build token-to-KV-page mapping for extend phase allocation using prefix and sequence lengths on NPU', 'build token-to-KV-page mapping for decode phase allocation using sequence lengths on NPU', 'test freeing allocated KV cache pages by passing a tensor of free indices to the allocator', 'review the NPUPagedTokenToKVPoolAllocator class and its page allocation strategies for NPU devices', 'create a cache management operation to prefetch matmul weights using NPU streams and torch_npu prefetch', 'run the CMO stream wait to synchronize the current NPU stream after prefetch operations complete', 'build a getter for the global CMO stream used to prefetch tensor weights on NPU hardware', 'refactor the CMO stream setter to configure the global stream for NPU prefetch operations', 'test the prepare_weight_cache function with a list of weight tensors and a prefetch handle', 'create an NPUMHATokenToKVPool instance for MHA KV cache on Ascend NPU devices', 'build an NPUMLATokenToKVPool instance for MLA KV cache on Ascend NPU devices', 'test the set_kv_buffer method to write key and value tensors into NPU KV cache buffers', 'review the get_contiguous_buf_infos method for retrieving contiguous buffer metadata in disagg scenarios', 'summarize the set_index_k_buffer method for writing index key tensors into MLA NPU KV cache', 'initialize the NPU backend for Ascend hardware by calling init_npu_backend once', 'test set_default_server_args to configure attention backend and memory defaults for NPU', 'build a function to cast tensors to NPU FRACTAL_NZ format for optimal Ascend performance', 'test _is_nz_aligned to verify tensor alignment requirements for FRACTAL_NZ format', 'build a function to process shared expert computations on NPU using async stream execution']
```

Usage

```
{'build_init_npu_backend': 'initialize the NPU backend for Ascend hardware by calling init_npu_backend once', 'test_set_default_server_args': 'test set_default_server_args to configure attention backend and memory defaults for NPU', 'build_npu_format_cast': 'build a function to cast tensors to NPU FRACTAL_NZ format for optimal Ascend performance', 'test_is_nz_aligned': 'test _is_nz_aligned to verify tensor alignment requirements for FRACTAL_NZ format', 'build_process_shared_expert': 'build a function to process shared expert computations on NPU using async stream execution'}
```


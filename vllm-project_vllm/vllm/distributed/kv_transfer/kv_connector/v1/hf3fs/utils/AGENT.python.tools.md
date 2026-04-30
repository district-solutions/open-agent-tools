# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/hf3fs/utils/common.py

Prompts

```
['create a thread-safe atomic counter for round-robin operations with a given size', 'build a load block info dataclass with computed blocks, blocks to load, and fetch block ids', 'build a save block info dataclass with skip leading blocks count', 'create a request scheduling state with token ids, allocated block ids, and scheduling phase', 'create hf3fs request metadata from a scheduling state with block size and load operation', 'build an hf3fs connector metadata container and add request metadata entries', 'test the request scheduling state needs_loading and is_ready_to_load methods', 'refactor the request scheduling state update_tokens_and_blocks to normalize block ids', 'scatter kv cache data from a source tensor to kv cache storage using token indices', 'gather kv cache data from kv cache storage to a destination tensor using token indices', 'create a copy buffer allocator memory pool for tensor buffers to avoid frequent allocation and deallocation', 'alloc tensor buffers from the copy buffer allocator pool by specifying the count', 'free tensor buffers back to the copy buffer allocator pool to reuse them', 'test the Hf3fsClient class that provides a mock file-based KV store for debugging and testing', 'test the batch_read method that reads data from a file at specified offsets into PyTorch tensors', 'test the batch_write method that writes tensor data to a file at specified offsets with CUDA event synchronization', 'test the Hf3fsClient constructor that initializes a mock client with path, size, bytes_per_page, and entries parameters', 'test the get_size method that returns the total size of the underlying storage file']
```

Usage

```
{'create_atomic_counter': 'create a thread-safe atomic counter for round-robin operations with a given size', 'build_load_block_info': 'build a load block info dataclass with computed blocks, blocks to load, and fetch block ids', 'build_save_block_info': 'build a save block info dataclass with skip leading blocks count', 'create_request_scheduling_state': 'create a request scheduling state with token ids, allocated block ids, and scheduling phase', 'create_hf3fs_request_metadata': 'create hf3fs request metadata from a scheduling state with block size and load operation', 'build_hf3fs_connector_metadata': 'build an hf3fs connector metadata container and add request metadata entries', 'test_request_scheduling_state': 'test the request scheduling state needs_loading and is_ready_to_load methods', 'refactor_request_scheduling_state': 'refactor the request scheduling state update_tokens_and_blocks to normalize block ids'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/hf3fs/utils/gather_scatter_helper.py

Prompts

```
['create a thread-safe atomic counter for round-robin operations with a given size', 'build a load block info dataclass with computed blocks, blocks to load, and fetch block ids', 'build a save block info dataclass with skip leading blocks count', 'create a request scheduling state with token ids, allocated block ids, and scheduling phase', 'create hf3fs request metadata from a scheduling state with block size and load operation', 'build an hf3fs connector metadata container and add request metadata entries', 'test the request scheduling state needs_loading and is_ready_to_load methods', 'refactor the request scheduling state update_tokens_and_blocks to normalize block ids', 'scatter kv cache data from a source tensor to kv cache storage using token indices', 'gather kv cache data from kv cache storage to a destination tensor using token indices', 'create a copy buffer allocator memory pool for tensor buffers to avoid frequent allocation and deallocation', 'alloc tensor buffers from the copy buffer allocator pool by specifying the count', 'free tensor buffers back to the copy buffer allocator pool to reuse them', 'test the Hf3fsClient class that provides a mock file-based KV store for debugging and testing', 'test the batch_read method that reads data from a file at specified offsets into PyTorch tensors', 'test the batch_write method that writes tensor data to a file at specified offsets with CUDA event synchronization', 'test the Hf3fsClient constructor that initializes a mock client with path, size, bytes_per_page, and entries parameters', 'test the get_size method that returns the total size of the underlying storage file']
```

Usage

```
{'scatter_kv_caches': 'scatter kv cache data from a source tensor to kv cache storage using token indices', 'gather_kv_caches': 'gather kv cache data from kv cache storage to a destination tensor using token indices', 'create_copybufferallocator': 'create a copy buffer allocator memory pool for tensor buffers to avoid frequent allocation and deallocation', 'alloc_buffer_copybufferallocator': 'alloc tensor buffers from the copy buffer allocator pool by specifying the count', 'free_buffer_copybufferallocator': 'free tensor buffers back to the copy buffer allocator pool to reuse them'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/hf3fs/utils/hf3fs_mock_client.py

Prompts

```
['create a thread-safe atomic counter for round-robin operations with a given size', 'build a load block info dataclass with computed blocks, blocks to load, and fetch block ids', 'build a save block info dataclass with skip leading blocks count', 'create a request scheduling state with token ids, allocated block ids, and scheduling phase', 'create hf3fs request metadata from a scheduling state with block size and load operation', 'build an hf3fs connector metadata container and add request metadata entries', 'test the request scheduling state needs_loading and is_ready_to_load methods', 'refactor the request scheduling state update_tokens_and_blocks to normalize block ids', 'scatter kv cache data from a source tensor to kv cache storage using token indices', 'gather kv cache data from kv cache storage to a destination tensor using token indices', 'create a copy buffer allocator memory pool for tensor buffers to avoid frequent allocation and deallocation', 'alloc tensor buffers from the copy buffer allocator pool by specifying the count', 'free tensor buffers back to the copy buffer allocator pool to reuse them', 'test the Hf3fsClient class that provides a mock file-based KV store for debugging and testing', 'test the batch_read method that reads data from a file at specified offsets into PyTorch tensors', 'test the batch_write method that writes tensor data to a file at specified offsets with CUDA event synchronization', 'test the Hf3fsClient constructor that initializes a mock client with path, size, bytes_per_page, and entries parameters', 'test the get_size method that returns the total size of the underlying storage file']
```

Usage

```
{'test_Hf3fsClient': 'test the Hf3fsClient class that provides a mock file-based KV store for debugging and testing', 'test_batch_read': 'test the batch_read method that reads data from a file at specified offsets into PyTorch tensors', 'test_batch_write': 'test the batch_write method that writes tensor data to a file at specified offsets with CUDA event synchronization', 'test_Hf3fsClient_init': 'test the Hf3fsClient constructor that initializes a mock client with path, size, bytes_per_page, and entries parameters', 'test_get_size': 'test the get_size method that returns the total size of the underlying storage file'}
```


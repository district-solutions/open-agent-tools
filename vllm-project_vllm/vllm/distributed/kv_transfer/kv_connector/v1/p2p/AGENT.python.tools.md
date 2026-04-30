# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/p2p/p2p_nccl_connector.py

Prompts

```
['create a P2pNcclConnector instance for KV cache transfer between vLLM worker nodes using NCCL', 'build P2pNcclConnectorMetadata containing request metadata for KV cache transfer operations', "run start_load_kv to load KV cache from remote workers into vLLM's paged KV buffer", "run save_kv_layer to save KV cache from vLLM's paged buffer to remote workers via NCCL", 'run build_connector_meta to construct connector metadata from scheduler output for chunked prefill and new requests', 'create a P2pNcclEngine instance for peer-to-peer NCCL-based KV cache transfer between GPU ranks', 'send a CUDA tensor to a remote address using P2pNcclEngine with PUT, PUT_ASYNC, or GET transfer mode', 'receive a CUDA tensor from a remote address using P2pNcclEngine with NCCL communication', 'test the P2pNcclEngine create_connect method for establishing ZMQ and NCCL connections to a remote address', 'review the P2pNcclEngine listen_for_requests method that handles NEW, PUT, and GET commands from remote peers', 'create a TensorMemoryPool instance with a given max_block_size and optional min_block_size for buddy allocation', 'allocate a memory block of at least the requested size using the buddy allocation system', 'store a CUDA tensor into pinned host memory and return its address', 'load a tensor from pinned host memory back to a specified CUDA device', 'free an allocated memory block and merge buddy blocks back into the free lists']
```

Usage

```
{'create_P2pNcclConnector': 'create a P2pNcclConnector instance for KV cache transfer between vLLM worker nodes using NCCL', 'build_P2pNcclConnectorMetadata': 'build P2pNcclConnectorMetadata containing request metadata for KV cache transfer operations', 'run_start_load_kv': "run start_load_kv to load KV cache from remote workers into vLLM's paged KV buffer", 'run_save_kv_layer': "run save_kv_layer to save KV cache from vLLM's paged buffer to remote workers via NCCL", 'run_build_connector_meta': 'run build_connector_meta to construct connector metadata from scheduler output for chunked prefill and new requests'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/p2p/p2p_nccl_engine.py

Prompts

```
['create a P2pNcclConnector instance for KV cache transfer between vLLM worker nodes using NCCL', 'build P2pNcclConnectorMetadata containing request metadata for KV cache transfer operations', "run start_load_kv to load KV cache from remote workers into vLLM's paged KV buffer", "run save_kv_layer to save KV cache from vLLM's paged buffer to remote workers via NCCL", 'run build_connector_meta to construct connector metadata from scheduler output for chunked prefill and new requests', 'create a P2pNcclEngine instance for peer-to-peer NCCL-based KV cache transfer between GPU ranks', 'send a CUDA tensor to a remote address using P2pNcclEngine with PUT, PUT_ASYNC, or GET transfer mode', 'receive a CUDA tensor from a remote address using P2pNcclEngine with NCCL communication', 'test the P2pNcclEngine create_connect method for establishing ZMQ and NCCL connections to a remote address', 'review the P2pNcclEngine listen_for_requests method that handles NEW, PUT, and GET commands from remote peers', 'create a TensorMemoryPool instance with a given max_block_size and optional min_block_size for buddy allocation', 'allocate a memory block of at least the requested size using the buddy allocation system', 'store a CUDA tensor into pinned host memory and return its address', 'load a tensor from pinned host memory back to a specified CUDA device', 'free an allocated memory block and merge buddy blocks back into the free lists']
```

Usage

```
{'create_P2pNcclEngine': 'create a P2pNcclEngine instance for peer-to-peer NCCL-based KV cache transfer between GPU ranks', 'send_P2pNcclEngine_tensor': 'send a CUDA tensor to a remote address using P2pNcclEngine with PUT, PUT_ASYNC, or GET transfer mode', 'recv_P2pNcclEngine_tensor': 'receive a CUDA tensor from a remote address using P2pNcclEngine with NCCL communication', 'test_P2pNcclEngine_create_connect': 'test the P2pNcclEngine create_connect method for establishing ZMQ and NCCL connections to a remote address', 'review_P2pNcclEngine_listen_for_requests': 'review the P2pNcclEngine listen_for_requests method that handles NEW, PUT, and GET commands from remote peers'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/p2p/tensor_memory_pool.py

Prompts

```
['create a P2pNcclConnector instance for KV cache transfer between vLLM worker nodes using NCCL', 'build P2pNcclConnectorMetadata containing request metadata for KV cache transfer operations', "run start_load_kv to load KV cache from remote workers into vLLM's paged KV buffer", "run save_kv_layer to save KV cache from vLLM's paged buffer to remote workers via NCCL", 'run build_connector_meta to construct connector metadata from scheduler output for chunked prefill and new requests', 'create a P2pNcclEngine instance for peer-to-peer NCCL-based KV cache transfer between GPU ranks', 'send a CUDA tensor to a remote address using P2pNcclEngine with PUT, PUT_ASYNC, or GET transfer mode', 'receive a CUDA tensor from a remote address using P2pNcclEngine with NCCL communication', 'test the P2pNcclEngine create_connect method for establishing ZMQ and NCCL connections to a remote address', 'review the P2pNcclEngine listen_for_requests method that handles NEW, PUT, and GET commands from remote peers', 'create a TensorMemoryPool instance with a given max_block_size and optional min_block_size for buddy allocation', 'allocate a memory block of at least the requested size using the buddy allocation system', 'store a CUDA tensor into pinned host memory and return its address', 'load a tensor from pinned host memory back to a specified CUDA device', 'free an allocated memory block and merge buddy blocks back into the free lists']
```

Usage

```
{'create_TensorMemoryPool': 'create a TensorMemoryPool instance with a given max_block_size and optional min_block_size for buddy allocation', 'allocate_memory_block': 'allocate a memory block of at least the requested size using the buddy allocation system', 'store_tensor_cuda': 'store a CUDA tensor into pinned host memory and return its address', 'load_tensor_to_device': 'load a tensor from pinned host memory back to a specified CUDA device', 'free_memory_block': 'free an allocated memory block and merge buddy blocks back into the free lists'}
```


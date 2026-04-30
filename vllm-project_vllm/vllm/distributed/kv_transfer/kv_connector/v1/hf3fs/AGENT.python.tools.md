# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/hf3fs/hf3fs_client.py

Prompts

```
['create an Hf3fsClient instance with a file path, size, bytes per page, and max concurrent entries', 'batch read tensors from the Hf3fsClient at specified byte offsets using read-synchronized I/O', 'batch write tensors to the Hf3fsClient at specified byte offsets using write-synchronized I/O', 'close the Hf3fsClient and release all shared memory, iorings, and file descriptor resources', 'flush pending writes to disk on the Hf3fsClient file descriptor via os.fsync', 'build an HF3FS KV connector for vLLM to store and retrieve KV cache data across distributed workers', 'submit an async save operation for KV cache blocks to HF3FS storage with block hashes and IDs', 'submit an async load operation to retrieve KV cache blocks from HF3FS storage by block hashes', 'get the number of new tokens that can be loaded from the external HF3FS cache for a request', 'build connector metadata from scheduler output to coordinate KV cache save and load across requests', 'collect KV connector statistics including save and load duration percentiles and failure counts', 'build Prometheus metrics for HF3FS KV connector save and load duration histograms and failure counters', 'run the HF3FS metadata server on a specified host and port for KV cache transfer', 'initialize a worker rank with a specified number of memory pages on the metadata server', 'allocate pages for a batch of keys on a specific rank in the distributed KV transfer system', 'confirm write operations for keys and release allocated pages back to the free pool', 'check if multiple keys exist and are complete across all ranks in the TP world']
```

Usage

```
{'create_hf3fs_client': 'create an Hf3fsClient instance with a file path, size, bytes per page, and max concurrent entries', 'batch_read_hf3fs_client': 'batch read tensors from the Hf3fsClient at specified byte offsets using read-synchronized I/O', 'batch_write_hf3fs_client': 'batch write tensors to the Hf3fsClient at specified byte offsets using write-synchronized I/O', 'close_hf3fs_client': 'close the Hf3fsClient and release all shared memory, iorings, and file descriptor resources', 'flush_hf3fs_client': 'flush pending writes to disk on the Hf3fsClient file descriptor via os.fsync'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/hf3fs/hf3fs_connector.py

Prompts

```
['create an Hf3fsClient instance with a file path, size, bytes per page, and max concurrent entries', 'batch read tensors from the Hf3fsClient at specified byte offsets using read-synchronized I/O', 'batch write tensors to the Hf3fsClient at specified byte offsets using write-synchronized I/O', 'close the Hf3fsClient and release all shared memory, iorings, and file descriptor resources', 'flush pending writes to disk on the Hf3fsClient file descriptor via os.fsync', 'build an HF3FS KV connector for vLLM to store and retrieve KV cache data across distributed workers', 'submit an async save operation for KV cache blocks to HF3FS storage with block hashes and IDs', 'submit an async load operation to retrieve KV cache blocks from HF3FS storage by block hashes', 'get the number of new tokens that can be loaded from the external HF3FS cache for a request', 'build connector metadata from scheduler output to coordinate KV cache save and load across requests', 'collect KV connector statistics including save and load duration percentiles and failure counts', 'build Prometheus metrics for HF3FS KV connector save and load duration histograms and failure counters', 'run the HF3FS metadata server on a specified host and port for KV cache transfer', 'initialize a worker rank with a specified number of memory pages on the metadata server', 'allocate pages for a batch of keys on a specific rank in the distributed KV transfer system', 'confirm write operations for keys and release allocated pages back to the free pool', 'check if multiple keys exist and are complete across all ranks in the TP world']
```

Usage

```
{'build_hf3fs_connector': 'build an HF3FS KV connector for vLLM to store and retrieve KV cache data across distributed workers', 'submit_save_operation': 'submit an async save operation for KV cache blocks to HF3FS storage with block hashes and IDs', 'submit_load_operation': 'submit an async load operation to retrieve KV cache blocks from HF3FS storage by block hashes', 'get_num_new_matched_tokens': 'get the number of new tokens that can be loaded from the external HF3FS cache for a request', 'build_connector_meta': 'build connector metadata from scheduler output to coordinate KV cache save and load across requests', 'collect_kv_connector_stats': 'collect KV connector statistics including save and load duration percentiles and failure counts', 'build_prom_metrics': 'build Prometheus metrics for HF3FS KV connector save and load duration histograms and failure counters'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/hf3fs/hf3fs_metadata_server.py

Prompts

```
['create an Hf3fsClient instance with a file path, size, bytes per page, and max concurrent entries', 'batch read tensors from the Hf3fsClient at specified byte offsets using read-synchronized I/O', 'batch write tensors to the Hf3fsClient at specified byte offsets using write-synchronized I/O', 'close the Hf3fsClient and release all shared memory, iorings, and file descriptor resources', 'flush pending writes to disk on the Hf3fsClient file descriptor via os.fsync', 'build an HF3FS KV connector for vLLM to store and retrieve KV cache data across distributed workers', 'submit an async save operation for KV cache blocks to HF3FS storage with block hashes and IDs', 'submit an async load operation to retrieve KV cache blocks from HF3FS storage by block hashes', 'get the number of new tokens that can be loaded from the external HF3FS cache for a request', 'build connector metadata from scheduler output to coordinate KV cache save and load across requests', 'collect KV connector statistics including save and load duration percentiles and failure counts', 'build Prometheus metrics for HF3FS KV connector save and load duration histograms and failure counters', 'run the HF3FS metadata server on a specified host and port for KV cache transfer', 'initialize a worker rank with a specified number of memory pages on the metadata server', 'allocate pages for a batch of keys on a specific rank in the distributed KV transfer system', 'confirm write operations for keys and release allocated pages back to the free pool', 'check if multiple keys exist and are complete across all ranks in the TP world']
```

Usage

```
{'run_metadata_server': 'run the HF3FS metadata server on a specified host and port for KV cache transfer', 'initialize_rank': 'initialize a worker rank with a specified number of memory pages on the metadata server', 'allocate_pages_for_keys': 'allocate pages for a batch of keys on a specific rank in the distributed KV transfer system', 'confirm_write_for_keys': 'confirm write operations for keys and release allocated pages back to the free pool', 'batch_key_exists': 'check if multiple keys exist and are complete across all ranks in the TP world'}
```


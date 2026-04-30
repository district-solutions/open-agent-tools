# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/offloading/metrics.py

Prompts

```
['create an OffloadingOperationMetrics dataclass instance with op_size and op_time fields', 'record a KV transfer operation with bytes, time, and transfer type using OffloadingConnectorStats', 'aggregate stats from multiple OffloadingConnectorStats instances into one combined stats object', 'reduce collected transfer observations to total bytes and total time per transfer type', 'observe KV offload transfer stats and record histogram, byte counter, and time counter metrics', 'create an OffloadingConnectorScheduler instance with an OffloadingSpec to manage KV cache offloading', 'get the number of new tokens that can be loaded from offloaded KV cache for a request', 'build KVConnectorMetadata containing requests to load, store, and flush from scheduler output', 'update offload state after GPU block allocation by preparing load transfer specs', 'handle request completion by determining if blocks should be deferred from freeing', 'create an OffloadingConnectorWorker instance with an OffloadingSpec to manage KV cache offloading transfers', 'register KV cache tensors from attention and Mamba layers with the offloading worker for canonical cache mapping', 'register cross-layers KV cache tensor with the offloading worker for shared attention backend layouts', 'start asynchronous KV cache load transfers for requests specified in OffloadingConnectorMetadata', 'prepare KV cache store transfers deferred until the next engine step to avoid delaying token generation', 'flush unsubmitted store jobs and wait for pending store jobs when request preemptions occur', 'check for completed asynchronous KV cache transfers and return finished sending and receiving request IDs', 'retrieve KV transfer statistics including bytes transferred, timing, and transfer type metrics']
```

Usage

```
{'create_OffloadingOperationMetrics': 'create an OffloadingOperationMetrics dataclass instance with op_size and op_time fields', 'record_transfer_OffloadingConnectorStats': 'record a KV transfer operation with bytes, time, and transfer type using OffloadingConnectorStats', 'aggregate_OffloadingConnectorStats': 'aggregate stats from multiple OffloadingConnectorStats instances into one combined stats object', 'reduce_OffloadingConnectorStats': 'reduce collected transfer observations to total bytes and total time per transfer type', 'observe_OffloadPromMetrics': 'observe KV offload transfer stats and record histogram, byte counter, and time counter metrics'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/offloading/scheduler.py

Prompts

```
['create an OffloadingOperationMetrics dataclass instance with op_size and op_time fields', 'record a KV transfer operation with bytes, time, and transfer type using OffloadingConnectorStats', 'aggregate stats from multiple OffloadingConnectorStats instances into one combined stats object', 'reduce collected transfer observations to total bytes and total time per transfer type', 'observe KV offload transfer stats and record histogram, byte counter, and time counter metrics', 'create an OffloadingConnectorScheduler instance with an OffloadingSpec to manage KV cache offloading', 'get the number of new tokens that can be loaded from offloaded KV cache for a request', 'build KVConnectorMetadata containing requests to load, store, and flush from scheduler output', 'update offload state after GPU block allocation by preparing load transfer specs', 'handle request completion by determining if blocks should be deferred from freeing', 'create an OffloadingConnectorWorker instance with an OffloadingSpec to manage KV cache offloading transfers', 'register KV cache tensors from attention and Mamba layers with the offloading worker for canonical cache mapping', 'register cross-layers KV cache tensor with the offloading worker for shared attention backend layouts', 'start asynchronous KV cache load transfers for requests specified in OffloadingConnectorMetadata', 'prepare KV cache store transfers deferred until the next engine step to avoid delaying token generation', 'flush unsubmitted store jobs and wait for pending store jobs when request preemptions occur', 'check for completed asynchronous KV cache transfers and return finished sending and receiving request IDs', 'retrieve KV transfer statistics including bytes transferred, timing, and transfer type metrics']
```

Usage

```
{'create_offloading_connector_scheduler': 'create an OffloadingConnectorScheduler instance with an OffloadingSpec to manage KV cache offloading', 'get_num_new_matched_tokens': 'get the number of new tokens that can be loaded from offloaded KV cache for a request', 'build_connector_meta': 'build KVConnectorMetadata containing requests to load, store, and flush from scheduler output', 'update_state_after_alloc': 'update offload state after GPU block allocation by preparing load transfer specs', 'request_finished': 'handle request completion by determining if blocks should be deferred from freeing'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/offloading/worker.py

Prompts

```
['create an OffloadingOperationMetrics dataclass instance with op_size and op_time fields', 'record a KV transfer operation with bytes, time, and transfer type using OffloadingConnectorStats', 'aggregate stats from multiple OffloadingConnectorStats instances into one combined stats object', 'reduce collected transfer observations to total bytes and total time per transfer type', 'observe KV offload transfer stats and record histogram, byte counter, and time counter metrics', 'create an OffloadingConnectorScheduler instance with an OffloadingSpec to manage KV cache offloading', 'get the number of new tokens that can be loaded from offloaded KV cache for a request', 'build KVConnectorMetadata containing requests to load, store, and flush from scheduler output', 'update offload state after GPU block allocation by preparing load transfer specs', 'handle request completion by determining if blocks should be deferred from freeing', 'create an OffloadingConnectorWorker instance with an OffloadingSpec to manage KV cache offloading transfers', 'register KV cache tensors from attention and Mamba layers with the offloading worker for canonical cache mapping', 'register cross-layers KV cache tensor with the offloading worker for shared attention backend layouts', 'start asynchronous KV cache load transfers for requests specified in OffloadingConnectorMetadata', 'prepare KV cache store transfers deferred until the next engine step to avoid delaying token generation', 'flush unsubmitted store jobs and wait for pending store jobs when request preemptions occur', 'check for completed asynchronous KV cache transfers and return finished sending and receiving request IDs', 'retrieve KV transfer statistics including bytes transferred, timing, and transfer type metrics']
```

Usage

```
{'create_OffloadingConnectorWorker': 'create an OffloadingConnectorWorker instance with an OffloadingSpec to manage KV cache offloading transfers', 'register_kv_caches': 'register KV cache tensors from attention and Mamba layers with the offloading worker for canonical cache mapping', 'register_cross_layers_kv_cache': 'register cross-layers KV cache tensor with the offloading worker for shared attention backend layouts', 'start_kv_transfers': 'start asynchronous KV cache load transfers for requests specified in OffloadingConnectorMetadata', 'prepare_store_kv': 'prepare KV cache store transfers deferred until the next engine step to avoid delaying token generation', 'handle_preemptions': 'flush unsubmitted store jobs and wait for pending store jobs when request preemptions occur', 'get_finished': 'check for completed asynchronous KV cache transfers and return finished sending and receiving request IDs', 'get_kv_connector_stats': 'retrieve KV transfer statistics including bytes transferred, timing, and transfer type metrics'}
```


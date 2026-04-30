# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/mooncake/mooncake_connector.py

Prompts

```
['create a MooncakeConnector instance with VllmConfig and KVConnectorRole for distributed KV cache transfer', 'build MooncakeConnectorMetadata to coordinate KV cache transfer requests between prefill and decode workers', 'run MooncakeConnectorScheduler to manage KV cache receive and send state for scheduled requests', 'test MooncakeConnectorWorker for registering KV caches and transferring KV blocks between workers', 'refactor group_concurrent_contiguous to group contiguous source and destination block indices for batched KV transfers', 'build a MooncakeBootstrapServer instance to register and query distributed prefiller worker addresses', 'start the MooncakeBootstrapServer on a given host and port for worker registration', 'register a prefiller worker with engine_id, dp_rank, tp_rank, pp_rank, and address via the bootstrap server', 'query all registered workers from the MooncakeBootstrapServer returning a dict of dp_rank to EngineEntry', 'shutdown the MooncakeBootstrapServer gracefully and stop the uvicorn server thread']
```

Usage

```
{'create_mooncake_connector': 'create a MooncakeConnector instance with VllmConfig and KVConnectorRole for distributed KV cache transfer', 'build_mooncake_connector_metadata': 'build MooncakeConnectorMetadata to coordinate KV cache transfer requests between prefill and decode workers', 'run_mooncake_connector_scheduler': 'run MooncakeConnectorScheduler to manage KV cache receive and send state for scheduled requests', 'test_mooncake_connector_worker': 'test MooncakeConnectorWorker for registering KV caches and transferring KV blocks between workers', 'refactor_group_concurrent_contiguous': 'refactor group_concurrent_contiguous to group contiguous source and destination block indices for batched KV transfers'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/mooncake/mooncake_utils.py

Prompts

```
['create a MooncakeConnector instance with VllmConfig and KVConnectorRole for distributed KV cache transfer', 'build MooncakeConnectorMetadata to coordinate KV cache transfer requests between prefill and decode workers', 'run MooncakeConnectorScheduler to manage KV cache receive and send state for scheduled requests', 'test MooncakeConnectorWorker for registering KV caches and transferring KV blocks between workers', 'refactor group_concurrent_contiguous to group contiguous source and destination block indices for batched KV transfers', 'build a MooncakeBootstrapServer instance to register and query distributed prefiller worker addresses', 'start the MooncakeBootstrapServer on a given host and port for worker registration', 'register a prefiller worker with engine_id, dp_rank, tp_rank, pp_rank, and address via the bootstrap server', 'query all registered workers from the MooncakeBootstrapServer returning a dict of dp_rank to EngineEntry', 'shutdown the MooncakeBootstrapServer gracefully and stop the uvicorn server thread']
```

Usage

```
{'build_mooncake_bootstrap_server': 'build a MooncakeBootstrapServer instance to register and query distributed prefiller worker addresses', 'start_mooncake_bootstrap_server': 'start the MooncakeBootstrapServer on a given host and port for worker registration', 'register_worker_mooncake': 'register a prefiller worker with engine_id, dp_rank, tp_rank, pp_rank, and address via the bootstrap server', 'query_mooncake_workers': 'query all registered workers from the MooncakeBootstrapServer returning a dict of dp_rank to EngineEntry', 'shutdown_mooncake_bootstrap_server': 'shutdown the MooncakeBootstrapServer gracefully and stop the uvicorn server thread'}
```


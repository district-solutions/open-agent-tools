# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/factory.py

Prompts

```
['create a vLLM KV transfer connector using KVConnectorFactory.create_connector with vllm config and role', 'register a custom KV connector class with KVConnectorFactory.register_connector by name, module path, and class name', 'get a registered KV connector class by name using KVConnectorFactory.get_connector_class_by_name', 'resolve the connector class from KVTransferConfig using KVConnectorFactory.get_connector_class', 'review whether a KV connector supports HMA via supports_hma before creating it with KVConnectorFactory.create_connector', 'build the KV connector cache layout by querying the current vLLM config and connector requirements', 'aggregate KV connector outputs from all workers into a single output for the scheduler using KVOutputAggregator', 'copy KV cache blocks between host and device buffers using src and dst block indices with direction h2d or d2h', 'transform received KV cache block layout to local block size and format using postprocess functions on receive', 'build a transfer topology with local TP identity and per-engine remote transfer info for KV cache distribution']
```

Usage

```
{'create_connector_build_kv_transfer': 'create a vLLM KV transfer connector using KVConnectorFactory.create_connector with vllm config and role', 'register_connector_add_custom': 'register a custom KV connector class with KVConnectorFactory.register_connector by name, module path, and class name', 'get_connector_class_lookup': 'get a registered KV connector class by name using KVConnectorFactory.get_connector_class_by_name', 'get_connector_class_resolve': 'resolve the connector class from KVTransferConfig using KVConnectorFactory.get_connector_class', 'review_connector_hma_check': 'review whether a KV connector supports HMA via supports_hma before creating it with KVConnectorFactory.create_connector'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/utils.py

Prompts

```
['create a vLLM KV transfer connector using KVConnectorFactory.create_connector with vllm config and role', 'register a custom KV connector class with KVConnectorFactory.register_connector by name, module path, and class name', 'get a registered KV connector class by name using KVConnectorFactory.get_connector_class_by_name', 'resolve the connector class from KVTransferConfig using KVConnectorFactory.get_connector_class', 'review whether a KV connector supports HMA via supports_hma before creating it with KVConnectorFactory.create_connector', 'build the KV connector cache layout by querying the current vLLM config and connector requirements', 'aggregate KV connector outputs from all workers into a single output for the scheduler using KVOutputAggregator', 'copy KV cache blocks between host and device buffers using src and dst block indices with direction h2d or d2h', 'transform received KV cache block layout to local block size and format using postprocess functions on receive', 'build a transfer topology with local TP identity and per-engine remote transfer info for KV cache distribution']
```

Usage

```
{'build_kv_connector_cache_layout': 'build the KV connector cache layout by querying the current vLLM config and connector requirements', 'aggregate_model_runner_outputs': 'aggregate KV connector outputs from all workers into a single output for the scheduler using KVOutputAggregator', 'copy_kv_blocks_between_devices': 'copy KV cache blocks between host and device buffers using src and dst block indices with direction h2d or d2h', 'transform_received_kv_cache_layout': 'transform received KV cache block layout to local block size and format using postprocess functions on receive', 'build_transfer_topology': 'build a transfer topology with local TP identity and per-engine remote transfer info for KV cache distribution'}
```


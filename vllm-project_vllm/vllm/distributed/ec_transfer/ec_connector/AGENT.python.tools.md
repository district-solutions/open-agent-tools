# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/ec_transfer/ec_connector/base.py

Prompts

```
['build ECConnectorMetadata subclass to communicate between scheduler and worker ECConnectors', 'create an ECConnectorBase subclass instance with VllmConfig and ECConnectorRole for encoder cache transfer', 'test the has_cache_item method to check if a single encoder cache exists by identifier', 'build connector metadata from SchedulerOutput on the scheduler side to coordinate cache loading', 'review the request_finished method to handle async encoder cache freeing when a request completes', 'create an ECExampleConnector instance with vLLM config and ECConnectorRole for disk-based encoder cache storage', 'build ECExampleConnectorMetadata from scheduler output containing multimodal data hashes and token counts', 'save encoder cache tensors to disk as safetensors files for a given multimodal hash', 'load encoder cache tensors from disk safetensors files into the encoder cache dictionary', 'register an EC connector with a name, module path, and class name in the factory registry', 'create an EC connector instance from a VllmConfig and a specified ECConnectorRole', 'get the connector class by name from the registry or by importing the module path', 'build an EC connector factory that lazily loads and creates connector instances', 'register the ECExampleConnector with the factory using its module path and class name']
```

Usage

```
{'build_ec_connector_metadata': 'build ECConnectorMetadata subclass to communicate between scheduler and worker ECConnectors', 'create_ec_connector_instance': 'create an ECConnectorBase subclass instance with VllmConfig and ECConnectorRole for encoder cache transfer', 'test_has_cache_item': 'test the has_cache_item method to check if a single encoder cache exists by identifier', 'build_connector_meta_scheduler': 'build connector metadata from SchedulerOutput on the scheduler side to coordinate cache loading', 'review_request_finished': 'review the request_finished method to handle async encoder cache freeing when a request completes'}
```

## File: vllm-project_vllm/vllm/distributed/ec_transfer/ec_connector/example_connector.py

Prompts

```
['build ECConnectorMetadata subclass to communicate between scheduler and worker ECConnectors', 'create an ECConnectorBase subclass instance with VllmConfig and ECConnectorRole for encoder cache transfer', 'test the has_cache_item method to check if a single encoder cache exists by identifier', 'build connector metadata from SchedulerOutput on the scheduler side to coordinate cache loading', 'review the request_finished method to handle async encoder cache freeing when a request completes', 'create an ECExampleConnector instance with vLLM config and ECConnectorRole for disk-based encoder cache storage', 'build ECExampleConnectorMetadata from scheduler output containing multimodal data hashes and token counts', 'save encoder cache tensors to disk as safetensors files for a given multimodal hash', 'load encoder cache tensors from disk safetensors files into the encoder cache dictionary', 'register an EC connector with a name, module path, and class name in the factory registry', 'create an EC connector instance from a VllmConfig and a specified ECConnectorRole', 'get the connector class by name from the registry or by importing the module path', 'build an EC connector factory that lazily loads and creates connector instances', 'register the ECExampleConnector with the factory using its module path and class name']
```

Usage

```
{'create_ec_example_connector': 'create an ECExampleConnector instance with vLLM config and ECConnectorRole for disk-based encoder cache storage', 'build_connector_metadata': 'build ECExampleConnectorMetadata from scheduler output containing multimodal data hashes and token counts', 'test_has_cache_item': 'test whether an encoder cache file exists externally for a given multimodal data hash', 'save_encoder_caches': 'save encoder cache tensors to disk as safetensors files for a given multimodal hash', 'load_encoder_caches': 'load encoder cache tensors from disk safetensors files into the encoder cache dictionary'}
```

## File: vllm-project_vllm/vllm/distributed/ec_transfer/ec_connector/factory.py

Prompts

```
['build ECConnectorMetadata subclass to communicate between scheduler and worker ECConnectors', 'create an ECConnectorBase subclass instance with VllmConfig and ECConnectorRole for encoder cache transfer', 'test the has_cache_item method to check if a single encoder cache exists by identifier', 'build connector metadata from SchedulerOutput on the scheduler side to coordinate cache loading', 'review the request_finished method to handle async encoder cache freeing when a request completes', 'create an ECExampleConnector instance with vLLM config and ECConnectorRole for disk-based encoder cache storage', 'build ECExampleConnectorMetadata from scheduler output containing multimodal data hashes and token counts', 'save encoder cache tensors to disk as safetensors files for a given multimodal hash', 'load encoder cache tensors from disk safetensors files into the encoder cache dictionary', 'register an EC connector with a name, module path, and class name in the factory registry', 'create an EC connector instance from a VllmConfig and a specified ECConnectorRole', 'get the connector class by name from the registry or by importing the module path', 'build an EC connector factory that lazily loads and creates connector instances', 'register the ECExampleConnector with the factory using its module path and class name']
```

Usage

```
{'register_connector_ec_connector': 'register an EC connector with a name, module path, and class name in the factory registry', 'create_connector_vllm_config': 'create an EC connector instance from a VllmConfig and a specified ECConnectorRole', 'get_connector_class_ec_config': 'get the connector class by name from the registry or by importing the module path', 'build_ec_connector_factory': 'build an EC connector factory that lazily loads and creates connector instances', 'register_ec_example_connector': 'register the ECExampleConnector with the factory using its module path and class name'}
```


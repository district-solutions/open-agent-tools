# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/adapters/config.py

Prompts

```
['create a ModuleMap dataclass instance with a module name and a dictionary of weight tensors', 'implement a concrete subclass of AdapterConfig that overrides the map_weights_for_model abstract method', 'define the map_weights_for_model method to return a ModuleMap and a set of unused weight names', 'use AdapterConfig as an abstract base class to enforce a consistent adapter configuration interface', 'map adapter weights to model modules using the map_weights_for_model method and return a ModuleMap', 'load a LoRA adapter configuration from a Hugging Face model ID using LoraConfig.load', 'prepare and shard LoRA weights for a specific layer type across all model layers using LoraWeights.prepare_weights', 'shard LoRA A and B weight tensors across a distributed process group using shard_lora_weights', 'compute the LoRA scaling factor from alpha and rank parameters using get_scaling_factor', 'load batch LoRA weights for a segment of adapters using BatchLoraWeights.load', 'create an AdapterBatchMetadata dataclass with adapter indices, adapter set, segments, and segment indices tensors', 'add an adapter with a given index and weights to a LayerAdapterWeights instance', 'remove an adapter by index from a LayerAdapterWeights instance', 'get batched adapter weight data from LayerAdapterWeights by bucketing adapters by batch class type', 'create an AdapterBatchData instance from AdapterBatchMetadata and a dictionary of LayerAdapterWeights']
```

Usage

```
{'create_modulemap_dataclass': 'create a ModuleMap dataclass instance with a module name and a dictionary of weight tensors', 'implement_adapterconfig_subclass': 'implement a concrete subclass of AdapterConfig that overrides the map_weights_for_model abstract method', 'define_map_weights_for_model': 'define the map_weights_for_model method to return a ModuleMap and a set of unused weight names', 'use_adapterconfig_base_class': 'use AdapterConfig as an abstract base class to enforce a consistent adapter configuration interface', 'map_adapter_weights_to_modules': 'map adapter weights to model modules using the map_weights_for_model method and return a ModuleMap'}
```

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/adapters/lora.py

Prompts

```
['create a ModuleMap dataclass instance with a module name and a dictionary of weight tensors', 'implement a concrete subclass of AdapterConfig that overrides the map_weights_for_model abstract method', 'define the map_weights_for_model method to return a ModuleMap and a set of unused weight names', 'use AdapterConfig as an abstract base class to enforce a consistent adapter configuration interface', 'map adapter weights to model modules using the map_weights_for_model method and return a ModuleMap', 'load a LoRA adapter configuration from a Hugging Face model ID using LoraConfig.load', 'prepare and shard LoRA weights for a specific layer type across all model layers using LoraWeights.prepare_weights', 'shard LoRA A and B weight tensors across a distributed process group using shard_lora_weights', 'compute the LoRA scaling factor from alpha and rank parameters using get_scaling_factor', 'load batch LoRA weights for a segment of adapters using BatchLoraWeights.load', 'create an AdapterBatchMetadata dataclass with adapter indices, adapter set, segments, and segment indices tensors', 'add an adapter with a given index and weights to a LayerAdapterWeights instance', 'remove an adapter by index from a LayerAdapterWeights instance', 'get batched adapter weight data from LayerAdapterWeights by bucketing adapters by batch class type', 'create an AdapterBatchData instance from AdapterBatchMetadata and a dictionary of LayerAdapterWeights']
```

Usage

```
{'load_lora_config': 'load a LoRA adapter configuration from a Hugging Face model ID using LoraConfig.load', 'prepare_lora_weights': 'prepare and shard LoRA weights for a specific layer type across all model layers using LoraWeights.prepare_weights', 'shard_lora_weights': 'shard LoRA A and B weight tensors across a distributed process group using shard_lora_weights', 'compute_scaling_factor': 'compute the LoRA scaling factor from alpha and rank parameters using get_scaling_factor', 'load_batch_lora_weights': 'load batch LoRA weights for a segment of adapters using BatchLoraWeights.load'}
```

## File: huggingface_text-generation-inference/backends/gaudi/server/text_generation_server/adapters/weights.py

Prompts

```
['create a ModuleMap dataclass instance with a module name and a dictionary of weight tensors', 'implement a concrete subclass of AdapterConfig that overrides the map_weights_for_model abstract method', 'define the map_weights_for_model method to return a ModuleMap and a set of unused weight names', 'use AdapterConfig as an abstract base class to enforce a consistent adapter configuration interface', 'map adapter weights to model modules using the map_weights_for_model method and return a ModuleMap', 'load a LoRA adapter configuration from a Hugging Face model ID using LoraConfig.load', 'prepare and shard LoRA weights for a specific layer type across all model layers using LoraWeights.prepare_weights', 'shard LoRA A and B weight tensors across a distributed process group using shard_lora_weights', 'compute the LoRA scaling factor from alpha and rank parameters using get_scaling_factor', 'load batch LoRA weights for a segment of adapters using BatchLoraWeights.load', 'create an AdapterBatchMetadata dataclass with adapter indices, adapter set, segments, and segment indices tensors', 'add an adapter with a given index and weights to a LayerAdapterWeights instance', 'remove an adapter by index from a LayerAdapterWeights instance', 'get batched adapter weight data from LayerAdapterWeights by bucketing adapters by batch class type', 'create an AdapterBatchData instance from AdapterBatchMetadata and a dictionary of LayerAdapterWeights']
```

Usage

```
{'create_adapter_batch_metadata': 'create an AdapterBatchMetadata dataclass with adapter indices, adapter set, segments, and segment indices tensors', 'add_adapter_to_layer': 'add an adapter with a given index and weights to a LayerAdapterWeights instance', 'remove_adapter_from_layer': 'remove an adapter by index from a LayerAdapterWeights instance', 'get_batched_adapter_data': 'get batched adapter weight data from LayerAdapterWeights by bucketing adapters by batch class type', 'create_adapter_batch_data_from_meta': 'create an AdapterBatchData instance from AdapterBatchMetadata and a dictionary of LayerAdapterWeights'}
```


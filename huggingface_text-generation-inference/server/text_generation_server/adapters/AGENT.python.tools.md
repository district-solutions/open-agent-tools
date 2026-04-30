# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/server/text_generation_server/adapters/config.py

Prompts

```
['create a ModuleMap dataclass instance with a module name and a dictionary of weight tensors', 'create a subclass of AdapterConfig that implements the map_weights_for_model abstract method', 'implement the map_weights_for_model method to map adapter weights to a ModuleMap and unused weight names', 'review the AdapterConfig abstract base class and its map_weights_for_model signature for correctness', 'refactor the ModuleMap dataclass to add validation for module_name or module_weights fields', 'load a LoRA adapter configuration from a Hugging Face model ID using LoraConfig.load', 'prepare and shard LoRA weights for a specific layer type using LoraWeights.prepare_weights', 'shard LoRA A and B weight tensors across a distributed process group using shard_lora_weights', 'compute the LoRA scaling factor from alpha and rank using get_scaling_factor', 'load batch LoRA weights for a segment using BatchLoraWeights.load', 'create an AdapterBatchMetadata dataclass with adapter_indices, adapter_set, adapter_segments, and segment_indices tensors', 'implement a subclass of AdapterWeights abstract class with get_batch_types and speculative_tokens methods', 'implement a subclass of BatchAdapterWeights with has_adapter and load abstract methods', 'use LayerAdapterWeights to add, remove, and check adapter weights for a specific model layer', 'build an AdapterBatchData from batch metadata and layer weights using the from_meta static method']
```

Usage

```
{'create_ModuleMap': 'create a ModuleMap dataclass instance with a module name and a dictionary of weight tensors', 'create_AdapterConfig_subclass': 'create a subclass of AdapterConfig that implements the map_weights_for_model abstract method', 'implement_map_weights_for_model': 'implement the map_weights_for_model method to map adapter weights to a ModuleMap and unused weight names', 'review_AdapterConfig': 'review the AdapterConfig abstract base class and its map_weights_for_model signature for correctness', 'refactor_ModuleMap': 'refactor the ModuleMap dataclass to add validation for module_name or module_weights fields'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/adapters/lora.py

Prompts

```
['create a ModuleMap dataclass instance with a module name and a dictionary of weight tensors', 'create a subclass of AdapterConfig that implements the map_weights_for_model abstract method', 'implement the map_weights_for_model method to map adapter weights to a ModuleMap and unused weight names', 'review the AdapterConfig abstract base class and its map_weights_for_model signature for correctness', 'refactor the ModuleMap dataclass to add validation for module_name or module_weights fields', 'load a LoRA adapter configuration from a Hugging Face model ID using LoraConfig.load', 'prepare and shard LoRA weights for a specific layer type using LoraWeights.prepare_weights', 'shard LoRA A and B weight tensors across a distributed process group using shard_lora_weights', 'compute the LoRA scaling factor from alpha and rank using get_scaling_factor', 'load batch LoRA weights for a segment using BatchLoraWeights.load', 'create an AdapterBatchMetadata dataclass with adapter_indices, adapter_set, adapter_segments, and segment_indices tensors', 'implement a subclass of AdapterWeights abstract class with get_batch_types and speculative_tokens methods', 'implement a subclass of BatchAdapterWeights with has_adapter and load abstract methods', 'use LayerAdapterWeights to add, remove, and check adapter weights for a specific model layer', 'build an AdapterBatchData from batch metadata and layer weights using the from_meta static method']
```

Usage

```
{'load_lora_config': 'load a LoRA adapter configuration from a Hugging Face model ID using LoraConfig.load', 'prepare_lora_weights': 'prepare and shard LoRA weights for a specific layer type using LoraWeights.prepare_weights', 'shard_lora_weights': 'shard LoRA A and B weight tensors across a distributed process group using shard_lora_weights', 'compute_scaling_factor': 'compute the LoRA scaling factor from alpha and rank using get_scaling_factor', 'load_batch_lora_weights': 'load batch LoRA weights for a segment using BatchLoraWeights.load'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/adapters/weights.py

Prompts

```
['create a ModuleMap dataclass instance with a module name and a dictionary of weight tensors', 'create a subclass of AdapterConfig that implements the map_weights_for_model abstract method', 'implement the map_weights_for_model method to map adapter weights to a ModuleMap and unused weight names', 'review the AdapterConfig abstract base class and its map_weights_for_model signature for correctness', 'refactor the ModuleMap dataclass to add validation for module_name or module_weights fields', 'load a LoRA adapter configuration from a Hugging Face model ID using LoraConfig.load', 'prepare and shard LoRA weights for a specific layer type using LoraWeights.prepare_weights', 'shard LoRA A and B weight tensors across a distributed process group using shard_lora_weights', 'compute the LoRA scaling factor from alpha and rank using get_scaling_factor', 'load batch LoRA weights for a segment using BatchLoraWeights.load', 'create an AdapterBatchMetadata dataclass with adapter_indices, adapter_set, adapter_segments, and segment_indices tensors', 'implement a subclass of AdapterWeights abstract class with get_batch_types and speculative_tokens methods', 'implement a subclass of BatchAdapterWeights with has_adapter and load abstract methods', 'use LayerAdapterWeights to add, remove, and check adapter weights for a specific model layer', 'build an AdapterBatchData from batch metadata and layer weights using the from_meta static method']
```

Usage

```
{'create_adapter_batch_metadata': 'create an AdapterBatchMetadata dataclass with adapter_indices, adapter_set, adapter_segments, and segment_indices tensors', 'implement_adapter_weights_subclass': 'implement a subclass of AdapterWeights abstract class with get_batch_types and speculative_tokens methods', 'implement_batch_adapter_weights_subclass': 'implement a subclass of BatchAdapterWeights with has_adapter and load abstract methods', 'manage_layer_adapter_weights': 'use LayerAdapterWeights to add, remove, and check adapter weights for a specific model layer', 'build_adapter_batch_data': 'build an AdapterBatchData from batch metadata and layer weights using the from_meta static method'}
```


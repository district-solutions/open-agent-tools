# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/model_executor/custom_op.py

Prompts

```
['register a custom op class with a name and optional dynamic argument dimensions', 'register a pluggable layer class with a name for module composition and out-of-tree replacement', 'test whether a registered custom op is enabled based on compilation config settings', 'build a forward method dispatcher that routes to the appropriate platform backend', 'review out-of-tree custom op registration that replaces in-tree ops at instantiation time', 'load weight data into a column-parallel parameter by narrowing and copying from loaded tensor', 'load weight data into a row-parallel parameter by narrowing and copying from loaded tensor', 'load qkv weight data into parameter with shard offset, shard size, shard id and num heads arguments', 'adjust shard size and shard offset for packed weights accounting for packed factor and marlin tile size', "permute a parameter's tensor layout to specified input and output dimensions while preserving packed dim", 'set attributes on a torch weight tensor without overwriting existing attributes', 'replace a parameter of a torch nn module layer while maintaining weight loader capability', 'get packed modules mapping from a torch nn model by merging child module mappings', 'get moe expert mapping from a torch nn model or its child modules', 'disable inductor graph partition for torch versions 2.9.0.dev and newer']
```

Usage

```
{'create_CustomOp_register': 'register a custom op class with a name and optional dynamic argument dimensions', 'create_PluggableLayer_register': 'register a pluggable layer class with a name for module composition and out-of-tree replacement', 'test_CustomOp_enabled': 'test whether a registered custom op is enabled based on compilation config settings', 'build_CustomOp_dispatch_forward': 'build a forward method dispatcher that routes to the appropriate platform backend', 'review_CustomOp_register_oot': 'review out-of-tree custom op registration that replaces in-tree ops at instantiation time'}
```

## File: vllm-project_vllm/vllm/model_executor/parameter.py

Prompts

```
['register a custom op class with a name and optional dynamic argument dimensions', 'register a pluggable layer class with a name for module composition and out-of-tree replacement', 'test whether a registered custom op is enabled based on compilation config settings', 'build a forward method dispatcher that routes to the appropriate platform backend', 'review out-of-tree custom op registration that replaces in-tree ops at instantiation time', 'load weight data into a column-parallel parameter by narrowing and copying from loaded tensor', 'load weight data into a row-parallel parameter by narrowing and copying from loaded tensor', 'load qkv weight data into parameter with shard offset, shard size, shard id and num heads arguments', 'adjust shard size and shard offset for packed weights accounting for packed factor and marlin tile size', "permute a parameter's tensor layout to specified input and output dimensions while preserving packed dim", 'set attributes on a torch weight tensor without overwriting existing attributes', 'replace a parameter of a torch nn module layer while maintaining weight loader capability', 'get packed modules mapping from a torch nn model by merging child module mappings', 'get moe expert mapping from a torch nn model or its child modules', 'disable inductor graph partition for torch versions 2.9.0.dev and newer']
```

Usage

```
{'load_weight_into_column_parallel_parameter': 'load weight data into a column-parallel parameter by narrowing and copying from loaded tensor', 'load_weight_into_row_parallel_parameter': 'load weight data into a row-parallel parameter by narrowing and copying from loaded tensor', 'load_qkv_weight_with_sharding': 'load qkv weight data into parameter with shard offset, shard size, shard id and num heads arguments', 'adjust_shard_indexes_for_packing': 'adjust shard size and shard offset for packed weights accounting for packed factor and marlin tile size', 'permute_param_layout': "permute a parameter's tensor layout to specified input and output dimensions while preserving packed dim"}
```

## File: vllm-project_vllm/vllm/model_executor/utils.py

Prompts

```
['register a custom op class with a name and optional dynamic argument dimensions', 'register a pluggable layer class with a name for module composition and out-of-tree replacement', 'test whether a registered custom op is enabled based on compilation config settings', 'build a forward method dispatcher that routes to the appropriate platform backend', 'review out-of-tree custom op registration that replaces in-tree ops at instantiation time', 'load weight data into a column-parallel parameter by narrowing and copying from loaded tensor', 'load weight data into a row-parallel parameter by narrowing and copying from loaded tensor', 'load qkv weight data into parameter with shard offset, shard size, shard id and num heads arguments', 'adjust shard size and shard offset for packed weights accounting for packed factor and marlin tile size', "permute a parameter's tensor layout to specified input and output dimensions while preserving packed dim", 'set attributes on a torch weight tensor without overwriting existing attributes', 'replace a parameter of a torch nn module layer while maintaining weight loader capability', 'get packed modules mapping from a torch nn model by merging child module mappings', 'get moe expert mapping from a torch nn model or its child modules', 'disable inductor graph partition for torch versions 2.9.0.dev and newer']
```

Usage

```
{'set_weight_attrs_tensor': 'set attributes on a torch weight tensor without overwriting existing attributes', 'replace_parameter_layer': 'replace a parameter of a torch nn module layer while maintaining weight loader capability', 'get_packed_modules_mapping_model': 'get packed modules mapping from a torch nn model by merging child module mappings', 'get_moe_expert_mapping_model': 'get moe expert mapping from a torch nn model or its child modules', 'maybe_disable_graph_partition_backend': 'disable inductor graph partition for torch versions 2.9.0.dev and newer'}
```


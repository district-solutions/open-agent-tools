# Agent Python Tools

- repo: google-deepmind/alphafold3
- repo_uri: https://github.com/google-deepmind/alphafold3

## File: google-deepmind_alphafold3/src/alphafold3/model/components/haiku_modules.py

Prompts

```
['create a LayerNorm module with upcast support for bfloat16 inputs in a Haiku neural network', 'build a custom Linear module with configurable initializer and einsum-based matrix multiplication for arbitrary rank inputs', 'get weight and bias parameters for a linear layer using haiku_linear_get_params with specified output channels', 'review the _get_initializer_scale function to understand fan-in scaling and truncated normal weight initialization logic', 'test the LayerNorm class upcast behavior to verify bfloat16 inputs are cast to float32 before normalization', 'build a python module using sharded_map to apply a function over shards with configurable shard_size and in_axes', 'build a python module using sharded_apply to process JAX arrays in memory-efficient shards with custom shard_size', 'build a python module using inference_subbatch to run a Haiku module over subbatches with split and concat', 'review the sharded_map function to understand how it trades off memory usage versus throughput using hk.vmap', 'review the sharded_apply function to understand how it slices inputs, scans shards, and stacks outputs', 'create a function that removes string and invalid dtype features from an AlphaFold batch dict before sending to TPU', 'build a Haiku custom getter that casts parameters to bfloat16 dtype when the original dtype is bfloat16', 'create a context manager that wraps Haiku modules with a bfloat16 getter for automatic dtype casting', 'compute a masked mean over JAX arrays with support for broadcasting along specified axes', 'review the list of valid numpy dtypes allowed for TPU feature tensors in AlphaFold batch processing']
```

Usage

```
{'create_layer_norm_module': 'create a LayerNorm module with upcast support for bfloat16 inputs in a Haiku neural network', 'build_linear_layer': 'build a custom Linear module with configurable initializer and einsum-based matrix multiplication for arbitrary rank inputs', 'get_linear_params': 'get weight and bias parameters for a linear layer using haiku_linear_get_params with specified output channels', 'review_get_initializer_scale': 'review the _get_initializer_scale function to understand fan-in scaling and truncated normal weight initialization logic', 'test_layer_norm_upcast': 'test the LayerNorm class upcast behavior to verify bfloat16 inputs are cast to float32 before normalization'}
```

## File: google-deepmind_alphafold3/src/alphafold3/model/components/mapping.py

Prompts

```
['create a LayerNorm module with upcast support for bfloat16 inputs in a Haiku neural network', 'build a custom Linear module with configurable initializer and einsum-based matrix multiplication for arbitrary rank inputs', 'get weight and bias parameters for a linear layer using haiku_linear_get_params with specified output channels', 'review the _get_initializer_scale function to understand fan-in scaling and truncated normal weight initialization logic', 'test the LayerNorm class upcast behavior to verify bfloat16 inputs are cast to float32 before normalization', 'build a python module using sharded_map to apply a function over shards with configurable shard_size and in_axes', 'build a python module using sharded_apply to process JAX arrays in memory-efficient shards with custom shard_size', 'build a python module using inference_subbatch to run a Haiku module over subbatches with split and concat', 'review the sharded_map function to understand how it trades off memory usage versus throughput using hk.vmap', 'review the sharded_apply function to understand how it slices inputs, scans shards, and stacks outputs', 'create a function that removes string and invalid dtype features from an AlphaFold batch dict before sending to TPU', 'build a Haiku custom getter that casts parameters to bfloat16 dtype when the original dtype is bfloat16', 'create a context manager that wraps Haiku modules with a bfloat16 getter for automatic dtype casting', 'compute a masked mean over JAX arrays with support for broadcasting along specified axes', 'review the list of valid numpy dtypes allowed for TPU feature tensors in AlphaFold batch processing']
```

Usage

```
{'build_sharded_map': 'build a python module using sharded_map to apply a function over shards with configurable shard_size and in_axes', 'build_sharded_apply': 'build a python module using sharded_apply to process JAX arrays in memory-efficient shards with custom shard_size', 'build_inference_subbatch': 'build a python module using inference_subbatch to run a Haiku module over subbatches with split and concat', 'review_sharded_map': 'review the sharded_map function to understand how it trades off memory usage versus throughput using hk.vmap', 'review_sharded_apply': 'review the sharded_apply function to understand how it slices inputs, scans shards, and stacks outputs'}
```

## File: google-deepmind_alphafold3/src/alphafold3/model/components/utils.py

Prompts

```
['create a LayerNorm module with upcast support for bfloat16 inputs in a Haiku neural network', 'build a custom Linear module with configurable initializer and einsum-based matrix multiplication for arbitrary rank inputs', 'get weight and bias parameters for a linear layer using haiku_linear_get_params with specified output channels', 'review the _get_initializer_scale function to understand fan-in scaling and truncated normal weight initialization logic', 'test the LayerNorm class upcast behavior to verify bfloat16 inputs are cast to float32 before normalization', 'build a python module using sharded_map to apply a function over shards with configurable shard_size and in_axes', 'build a python module using sharded_apply to process JAX arrays in memory-efficient shards with custom shard_size', 'build a python module using inference_subbatch to run a Haiku module over subbatches with split and concat', 'review the sharded_map function to understand how it trades off memory usage versus throughput using hk.vmap', 'review the sharded_apply function to understand how it slices inputs, scans shards, and stacks outputs', 'create a function that removes string and invalid dtype features from an AlphaFold batch dict before sending to TPU', 'build a Haiku custom getter that casts parameters to bfloat16 dtype when the original dtype is bfloat16', 'create a context manager that wraps Haiku modules with a bfloat16 getter for automatic dtype casting', 'compute a masked mean over JAX arrays with support for broadcasting along specified axes', 'review the list of valid numpy dtypes allowed for TPU feature tensors in AlphaFold batch processing']
```

Usage

```
{'remove_invalidly_typed_feats': 'create a function that removes string and invalid dtype features from an AlphaFold batch dict before sending to TPU', 'bfloat16_getter': 'build a Haiku custom getter that casts parameters to bfloat16 dtype when the original dtype is bfloat16', 'bfloat16_context': 'create a context manager that wraps Haiku modules with a bfloat16 getter for automatic dtype casting', 'mask_mean': 'compute a masked mean over JAX arrays with support for broadcasting along specified axes', 'VALID_DTYPES': 'review the list of valid numpy dtypes allowed for TPU feature tensors in AlphaFold batch processing'}
```


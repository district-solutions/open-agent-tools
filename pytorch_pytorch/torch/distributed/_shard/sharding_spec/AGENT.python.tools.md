# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/_shard/sharding_spec/_internals.py

Prompts

```
['test the validate_non_overlapping_shards_metadata function to detect overlapping shard metadata', 'build a check_tensor function to verify shard metadata is compatible with tensor dimensions', 'create a get_chunk_sharding_params function to compute start position and chunk size for a given rank', 'build a get_split_size function to compute chunk size inline with torch.chunk behavior', 'build a get_chunked_dim_size function to compute the dimension size of a chunk at a given index', 'create an EnumerableShardingSpec with a list of ShardMetadata objects to define a custom sharding layout', 'build ShardedTensorMetadata from tensor sizes and tensor properties using EnumerableShardingSpec', 'test EnumerableShardingSpec shard validation for overlapping shards and inconsistent ranks', 'create a custom sharding spec op decorator to override torch operations for a ShardingSpec subclass', 'infer a ChunkShardingSpec or EnumerableShardingSpec from a list of ShardMetadata objects', 'create a ChunkShardingSpec to shard a tensor along a specified dimension across multiple devices', 'build sharded tensor metadata from tensor sizes and properties using ChunkShardingSpec', 'shard a local tensor into a distributed ShardedTensor using ChunkShardingSpec and scatter across ranks', 'verify that a sharding dimension is a valid integer for ChunkShardingSpec', 'parse and validate remote device placement strings in ChunkShardingSpec placements list']
```

Usage

```
{'test_validate_non_overlapping_shards_metadata': 'test the validate_non_overlapping_shards_metadata function to detect overlapping shard metadata', 'build_check_tensor_compatibility': 'build a check_tensor function to verify shard metadata is compatible with tensor dimensions', 'create_get_chunk_sharding_params': 'create a get_chunk_sharding_params function to compute start position and chunk size for a given rank', 'build_get_split_size': 'build a get_split_size function to compute chunk size inline with torch.chunk behavior', 'build_get_chunked_dim_size': 'build a get_chunked_dim_size function to compute the dimension size of a chunk at a given index'}
```

## File: pytorch_pytorch/torch/distributed/_shard/sharding_spec/api.py

Prompts

```
['test the validate_non_overlapping_shards_metadata function to detect overlapping shard metadata', 'build a check_tensor function to verify shard metadata is compatible with tensor dimensions', 'create a get_chunk_sharding_params function to compute start position and chunk size for a given rank', 'build a get_split_size function to compute chunk size inline with torch.chunk behavior', 'build a get_chunked_dim_size function to compute the dimension size of a chunk at a given index', 'create an EnumerableShardingSpec with a list of ShardMetadata objects to define a custom sharding layout', 'build ShardedTensorMetadata from tensor sizes and tensor properties using EnumerableShardingSpec', 'test EnumerableShardingSpec shard validation for overlapping shards and inconsistent ranks', 'create a custom sharding spec op decorator to override torch operations for a ShardingSpec subclass', 'infer a ChunkShardingSpec or EnumerableShardingSpec from a list of ShardMetadata objects', 'create a ChunkShardingSpec to shard a tensor along a specified dimension across multiple devices', 'build sharded tensor metadata from tensor sizes and properties using ChunkShardingSpec', 'shard a local tensor into a distributed ShardedTensor using ChunkShardingSpec and scatter across ranks', 'verify that a sharding dimension is a valid integer for ChunkShardingSpec', 'parse and validate remote device placement strings in ChunkShardingSpec placements list']
```

Usage

```
{'create_EnumerableShardingSpec': 'create an EnumerableShardingSpec with a list of ShardMetadata objects to define a custom sharding layout', 'build_EnumerableShardingSpec_metadata': 'build ShardedTensorMetadata from tensor sizes and tensor properties using EnumerableShardingSpec', 'test_EnumerableShardingSpec_validation': 'test EnumerableShardingSpec shard validation for overlapping shards and inconsistent ranks', 'create_custom_sharding_spec_op': 'create a custom sharding spec op decorator to override torch operations for a ShardingSpec subclass', 'infer_sharding_spec_from_metadata': 'infer a ChunkShardingSpec or EnumerableShardingSpec from a list of ShardMetadata objects'}
```

## File: pytorch_pytorch/torch/distributed/_shard/sharding_spec/chunk_sharding_spec.py

Prompts

```
['test the validate_non_overlapping_shards_metadata function to detect overlapping shard metadata', 'build a check_tensor function to verify shard metadata is compatible with tensor dimensions', 'create a get_chunk_sharding_params function to compute start position and chunk size for a given rank', 'build a get_split_size function to compute chunk size inline with torch.chunk behavior', 'build a get_chunked_dim_size function to compute the dimension size of a chunk at a given index', 'create an EnumerableShardingSpec with a list of ShardMetadata objects to define a custom sharding layout', 'build ShardedTensorMetadata from tensor sizes and tensor properties using EnumerableShardingSpec', 'test EnumerableShardingSpec shard validation for overlapping shards and inconsistent ranks', 'create a custom sharding spec op decorator to override torch operations for a ShardingSpec subclass', 'infer a ChunkShardingSpec or EnumerableShardingSpec from a list of ShardMetadata objects', 'create a ChunkShardingSpec to shard a tensor along a specified dimension across multiple devices', 'build sharded tensor metadata from tensor sizes and properties using ChunkShardingSpec', 'shard a local tensor into a distributed ShardedTensor using ChunkShardingSpec and scatter across ranks', 'verify that a sharding dimension is a valid integer for ChunkShardingSpec', 'parse and validate remote device placement strings in ChunkShardingSpec placements list']
```

Usage

```
{'create_ChunkShardingSpec': 'create a ChunkShardingSpec to shard a tensor along a specified dimension across multiple devices', 'build_ChunkShardingSpec_metadata': 'build sharded tensor metadata from tensor sizes and properties using ChunkShardingSpec', 'shard_tensor_ChunkShardingSpec': 'shard a local tensor into a distributed ShardedTensor using ChunkShardingSpec and scatter across ranks', 'verify_ChunkShardingSpec_dim': 'verify that a sharding dimension is a valid integer for ChunkShardingSpec', 'parse_remote_device_ChunkShardingSpec': 'parse and validate remote device placement strings in ChunkShardingSpec placements list'}
```


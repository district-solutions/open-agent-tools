# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/_shard/sharding_spec/chunk_sharding_spec_ops/_common.py

Prompts

```
['register a sharded op on local tensor for __torch_function__ dispatch with optional early stop and customized logic', 'handle col-wise sharding base for embedding and embedding_bag operations with result distribution and column rearrangement', 'distribute results to each rank with column rearrangement based on sharding spec placements using all2all communication', 'handle max norm col-wise sharding by aggregating norms across ranks and re-normalizing embedding vectors exceeding max norm', 'handle row-wise mask for embedding look-up by masking input IDs not stored on current rank and adjusting padding index', 'test the sharded_embedding function that dispatches torch.nn.functional.embedding for sharded tensors', 'test the _validate_embedding_param function that validates input types, dimensions, and flags for sharded embedding', 'run the _handle_col_wise_sharding function that performs embedding lookup with column-wise weight sharding across ranks', 'run the _handle_row_wise_sharding function that performs embedding lookup with row-wise weight sharding across ranks', 'review the @custom_sharding_spec_op decorator that registers sharded embedding operations for ChunkShardingSpec', 'run sharded_embedding_bag to compute a sharded embedding bag aggregation with ChunkShardingSpec across multiple GPUs', 'validate input parameters for sharded embedding bag operations including tensor types, dimensions, and mode', 'handle column-wise sharding of weight for embedding bag by gathering inputs, performing local embedding lookups, and reducing results', 'handle row-wise sharding of weight for embedding bag by masking input IDs, performing local lookups, and reducing via reduce_scatter', 'gather embedding bag inputs, per_sample_weights, and offsets from all ranks using a single all_gather collective communication']
```

Usage

```
{'register_sharded_op_on_local_tensor': 'register a sharded op on local tensor for __torch_function__ dispatch with optional early stop and customized logic', 'handle_col_wise_sharding_base': 'handle col-wise sharding base for embedding and embedding_bag operations with result distribution and column rearrangement', 'result_distribute_with_col_rearrange': 'distribute results to each rank with column rearrangement based on sharding spec placements using all2all communication', 'handle_max_norm_col_wise': 'handle max norm col-wise sharding by aggregating norms across ranks and re-normalizing embedding vectors exceeding max norm', 'handle_row_wise_mask': 'handle row-wise mask for embedding look-up by masking input IDs not stored on current rank and adjusting padding index'}
```

## File: pytorch_pytorch/torch/distributed/_shard/sharding_spec/chunk_sharding_spec_ops/embedding.py

Prompts

```
['register a sharded op on local tensor for __torch_function__ dispatch with optional early stop and customized logic', 'handle col-wise sharding base for embedding and embedding_bag operations with result distribution and column rearrangement', 'distribute results to each rank with column rearrangement based on sharding spec placements using all2all communication', 'handle max norm col-wise sharding by aggregating norms across ranks and re-normalizing embedding vectors exceeding max norm', 'handle row-wise mask for embedding look-up by masking input IDs not stored on current rank and adjusting padding index', 'test the sharded_embedding function that dispatches torch.nn.functional.embedding for sharded tensors', 'test the _validate_embedding_param function that validates input types, dimensions, and flags for sharded embedding', 'run the _handle_col_wise_sharding function that performs embedding lookup with column-wise weight sharding across ranks', 'run the _handle_row_wise_sharding function that performs embedding lookup with row-wise weight sharding across ranks', 'review the @custom_sharding_spec_op decorator that registers sharded embedding operations for ChunkShardingSpec', 'run sharded_embedding_bag to compute a sharded embedding bag aggregation with ChunkShardingSpec across multiple GPUs', 'validate input parameters for sharded embedding bag operations including tensor types, dimensions, and mode', 'handle column-wise sharding of weight for embedding bag by gathering inputs, performing local embedding lookups, and reducing results', 'handle row-wise sharding of weight for embedding bag by masking input IDs, performing local lookups, and reducing via reduce_scatter', 'gather embedding bag inputs, per_sample_weights, and offsets from all ranks using a single all_gather collective communication']
```

Usage

```
{'test_sharded_embedding': 'test the sharded_embedding function that dispatches torch.nn.functional.embedding for sharded tensors', 'test_validate_embedding_param': 'test the _validate_embedding_param function that validates input types, dimensions, and flags for sharded embedding', 'run_handle_col_wise_sharding': 'run the _handle_col_wise_sharding function that performs embedding lookup with column-wise weight sharding across ranks', 'run_handle_row_wise_sharding': 'run the _handle_row_wise_sharding function that performs embedding lookup with row-wise weight sharding across ranks', 'review_custom_sharding_spec_op': 'review the @custom_sharding_spec_op decorator that registers sharded embedding operations for ChunkShardingSpec'}
```

## File: pytorch_pytorch/torch/distributed/_shard/sharding_spec/chunk_sharding_spec_ops/embedding_bag.py

Prompts

```
['register a sharded op on local tensor for __torch_function__ dispatch with optional early stop and customized logic', 'handle col-wise sharding base for embedding and embedding_bag operations with result distribution and column rearrangement', 'distribute results to each rank with column rearrangement based on sharding spec placements using all2all communication', 'handle max norm col-wise sharding by aggregating norms across ranks and re-normalizing embedding vectors exceeding max norm', 'handle row-wise mask for embedding look-up by masking input IDs not stored on current rank and adjusting padding index', 'test the sharded_embedding function that dispatches torch.nn.functional.embedding for sharded tensors', 'test the _validate_embedding_param function that validates input types, dimensions, and flags for sharded embedding', 'run the _handle_col_wise_sharding function that performs embedding lookup with column-wise weight sharding across ranks', 'run the _handle_row_wise_sharding function that performs embedding lookup with row-wise weight sharding across ranks', 'review the @custom_sharding_spec_op decorator that registers sharded embedding operations for ChunkShardingSpec', 'run sharded_embedding_bag to compute a sharded embedding bag aggregation with ChunkShardingSpec across multiple GPUs', 'validate input parameters for sharded embedding bag operations including tensor types, dimensions, and mode', 'handle column-wise sharding of weight for embedding bag by gathering inputs, performing local embedding lookups, and reducing results', 'handle row-wise sharding of weight for embedding bag by masking input IDs, performing local lookups, and reducing via reduce_scatter', 'gather embedding bag inputs, per_sample_weights, and offsets from all ranks using a single all_gather collective communication']
```

Usage

```
{'run_sharded_embedding_bag': 'run sharded_embedding_bag to compute a sharded embedding bag aggregation with ChunkShardingSpec across multiple GPUs', 'validate_embedding_bag_params': 'validate input parameters for sharded embedding bag operations including tensor types, dimensions, and mode', 'handle_col_wise_sharding': 'handle column-wise sharding of weight for embedding bag by gathering inputs, performing local embedding lookups, and reducing results', 'handle_row_wise_sharding': 'handle row-wise sharding of weight for embedding bag by masking input IDs, performing local lookups, and reducing via reduce_scatter', 'gather_embedding_bag_inputs': 'gather embedding bag inputs, per_sample_weights, and offsets from all ranks using a single all_gather collective communication'}
```


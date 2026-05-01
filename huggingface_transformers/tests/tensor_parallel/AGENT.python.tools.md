# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/tensor_parallel/test_tensor_parallel.py

Prompts

```
['test the get_packed_weights and repack_weights functions to verify packed tensor sharding and reconstruction across devices', 'test setting and retrieving the tp_plan property on a HuggingFace model with colwise and rowwise parallel styles', 'test ColwiseParallel layer sharding to verify expected sharded shapes and module attribute updates across device ranks', 'test RowwiseParallel layer sharding to verify expected sharded shapes and input feature attribute updates across device ranks', 'test PackedColwiseParallel and PackedRowwiseParallel sharding on packed and unpacked tensors to verify correct shape handling']
```

Usage

```
{'test_tensor_parallel_utils_packed_unpacked_conversion': 'test the get_packed_weights and repack_weights functions to verify packed tensor sharding and reconstruction across devices', 'test_tp_plan_property_setter_getter': 'test setting and retrieving the tp_plan property on a HuggingFace model with colwise and rowwise parallel styles', 'test_colwise_parallel_sharding': 'test ColwiseParallel layer sharding to verify expected sharded shapes and module attribute updates across device ranks', 'test_rowwise_parallel_sharding': 'test RowwiseParallel layer sharding to verify expected sharded shapes and input feature attribute updates across device ranks', 'test_packed_colwise_rowwise_sharding': 'test PackedColwiseParallel and PackedRowwiseParallel sharding on packed and unpacked tensors to verify correct shape handling'}
```


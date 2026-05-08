# Agent Python Tools

- repo: facebookresearch/optimizers
- repo_uri: https://github.com/facebookresearch/optimizers

## File: facebookresearch_optimizers/distributed_shampoo/distributor/tests/shampoo_distributor_test.py

Prompts

```
['test the Distributor merge_and_block_gradients method to verify gradient blocking and masking behavior', 'test the Distributor update_params method with blocked search directions to verify parameter updates', 'test the Distributor local_grad_selector property to verify which blocks have valid gradients', 'test the Distributor local_blocked_params property to verify the shape and values of blocked parameters', 'test the Distributor local_block_info_list property to verify BlockInfo objects and composable block IDs', 'test the FSDPDistributor _split_tensor_block_recovery method with a flattened tensor shard and original shape', 'test that _split_tensor_block_recovery raises ValueError when given a non-flat input tensor shard', 'test _split_tensor_block_recovery with 1D tensor shards using various start and end index ranges', 'test _split_tensor_block_recovery with 2D tensor shards across multiple index ranges', 'test _split_tensor_block_recovery with 3D tensor shards including partial and full block recovery', 'review SplitTensorBlockRecoveryTest class and parametrized test methods for tensor block recovery logic']
```

Usage

```
{'test_distributor_merge_and_block_gradients': 'test the Distributor merge_and_block_gradients method to verify gradient blocking and masking behavior', 'test_distributor_update_params': 'test the Distributor update_params method with blocked search directions to verify parameter updates', 'test_distributor_local_grad_selector': 'test the Distributor local_grad_selector property to verify which blocks have valid gradients', 'test_distributor_local_blocked_params': 'test the Distributor local_blocked_params property to verify the shape and values of blocked parameters', 'test_distributor_local_block_info_list': 'test the Distributor local_block_info_list property to verify BlockInfo objects and composable block IDs'}
```

## File: facebookresearch_optimizers/distributed_shampoo/distributor/tests/shampoo_fsdp_distributor_test.py

Prompts

```
['test the Distributor merge_and_block_gradients method to verify gradient blocking and masking behavior', 'test the Distributor update_params method with blocked search directions to verify parameter updates', 'test the Distributor local_grad_selector property to verify which blocks have valid gradients', 'test the Distributor local_blocked_params property to verify the shape and values of blocked parameters', 'test the Distributor local_block_info_list property to verify BlockInfo objects and composable block IDs', 'test the FSDPDistributor _split_tensor_block_recovery method with a flattened tensor shard and original shape', 'test that _split_tensor_block_recovery raises ValueError when given a non-flat input tensor shard', 'test _split_tensor_block_recovery with 1D tensor shards using various start and end index ranges', 'test _split_tensor_block_recovery with 2D tensor shards across multiple index ranges', 'test _split_tensor_block_recovery with 3D tensor shards including partial and full block recovery', 'review SplitTensorBlockRecoveryTest class and parametrized test methods for tensor block recovery logic']
```

Usage

```
{'test_split_tensor_block_recovery': 'test the FSDPDistributor _split_tensor_block_recovery method with a flattened tensor shard and original shape', 'test_illegal_tensor_shard_size': 'test that _split_tensor_block_recovery raises ValueError when given a non-flat input tensor shard', 'test_split_tensor_block_recovery_one_dim': 'test _split_tensor_block_recovery with 1D tensor shards using various start and end index ranges', 'test_split_tensor_block_recovery_two_dim': 'test _split_tensor_block_recovery with 2D tensor shards across multiple index ranges', 'test_split_tensor_block_recovery_three_dim': 'test _split_tensor_block_recovery with 3D tensor shards including partial and full block recovery'}
```

## File: facebookresearch_optimizers/distributed_shampoo/distributor/tests/shampoo_hsdp_distributor_test.py

Prompts

```
['test the Distributor merge_and_block_gradients method to verify gradient blocking and masking behavior', 'test the Distributor update_params method with blocked search directions to verify parameter updates', 'test the Distributor local_grad_selector property to verify which blocks have valid gradients', 'test the Distributor local_blocked_params property to verify the shape and values of blocked parameters', 'test the Distributor local_block_info_list property to verify BlockInfo objects and composable block IDs', 'test the FSDPDistributor _split_tensor_block_recovery method with a flattened tensor shard and original shape', 'test that _split_tensor_block_recovery raises ValueError when given a non-flat input tensor shard', 'test _split_tensor_block_recovery with 1D tensor shards using various start and end index ranges', 'test _split_tensor_block_recovery with 2D tensor shards across multiple index ranges', 'test _split_tensor_block_recovery with 3D tensor shards including partial and full block recovery', 'review SplitTensorBlockRecoveryTest class and parametrized test methods for tensor block recovery logic']
```

Usage

```
{'test_split_tensor_block_recovery_one_dim': 'test HSDPDistributor._split_tensor_block_recovery with 1D tensor shards and index ranges', 'test_split_tensor_block_recovery_two_dim': 'test HSDPDistributor._split_tensor_block_recovery with 2D tensor shards and index ranges', 'test_split_tensor_block_recovery_three_dim': 'test HSDPDistributor._split_tensor_block_recovery with 3D tensor shards and index ranges', 'test_illegal_tensor_shard_size': 'test HSDPDistributor._split_tensor_block_recovery raises ValueError when input tensor shard is not flat', 'review_split_tensor_block_recovery': 'review SplitTensorBlockRecoveryTest class and parametrized test methods for tensor block recovery logic'}
```


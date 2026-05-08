# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/common/test_data_parallel_batch_sampler.py

Prompts

```
['test creating a BalancedBatchSampler with mode atoms for a valid dataset with natoms metadata', 'test that BalancedBatchSampler raises ValueError when given an unsupported mode like natoms or neighbors', 'test that BalancedBatchSampler raises UnsupportedDatasetError when the dataset lacks natoms metadata support', 'test StatefulDistributedSampler can restore iteration state using set_epoch_and_start_iteration to skip batches', 'test the _balanced_partition function to verify it distributes samples across ranks by atom count', 'test scatter_to_model_parallel_region to split tensors across GP ranks in a multi-process setup', 'test gather_from_model_parallel_region_sum_grad to reconstruct tensors from scattered GP partitions with gradient support', 'test backward gradient flow through scatter_to_model_parallel_region using autograd with create_graph enabled', 'test backward gradient flow through gather and reduce operations across GP ranks with second-order derivatives', 'test SimpleNet forward and backward pass with node embeddings and edge index across GP and DDP ranks', 'test the get_deep utility function that retrieves nested dictionary values using dot-separated keys', 'run the pytest test for get_deep to verify nested dictionary key lookup with default values', 'review the test_get_deep function to understand how get_deep handles missing keys and defaults', 'summarize the test_get_deep test case covering nested dict access via dot-separated key paths', 'refactor the test_get_deep function to add additional edge cases for get_deep dictionary traversal', 'test that UniqueKeyLoader raises ValueError when a YAML file contains duplicate keys', 'test that UniqueKeyLoader successfully loads a YAML file with unique keys', 'create a pytest fixture that returns YAML content with duplicate keys for testing', 'create a pytest fixture that returns valid YAML content with unique keys for testing', 'create a pytest fixture that returns YAML content with an includes directive for testing']
```

Usage

```
{'test_BalancedBatchSampler_creation': 'test creating a BalancedBatchSampler with mode atoms for a valid dataset with natoms metadata', 'test_BalancedBatchSampler_invalid_mode': 'test that BalancedBatchSampler raises ValueError when given an unsupported mode like natoms or neighbors', 'test_BalancedBatchSampler_invalid_dataset': 'test that BalancedBatchSampler raises UnsupportedDatasetError when the dataset lacks natoms metadata support', 'test_StatefulDistributedSampler_state_restoration': 'test StatefulDistributedSampler can restore iteration state using set_epoch_and_start_iteration to skip batches', 'test_balanced_partition': 'test the _balanced_partition function to verify it distributes samples across ranks by atom count'}
```

## File: facebookresearch_fairchem/tests/core/common/test_gp_utils.py

Prompts

```
['test creating a BalancedBatchSampler with mode atoms for a valid dataset with natoms metadata', 'test that BalancedBatchSampler raises ValueError when given an unsupported mode like natoms or neighbors', 'test that BalancedBatchSampler raises UnsupportedDatasetError when the dataset lacks natoms metadata support', 'test StatefulDistributedSampler can restore iteration state using set_epoch_and_start_iteration to skip batches', 'test the _balanced_partition function to verify it distributes samples across ranks by atom count', 'test scatter_to_model_parallel_region to split tensors across GP ranks in a multi-process setup', 'test gather_from_model_parallel_region_sum_grad to reconstruct tensors from scattered GP partitions with gradient support', 'test backward gradient flow through scatter_to_model_parallel_region using autograd with create_graph enabled', 'test backward gradient flow through gather and reduce operations across GP ranks with second-order derivatives', 'test SimpleNet forward and backward pass with node embeddings and edge index across GP and DDP ranks', 'test the get_deep utility function that retrieves nested dictionary values using dot-separated keys', 'run the pytest test for get_deep to verify nested dictionary key lookup with default values', 'review the test_get_deep function to understand how get_deep handles missing keys and defaults', 'summarize the test_get_deep test case covering nested dict access via dot-separated key paths', 'refactor the test_get_deep function to add additional edge cases for get_deep dictionary traversal', 'test that UniqueKeyLoader raises ValueError when a YAML file contains duplicate keys', 'test that UniqueKeyLoader successfully loads a YAML file with unique keys', 'create a pytest fixture that returns YAML content with duplicate keys for testing', 'create a pytest fixture that returns valid YAML content with unique keys for testing', 'create a pytest fixture that returns YAML content with an includes directive for testing']
```

Usage

```
{'test_scatter_to_model_parallel_region': 'test scatter_to_model_parallel_region to split tensors across GP ranks in a multi-process setup', 'test_gather_from_model_parallel_region_sum_grad': 'test gather_from_model_parallel_region_sum_grad to reconstruct tensors from scattered GP partitions with gradient support', 'test_scatter_bwd_gradient_flow': 'test backward gradient flow through scatter_to_model_parallel_region using autograd with create_graph enabled', 'test_gather_sum_bwd_gradient_flow': 'test backward gradient flow through gather and reduce operations across GP ranks with second-order derivatives', 'test_simple_energy_forward_backward': 'test SimpleNet forward and backward pass with node embeddings and edge index across GP and DDP ranks'}
```

## File: facebookresearch_fairchem/tests/core/common/test_utils_.py

Prompts

```
['test creating a BalancedBatchSampler with mode atoms for a valid dataset with natoms metadata', 'test that BalancedBatchSampler raises ValueError when given an unsupported mode like natoms or neighbors', 'test that BalancedBatchSampler raises UnsupportedDatasetError when the dataset lacks natoms metadata support', 'test StatefulDistributedSampler can restore iteration state using set_epoch_and_start_iteration to skip batches', 'test the _balanced_partition function to verify it distributes samples across ranks by atom count', 'test scatter_to_model_parallel_region to split tensors across GP ranks in a multi-process setup', 'test gather_from_model_parallel_region_sum_grad to reconstruct tensors from scattered GP partitions with gradient support', 'test backward gradient flow through scatter_to_model_parallel_region using autograd with create_graph enabled', 'test backward gradient flow through gather and reduce operations across GP ranks with second-order derivatives', 'test SimpleNet forward and backward pass with node embeddings and edge index across GP and DDP ranks', 'test the get_deep utility function that retrieves nested dictionary values using dot-separated keys', 'run the pytest test for get_deep to verify nested dictionary key lookup with default values', 'review the test_get_deep function to understand how get_deep handles missing keys and defaults', 'summarize the test_get_deep test case covering nested dict access via dot-separated key paths', 'refactor the test_get_deep function to add additional edge cases for get_deep dictionary traversal', 'test that UniqueKeyLoader raises ValueError when a YAML file contains duplicate keys', 'test that UniqueKeyLoader successfully loads a YAML file with unique keys', 'create a pytest fixture that returns YAML content with duplicate keys for testing', 'create a pytest fixture that returns valid YAML content with unique keys for testing', 'create a pytest fixture that returns YAML content with an includes directive for testing']
```

Usage

```
{'test_get_deep': 'test the get_deep utility function that retrieves nested dictionary values using dot-separated keys', 'run_test_get_deep': 'run the pytest test for get_deep to verify nested dictionary key lookup with default values', 'review_test_get_deep': 'review the test_get_deep function to understand how get_deep handles missing keys and defaults', 'summarize_test_get_deep': 'summarize the test_get_deep test case covering nested dict access via dot-separated key paths', 'refactor_test_get_deep': 'refactor the test_get_deep function to add additional edge cases for get_deep dictionary traversal'}
```

## File: facebookresearch_fairchem/tests/core/common/test_yaml_loader.py

Prompts

```
['test creating a BalancedBatchSampler with mode atoms for a valid dataset with natoms metadata', 'test that BalancedBatchSampler raises ValueError when given an unsupported mode like natoms or neighbors', 'test that BalancedBatchSampler raises UnsupportedDatasetError when the dataset lacks natoms metadata support', 'test StatefulDistributedSampler can restore iteration state using set_epoch_and_start_iteration to skip batches', 'test the _balanced_partition function to verify it distributes samples across ranks by atom count', 'test scatter_to_model_parallel_region to split tensors across GP ranks in a multi-process setup', 'test gather_from_model_parallel_region_sum_grad to reconstruct tensors from scattered GP partitions with gradient support', 'test backward gradient flow through scatter_to_model_parallel_region using autograd with create_graph enabled', 'test backward gradient flow through gather and reduce operations across GP ranks with second-order derivatives', 'test SimpleNet forward and backward pass with node embeddings and edge index across GP and DDP ranks', 'test the get_deep utility function that retrieves nested dictionary values using dot-separated keys', 'run the pytest test for get_deep to verify nested dictionary key lookup with default values', 'review the test_get_deep function to understand how get_deep handles missing keys and defaults', 'summarize the test_get_deep test case covering nested dict access via dot-separated key paths', 'refactor the test_get_deep function to add additional edge cases for get_deep dictionary traversal', 'test that UniqueKeyLoader raises ValueError when a YAML file contains duplicate keys', 'test that UniqueKeyLoader successfully loads a YAML file with unique keys', 'create a pytest fixture that returns YAML content with duplicate keys for testing', 'create a pytest fixture that returns valid YAML content with unique keys for testing', 'create a pytest fixture that returns YAML content with an includes directive for testing']
```

Usage

```
{'test_invalid_config': 'test that UniqueKeyLoader raises ValueError when a YAML file contains duplicate keys', 'test_valid_config': 'test that UniqueKeyLoader successfully loads a YAML file with unique keys', 'fixture_invalid_yaml_config': 'create a pytest fixture that returns YAML content with duplicate keys for testing', 'fixture_valid_yaml_config': 'create a pytest fixture that returns valid YAML content with unique keys for testing', 'fixture_include_path_in_yaml_config': 'create a pytest fixture that returns YAML content with an includes directive for testing'}
```


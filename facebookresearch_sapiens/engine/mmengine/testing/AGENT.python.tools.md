# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/testing/compare.py

Prompts

```
['assert two PyTorch tensors are close within a given relative and absolute tolerance', 'run a Python script in the current process with custom sys.argv for coverage tracking', 'assert a dictionary contains all key-value pairs from an expected subset dictionary', "assert an object's attributes match expected values from a dictionary of attribute names and values", 'assert all weight and bias parameters of a PyTorch module are initialized to zero', 'build an mmengine Runner from a Config object using RunnerTestCase build_runner method', 'create a ToyModel with two linear layers for tensor loss and predict modes', 'create a ToyDataset with random 2D input data and label tensors for testing', 'setup distributed training environment variables including MASTER_PORT RANK and WORLD_SIZE', 'test an mmengine Runner with epoch based training config and validation interval']
```

Usage

```
{'test_tensors_allclose': 'assert two PyTorch tensors are close within a given relative and absolute tolerance', 'run_python_script_in_process': 'run a Python script in the current process with custom sys.argv for coverage tracking', 'test_dict_contains_subset': 'assert a dictionary contains all key-value pairs from an expected subset dictionary', 'test_object_attrs_equal': "assert an object's attributes match expected values from a dictionary of attribute names and values", 'test_module_params_all_zeros': 'assert all weight and bias parameters of a PyTorch module are initialized to zero'}
```

## File: facebookresearch_sapiens/engine/mmengine/testing/runner_test_case.py

Prompts

```
['assert two PyTorch tensors are close within a given relative and absolute tolerance', 'run a Python script in the current process with custom sys.argv for coverage tracking', 'assert a dictionary contains all key-value pairs from an expected subset dictionary', "assert an object's attributes match expected values from a dictionary of attribute names and values", 'assert all weight and bias parameters of a PyTorch module are initialized to zero', 'build an mmengine Runner from a Config object using RunnerTestCase build_runner method', 'create a ToyModel with two linear layers for tensor loss and predict modes', 'create a ToyDataset with random 2D input data and label tensors for testing', 'setup distributed training environment variables including MASTER_PORT RANK and WORLD_SIZE', 'test an mmengine Runner with epoch based training config and validation interval']
```

Usage

```
{'build_runner_from_cfg': 'build an mmengine Runner from a Config object using RunnerTestCase build_runner method', 'create_toy_model': 'create a ToyModel with two linear layers for tensor loss and predict modes', 'create_toy_dataset': 'create a ToyDataset with random 2D input data and label tensors for testing', 'setup_dist_env': 'setup distributed training environment variables including MASTER_PORT RANK and WORLD_SIZE', 'test_runner_epoch_based': 'test an mmengine Runner with epoch based training config and validation interval'}
```


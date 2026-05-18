# Agent Python Tools

- repo: facebookresearch/mmf
- repo_uri: https://github.com/facebookresearch/mmf

## File: facebookresearch_mmf/tests/conftest.py

Prompts

```
['get the current process RSS memory usage in bytes using psutil', 'log the start memory consumption for a pytest test item before it runs', 'log the end memory consumption for a pytest test item after it finishes', 'report memory leaks exceeding 10MB per test in the pytest terminal summary', 'create a named tuple entry with nodeid, phase, and consumed_ram for memory tracking', 'compare two PyTorch tensors for equality using torch.equal', 'compare two state dicts checking keys and tensor values for equality', 'search a log file for lines matching callable conditions and return the JSON result', 'test the SimpleModel class forward pass with a prepared batch dictionary', 'test the NumbersDataset class by creating samples with indexed tensor values']
```

Usage

```
{'get_consumed_ram': 'get the current process RSS memory usage in bytes using psutil', 'pytest_runtest_setup': 'log the start memory consumption for a pytest test item before it runs', 'pytest_runtest_teardown': 'log the end memory consumption for a pytest test item after it finishes', 'pytest_terminal_summary': 'report memory leaks exceeding 10MB per test in the pytest terminal summary', 'ConsumedRamLogEntry': 'create a named tuple entry with nodeid, phase, and consumed_ram for memory tracking'}
```

## File: facebookresearch_mmf/tests/test_utils.py

Prompts

```
['get the current process RSS memory usage in bytes using psutil', 'log the start memory consumption for a pytest test item before it runs', 'log the end memory consumption for a pytest test item after it finishes', 'report memory leaks exceeding 10MB per test in the pytest terminal summary', 'create a named tuple entry with nodeid, phase, and consumed_ram for memory tracking', 'compare two PyTorch tensors for equality using torch.equal', 'compare two state dicts checking keys and tensor values for equality', 'search a log file for lines matching callable conditions and return the JSON result', 'test the SimpleModel class forward pass with a prepared batch dictionary', 'test the NumbersDataset class by creating samples with indexed tensor values']
```

Usage

```
{'compare_tensors': 'compare two PyTorch tensors for equality using torch.equal', 'compare_state_dicts': 'compare two state dicts checking keys and tensor values for equality', 'search_log': 'search a log file for lines matching callable conditions and return the JSON result', 'test_SimpleModel': 'test the SimpleModel class forward pass with a prepared batch dictionary', 'test_NumbersDataset': 'test the NumbersDataset class by creating samples with indexed tensor values'}
```


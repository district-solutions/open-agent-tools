# Agent Python Tools

- repo: facebookresearch/cpcaudio
- repo_uri: https://github.com/facebookresearch/cpc_audio

## File: facebookresearch_cpcaudio/cpc/utils/misc.py

Prompts

```
['recursively convert torch tensors in nested lists and dicts to plain Python lists', 'save a dictionary of training logs to a JSON file with pretty printing', 'compute averaged log values by subtracting previous logs and dividing by the number of steps', 'set random seeds for Python, NumPy, and PyTorch including CUDA for reproducible experiments', 'apply a list of learning rate schedulers sequentially based on activation step thresholds', 'run the TestCombineSchedulers testCombineRamp unit test to verify ramp scheduling function behavior', 'run the TestCombineSchedulers testCombineRampStep unit test to verify combined ramp and step scheduler behavior', 'test the ramp_scheduling_function utility that linearly ramps learning rate over a specified number of epochs', 'test the SchedulerCombiner class that applies multiple learning rate schedulers sequentially with activation steps', 'review the TestCombineSchedulers unittest class and its setUp method for PyTorch optimizer and scheduler setup']
```

Usage

```
{'untensor_convert_tensors': 'recursively convert torch tensors in nested lists and dicts to plain Python lists', 'save_logs_json': 'save a dictionary of training logs to a JSON file with pretty printing', 'update_logs_average': 'compute averaged log values by subtracting previous logs and dividing by the number of steps', 'set_seed_reproducibility': 'set random seeds for Python, NumPy, and PyTorch including CUDA for reproducible experiments', 'SchedulerCombiner_sequential_schedulers': 'apply a list of learning rate schedulers sequentially based on activation step thresholds'}
```

## File: facebookresearch_cpcaudio/cpc/utils/unit_tests.py

Prompts

```
['recursively convert torch tensors in nested lists and dicts to plain Python lists', 'save a dictionary of training logs to a JSON file with pretty printing', 'compute averaged log values by subtracting previous logs and dividing by the number of steps', 'set random seeds for Python, NumPy, and PyTorch including CUDA for reproducible experiments', 'apply a list of learning rate schedulers sequentially based on activation step thresholds', 'run the TestCombineSchedulers testCombineRamp unit test to verify ramp scheduling function behavior', 'run the TestCombineSchedulers testCombineRampStep unit test to verify combined ramp and step scheduler behavior', 'test the ramp_scheduling_function utility that linearly ramps learning rate over a specified number of epochs', 'test the SchedulerCombiner class that applies multiple learning rate schedulers sequentially with activation steps', 'review the TestCombineSchedulers unittest class and its setUp method for PyTorch optimizer and scheduler setup']
```

Usage

```
{'run_testCombineRamp': 'run the TestCombineSchedulers testCombineRamp unit test to verify ramp scheduling function behavior', 'run_testCombineRampStep': 'run the TestCombineSchedulers testCombineRampStep unit test to verify combined ramp and step scheduler behavior', 'test_ramp_scheduling_function': 'test the ramp_scheduling_function utility that linearly ramps learning rate over a specified number of epochs', 'test_SchedulerCombiner': 'test the SchedulerCombiner class that applies multiple learning rate schedulers sequentially with activation steps', 'review_TestCombineSchedulers': 'review the TestCombineSchedulers unittest class and its setUp method for PyTorch optimizer and scheduler setup'}
```


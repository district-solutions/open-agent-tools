# Agent Python Tools

- repo: facebookresearch/modelopt
- repo_uri: https://github.com/facebookresearch/model_opt

## File: facebookresearch_modelopt/examples/max_batch_size.py

Prompts

```
['run a binary search to find the maximum batch size a model can handle', 'run a model with a given batch size and return whether it succeeds', 'run a model test in a separate process to isolate memory errors', 'run any function in a separate process using ProcessPoolExecutor', 'run a PyTorch model in eager mode with optional training and loss computation']
```

Usage

```
{'run_get_max': 'run a binary search to find the maximum batch size a model can handle', 'run_try_model': 'run a model with a given batch size and return whether it succeeds', 'run_try_model_in_process': 'run a model test in a separate process to isolate memory errors', 'run_run_in_process': 'run any function in a separate process using ProcessPoolExecutor', 'run_run_eager': 'run a PyTorch model in eager mode with optional training and loss computation'}
```


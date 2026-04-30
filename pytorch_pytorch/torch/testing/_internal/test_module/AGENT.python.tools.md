# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/testing/_internal/test_module/future_div.py

Prompts

```
['run the div_int_future function to compute integer division using true division operator', 'run the div_float_future function to compute float division of 3.14 by 0.125', 'test the div_int_future function to verify it returns 0.5', 'test the div_float_future function to verify it returns 25.12', 'summarize the div_int_future function that performs true division of 1 by 2', 'test the div_int_nofuture function that performs true division of 1 by 2', 'test the div_float_nofuture function that performs true division of 3.14 by 0.125', 'summarize the div_int_nofuture function that returns the true division of 1 divided by 2', 'summarize the div_float_nofuture function that returns the true division of 3.14 divided by 0.125', 'refactor the div_int_nofuture function to accept two numeric arguments for general true division']
```

Usage

```
{'run_div_int_future': 'run the div_int_future function to compute integer division using true division operator', 'run_div_float_future': 'run the div_float_future function to compute float division of 3.14 by 0.125', 'test_div_int_future': 'test the div_int_future function to verify it returns 0.5', 'test_div_float_future': 'test the div_float_future function to verify it returns 25.12', 'summarize_div_int_future': 'summarize the div_int_future function that performs true division of 1 by 2'}
```

## File: pytorch_pytorch/torch/testing/_internal/test_module/no_future_div.py

Prompts

```
['run the div_int_future function to compute integer division using true division operator', 'run the div_float_future function to compute float division of 3.14 by 0.125', 'test the div_int_future function to verify it returns 0.5', 'test the div_float_future function to verify it returns 25.12', 'summarize the div_int_future function that performs true division of 1 by 2', 'test the div_int_nofuture function that performs true division of 1 by 2', 'test the div_float_nofuture function that performs true division of 3.14 by 0.125', 'summarize the div_int_nofuture function that returns the true division of 1 divided by 2', 'summarize the div_float_nofuture function that returns the true division of 3.14 divided by 0.125', 'refactor the div_int_nofuture function to accept two numeric arguments for general true division']
```

Usage

```
{'test_div_int_nofuture': 'test the div_int_nofuture function that performs true division of 1 by 2', 'test_div_float_nofuture': 'test the div_float_nofuture function that performs true division of 3.14 by 0.125', 'summarize_div_int_nofuture': 'summarize the div_int_nofuture function that returns the true division of 1 divided by 2', 'summarize_div_float_nofuture': 'summarize the div_float_nofuture function that returns the true division of 3.14 divided by 0.125', 'refactor_div_int_nofuture': 'refactor the div_int_nofuture function to accept two numeric arguments for general true division'}
```


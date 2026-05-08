# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/test_apps/app_with_cfg_decorated/decorators/inner_decorator.py

Prompts

```
['create a decorator that asserts conf.dataset.path equals /datasets/imagenet before calling the wrapped function', 'test the inner_decorator to verify it asserts the correct dataset path on a DictConfig', 'review the inner_decorator function and its use of functools.wraps to preserve the original function metadata', 'refactor the inner_decorator to accept a configurable expected path instead of hardcoding /datasets/imagenet', 'summarize the inner_decorator which wraps a function to validate a DictConfig dataset path before execution', 'create a parameterized decorator that appends an argument string to a shared list on each call', 'use the outer_decorator to wrap a function and track calls via the module-level data list', 'test the outer_decorator by applying it to a function and verifying the data list captures arg1', 'review the outer_decorator implementation to understand how it uses functools.wraps to preserve function metadata', 'summarize the outer_decorator as a parameterized decorator factory that logs invocation arguments into a shared list']
```

Usage

```
{'create_inner_decorator': 'create a decorator that asserts conf.dataset.path equals /datasets/imagenet before calling the wrapped function', 'test_inner_decorator': 'test the inner_decorator to verify it asserts the correct dataset path on a DictConfig', 'review_inner_decorator': 'review the inner_decorator function and its use of functools.wraps to preserve the original function metadata', 'refactor_inner_decorator': 'refactor the inner_decorator to accept a configurable expected path instead of hardcoding /datasets/imagenet', 'summarize_inner_decorator': 'summarize the inner_decorator which wraps a function to validate a DictConfig dataset path before execution'}
```

## File: facebookresearch_hydra/tests/test_apps/app_with_cfg_decorated/decorators/outer_decorator.py

Prompts

```
['create a decorator that asserts conf.dataset.path equals /datasets/imagenet before calling the wrapped function', 'test the inner_decorator to verify it asserts the correct dataset path on a DictConfig', 'review the inner_decorator function and its use of functools.wraps to preserve the original function metadata', 'refactor the inner_decorator to accept a configurable expected path instead of hardcoding /datasets/imagenet', 'summarize the inner_decorator which wraps a function to validate a DictConfig dataset path before execution', 'create a parameterized decorator that appends an argument string to a shared list on each call', 'use the outer_decorator to wrap a function and track calls via the module-level data list', 'test the outer_decorator by applying it to a function and verifying the data list captures arg1', 'review the outer_decorator implementation to understand how it uses functools.wraps to preserve function metadata', 'summarize the outer_decorator as a parameterized decorator factory that logs invocation arguments into a shared list']
```

Usage

```
{'create_parameterized_decorator': 'create a parameterized decorator that appends an argument string to a shared list on each call', 'use_outer_decorator': 'use the outer_decorator to wrap a function and track calls via the module-level data list', 'test_outer_decorator': 'test the outer_decorator by applying it to a function and verifying the data list captures arg1', 'review_outer_decorator': 'review the outer_decorator implementation to understand how it uses functools.wraps to preserve function metadata', 'summarize_outer_decorator': 'summarize the outer_decorator as a parameterized decorator factory that logs invocation arguments into a shared list'}
```


# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/_dispatch/python.py

Prompts

```
['enable the Python dispatcher for torch ops to intercept and customize operator dispatch behavior', 'disable the Python dispatcher to bypass Python-level operator dispatch interception', 'suspend functionalization temporarily within a context manager to disable view reapplication', 'check that two nested structures of tensors match in size, dtype, and stride metadata', 'create a handler that cross-references fake tensor execution against real execution using the Functionalize dispatch key']
```

Usage

```
{'enable_python_dispatcher': 'enable the Python dispatcher for torch ops to intercept and customize operator dispatch behavior', 'no_python_dispatcher': 'disable the Python dispatcher to bypass Python-level operator dispatch interception', 'suspend_functionalization': 'suspend functionalization temporarily within a context manager to disable view reapplication', 'check_metadata_matches': 'check that two nested structures of tensors match in size, dtype, and stride metadata', 'make_crossref_functionalize': 'create a handler that cross-references fake tensor execution against real execution using the Functionalize dispatch key'}
```


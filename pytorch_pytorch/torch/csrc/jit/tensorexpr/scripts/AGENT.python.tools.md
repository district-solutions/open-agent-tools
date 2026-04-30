# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/csrc/jit/tensorexpr/scripts/bisect.py

Prompts

```
['test the bisect.py test function with a command and limit value to determine pass, fail, or skip', 'run the bisect CLI tool with --cmd option to binary-search for the failing tensorexpr_fuser opt limit', 'test the bisect binary search logic that narrows last good and first bad opt limit values', 'test the skip handling logic that marks INTERNAL ASSERT FAILED limits and scans forward or backward', 'test the binary search algorithm that converges last_good and first_bad to pinpoint the boundary']
```

Usage

```
{'test_bisect_cmd': 'test the bisect.py test function with a command and limit value to determine pass, fail, or skip', 'run_bisect_cli': 'run the bisect CLI tool with --cmd option to binary-search for the failing tensorexpr_fuser opt limit', 'test_bisect_range': 'test the bisect binary search logic that narrows last good and first bad opt limit values', 'test_skip_handling': 'test the skip handling logic that marks INTERNAL ASSERT FAILED limits and scans forward or backward', 'test_binary_search': 'test the binary search algorithm that converges last_good and first_bad to pinpoint the boundary'}
```


# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/fx/passes/dialect/common/cse_pass.py

Prompts

```
['build a CSE pass to eliminate redundant computations in a PyTorch FX graph module', 'test the CSEPass call method to apply common subexpression elimination on a traced FX graph', 'get the set of banned operations (random and inplace ops) that CSEPass excludes from elimination', 'create a CSEPass instance with custom banned ops to exclude stateful operators from CSE', 'refactor a PyTorch FX graph by applying CSEPass to remove duplicate identical computations']
```

Usage

```
{'build_cse_pass': 'build a CSE pass to eliminate redundant computations in a PyTorch FX graph module', 'test_cse_pass_call': 'test the CSEPass call method to apply common subexpression elimination on a traced FX graph', 'get_cse_banned_ops': 'get the set of banned operations (random and inplace ops) that CSEPass excludes from elimination', 'create_cse_pass_banned': 'create a CSEPass instance with custom banned ops to exclude stateful operators from CSE', 'refactor_fx_graph_cse': 'refactor a PyTorch FX graph by applying CSEPass to remove duplicate identical computations'}
```


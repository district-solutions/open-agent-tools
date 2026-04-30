# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/fx/passes/tests/test_pass_manager.py

Prompts

```
['build a PassManager with a list of callable passes and validate execution order', 'test PassManager construction with a list of lambda passes and validate without errors', 'test this_before_that_pass_constraint raises RuntimeError when constraint is unfulfillable', 'test these_before_those_pass_constraint with inplace_wrapper raises RuntimeError on violation', 'test two independent PassManager instances do not share state between them']
```

Usage

```
{'build_pass_manager': 'build a PassManager with a list of callable passes and validate execution order', 'test_pass_manager_builder': 'test PassManager construction with a list of lambda passes and validate without errors', 'test_this_before_that_pass_constraint': 'test this_before_that_pass_constraint raises RuntimeError when constraint is unfulfillable', 'test_these_before_those_pass_constraint': 'test these_before_those_pass_constraint with inplace_wrapper raises RuntimeError on violation', 'test_pass_manager_isolation': 'test two independent PassManager instances do not share state between them'}
```


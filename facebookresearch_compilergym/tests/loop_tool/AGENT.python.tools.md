# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/loop_tool/actions_test.py

Prompts

```
['test the loop_tool-v0 environment by stepping through a sequence of simple actions and printing observations', 'test the loop_tool-v0 environment by sampling random actions and tracking the best FLOPs observed', 'test the loop_tool-v0 environment to verify induced remainder behavior in the loop tree observation', 'test the loop_tool-v0 environment to verify thread removal via the toggle_thread action', 'test the loop_tool-v0 environment to verify thread addition on nested loops via toggle_thread action']
```

Usage

```
{'test_basic_loop_tool_env': 'test the loop_tool-v0 environment by stepping through a sequence of simple actions and printing observations', 'test_rand_loop_tool_env': 'test the loop_tool-v0 environment by sampling random actions and tracking the best FLOPs observed', 'test_induced_remainder_loop_tool': 'test the loop_tool-v0 environment to verify induced remainder behavior in the loop tree observation', 'test_thread_removal_loop_tool': 'test the loop_tool-v0 environment to verify thread removal via the toggle_thread action', 'test_thread_addition_loop_tool': 'test the loop_tool-v0 environment to verify thread addition on nested loops via toggle_thread action'}
```


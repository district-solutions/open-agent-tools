# Agent Python Tools

- repo: facebookresearch/ctrlbenchmark
- repo_uri: https://github.com/facebookresearch/ctrlbenchmark

## File: facebookresearch_ctrlbenchmark/tests/test_ctrl.py

Prompts

```
["run ctrl.get_stream('s_plus') to generate 6 tasks with increasing dataset sizes", "run ctrl.get_stream('s_minus') to generate 6 tasks with decreasing dataset sizes", "run ctrl.get_stream('s_in') to generate 6 in-distribution tasks for evaluation", "run ctrl.get_stream('s_out') to generate 6 out-of-distribution tasks for evaluation", "test ctrl.get_stream('s_minus', 10) returns identical tasks across two calls with the same seed"]
```

Usage

```
{'run_ctrl_s_plus_stream': "run ctrl.get_stream('s_plus') to generate 6 tasks with increasing dataset sizes", 'run_ctrl_s_minus_stream': "run ctrl.get_stream('s_minus') to generate 6 tasks with decreasing dataset sizes", 'run_ctrl_s_in_stream': "run ctrl.get_stream('s_in') to generate 6 in-distribution tasks for evaluation", 'run_ctrl_s_out_stream': "run ctrl.get_stream('s_out') to generate 6 out-of-distribution tasks for evaluation", 'test_ctrl_stream_determinism': "test ctrl.get_stream('s_minus', 10) returns identical tasks across two calls with the same seed"}
```


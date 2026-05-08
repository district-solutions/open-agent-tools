# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/tests/helpers/utils.py

Prompts

```
['run a Python script as __main__ with patched sys.argv and sys.path for the target file', 'run a Python script in a separate spawn process to avoid OpenGL context clashes', 'simulate physics at 60FPS for a given duration and optionally collect sensor observations', 'test running a Python script in a subprocess and assert it exits with code 0', 'review the simulate function that steps physics at 60FPS and returns sensor observations']
```

Usage

```
{'run_main': 'run a Python script as __main__ with patched sys.argv and sys.path for the target file', 'run_main_subproc': 'run a Python script in a separate spawn process to avoid OpenGL context clashes', 'simulate_step_physics': 'simulate physics at 60FPS for a given duration and optionally collect sensor observations', 'test_run_main_subproc': 'test running a Python script in a subprocess and assert it exits with code 0', 'review_simulate': 'review the simulate function that steps physics at 60FPS and returns sensor observations'}
```


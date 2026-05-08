# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/rl/swerl/eval_backend/eval.py

Prompts

```
['run a SWE-Bench style evaluation on a test instance using the modal backend', 'evaluate a test spec against a predicted patch inside a Modal sandbox container', 'run a general evaluation with custom test scripts and patches in a Modal sandbox', 'create a frozen dataclass representing an evaluation outcome with pass, fail, env_error, or timeout status', 'use the list of git apply and patch commands to retry applying a diff with multiple strategies']
```

Usage

```
{'eval_instance_default': 'run a SWE-Bench style evaluation on a test instance using the modal backend', 'eval_instance_modal': 'evaluate a test spec against a predicted patch inside a Modal sandbox container', 'eval_instance_general_modal': 'run a general evaluation with custom test scripts and patches in a Modal sandbox', 'EvalResult': 'create a frozen dataclass representing an evaluation outcome with pass, fail, env_error, or timeout status', 'GIT_APPLY_CMDS': 'use the list of git apply and patch commands to retry applying a diff with multiple strategies'}
```


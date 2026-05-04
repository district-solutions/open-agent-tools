# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/onedocker/common/util.py

Prompts

```
['run a shell command with a configurable timeout and proper signal handling', 'run a shell command that terminates automatically if it exceeds the specified timeout', 'run a shell command that handles Ctrl+C interrupts and cleans up child processes', 'run a shell command that kills the entire process group on timeout or interruption', 'run a shell command in a new session so all child processes can be terminated together']
```

Usage

```
{'run_cmd': 'run a shell command with a configurable timeout and proper signal handling', 'run_cmd_timeout': 'run a shell command that terminates automatically if it exceeds the specified timeout', 'run_cmd_sigint': 'run a shell command that handles Ctrl+C interrupts and cleans up child processes', 'run_cmd_killpg': 'run a shell command that kills the entire process group on timeout or interruption', 'run_cmd_setsid': 'run a shell command in a new session so all child processes can be terminated together'}
```


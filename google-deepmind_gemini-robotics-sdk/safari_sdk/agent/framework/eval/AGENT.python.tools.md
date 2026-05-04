# Agent Python Tools

- repo: google-deepmind/gemini-robotics-sdk
- repo_uri: https://github.com/google-deepmind/gemini-robotics-sdk

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/eval/agent_eval_lib.py

Prompts

```
['run the agentic evaluation loop that connects to ORCA and executes work units end to end', 'execute a single work unit by starting backends, sending instructions, and collecting operator ratings', 'start the robot backend subprocess and wait for it to become responsive on localhost port 8888', 'start the agent backend subprocess and wait for it to become responsive on localhost port 8887', 'get the post episode success score rating from the operator using checklist or single selection format', 'start a backend subprocess with serialized policy details and stream stdout and stderr to log files', 'read output from a subprocess pipe and write lines to a log file with optional logging', 'terminate a running subprocess with a timeout and force kill if it does not stop', 'serialize policy details to a base64 encoded JSON string for passing to a runner subprocess', 'create a console-based user IO connection that prompts the user with numbered choices and validates input']
```

Usage

```
{'run_eval_loop': 'run the agentic evaluation loop that connects to ORCA and executes work units end to end', 'execute_work_unit': 'execute a single work unit by starting backends, sending instructions, and collecting operator ratings', 'start_robot_backend': 'start the robot backend subprocess and wait for it to become responsive on localhost port 8888', 'start_agent_backend': 'start the agent backend subprocess and wait for it to become responsive on localhost port 8887', 'get_operator_rating': 'get the post episode success score rating from the operator using checklist or single selection format'}
```

## File: google-deepmind_gemini-robotics-sdk/safari_sdk/agent/framework/eval/agent_eval_util.py

Prompts

```
['run the agentic evaluation loop that connects to ORCA and executes work units end to end', 'execute a single work unit by starting backends, sending instructions, and collecting operator ratings', 'start the robot backend subprocess and wait for it to become responsive on localhost port 8888', 'start the agent backend subprocess and wait for it to become responsive on localhost port 8887', 'get the post episode success score rating from the operator using checklist or single selection format', 'start a backend subprocess with serialized policy details and stream stdout and stderr to log files', 'read output from a subprocess pipe and write lines to a log file with optional logging', 'terminate a running subprocess with a timeout and force kill if it does not stop', 'serialize policy details to a base64 encoded JSON string for passing to a runner subprocess', 'create a console-based user IO connection that prompts the user with numbered choices and validates input']
```

Usage

```
{'start_backend_subprocess': 'start a backend subprocess with serialized policy details and stream stdout and stderr to log files', 'stream_output': 'read output from a subprocess pipe and write lines to a log file with optional logging', 'terminate_process': 'terminate a running subprocess with a timeout and force kill if it does not stop', 'serialize_policy_details': 'serialize policy details to a base64 encoded JSON string for passing to a runner subprocess', 'SetUserIoConnectionAsConsole': 'create a console-based user IO connection that prompts the user with numbered choices and validates input'}
```


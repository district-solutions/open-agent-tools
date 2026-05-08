# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/rl/swerl/remote/client.py

Prompts

```
['create a PersistentClient by selecting a random server from a registry directory path', 'run a command in an existing session and return the output with exit code', 'submit a command to run in the background and return a task ID for later polling', 'check the status of a background task and retrieve its result when done', 'poll a background task repeatedly until it completes and return the final result', 'create a TCP server that handles multiple clients and executes commands in persistent sessions', 'run a command in an existing persistent session and return the output', 'create a new persistent session with command args, timeout, and optional start script', 'run an async command as a background task and check its status later', 'stop an existing persistent session and clean up its resources from the session store', 'create an AsyncSession with bash command args and a timeout value', 'send a shell command to the AsyncSession and read its output', 'get the exit code of the last command run in the AsyncSession', 'restart an AsyncSession by stopping the current process and starting a new one']
```

Usage

```
{'create_persistent_client_from_registry': 'create a PersistentClient by selecting a random server from a registry directory path', 'run_command_in_session': 'run a command in an existing session and return the output with exit code', 'submit_background_task': 'submit a command to run in the background and return a task ID for later polling', 'check_task_status': 'check the status of a background task and retrieve its result when done', 'fetch_task_result_until_success': 'poll a background task repeatedly until it completes and return the final result'}
```

## File: facebookresearch_cwm/cwm/rl/swerl/remote/server.py

Prompts

```
['create a PersistentClient by selecting a random server from a registry directory path', 'run a command in an existing session and return the output with exit code', 'submit a command to run in the background and return a task ID for later polling', 'check the status of a background task and retrieve its result when done', 'poll a background task repeatedly until it completes and return the final result', 'create a TCP server that handles multiple clients and executes commands in persistent sessions', 'run a command in an existing persistent session and return the output', 'create a new persistent session with command args, timeout, and optional start script', 'run an async command as a background task and check its status later', 'stop an existing persistent session and clean up its resources from the session store', 'create an AsyncSession with bash command args and a timeout value', 'send a shell command to the AsyncSession and read its output', 'get the exit code of the last command run in the AsyncSession', 'restart an AsyncSession by stopping the current process and starting a new one']
```

Usage

```
{'create_tcp_server': 'create a TCP server that handles multiple clients and executes commands in persistent sessions', 'run_session_command': 'run a command in an existing persistent session and return the output', 'create_session': 'create a new persistent session with command args, timeout, and optional start script', 'run_background_task': 'run an async command as a background task and check its status later', 'stop_session': 'stop an existing persistent session and clean up its resources from the session store'}
```

## File: facebookresearch_cwm/cwm/rl/swerl/remote/session.py

Prompts

```
['create a PersistentClient by selecting a random server from a registry directory path', 'run a command in an existing session and return the output with exit code', 'submit a command to run in the background and return a task ID for later polling', 'check the status of a background task and retrieve its result when done', 'poll a background task repeatedly until it completes and return the final result', 'create a TCP server that handles multiple clients and executes commands in persistent sessions', 'run a command in an existing persistent session and return the output', 'create a new persistent session with command args, timeout, and optional start script', 'run an async command as a background task and check its status later', 'stop an existing persistent session and clean up its resources from the session store', 'create an AsyncSession with bash command args and a timeout value', 'send a shell command to the AsyncSession and read its output', 'get the exit code of the last command run in the AsyncSession', 'restart an AsyncSession by stopping the current process and starting a new one']
```

Usage

```
{'create_async_session': 'create an AsyncSession with bash command args and a timeout value', 'communicate_command': 'send a shell command to the AsyncSession and read its output', 'get_exitcode': 'get the exit code of the last command run in the AsyncSession', 'restart_session': 'restart an AsyncSession by stopping the current process and starting a new one', 'stop_session': 'stop an AsyncSession by terminating its subprocess and cleaning up resources'}
```


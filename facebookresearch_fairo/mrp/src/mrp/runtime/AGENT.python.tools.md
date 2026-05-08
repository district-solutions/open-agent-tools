# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/mrp/src/mrp/runtime/base.py

Prompts

```
['recursively convert psutil named tuples and nested objects into JSON-serializable dictionaries', 'review the BaseLauncher async run method that starts a process given a name and ProcDef', 'review the BaseLauncher down_watcher method that watches for lifecycle DOWN signals and triggers a callback', 'review the BaseLauncher log_psutil method that polls process metrics and publishes them as JSON packets', 'review the BaseRuntime abstract class defining asdict, _build, and _launcher methods for runtime implementations', 'create a CondaEnv by loading channels and dependencies from a YAML file using CondaEnv.load()', 'merge two CondaEnv instances combining their channels and dependencies with CondaEnv.merge()', 'load a CondaEnv definition from an existing named conda environment using CondaEnv.from_named_env()', 'build a Conda runtime using a SharedEnv to manage environment creation, caching, and setup commands', 'launch a process in a conda environment using Launcher which handles envvar detection and PTY management', 'create a Docker runtime instance with an image or dockerfile for containerized process execution', 'run a Docker container with environment variables, volume mounts, and host network mode via the Launcher class', 'build a Docker image from a dockerfile with optional caching and verbose output using the Docker class', 'pipe stdout and stdin between a Docker container and an async message publisher using websocket I/O', 'handle Docker container lifecycle events including start, stop, wait, and cleanup with state tracking', 'create a Host runtime instance with a run command and optional build commands', 'run a Launcher subprocess asynchronously with PTY pipes and environment variables', 'build a project by executing Host build commands via subprocess in bash', 'handle graceful shutdown of a Launcher process with SIGTERM and SIGKILL fallback', 'get the process ID of a running Launcher subprocess']
```

Usage

```
{'walk_asdict_psutil': 'recursively convert psutil named tuples and nested objects into JSON-serializable dictionaries', 'review_baselauncher_run': 'review the BaseLauncher async run method that starts a process given a name and ProcDef', 'review_baselauncher_down_watcher': 'review the BaseLauncher down_watcher method that watches for lifecycle DOWN signals and triggers a callback', 'review_baselauncher_log_psutil': 'review the BaseLauncher log_psutil method that polls process metrics and publishes them as JSON packets', 'review_baseruntime_abstract': 'review the BaseRuntime abstract class defining asdict, _build, and _launcher methods for runtime implementations'}
```

## File: facebookresearch_fairo/mrp/src/mrp/runtime/conda.py

Prompts

```
['recursively convert psutil named tuples and nested objects into JSON-serializable dictionaries', 'review the BaseLauncher async run method that starts a process given a name and ProcDef', 'review the BaseLauncher down_watcher method that watches for lifecycle DOWN signals and triggers a callback', 'review the BaseLauncher log_psutil method that polls process metrics and publishes them as JSON packets', 'review the BaseRuntime abstract class defining asdict, _build, and _launcher methods for runtime implementations', 'create a CondaEnv by loading channels and dependencies from a YAML file using CondaEnv.load()', 'merge two CondaEnv instances combining their channels and dependencies with CondaEnv.merge()', 'load a CondaEnv definition from an existing named conda environment using CondaEnv.from_named_env()', 'build a Conda runtime using a SharedEnv to manage environment creation, caching, and setup commands', 'launch a process in a conda environment using Launcher which handles envvar detection and PTY management', 'create a Docker runtime instance with an image or dockerfile for containerized process execution', 'run a Docker container with environment variables, volume mounts, and host network mode via the Launcher class', 'build a Docker image from a dockerfile with optional caching and verbose output using the Docker class', 'pipe stdout and stdin between a Docker container and an async message publisher using websocket I/O', 'handle Docker container lifecycle events including start, stop, wait, and cleanup with state tracking', 'create a Host runtime instance with a run command and optional build commands', 'run a Launcher subprocess asynchronously with PTY pipes and environment variables', 'build a project by executing Host build commands via subprocess in bash', 'handle graceful shutdown of a Launcher process with SIGTERM and SIGKILL fallback', 'get the process ID of a running Launcher subprocess']
```

Usage

```
{'create_conda_env_from_yaml': 'create a CondaEnv by loading channels and dependencies from a YAML file using CondaEnv.load()', 'merge_conda_environments': 'merge two CondaEnv instances combining their channels and dependencies with CondaEnv.merge()', 'load_conda_env_from_named': 'load a CondaEnv definition from an existing named conda environment using CondaEnv.from_named_env()', 'build_conda_runtime_with_shared_env': 'build a Conda runtime using a SharedEnv to manage environment creation, caching, and setup commands', 'launch_conda_process_with_launcher': 'launch a process in a conda environment using Launcher which handles envvar detection and PTY management'}
```

## File: facebookresearch_fairo/mrp/src/mrp/runtime/docker.py

Prompts

```
['recursively convert psutil named tuples and nested objects into JSON-serializable dictionaries', 'review the BaseLauncher async run method that starts a process given a name and ProcDef', 'review the BaseLauncher down_watcher method that watches for lifecycle DOWN signals and triggers a callback', 'review the BaseLauncher log_psutil method that polls process metrics and publishes them as JSON packets', 'review the BaseRuntime abstract class defining asdict, _build, and _launcher methods for runtime implementations', 'create a CondaEnv by loading channels and dependencies from a YAML file using CondaEnv.load()', 'merge two CondaEnv instances combining their channels and dependencies with CondaEnv.merge()', 'load a CondaEnv definition from an existing named conda environment using CondaEnv.from_named_env()', 'build a Conda runtime using a SharedEnv to manage environment creation, caching, and setup commands', 'launch a process in a conda environment using Launcher which handles envvar detection and PTY management', 'create a Docker runtime instance with an image or dockerfile for containerized process execution', 'run a Docker container with environment variables, volume mounts, and host network mode via the Launcher class', 'build a Docker image from a dockerfile with optional caching and verbose output using the Docker class', 'pipe stdout and stdin between a Docker container and an async message publisher using websocket I/O', 'handle Docker container lifecycle events including start, stop, wait, and cleanup with state tracking', 'create a Host runtime instance with a run command and optional build commands', 'run a Launcher subprocess asynchronously with PTY pipes and environment variables', 'build a project by executing Host build commands via subprocess in bash', 'handle graceful shutdown of a Launcher process with SIGTERM and SIGKILL fallback', 'get the process ID of a running Launcher subprocess']
```

Usage

```
{'create_Docker_runtime': 'create a Docker runtime instance with an image or dockerfile for containerized process execution', 'run_Launcher_container': 'run a Docker container with environment variables, volume mounts, and host network mode via the Launcher class', 'build_Docker_image_from_dockerfile': 'build a Docker image from a dockerfile with optional caching and verbose output using the Docker class', 'pipe_Docker_stdout_stdin': 'pipe stdout and stdin between a Docker container and an async message publisher using websocket I/O', 'handle_Docker_container_lifecycle': 'handle Docker container lifecycle events including start, stop, wait, and cleanup with state tracking'}
```

## File: facebookresearch_fairo/mrp/src/mrp/runtime/host.py

Prompts

```
['recursively convert psutil named tuples and nested objects into JSON-serializable dictionaries', 'review the BaseLauncher async run method that starts a process given a name and ProcDef', 'review the BaseLauncher down_watcher method that watches for lifecycle DOWN signals and triggers a callback', 'review the BaseLauncher log_psutil method that polls process metrics and publishes them as JSON packets', 'review the BaseRuntime abstract class defining asdict, _build, and _launcher methods for runtime implementations', 'create a CondaEnv by loading channels and dependencies from a YAML file using CondaEnv.load()', 'merge two CondaEnv instances combining their channels and dependencies with CondaEnv.merge()', 'load a CondaEnv definition from an existing named conda environment using CondaEnv.from_named_env()', 'build a Conda runtime using a SharedEnv to manage environment creation, caching, and setup commands', 'launch a process in a conda environment using Launcher which handles envvar detection and PTY management', 'create a Docker runtime instance with an image or dockerfile for containerized process execution', 'run a Docker container with environment variables, volume mounts, and host network mode via the Launcher class', 'build a Docker image from a dockerfile with optional caching and verbose output using the Docker class', 'pipe stdout and stdin between a Docker container and an async message publisher using websocket I/O', 'handle Docker container lifecycle events including start, stop, wait, and cleanup with state tracking', 'create a Host runtime instance with a run command and optional build commands', 'run a Launcher subprocess asynchronously with PTY pipes and environment variables', 'build a project by executing Host build commands via subprocess in bash', 'handle graceful shutdown of a Launcher process with SIGTERM and SIGKILL fallback', 'get the process ID of a running Launcher subprocess']
```

Usage

```
{'create_Host_runtime': 'create a Host runtime instance with a run command and optional build commands', 'run_Launcher_process': 'run a Launcher subprocess asynchronously with PTY pipes and environment variables', 'build_Host_commands': 'build a project by executing Host build commands via subprocess in bash', 'handle_Launcher_shutdown': 'handle graceful shutdown of a Launcher process with SIGTERM and SIGKILL fallback', 'get_Launcher_pid': 'get the process ID of a running Launcher subprocess'}
```


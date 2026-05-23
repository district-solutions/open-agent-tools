# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/core/cache.py

Prompts

```
['create a FileCache instance with a caching directory path to store pickled module results', 'get cached results from a FileCache for a StopesModule by iteration value and index', 'save module results to a FileCache as a pickle file with optional config YAML', 'invalidate and remove cached pickle files for a specific StopesModule iteration from FileCache', 'create a NoCache instance that raises MissingCache on get and no-ops on save and invalidate', 'create a Launcher instance to schedule StopesModule jobs on a Slurm cluster with retries', 'schedule a StopesModule using the Launcher to run single or array jobs on the cluster', 'configure a ThrottleConfig to limit parallel job submissions across processes using a shared semaphore', 'wait on a Task instance and retrieve its final_result after the job completes', 'handle a TaskExecutionError when a StopesModule job fails on the Slurm cluster', 'build a StopesModule subclass that implements run and requirements methods for cluster job execution', 'build a Requirements dataclass to specify nodes, GPUs, CPUs, memory, and timeout for a job', 'review the StopesModule.build static method that instantiates modules from a Hydra config with _target_ entry', 'test the StopesModule validate method to check if output paths exist and invalidate cache on missing files', 'refactor the StopesModule array method to return a list of values for parallel array job submission', 'build a bash pipefail pipeline command from multiple shell command parts', 'create a sha256 hex digest hash from a raw string key', 'sort lines in a file by a specific column and optionally deduplicate', 'split large files into smaller shards under a max size threshold', 'use an async IPC semaphore shared across processes for concurrency control']
```

Usage

```
{'create_FileCache': 'create a FileCache instance with a caching directory path to store pickled module results', 'get_cache_FileCache': 'get cached results from a FileCache for a StopesModule by iteration value and index', 'save_cache_FileCache': 'save module results to a FileCache as a pickle file with optional config YAML', 'invalidate_cache_FileCache': 'invalidate and remove cached pickle files for a specific StopesModule iteration from FileCache', 'create_NoCache': 'create a NoCache instance that raises MissingCache on get and no-ops on save and invalidate'}
```

## File: facebookresearch_stopes/stopes/core/launcher.py

Prompts

```
['create a FileCache instance with a caching directory path to store pickled module results', 'get cached results from a FileCache for a StopesModule by iteration value and index', 'save module results to a FileCache as a pickle file with optional config YAML', 'invalidate and remove cached pickle files for a specific StopesModule iteration from FileCache', 'create a NoCache instance that raises MissingCache on get and no-ops on save and invalidate', 'create a Launcher instance to schedule StopesModule jobs on a Slurm cluster with retries', 'schedule a StopesModule using the Launcher to run single or array jobs on the cluster', 'configure a ThrottleConfig to limit parallel job submissions across processes using a shared semaphore', 'wait on a Task instance and retrieve its final_result after the job completes', 'handle a TaskExecutionError when a StopesModule job fails on the Slurm cluster', 'build a StopesModule subclass that implements run and requirements methods for cluster job execution', 'build a Requirements dataclass to specify nodes, GPUs, CPUs, memory, and timeout for a job', 'review the StopesModule.build static method that instantiates modules from a Hydra config with _target_ entry', 'test the StopesModule validate method to check if output paths exist and invalidate cache on missing files', 'refactor the StopesModule array method to return a list of values for parallel array job submission', 'build a bash pipefail pipeline command from multiple shell command parts', 'create a sha256 hex digest hash from a raw string key', 'sort lines in a file by a specific column and optionally deduplicate', 'split large files into smaller shards under a max size threshold', 'use an async IPC semaphore shared across processes for concurrency control']
```

Usage

```
{'create_Launcher_for_slurm': 'create a Launcher instance to schedule StopesModule jobs on a Slurm cluster with retries', 'schedule_StopesModule_with_Launcher': 'schedule a StopesModule using the Launcher to run single or array jobs on the cluster', 'configure_throttle_with_ThrottleConfig': 'configure a ThrottleConfig to limit parallel job submissions across processes using a shared semaphore', 'wait_for_Task_result': 'wait on a Task instance and retrieve its final_result after the job completes', 'handle_TaskExecutionError_on_failure': 'handle a TaskExecutionError when a StopesModule job fails on the Slurm cluster'}
```

## File: facebookresearch_stopes/stopes/core/stopes_module.py

Prompts

```
['create a FileCache instance with a caching directory path to store pickled module results', 'get cached results from a FileCache for a StopesModule by iteration value and index', 'save module results to a FileCache as a pickle file with optional config YAML', 'invalidate and remove cached pickle files for a specific StopesModule iteration from FileCache', 'create a NoCache instance that raises MissingCache on get and no-ops on save and invalidate', 'create a Launcher instance to schedule StopesModule jobs on a Slurm cluster with retries', 'schedule a StopesModule using the Launcher to run single or array jobs on the cluster', 'configure a ThrottleConfig to limit parallel job submissions across processes using a shared semaphore', 'wait on a Task instance and retrieve its final_result after the job completes', 'handle a TaskExecutionError when a StopesModule job fails on the Slurm cluster', 'build a StopesModule subclass that implements run and requirements methods for cluster job execution', 'build a Requirements dataclass to specify nodes, GPUs, CPUs, memory, and timeout for a job', 'review the StopesModule.build static method that instantiates modules from a Hydra config with _target_ entry', 'test the StopesModule validate method to check if output paths exist and invalidate cache on missing files', 'refactor the StopesModule array method to return a list of values for parallel array job submission', 'build a bash pipefail pipeline command from multiple shell command parts', 'create a sha256 hex digest hash from a raw string key', 'sort lines in a file by a specific column and optionally deduplicate', 'split large files into smaller shards under a max size threshold', 'use an async IPC semaphore shared across processes for concurrency control']
```

Usage

```
{'build_StopesModule': 'build a StopesModule subclass that implements run and requirements methods for cluster job execution', 'build_Requirements': 'build a Requirements dataclass to specify nodes, GPUs, CPUs, memory, and timeout for a job', 'review_StopesModule_build': 'review the StopesModule.build static method that instantiates modules from a Hydra config with _target_ entry', 'test_StopesModule_validate': 'test the StopesModule validate method to check if output paths exist and invalidate cache on missing files', 'refactor_StopesModule_array': 'refactor the StopesModule array method to return a list of values for parallel array job submission'}
```

## File: facebookresearch_stopes/stopes/core/utils.py

Prompts

```
['create a FileCache instance with a caching directory path to store pickled module results', 'get cached results from a FileCache for a StopesModule by iteration value and index', 'save module results to a FileCache as a pickle file with optional config YAML', 'invalidate and remove cached pickle files for a specific StopesModule iteration from FileCache', 'create a NoCache instance that raises MissingCache on get and no-ops on save and invalidate', 'create a Launcher instance to schedule StopesModule jobs on a Slurm cluster with retries', 'schedule a StopesModule using the Launcher to run single or array jobs on the cluster', 'configure a ThrottleConfig to limit parallel job submissions across processes using a shared semaphore', 'wait on a Task instance and retrieve its final_result after the job completes', 'handle a TaskExecutionError when a StopesModule job fails on the Slurm cluster', 'build a StopesModule subclass that implements run and requirements methods for cluster job execution', 'build a Requirements dataclass to specify nodes, GPUs, CPUs, memory, and timeout for a job', 'review the StopesModule.build static method that instantiates modules from a Hydra config with _target_ entry', 'test the StopesModule validate method to check if output paths exist and invalidate cache on missing files', 'refactor the StopesModule array method to return a list of values for parallel array job submission', 'build a bash pipefail pipeline command from multiple shell command parts', 'create a sha256 hex digest hash from a raw string key', 'sort lines in a file by a specific column and optionally deduplicate', 'split large files into smaller shards under a max size threshold', 'use an async IPC semaphore shared across processes for concurrency control']
```

Usage

```
{'build_bash_pipeline': 'build a bash pipefail pipeline command from multiple shell command parts', 'create_sha256_hash': 'create a sha256 hex digest hash from a raw string key', 'sort_file_by_column': 'sort lines in a file by a specific column and optionally deduplicate', 'split_large_files': 'split large files into smaller shards under a max size threshold', 'use_async_ipc_semaphore': 'use an async IPC semaphore shared across processes for concurrency control'}
```


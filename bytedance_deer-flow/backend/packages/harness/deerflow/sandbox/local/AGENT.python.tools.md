# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/sandbox/local/list_dir.py

Prompts

```
['list the contents of a directory up to 2 levels deep, excluding ignored patterns', 'recurse into a directory tree listing files and subdirectories up to a specified max depth', 'resolve relative directory paths to absolute paths and return sorted results', 'filter out files and directories matching ignore patterns like .git or __pycache__', 'handle permission errors gracefully when traversing restricted directories', 'create a LocalSandbox instance with an id and optional read-only path mappings for container-to-local path translation', 'build PathMapping objects to map container filesystem paths to local filesystem paths with optional read-only flags', 'run shell commands inside a LocalSandbox with automatic container-to-local path resolution and cross-platform shell detection', 'read a file through a LocalSandbox with container path resolution and reverse-resolving of agent-authored content paths', 'write content to a file through a LocalSandbox with container path resolution, read-only enforcement, and agent write tracking', 'build a LocalSandboxProvider instance that initializes path mappings from config for local sandbox execution', 'setup path mappings for the local sandbox by reading skills directory and custom mounts from config.yaml', 'acquire a singleton LocalSandbox instance with a thread_id for use in a multi-turn conversation', 'get a LocalSandbox instance by its sandbox_id, creating it lazily if it does not exist yet', 'release a LocalSandbox instance, which is a no-op since the provider uses a singleton pattern']
```

Usage

```
{'list_dir_list_files': 'list the contents of a directory up to 2 levels deep, excluding ignored patterns', 'list_dir_recurse': 'recurse into a directory tree listing files and subdirectories up to a specified max depth', 'list_dir_resolve_paths': 'resolve relative directory paths to absolute paths and return sorted results', 'should_ignore_name_filter': 'filter out files and directories matching ignore patterns like .git or __pycache__', 'list_dir_handle_errors': 'handle permission errors gracefully when traversing restricted directories'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/sandbox/local/local_sandbox.py

Prompts

```
['list the contents of a directory up to 2 levels deep, excluding ignored patterns', 'recurse into a directory tree listing files and subdirectories up to a specified max depth', 'resolve relative directory paths to absolute paths and return sorted results', 'filter out files and directories matching ignore patterns like .git or __pycache__', 'handle permission errors gracefully when traversing restricted directories', 'create a LocalSandbox instance with an id and optional read-only path mappings for container-to-local path translation', 'build PathMapping objects to map container filesystem paths to local filesystem paths with optional read-only flags', 'run shell commands inside a LocalSandbox with automatic container-to-local path resolution and cross-platform shell detection', 'read a file through a LocalSandbox with container path resolution and reverse-resolving of agent-authored content paths', 'write content to a file through a LocalSandbox with container path resolution, read-only enforcement, and agent write tracking', 'build a LocalSandboxProvider instance that initializes path mappings from config for local sandbox execution', 'setup path mappings for the local sandbox by reading skills directory and custom mounts from config.yaml', 'acquire a singleton LocalSandbox instance with a thread_id for use in a multi-turn conversation', 'get a LocalSandbox instance by its sandbox_id, creating it lazily if it does not exist yet', 'release a LocalSandbox instance, which is a no-op since the provider uses a singleton pattern']
```

Usage

```
{'create_local_sandbox': 'create a LocalSandbox instance with an id and optional read-only path mappings for container-to-local path translation', 'build_path_mappings': 'build PathMapping objects to map container filesystem paths to local filesystem paths with optional read-only flags', 'run_command_sandbox': 'run shell commands inside a LocalSandbox with automatic container-to-local path resolution and cross-platform shell detection', 'read_file_sandbox': 'read a file through a LocalSandbox with container path resolution and reverse-resolving of agent-authored content paths', 'write_file_sandbox': 'write content to a file through a LocalSandbox with container path resolution, read-only enforcement, and agent write tracking'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/sandbox/local/local_sandbox_provider.py

Prompts

```
['list the contents of a directory up to 2 levels deep, excluding ignored patterns', 'recurse into a directory tree listing files and subdirectories up to a specified max depth', 'resolve relative directory paths to absolute paths and return sorted results', 'filter out files and directories matching ignore patterns like .git or __pycache__', 'handle permission errors gracefully when traversing restricted directories', 'create a LocalSandbox instance with an id and optional read-only path mappings for container-to-local path translation', 'build PathMapping objects to map container filesystem paths to local filesystem paths with optional read-only flags', 'run shell commands inside a LocalSandbox with automatic container-to-local path resolution and cross-platform shell detection', 'read a file through a LocalSandbox with container path resolution and reverse-resolving of agent-authored content paths', 'write content to a file through a LocalSandbox with container path resolution, read-only enforcement, and agent write tracking', 'build a LocalSandboxProvider instance that initializes path mappings from config for local sandbox execution', 'setup path mappings for the local sandbox by reading skills directory and custom mounts from config.yaml', 'acquire a singleton LocalSandbox instance with a thread_id for use in a multi-turn conversation', 'get a LocalSandbox instance by its sandbox_id, creating it lazily if it does not exist yet', 'release a LocalSandbox instance, which is a no-op since the provider uses a singleton pattern']
```

Usage

```
{'build_local_sandbox_provider': 'build a LocalSandboxProvider instance that initializes path mappings from config for local sandbox execution', 'setup_path_mappings': 'setup path mappings for the local sandbox by reading skills directory and custom mounts from config.yaml', 'acquire_sandbox': 'acquire a singleton LocalSandbox instance with a thread_id for use in a multi-turn conversation', 'get_sandbox_by_id': 'get a LocalSandbox instance by its sandbox_id, creating it lazily if it does not exist yet', 'release_sandbox': 'release a LocalSandbox instance, which is a no-op since the provider uses a singleton pattern'}
```


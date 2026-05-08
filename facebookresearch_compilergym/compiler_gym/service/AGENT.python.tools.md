# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/service/client_service_compiler_env.py

Prompts

```
['create a ClientServiceCompilerEnv instance connected to a gRPC compiler service endpoint', 'reset the compiler environment with a specified benchmark and observation space', 'take a single action step in the compiler environment and return observations and rewards', 'fork the current compiler environment to create an independent copy with the same state', 'send key value parameters to the compiler service for runtime configuration', 'create a subclass of CompilationSession to add support for a new compiler in CompilerGym', 'apply an action to a CompilationSession and get the end_of_session and new_action_space tuple', 'get an observation from a CompilationSession for a given observation space', 'fork a CompilationSession to create a copy of the current session state', 'handle a session parameter key-value pair sent by the frontend to a CompilationSession', 'create a ConnectionOpts config to set rpc_max_retries, retry_wait_seconds, and init_max_seconds for a service connection', 'create a CompilerGymServiceConnection to an unmanaged service by passing a host:port URL string like localhost:8080', 'create a CompilerGymServiceConnection to a managed service by passing a Path to a local service binary', 'invoke an RPC method on a CompilerGymServiceConnection stub with a request message and optional timeout and retry parameters', 'restart a CompilerGymServiceConnection to kill and replace a managed service process or reconnect to an unmanaged service', 'create a ServiceCache instance to get an exclusive temporary directory for a managed service', 'create a timestamped unique service directory under a given root path with collision retry logic', 'close a ServiceCache instance to remove its temporary cache directories from the filesystem', 'access a subdirectory within a ServiceCache using the forward slash operator syntax', 'review the ServiceCache class to understand its in-memory and disk fallback directory structure']
```

Usage

```
{'create_client_service_compiler_env': 'create a ClientServiceCompilerEnv instance connected to a gRPC compiler service endpoint', 'reset_environment_with_benchmark': 'reset the compiler environment with a specified benchmark and observation space', 'step_with_action': 'take a single action step in the compiler environment and return observations and rewards', 'fork_environment': 'fork the current compiler environment to create an independent copy with the same state', 'send_params_to_service': 'send key value parameters to the compiler service for runtime configuration'}
```

## File: facebookresearch_compilergym/compiler_gym/service/compilation_session.py

Prompts

```
['create a ClientServiceCompilerEnv instance connected to a gRPC compiler service endpoint', 'reset the compiler environment with a specified benchmark and observation space', 'take a single action step in the compiler environment and return observations and rewards', 'fork the current compiler environment to create an independent copy with the same state', 'send key value parameters to the compiler service for runtime configuration', 'create a subclass of CompilationSession to add support for a new compiler in CompilerGym', 'apply an action to a CompilationSession and get the end_of_session and new_action_space tuple', 'get an observation from a CompilationSession for a given observation space', 'fork a CompilationSession to create a copy of the current session state', 'handle a session parameter key-value pair sent by the frontend to a CompilationSession', 'create a ConnectionOpts config to set rpc_max_retries, retry_wait_seconds, and init_max_seconds for a service connection', 'create a CompilerGymServiceConnection to an unmanaged service by passing a host:port URL string like localhost:8080', 'create a CompilerGymServiceConnection to a managed service by passing a Path to a local service binary', 'invoke an RPC method on a CompilerGymServiceConnection stub with a request message and optional timeout and retry parameters', 'restart a CompilerGymServiceConnection to kill and replace a managed service process or reconnect to an unmanaged service', 'create a ServiceCache instance to get an exclusive temporary directory for a managed service', 'create a timestamped unique service directory under a given root path with collision retry logic', 'close a ServiceCache instance to remove its temporary cache directories from the filesystem', 'access a subdirectory within a ServiceCache using the forward slash operator syntax', 'review the ServiceCache class to understand its in-memory and disk fallback directory structure']
```

Usage

```
{'create_compilation_session_subclass': 'create a subclass of CompilationSession to add support for a new compiler in CompilerGym', 'apply_action_to_session': 'apply an action to a CompilationSession and get the end_of_session and new_action_space tuple', 'get_observation_from_session': 'get an observation from a CompilationSession for a given observation space', 'fork_compilation_session': 'fork a CompilationSession to create a copy of the current session state', 'handle_session_parameter': 'handle a session parameter key-value pair sent by the frontend to a CompilationSession'}
```

## File: facebookresearch_compilergym/compiler_gym/service/connection.py

Prompts

```
['create a ClientServiceCompilerEnv instance connected to a gRPC compiler service endpoint', 'reset the compiler environment with a specified benchmark and observation space', 'take a single action step in the compiler environment and return observations and rewards', 'fork the current compiler environment to create an independent copy with the same state', 'send key value parameters to the compiler service for runtime configuration', 'create a subclass of CompilationSession to add support for a new compiler in CompilerGym', 'apply an action to a CompilationSession and get the end_of_session and new_action_space tuple', 'get an observation from a CompilationSession for a given observation space', 'fork a CompilationSession to create a copy of the current session state', 'handle a session parameter key-value pair sent by the frontend to a CompilationSession', 'create a ConnectionOpts config to set rpc_max_retries, retry_wait_seconds, and init_max_seconds for a service connection', 'create a CompilerGymServiceConnection to an unmanaged service by passing a host:port URL string like localhost:8080', 'create a CompilerGymServiceConnection to a managed service by passing a Path to a local service binary', 'invoke an RPC method on a CompilerGymServiceConnection stub with a request message and optional timeout and retry parameters', 'restart a CompilerGymServiceConnection to kill and replace a managed service process or reconnect to an unmanaged service', 'create a ServiceCache instance to get an exclusive temporary directory for a managed service', 'create a timestamped unique service directory under a given root path with collision retry logic', 'close a ServiceCache instance to remove its temporary cache directories from the filesystem', 'access a subdirectory within a ServiceCache using the forward slash operator syntax', 'review the ServiceCache class to understand its in-memory and disk fallback directory structure']
```

Usage

```
{'create_connection_opts': 'create a ConnectionOpts config to set rpc_max_retries, retry_wait_seconds, and init_max_seconds for a service connection', 'connect_to_unmanaged_service': 'create a CompilerGymServiceConnection to an unmanaged service by passing a host:port URL string like localhost:8080', 'connect_to_managed_service': 'create a CompilerGymServiceConnection to a managed service by passing a Path to a local service binary', 'invoke_rpc_call': 'invoke an RPC method on a CompilerGymServiceConnection stub with a request message and optional timeout and retry parameters', 'restart_connection': 'restart a CompilerGymServiceConnection to kill and replace a managed service process or reconnect to an unmanaged service'}
```

## File: facebookresearch_compilergym/compiler_gym/service/service_cache.py

Prompts

```
['create a ClientServiceCompilerEnv instance connected to a gRPC compiler service endpoint', 'reset the compiler environment with a specified benchmark and observation space', 'take a single action step in the compiler environment and return observations and rewards', 'fork the current compiler environment to create an independent copy with the same state', 'send key value parameters to the compiler service for runtime configuration', 'create a subclass of CompilationSession to add support for a new compiler in CompilerGym', 'apply an action to a CompilationSession and get the end_of_session and new_action_space tuple', 'get an observation from a CompilationSession for a given observation space', 'fork a CompilationSession to create a copy of the current session state', 'handle a session parameter key-value pair sent by the frontend to a CompilationSession', 'create a ConnectionOpts config to set rpc_max_retries, retry_wait_seconds, and init_max_seconds for a service connection', 'create a CompilerGymServiceConnection to an unmanaged service by passing a host:port URL string like localhost:8080', 'create a CompilerGymServiceConnection to a managed service by passing a Path to a local service binary', 'invoke an RPC method on a CompilerGymServiceConnection stub with a request message and optional timeout and retry parameters', 'restart a CompilerGymServiceConnection to kill and replace a managed service process or reconnect to an unmanaged service', 'create a ServiceCache instance to get an exclusive temporary directory for a managed service', 'create a timestamped unique service directory under a given root path with collision retry logic', 'close a ServiceCache instance to remove its temporary cache directories from the filesystem', 'access a subdirectory within a ServiceCache using the forward slash operator syntax', 'review the ServiceCache class to understand its in-memory and disk fallback directory structure']
```

Usage

```
{'create_service_cache': 'create a ServiceCache instance to get an exclusive temporary directory for a managed service', 'create_unique_service_dir': 'create a timestamped unique service directory under a given root path with collision retry logic', 'close_service_cache': 'close a ServiceCache instance to remove its temporary cache directories from the filesystem', 'access_cache_subpath': 'access a subdirectory within a ServiceCache using the forward slash operator syntax', 'review_service_cache_class': 'review the ServiceCache class to understand its in-memory and disk fallback directory structure'}
```


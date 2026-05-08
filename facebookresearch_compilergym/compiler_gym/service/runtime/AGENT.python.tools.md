# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/service/runtime/benchmark_cache.py

Prompts

```
['create a BenchmarkCache instance with a custom max size in bytes and optional random number generator', 'add a Benchmark message to the cache by URI with automatic eviction when size exceeds the maximum', 'get a cached Benchmark message by its URI string, raising KeyError if not found', 'check whether a given URI exists in the BenchmarkCache using the in operator', 'evict random benchmarks from the cache to reduce size below a target byte threshold', 'create a CompilerGymService gRPC servicer instance with a working directory and compilation session type', 'start a new compilation session with a benchmark URI and requested action and observation spaces', 'fork an existing compilation session to create a new independent session with a new session ID', 'apply a list of actions to a compilation session and retrieve observations for the requested observation spaces', 'send key-value parameters to a session to configure benchmark cache size or retrieve cache statistics', 'create and run a gRPC CompilerGym service for a custom CompilationSession subclass', 'run a CompilerGym service listening on a specified port with configurable worker threads', 'handle SIGTERM signals to gracefully shut down the CompilerGym gRPC service', 'configure a CompilerGym service with a custom working directory and log output', 'write the service port and PID to port.txt and pid.txt files atomically']
```

Usage

```
{'create_benchmark_cache': 'create a BenchmarkCache instance with a custom max size in bytes and optional random number generator', 'add_benchmark_to_cache': 'add a Benchmark message to the cache by URI with automatic eviction when size exceeds the maximum', 'get_benchmark_from_cache': 'get a cached Benchmark message by its URI string, raising KeyError if not found', 'check_benchmark_in_cache': 'check whether a given URI exists in the BenchmarkCache using the in operator', 'evict_benchmarks_to_capacity': 'evict random benchmarks from the cache to reduce size below a target byte threshold'}
```

## File: facebookresearch_compilergym/compiler_gym/service/runtime/compiler_gym_service.py

Prompts

```
['create a BenchmarkCache instance with a custom max size in bytes and optional random number generator', 'add a Benchmark message to the cache by URI with automatic eviction when size exceeds the maximum', 'get a cached Benchmark message by its URI string, raising KeyError if not found', 'check whether a given URI exists in the BenchmarkCache using the in operator', 'evict random benchmarks from the cache to reduce size below a target byte threshold', 'create a CompilerGymService gRPC servicer instance with a working directory and compilation session type', 'start a new compilation session with a benchmark URI and requested action and observation spaces', 'fork an existing compilation session to create a new independent session with a new session ID', 'apply a list of actions to a compilation session and retrieve observations for the requested observation spaces', 'send key-value parameters to a session to configure benchmark cache size or retrieve cache statistics', 'create and run a gRPC CompilerGym service for a custom CompilationSession subclass', 'run a CompilerGym service listening on a specified port with configurable worker threads', 'handle SIGTERM signals to gracefully shut down the CompilerGym gRPC service', 'configure a CompilerGym service with a custom working directory and log output', 'write the service port and PID to port.txt and pid.txt files atomically']
```

Usage

```
{'create_grpc_service': 'create a CompilerGymService gRPC servicer instance with a working directory and compilation session type', 'start_compilation_session': 'start a new compilation session with a benchmark URI and requested action and observation spaces', 'fork_compilation_session': 'fork an existing compilation session to create a new independent session with a new session ID', 'step_compilation_session': 'apply a list of actions to a compilation session and retrieve observations for the requested observation spaces', 'send_session_parameter': 'send key-value parameters to a session to configure benchmark cache size or retrieve cache statistics'}
```

## File: facebookresearch_compilergym/compiler_gym/service/runtime/create_and_run_compiler_gym_service.py

Prompts

```
['create a BenchmarkCache instance with a custom max size in bytes and optional random number generator', 'add a Benchmark message to the cache by URI with automatic eviction when size exceeds the maximum', 'get a cached Benchmark message by its URI string, raising KeyError if not found', 'check whether a given URI exists in the BenchmarkCache using the in operator', 'evict random benchmarks from the cache to reduce size below a target byte threshold', 'create a CompilerGymService gRPC servicer instance with a working directory and compilation session type', 'start a new compilation session with a benchmark URI and requested action and observation spaces', 'fork an existing compilation session to create a new independent session with a new session ID', 'apply a list of actions to a compilation session and retrieve observations for the requested observation spaces', 'send key-value parameters to a session to configure benchmark cache size or retrieve cache statistics', 'create and run a gRPC CompilerGym service for a custom CompilationSession subclass', 'run a CompilerGym service listening on a specified port with configurable worker threads', 'handle SIGTERM signals to gracefully shut down the CompilerGym gRPC service', 'configure a CompilerGym service with a custom working directory and log output', 'write the service port and PID to port.txt and pid.txt files atomically']
```

Usage

```
{'create_compiler_gym_rpc_service': 'create and run a gRPC CompilerGym service for a custom CompilationSession subclass', 'run_compiler_gym_service_on_port': 'run a CompilerGym service listening on a specified port with configurable worker threads', 'handle_service_shutdown_signal': 'handle SIGTERM signals to gracefully shut down the CompilerGym gRPC service', 'configure_service_working_directory': 'configure a CompilerGym service with a custom working directory and log output', 'write_service_port_and_pid': 'write the service port and PID to port.txt and pid.txt files atomically'}
```


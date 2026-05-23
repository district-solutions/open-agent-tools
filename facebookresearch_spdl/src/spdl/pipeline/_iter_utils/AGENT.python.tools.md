# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/src/spdl/pipeline/_iter_utils/_cache_iterator.py

Prompts

```
['build a python module to wrap a data loader with cache_iterator for benchmarking data loading performance', 'create a cached data loader using cache_iterator to estimate maximum performance gain from optimizing data loading', 'test the cache_iterator function with stop_after parameter to limit total iterations including cached values', 'refactor the cache_iterator validation logic to support additional parameter constraints for return_caches_after and stop_after', 'review the cache_iterator delete_src parameter to understand how resources are released when returning cached values', 'build a worker that runs initializers then iterates an iterable sending results over a queue', 'review the _Cmd IntEnum that defines ABORT START_ITERATION and STOP_ITERATION commands for workers', 'review the _Status IntEnum that defines worker lifecycle states like INITIALIZATION_SUCCEEDED and ITERATOR_SUCCESS', 'test the _wait_for_init function that waits for a worker to report initialization success or failure', 'test the _iterate_results generator that yields items from a worker queue until iteration finishes', 'run an iterable function in a Python 3.14 subinterpreter with configurable buffer size and timeout', 'create a reusable subinterpreter iterable that supports multiple iterations without recreating the subinterpreter', 'build a subinterpreter pipeline with initializer functions executed before iteration starts', 'test the subinterpreter iteration with a custom inactivity timeout to terminate unresponsive workers', 'review the _SubinterpreterIterable class that wraps subinterpreter iteration with automatic termination on exceptions', 'run an iterable function in a subprocess with configurable buffer size and timeout', 'review the SubprocessIterable class that manages iteration over results from a worker subprocess', 'test the iterate_in_subprocess function to verify it correctly runs an iterable in a separate process', 'refactor the ipc dataclass to support additional IPC channels for command and data queues', 'summarize the join helper function that gracefully terminates a subprocess with escalating signals']
```

Usage

```
{'build_cache_iterator_benchmark': 'build a python module to wrap a data loader with cache_iterator for benchmarking data loading performance', 'create_cached_data_loader': 'create a cached data loader using cache_iterator to estimate maximum performance gain from optimizing data loading', 'test_cache_iterator_stop_after': 'test the cache_iterator function with stop_after parameter to limit total iterations including cached values', 'refactor_cache_iterator_validation': 'refactor the cache_iterator validation logic to support additional parameter constraints for return_caches_after and stop_after', 'review_cache_iterator_memory_management': 'review the cache_iterator delete_src parameter to understand how resources are released when returning cached values'}
```

## File: facebookresearch_spdl/src/spdl/pipeline/_iter_utils/_common.py

Prompts

```
['build a python module to wrap a data loader with cache_iterator for benchmarking data loading performance', 'create a cached data loader using cache_iterator to estimate maximum performance gain from optimizing data loading', 'test the cache_iterator function with stop_after parameter to limit total iterations including cached values', 'refactor the cache_iterator validation logic to support additional parameter constraints for return_caches_after and stop_after', 'review the cache_iterator delete_src parameter to understand how resources are released when returning cached values', 'build a worker that runs initializers then iterates an iterable sending results over a queue', 'review the _Cmd IntEnum that defines ABORT START_ITERATION and STOP_ITERATION commands for workers', 'review the _Status IntEnum that defines worker lifecycle states like INITIALIZATION_SUCCEEDED and ITERATOR_SUCCESS', 'test the _wait_for_init function that waits for a worker to report initialization success or failure', 'test the _iterate_results generator that yields items from a worker queue until iteration finishes', 'run an iterable function in a Python 3.14 subinterpreter with configurable buffer size and timeout', 'create a reusable subinterpreter iterable that supports multiple iterations without recreating the subinterpreter', 'build a subinterpreter pipeline with initializer functions executed before iteration starts', 'test the subinterpreter iteration with a custom inactivity timeout to terminate unresponsive workers', 'review the _SubinterpreterIterable class that wraps subinterpreter iteration with automatic termination on exceptions', 'run an iterable function in a subprocess with configurable buffer size and timeout', 'review the SubprocessIterable class that manages iteration over results from a worker subprocess', 'test the iterate_in_subprocess function to verify it correctly runs an iterable in a separate process', 'refactor the ipc dataclass to support additional IPC channels for command and data queues', 'summarize the join helper function that gracefully terminates a subprocess with escalating signals']
```

Usage

```
{'build_execute_iterable': 'build a worker that runs initializers then iterates an iterable sending results over a queue', 'review_Cmd_enum': 'review the _Cmd IntEnum that defines ABORT START_ITERATION and STOP_ITERATION commands for workers', 'review_Status_enum': 'review the _Status IntEnum that defines worker lifecycle states like INITIALIZATION_SUCCEEDED and ITERATOR_SUCCESS', 'test_wait_for_init': 'test the _wait_for_init function that waits for a worker to report initialization success or failure', 'test_iterate_results': 'test the _iterate_results generator that yields items from a worker queue until iteration finishes'}
```

## File: facebookresearch_spdl/src/spdl/pipeline/_iter_utils/_subinterpreter.py

Prompts

```
['build a python module to wrap a data loader with cache_iterator for benchmarking data loading performance', 'create a cached data loader using cache_iterator to estimate maximum performance gain from optimizing data loading', 'test the cache_iterator function with stop_after parameter to limit total iterations including cached values', 'refactor the cache_iterator validation logic to support additional parameter constraints for return_caches_after and stop_after', 'review the cache_iterator delete_src parameter to understand how resources are released when returning cached values', 'build a worker that runs initializers then iterates an iterable sending results over a queue', 'review the _Cmd IntEnum that defines ABORT START_ITERATION and STOP_ITERATION commands for workers', 'review the _Status IntEnum that defines worker lifecycle states like INITIALIZATION_SUCCEEDED and ITERATOR_SUCCESS', 'test the _wait_for_init function that waits for a worker to report initialization success or failure', 'test the _iterate_results generator that yields items from a worker queue until iteration finishes', 'run an iterable function in a Python 3.14 subinterpreter with configurable buffer size and timeout', 'create a reusable subinterpreter iterable that supports multiple iterations without recreating the subinterpreter', 'build a subinterpreter pipeline with initializer functions executed before iteration starts', 'test the subinterpreter iteration with a custom inactivity timeout to terminate unresponsive workers', 'review the _SubinterpreterIterable class that wraps subinterpreter iteration with automatic termination on exceptions', 'run an iterable function in a subprocess with configurable buffer size and timeout', 'review the SubprocessIterable class that manages iteration over results from a worker subprocess', 'test the iterate_in_subprocess function to verify it correctly runs an iterable in a separate process', 'refactor the ipc dataclass to support additional IPC channels for command and data queues', 'summarize the join helper function that gracefully terminates a subprocess with escalating signals']
```

Usage

```
{'run_iterate_in_subinterpreter': 'run an iterable function in a Python 3.14 subinterpreter with configurable buffer size and timeout', 'create_subinterpreter_iterable': 'create a reusable subinterpreter iterable that supports multiple iterations without recreating the subinterpreter', 'build_pipeline_with_initializer': 'build a subinterpreter pipeline with initializer functions executed before iteration starts', 'test_subinterpreter_timeout': 'test the subinterpreter iteration with a custom inactivity timeout to terminate unresponsive workers', 'review_SubinterpreterIterable_class': 'review the _SubinterpreterIterable class that wraps subinterpreter iteration with automatic termination on exceptions'}
```

## File: facebookresearch_spdl/src/spdl/pipeline/_iter_utils/_subprocess.py

Prompts

```
['build a python module to wrap a data loader with cache_iterator for benchmarking data loading performance', 'create a cached data loader using cache_iterator to estimate maximum performance gain from optimizing data loading', 'test the cache_iterator function with stop_after parameter to limit total iterations including cached values', 'refactor the cache_iterator validation logic to support additional parameter constraints for return_caches_after and stop_after', 'review the cache_iterator delete_src parameter to understand how resources are released when returning cached values', 'build a worker that runs initializers then iterates an iterable sending results over a queue', 'review the _Cmd IntEnum that defines ABORT START_ITERATION and STOP_ITERATION commands for workers', 'review the _Status IntEnum that defines worker lifecycle states like INITIALIZATION_SUCCEEDED and ITERATOR_SUCCESS', 'test the _wait_for_init function that waits for a worker to report initialization success or failure', 'test the _iterate_results generator that yields items from a worker queue until iteration finishes', 'run an iterable function in a Python 3.14 subinterpreter with configurable buffer size and timeout', 'create a reusable subinterpreter iterable that supports multiple iterations without recreating the subinterpreter', 'build a subinterpreter pipeline with initializer functions executed before iteration starts', 'test the subinterpreter iteration with a custom inactivity timeout to terminate unresponsive workers', 'review the _SubinterpreterIterable class that wraps subinterpreter iteration with automatic termination on exceptions', 'run an iterable function in a subprocess with configurable buffer size and timeout', 'review the SubprocessIterable class that manages iteration over results from a worker subprocess', 'test the iterate_in_subprocess function to verify it correctly runs an iterable in a separate process', 'refactor the ipc dataclass to support additional IPC channels for command and data queues', 'summarize the join helper function that gracefully terminates a subprocess with escalating signals']
```

Usage

```
{'iterate_in_subprocess': 'run an iterable function in a subprocess with configurable buffer size and timeout', 'review_SubprocessIterable': 'review the SubprocessIterable class that manages iteration over results from a worker subprocess', 'test_iterate_in_subprocess': 'test the iterate_in_subprocess function to verify it correctly runs an iterable in a separate process', 'refactor_ipc_dataclass': 'refactor the ipc dataclass to support additional IPC channels for command and data queues', 'summarize_join_helper': 'summarize the join helper function that gracefully terminates a subprocess with escalating signals'}
```


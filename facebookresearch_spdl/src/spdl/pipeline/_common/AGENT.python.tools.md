# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/src/spdl/pipeline/_common/_convert.py

Prompts

```
['convert a synchronous function to an async function using convert_to_async with an executor', 'convert a sync generator function to an async generator using convert_to_async with an executor', 'check if an executor is or wraps a ProcessPoolExecutor using _is_process_pool', 'run a function in a subprocess and enrich exceptions with source location via _func_in_subprocess', 'convert a sync generator to a batch async generator using _to_batch_async_gen for subprocess execution', 'create an asyncio task with automatic exception logging and cancellation warnings attached as a done callback', 'get a boolean value from an environment variable with support for multiple truthy and falsy string formats', 'set the compact logging mode to reduce task exception log verbosity to a single line format', 'suppress repeated exception logs from the same source location after reaching a configurable threshold', 'log task exceptions with source file location, line number, and function name for better debugging context', 'locate the source file path and line number of a given function or callable object', 'locate the source of a functools.partial instance and extract its partial arguments and keyword arguments', 'locate the source of a built-in function like len or print and return its qualified name', 'locate the source file and line number of a callable class instance by inspecting its class', 'get the fully qualified name of an object including its module and qualified name']
```

Usage

```
{'convert_sync_function_to_async': 'convert a synchronous function to an async function using convert_to_async with an executor', 'convert_sync_generator_to_async_gen': 'convert a sync generator function to an async generator using convert_to_async with an executor', 'check_executor_is_process_pool': 'check if an executor is or wraps a ProcessPoolExecutor using _is_process_pool', 'run_function_in_subprocess_with_error_context': 'run a function in a subprocess and enrich exceptions with source location via _func_in_subprocess', 'convert_generator_to_batch_async_gen': 'convert a sync generator to a batch async generator using _to_batch_async_gen for subprocess execution'}
```

## File: facebookresearch_spdl/src/spdl/pipeline/_common/_misc.py

Prompts

```
['convert a synchronous function to an async function using convert_to_async with an executor', 'convert a sync generator function to an async generator using convert_to_async with an executor', 'check if an executor is or wraps a ProcessPoolExecutor using _is_process_pool', 'run a function in a subprocess and enrich exceptions with source location via _func_in_subprocess', 'convert a sync generator to a batch async generator using _to_batch_async_gen for subprocess execution', 'create an asyncio task with automatic exception logging and cancellation warnings attached as a done callback', 'get a boolean value from an environment variable with support for multiple truthy and falsy string formats', 'set the compact logging mode to reduce task exception log verbosity to a single line format', 'suppress repeated exception logs from the same source location after reaching a configurable threshold', 'log task exceptions with source file location, line number, and function name for better debugging context', 'locate the source file path and line number of a given function or callable object', 'locate the source of a functools.partial instance and extract its partial arguments and keyword arguments', 'locate the source of a built-in function like len or print and return its qualified name', 'locate the source file and line number of a callable class instance by inspecting its class', 'get the fully qualified name of an object including its module and qualified name']
```

Usage

```
{'create_task_with_logging': 'create an asyncio task with automatic exception logging and cancellation warnings attached as a done callback', 'get_env_bool': 'get a boolean value from an environment variable with support for multiple truthy and falsy string formats', 'set_compact_log': 'set the compact logging mode to reduce task exception log verbosity to a single line format', 'suppress_repeated_logs': 'suppress repeated exception logs from the same source location after reaching a configurable threshold', 'log_task_exceptions': 'log task exceptions with source file location, line number, and function name for better debugging context'}
```

## File: facebookresearch_spdl/src/spdl/pipeline/_common/_source_locator.py

Prompts

```
['convert a synchronous function to an async function using convert_to_async with an executor', 'convert a sync generator function to an async generator using convert_to_async with an executor', 'check if an executor is or wraps a ProcessPoolExecutor using _is_process_pool', 'run a function in a subprocess and enrich exceptions with source location via _func_in_subprocess', 'convert a sync generator to a batch async generator using _to_batch_async_gen for subprocess execution', 'create an asyncio task with automatic exception logging and cancellation warnings attached as a done callback', 'get a boolean value from an environment variable with support for multiple truthy and falsy string formats', 'set the compact logging mode to reduce task exception log verbosity to a single line format', 'suppress repeated exception logs from the same source location after reaching a configurable threshold', 'log task exceptions with source file location, line number, and function name for better debugging context', 'locate the source file path and line number of a given function or callable object', 'locate the source of a functools.partial instance and extract its partial arguments and keyword arguments', 'locate the source of a built-in function like len or print and return its qualified name', 'locate the source file and line number of a callable class instance by inspecting its class', 'get the fully qualified name of an object including its module and qualified name']
```

Usage

```
{'locate_source_function': 'locate the source file path and line number of a given function or callable object', 'locate_source_partial': 'locate the source of a functools.partial instance and extract its partial arguments and keyword arguments', 'locate_source_builtin': 'locate the source of a built-in function like len or print and return its qualified name', 'locate_source_callable_class': 'locate the source file and line number of a callable class instance by inspecting its class', 'get_qualified_name_object': 'get the fully qualified name of an object including its module and qualified name'}
```


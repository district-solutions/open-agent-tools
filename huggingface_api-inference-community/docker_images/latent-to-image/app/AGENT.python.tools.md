# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/latent-to-image/app/healthchecks.py

Prompts

```
['run the starlette healthcheck metrics server that exposes app status and connection metrics', 'compute and update global metrics by counting connections and checking app status with timeout', 'count the current established TCP connections to a given app port and return prometheus metrics', 'check if the main ASGI app is ok, busy, or error by sending a request with a 0.5 second timeout', 'find the gunicorn process listening on a given port by scanning network connections with psutil', 'run the async live check loop that monitors request activity and terminates the worker on idle timeout', 'use the request_witnesses context manager to track request start and end timestamps for idle monitoring', 'configure the idle timeout duration by setting the IDLE_TIMEOUT environment variable before importing', 'enable automatic worker unloading on idle by setting the UNLOAD_IDLE environment variable to true', 'review the live_check_loop function to understand how it checks LAST_START and LAST_END timestamps for activity', 'run the starlette app that serves the latent-to-image pipeline via HTTP routes', 'get the cached pipeline instance for the configured TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dictionary to map task names to their pipeline classes', 'setup gzip and optional CORS middleware for the starlette application', 'reset logging to debug level with timestamp and message format', 'create a timing decorator that logs function execution time in seconds', 'use the timing decorator on a slow function to measure its execution duration', 'wrap any function with the timing decorator to log how long it takes to execute', 'review the timing decorator that logs function name and execution time via debug logging', 'refactor the timing decorator to support custom metrics collection beyond basic timing', 'test the str_to_bool function with strings like true, yes, and 1', 'refactor str_to_bool to return a boolean instead of a regex match object', 'review the str_to_bool function for edge cases and input validation', 'summarize the str_to_bool function that matches true, yes, or 1 strings', 'create a wrapper function around str_to_bool that handles None and empty input']
```

Usage

```
{'run_healthcheck_metrics_server': 'run the starlette healthcheck metrics server that exposes app status and connection metrics', 'compute_app_metrics': 'compute and update global metrics by counting connections and checking app status with timeout', 'count_established_connections': 'count the current established TCP connections to a given app port and return prometheus metrics', 'check_app_status_with_timeout': 'check if the main ASGI app is ok, busy, or error by sending a request with a 0.5 second timeout', 'find_gunicorn_process_by_port': 'find the gunicorn process listening on a given port by scanning network connections with psutil'}
```

## File: huggingface_api-inference-community/docker_images/latent-to-image/app/idle.py

Prompts

```
['run the starlette healthcheck metrics server that exposes app status and connection metrics', 'compute and update global metrics by counting connections and checking app status with timeout', 'count the current established TCP connections to a given app port and return prometheus metrics', 'check if the main ASGI app is ok, busy, or error by sending a request with a 0.5 second timeout', 'find the gunicorn process listening on a given port by scanning network connections with psutil', 'run the async live check loop that monitors request activity and terminates the worker on idle timeout', 'use the request_witnesses context manager to track request start and end timestamps for idle monitoring', 'configure the idle timeout duration by setting the IDLE_TIMEOUT environment variable before importing', 'enable automatic worker unloading on idle by setting the UNLOAD_IDLE environment variable to true', 'review the live_check_loop function to understand how it checks LAST_START and LAST_END timestamps for activity', 'run the starlette app that serves the latent-to-image pipeline via HTTP routes', 'get the cached pipeline instance for the configured TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dictionary to map task names to their pipeline classes', 'setup gzip and optional CORS middleware for the starlette application', 'reset logging to debug level with timestamp and message format', 'create a timing decorator that logs function execution time in seconds', 'use the timing decorator on a slow function to measure its execution duration', 'wrap any function with the timing decorator to log how long it takes to execute', 'review the timing decorator that logs function name and execution time via debug logging', 'refactor the timing decorator to support custom metrics collection beyond basic timing', 'test the str_to_bool function with strings like true, yes, and 1', 'refactor str_to_bool to return a boolean instead of a regex match object', 'review the str_to_bool function for edge cases and input validation', 'summarize the str_to_bool function that matches true, yes, or 1 strings', 'create a wrapper function around str_to_bool that handles None and empty input']
```

Usage

```
{'run_live_check_loop': 'run the async live check loop that monitors request activity and terminates the worker on idle timeout', 'use_request_witnesses_context_manager': 'use the request_witnesses context manager to track request start and end timestamps for idle monitoring', 'configure_idle_timeout': 'configure the idle timeout duration by setting the IDLE_TIMEOUT environment variable before importing', 'enable_unload_idle': 'enable automatic worker unloading on idle by setting the UNLOAD_IDLE environment variable to true', 'review_live_check_loop': 'review the live_check_loop function to understand how it checks LAST_START and LAST_END timestamps for activity'}
```

## File: huggingface_api-inference-community/docker_images/latent-to-image/app/main.py

Prompts

```
['run the starlette healthcheck metrics server that exposes app status and connection metrics', 'compute and update global metrics by counting connections and checking app status with timeout', 'count the current established TCP connections to a given app port and return prometheus metrics', 'check if the main ASGI app is ok, busy, or error by sending a request with a 0.5 second timeout', 'find the gunicorn process listening on a given port by scanning network connections with psutil', 'run the async live check loop that monitors request activity and terminates the worker on idle timeout', 'use the request_witnesses context manager to track request start and end timestamps for idle monitoring', 'configure the idle timeout duration by setting the IDLE_TIMEOUT environment variable before importing', 'enable automatic worker unloading on idle by setting the UNLOAD_IDLE environment variable to true', 'review the live_check_loop function to understand how it checks LAST_START and LAST_END timestamps for activity', 'run the starlette app that serves the latent-to-image pipeline via HTTP routes', 'get the cached pipeline instance for the configured TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dictionary to map task names to their pipeline classes', 'setup gzip and optional CORS middleware for the starlette application', 'reset logging to debug level with timestamp and message format', 'create a timing decorator that logs function execution time in seconds', 'use the timing decorator on a slow function to measure its execution duration', 'wrap any function with the timing decorator to log how long it takes to execute', 'review the timing decorator that logs function name and execution time via debug logging', 'refactor the timing decorator to support custom metrics collection beyond basic timing', 'test the str_to_bool function with strings like true, yes, and 1', 'refactor str_to_bool to return a boolean instead of a regex match object', 'review the str_to_bool function for edge cases and input validation', 'summarize the str_to_bool function that matches true, yes, or 1 strings', 'create a wrapper function around str_to_bool that handles None and empty input']
```

Usage

```
{'run_starlette_app': 'run the starlette app that serves the latent-to-image pipeline via HTTP routes', 'get_pipeline': 'get the cached pipeline instance for the configured TASK and MODEL_ID environment variables', 'configure_allowed_tasks': 'configure the ALLOWED_TASKS dictionary to map task names to their pipeline classes', 'setup_middleware': 'setup gzip and optional CORS middleware for the starlette application', 'reset_logging': 'reset logging to debug level with timestamp and message format'}
```

## File: huggingface_api-inference-community/docker_images/latent-to-image/app/timing.py

Prompts

```
['run the starlette healthcheck metrics server that exposes app status and connection metrics', 'compute and update global metrics by counting connections and checking app status with timeout', 'count the current established TCP connections to a given app port and return prometheus metrics', 'check if the main ASGI app is ok, busy, or error by sending a request with a 0.5 second timeout', 'find the gunicorn process listening on a given port by scanning network connections with psutil', 'run the async live check loop that monitors request activity and terminates the worker on idle timeout', 'use the request_witnesses context manager to track request start and end timestamps for idle monitoring', 'configure the idle timeout duration by setting the IDLE_TIMEOUT environment variable before importing', 'enable automatic worker unloading on idle by setting the UNLOAD_IDLE environment variable to true', 'review the live_check_loop function to understand how it checks LAST_START and LAST_END timestamps for activity', 'run the starlette app that serves the latent-to-image pipeline via HTTP routes', 'get the cached pipeline instance for the configured TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dictionary to map task names to their pipeline classes', 'setup gzip and optional CORS middleware for the starlette application', 'reset logging to debug level with timestamp and message format', 'create a timing decorator that logs function execution time in seconds', 'use the timing decorator on a slow function to measure its execution duration', 'wrap any function with the timing decorator to log how long it takes to execute', 'review the timing decorator that logs function name and execution time via debug logging', 'refactor the timing decorator to support custom metrics collection beyond basic timing', 'test the str_to_bool function with strings like true, yes, and 1', 'refactor str_to_bool to return a boolean instead of a regex match object', 'review the str_to_bool function for edge cases and input validation', 'summarize the str_to_bool function that matches true, yes, or 1 strings', 'create a wrapper function around str_to_bool that handles None and empty input']
```

Usage

```
{'create_timing_decorator': 'create a timing decorator that logs function execution time in seconds', 'use_timing_on_slow_function': 'use the timing decorator on a slow function to measure its execution duration', 'wrap_function_with_timing': 'wrap any function with the timing decorator to log how long it takes to execute', 'review_timing_decorator': 'review the timing decorator that logs function name and execution time via debug logging', 'refactor_timing_to_add_metrics': 'refactor the timing decorator to support custom metrics collection beyond basic timing'}
```

## File: huggingface_api-inference-community/docker_images/latent-to-image/app/validation.py

Prompts

```
['run the starlette healthcheck metrics server that exposes app status and connection metrics', 'compute and update global metrics by counting connections and checking app status with timeout', 'count the current established TCP connections to a given app port and return prometheus metrics', 'check if the main ASGI app is ok, busy, or error by sending a request with a 0.5 second timeout', 'find the gunicorn process listening on a given port by scanning network connections with psutil', 'run the async live check loop that monitors request activity and terminates the worker on idle timeout', 'use the request_witnesses context manager to track request start and end timestamps for idle monitoring', 'configure the idle timeout duration by setting the IDLE_TIMEOUT environment variable before importing', 'enable automatic worker unloading on idle by setting the UNLOAD_IDLE environment variable to true', 'review the live_check_loop function to understand how it checks LAST_START and LAST_END timestamps for activity', 'run the starlette app that serves the latent-to-image pipeline via HTTP routes', 'get the cached pipeline instance for the configured TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dictionary to map task names to their pipeline classes', 'setup gzip and optional CORS middleware for the starlette application', 'reset logging to debug level with timestamp and message format', 'create a timing decorator that logs function execution time in seconds', 'use the timing decorator on a slow function to measure its execution duration', 'wrap any function with the timing decorator to log how long it takes to execute', 'review the timing decorator that logs function name and execution time via debug logging', 'refactor the timing decorator to support custom metrics collection beyond basic timing', 'test the str_to_bool function with strings like true, yes, and 1', 'refactor str_to_bool to return a boolean instead of a regex match object', 'review the str_to_bool function for edge cases and input validation', 'summarize the str_to_bool function that matches true, yes, or 1 strings', 'create a wrapper function around str_to_bool that handles None and empty input']
```

Usage

```
{'test_str_to_bool': 'test the str_to_bool function with strings like true, yes, and 1', 'refactor_str_to_bool': 'refactor str_to_bool to return a boolean instead of a regex match object', 'review_str_to_bool': 'review the str_to_bool function for edge cases and input validation', 'summarize_str_to_bool': 'summarize the str_to_bool function that matches true, yes, or 1 strings', 'create_str_to_bool_wrapper': 'create a wrapper function around str_to_bool that handles None and empty input'}
```


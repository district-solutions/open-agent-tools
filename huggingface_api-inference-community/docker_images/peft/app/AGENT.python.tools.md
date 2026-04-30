# Agent Python Tools

- repo: huggingface/api-inference-community
- repo_uri: https://github.com/huggingface/api-inference-community

## File: huggingface_api-inference-community/docker_images/peft/app/idle.py

Prompts

```
['run the async live check loop that monitors request activity and sends SIGTERM if idle', 'use the request_witnesses context manager to track request start and end timestamps', 'review the live_check_loop function that aborts the worker process after exceeding the idle timeout', 'refactor the request_witnesses context manager to support custom timestamp tracking logic', 'summarize the idle module that manages GPU model unloading based on request activity timeouts', 'run a Starlette server that serves Hugging Face PEFT model inference via POST routes', 'create a cached pipeline instance using TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dictionary to map task names to Pipeline classes', 'setup an async startup event that initializes logging and starts the idle check loop', 'reset the Python logging configuration to DEBUG level with timestamp format', 'create a decorator that logs the execution time of any wrapped function', 'refactor a slow function by adding the timing decorator to measure its execution time', 'review the timing decorator that wraps functions and logs execution duration via debug logging', 'summarize the timing decorator that measures and logs how long a function takes to execute', 'test the timing decorator by wrapping a function and verifying it logs execution time']
```

Usage

```
{'run_live_check_loop': 'run the async live check loop that monitors request activity and sends SIGTERM if idle', 'use_request_witnesses_context_manager': 'use the request_witnesses context manager to track request start and end timestamps', 'review_live_check_loop': 'review the live_check_loop function that aborts the worker process after exceeding the idle timeout', 'refactor_request_witnesses': 'refactor the request_witnesses context manager to support custom timestamp tracking logic', 'summarize_idle_module': 'summarize the idle module that manages GPU model unloading based on request activity timeouts'}
```

## File: huggingface_api-inference-community/docker_images/peft/app/main.py

Prompts

```
['run the async live check loop that monitors request activity and sends SIGTERM if idle', 'use the request_witnesses context manager to track request start and end timestamps', 'review the live_check_loop function that aborts the worker process after exceeding the idle timeout', 'refactor the request_witnesses context manager to support custom timestamp tracking logic', 'summarize the idle module that manages GPU model unloading based on request activity timeouts', 'run a Starlette server that serves Hugging Face PEFT model inference via POST routes', 'create a cached pipeline instance using TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dictionary to map task names to Pipeline classes', 'setup an async startup event that initializes logging and starts the idle check loop', 'reset the Python logging configuration to DEBUG level with timestamp format', 'create a decorator that logs the execution time of any wrapped function', 'refactor a slow function by adding the timing decorator to measure its execution time', 'review the timing decorator that wraps functions and logs execution duration via debug logging', 'summarize the timing decorator that measures and logs how long a function takes to execute', 'test the timing decorator by wrapping a function and verifying it logs execution time']
```

Usage

```
{'run_starlette_inference_server': 'run a Starlette server that serves Hugging Face PEFT model inference via POST routes', 'create_pipeline_from_env': 'create a cached pipeline instance using TASK and MODEL_ID environment variables', 'configure_allowed_tasks': 'configure the ALLOWED_TASKS dictionary to map task names to Pipeline classes', 'setup_startup_event': 'setup an async startup event that initializes logging and starts the idle check loop', 'reset_logging_config': 'reset the Python logging configuration to DEBUG level with timestamp format'}
```

## File: huggingface_api-inference-community/docker_images/peft/app/timing.py

Prompts

```
['run the async live check loop that monitors request activity and sends SIGTERM if idle', 'use the request_witnesses context manager to track request start and end timestamps', 'review the live_check_loop function that aborts the worker process after exceeding the idle timeout', 'refactor the request_witnesses context manager to support custom timestamp tracking logic', 'summarize the idle module that manages GPU model unloading based on request activity timeouts', 'run a Starlette server that serves Hugging Face PEFT model inference via POST routes', 'create a cached pipeline instance using TASK and MODEL_ID environment variables', 'configure the ALLOWED_TASKS dictionary to map task names to Pipeline classes', 'setup an async startup event that initializes logging and starts the idle check loop', 'reset the Python logging configuration to DEBUG level with timestamp format', 'create a decorator that logs the execution time of any wrapped function', 'refactor a slow function by adding the timing decorator to measure its execution time', 'review the timing decorator that wraps functions and logs execution duration via debug logging', 'summarize the timing decorator that measures and logs how long a function takes to execute', 'test the timing decorator by wrapping a function and verifying it logs execution time']
```

Usage

```
{'create_function_timing': 'create a decorator that logs the execution time of any wrapped function', 'refactor_function_with_timing': 'refactor a slow function by adding the timing decorator to measure its execution time', 'review_timing_decorator': 'review the timing decorator that wraps functions and logs execution duration via debug logging', 'summarize_timing': 'summarize the timing decorator that measures and logs how long a function takes to execute', 'test_timing_decorator': 'test the timing decorator by wrapping a function and verifying it logs execution time'}
```


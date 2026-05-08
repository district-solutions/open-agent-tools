# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/tests/unit/utils/test_basics.py

Prompts

```
['convert a Python object with dataclasses, enums, tuples, and sets into a JSON-compatible dictionary', 'sanitize a model or app name by replacing slashes with dashes for Ray Serve compatibility', 'extract the first user message from a Llama 3 formatted prompt with header tags', 'resolve a dotted path string like matrix.job.job_utils.echo into a callable Python function', 'access a nested value in a dictionary or list using a dotted path string with bracket index notation', 'test the async fetch_url function that performs GET requests and returns status and content', 'test that fetch_url gracefully handles network errors by returning None status and error message', 'test the async post_url function that sends JSON payloads via aiohttp ClientSession', 'test the synchronous fetch_url_sync function that performs GET requests using the requests library', 'test that post_url surfaces unexpected errors by returning None status and the exception message', 'run a subprocess command with streaming output and optional logging support', 'kill a process and all its child processes using psutil with a timeout', 'find a specified number of unique free TCP ports on the local machine', 'batch execute async function calls with a configurable batch size and error handling', 'create symlinks for job stdout and stderr files with optional index incrementing', 'test the get_ray_address function that constructs a ray://host:port URL from ClusterInfo', 'test the get_ray_dashboard_address function that constructs an http://host:port URL from ClusterInfo', 'test the status_is_success helper that returns True when a Ray app status is RUNNING', 'test the status_is_failure helper that returns True for DEPLOY_FAILED or DELETING Ray app statuses', 'test the status_is_pending helper that returns True for NOT_STARTED, DEPLOYING, or UNHEALTHY Ray app statuses']
```

Usage

```
{'convert_to_json_compatible': 'convert a Python object with dataclasses, enums, tuples, and sets into a JSON-compatible dictionary', 'sanitize_app_name': 'sanitize a model or app name by replacing slashes with dashes for Ray Serve compatibility', 'get_user_message_from_llama3_prompt': 'extract the first user message from a Llama 3 formatted prompt with header tags', 'str_to_callable': 'resolve a dotted path string like matrix.job.job_utils.echo into a callable Python function', 'get_nested_value': 'access a nested value in a dictionary or list using a dotted path string with bracket index notation'}
```

## File: facebookresearch_matrix/tests/unit/utils/test_http.py

Prompts

```
['convert a Python object with dataclasses, enums, tuples, and sets into a JSON-compatible dictionary', 'sanitize a model or app name by replacing slashes with dashes for Ray Serve compatibility', 'extract the first user message from a Llama 3 formatted prompt with header tags', 'resolve a dotted path string like matrix.job.job_utils.echo into a callable Python function', 'access a nested value in a dictionary or list using a dotted path string with bracket index notation', 'test the async fetch_url function that performs GET requests and returns status and content', 'test that fetch_url gracefully handles network errors by returning None status and error message', 'test the async post_url function that sends JSON payloads via aiohttp ClientSession', 'test the synchronous fetch_url_sync function that performs GET requests using the requests library', 'test that post_url surfaces unexpected errors by returning None status and the exception message', 'run a subprocess command with streaming output and optional logging support', 'kill a process and all its child processes using psutil with a timeout', 'find a specified number of unique free TCP ports on the local machine', 'batch execute async function calls with a configurable batch size and error handling', 'create symlinks for job stdout and stderr files with optional index incrementing', 'test the get_ray_address function that constructs a ray://host:port URL from ClusterInfo', 'test the get_ray_dashboard_address function that constructs an http://host:port URL from ClusterInfo', 'test the status_is_success helper that returns True when a Ray app status is RUNNING', 'test the status_is_failure helper that returns True for DEPLOY_FAILED or DELETING Ray app statuses', 'test the status_is_pending helper that returns True for NOT_STARTED, DEPLOYING, or UNHEALTHY Ray app statuses']
```

Usage

```
{'test_fetch_url_async': 'test the async fetch_url function that performs GET requests and returns status and content', 'test_fetch_url_error_handling': 'test that fetch_url gracefully handles network errors by returning None status and error message', 'test_post_url_async': 'test the async post_url function that sends JSON payloads via aiohttp ClientSession', 'test_fetch_url_sync': 'test the synchronous fetch_url_sync function that performs GET requests using the requests library', 'test_post_url_error_handling': 'test that post_url surfaces unexpected errors by returning None status and the exception message'}
```

## File: facebookresearch_matrix/tests/unit/utils/test_os.py

Prompts

```
['convert a Python object with dataclasses, enums, tuples, and sets into a JSON-compatible dictionary', 'sanitize a model or app name by replacing slashes with dashes for Ray Serve compatibility', 'extract the first user message from a Llama 3 formatted prompt with header tags', 'resolve a dotted path string like matrix.job.job_utils.echo into a callable Python function', 'access a nested value in a dictionary or list using a dotted path string with bracket index notation', 'test the async fetch_url function that performs GET requests and returns status and content', 'test that fetch_url gracefully handles network errors by returning None status and error message', 'test the async post_url function that sends JSON payloads via aiohttp ClientSession', 'test the synchronous fetch_url_sync function that performs GET requests using the requests library', 'test that post_url surfaces unexpected errors by returning None status and the exception message', 'run a subprocess command with streaming output and optional logging support', 'kill a process and all its child processes using psutil with a timeout', 'find a specified number of unique free TCP ports on the local machine', 'batch execute async function calls with a configurable batch size and error handling', 'create symlinks for job stdout and stderr files with optional index incrementing', 'test the get_ray_address function that constructs a ray://host:port URL from ClusterInfo', 'test the get_ray_dashboard_address function that constructs an http://host:port URL from ClusterInfo', 'test the status_is_success helper that returns True when a Ray app status is RUNNING', 'test the status_is_failure helper that returns True for DEPLOY_FAILED or DELETING Ray app statuses', 'test the status_is_pending helper that returns True for NOT_STARTED, DEPLOYING, or UNHEALTHY Ray app statuses']
```

Usage

```
{'run_and_stream_subprocess': 'run a subprocess command with streaming output and optional logging support', 'kill_proc_tree': 'kill a process and all its child processes using psutil with a timeout', 'find_free_ports': 'find a specified number of unique free TCP ports on the local machine', 'batch_requests_async': 'batch execute async function calls with a configurable batch size and error handling', 'create_symlinks': 'create symlinks for job stdout and stderr files with optional index incrementing'}
```

## File: facebookresearch_matrix/tests/unit/utils/test_ray.py

Prompts

```
['convert a Python object with dataclasses, enums, tuples, and sets into a JSON-compatible dictionary', 'sanitize a model or app name by replacing slashes with dashes for Ray Serve compatibility', 'extract the first user message from a Llama 3 formatted prompt with header tags', 'resolve a dotted path string like matrix.job.job_utils.echo into a callable Python function', 'access a nested value in a dictionary or list using a dotted path string with bracket index notation', 'test the async fetch_url function that performs GET requests and returns status and content', 'test that fetch_url gracefully handles network errors by returning None status and error message', 'test the async post_url function that sends JSON payloads via aiohttp ClientSession', 'test the synchronous fetch_url_sync function that performs GET requests using the requests library', 'test that post_url surfaces unexpected errors by returning None status and the exception message', 'run a subprocess command with streaming output and optional logging support', 'kill a process and all its child processes using psutil with a timeout', 'find a specified number of unique free TCP ports on the local machine', 'batch execute async function calls with a configurable batch size and error handling', 'create symlinks for job stdout and stderr files with optional index incrementing', 'test the get_ray_address function that constructs a ray://host:port URL from ClusterInfo', 'test the get_ray_dashboard_address function that constructs an http://host:port URL from ClusterInfo', 'test the status_is_success helper that returns True when a Ray app status is RUNNING', 'test the status_is_failure helper that returns True for DEPLOY_FAILED or DELETING Ray app statuses', 'test the status_is_pending helper that returns True for NOT_STARTED, DEPLOYING, or UNHEALTHY Ray app statuses']
```

Usage

```
{'test_get_ray_address': 'test the get_ray_address function that constructs a ray://host:port URL from ClusterInfo', 'test_get_ray_dashboard_address': 'test the get_ray_dashboard_address function that constructs an http://host:port URL from ClusterInfo', 'test_status_is_success': 'test the status_is_success helper that returns True when a Ray app status is RUNNING', 'test_status_is_failure': 'test the status_is_failure helper that returns True for DEPLOY_FAILED or DELETING Ray app statuses', 'test_status_is_pending': 'test the status_is_pending helper that returns True for NOT_STARTED, DEPLOYING, or UNHEALTHY Ray app statuses'}
```


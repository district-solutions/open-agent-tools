# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/utils/basics.py

Prompts

```
['convert a Python object with dataclasses and enums into a JSON-compatible dictionary', 'sanitize a string by removing slashes to create a Ray Serve compatible application name', 'extract the user message from a LLaMA 3 formatted prompt with header tokens', 'resolve a dotted path string like module.function into a callable Python object', 'access a nested value in a dictionary or list using a dotted path string', 'fetch data from a URL asynchronously using aiohttp and return the status code and response body', 'fetch data from a URL synchronously using requests and return the status code and response body', 'send a POST request with optional JSON data to a URL using an aiohttp session', 'review the async fetch_url function that uses aiohttp to GET a URL and return status and content', 'refactor the sync fetch_url_sync function to support additional HTTP methods beyond GET', 'run a shell command via subprocess and return True if it exits with code zero', 'kill a process and all its child processes recursively using psutil', 'find a list of N free TCP ports on localhost by binding ephemeral sockets', 'run a subprocess with real-time stdout streaming and optional blocking wait for exit', 'run a list of async function calls in parallel with a configurable concurrency limit and progress bar', 'get a list of alive or pending Ray actors in the matrix namespace filtered by optional prefix', 'kill all matrix namespace Ray actors optionally filtered by name prefix and return deleted names', 'initialize a Ray connection to the cluster if Ray is not already initialized', 'asynchronously retrieve results from Ray object refs or lists of refs with timeout support', 'fetch the list of Ray Serve applications and their status from the Ray dashboard HTTP API']
```

Usage

```
{'convert_to_json_compatible': 'convert a Python object with dataclasses and enums into a JSON-compatible dictionary', 'sanitize_app_name': 'sanitize a string by removing slashes to create a Ray Serve compatible application name', 'get_user_message_from_llama3_prompt': 'extract the user message from a LLaMA 3 formatted prompt with header tokens', 'str_to_callable': 'resolve a dotted path string like module.function into a callable Python object', 'get_nested_value': 'access a nested value in a dictionary or list using a dotted path string'}
```

## File: facebookresearch_matrix/matrix/utils/http.py

Prompts

```
['convert a Python object with dataclasses and enums into a JSON-compatible dictionary', 'sanitize a string by removing slashes to create a Ray Serve compatible application name', 'extract the user message from a LLaMA 3 formatted prompt with header tokens', 'resolve a dotted path string like module.function into a callable Python object', 'access a nested value in a dictionary or list using a dotted path string', 'fetch data from a URL asynchronously using aiohttp and return the status code and response body', 'fetch data from a URL synchronously using requests and return the status code and response body', 'send a POST request with optional JSON data to a URL using an aiohttp session', 'review the async fetch_url function that uses aiohttp to GET a URL and return status and content', 'refactor the sync fetch_url_sync function to support additional HTTP methods beyond GET', 'run a shell command via subprocess and return True if it exits with code zero', 'kill a process and all its child processes recursively using psutil', 'find a list of N free TCP ports on localhost by binding ephemeral sockets', 'run a subprocess with real-time stdout streaming and optional blocking wait for exit', 'run a list of async function calls in parallel with a configurable concurrency limit and progress bar', 'get a list of alive or pending Ray actors in the matrix namespace filtered by optional prefix', 'kill all matrix namespace Ray actors optionally filtered by name prefix and return deleted names', 'initialize a Ray connection to the cluster if Ray is not already initialized', 'asynchronously retrieve results from Ray object refs or lists of refs with timeout support', 'fetch the list of Ray Serve applications and their status from the Ray dashboard HTTP API']
```

Usage

```
{'fetch_url_async': 'fetch data from a URL asynchronously using aiohttp and return the status code and response body', 'fetch_url_sync': 'fetch data from a URL synchronously using requests and return the status code and response body', 'post_url_async': 'send a POST request with optional JSON data to a URL using an aiohttp session', 'review_fetch_url_async': 'review the async fetch_url function that uses aiohttp to GET a URL and return status and content', 'refactor_fetch_url_sync': 'refactor the sync fetch_url_sync function to support additional HTTP methods beyond GET'}
```

## File: facebookresearch_matrix/matrix/utils/os.py

Prompts

```
['convert a Python object with dataclasses and enums into a JSON-compatible dictionary', 'sanitize a string by removing slashes to create a Ray Serve compatible application name', 'extract the user message from a LLaMA 3 formatted prompt with header tokens', 'resolve a dotted path string like module.function into a callable Python object', 'access a nested value in a dictionary or list using a dotted path string', 'fetch data from a URL asynchronously using aiohttp and return the status code and response body', 'fetch data from a URL synchronously using requests and return the status code and response body', 'send a POST request with optional JSON data to a URL using an aiohttp session', 'review the async fetch_url function that uses aiohttp to GET a URL and return status and content', 'refactor the sync fetch_url_sync function to support additional HTTP methods beyond GET', 'run a shell command via subprocess and return True if it exits with code zero', 'kill a process and all its child processes recursively using psutil', 'find a list of N free TCP ports on localhost by binding ephemeral sockets', 'run a subprocess with real-time stdout streaming and optional blocking wait for exit', 'run a list of async function calls in parallel with a configurable concurrency limit and progress bar', 'get a list of alive or pending Ray actors in the matrix namespace filtered by optional prefix', 'kill all matrix namespace Ray actors optionally filtered by name prefix and return deleted names', 'initialize a Ray connection to the cluster if Ray is not already initialized', 'asynchronously retrieve results from Ray object refs or lists of refs with timeout support', 'fetch the list of Ray Serve applications and their status from the Ray dashboard HTTP API']
```

Usage

```
{'run_subprocess_command': 'run a shell command via subprocess and return True if it exits with code zero', 'kill_proc_tree': 'kill a process and all its child processes recursively using psutil', 'find_free_ports': 'find a list of N free TCP ports on localhost by binding ephemeral sockets', 'run_and_stream_subprocess': 'run a subprocess with real-time stdout streaming and optional blocking wait for exit', 'batch_requests_async': 'run a list of async function calls in parallel with a configurable concurrency limit and progress bar'}
```

## File: facebookresearch_matrix/matrix/utils/ray.py

Prompts

```
['convert a Python object with dataclasses and enums into a JSON-compatible dictionary', 'sanitize a string by removing slashes to create a Ray Serve compatible application name', 'extract the user message from a LLaMA 3 formatted prompt with header tokens', 'resolve a dotted path string like module.function into a callable Python object', 'access a nested value in a dictionary or list using a dotted path string', 'fetch data from a URL asynchronously using aiohttp and return the status code and response body', 'fetch data from a URL synchronously using requests and return the status code and response body', 'send a POST request with optional JSON data to a URL using an aiohttp session', 'review the async fetch_url function that uses aiohttp to GET a URL and return status and content', 'refactor the sync fetch_url_sync function to support additional HTTP methods beyond GET', 'run a shell command via subprocess and return True if it exits with code zero', 'kill a process and all its child processes recursively using psutil', 'find a list of N free TCP ports on localhost by binding ephemeral sockets', 'run a subprocess with real-time stdout streaming and optional blocking wait for exit', 'run a list of async function calls in parallel with a configurable concurrency limit and progress bar', 'get a list of alive or pending Ray actors in the matrix namespace filtered by optional prefix', 'kill all matrix namespace Ray actors optionally filtered by name prefix and return deleted names', 'initialize a Ray connection to the cluster if Ray is not already initialized', 'asynchronously retrieve results from Ray object refs or lists of refs with timeout support', 'fetch the list of Ray Serve applications and their status from the Ray dashboard HTTP API']
```

Usage

```
{'get_matrix_actors': 'get a list of alive or pending Ray actors in the matrix namespace filtered by optional prefix', 'kill_matrix_actors': 'kill all matrix namespace Ray actors optionally filtered by name prefix and return deleted names', 'init_ray_if_necessary': 'initialize a Ray connection to the cluster if Ray is not already initialized', 'ray_get_async': 'asynchronously retrieve results from Ray object refs or lists of refs with timeout support', 'get_serve_applications': 'fetch the list of Ray Serve applications and their status from the Ray dashboard HTTP API'}
```


# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/elastic/utils/api.py

Prompts

```
['create a function that retrieves an environment variable or raises ValueError if not set', 'build a function that creates a listening socket bound to localhost on an available port', 'test the macros.substitute function that substitutes ${local_rank} placeholders in command-line argument lists', 'refactor the macros.substitute method to support additional template variable substitutions beyond local_rank', 'review the macros class that provides template-based argument substitution for distributed launch commands', 'create a c10d TCPStore for distributed elastic training with configurable server port and timeout', 'create a c10d TCPStore that retries on port conflict when server_port is not statically specified', 'check that all world_size members have checked in to the TCPStore before proceeding', 'get a free port on localhost by binding and closing a temporary socket', 'get a socket bound to a free port on localhost that can be passed to a server function', "test the get_log_level function returns the string 'WARNING'", 'summarize the get_log_level function that returns the default pytorch log level', 'refactor the get_log_level function to accept an optional environment variable override', 'review the get_log_level function and its type annotation returning a log level string', 'create a function that retrieves the default log level for pytorch distributed elastic', 'create a logger using get_logger that writes to stderr with LOGLEVEL env var', 'build a logger via _setup_logger with a custom name and log level from env', 'test _derive_module_name to extract caller module name from stack frames', 'refactor get_logger to support configurable stack depth for module name derivation', 'review the logging utility module for proper error handling and fallback behavior', 'test the get_all function that retrieves data from a store for all ranks using a prefix and size', 'test the synchronize function that synchronizes world_size agents using a c10d store and shared data', 'test the barrier function that creates a global lock between distributed agents', 'review the get_all function that fetches prefixed store keys and waits for all ranks to finish', 'review the synchronize function that sets per-rank data and collects all agent data from the store']
```

Usage

```
{'create_get_env_variable_or_raise': 'create a function that retrieves an environment variable or raises ValueError if not set', 'build_get_socket_with_port': 'build a function that creates a listening socket bound to localhost on an available port', 'test_macros_substitute': 'test the macros.substitute function that substitutes ${local_rank} placeholders in command-line argument lists', 'refactor_macros_substitute': 'refactor the macros.substitute method to support additional template variable substitutions beyond local_rank', 'review_macros_class': 'review the macros class that provides template-based argument substitution for distributed launch commands'}
```

## File: pytorch_pytorch/torch/distributed/elastic/utils/distributed.py

Prompts

```
['create a function that retrieves an environment variable or raises ValueError if not set', 'build a function that creates a listening socket bound to localhost on an available port', 'test the macros.substitute function that substitutes ${local_rank} placeholders in command-line argument lists', 'refactor the macros.substitute method to support additional template variable substitutions beyond local_rank', 'review the macros class that provides template-based argument substitution for distributed launch commands', 'create a c10d TCPStore for distributed elastic training with configurable server port and timeout', 'create a c10d TCPStore that retries on port conflict when server_port is not statically specified', 'check that all world_size members have checked in to the TCPStore before proceeding', 'get a free port on localhost by binding and closing a temporary socket', 'get a socket bound to a free port on localhost that can be passed to a server function', "test the get_log_level function returns the string 'WARNING'", 'summarize the get_log_level function that returns the default pytorch log level', 'refactor the get_log_level function to accept an optional environment variable override', 'review the get_log_level function and its type annotation returning a log level string', 'create a function that retrieves the default log level for pytorch distributed elastic', 'create a logger using get_logger that writes to stderr with LOGLEVEL env var', 'build a logger via _setup_logger with a custom name and log level from env', 'test _derive_module_name to extract caller module name from stack frames', 'refactor get_logger to support configurable stack depth for module name derivation', 'review the logging utility module for proper error handling and fallback behavior', 'test the get_all function that retrieves data from a store for all ranks using a prefix and size', 'test the synchronize function that synchronizes world_size agents using a c10d store and shared data', 'test the barrier function that creates a global lock between distributed agents', 'review the get_all function that fetches prefixed store keys and waits for all ranks to finish', 'review the synchronize function that sets per-rank data and collects all agent data from the store']
```

Usage

```
{'create_c10d_store': 'create a c10d TCPStore for distributed elastic training with configurable server port and timeout', 'create_c10d_store_with_retry': 'create a c10d TCPStore that retries on port conflict when server_port is not statically specified', 'check_full_rank': 'check that all world_size members have checked in to the TCPStore before proceeding', 'get_free_port': 'get a free port on localhost by binding and closing a temporary socket', 'get_socket_with_port': 'get a socket bound to a free port on localhost that can be passed to a server function'}
```

## File: pytorch_pytorch/torch/distributed/elastic/utils/log_level.py

Prompts

```
['create a function that retrieves an environment variable or raises ValueError if not set', 'build a function that creates a listening socket bound to localhost on an available port', 'test the macros.substitute function that substitutes ${local_rank} placeholders in command-line argument lists', 'refactor the macros.substitute method to support additional template variable substitutions beyond local_rank', 'review the macros class that provides template-based argument substitution for distributed launch commands', 'create a c10d TCPStore for distributed elastic training with configurable server port and timeout', 'create a c10d TCPStore that retries on port conflict when server_port is not statically specified', 'check that all world_size members have checked in to the TCPStore before proceeding', 'get a free port on localhost by binding and closing a temporary socket', 'get a socket bound to a free port on localhost that can be passed to a server function', "test the get_log_level function returns the string 'WARNING'", 'summarize the get_log_level function that returns the default pytorch log level', 'refactor the get_log_level function to accept an optional environment variable override', 'review the get_log_level function and its type annotation returning a log level string', 'create a function that retrieves the default log level for pytorch distributed elastic', 'create a logger using get_logger that writes to stderr with LOGLEVEL env var', 'build a logger via _setup_logger with a custom name and log level from env', 'test _derive_module_name to extract caller module name from stack frames', 'refactor get_logger to support configurable stack depth for module name derivation', 'review the logging utility module for proper error handling and fallback behavior', 'test the get_all function that retrieves data from a store for all ranks using a prefix and size', 'test the synchronize function that synchronizes world_size agents using a c10d store and shared data', 'test the barrier function that creates a global lock between distributed agents', 'review the get_all function that fetches prefixed store keys and waits for all ranks to finish', 'review the synchronize function that sets per-rank data and collects all agent data from the store']
```

Usage

```
{'test_get_log_level': "test the get_log_level function returns the string 'WARNING'", 'summarize_get_log_level': 'summarize the get_log_level function that returns the default pytorch log level', 'refactor_get_log_level': 'refactor the get_log_level function to accept an optional environment variable override', 'review_get_log_level': 'review the get_log_level function and its type annotation returning a log level string', 'create_function_get_log_level': 'create a function that retrieves the default log level for pytorch distributed elastic'}
```

## File: pytorch_pytorch/torch/distributed/elastic/utils/logging.py

Prompts

```
['create a function that retrieves an environment variable or raises ValueError if not set', 'build a function that creates a listening socket bound to localhost on an available port', 'test the macros.substitute function that substitutes ${local_rank} placeholders in command-line argument lists', 'refactor the macros.substitute method to support additional template variable substitutions beyond local_rank', 'review the macros class that provides template-based argument substitution for distributed launch commands', 'create a c10d TCPStore for distributed elastic training with configurable server port and timeout', 'create a c10d TCPStore that retries on port conflict when server_port is not statically specified', 'check that all world_size members have checked in to the TCPStore before proceeding', 'get a free port on localhost by binding and closing a temporary socket', 'get a socket bound to a free port on localhost that can be passed to a server function', "test the get_log_level function returns the string 'WARNING'", 'summarize the get_log_level function that returns the default pytorch log level', 'refactor the get_log_level function to accept an optional environment variable override', 'review the get_log_level function and its type annotation returning a log level string', 'create a function that retrieves the default log level for pytorch distributed elastic', 'create a logger using get_logger that writes to stderr with LOGLEVEL env var', 'build a logger via _setup_logger with a custom name and log level from env', 'test _derive_module_name to extract caller module name from stack frames', 'refactor get_logger to support configurable stack depth for module name derivation', 'review the logging utility module for proper error handling and fallback behavior', 'test the get_all function that retrieves data from a store for all ranks using a prefix and size', 'test the synchronize function that synchronizes world_size agents using a c10d store and shared data', 'test the barrier function that creates a global lock between distributed agents', 'review the get_all function that fetches prefixed store keys and waits for all ranks to finish', 'review the synchronize function that sets per-rank data and collects all agent data from the store']
```

Usage

```
{'create_get_logger': 'create a logger using get_logger that writes to stderr with LOGLEVEL env var', 'build_setup_logger': 'build a logger via _setup_logger with a custom name and log level from env', 'test_derive_module_name': 'test _derive_module_name to extract caller module name from stack frames', 'refactor_get_logger': 'refactor get_logger to support configurable stack depth for module name derivation', 'review_logging_module': 'review the logging utility module for proper error handling and fallback behavior'}
```

## File: pytorch_pytorch/torch/distributed/elastic/utils/store.py

Prompts

```
['create a function that retrieves an environment variable or raises ValueError if not set', 'build a function that creates a listening socket bound to localhost on an available port', 'test the macros.substitute function that substitutes ${local_rank} placeholders in command-line argument lists', 'refactor the macros.substitute method to support additional template variable substitutions beyond local_rank', 'review the macros class that provides template-based argument substitution for distributed launch commands', 'create a c10d TCPStore for distributed elastic training with configurable server port and timeout', 'create a c10d TCPStore that retries on port conflict when server_port is not statically specified', 'check that all world_size members have checked in to the TCPStore before proceeding', 'get a free port on localhost by binding and closing a temporary socket', 'get a socket bound to a free port on localhost that can be passed to a server function', "test the get_log_level function returns the string 'WARNING'", 'summarize the get_log_level function that returns the default pytorch log level', 'refactor the get_log_level function to accept an optional environment variable override', 'review the get_log_level function and its type annotation returning a log level string', 'create a function that retrieves the default log level for pytorch distributed elastic', 'create a logger using get_logger that writes to stderr with LOGLEVEL env var', 'build a logger via _setup_logger with a custom name and log level from env', 'test _derive_module_name to extract caller module name from stack frames', 'refactor get_logger to support configurable stack depth for module name derivation', 'review the logging utility module for proper error handling and fallback behavior', 'test the get_all function that retrieves data from a store for all ranks using a prefix and size', 'test the synchronize function that synchronizes world_size agents using a c10d store and shared data', 'test the barrier function that creates a global lock between distributed agents', 'review the get_all function that fetches prefixed store keys and waits for all ranks to finish', 'review the synchronize function that sets per-rank data and collects all agent data from the store']
```

Usage

```
{'test_get_all': 'test the get_all function that retrieves data from a store for all ranks using a prefix and size', 'test_synchronize': 'test the synchronize function that synchronizes world_size agents using a c10d store and shared data', 'test_barrier': 'test the barrier function that creates a global lock between distributed agents', 'review_get_all': 'review the get_all function that fetches prefixed store keys and waits for all ranks to finish', 'review_synchronize': 'review the synchronize function that sets per-rank data and collects all agent data from the store'}
```


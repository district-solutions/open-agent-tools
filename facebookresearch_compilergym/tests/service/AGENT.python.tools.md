# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/service/connection_test.py

Prompts

```
['test that CompilerGymServiceConnection raises TypeError when initialized with an empty endpoint string', 'test that CompilerGymServiceConnection raises ServiceError when connecting to a dead service with short RPC timeout', 'test that CompilerGymServiceConnection raises OSError when connecting to a dead service with long RPC timeout', 'test that calling a connection stub with an invalid request type raises a TypeError', 'test that calling a connection stub with a negative timeout raises a TimeoutError', 'test that ServiceCache creates a directory with logs and disk subdirectories on initialization', 'test accessing ServiceCache path using the forward slash operator to navigate subdirectories', 'test creating empty files in the ServiceCache root, logs, and disk directories to verify write permissions', 'test that calling close on ServiceCache removes the cache directory and all created files', 'test that ServiceCache uses an in-memory filesystem when available and symlinks disk to a real path']
```

Usage

```
{'test_create_invalid_connection': 'test that CompilerGymServiceConnection raises TypeError when initialized with an empty endpoint string', 'test_failed_subprocess_connection': 'test that CompilerGymServiceConnection raises ServiceError when connecting to a dead service with short RPC timeout', 'test_failed_connection_rpc_timeout': 'test that CompilerGymServiceConnection raises OSError when connecting to a dead service with long RPC timeout', 'test_stub_invalid_request_type': 'test that calling a connection stub with an invalid request type raises a TypeError', 'test_stub_negative_timeout': 'test that calling a connection stub with a negative timeout raises a TimeoutError'}
```

## File: facebookresearch_compilergym/tests/service/service_cache_test.py

Prompts

```
['test that CompilerGymServiceConnection raises TypeError when initialized with an empty endpoint string', 'test that CompilerGymServiceConnection raises ServiceError when connecting to a dead service with short RPC timeout', 'test that CompilerGymServiceConnection raises OSError when connecting to a dead service with long RPC timeout', 'test that calling a connection stub with an invalid request type raises a TypeError', 'test that calling a connection stub with a negative timeout raises a TimeoutError', 'test that ServiceCache creates a directory with logs and disk subdirectories on initialization', 'test accessing ServiceCache path using the forward slash operator to navigate subdirectories', 'test creating empty files in the ServiceCache root, logs, and disk directories to verify write permissions', 'test that calling close on ServiceCache removes the cache directory and all created files', 'test that ServiceCache uses an in-memory filesystem when available and symlinks disk to a real path']
```

Usage

```
{'test_service_cache_creation': 'test that ServiceCache creates a directory with logs and disk subdirectories on initialization', 'test_service_cache_path_access': 'test accessing ServiceCache path using the forward slash operator to navigate subdirectories', 'test_service_cache_file_permissions': 'test creating empty files in the ServiceCache root, logs, and disk directories to verify write permissions', 'test_service_cache_cleanup': 'test that calling close on ServiceCache removes the cache directory and all created files', 'test_service_cache_in_memory': 'test that ServiceCache uses an in-memory filesystem when available and symlinks disk to a real path'}
```


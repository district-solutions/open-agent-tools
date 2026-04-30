# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/meta/build.py

Prompts

```
['build a call to polars.meta.build.build_info that returns a dictionary of Polars build metadata including version, compiler, features, and dependencies', 'summarize the python function get_index_type that returns the data type used for Polars indexing', 'test the python function get_index_type returns UInt32 in regular Polars or UInt64 in bigidx Polars', 'review the python function get_index_type and its return type PolarsIntegerType', 'create a script that calls get_index_type to determine the default indexing type for Polars operations', 'refactor the python function get_index_type to support custom index type configuration', 'summarize the thread_pool_size function that returns the number of threads in the Polars thread pool', 'test the thread_pool_size function returns an integer representing the current thread pool size', 'review the deprecated threadpool_size function that was renamed to thread_pool_size', 'run thread_pool_size to check the number of threads configured in the Polars engine', 'refactor the deprecated threadpool_size function to use thread_pool_size instead', 'display Polars version info and all optional dependency versions installed in the environment', 'test the _get_dependency_list function returns the full list of optional dependency names', 'test the _get_dependency_version function retrieves version string for a given dependency name', 'summarize the show_versions function that prints Polars, platform, Python, runtime, and dependency versions', 'review the show_versions function that gathers and prints core properties and optional dependency versions']
```

Usage

```
{'build_build_info': 'build a call to polars.meta.build.build_info that returns a dictionary of Polars build metadata including version, compiler, features, and dependencies'}
```

## File: pola-rs_polars/py-polars/src/polars/meta/index_type.py

Prompts

```
['build a call to polars.meta.build.build_info that returns a dictionary of Polars build metadata including version, compiler, features, and dependencies', 'summarize the python function get_index_type that returns the data type used for Polars indexing', 'test the python function get_index_type returns UInt32 in regular Polars or UInt64 in bigidx Polars', 'review the python function get_index_type and its return type PolarsIntegerType', 'create a script that calls get_index_type to determine the default indexing type for Polars operations', 'refactor the python function get_index_type to support custom index type configuration', 'summarize the thread_pool_size function that returns the number of threads in the Polars thread pool', 'test the thread_pool_size function returns an integer representing the current thread pool size', 'review the deprecated threadpool_size function that was renamed to thread_pool_size', 'run thread_pool_size to check the number of threads configured in the Polars engine', 'refactor the deprecated threadpool_size function to use thread_pool_size instead', 'display Polars version info and all optional dependency versions installed in the environment', 'test the _get_dependency_list function returns the full list of optional dependency names', 'test the _get_dependency_version function retrieves version string for a given dependency name', 'summarize the show_versions function that prints Polars, platform, Python, runtime, and dependency versions', 'review the show_versions function that gathers and prints core properties and optional dependency versions']
```

Usage

```
{'summarize_get_index_type': 'summarize the python function get_index_type that returns the data type used for Polars indexing', 'test_get_index_type': 'test the python function get_index_type returns UInt32 in regular Polars or UInt64 in bigidx Polars', 'review_get_index_type': 'review the python function get_index_type and its return type PolarsIntegerType', 'create_use_index_type': 'create a script that calls get_index_type to determine the default indexing type for Polars operations', 'refactor_get_index_type': 'refactor the python function get_index_type to support custom index type configuration'}
```

## File: pola-rs_polars/py-polars/src/polars/meta/thread_pool.py

Prompts

```
['build a call to polars.meta.build.build_info that returns a dictionary of Polars build metadata including version, compiler, features, and dependencies', 'summarize the python function get_index_type that returns the data type used for Polars indexing', 'test the python function get_index_type returns UInt32 in regular Polars or UInt64 in bigidx Polars', 'review the python function get_index_type and its return type PolarsIntegerType', 'create a script that calls get_index_type to determine the default indexing type for Polars operations', 'refactor the python function get_index_type to support custom index type configuration', 'summarize the thread_pool_size function that returns the number of threads in the Polars thread pool', 'test the thread_pool_size function returns an integer representing the current thread pool size', 'review the deprecated threadpool_size function that was renamed to thread_pool_size', 'run thread_pool_size to check the number of threads configured in the Polars engine', 'refactor the deprecated threadpool_size function to use thread_pool_size instead', 'display Polars version info and all optional dependency versions installed in the environment', 'test the _get_dependency_list function returns the full list of optional dependency names', 'test the _get_dependency_version function retrieves version string for a given dependency name', 'summarize the show_versions function that prints Polars, platform, Python, runtime, and dependency versions', 'review the show_versions function that gathers and prints core properties and optional dependency versions']
```

Usage

```
{'summarize_thread_pool_size': 'summarize the thread_pool_size function that returns the number of threads in the Polars thread pool', 'test_thread_pool_size': 'test the thread_pool_size function returns an integer representing the current thread pool size', 'review_threadpool_size': 'review the deprecated threadpool_size function that was renamed to thread_pool_size', 'run_thread_pool_size': 'run thread_pool_size to check the number of threads configured in the Polars engine', 'refactor_threadpool_size': 'refactor the deprecated threadpool_size function to use thread_pool_size instead'}
```

## File: pola-rs_polars/py-polars/src/polars/meta/versions.py

Prompts

```
['build a call to polars.meta.build.build_info that returns a dictionary of Polars build metadata including version, compiler, features, and dependencies', 'summarize the python function get_index_type that returns the data type used for Polars indexing', 'test the python function get_index_type returns UInt32 in regular Polars or UInt64 in bigidx Polars', 'review the python function get_index_type and its return type PolarsIntegerType', 'create a script that calls get_index_type to determine the default indexing type for Polars operations', 'refactor the python function get_index_type to support custom index type configuration', 'summarize the thread_pool_size function that returns the number of threads in the Polars thread pool', 'test the thread_pool_size function returns an integer representing the current thread pool size', 'review the deprecated threadpool_size function that was renamed to thread_pool_size', 'run thread_pool_size to check the number of threads configured in the Polars engine', 'refactor the deprecated threadpool_size function to use thread_pool_size instead', 'display Polars version info and all optional dependency versions installed in the environment', 'test the _get_dependency_list function returns the full list of optional dependency names', 'test the _get_dependency_version function retrieves version string for a given dependency name', 'summarize the show_versions function that prints Polars, platform, Python, runtime, and dependency versions', 'review the show_versions function that gathers and prints core properties and optional dependency versions']
```

Usage

```
{'show_versions_display': 'display Polars version info and all optional dependency versions installed in the environment', 'test_get_dependency_list': 'test the _get_dependency_list function returns the full list of optional dependency names', 'test_get_dependency_version': 'test the _get_dependency_version function retrieves version string for a given dependency name', 'summarize_show_versions': 'summarize the show_versions function that prints Polars, platform, Python, runtime, and dependency versions', 'review_show_versions': 'review the show_versions function that gathers and prints core properties and optional dependency versions'}
```


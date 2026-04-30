# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/api/test_api.py

Prompts

```
['test the pandas public API to verify all expected classes, functions, and modules are exposed', 'test the pandas.api submodules including types, typing, executors, extensions, indexers, and interchange', 'test the pandas.api.typing aliases to verify all type alias exports are present', 'test that all public pandas objects have their __module__ set to the correct import path', 'summarize the get_pandas_objects function that recursively discovers pandas objects within a module', 'test the pandas.api.types is_bool_dtype function checks if a dtype is boolean', 'test the pandas.api.types is_integer_dtype function checks if a dtype is integer', 'test the pandas.api.types is_float_dtype function checks if a dtype is floating point', 'test the pandas.api.types is_datetime64_ns_dtype function checks for datetime64 with nanosecond precision', 'test the pandas.api.types is_list_like function checks if an object is list-like']
```

Usage

```
{'test_pandas_public_api': 'test the pandas public API to verify all expected classes, functions, and modules are exposed', 'test_api_submodules': 'test the pandas.api submodules including types, typing, executors, extensions, indexers, and interchange', 'test_api_typing_aliases': 'test the pandas.api.typing aliases to verify all type alias exports are present', 'test_attributes_module': 'test that all public pandas objects have their __module__ set to the correct import path', 'summarize_get_pandas_objects': 'summarize the get_pandas_objects function that recursively discovers pandas objects within a module'}
```

## File: pandas-dev_pandas/pandas/tests/api/test_types.py

Prompts

```
['test the pandas public API to verify all expected classes, functions, and modules are exposed', 'test the pandas.api submodules including types, typing, executors, extensions, indexers, and interchange', 'test the pandas.api.typing aliases to verify all type alias exports are present', 'test that all public pandas objects have their __module__ set to the correct import path', 'summarize the get_pandas_objects function that recursively discovers pandas objects within a module', 'test the pandas.api.types is_bool_dtype function checks if a dtype is boolean', 'test the pandas.api.types is_integer_dtype function checks if a dtype is integer', 'test the pandas.api.types is_float_dtype function checks if a dtype is floating point', 'test the pandas.api.types is_datetime64_ns_dtype function checks for datetime64 with nanosecond precision', 'test the pandas.api.types is_list_like function checks if an object is list-like']
```

Usage

```
{'test_is_bool_dtype': 'test the pandas.api.types is_bool_dtype function checks if a dtype is boolean', 'test_is_integer_dtype': 'test the pandas.api.types is_integer_dtype function checks if a dtype is integer', 'test_is_float_dtype': 'test the pandas.api.types is_float_dtype function checks if a dtype is floating point', 'test_is_datetime64_ns_dtype': 'test the pandas.api.types is_datetime64_ns_dtype function checks for datetime64 with nanosecond precision', 'test_is_list_like': 'test the pandas.api.types is_list_like function checks if an object is list-like'}
```


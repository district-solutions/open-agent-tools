# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/core/util/hashing.py

Prompts

```
['create a function that hashes a pandas Series, DataFrame, or Index and returns a Series of uint64 hash values', 'create a function that hashes a 1D numpy array or ExtensionArray and returns an array of deterministic uint64 integers', 'create a function that efficiently hashes a MultiIndex or list-of-tuples into uint64 hash values', 'create a function that combines multiple hash arrays into a single uint64 array using a CPython-style tuple hash algorithm', 'test the hash_pandas_object function to verify it produces consistent hashes for the same DataFrame values and index', 'test the maybe_use_numba function to determine whether numba routines should be used', 'build a call to set_use_numba to globally enable or disable numba acceleration', 'create a call to get_jit_arguments to retrieve nogil and parallel settings for numba JIT compilation', 'review the jit_user_function utility that marks user functions as jitable for numba', 'refactor prepare_function_arguments to convert kwargs into positional args for numba-compatible calls']
```

Usage

```
{'create_function_hash_pandas_object': 'create a function that hashes a pandas Series, DataFrame, or Index and returns a Series of uint64 hash values', 'create_function_hash_array': 'create a function that hashes a 1D numpy array or ExtensionArray and returns an array of deterministic uint64 integers', 'create_function_hash_tuples': 'create a function that efficiently hashes a MultiIndex or list-of-tuples into uint64 hash values', 'create_function_combine_hash_arrays': 'create a function that combines multiple hash arrays into a single uint64 array using a CPython-style tuple hash algorithm', 'test_function_hash_pandas_object': 'test the hash_pandas_object function to verify it produces consistent hashes for the same DataFrame values and index'}
```

## File: pandas-dev_pandas/pandas/core/util/numba_.py

Prompts

```
['create a function that hashes a pandas Series, DataFrame, or Index and returns a Series of uint64 hash values', 'create a function that hashes a 1D numpy array or ExtensionArray and returns an array of deterministic uint64 integers', 'create a function that efficiently hashes a MultiIndex or list-of-tuples into uint64 hash values', 'create a function that combines multiple hash arrays into a single uint64 array using a CPython-style tuple hash algorithm', 'test the hash_pandas_object function to verify it produces consistent hashes for the same DataFrame values and index', 'test the maybe_use_numba function to determine whether numba routines should be used', 'build a call to set_use_numba to globally enable or disable numba acceleration', 'create a call to get_jit_arguments to retrieve nogil and parallel settings for numba JIT compilation', 'review the jit_user_function utility that marks user functions as jitable for numba', 'refactor prepare_function_arguments to convert kwargs into positional args for numba-compatible calls']
```

Usage

```
{'test_maybe_use_numba': 'test the maybe_use_numba function to determine whether numba routines should be used', 'build_set_use_numba': 'build a call to set_use_numba to globally enable or disable numba acceleration', 'create_get_jit_arguments': 'create a call to get_jit_arguments to retrieve nogil and parallel settings for numba JIT compilation', 'review_jit_user_function': 'review the jit_user_function utility that marks user functions as jitable for numba', 'refactor_prepare_function_arguments': 'refactor prepare_function_arguments to convert kwargs into positional args for numba-compatible calls'}
```


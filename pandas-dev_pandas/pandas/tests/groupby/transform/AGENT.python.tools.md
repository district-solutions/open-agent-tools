# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/groupby/transform/test_numba.py

Prompts

```
['test groupby transform with numba engine requires a (values, index) function signature', 'test groupby transform with numba engine rejects keyword-only arguments in user-defined functions', 'test groupby transform results match between numba and cython engines with custom user-defined functions', 'test groupby transform with numba engine does not cache results across different positional arguments', 'test groupby transform with numba engine does not cache jitted functions when engine_kwargs change', 'test groupby transform with numba engine raises NotImplementedError for multi-key grouping', 'test groupby transform respects the compute.use_numba global config option', 'test groupby transform with multi-label keys and custom user-defined function matches cython results', 'test groupby transform with lambda function to demean values within each group', "test groupby transform using string alias 'mean' with numeric data", "test groupby transform with string alias 'first' on mixed dtype columns", 'test groupby transform broadcasting mean values back to original index', 'test groupby ffill and bfill transform methods with various limit and grouping options']
```

Usage

```
{'test_groupby_transform_numba_signature': 'test groupby transform with numba engine requires a (values, index) function signature', 'test_groupby_transform_nopython_kwargs': 'test groupby transform with numba engine rejects keyword-only arguments in user-defined functions', 'test_groupby_transform_numba_vs_cython': 'test groupby transform results match between numba and cython engines with custom user-defined functions', 'test_groupby_transform_args_not_cached': 'test groupby transform with numba engine does not cache results across different positional arguments', 'test_groupby_transform_engine_kwargs_not_cached': 'test groupby transform with numba engine does not cache jitted functions when engine_kwargs change', 'test_groupby_transform_multiindex_multi_key_not_supported': 'test groupby transform with numba engine raises NotImplementedError for multi-key grouping', 'test_groupby_transform_use_global_config': 'test groupby transform respects the compute.use_numba global config option', 'test_groupby_transform_multilabel_udf_numba_vs_cython': 'test groupby transform with multi-label keys and custom user-defined function matches cython results'}
```

## File: pandas-dev_pandas/pandas/tests/groupby/transform/test_transform.py

Prompts

```
['test groupby transform with numba engine requires a (values, index) function signature', 'test groupby transform with numba engine rejects keyword-only arguments in user-defined functions', 'test groupby transform results match between numba and cython engines with custom user-defined functions', 'test groupby transform with numba engine does not cache results across different positional arguments', 'test groupby transform with numba engine does not cache jitted functions when engine_kwargs change', 'test groupby transform with numba engine raises NotImplementedError for multi-key grouping', 'test groupby transform respects the compute.use_numba global config option', 'test groupby transform with multi-label keys and custom user-defined function matches cython results', 'test groupby transform with lambda function to demean values within each group', "test groupby transform using string alias 'mean' with numeric data", "test groupby transform with string alias 'first' on mixed dtype columns", 'test groupby transform broadcasting mean values back to original index', 'test groupby ffill and bfill transform methods with various limit and grouping options']
```

Usage

```
{'test_groupby_transform_basic': 'test groupby transform with lambda function to demean values within each group', 'test_transform_fast': "test groupby transform using string alias 'mean' with numeric data", 'test_transform_fast2': "test groupby transform with string alias 'first' on mixed dtype columns", 'test_transform_broadcast': 'test groupby transform broadcasting mean values back to original index', 'test_group_fill_methods': 'test groupby ffill and bfill transform methods with various limit and grouping options'}
```


# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/core/_numba/executor.py

Prompts

```
['generate a numba-compiled looper function that applies a user function across rows or columns of a 2D array with parallel execution', 'make a numba-compiled column looper kernel that supports either grouped or non-grouped aggregation with min_periods handling', 'generate a shared aggregator wrapper that dispatches dtype mappings and applies a numba column looper over 2D values with NaN post-processing', 'use the default dtype mapping to promote integer and float numpy dtypes to int64 or float64 for numba kernel results', 'use the float dtype mapping to convert all numpy dtypes including integers and complexes to float64 for numba kernel results', 'build a numba type class for pandas Index objects with dtype, layout, and pyclass attributes', 'create a numba type class for pandas Series objects with dtype, index, values, and name attributes', 'test the numba-compiled get_loc method on IndexType that lazily builds a hashmap for O(1) lookups', 'refactor the SeriesType to support binary operations like add, sub, mul, truediv between series and scalars', 'summarize the generated series reduction methods sum, mean, min, max compiled via numba overload_method', 'build a numba type class for pandas _iLocIndexer with obj_type and overload_attribute for iloc access', 'create a numba StructModel for IndexType with data, hashmap, and parent members', 'review the box and unbox functions that convert between native numba structures and pandas Index/Series objects']
```

Usage

```
{'generate_apply_looper': 'generate a numba-compiled looper function that applies a user function across rows or columns of a 2D array with parallel execution', 'make_looper': 'make a numba-compiled column looper kernel that supports either grouped or non-grouped aggregation with min_periods handling', 'generate_shared_aggregator': 'generate a shared aggregator wrapper that dispatches dtype mappings and applies a numba column looper over 2D values with NaN post-processing', 'use_default_dtype_mapping': 'use the default dtype mapping to promote integer and float numpy dtypes to int64 or float64 for numba kernel results', 'use_float_dtype_mapping': 'use the float dtype mapping to convert all numpy dtypes including integers and complexes to float64 for numba kernel results'}
```

## File: pandas-dev_pandas/pandas/core/_numba/extensions.py

Prompts

```
['generate a numba-compiled looper function that applies a user function across rows or columns of a 2D array with parallel execution', 'make a numba-compiled column looper kernel that supports either grouped or non-grouped aggregation with min_periods handling', 'generate a shared aggregator wrapper that dispatches dtype mappings and applies a numba column looper over 2D values with NaN post-processing', 'use the default dtype mapping to promote integer and float numpy dtypes to int64 or float64 for numba kernel results', 'use the float dtype mapping to convert all numpy dtypes including integers and complexes to float64 for numba kernel results', 'build a numba type class for pandas Index objects with dtype, layout, and pyclass attributes', 'create a numba type class for pandas Series objects with dtype, index, values, and name attributes', 'test the numba-compiled get_loc method on IndexType that lazily builds a hashmap for O(1) lookups', 'refactor the SeriesType to support binary operations like add, sub, mul, truediv between series and scalars', 'summarize the generated series reduction methods sum, mean, min, max compiled via numba overload_method', 'build a numba type class for pandas _iLocIndexer with obj_type and overload_attribute for iloc access', 'create a numba StructModel for IndexType with data, hashmap, and parent members', 'review the box and unbox functions that convert between native numba structures and pandas Index/Series objects']
```

Usage

```
{'build_numba_index_type': 'build a numba type class for pandas Index objects with dtype, layout, and pyclass attributes', 'create_numba_series_type': 'create a numba type class for pandas Series objects with dtype, index, values, and name attributes', 'test_index_get_loc': 'test the numba-compiled get_loc method on IndexType that lazily builds a hashmap for O(1) lookups', 'refactor_series_binop': 'refactor the SeriesType to support binary operations like add, sub, mul, truediv between series and scalars', 'summarize_series_reductions': 'summarize the generated series reduction methods sum, mean, min, max compiled via numba overload_method', 'build_iloc_indexer_type': 'build a numba type class for pandas _iLocIndexer with obj_type and overload_attribute for iloc access', 'create_index_model': 'create a numba StructModel for IndexType with data, hashmap, and parent members', 'review_box_unbox': 'review the box and unbox functions that convert between native numba structures and pandas Index/Series objects'}
```


# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/internals/test_api.py

Prompts

```
['test create_dataframe_from_blocks reconstructs a DataFrame from internal blocks and metadata', 'test create_dataframe_from_blocks handles multiple dtypes including int, uint, float, bool, string, datetime, categorical, and interval', 'test create_dataframe_from_blocks reconstructs datetimelike columns from numpy arrays with correct unit conversion', 'test create_dataframe_from_blocks accepts 1D ExtensionArrays for datetime, period, and timedelta types', 'test api.make_block creates a 2D block from a datetime index with timezone info', 'create a pandas BlockManager block from a type string and placement with supported dtypes like float int complex bool datetime timedelta sparse and category', 'create a pandas BlockManager from a semicolon-separated string description with column names and dtype identifiers', 'test BlockPlacement slice conversion to array and array to slice for contiguous and strided index sequences', 'test pickling and unpickling a BlockManager with mixed dtypes and verify reconstructed DataFrame equality', 'test BlockManager slicing taking and reindexing operations against equivalent numpy array operations', 'test whether a pandas Block can hold specific element types for datetime interval and period dtypes', 'test deleting columns from a Block and verifying updated manager locations and values', 'test splitting a Block into per-location sub-blocks that remain views of the original values']
```

Usage

```
{'test_create_dataframe_from_blocks': 'test create_dataframe_from_blocks reconstructs a DataFrame from internal blocks and metadata', 'test_create_dataframe_from_blocks_types': 'test create_dataframe_from_blocks handles multiple dtypes including int, uint, float, bool, string, datetime, categorical, and interval', 'test_create_dataframe_from_blocks_datetimelike': 'test create_dataframe_from_blocks reconstructs datetimelike columns from numpy arrays with correct unit conversion', 'test_create_dataframe_from_blocks_1dEA': 'test create_dataframe_from_blocks accepts 1D ExtensionArrays for datetime, period, and timedelta types', 'test_make_block_2d_with_dti': 'test api.make_block creates a 2D block from a datetime index with timezone info'}
```

## File: pandas-dev_pandas/pandas/tests/internals/test_internals.py

Prompts

```
['test create_dataframe_from_blocks reconstructs a DataFrame from internal blocks and metadata', 'test create_dataframe_from_blocks handles multiple dtypes including int, uint, float, bool, string, datetime, categorical, and interval', 'test create_dataframe_from_blocks reconstructs datetimelike columns from numpy arrays with correct unit conversion', 'test create_dataframe_from_blocks accepts 1D ExtensionArrays for datetime, period, and timedelta types', 'test api.make_block creates a 2D block from a datetime index with timezone info', 'create a pandas BlockManager block from a type string and placement with supported dtypes like float int complex bool datetime timedelta sparse and category', 'create a pandas BlockManager from a semicolon-separated string description with column names and dtype identifiers', 'test BlockPlacement slice conversion to array and array to slice for contiguous and strided index sequences', 'test pickling and unpickling a BlockManager with mixed dtypes and verify reconstructed DataFrame equality', 'test BlockManager slicing taking and reindexing operations against equivalent numpy array operations', 'test whether a pandas Block can hold specific element types for datetime interval and period dtypes', 'test deleting columns from a Block and verifying updated manager locations and values', 'test splitting a Block into per-location sub-blocks that remain views of the original values']
```

Usage

```
{'create_block': 'create a pandas BlockManager block from a type string and placement with supported dtypes like float int complex bool datetime timedelta sparse and category', 'create_mgr': 'create a pandas BlockManager from a semicolon-separated string description with column names and dtype identifiers', 'test_block_placement_slice': 'test BlockPlacement slice conversion to array and array to slice for contiguous and strided index sequences', 'test_block_manager_pickle': 'test pickling and unpickling a BlockManager with mixed dtypes and verify reconstructed DataFrame equality', 'test_block_manager_indexing': 'test BlockManager slicing taking and reindexing operations against equivalent numpy array operations', 'test_block_can_hold_element': 'test whether a pandas Block can hold specific element types for datetime interval and period dtypes', 'test_block_delete': 'test deleting columns from a Block and verifying updated manager locations and values', 'test_block_split': 'test splitting a Block into per-location sub-blocks that remain views of the original values'}
```


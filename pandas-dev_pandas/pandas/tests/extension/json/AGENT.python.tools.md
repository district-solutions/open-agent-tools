# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/extension/json/array.py

Prompts

```
['create a JSON extension dtype for storing nested data in pandas containers', 'build a JSONArray extension array that stores lists of dictionaries as scalars', 'test JSONArray __getitem__ with integer, slice, boolean mask, and list indices', 'test JSONArray take method with allow_fill and fill_value for padding operations', 'summarize JSONArray _concat_same_type for concatenating arrays of the same type', 'test the JSONArray extension array class against pandas extension test base suite', 'test fillna behavior for JSONArray with dictionary NA values and None handling', 'test setitem operations for JSONArray with mask, integer array, slice, and scalar indexers', 'test groupby extension transform and apply for unhashable JSONArray dictionary values', 'test scalar and array comparison operations for JSONArray with eq and ne methods']
```

Usage

```
{'create_json_dtype': 'create a JSON extension dtype for storing nested data in pandas containers', 'build_json_array': 'build a JSONArray extension array that stores lists of dictionaries as scalars', 'test_json_array_indexing': 'test JSONArray __getitem__ with integer, slice, boolean mask, and list indices', 'test_json_array_take': 'test JSONArray take method with allow_fill and fill_value for padding operations', 'summarize_json_array_concat': 'summarize JSONArray _concat_same_type for concatenating arrays of the same type'}
```

## File: pandas-dev_pandas/pandas/tests/extension/json/test_json.py

Prompts

```
['create a JSON extension dtype for storing nested data in pandas containers', 'build a JSONArray extension array that stores lists of dictionaries as scalars', 'test JSONArray __getitem__ with integer, slice, boolean mask, and list indices', 'test JSONArray take method with allow_fill and fill_value for padding operations', 'summarize JSONArray _concat_same_type for concatenating arrays of the same type', 'test the JSONArray extension array class against pandas extension test base suite', 'test fillna behavior for JSONArray with dictionary NA values and None handling', 'test setitem operations for JSONArray with mask, integer array, slice, and scalar indexers', 'test groupby extension transform and apply for unhashable JSONArray dictionary values', 'test scalar and array comparison operations for JSONArray with eq and ne methods']
```

Usage

```
{'test_json_array_semantics': 'test the JSONArray extension array class against pandas extension test base suite', 'test_json_fillna_behavior': 'test fillna behavior for JSONArray with dictionary NA values and None handling', 'test_json_setitem_indexing': 'test setitem operations for JSONArray with mask, integer array, slice, and scalar indexers', 'test_json_groupby_transform': 'test groupby extension transform and apply for unhashable JSONArray dictionary values', 'test_json_comparison_ops': 'test scalar and array comparison operations for JSONArray with eq and ne methods'}
```


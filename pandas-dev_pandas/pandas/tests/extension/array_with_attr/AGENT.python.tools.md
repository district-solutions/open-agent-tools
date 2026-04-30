# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/extension/array_with_attr/array.py

Prompts

```
['create a FloatAttrDtype extension dtype for pandas with custom float attribute support', 'build a FloatAttrArray extension array from a numpy float64 array with optional custom attribute', 'test the FloatAttrArray._from_sequence method to construct an array from scalar sequences', 'test the FloatAttrArray._concat_same_type method to concatenate multiple arrays of the same type', 'test the FloatAttrArray.take method with allow_fill and fill_value for indexed element retrieval', 'test pd.merge and pd.concat preserve custom extension array attributes when merging dataframes with all-NaN columns', 'create a FloatAttrArray instance with NaN data and a custom attribute for extension dtype testing', 'test pd.merge preserves custom array attributes on columns after merging dataframes on a key', 'test pd.concat preserves custom array attributes on columns when concatenating dataframes axis=1', 'test tm.assert_frame_equal validates dataframe equality including custom extension array attributes']
```

Usage

```
{'create_FloatAttrDtype': 'create a FloatAttrDtype extension dtype for pandas with custom float attribute support', 'build_FloatAttrArray': 'build a FloatAttrArray extension array from a numpy float64 array with optional custom attribute', 'test_from_sequence': 'test the FloatAttrArray._from_sequence method to construct an array from scalar sequences', 'test_concat_same_type': 'test the FloatAttrArray._concat_same_type method to concatenate multiple arrays of the same type', 'test_take_with_fill': 'test the FloatAttrArray.take method with allow_fill and fill_value for indexed element retrieval'}
```

## File: pandas-dev_pandas/pandas/tests/extension/array_with_attr/test_array_with_attr.py

Prompts

```
['create a FloatAttrDtype extension dtype for pandas with custom float attribute support', 'build a FloatAttrArray extension array from a numpy float64 array with optional custom attribute', 'test the FloatAttrArray._from_sequence method to construct an array from scalar sequences', 'test the FloatAttrArray._concat_same_type method to concatenate multiple arrays of the same type', 'test the FloatAttrArray.take method with allow_fill and fill_value for indexed element retrieval', 'test pd.merge and pd.concat preserve custom extension array attributes when merging dataframes with all-NaN columns', 'create a FloatAttrArray instance with NaN data and a custom attribute for extension dtype testing', 'test pd.merge preserves custom array attributes on columns after merging dataframes on a key', 'test pd.concat preserves custom array attributes on columns when concatenating dataframes axis=1', 'test tm.assert_frame_equal validates dataframe equality including custom extension array attributes']
```

Usage

```
{'test_concat_with_all_na': 'test pd.merge and pd.concat preserve custom extension array attributes when merging dataframes with all-NaN columns', 'create_FloatAttrArray': 'create a FloatAttrArray instance with NaN data and a custom attribute for extension dtype testing', 'test_merge_preserves_array_attr': 'test pd.merge preserves custom array attributes on columns after merging dataframes on a key', 'test_concat_preserves_array_attr': 'test pd.concat preserves custom array attributes on columns when concatenating dataframes axis=1', 'test_assert_frame_equal_with_array_attr': 'test tm.assert_frame_equal validates dataframe equality including custom extension array attributes'}
```


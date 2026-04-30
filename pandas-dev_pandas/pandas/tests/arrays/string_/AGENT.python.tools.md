# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/arrays/string_/test_concat.py

Prompts

```
['test concatenating pandas Series with pyarrow and python StringDtype storage backends and NA values', 'test concatenating a StringDtype Series with an object dtype Series results in object dtype', 'test find_common_type between StringDtype and various numpy dtypes including U, S, int64, and StringDType', 'test that pyarrow StringDtype is preferred over python StringDtype when concatenating mixed storage types', 'test that pd.NA is preferred over np.nan as the na_value when concatenating python StringDtype Series', 'test StringDtype equality comparison between python and pyarrow storage backends', 'test repr output of StringArray and ArrowStringArray with different na_value settings', "test that None values are converted to the dtype's na_value in StringArray construction", 'test that setitem on StringArray validates values and raises TypeError for invalid types', 'test roundtrip conversion of datetime and timedelta series to string dtype and back', 'test ArrowStringArray constructor with valid pyarrow large_string and chunked arrays', 'test ArrowStringArray setitem with integer, slice, and boolean indexers', 'test ArrowStringArray._from_sequence converting numpy int, bool, and masked arrays to pyarrow strings', 'test StringDtype config with pyarrow storage option and pd.option_context', 'test ArrowStringArray pickle roundtrip for full and sliced pyarrow-backed string series']
```

Usage

```
{'test_concat_series': 'test concatenating pandas Series with pyarrow and python StringDtype storage backends and NA values', 'test_concat_with_object': 'test concatenating a StringDtype Series with an object dtype Series results in object dtype', 'test_concat_with_numpy': 'test find_common_type between StringDtype and various numpy dtypes including U, S, int64, and StringDType', 'test_pyarrow_preference': 'test that pyarrow StringDtype is preferred over python StringDtype when concatenating mixed storage types', 'test_na_value_preference': 'test that pd.NA is preferred over np.nan as the na_value when concatenating python StringDtype Series'}
```

## File: pandas-dev_pandas/pandas/tests/arrays/string_/test_string.py

Prompts

```
['test concatenating pandas Series with pyarrow and python StringDtype storage backends and NA values', 'test concatenating a StringDtype Series with an object dtype Series results in object dtype', 'test find_common_type between StringDtype and various numpy dtypes including U, S, int64, and StringDType', 'test that pyarrow StringDtype is preferred over python StringDtype when concatenating mixed storage types', 'test that pd.NA is preferred over np.nan as the na_value when concatenating python StringDtype Series', 'test StringDtype equality comparison between python and pyarrow storage backends', 'test repr output of StringArray and ArrowStringArray with different na_value settings', "test that None values are converted to the dtype's na_value in StringArray construction", 'test that setitem on StringArray validates values and raises TypeError for invalid types', 'test roundtrip conversion of datetime and timedelta series to string dtype and back', 'test ArrowStringArray constructor with valid pyarrow large_string and chunked arrays', 'test ArrowStringArray setitem with integer, slice, and boolean indexers', 'test ArrowStringArray._from_sequence converting numpy int, bool, and masked arrays to pyarrow strings', 'test StringDtype config with pyarrow storage option and pd.option_context', 'test ArrowStringArray pickle roundtrip for full and sliced pyarrow-backed string series']
```

Usage

```
{'test_string_dtype_equality': 'test StringDtype equality comparison between python and pyarrow storage backends', 'test_string_array_repr': 'test repr output of StringArray and ArrowStringArray with different na_value settings', 'test_string_array_none_to_nan': "test that None values are converted to the dtype's na_value in StringArray construction", 'test_string_array_setitem_validates': 'test that setitem on StringArray validates values and raises TypeError for invalid types', 'test_string_array_astype_roundtrip': 'test roundtrip conversion of datetime and timedelta series to string dtype and back'}
```

## File: pandas-dev_pandas/pandas/tests/arrays/string_/test_string_arrow.py

Prompts

```
['test concatenating pandas Series with pyarrow and python StringDtype storage backends and NA values', 'test concatenating a StringDtype Series with an object dtype Series results in object dtype', 'test find_common_type between StringDtype and various numpy dtypes including U, S, int64, and StringDType', 'test that pyarrow StringDtype is preferred over python StringDtype when concatenating mixed storage types', 'test that pd.NA is preferred over np.nan as the na_value when concatenating python StringDtype Series', 'test StringDtype equality comparison between python and pyarrow storage backends', 'test repr output of StringArray and ArrowStringArray with different na_value settings', "test that None values are converted to the dtype's na_value in StringArray construction", 'test that setitem on StringArray validates values and raises TypeError for invalid types', 'test roundtrip conversion of datetime and timedelta series to string dtype and back', 'test ArrowStringArray constructor with valid pyarrow large_string and chunked arrays', 'test ArrowStringArray setitem with integer, slice, and boolean indexers', 'test ArrowStringArray._from_sequence converting numpy int, bool, and masked arrays to pyarrow strings', 'test StringDtype config with pyarrow storage option and pd.option_context', 'test ArrowStringArray pickle roundtrip for full and sliced pyarrow-backed string series']
```

Usage

```
{'test_ArrowStringArray_constructor': 'test ArrowStringArray constructor with valid pyarrow large_string and chunked arrays', 'test_ArrowStringArray_setitem': 'test ArrowStringArray setitem with integer, slice, and boolean indexers', 'test_ArrowStringArray_from_sequence': 'test ArrowStringArray._from_sequence converting numpy int, bool, and masked arrays to pyarrow strings', 'test_StringDtype_config': 'test StringDtype config with pyarrow storage option and pd.option_context', 'test_ArrowStringArray_pickle': 'test ArrowStringArray pickle roundtrip for full and sliced pyarrow-backed string series'}
```


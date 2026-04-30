# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/tests/interchange/test_impl.py

Prompts

```
['test the interchange protocol for ordered and unordered pandas categorical dtypes', 'test pyarrow dictionary-encoded categorical conversion via the dataframe interchange protocol', 'test round-trip conversion of a pandas dataframe through the dataframe interchange protocol', 'test pandas nullable dtypes with missing values via pyarrow interchange conversion', 'test buffer dtype metadata for categorical, datetime, string, int, and float columns', 'test the interchange protocol with a dataframe containing a single dtype per column', 'test the interchange protocol with a dataframe containing mixed dtypes including int float boolean and string', 'test the interchange protocol with a categorical column and verify describe_categorical returns is_ordered and is_dictionary', 'test the interchange protocol dataframe api for num_columns num_rows num_chunks column_names and select_columns', 'test the interchange protocol buffer access via __dlpack_device__ and direct memory read of column data', 'test dtype_to_arrow_c_fmt with numpy dtypes like int64, float64, bool and returns their Arrow C format strings', 'test dtype_to_arrow_c_fmt with pandas dtypes like datetime64, categorical and string returning their Arrow C format strings', 'test dtype_to_arrow_c_fmt with pyarrow-backed ArrowDtype including timestamp, duration, decimal and time types', 'test dtype_to_arrow_c_fmt with pyarrow null and binary types returning n and z format strings', 'test dtype_to_arrow_c_fmt with pyarrow timestamp including timezone returning tsn:UTC format string']
```

Usage

```
{'test_categorical_dtype': 'test the interchange protocol for ordered and unordered pandas categorical dtypes', 'test_categorical_pyarrow': 'test pyarrow dictionary-encoded categorical conversion via the dataframe interchange protocol', 'test_from_dataframe': 'test round-trip conversion of a pandas dataframe through the dataframe interchange protocol', 'test_pandas_nullable_with_missing_values': 'test pandas nullable dtypes with missing values via pyarrow interchange conversion', 'test_buffer_dtype_categorical': 'test buffer dtype metadata for categorical, datetime, string, int, and float columns'}
```

## File: pandas-dev_pandas/pandas/tests/interchange/test_spec_conformance.py

Prompts

```
['test the interchange protocol for ordered and unordered pandas categorical dtypes', 'test pyarrow dictionary-encoded categorical conversion via the dataframe interchange protocol', 'test round-trip conversion of a pandas dataframe through the dataframe interchange protocol', 'test pandas nullable dtypes with missing values via pyarrow interchange conversion', 'test buffer dtype metadata for categorical, datetime, string, int, and float columns', 'test the interchange protocol with a dataframe containing a single dtype per column', 'test the interchange protocol with a dataframe containing mixed dtypes including int float boolean and string', 'test the interchange protocol with a categorical column and verify describe_categorical returns is_ordered and is_dictionary', 'test the interchange protocol dataframe api for num_columns num_rows num_chunks column_names and select_columns', 'test the interchange protocol buffer access via __dlpack_device__ and direct memory read of column data', 'test dtype_to_arrow_c_fmt with numpy dtypes like int64, float64, bool and returns their Arrow C format strings', 'test dtype_to_arrow_c_fmt with pandas dtypes like datetime64, categorical and string returning their Arrow C format strings', 'test dtype_to_arrow_c_fmt with pyarrow-backed ArrowDtype including timestamp, duration, decimal and time types', 'test dtype_to_arrow_c_fmt with pyarrow null and binary types returning n and z format strings', 'test dtype_to_arrow_c_fmt with pyarrow timestamp including timezone returning tsn:UTC format string']
```

Usage

```
{'test_only_one_dtype': 'test the interchange protocol with a dataframe containing a single dtype per column', 'test_mixed_dtypes': 'test the interchange protocol with a dataframe containing mixed dtypes including int float boolean and string', 'test_categorical': 'test the interchange protocol with a categorical column and verify describe_categorical returns is_ordered and is_dictionary', 'test_dataframe_operations': 'test the interchange protocol dataframe api for num_columns num_rows num_chunks column_names and select_columns', 'test_buffer_access': 'test the interchange protocol buffer access via __dlpack_device__ and direct memory read of column data'}
```

## File: pandas-dev_pandas/pandas/tests/interchange/test_utils.py

Prompts

```
['test the interchange protocol for ordered and unordered pandas categorical dtypes', 'test pyarrow dictionary-encoded categorical conversion via the dataframe interchange protocol', 'test round-trip conversion of a pandas dataframe through the dataframe interchange protocol', 'test pandas nullable dtypes with missing values via pyarrow interchange conversion', 'test buffer dtype metadata for categorical, datetime, string, int, and float columns', 'test the interchange protocol with a dataframe containing a single dtype per column', 'test the interchange protocol with a dataframe containing mixed dtypes including int float boolean and string', 'test the interchange protocol with a categorical column and verify describe_categorical returns is_ordered and is_dictionary', 'test the interchange protocol dataframe api for num_columns num_rows num_chunks column_names and select_columns', 'test the interchange protocol buffer access via __dlpack_device__ and direct memory read of column data', 'test dtype_to_arrow_c_fmt with numpy dtypes like int64, float64, bool and returns their Arrow C format strings', 'test dtype_to_arrow_c_fmt with pandas dtypes like datetime64, categorical and string returning their Arrow C format strings', 'test dtype_to_arrow_c_fmt with pyarrow-backed ArrowDtype including timestamp, duration, decimal and time types', 'test dtype_to_arrow_c_fmt with pyarrow null and binary types returning n and z format strings', 'test dtype_to_arrow_c_fmt with pyarrow timestamp including timezone returning tsn:UTC format string']
```

Usage

```
{'test_dtype_to_arrow_c_fmt_numpy_dtypes': 'test dtype_to_arrow_c_fmt with numpy dtypes like int64, float64, bool and returns their Arrow C format strings', 'test_dtype_to_arrow_c_fmt_pandas_dtypes': 'test dtype_to_arrow_c_fmt with pandas dtypes like datetime64, categorical and string returning their Arrow C format strings', 'test_dtype_to_arrow_c_fmt_arrow_dtypes': 'test dtype_to_arrow_c_fmt with pyarrow-backed ArrowDtype including timestamp, duration, decimal and time types', 'test_dtype_to_arrow_c_fmt_null_binary': 'test dtype_to_arrow_c_fmt with pyarrow null and binary types returning n and z format strings', 'test_dtype_to_arrow_c_fmt_tz_aware_timestamp': 'test dtype_to_arrow_c_fmt with pyarrow timestamp including timezone returning tsn:UTC format string'}
```


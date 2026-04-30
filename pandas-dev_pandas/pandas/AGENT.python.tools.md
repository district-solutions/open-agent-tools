# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/_typing.py

Prompts

```
['create a protocol class that defines sequence-like behavior excluding strings and bytes for typed indexing', 'create a base buffer protocol defining mode, seek, seekable, and tell methods for file-like objects', 'create a CSV read buffer protocol extending ReadBuffer with iter, fileno, readline, and closed property', 'create an Arrow array export protocol requiring __arrow_c_array__ for zero-copy Arrow data interchange', 'create an Arrow stream export protocol requiring __arrow_c_stream__ for zero-copy Arrow stream data interchange', 'test pandas Index objects with many types including datetime, categorical, interval, and multiindex variants', 'test pandas dtypes including string, float, int, complex, nullable, and pyarrow-backed types', 'test pandas Series and DataFrame fixtures with pre-built data and various index types', 'test pandas arithmetic, comparison, and logical operators with parameterized dunder methods', 'test pandas timezone handling with naive, aware, UTC, and pytz timezone variants']
```

Usage

```
{'create_protocol_SequenceNotStr': 'create a protocol class that defines sequence-like behavior excluding strings and bytes for typed indexing', 'create_protocol_BaseBuffer': 'create a base buffer protocol defining mode, seek, seekable, and tell methods for file-like objects', 'create_protocol_ReadCsvBuffer': 'create a CSV read buffer protocol extending ReadBuffer with iter, fileno, readline, and closed property', 'create_protocol_ArrowArrayExportable': 'create an Arrow array export protocol requiring __arrow_c_array__ for zero-copy Arrow data interchange', 'create_protocol_ArrowStreamExportable': 'create an Arrow stream export protocol requiring __arrow_c_stream__ for zero-copy Arrow stream data interchange'}
```

## File: pandas-dev_pandas/pandas/conftest.py

Prompts

```
['create a protocol class that defines sequence-like behavior excluding strings and bytes for typed indexing', 'create a base buffer protocol defining mode, seek, seekable, and tell methods for file-like objects', 'create a CSV read buffer protocol extending ReadBuffer with iter, fileno, readline, and closed property', 'create an Arrow array export protocol requiring __arrow_c_array__ for zero-copy Arrow data interchange', 'create an Arrow stream export protocol requiring __arrow_c_stream__ for zero-copy Arrow stream data interchange', 'test pandas Index objects with many types including datetime, categorical, interval, and multiindex variants', 'test pandas dtypes including string, float, int, complex, nullable, and pyarrow-backed types', 'test pandas Series and DataFrame fixtures with pre-built data and various index types', 'test pandas arithmetic, comparison, and logical operators with parameterized dunder methods', 'test pandas timezone handling with naive, aware, UTC, and pytz timezone variants']
```

Usage

```
{'test_index_fixture': 'test pandas Index objects with many types including datetime, categorical, interval, and multiindex variants', 'test_dtype_fixture': 'test pandas dtypes including string, float, int, complex, nullable, and pyarrow-backed types', 'test_series_dataframe_fixture': 'test pandas Series and DataFrame fixtures with pre-built data and various index types', 'test_operator_fixture': 'test pandas arithmetic, comparison, and logical operators with parameterized dunder methods', 'test_timezone_fixture': 'test pandas timezone handling with naive, aware, UTC, and pytz timezone variants'}
```


# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/_utils/construction/dataframe.py

Prompts

```
['build a DataFrame from a dictionary of sequences with optional schema overrides and strict type enforcement', 'build a DataFrame from a sequence of rows or columns with automatic orientation inference', 'build a Polars DataFrame from a pandas DataFrame with optional index inclusion and type casting', 'build a Polars DataFrame from an Arrow Table or RecordBatch with schema renaming and rechunking', 'build a Polars DataFrame from a NumPy ndarray with row or column orientation and structured array support', 'convert a pandas Series or Index to a PyArrow Array with NaN-to-null handling', 'coerce a multi-chunk PyArrow dictionary array to use uint32 keys and combine chunks', 'test the pandas_series_to_arrow function with object dtype and string values', 'refactor the coerce_arrow function to support additional small integer index types', 'review the pandas_series_to_arrow function for handling duplicate column edge cases', 'create a Polars Series from a Python sequence with optional dtype and strict mode', 'build a Polars Series from an iterable or generator with chunked processing', 'create a Polars Series from a NumPy array with automatic dtype inference', 'build a Polars Series from a pandas Series or DatetimeIndex via Arrow conversion', 'create a Polars Series from an Arrow array with optional rechunking and dtype casting', 'test the is_namedtuple function to check if a class derives from NamedTuple', 'test the is_pydantic_model function to check if a value derives from pydantic.BaseModel', 'test the is_sqlalchemy_row function to check if a value is a SQLAlchemy sequence or mapping object', 'test the contains_nested function to determine if a value contains nested structured data', 'test the is_simple_numpy_backed_pandas_series function to check if a pandas series uses simple numpy dtypes']
```

Usage

```
{'build_dataframe_from_dict': 'build a DataFrame from a dictionary of sequences with optional schema overrides and strict type enforcement', 'build_dataframe_from_sequence': 'build a DataFrame from a sequence of rows or columns with automatic orientation inference', 'build_dataframe_from_pandas': 'build a Polars DataFrame from a pandas DataFrame with optional index inclusion and type casting', 'build_dataframe_from_arrow': 'build a Polars DataFrame from an Arrow Table or RecordBatch with schema renaming and rechunking', 'build_dataframe_from_numpy': 'build a Polars DataFrame from a NumPy ndarray with row or column orientation and structured array support'}
```

## File: pola-rs_polars/py-polars/src/polars/_utils/construction/other.py

Prompts

```
['build a DataFrame from a dictionary of sequences with optional schema overrides and strict type enforcement', 'build a DataFrame from a sequence of rows or columns with automatic orientation inference', 'build a Polars DataFrame from a pandas DataFrame with optional index inclusion and type casting', 'build a Polars DataFrame from an Arrow Table or RecordBatch with schema renaming and rechunking', 'build a Polars DataFrame from a NumPy ndarray with row or column orientation and structured array support', 'convert a pandas Series or Index to a PyArrow Array with NaN-to-null handling', 'coerce a multi-chunk PyArrow dictionary array to use uint32 keys and combine chunks', 'test the pandas_series_to_arrow function with object dtype and string values', 'refactor the coerce_arrow function to support additional small integer index types', 'review the pandas_series_to_arrow function for handling duplicate column edge cases', 'create a Polars Series from a Python sequence with optional dtype and strict mode', 'build a Polars Series from an iterable or generator with chunked processing', 'create a Polars Series from a NumPy array with automatic dtype inference', 'build a Polars Series from a pandas Series or DatetimeIndex via Arrow conversion', 'create a Polars Series from an Arrow array with optional rechunking and dtype casting', 'test the is_namedtuple function to check if a class derives from NamedTuple', 'test the is_pydantic_model function to check if a value derives from pydantic.BaseModel', 'test the is_sqlalchemy_row function to check if a value is a SQLAlchemy sequence or mapping object', 'test the contains_nested function to determine if a value contains nested structured data', 'test the is_simple_numpy_backed_pandas_series function to check if a pandas series uses simple numpy dtypes']
```

Usage

```
{'convert_pandas_series_to_arrow': 'convert a pandas Series or Index to a PyArrow Array with NaN-to-null handling', 'coerce_arrow_dictionary_chunks': 'coerce a multi-chunk PyArrow dictionary array to use uint32 keys and combine chunks', 'test_pandas_series_to_arrow': 'test the pandas_series_to_arrow function with object dtype and string values', 'refactor_coerce_arrow': 'refactor the coerce_arrow function to support additional small integer index types', 'review_pandas_series_to_arrow': 'review the pandas_series_to_arrow function for handling duplicate column edge cases'}
```

## File: pola-rs_polars/py-polars/src/polars/_utils/construction/series.py

Prompts

```
['build a DataFrame from a dictionary of sequences with optional schema overrides and strict type enforcement', 'build a DataFrame from a sequence of rows or columns with automatic orientation inference', 'build a Polars DataFrame from a pandas DataFrame with optional index inclusion and type casting', 'build a Polars DataFrame from an Arrow Table or RecordBatch with schema renaming and rechunking', 'build a Polars DataFrame from a NumPy ndarray with row or column orientation and structured array support', 'convert a pandas Series or Index to a PyArrow Array with NaN-to-null handling', 'coerce a multi-chunk PyArrow dictionary array to use uint32 keys and combine chunks', 'test the pandas_series_to_arrow function with object dtype and string values', 'refactor the coerce_arrow function to support additional small integer index types', 'review the pandas_series_to_arrow function for handling duplicate column edge cases', 'create a Polars Series from a Python sequence with optional dtype and strict mode', 'build a Polars Series from an iterable or generator with chunked processing', 'create a Polars Series from a NumPy array with automatic dtype inference', 'build a Polars Series from a pandas Series or DatetimeIndex via Arrow conversion', 'create a Polars Series from an Arrow array with optional rechunking and dtype casting', 'test the is_namedtuple function to check if a class derives from NamedTuple', 'test the is_pydantic_model function to check if a value derives from pydantic.BaseModel', 'test the is_sqlalchemy_row function to check if a value is a SQLAlchemy sequence or mapping object', 'test the contains_nested function to determine if a value contains nested structured data', 'test the is_simple_numpy_backed_pandas_series function to check if a pandas series uses simple numpy dtypes']
```

Usage

```
{'create_series_from_sequence': 'create a Polars Series from a Python sequence with optional dtype and strict mode', 'build_series_from_iterable': 'build a Polars Series from an iterable or generator with chunked processing', 'create_series_from_numpy': 'create a Polars Series from a NumPy array with automatic dtype inference', 'build_series_from_pandas': 'build a Polars Series from a pandas Series or DatetimeIndex via Arrow conversion', 'create_series_from_arrow': 'create a Polars Series from an Arrow array with optional rechunking and dtype casting'}
```

## File: pola-rs_polars/py-polars/src/polars/_utils/construction/utils.py

Prompts

```
['build a DataFrame from a dictionary of sequences with optional schema overrides and strict type enforcement', 'build a DataFrame from a sequence of rows or columns with automatic orientation inference', 'build a Polars DataFrame from a pandas DataFrame with optional index inclusion and type casting', 'build a Polars DataFrame from an Arrow Table or RecordBatch with schema renaming and rechunking', 'build a Polars DataFrame from a NumPy ndarray with row or column orientation and structured array support', 'convert a pandas Series or Index to a PyArrow Array with NaN-to-null handling', 'coerce a multi-chunk PyArrow dictionary array to use uint32 keys and combine chunks', 'test the pandas_series_to_arrow function with object dtype and string values', 'refactor the coerce_arrow function to support additional small integer index types', 'review the pandas_series_to_arrow function for handling duplicate column edge cases', 'create a Polars Series from a Python sequence with optional dtype and strict mode', 'build a Polars Series from an iterable or generator with chunked processing', 'create a Polars Series from a NumPy array with automatic dtype inference', 'build a Polars Series from a pandas Series or DatetimeIndex via Arrow conversion', 'create a Polars Series from an Arrow array with optional rechunking and dtype casting', 'test the is_namedtuple function to check if a class derives from NamedTuple', 'test the is_pydantic_model function to check if a value derives from pydantic.BaseModel', 'test the is_sqlalchemy_row function to check if a value is a SQLAlchemy sequence or mapping object', 'test the contains_nested function to determine if a value contains nested structured data', 'test the is_simple_numpy_backed_pandas_series function to check if a pandas series uses simple numpy dtypes']
```

Usage

```
{'test_is_namedtuple': 'test the is_namedtuple function to check if a class derives from NamedTuple', 'test_is_pydantic_model': 'test the is_pydantic_model function to check if a value derives from pydantic.BaseModel', 'test_is_sqlalchemy_row': 'test the is_sqlalchemy_row function to check if a value is a SQLAlchemy sequence or mapping object', 'test_contains_nested': 'test the contains_nested function to determine if a value contains nested structured data', 'test_is_simple_numpy_backed_pandas_series': 'test the is_simple_numpy_backed_pandas_series function to check if a pandas series uses simple numpy dtypes'}
```


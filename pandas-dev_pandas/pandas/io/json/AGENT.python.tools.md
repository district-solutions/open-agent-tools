# Agent Python Tools

- repo: pandas-dev/pandas
- repo_uri: https://github.com/pandas-dev/pandas.git

## File: pandas-dev_pandas/pandas/io/json/_json.py

Prompts

```
['create a function that serializes a pandas DataFrame or Series to a JSON string or file', 'create a function that reads a JSON string or file and returns a pandas DataFrame or Series', 'build an iterator that reads line-delimited JSON files in chunksize increments', 'test the FrameParser class that parses split-format JSON documents into DataFrames', 'review the JSONTableWriter class that writes DataFrames with Table Schema metadata to JSON', 'normalize semi-structured JSON data into a flat pandas DataFrame with nested dict expansion', 'normalize JSON data extracting nested record paths and metadata fields into a flat table', 'flatten a nested dictionary into a flat dict with dot-separated keys for nested values', 'convert a JSON array string into line-delimited JSON format', 'normalize nested JSON data up to a specified maximum depth level', 'build a table schema dictionary from a pandas DataFrame or Series with optional index and primary key', 'create a DataFrame from a JSON table schema string with type conversion and index restoration', 'create a JSON field descriptor dictionary from a pandas Series with dtype, name, and constraints', 'test converting a JSON field descriptor back to a pandas dtype string or CategoricalDtype', 'summarize how a NumPy or pandas dtype maps to a Table Schema type string']
```

Usage

```
{'create_function_to_json': 'create a function that serializes a pandas DataFrame or Series to a JSON string or file', 'create_function_read_json': 'create a function that reads a JSON string or file and returns a pandas DataFrame or Series', 'build_json_reader_iterator': 'build an iterator that reads line-delimited JSON files in chunksize increments', 'test_parser_orient_split': 'test the FrameParser class that parses split-format JSON documents into DataFrames', 'review_json_table_writer': 'review the JSONTableWriter class that writes DataFrames with Table Schema metadata to JSON'}
```

## File: pandas-dev_pandas/pandas/io/json/_normalize.py

Prompts

```
['create a function that serializes a pandas DataFrame or Series to a JSON string or file', 'create a function that reads a JSON string or file and returns a pandas DataFrame or Series', 'build an iterator that reads line-delimited JSON files in chunksize increments', 'test the FrameParser class that parses split-format JSON documents into DataFrames', 'review the JSONTableWriter class that writes DataFrames with Table Schema metadata to JSON', 'normalize semi-structured JSON data into a flat pandas DataFrame with nested dict expansion', 'normalize JSON data extracting nested record paths and metadata fields into a flat table', 'flatten a nested dictionary into a flat dict with dot-separated keys for nested values', 'convert a JSON array string into line-delimited JSON format', 'normalize nested JSON data up to a specified maximum depth level', 'build a table schema dictionary from a pandas DataFrame or Series with optional index and primary key', 'create a DataFrame from a JSON table schema string with type conversion and index restoration', 'create a JSON field descriptor dictionary from a pandas Series with dtype, name, and constraints', 'test converting a JSON field descriptor back to a pandas dtype string or CategoricalDtype', 'summarize how a NumPy or pandas dtype maps to a Table Schema type string']
```

Usage

```
{'normalize_json_to_dataframe': 'normalize semi-structured JSON data into a flat pandas DataFrame with nested dict expansion', 'normalize_json_with_record_path': 'normalize JSON data extracting nested record paths and metadata fields into a flat table', 'flatten_nested_dict_to_record': 'flatten a nested dictionary into a flat dict with dot-separated keys for nested values', 'convert_json_list_to_line_delimited': 'convert a JSON array string into line-delimited JSON format', 'normalize_json_with_max_depth': 'normalize nested JSON data up to a specified maximum depth level'}
```

## File: pandas-dev_pandas/pandas/io/json/_table_schema.py

Prompts

```
['create a function that serializes a pandas DataFrame or Series to a JSON string or file', 'create a function that reads a JSON string or file and returns a pandas DataFrame or Series', 'build an iterator that reads line-delimited JSON files in chunksize increments', 'test the FrameParser class that parses split-format JSON documents into DataFrames', 'review the JSONTableWriter class that writes DataFrames with Table Schema metadata to JSON', 'normalize semi-structured JSON data into a flat pandas DataFrame with nested dict expansion', 'normalize JSON data extracting nested record paths and metadata fields into a flat table', 'flatten a nested dictionary into a flat dict with dot-separated keys for nested values', 'convert a JSON array string into line-delimited JSON format', 'normalize nested JSON data up to a specified maximum depth level', 'build a table schema dictionary from a pandas DataFrame or Series with optional index and primary key', 'create a DataFrame from a JSON table schema string with type conversion and index restoration', 'create a JSON field descriptor dictionary from a pandas Series with dtype, name, and constraints', 'test converting a JSON field descriptor back to a pandas dtype string or CategoricalDtype', 'summarize how a NumPy or pandas dtype maps to a Table Schema type string']
```

Usage

```
{'build_build_table_schema': 'build a table schema dictionary from a pandas DataFrame or Series with optional index and primary key', 'create_parse_table_schema': 'create a DataFrame from a JSON table schema string with type conversion and index restoration', 'create_convert_pandas_type_to_json_field': 'create a JSON field descriptor dictionary from a pandas Series with dtype, name, and constraints', 'test_convert_json_field_to_pandas_type': 'test converting a JSON field descriptor back to a pandas dtype string or CategoricalDtype', 'summarize_as_json_table_type': 'summarize how a NumPy or pandas dtype maps to a Table Schema type string'}
```


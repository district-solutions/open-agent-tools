# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/convert/general.py

Prompts

```
['create a DataFrame from a dictionary of sequences using from_dict with column names and values', 'build a DataFrame from a sequence of dictionaries with optional schema and schema_overrides parameters', 'create a DataFrame from a sequence of sequences (records) with orient and schema parameters', 'build a DataFrame from a NumPy ndarray with optional schema and orientation', 'create a DataFrame from a PyTorch Tensor with optional schema, orientation, and force parameters', 'build a DataFrame or Series from a PyArrow Table, Array, or RecordBatch with rechunk option', 'create a DataFrame or Series from a pandas DataFrame or Series with nan_to_null and include_index options', 'build a DataFrame or Series from its string representation using from_repr', 'create a Polars DataFrame from any object supporting the PyCapsule Interface or Dataframe Interchange Protocol', 'normalize semi-structured JSON data into a flat Polars DataFrame with nested keys separated by dots', 'normalize nested JSON data to a specific depth using max_level to control recursion depth', 'normalize JSON data using a custom separator string instead of the default dot separator', 'normalize JSON data using a custom JSON encoder like orjson for binary encoding of nested dicts', 'normalize an empty JSON sequence and return an empty Polars DataFrame with an optional schema']
```

Usage

```
{'create_dataframe_from_dict': 'create a DataFrame from a dictionary of sequences using from_dict with column names and values', 'create_dataframe_from_dicts': 'build a DataFrame from a sequence of dictionaries with optional schema and schema_overrides parameters', 'create_dataframe_from_records': 'create a DataFrame from a sequence of sequences (records) with orient and schema parameters', 'create_dataframe_from_numpy': 'build a DataFrame from a NumPy ndarray with optional schema and orientation', 'create_dataframe_from_torch': 'create a DataFrame from a PyTorch Tensor with optional schema, orientation, and force parameters', 'create_dataframe_from_arrow': 'build a DataFrame or Series from a PyArrow Table, Array, or RecordBatch with rechunk option', 'create_dataframe_from_pandas': 'create a DataFrame or Series from a pandas DataFrame or Series with nan_to_null and include_index options', 'create_dataframe_from_repr': 'build a DataFrame or Series from its string representation using from_repr', 'create_dataframe_from_interchange': 'create a Polars DataFrame from any object supporting the PyCapsule Interface or Dataframe Interchange Protocol'}
```

## File: pola-rs_polars/py-polars/src/polars/convert/normalize.py

Prompts

```
['create a DataFrame from a dictionary of sequences using from_dict with column names and values', 'build a DataFrame from a sequence of dictionaries with optional schema and schema_overrides parameters', 'create a DataFrame from a sequence of sequences (records) with orient and schema parameters', 'build a DataFrame from a NumPy ndarray with optional schema and orientation', 'create a DataFrame from a PyTorch Tensor with optional schema, orientation, and force parameters', 'build a DataFrame or Series from a PyArrow Table, Array, or RecordBatch with rechunk option', 'create a DataFrame or Series from a pandas DataFrame or Series with nan_to_null and include_index options', 'build a DataFrame or Series from its string representation using from_repr', 'create a Polars DataFrame from any object supporting the PyCapsule Interface or Dataframe Interchange Protocol', 'normalize semi-structured JSON data into a flat Polars DataFrame with nested keys separated by dots', 'normalize nested JSON data to a specific depth using max_level to control recursion depth', 'normalize JSON data using a custom separator string instead of the default dot separator', 'normalize JSON data using a custom JSON encoder like orjson for binary encoding of nested dicts', 'normalize an empty JSON sequence and return an empty Polars DataFrame with an optional schema']
```

Usage

```
{'normalize_json_data': 'normalize semi-structured JSON data into a flat Polars DataFrame with nested keys separated by dots', 'normalize_json_with_max_level': 'normalize nested JSON data to a specific depth using max_level to control recursion depth', 'normalize_json_with_custom_separator': 'normalize JSON data using a custom separator string instead of the default dot separator', 'normalize_json_with_custom_encoder': 'normalize JSON data using a custom JSON encoder like orjson for binary encoding of nested dicts', 'normalize_empty_json_data': 'normalize an empty JSON sequence and return an empty Polars DataFrame with an optional schema'}
```


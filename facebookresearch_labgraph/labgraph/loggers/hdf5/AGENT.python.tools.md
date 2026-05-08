# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/loggers/hdf5/logger.py

Prompts

```
['build a python module that uses HDF5Logger to write labgraph messages to an HDF5 file', 'create an HDF5Logger instance and call setup to open a new HDF5 file for writing', 'test the HDF5Logger write method to persist messages by logging ID into HDF5 datasets', 'refactor get_numpy_type_for_field_type to support additional labgraph field types for numpy conversion', 'review the HDF5Logger cleanup method to ensure the HDF5 file is properly closed and flushed', 'create an HDF5Reader instance with a file path and log types dict to read HDF5 log data', 'access the logs property on an HDF5Reader to parse and retrieve deserialized Message objects from the HDF5 file', 'call get_deserialized_value with a raw value and FieldType to convert HDF5 raw data to the correct Python type', 'review the HDF5Reader class and its lazy parsing approach that defers file I/O until the logs property is accessed', 'summarize the get_deserialized_value function which handles BoolType, BytesType, FloatType, IntEnumType, IntType, NumpyType, and StrType deserialization']
```

Usage

```
{'build_HDF5Logger': 'build a python module that uses HDF5Logger to write labgraph messages to an HDF5 file', 'create_HDF5Logger_setup': 'create an HDF5Logger instance and call setup to open a new HDF5 file for writing', 'test_HDF5Logger_write': 'test the HDF5Logger write method to persist messages by logging ID into HDF5 datasets', 'refactor_get_numpy_type_for_field_type': 'refactor get_numpy_type_for_field_type to support additional labgraph field types for numpy conversion', 'review_HDF5Logger_cleanup': 'review the HDF5Logger cleanup method to ensure the HDF5 file is properly closed and flushed'}
```

## File: facebookresearch_labgraph/labgraph/loggers/hdf5/reader.py

Prompts

```
['build a python module that uses HDF5Logger to write labgraph messages to an HDF5 file', 'create an HDF5Logger instance and call setup to open a new HDF5 file for writing', 'test the HDF5Logger write method to persist messages by logging ID into HDF5 datasets', 'refactor get_numpy_type_for_field_type to support additional labgraph field types for numpy conversion', 'review the HDF5Logger cleanup method to ensure the HDF5 file is properly closed and flushed', 'create an HDF5Reader instance with a file path and log types dict to read HDF5 log data', 'access the logs property on an HDF5Reader to parse and retrieve deserialized Message objects from the HDF5 file', 'call get_deserialized_value with a raw value and FieldType to convert HDF5 raw data to the correct Python type', 'review the HDF5Reader class and its lazy parsing approach that defers file I/O until the logs property is accessed', 'summarize the get_deserialized_value function which handles BoolType, BytesType, FloatType, IntEnumType, IntType, NumpyType, and StrType deserialization']
```

Usage

```
{'read_hdf5_logs': 'create an HDF5Reader instance with a file path and log types dict to read HDF5 log data', 'parse_hdf5_messages': 'access the logs property on an HDF5Reader to parse and retrieve deserialized Message objects from the HDF5 file', 'deserialize_field_value': 'call get_deserialized_value with a raw value and FieldType to convert HDF5 raw data to the correct Python type', 'review_HDF5Reader_class': 'review the HDF5Reader class and its lazy parsing approach that defers file I/O until the logs property is accessed', 'summarize_get_deserialized_value': 'summarize the get_deserialized_value function which handles BoolType, BytesType, FloatType, IntEnumType, IntType, NumpyType, and StrType deserialization'}
```


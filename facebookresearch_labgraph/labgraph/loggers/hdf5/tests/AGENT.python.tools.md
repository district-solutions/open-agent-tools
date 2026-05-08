# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/loggers/hdf5/tests/test_logger.py

Prompts

```
['test that messages written to an HDF5 file can be read back and verified', 'test the HDF5 logger handles StrType, StrDynamicType, and DynamicType field types correctly', 'test the HDF5 logger preprocesses and postprocesses SERIALIZABLE_DYNAMIC_TYPES like ListType and DataclassType', 'test that string fields are decoded using the correct encoding from StrType or StrDynamicType', 'test that DynamicType fields excluding StrDynamicType are compared as raw bytes', 'test the HDF5Reader class by reading back logged messages from an HDF5 file and verifying field values', 'run the test_hdf5_reader function to validate HDF5Reader correctly parses all message field types from an HDF5 file', 'review the HDF5Reader class and its logs property that lazily parses HDF5 files into typed Message lists', 'review the get_deserialized_value function that converts raw HDF5 values into Python types based on field type', 'refactor the test_hdf5_reader function to add assertions for additional field types or edge cases', 'write synthetic labgraph messages with all field types to an HDF5 file using a Logger subclass', 'create a MyMessage instance with int, str, float, bool, bytes, enum, list, dict, and dataclass fields', 'test the MyIntEnum class with integer-backed enum values A equals 1 and B equals 2', 'test the MyStrEnum class with string-backed enum values A and B', 'review the MyDataclass dataclass with sub_int_field and sub_str_field for nested message serialization']
```

Usage

```
{'test_hdf5_logger_write_read': 'test that messages written to an HDF5 file can be read back and verified', 'test_hdf5_logger_field_types': 'test the HDF5 logger handles StrType, StrDynamicType, and DynamicType field types correctly', 'test_hdf5_logger_serializable_dynamic': 'test the HDF5 logger preprocesses and postprocesses SERIALIZABLE_DYNAMIC_TYPES like ListType and DataclassType', 'test_hdf5_logger_string_encoding': 'test that string fields are decoded using the correct encoding from StrType or StrDynamicType', 'test_hdf5_logger_dynamic_bytes': 'test that DynamicType fields excluding StrDynamicType are compared as raw bytes'}
```

## File: facebookresearch_labgraph/labgraph/loggers/hdf5/tests/test_reader.py

Prompts

```
['test that messages written to an HDF5 file can be read back and verified', 'test the HDF5 logger handles StrType, StrDynamicType, and DynamicType field types correctly', 'test the HDF5 logger preprocesses and postprocesses SERIALIZABLE_DYNAMIC_TYPES like ListType and DataclassType', 'test that string fields are decoded using the correct encoding from StrType or StrDynamicType', 'test that DynamicType fields excluding StrDynamicType are compared as raw bytes', 'test the HDF5Reader class by reading back logged messages from an HDF5 file and verifying field values', 'run the test_hdf5_reader function to validate HDF5Reader correctly parses all message field types from an HDF5 file', 'review the HDF5Reader class and its logs property that lazily parses HDF5 files into typed Message lists', 'review the get_deserialized_value function that converts raw HDF5 values into Python types based on field type', 'refactor the test_hdf5_reader function to add assertions for additional field types or edge cases', 'write synthetic labgraph messages with all field types to an HDF5 file using a Logger subclass', 'create a MyMessage instance with int, str, float, bool, bytes, enum, list, dict, and dataclass fields', 'test the MyIntEnum class with integer-backed enum values A equals 1 and B equals 2', 'test the MyStrEnum class with string-backed enum values A and B', 'review the MyDataclass dataclass with sub_int_field and sub_str_field for nested message serialization']
```

Usage

```
{'test_hdf5_reader': 'test the HDF5Reader class by reading back logged messages from an HDF5 file and verifying field values', 'run_hdf5_reader_test': 'run the test_hdf5_reader function to validate HDF5Reader correctly parses all message field types from an HDF5 file', 'review_hdf5reader_class': 'review the HDF5Reader class and its logs property that lazily parses HDF5 files into typed Message lists', 'review_get_deserialized_value': 'review the get_deserialized_value function that converts raw HDF5 values into Python types based on field type', 'refactor_hdf5_reader_test': 'refactor the test_hdf5_reader function to add assertions for additional field types or edge cases'}
```

## File: facebookresearch_labgraph/labgraph/loggers/hdf5/tests/test_utils.py

Prompts

```
['test that messages written to an HDF5 file can be read back and verified', 'test the HDF5 logger handles StrType, StrDynamicType, and DynamicType field types correctly', 'test the HDF5 logger preprocesses and postprocesses SERIALIZABLE_DYNAMIC_TYPES like ListType and DataclassType', 'test that string fields are decoded using the correct encoding from StrType or StrDynamicType', 'test that DynamicType fields excluding StrDynamicType are compared as raw bytes', 'test the HDF5Reader class by reading back logged messages from an HDF5 file and verifying field values', 'run the test_hdf5_reader function to validate HDF5Reader correctly parses all message field types from an HDF5 file', 'review the HDF5Reader class and its logs property that lazily parses HDF5 files into typed Message lists', 'review the get_deserialized_value function that converts raw HDF5 values into Python types based on field type', 'refactor the test_hdf5_reader function to add assertions for additional field types or edge cases', 'write synthetic labgraph messages with all field types to an HDF5 file using a Logger subclass', 'create a MyMessage instance with int, str, float, bool, bytes, enum, list, dict, and dataclass fields', 'test the MyIntEnum class with integer-backed enum values A equals 1 and B equals 2', 'test the MyStrEnum class with string-backed enum values A and B', 'review the MyDataclass dataclass with sub_int_field and sub_str_field for nested message serialization']
```

Usage

```
{'write_logs_to_hdf5': 'write synthetic labgraph messages with all field types to an HDF5 file using a Logger subclass', 'create_MyMessage': 'create a MyMessage instance with int, str, float, bool, bytes, enum, list, dict, and dataclass fields', 'test_MyIntEnum': 'test the MyIntEnum class with integer-backed enum values A equals 1 and B equals 2', 'test_MyStrEnum': 'test the MyStrEnum class with string-backed enum values A and B', 'review_MyDataclass': 'review the MyDataclass dataclass with sub_int_field and sub_str_field for nested message serialization'}
```


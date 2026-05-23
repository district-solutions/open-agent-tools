# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/helper.py

Prompts

```
['create a FooEnvironment instance initialized with a dictionary of key-value string pairs', 'get a value from FooEnvironment by key using the get method', 'use maybe_get on FooEnvironment to retrieve a value with a fallback default', 'set a key-value pair in FooEnvironment and check existence with has', 'iterate over FooEnvironment to yield all key-value tuples as an iterator', 'test the set_dtype context manager to temporarily change the default tensor dtype within a scoped block', 'test the get_current_dtype function to retrieve the current thread-local floating-point data type', 'test nested set_dtype context managers to verify dtype scoping and restoration after exiting each scope', 'test the DataTypeContext abstract class interface for getting and setting the current floating-point data type', 'test that tensors created outside any set_dtype scope default to torch.float32 as the standard dtype', 'test FSspecFileSystem open method to read and write binary files using FileMode enum', 'test FSspecFileSystem open_text method to read and write text files with utf-8 encoding', 'test FSspecFileSystem glob method to find files matching a wildcard pattern in a directory', 'test GlobalFileSystem to verify it delegates local path operations through the FileSystemRegistry dispatch chain', 'test FSspecFileSystem get_short_uri and get_long_uri to strip and add URI prefixes from paths', 'create fake gangs for a given device to use in unit tests', 'get the current gangs active in the present context scope', 'get the default gangs that were set globally before context changes', 'set the default gangs globally so all new contexts inherit them', 'use set_gangs as a context manager to temporarily override current gangs']
```

Usage

```
{'create_FooEnvironment_with_data': 'create a FooEnvironment instance initialized with a dictionary of key-value string pairs', 'get_value_from_FooEnvironment': 'get a value from FooEnvironment by key using the get method', 'maybe_get_with_default': 'use maybe_get on FooEnvironment to retrieve a value with a fallback default', 'set_and_check_FooEnvironment': 'set a key-value pair in FooEnvironment and check existence with has', 'iterate_FooEnvironment': 'iterate over FooEnvironment to yield all key-value tuples as an iterator'}
```

## File: facebookresearch_fairseq2/tests/unit/test_data_type.py

Prompts

```
['create a FooEnvironment instance initialized with a dictionary of key-value string pairs', 'get a value from FooEnvironment by key using the get method', 'use maybe_get on FooEnvironment to retrieve a value with a fallback default', 'set a key-value pair in FooEnvironment and check existence with has', 'iterate over FooEnvironment to yield all key-value tuples as an iterator', 'test the set_dtype context manager to temporarily change the default tensor dtype within a scoped block', 'test the get_current_dtype function to retrieve the current thread-local floating-point data type', 'test nested set_dtype context managers to verify dtype scoping and restoration after exiting each scope', 'test the DataTypeContext abstract class interface for getting and setting the current floating-point data type', 'test that tensors created outside any set_dtype scope default to torch.float32 as the standard dtype', 'test FSspecFileSystem open method to read and write binary files using FileMode enum', 'test FSspecFileSystem open_text method to read and write text files with utf-8 encoding', 'test FSspecFileSystem glob method to find files matching a wildcard pattern in a directory', 'test GlobalFileSystem to verify it delegates local path operations through the FileSystemRegistry dispatch chain', 'test FSspecFileSystem get_short_uri and get_long_uri to strip and add URI prefixes from paths', 'create fake gangs for a given device to use in unit tests', 'get the current gangs active in the present context scope', 'get the default gangs that were set globally before context changes', 'set the default gangs globally so all new contexts inherit them', 'use set_gangs as a context manager to temporarily override current gangs']
```

Usage

```
{'test_set_dtype_context_manager': 'test the set_dtype context manager to temporarily change the default tensor dtype within a scoped block', 'test_get_current_dtype': 'test the get_current_dtype function to retrieve the current thread-local floating-point data type', 'test_nested_set_dtype_scopes': 'test nested set_dtype context managers to verify dtype scoping and restoration after exiting each scope', 'test_datatype_context_abstraction': 'test the DataTypeContext abstract class interface for getting and setting the current floating-point data type', 'test_default_dtype_fallback': 'test that tensors created outside any set_dtype scope default to torch.float32 as the standard dtype'}
```

## File: facebookresearch_fairseq2/tests/unit/test_file_system.py

Prompts

```
['create a FooEnvironment instance initialized with a dictionary of key-value string pairs', 'get a value from FooEnvironment by key using the get method', 'use maybe_get on FooEnvironment to retrieve a value with a fallback default', 'set a key-value pair in FooEnvironment and check existence with has', 'iterate over FooEnvironment to yield all key-value tuples as an iterator', 'test the set_dtype context manager to temporarily change the default tensor dtype within a scoped block', 'test the get_current_dtype function to retrieve the current thread-local floating-point data type', 'test nested set_dtype context managers to verify dtype scoping and restoration after exiting each scope', 'test the DataTypeContext abstract class interface for getting and setting the current floating-point data type', 'test that tensors created outside any set_dtype scope default to torch.float32 as the standard dtype', 'test FSspecFileSystem open method to read and write binary files using FileMode enum', 'test FSspecFileSystem open_text method to read and write text files with utf-8 encoding', 'test FSspecFileSystem glob method to find files matching a wildcard pattern in a directory', 'test GlobalFileSystem to verify it delegates local path operations through the FileSystemRegistry dispatch chain', 'test FSspecFileSystem get_short_uri and get_long_uri to strip and add URI prefixes from paths', 'create fake gangs for a given device to use in unit tests', 'get the current gangs active in the present context scope', 'get the default gangs that were set globally before context changes', 'set the default gangs globally so all new contexts inherit them', 'use set_gangs as a context manager to temporarily override current gangs']
```

Usage

```
{'test_FSspecFileSystem_open': 'test FSspecFileSystem open method to read and write binary files using FileMode enum', 'test_FSspecFileSystem_open_text': 'test FSspecFileSystem open_text method to read and write text files with utf-8 encoding', 'test_FSspecFileSystem_glob': 'test FSspecFileSystem glob method to find files matching a wildcard pattern in a directory', 'test_GlobalFileSystem_delegation': 'test GlobalFileSystem to verify it delegates local path operations through the FileSystemRegistry dispatch chain', 'test_FSspecFileSystem_uri_prefix': 'test FSspecFileSystem get_short_uri and get_long_uri to strip and add URI prefixes from paths'}
```

## File: facebookresearch_fairseq2/tests/unit/test_gang.py

Prompts

```
['create a FooEnvironment instance initialized with a dictionary of key-value string pairs', 'get a value from FooEnvironment by key using the get method', 'use maybe_get on FooEnvironment to retrieve a value with a fallback default', 'set a key-value pair in FooEnvironment and check existence with has', 'iterate over FooEnvironment to yield all key-value tuples as an iterator', 'test the set_dtype context manager to temporarily change the default tensor dtype within a scoped block', 'test the get_current_dtype function to retrieve the current thread-local floating-point data type', 'test nested set_dtype context managers to verify dtype scoping and restoration after exiting each scope', 'test the DataTypeContext abstract class interface for getting and setting the current floating-point data type', 'test that tensors created outside any set_dtype scope default to torch.float32 as the standard dtype', 'test FSspecFileSystem open method to read and write binary files using FileMode enum', 'test FSspecFileSystem open_text method to read and write text files with utf-8 encoding', 'test FSspecFileSystem glob method to find files matching a wildcard pattern in a directory', 'test GlobalFileSystem to verify it delegates local path operations through the FileSystemRegistry dispatch chain', 'test FSspecFileSystem get_short_uri and get_long_uri to strip and add URI prefixes from paths', 'create fake gangs for a given device to use in unit tests', 'get the current gangs active in the present context scope', 'get the default gangs that were set globally before context changes', 'set the default gangs globally so all new contexts inherit them', 'use set_gangs as a context manager to temporarily override current gangs']
```

Usage

```
{'create_fake_gangs': 'create fake gangs for a given device to use in unit tests', 'get_current_gangs': 'get the current gangs active in the present context scope', 'get_default_gangs': 'get the default gangs that were set globally before context changes', 'set_default_gangs': 'set the default gangs globally so all new contexts inherit them', 'set_gangs_context': 'use set_gangs as a context manager to temporarily override current gangs'}
```


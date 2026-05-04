# Agent Python Tools

- repo: google-deepmind/alphastar
- repo_uri: https://github.com/google-deepmind/alphastar

## File: google-deepmind_alphastar/alphastar/types/types.py

Prompts

```
["create a NestedDict with nested key-value pairs using tuple keys like ('a', 'b') = 100", 'filter a NestedDict to return only entries matching another NestedDict or sequence of keys', 'validate data against a SpecDict to check keys, shapes, and dtypes match the spec', 'convert a NestedDict to a plain nested Python dict using the asdict method', 'create a deep copy of a NestedDict or SpecDict using the copy method', "create a NestedDict from a list of tuple-key value pairs like (('a','b'), 42)", "access nested values using tuple keys like x['b','c'] to get or set data", 'filter a NestedDict to keep only specified key paths using the filter method', 'validate numpy or jax array data against dm_env specs using SpecDict validate', 'flatten and map over a NestedDict using jax tree_flatten tree_map utilities']
```

Usage

```
{'create_nested_dict': "create a NestedDict with nested key-value pairs using tuple keys like ('a', 'b') = 100", 'filter_nested_dict': 'filter a NestedDict to return only entries matching another NestedDict or sequence of keys', 'validate_spec_dict': 'validate data against a SpecDict to check keys, shapes, and dtypes match the spec', 'convert_nested_dict_to_dict': 'convert a NestedDict to a plain nested Python dict using the asdict method', 'copy_nested_dict': 'create a deep copy of a NestedDict or SpecDict using the copy method'}
```

## File: google-deepmind_alphastar/alphastar/types/types_test.py

Prompts

```
["create a NestedDict with nested key-value pairs using tuple keys like ('a', 'b') = 100", 'filter a NestedDict to return only entries matching another NestedDict or sequence of keys', 'validate data against a SpecDict to check keys, shapes, and dtypes match the spec', 'convert a NestedDict to a plain nested Python dict using the asdict method', 'create a deep copy of a NestedDict or SpecDict using the copy method', "create a NestedDict from a list of tuple-key value pairs like (('a','b'), 42)", "access nested values using tuple keys like x['b','c'] to get or set data", 'filter a NestedDict to keep only specified key paths using the filter method', 'validate numpy or jax array data against dm_env specs using SpecDict validate', 'flatten and map over a NestedDict using jax tree_flatten tree_map utilities']
```

Usage

```
{'create_nested_dict_from_tuples': "create a NestedDict from a list of tuple-key value pairs like (('a','b'), 42)", 'access_nested_dict_with_tuple_keys': "access nested values using tuple keys like x['b','c'] to get or set data", 'filter_nested_dict_by_keys': 'filter a NestedDict to keep only specified key paths using the filter method', 'validate_data_with_spec_dict': 'validate numpy or jax array data against dm_env specs using SpecDict validate', 'flatten_nested_dict_with_jax_tree': 'flatten and map over a NestedDict using jax tree_flatten tree_map utilities'}
```


# Agent Python Tools

- repo: google-deepmind/dmenvrpc
- repo_uri: https://github.com/google-deepmind/dm_env_rpc

## File: google-deepmind_dmenvrpc/dm_env_rpc/v1/extensions/properties.py

Prompts

```
['read a property value by key from a dm_env_rpc server using PropertiesExtension', 'write a scalar or numpy array value to a property on a dm_env_rpc server', 'list all available property specs under a given key path via PropertiesExtension', 'get a dictionary mapping property keys to PropertySpec objects for a given key path', 'inspect a PropertySpec to check its key, readable, writable, listable, and description attributes', 'test the PropertiesExtension class to read a property value by key using bracket notation', 'test the PropertiesExtension class to write a property value by key and verify it was set', 'test the PropertiesExtension specs method to list all available property specs at root or under a key', 'test the PropertySpec class attributes including readable, writable, listable, spec, and description', 'test the PropertiesExtension error handling for invalid keys, bad arguments, and permission denied scenarios']
```

Usage

```
{'read_property_value': 'read a property value by key from a dm_env_rpc server using PropertiesExtension', 'write_property_value': 'write a scalar or numpy array value to a property on a dm_env_rpc server', 'list_property_specs': 'list all available property specs under a given key path via PropertiesExtension', 'get_property_spec_dict': 'get a dictionary mapping property keys to PropertySpec objects for a given key path', 'inspect_property_spec': 'inspect a PropertySpec to check its key, readable, writable, listable, and description attributes'}
```

## File: google-deepmind_dmenvrpc/dm_env_rpc/v1/extensions/properties_test.py

Prompts

```
['read a property value by key from a dm_env_rpc server using PropertiesExtension', 'write a scalar or numpy array value to a property on a dm_env_rpc server', 'list all available property specs under a given key path via PropertiesExtension', 'get a dictionary mapping property keys to PropertySpec objects for a given key path', 'inspect a PropertySpec to check its key, readable, writable, listable, and description attributes', 'test the PropertiesExtension class to read a property value by key using bracket notation', 'test the PropertiesExtension class to write a property value by key and verify it was set', 'test the PropertiesExtension specs method to list all available property specs at root or under a key', 'test the PropertySpec class attributes including readable, writable, listable, spec, and description', 'test the PropertiesExtension error handling for invalid keys, bad arguments, and permission denied scenarios']
```

Usage

```
{'test_properties_extension_read': 'test the PropertiesExtension class to read a property value by key using bracket notation', 'test_properties_extension_write': 'test the PropertiesExtension class to write a property value by key and verify it was set', 'test_properties_extension_specs': 'test the PropertiesExtension specs method to list all available property specs at root or under a key', 'test_property_spec_attributes': 'test the PropertySpec class attributes including readable, writable, listable, spec, and description', 'test_properties_error_handling': 'test the PropertiesExtension error handling for invalid keys, bad arguments, and permission denied scenarios'}
```


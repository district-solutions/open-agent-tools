# Agent Python Tools

- repo: facebookresearch/fbpcs
- repo_uri: https://github.com/facebookresearch/fbpcs

## File: facebookresearch_fbpcs/fbpcs/utils/config_yaml/config_yaml_dict.py

Prompts

```
['read a YAML config file into a ConfigYamlDict with custom error handling for missing fields', 'convert a standard Python dictionary into a ConfigYamlDict with recursive nested dict conversion', 'access a config field by key and raise ConfigYamlFieldNotFoundError if the key is missing', 'validate config values and raise ConfigYamlValidationError when TODO placeholders are found', 'set a config value with automatic conversion of nested dicts to ConfigYamlDict instances', 'get a class object from a module path string and validate it against a target class type', 'construct an instance of a class from a config.yml dict with class path and constructor args', 'handle deprecated class paths by emitting a warning and resolving to the new module path', 'validate constructor arguments from config dict and raise errors for TODO placeholders or type mismatches', 'review the get_class function that resolves a dotted module path to a class and asserts it is a subclass of the target']
```

Usage

```
{'load_yaml_config': 'read a YAML config file into a ConfigYamlDict with custom error handling for missing fields', 'convert_dict_to_config': 'convert a standard Python dictionary into a ConfigYamlDict with recursive nested dict conversion', 'access_config_field': 'access a config field by key and raise ConfigYamlFieldNotFoundError if the key is missing', 'validate_config_todos': 'validate config values and raise ConfigYamlValidationError when TODO placeholders are found', 'set_config_value': 'set a config value with automatic conversion of nested dicts to ConfigYamlDict instances'}
```

## File: facebookresearch_fbpcs/fbpcs/utils/config_yaml/reflect.py

Prompts

```
['read a YAML config file into a ConfigYamlDict with custom error handling for missing fields', 'convert a standard Python dictionary into a ConfigYamlDict with recursive nested dict conversion', 'access a config field by key and raise ConfigYamlFieldNotFoundError if the key is missing', 'validate config values and raise ConfigYamlValidationError when TODO placeholders are found', 'set a config value with automatic conversion of nested dicts to ConfigYamlDict instances', 'get a class object from a module path string and validate it against a target class type', 'construct an instance of a class from a config.yml dict with class path and constructor args', 'handle deprecated class paths by emitting a warning and resolving to the new module path', 'validate constructor arguments from config dict and raise errors for TODO placeholders or type mismatches', 'review the get_class function that resolves a dotted module path to a class and asserts it is a subclass of the target']
```

Usage

```
{'get_class_from_path': 'get a class object from a module path string and validate it against a target class type', 'get_instance_from_config': 'construct an instance of a class from a config.yml dict with class path and constructor args', 'handle_deprecated_class_paths': 'handle deprecated class paths by emitting a warning and resolving to the new module path', 'validate_constructor_args': 'validate constructor arguments from config dict and raise errors for TODO placeholders or type mismatches', 'review_get_class': 'review the get_class function that resolves a dotted module path to a class and asserts it is a subclass of the target'}
```


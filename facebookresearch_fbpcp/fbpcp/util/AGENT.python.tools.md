# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/fbpcp/util/arg_builder.py

Prompts

```
['build a command-line argument string from keyword arguments with proper shell quoting', 'build command-line args that automatically skip None values from keyword arguments', 'build a quoted argument string safe for passing to subprocess commands', 'refactor build_cmd_args to support additional argument formatting options', 'review the build_cmd_args function and its use of shlex.quote for safety', 'convert a Python dictionary to a list of dicts with custom key and value field names', 'convert a list of dicts back to a flat dictionary using specified key and value fields', 'convert AWS VPC tags and VPC ID into a list of filter dicts for boto3 queries', 'split an ECS container definition string into task definition and container name parts', 'validate an ECS container definition string against the expected format pattern', "get a class from a dot-separated path string like 'os.path.join' using dynamic import", 'review the get_class function that dynamically imports and returns a class from a module path string', 'test the get_class function by passing a valid module and class path and verifying the returned class', 'refactor the get_class function to add error handling for invalid module or class paths', 'summarize the get_class function which splits a class path string and uses importlib to dynamically retrieve it', 'use checked_cast to validate that a value is an instance of a specific type at runtime', 'use checked_cast to safely downcast a value to a more specific type with runtime verification', 'use checked_cast to guard configuration values ensuring they match the expected type before use', 'use checked_cast to assert a variable type and raise a clear ValueError on mismatch', 'use checked_cast to validate API input parameters are of the correct expected type', 'load a YAML file from a given path and return its contents as a dictionary', 'dump a dictionary to a YAML file at the specified path', 'review the yaml load function to safely parse YAML files using safe_load', 'review the yaml dump function to serialize a dictionary to a YAML file', 'refactor the yaml load and dump functions to support additional serialization options']
```

Usage

```
{'build_cmd_args_string': 'build a command-line argument string from keyword arguments with proper shell quoting', 'build_cmd_args_with_none_filtering': 'build command-line args that automatically skip None values from keyword arguments', 'build_cmd_args_for_subprocess': 'build a quoted argument string safe for passing to subprocess commands', 'refactor_build_cmd_args': 'refactor build_cmd_args to support additional argument formatting options', 'review_build_cmd_args': 'review the build_cmd_args function and its use of shlex.quote for safety'}
```

## File: facebookresearch_fbpcp/fbpcp/util/aws.py

Prompts

```
['build a command-line argument string from keyword arguments with proper shell quoting', 'build command-line args that automatically skip None values from keyword arguments', 'build a quoted argument string safe for passing to subprocess commands', 'refactor build_cmd_args to support additional argument formatting options', 'review the build_cmd_args function and its use of shlex.quote for safety', 'convert a Python dictionary to a list of dicts with custom key and value field names', 'convert a list of dicts back to a flat dictionary using specified key and value fields', 'convert AWS VPC tags and VPC ID into a list of filter dicts for boto3 queries', 'split an ECS container definition string into task definition and container name parts', 'validate an ECS container definition string against the expected format pattern', "get a class from a dot-separated path string like 'os.path.join' using dynamic import", 'review the get_class function that dynamically imports and returns a class from a module path string', 'test the get_class function by passing a valid module and class path and verifying the returned class', 'refactor the get_class function to add error handling for invalid module or class paths', 'summarize the get_class function which splits a class path string and uses importlib to dynamically retrieve it', 'use checked_cast to validate that a value is an instance of a specific type at runtime', 'use checked_cast to safely downcast a value to a more specific type with runtime verification', 'use checked_cast to guard configuration values ensuring they match the expected type before use', 'use checked_cast to assert a variable type and raise a clear ValueError on mismatch', 'use checked_cast to validate API input parameters are of the correct expected type', 'load a YAML file from a given path and return its contents as a dictionary', 'dump a dictionary to a YAML file at the specified path', 'review the yaml load function to safely parse YAML files using safe_load', 'review the yaml dump function to serialize a dictionary to a YAML file', 'refactor the yaml load and dump functions to support additional serialization options']
```

Usage

```
{'convert_dict_to_list': 'convert a Python dictionary to a list of dicts with custom key and value field names', 'convert_list_to_dict': 'convert a list of dicts back to a flat dictionary using specified key and value fields', 'convert_vpc_tags_to_filter': 'convert AWS VPC tags and VPC ID into a list of filter dicts for boto3 queries', 'split_container_definition': 'split an ECS container definition string into task definition and container name parts', 'is_container_definition_valid': 'validate an ECS container definition string against the expected format pattern'}
```

## File: facebookresearch_fbpcp/fbpcp/util/reflect.py

Prompts

```
['build a command-line argument string from keyword arguments with proper shell quoting', 'build command-line args that automatically skip None values from keyword arguments', 'build a quoted argument string safe for passing to subprocess commands', 'refactor build_cmd_args to support additional argument formatting options', 'review the build_cmd_args function and its use of shlex.quote for safety', 'convert a Python dictionary to a list of dicts with custom key and value field names', 'convert a list of dicts back to a flat dictionary using specified key and value fields', 'convert AWS VPC tags and VPC ID into a list of filter dicts for boto3 queries', 'split an ECS container definition string into task definition and container name parts', 'validate an ECS container definition string against the expected format pattern', "get a class from a dot-separated path string like 'os.path.join' using dynamic import", 'review the get_class function that dynamically imports and returns a class from a module path string', 'test the get_class function by passing a valid module and class path and verifying the returned class', 'refactor the get_class function to add error handling for invalid module or class paths', 'summarize the get_class function which splits a class path string and uses importlib to dynamically retrieve it', 'use checked_cast to validate that a value is an instance of a specific type at runtime', 'use checked_cast to safely downcast a value to a more specific type with runtime verification', 'use checked_cast to guard configuration values ensuring they match the expected type before use', 'use checked_cast to assert a variable type and raise a clear ValueError on mismatch', 'use checked_cast to validate API input parameters are of the correct expected type', 'load a YAML file from a given path and return its contents as a dictionary', 'dump a dictionary to a YAML file at the specified path', 'review the yaml load function to safely parse YAML files using safe_load', 'review the yaml dump function to serialize a dictionary to a YAML file', 'refactor the yaml load and dump functions to support additional serialization options']
```

Usage

```
{'get_class_by_path': "get a class from a dot-separated path string like 'os.path.join' using dynamic import", 'review_get_class': 'review the get_class function that dynamically imports and returns a class from a module path string', 'test_get_class': 'test the get_class function by passing a valid module and class path and verifying the returned class', 'refactor_get_class': 'refactor the get_class function to add error handling for invalid module or class paths', 'summarize_get_class': 'summarize the get_class function which splits a class path string and uses importlib to dynamically retrieve it'}
```

## File: facebookresearch_fbpcp/fbpcp/util/typing.py

Prompts

```
['build a command-line argument string from keyword arguments with proper shell quoting', 'build command-line args that automatically skip None values from keyword arguments', 'build a quoted argument string safe for passing to subprocess commands', 'refactor build_cmd_args to support additional argument formatting options', 'review the build_cmd_args function and its use of shlex.quote for safety', 'convert a Python dictionary to a list of dicts with custom key and value field names', 'convert a list of dicts back to a flat dictionary using specified key and value fields', 'convert AWS VPC tags and VPC ID into a list of filter dicts for boto3 queries', 'split an ECS container definition string into task definition and container name parts', 'validate an ECS container definition string against the expected format pattern', "get a class from a dot-separated path string like 'os.path.join' using dynamic import", 'review the get_class function that dynamically imports and returns a class from a module path string', 'test the get_class function by passing a valid module and class path and verifying the returned class', 'refactor the get_class function to add error handling for invalid module or class paths', 'summarize the get_class function which splits a class path string and uses importlib to dynamically retrieve it', 'use checked_cast to validate that a value is an instance of a specific type at runtime', 'use checked_cast to safely downcast a value to a more specific type with runtime verification', 'use checked_cast to guard configuration values ensuring they match the expected type before use', 'use checked_cast to assert a variable type and raise a clear ValueError on mismatch', 'use checked_cast to validate API input parameters are of the correct expected type', 'load a YAML file from a given path and return its contents as a dictionary', 'dump a dictionary to a YAML file at the specified path', 'review the yaml load function to safely parse YAML files using safe_load', 'review the yaml dump function to serialize a dictionary to a YAML file', 'refactor the yaml load and dump functions to support additional serialization options']
```

Usage

```
{'checked_cast_validate_type': 'use checked_cast to validate that a value is an instance of a specific type at runtime', 'checked_cast_safe_downcast': 'use checked_cast to safely downcast a value to a more specific type with runtime verification', 'checked_cast_guard_config': 'use checked_cast to guard configuration values ensuring they match the expected type before use', 'checked_cast_assert_type': 'use checked_cast to assert a variable type and raise a clear ValueError on mismatch', 'checked_cast_validate_api_input': 'use checked_cast to validate API input parameters are of the correct expected type'}
```

## File: facebookresearch_fbpcp/fbpcp/util/yaml.py

Prompts

```
['build a command-line argument string from keyword arguments with proper shell quoting', 'build command-line args that automatically skip None values from keyword arguments', 'build a quoted argument string safe for passing to subprocess commands', 'refactor build_cmd_args to support additional argument formatting options', 'review the build_cmd_args function and its use of shlex.quote for safety', 'convert a Python dictionary to a list of dicts with custom key and value field names', 'convert a list of dicts back to a flat dictionary using specified key and value fields', 'convert AWS VPC tags and VPC ID into a list of filter dicts for boto3 queries', 'split an ECS container definition string into task definition and container name parts', 'validate an ECS container definition string against the expected format pattern', "get a class from a dot-separated path string like 'os.path.join' using dynamic import", 'review the get_class function that dynamically imports and returns a class from a module path string', 'test the get_class function by passing a valid module and class path and verifying the returned class', 'refactor the get_class function to add error handling for invalid module or class paths', 'summarize the get_class function which splits a class path string and uses importlib to dynamically retrieve it', 'use checked_cast to validate that a value is an instance of a specific type at runtime', 'use checked_cast to safely downcast a value to a more specific type with runtime verification', 'use checked_cast to guard configuration values ensuring they match the expected type before use', 'use checked_cast to assert a variable type and raise a clear ValueError on mismatch', 'use checked_cast to validate API input parameters are of the correct expected type', 'load a YAML file from a given path and return its contents as a dictionary', 'dump a dictionary to a YAML file at the specified path', 'review the yaml load function to safely parse YAML files using safe_load', 'review the yaml dump function to serialize a dictionary to a YAML file', 'refactor the yaml load and dump functions to support additional serialization options']
```

Usage

```
{'load_yaml_file': 'load a YAML file from a given path and return its contents as a dictionary', 'dump_yaml_file': 'dump a dictionary to a YAML file at the specified path', 'review_yaml_load': 'review the yaml load function to safely parse YAML files using safe_load', 'review_yaml_dump': 'review the yaml dump function to serialize a dictionary to a YAML file', 'refactor_yaml_io': 'refactor the yaml load and dump functions to support additional serialization options'}
```


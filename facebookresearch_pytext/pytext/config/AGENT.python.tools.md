# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/config/component.py

Prompts

```
['create a model component from a model config using create_model', 'create a trainer component from a trainer config and model using create_trainer', 'create an optimizer component from an optimizer config and model using create_optimizer', 'create a predictor component from a predictor config using create_predicter', 'get the human-readable name of a component class or config object using get_component_name', 'upgrade a PyText JSON config to the latest version using registered adapter functions', 'downgrade a PyText JSON config to a specific older version using downgrade adapter functions', 'rename a config parameter from an old dotted path to a new dotted path with optional transform', 'recursively find all nested dictionaries in a JSON config that contain a given key', 'register a new version upgrade adapter function using the register_adapter decorator', 'create a PyTextConfig with task, version, and export settings for model training', 'create an ExportConfig to specify ONNX, TorchScript, or Caffe2 model export paths', 'create a TestConfig with load_snapshot_path and test_path for model evaluation', 'create a LogitsConfig with batch_size and gpu settings for inference output', 'create a ConfigBase subclass with typed annotations and default values for custom config', 'parse a PyTextConfig object from a JSON configuration string or file using parse_config', 'create a config object from a JSON dictionary by calling config_from_json with a config class', 'serialise a config object back to a JSON dictionary using config_to_json', 'build a PyTextConfig from JSON with automatic schema upgrade via pytext_config_from_json', 'look up a registered component config class type by its type name string', 'find all config field paths matching a given suffix recursively in a PyText config object', 'cast a string value to int, float, bool, list, or dict using type annotations', 'replace a config parameter by dotted path with automatic type casting from a string value', 'resolve an Optional type annotation to its inner non-None type argument', 'check if an object is a component class by verifying its class name starts with an uppercase letter']
```

Usage

```
{'create_model_from_config': 'create a model component from a model config using create_model', 'create_trainer_from_config': 'create a trainer component from a trainer config and model using create_trainer', 'create_optimizer_from_config': 'create an optimizer component from an optimizer config and model using create_optimizer', 'create_predictor_from_config': 'create a predictor component from a predictor config using create_predicter', 'get_component_name': 'get the human-readable name of a component class or config object using get_component_name'}
```

## File: facebookresearch_pytext/pytext/config/config_adapter.py

Prompts

```
['create a model component from a model config using create_model', 'create a trainer component from a trainer config and model using create_trainer', 'create an optimizer component from an optimizer config and model using create_optimizer', 'create a predictor component from a predictor config using create_predicter', 'get the human-readable name of a component class or config object using get_component_name', 'upgrade a PyText JSON config to the latest version using registered adapter functions', 'downgrade a PyText JSON config to a specific older version using downgrade adapter functions', 'rename a config parameter from an old dotted path to a new dotted path with optional transform', 'recursively find all nested dictionaries in a JSON config that contain a given key', 'register a new version upgrade adapter function using the register_adapter decorator', 'create a PyTextConfig with task, version, and export settings for model training', 'create an ExportConfig to specify ONNX, TorchScript, or Caffe2 model export paths', 'create a TestConfig with load_snapshot_path and test_path for model evaluation', 'create a LogitsConfig with batch_size and gpu settings for inference output', 'create a ConfigBase subclass with typed annotations and default values for custom config', 'parse a PyTextConfig object from a JSON configuration string or file using parse_config', 'create a config object from a JSON dictionary by calling config_from_json with a config class', 'serialise a config object back to a JSON dictionary using config_to_json', 'build a PyTextConfig from JSON with automatic schema upgrade via pytext_config_from_json', 'look up a registered component config class type by its type name string', 'find all config field paths matching a given suffix recursively in a PyText config object', 'cast a string value to int, float, bool, list, or dict using type annotations', 'replace a config parameter by dotted path with automatic type casting from a string value', 'resolve an Optional type annotation to its inner non-None type argument', 'check if an object is a component class by verifying its class name starts with an uppercase letter']
```

Usage

```
{'upgrade_config_to_latest': 'upgrade a PyText JSON config to the latest version using registered adapter functions', 'downgrade_config_to_version': 'downgrade a PyText JSON config to a specific older version using downgrade adapter functions', 'rename_parameter_in_config': 'rename a config parameter from an old dotted path to a new dotted path with optional transform', 'find_dicts_containing_key': 'recursively find all nested dictionaries in a JSON config that contain a given key', 'register_config_adapter': 'register a new version upgrade adapter function using the register_adapter decorator'}
```

## File: facebookresearch_pytext/pytext/config/pytext_config.py

Prompts

```
['create a model component from a model config using create_model', 'create a trainer component from a trainer config and model using create_trainer', 'create an optimizer component from an optimizer config and model using create_optimizer', 'create a predictor component from a predictor config using create_predicter', 'get the human-readable name of a component class or config object using get_component_name', 'upgrade a PyText JSON config to the latest version using registered adapter functions', 'downgrade a PyText JSON config to a specific older version using downgrade adapter functions', 'rename a config parameter from an old dotted path to a new dotted path with optional transform', 'recursively find all nested dictionaries in a JSON config that contain a given key', 'register a new version upgrade adapter function using the register_adapter decorator', 'create a PyTextConfig with task, version, and export settings for model training', 'create an ExportConfig to specify ONNX, TorchScript, or Caffe2 model export paths', 'create a TestConfig with load_snapshot_path and test_path for model evaluation', 'create a LogitsConfig with batch_size and gpu settings for inference output', 'create a ConfigBase subclass with typed annotations and default values for custom config', 'parse a PyTextConfig object from a JSON configuration string or file using parse_config', 'create a config object from a JSON dictionary by calling config_from_json with a config class', 'serialise a config object back to a JSON dictionary using config_to_json', 'build a PyTextConfig from JSON with automatic schema upgrade via pytext_config_from_json', 'look up a registered component config class type by its type name string', 'find all config field paths matching a given suffix recursively in a PyText config object', 'cast a string value to int, float, bool, list, or dict using type annotations', 'replace a config parameter by dotted path with automatic type casting from a string value', 'resolve an Optional type annotation to its inner non-None type argument', 'check if an object is a component class by verifying its class name starts with an uppercase letter']
```

Usage

```
{'create_pytext_config': 'create a PyTextConfig with task, version, and export settings for model training', 'create_export_config': 'create an ExportConfig to specify ONNX, TorchScript, or Caffe2 model export paths', 'create_test_config': 'create a TestConfig with load_snapshot_path and test_path for model evaluation', 'create_logits_config': 'create a LogitsConfig with batch_size and gpu settings for inference output', 'create_config_base_subclass': 'create a ConfigBase subclass with typed annotations and default values for custom config'}
```

## File: facebookresearch_pytext/pytext/config/serialize.py

Prompts

```
['create a model component from a model config using create_model', 'create a trainer component from a trainer config and model using create_trainer', 'create an optimizer component from an optimizer config and model using create_optimizer', 'create a predictor component from a predictor config using create_predicter', 'get the human-readable name of a component class or config object using get_component_name', 'upgrade a PyText JSON config to the latest version using registered adapter functions', 'downgrade a PyText JSON config to a specific older version using downgrade adapter functions', 'rename a config parameter from an old dotted path to a new dotted path with optional transform', 'recursively find all nested dictionaries in a JSON config that contain a given key', 'register a new version upgrade adapter function using the register_adapter decorator', 'create a PyTextConfig with task, version, and export settings for model training', 'create an ExportConfig to specify ONNX, TorchScript, or Caffe2 model export paths', 'create a TestConfig with load_snapshot_path and test_path for model evaluation', 'create a LogitsConfig with batch_size and gpu settings for inference output', 'create a ConfigBase subclass with typed annotations and default values for custom config', 'parse a PyTextConfig object from a JSON configuration string or file using parse_config', 'create a config object from a JSON dictionary by calling config_from_json with a config class', 'serialise a config object back to a JSON dictionary using config_to_json', 'build a PyTextConfig from JSON with automatic schema upgrade via pytext_config_from_json', 'look up a registered component config class type by its type name string', 'find all config field paths matching a given suffix recursively in a PyText config object', 'cast a string value to int, float, bool, list, or dict using type annotations', 'replace a config parameter by dotted path with automatic type casting from a string value', 'resolve an Optional type annotation to its inner non-None type argument', 'check if an object is a component class by verifying its class name starts with an uppercase letter']
```

Usage

```
{'parse_config_from_json': 'parse a PyTextConfig object from a JSON configuration string or file using parse_config', 'config_from_json_to_object': 'create a config object from a JSON dictionary by calling config_from_json with a config class', 'config_to_json_serialise': 'serialise a config object back to a JSON dictionary using config_to_json', 'pytext_config_from_json_upgrade': 'build a PyTextConfig from JSON with automatic schema upgrade via pytext_config_from_json', 'component_config_type_from_name': 'look up a registered component config class type by its type name string'}
```

## File: facebookresearch_pytext/pytext/config/utils.py

Prompts

```
['create a model component from a model config using create_model', 'create a trainer component from a trainer config and model using create_trainer', 'create an optimizer component from an optimizer config and model using create_optimizer', 'create a predictor component from a predictor config using create_predicter', 'get the human-readable name of a component class or config object using get_component_name', 'upgrade a PyText JSON config to the latest version using registered adapter functions', 'downgrade a PyText JSON config to a specific older version using downgrade adapter functions', 'rename a config parameter from an old dotted path to a new dotted path with optional transform', 'recursively find all nested dictionaries in a JSON config that contain a given key', 'register a new version upgrade adapter function using the register_adapter decorator', 'create a PyTextConfig with task, version, and export settings for model training', 'create an ExportConfig to specify ONNX, TorchScript, or Caffe2 model export paths', 'create a TestConfig with load_snapshot_path and test_path for model evaluation', 'create a LogitsConfig with batch_size and gpu settings for inference output', 'create a ConfigBase subclass with typed annotations and default values for custom config', 'parse a PyTextConfig object from a JSON configuration string or file using parse_config', 'create a config object from a JSON dictionary by calling config_from_json with a config class', 'serialise a config object back to a JSON dictionary using config_to_json', 'build a PyTextConfig from JSON with automatic schema upgrade via pytext_config_from_json', 'look up a registered component config class type by its type name string', 'find all config field paths matching a given suffix recursively in a PyText config object', 'cast a string value to int, float, bool, list, or dict using type annotations', 'replace a config parameter by dotted path with automatic type casting from a string value', 'resolve an Optional type annotation to its inner non-None type argument', 'check if an object is a component class by verifying its class name starts with an uppercase letter']
```

Usage

```
{'find_param_config_fields': 'find all config field paths matching a given suffix recursively in a PyText config object', 'cast_str_to_type': 'cast a string value to int, float, bool, list, or dict using type annotations', 'replace_param_in_config': 'replace a config parameter by dotted path with automatic type casting from a string value', 'resolve_optional_type': 'resolve an Optional type annotation to its inner non-None type argument', 'is_component_class_check': 'check if an object is a component class by verifying its class name starts with an uppercase letter'}
```


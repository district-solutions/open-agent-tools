# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/detectron2/config/compat.py

Prompts

```
['upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess the version of a partial detectron2 config that is missing the VERSION field', 'rename old detectron2 config keys to new names using the internal _rename helper function', 'review the ConverterV2 class that handles bulk config key renames before the public release', 'get a copy of the default detectron2 CfgNode config instance', 'set the global config to point to a given CfgNode instance', 'merge configuration from a YAML file into a CfgNode with version support', 'dump a CfgNode config object to a YAML string representation', 'decorate a class init or function to accept a CfgNode via from_config', 'instantiate a Python object from a config dict containing a _target_ key and constructor arguments', 'recursively instantiate nested config dicts and lists that contain _target_ entries into real objects', 'dump a dataclass instance into a serializable dict with a _target_ key for later instantiation', 'recursively dump nested dataclass objects and lists of dataclasses into dicts with _target_ keys', 'review the instantiate function to understand how it handles TypeError when calling a target class constructor', 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load a Python or YAML config file and return an omegaconf DictConfig object', 'save an omegaconf config object to a YAML file with cloudpickle fallback', 'apply a list of override strings to in-place update config values', 'convert an omegaconf config object into human-readable Python-like pseudo code']
```

Usage

```
{'upgrade_config': 'upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade_config': 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess_version': 'guess the version of a partial detectron2 config that is missing the VERSION field', 'rename_config_keys': 'rename old detectron2 config keys to new names using the internal _rename helper function', 'review_ConverterV2': 'review the ConverterV2 class that handles bulk config key renames before the public release'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/config/config.py

Prompts

```
['upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess the version of a partial detectron2 config that is missing the VERSION field', 'rename old detectron2 config keys to new names using the internal _rename helper function', 'review the ConverterV2 class that handles bulk config key renames before the public release', 'get a copy of the default detectron2 CfgNode config instance', 'set the global config to point to a given CfgNode instance', 'merge configuration from a YAML file into a CfgNode with version support', 'dump a CfgNode config object to a YAML string representation', 'decorate a class init or function to accept a CfgNode via from_config', 'instantiate a Python object from a config dict containing a _target_ key and constructor arguments', 'recursively instantiate nested config dicts and lists that contain _target_ entries into real objects', 'dump a dataclass instance into a serializable dict with a _target_ key for later instantiation', 'recursively dump nested dataclass objects and lists of dataclasses into dicts with _target_ keys', 'review the instantiate function to understand how it handles TypeError when calling a target class constructor', 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load a Python or YAML config file and return an omegaconf DictConfig object', 'save an omegaconf config object to a YAML file with cloudpickle fallback', 'apply a list of override strings to in-place update config values', 'convert an omegaconf config object into human-readable Python-like pseudo code']
```

Usage

```
{'get_cfg': 'get a copy of the default detectron2 CfgNode config instance', 'set_global_cfg': 'set the global config to point to a given CfgNode instance', 'CfgNode_merge_from_file': 'merge configuration from a YAML file into a CfgNode with version support', 'CfgNode_dump': 'dump a CfgNode config object to a YAML string representation', 'configurable_decorator': 'decorate a class init or function to accept a CfgNode via from_config'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/config/instantiate.py

Prompts

```
['upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess the version of a partial detectron2 config that is missing the VERSION field', 'rename old detectron2 config keys to new names using the internal _rename helper function', 'review the ConverterV2 class that handles bulk config key renames before the public release', 'get a copy of the default detectron2 CfgNode config instance', 'set the global config to point to a given CfgNode instance', 'merge configuration from a YAML file into a CfgNode with version support', 'dump a CfgNode config object to a YAML string representation', 'decorate a class init or function to accept a CfgNode via from_config', 'instantiate a Python object from a config dict containing a _target_ key and constructor arguments', 'recursively instantiate nested config dicts and lists that contain _target_ entries into real objects', 'dump a dataclass instance into a serializable dict with a _target_ key for later instantiation', 'recursively dump nested dataclass objects and lists of dataclasses into dicts with _target_ keys', 'review the instantiate function to understand how it handles TypeError when calling a target class constructor', 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load a Python or YAML config file and return an omegaconf DictConfig object', 'save an omegaconf config object to a YAML file with cloudpickle fallback', 'apply a list of override strings to in-place update config values', 'convert an omegaconf config object into human-readable Python-like pseudo code']
```

Usage

```
{'instantiate_from_config_dict': 'instantiate a Python object from a config dict containing a _target_ key and constructor arguments', 'instantiate_nested_config': 'recursively instantiate nested config dicts and lists that contain _target_ entries into real objects', 'dump_dataclass_to_dict': 'dump a dataclass instance into a serializable dict with a _target_ key for later instantiation', 'dump_nested_dataclass': 'recursively dump nested dataclass objects and lists of dataclasses into dicts with _target_ keys', 'review_instantiate_error_handling': 'review the instantiate function to understand how it handles TypeError when calling a target class constructor'}
```

## File: facebookresearch_banmo/third_party/detectron2/detectron2/config/lazy.py

Prompts

```
['upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess the version of a partial detectron2 config that is missing the VERSION field', 'rename old detectron2 config keys to new names using the internal _rename helper function', 'review the ConverterV2 class that handles bulk config key renames before the public release', 'get a copy of the default detectron2 CfgNode config instance', 'set the global config to point to a given CfgNode instance', 'merge configuration from a YAML file into a CfgNode with version support', 'dump a CfgNode config object to a YAML string representation', 'decorate a class init or function to accept a CfgNode via from_config', 'instantiate a Python object from a config dict containing a _target_ key and constructor arguments', 'recursively instantiate nested config dicts and lists that contain _target_ entries into real objects', 'dump a dataclass instance into a serializable dict with a _target_ key for later instantiation', 'recursively dump nested dataclass objects and lists of dataclasses into dicts with _target_ keys', 'review the instantiate function to understand how it handles TypeError when calling a target class constructor', 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load a Python or YAML config file and return an omegaconf DictConfig object', 'save an omegaconf config object to a YAML file with cloudpickle fallback', 'apply a list of override strings to in-place update config values', 'convert an omegaconf config object into human-readable Python-like pseudo code']
```

Usage

```
{'create_LazyCall': 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load_LazyConfig': 'load a Python or YAML config file and return an omegaconf DictConfig object', 'save_LazyConfig': 'save an omegaconf config object to a YAML file with cloudpickle fallback', 'apply_overrides_LazyConfig': 'apply a list of override strings to in-place update config values', 'to_py_LazyConfig': 'convert an omegaconf config object into human-readable Python-like pseudo code'}
```


# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/config/compat.py

Prompts

```
['upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess the version of a partial detectron2 config that is missing the VERSION field', 'review the ConverterV1 class that renames MODEL.RPN_HEAD.NAME to MODEL.RPN.HEAD_NAME during config upgrades', 'review the ConverterV2 class that handles bulk config key renames and anchor generator migration before public release', 'get a copy of the default detectron2 CfgNode config instance', 'set the global config to a given CfgNode for access anywhere in code', 'merge configuration values from a YAML file into a CfgNode with versioning support', 'dump a CfgNode config object to a YAML string representation', 'decorate a class init or function to accept a CfgNode via from_config', 'dump a dataclass instance recursively into a serializable dictionary with _target_ metadata', 'instantiate objects from a config dictionary using _target_ keys and argument values', 'recursively instantiate nested config dictionaries and lists containing _target_ entries', 'review the dump_dataclass function to understand recursive dataclass serialization logic', 'review the instantiate function to understand how _target_ based object construction works', 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load a Python or YAML config file into an omegaconf DictConfig object', 'save an omegaconf config object to a YAML file with cloudpickle fallback', "apply command-style override strings like 'a.b=c' to an omegaconf config in place", 'convert an omegaconf config object into formatted Python source code using black']
```

Usage

```
{'upgrade_config': 'upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade_config': 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess_version': 'guess the version of a partial detectron2 config that is missing the VERSION field', 'review_ConverterV1': 'review the ConverterV1 class that renames MODEL.RPN_HEAD.NAME to MODEL.RPN.HEAD_NAME during config upgrades', 'review_ConverterV2': 'review the ConverterV2 class that handles bulk config key renames and anchor generator migration before public release'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/config/config.py

Prompts

```
['upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess the version of a partial detectron2 config that is missing the VERSION field', 'review the ConverterV1 class that renames MODEL.RPN_HEAD.NAME to MODEL.RPN.HEAD_NAME during config upgrades', 'review the ConverterV2 class that handles bulk config key renames and anchor generator migration before public release', 'get a copy of the default detectron2 CfgNode config instance', 'set the global config to a given CfgNode for access anywhere in code', 'merge configuration values from a YAML file into a CfgNode with versioning support', 'dump a CfgNode config object to a YAML string representation', 'decorate a class init or function to accept a CfgNode via from_config', 'dump a dataclass instance recursively into a serializable dictionary with _target_ metadata', 'instantiate objects from a config dictionary using _target_ keys and argument values', 'recursively instantiate nested config dictionaries and lists containing _target_ entries', 'review the dump_dataclass function to understand recursive dataclass serialization logic', 'review the instantiate function to understand how _target_ based object construction works', 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load a Python or YAML config file into an omegaconf DictConfig object', 'save an omegaconf config object to a YAML file with cloudpickle fallback', "apply command-style override strings like 'a.b=c' to an omegaconf config in place", 'convert an omegaconf config object into formatted Python source code using black']
```

Usage

```
{'get_cfg': 'get a copy of the default detectron2 CfgNode config instance', 'set_global_cfg': 'set the global config to a given CfgNode for access anywhere in code', 'CfgNode_merge_from_file': 'merge configuration values from a YAML file into a CfgNode with versioning support', 'CfgNode_dump': 'dump a CfgNode config object to a YAML string representation', 'configurable_decorator': 'decorate a class init or function to accept a CfgNode via from_config'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/config/instantiate.py

Prompts

```
['upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess the version of a partial detectron2 config that is missing the VERSION field', 'review the ConverterV1 class that renames MODEL.RPN_HEAD.NAME to MODEL.RPN.HEAD_NAME during config upgrades', 'review the ConverterV2 class that handles bulk config key renames and anchor generator migration before public release', 'get a copy of the default detectron2 CfgNode config instance', 'set the global config to a given CfgNode for access anywhere in code', 'merge configuration values from a YAML file into a CfgNode with versioning support', 'dump a CfgNode config object to a YAML string representation', 'decorate a class init or function to accept a CfgNode via from_config', 'dump a dataclass instance recursively into a serializable dictionary with _target_ metadata', 'instantiate objects from a config dictionary using _target_ keys and argument values', 'recursively instantiate nested config dictionaries and lists containing _target_ entries', 'review the dump_dataclass function to understand recursive dataclass serialization logic', 'review the instantiate function to understand how _target_ based object construction works', 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load a Python or YAML config file into an omegaconf DictConfig object', 'save an omegaconf config object to a YAML file with cloudpickle fallback', "apply command-style override strings like 'a.b=c' to an omegaconf config in place", 'convert an omegaconf config object into formatted Python source code using black']
```

Usage

```
{'dump_dataclass_to_dict': 'dump a dataclass instance recursively into a serializable dictionary with _target_ metadata', 'instantiate_from_config_dict': 'instantiate objects from a config dictionary using _target_ keys and argument values', 'instantiate_nested_config': 'recursively instantiate nested config dictionaries and lists containing _target_ entries', 'review_dump_dataclass': 'review the dump_dataclass function to understand recursive dataclass serialization logic', 'review_instantiate': 'review the instantiate function to understand how _target_ based object construction works'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/detectron2/config/lazy.py

Prompts

```
['upgrade a detectron2 config CfgNode from its current version to the latest or a specified version', 'downgrade a detectron2 config CfgNode from its current version to an older specified version', 'guess the version of a partial detectron2 config that is missing the VERSION field', 'review the ConverterV1 class that renames MODEL.RPN_HEAD.NAME to MODEL.RPN.HEAD_NAME during config upgrades', 'review the ConverterV2 class that handles bulk config key renames and anchor generator migration before public release', 'get a copy of the default detectron2 CfgNode config instance', 'set the global config to a given CfgNode for access anywhere in code', 'merge configuration values from a YAML file into a CfgNode with versioning support', 'dump a CfgNode config object to a YAML string representation', 'decorate a class init or function to accept a CfgNode via from_config', 'dump a dataclass instance recursively into a serializable dictionary with _target_ metadata', 'instantiate objects from a config dictionary using _target_ keys and argument values', 'recursively instantiate nested config dictionaries and lists containing _target_ entries', 'review the dump_dataclass function to understand recursive dataclass serialization logic', 'review the instantiate function to understand how _target_ based object construction works', 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load a Python or YAML config file into an omegaconf DictConfig object', 'save an omegaconf config object to a YAML file with cloudpickle fallback', "apply command-style override strings like 'a.b=c' to an omegaconf config in place", 'convert an omegaconf config object into formatted Python source code using black']
```

Usage

```
{'create_LazyCall': 'create a LazyCall wrapper around a callable to defer instantiation until later', 'load_LazyConfig': 'load a Python or YAML config file into an omegaconf DictConfig object', 'save_LazyConfig': 'save an omegaconf config object to a YAML file with cloudpickle fallback', 'apply_overrides_LazyConfig': "apply command-style override strings like 'a.b=c' to an omegaconf config in place", 'to_py_LazyConfig': 'convert an omegaconf config object into formatted Python source code using black'}
```


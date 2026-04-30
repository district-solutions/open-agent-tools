# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/detectron2/config/compat.py

Prompts

```
['upgrade a detectron2 CfgNode config from an older version to a newer version', 'downgrade a detectron2 CfgNode config from a newer version to an older version', 'guess the config version from a partial detectron2 CfgNode missing the VERSION field', 'rename nested config keys in a detectron2 CfgNode from old dot-notation paths to new ones', 'convert a detectron2 config from v1 to v2 by renaming keys and migrating anchor generator settings', 'load a YAML config file and merge it into a CfgNode with automatic version upgrading', 'create a copy of the default detectron2 config using get_cfg', 'set a global config copy accessible anywhere via global_cfg without passing it through code', 'decorate a class __init__ with @configurable so it can be called with a CfgNode or regular arguments', 'test the @configurable decorator on a standalone function with from_config argument translation', 'dump a dataclass instance into a dict with _target_ for later instantiation', 'recursively instantiate objects from a dict using _target_ and keyword arguments', 'instantiate omegaconf ListConfig elements recursively preserving object references', 'convert a DictConfig backed by dataclasses to actual dataclass objects', 'instantiate nested _target_ entries by resolving string class paths and calling cls(**kwargs)', 'create a LazyCall wrapper around a callable to defer execution and return a config dict with keyword arguments', 'load a python or yaml config file with LazyConfig.load and return omegaconf DictConfig objects', 'save an omegaconf config object to a yaml file with LazyConfig.save, falling back to cloudpickle if needed', "apply command-line style overrides in 'key=value' format to an omegaconf config object in-place", 'convert an omegaconf config object into human-readable Python-like pseudo code with LazyConfig.to_py']
```

Usage

```
{'upgrade_config': 'upgrade a detectron2 CfgNode config from an older version to a newer version', 'downgrade_config': 'downgrade a detectron2 CfgNode config from a newer version to an older version', 'guess_version': 'guess the config version from a partial detectron2 CfgNode missing the VERSION field', 'rename_config_keys': 'rename nested config keys in a detectron2 CfgNode from old dot-notation paths to new ones', 'convert_config_v2': 'convert a detectron2 config from v1 to v2 by renaming keys and migrating anchor generator settings'}
```

## File: facebookresearch_detectron2/detectron2/config/config.py

Prompts

```
['upgrade a detectron2 CfgNode config from an older version to a newer version', 'downgrade a detectron2 CfgNode config from a newer version to an older version', 'guess the config version from a partial detectron2 CfgNode missing the VERSION field', 'rename nested config keys in a detectron2 CfgNode from old dot-notation paths to new ones', 'convert a detectron2 config from v1 to v2 by renaming keys and migrating anchor generator settings', 'load a YAML config file and merge it into a CfgNode with automatic version upgrading', 'create a copy of the default detectron2 config using get_cfg', 'set a global config copy accessible anywhere via global_cfg without passing it through code', 'decorate a class __init__ with @configurable so it can be called with a CfgNode or regular arguments', 'test the @configurable decorator on a standalone function with from_config argument translation', 'dump a dataclass instance into a dict with _target_ for later instantiation', 'recursively instantiate objects from a dict using _target_ and keyword arguments', 'instantiate omegaconf ListConfig elements recursively preserving object references', 'convert a DictConfig backed by dataclasses to actual dataclass objects', 'instantiate nested _target_ entries by resolving string class paths and calling cls(**kwargs)', 'create a LazyCall wrapper around a callable to defer execution and return a config dict with keyword arguments', 'load a python or yaml config file with LazyConfig.load and return omegaconf DictConfig objects', 'save an omegaconf config object to a yaml file with LazyConfig.save, falling back to cloudpickle if needed', "apply command-line style overrides in 'key=value' format to an omegaconf config object in-place", 'convert an omegaconf config object into human-readable Python-like pseudo code with LazyConfig.to_py']
```

Usage

```
{'build_load_config_file': 'load a YAML config file and merge it into a CfgNode with automatic version upgrading', 'create_get_default_cfg': 'create a copy of the default detectron2 config using get_cfg', 'set_global_config_access': 'set a global config copy accessible anywhere via global_cfg without passing it through code', 'build_configurable_init': 'decorate a class __init__ with @configurable so it can be called with a CfgNode or regular arguments', 'test_configurable_function': 'test the @configurable decorator on a standalone function with from_config argument translation'}
```

## File: facebookresearch_detectron2/detectron2/config/instantiate.py

Prompts

```
['upgrade a detectron2 CfgNode config from an older version to a newer version', 'downgrade a detectron2 CfgNode config from a newer version to an older version', 'guess the config version from a partial detectron2 CfgNode missing the VERSION field', 'rename nested config keys in a detectron2 CfgNode from old dot-notation paths to new ones', 'convert a detectron2 config from v1 to v2 by renaming keys and migrating anchor generator settings', 'load a YAML config file and merge it into a CfgNode with automatic version upgrading', 'create a copy of the default detectron2 config using get_cfg', 'set a global config copy accessible anywhere via global_cfg without passing it through code', 'decorate a class __init__ with @configurable so it can be called with a CfgNode or regular arguments', 'test the @configurable decorator on a standalone function with from_config argument translation', 'dump a dataclass instance into a dict with _target_ for later instantiation', 'recursively instantiate objects from a dict using _target_ and keyword arguments', 'instantiate omegaconf ListConfig elements recursively preserving object references', 'convert a DictConfig backed by dataclasses to actual dataclass objects', 'instantiate nested _target_ entries by resolving string class paths and calling cls(**kwargs)', 'create a LazyCall wrapper around a callable to defer execution and return a config dict with keyword arguments', 'load a python or yaml config file with LazyConfig.load and return omegaconf DictConfig objects', 'save an omegaconf config object to a yaml file with LazyConfig.save, falling back to cloudpickle if needed', "apply command-line style overrides in 'key=value' format to an omegaconf config object in-place", 'convert an omegaconf config object into human-readable Python-like pseudo code with LazyConfig.to_py']
```

Usage

```
{'dump_dataclass_dataclass_obj': 'dump a dataclass instance into a dict with _target_ for later instantiation', 'instantiate_cfg_dict': 'recursively instantiate objects from a dict using _target_ and keyword arguments', 'instantiate_omegaconf_list': 'instantiate omegaconf ListConfig elements recursively preserving object references', 'instantiate_omegaconf_dictconfig': 'convert a DictConfig backed by dataclasses to actual dataclass objects', 'instantiate_nested_target': 'instantiate nested _target_ entries by resolving string class paths and calling cls(**kwargs)'}
```

## File: facebookresearch_detectron2/detectron2/config/lazy.py

Prompts

```
['upgrade a detectron2 CfgNode config from an older version to a newer version', 'downgrade a detectron2 CfgNode config from a newer version to an older version', 'guess the config version from a partial detectron2 CfgNode missing the VERSION field', 'rename nested config keys in a detectron2 CfgNode from old dot-notation paths to new ones', 'convert a detectron2 config from v1 to v2 by renaming keys and migrating anchor generator settings', 'load a YAML config file and merge it into a CfgNode with automatic version upgrading', 'create a copy of the default detectron2 config using get_cfg', 'set a global config copy accessible anywhere via global_cfg without passing it through code', 'decorate a class __init__ with @configurable so it can be called with a CfgNode or regular arguments', 'test the @configurable decorator on a standalone function with from_config argument translation', 'dump a dataclass instance into a dict with _target_ for later instantiation', 'recursively instantiate objects from a dict using _target_ and keyword arguments', 'instantiate omegaconf ListConfig elements recursively preserving object references', 'convert a DictConfig backed by dataclasses to actual dataclass objects', 'instantiate nested _target_ entries by resolving string class paths and calling cls(**kwargs)', 'create a LazyCall wrapper around a callable to defer execution and return a config dict with keyword arguments', 'load a python or yaml config file with LazyConfig.load and return omegaconf DictConfig objects', 'save an omegaconf config object to a yaml file with LazyConfig.save, falling back to cloudpickle if needed', "apply command-line style overrides in 'key=value' format to an omegaconf config object in-place", 'convert an omegaconf config object into human-readable Python-like pseudo code with LazyConfig.to_py']
```

Usage

```
{'create_LazyCall': 'create a LazyCall wrapper around a callable to defer execution and return a config dict with keyword arguments', 'load_LazyConfig': 'load a python or yaml config file with LazyConfig.load and return omegaconf DictConfig objects', 'save_LazyConfig': 'save an omegaconf config object to a yaml file with LazyConfig.save, falling back to cloudpickle if needed', 'override_LazyConfig': "apply command-line style overrides in 'key=value' format to an omegaconf config object in-place", 'convert_LazyConfig': 'convert an omegaconf config object into human-readable Python-like pseudo code with LazyConfig.to_py'}
```


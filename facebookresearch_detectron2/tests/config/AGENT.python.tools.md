# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/tests/config/test_instantiate_config.py

Prompts

```
['test the instantiate function to resolve LazyCall configs into real Python objects', 'test LazyCall construction with nested arguments and interpolation references', 'test reload_lazy_config to serialize and deserialize LazyCall config objects', 'test instantiate with ShapeSpec dataclass as a subconfig argument', 'test OmegaConf interpolation syntax in LazyCall config arguments', 'test loading a Python or YAML config file using LazyConfig.load and verify config values', 'test saving a config to YAML with LazyConfig.save then reloading it with LazyConfig.load', 'test overriding config values in-place using LazyConfig.apply_overrides with key=value strings', 'test converting a config object to human-readable Python pseudo code using LazyConfig.to_py', 'test wrapping a callable with LazyCall to defer instantiation and modify arguments before calling', 'test that downgrade_config and upgrade_config preserve custom config fields across version changes', 'test the configurable decorator on a class init with a from_config classmethod to parse cfg', 'test the configurable decorator on a function with a lambda from_config to extract args from cfg', 'test initializing a configurable class with a cfg object and overwriting wrong config values via kwargs', 'test building a detectron2 model using an OmegaConf config created from a model_zoo YAML file']
```

Usage

```
{'test_instantiate_lazyconfig': 'test the instantiate function to resolve LazyCall configs into real Python objects', 'test_lazycall_construction': 'test LazyCall construction with nested arguments and interpolation references', 'test_reload_lazy_config': 'test reload_lazy_config to serialize and deserialize LazyCall config objects', 'test_instantiate_dataclass': 'test instantiate with ShapeSpec dataclass as a subconfig argument', 'test_interpolation': 'test OmegaConf interpolation syntax in LazyCall config arguments'}
```

## File: facebookresearch_detectron2/tests/config/test_lazy_config.py

Prompts

```
['test the instantiate function to resolve LazyCall configs into real Python objects', 'test LazyCall construction with nested arguments and interpolation references', 'test reload_lazy_config to serialize and deserialize LazyCall config objects', 'test instantiate with ShapeSpec dataclass as a subconfig argument', 'test OmegaConf interpolation syntax in LazyCall config arguments', 'test loading a Python or YAML config file using LazyConfig.load and verify config values', 'test saving a config to YAML with LazyConfig.save then reloading it with LazyConfig.load', 'test overriding config values in-place using LazyConfig.apply_overrides with key=value strings', 'test converting a config object to human-readable Python pseudo code using LazyConfig.to_py', 'test wrapping a callable with LazyCall to defer instantiation and modify arguments before calling', 'test that downgrade_config and upgrade_config preserve custom config fields across version changes', 'test the configurable decorator on a class init with a from_config classmethod to parse cfg', 'test the configurable decorator on a function with a lambda from_config to extract args from cfg', 'test initializing a configurable class with a cfg object and overwriting wrong config values via kwargs', 'test building a detectron2 model using an OmegaConf config created from a model_zoo YAML file']
```

Usage

```
{'test_LazyConfig_load': 'test loading a Python or YAML config file using LazyConfig.load and verify config values', 'test_LazyConfig_save_load': 'test saving a config to YAML with LazyConfig.save then reloading it with LazyConfig.load', 'test_LazyConfig_apply_overrides': 'test overriding config values in-place using LazyConfig.apply_overrides with key=value strings', 'test_LazyConfig_to_py': 'test converting a config object to human-readable Python pseudo code using LazyConfig.to_py', 'test_LazyCall_lazy_instantiation': 'test wrapping a callable with LazyCall to defer instantiation and modify arguments before calling'}
```

## File: facebookresearch_detectron2/tests/config/test_yacs_config.py

Prompts

```
['test the instantiate function to resolve LazyCall configs into real Python objects', 'test LazyCall construction with nested arguments and interpolation references', 'test reload_lazy_config to serialize and deserialize LazyCall config objects', 'test instantiate with ShapeSpec dataclass as a subconfig argument', 'test OmegaConf interpolation syntax in LazyCall config arguments', 'test loading a Python or YAML config file using LazyConfig.load and verify config values', 'test saving a config to YAML with LazyConfig.save then reloading it with LazyConfig.load', 'test overriding config values in-place using LazyConfig.apply_overrides with key=value strings', 'test converting a config object to human-readable Python pseudo code using LazyConfig.to_py', 'test wrapping a callable with LazyCall to defer instantiation and modify arguments before calling', 'test that downgrade_config and upgrade_config preserve custom config fields across version changes', 'test the configurable decorator on a class init with a from_config classmethod to parse cfg', 'test the configurable decorator on a function with a lambda from_config to extract args from cfg', 'test initializing a configurable class with a cfg object and overwriting wrong config values via kwargs', 'test building a detectron2 model using an OmegaConf config created from a model_zoo YAML file']
```

Usage

```
{'test_config_versioning_upgrade_downgrade': 'test that downgrade_config and upgrade_config preserve custom config fields across version changes', 'test_configurable_decorator_on_class': 'test the configurable decorator on a class init with a from_config classmethod to parse cfg', 'test_configurable_decorator_on_function': 'test the configurable decorator on a function with a lambda from_config to extract args from cfg', 'test_cfg_init_with_overwrite': 'test initializing a configurable class with a cfg object and overwriting wrong config values via kwargs', 'test_omegaconf_model_build': 'test building a detectron2 model using an OmegaConf config created from a model_zoo YAML file'}
```


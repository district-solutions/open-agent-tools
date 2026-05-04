# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/tests/config/test_instantiate_config.py

Prompts

```
['test instantiate a TestClass object using LazyCall with nested arguments and interpolation', 'test that instantiate passes through non-LazyCall objects like integers, lists, and dicts unchanged', 'test instantiate a LazyCall where the _target_ itself is a LazyCall result', 'test instantiate a list containing LazyCall objects that get recursively instantiated', 'test instantiate a dataclass using LazyCall and verify field values are correctly set', 'test loading a LazyConfig from a Python config file and verify its values', 'test saving a LazyConfig to YAML and reloading it to verify round-trip equality', 'test applying key=value string overrides to a LazyConfig and verify updated values', 'test converting a LazyConfig with nested LazyCall objects to a Python source string', 'test saving a DictConfig with unpicklable lambda objects and verify pickle fallback', 'test that downgrade_config and upgrade_config preserve custom config fields across version changes', 'test the configurable decorator on a torch.nn.Module class with from_config class method', 'test the configurable decorator on a standalone function with a lambda from_config', 'test get_cfg to create a default config and merge YAML strings into it', 'test build_model with an OmegaConf config loaded from the Detectron2 model zoo']
```

Usage

```
{'test_instantiate_with_lazycall': 'test instantiate a TestClass object using LazyCall with nested arguments and interpolation', 'test_instantiate_other_objects': 'test that instantiate passes through non-LazyCall objects like integers, lists, and dicts unchanged', 'test_instantiate_lazy_target': 'test instantiate a LazyCall where the _target_ itself is a LazyCall result', 'test_instantiate_list_with_lazycall': 'test instantiate a list containing LazyCall objects that get recursively instantiated', 'test_instantiate_dataclass': 'test instantiate a dataclass using LazyCall and verify field values are correctly set'}
```

## File: facebookresearch_banmo/third_party/detectron2/tests/config/test_lazy_config.py

Prompts

```
['test instantiate a TestClass object using LazyCall with nested arguments and interpolation', 'test that instantiate passes through non-LazyCall objects like integers, lists, and dicts unchanged', 'test instantiate a LazyCall where the _target_ itself is a LazyCall result', 'test instantiate a list containing LazyCall objects that get recursively instantiated', 'test instantiate a dataclass using LazyCall and verify field values are correctly set', 'test loading a LazyConfig from a Python config file and verify its values', 'test saving a LazyConfig to YAML and reloading it to verify round-trip equality', 'test applying key=value string overrides to a LazyConfig and verify updated values', 'test converting a LazyConfig with nested LazyCall objects to a Python source string', 'test saving a DictConfig with unpicklable lambda objects and verify pickle fallback', 'test that downgrade_config and upgrade_config preserve custom config fields across version changes', 'test the configurable decorator on a torch.nn.Module class with from_config class method', 'test the configurable decorator on a standalone function with a lambda from_config', 'test get_cfg to create a default config and merge YAML strings into it', 'test build_model with an OmegaConf config loaded from the Detectron2 model zoo']
```

Usage

```
{'test_LazyConfig_load': 'test loading a LazyConfig from a Python config file and verify its values', 'test_LazyConfig_save_load': 'test saving a LazyConfig to YAML and reloading it to verify round-trip equality', 'test_LazyConfig_apply_overrides': 'test applying key=value string overrides to a LazyConfig and verify updated values', 'test_LazyConfig_to_py': 'test converting a LazyConfig with nested LazyCall objects to a Python source string', 'test_LazyConfig_failed_save': 'test saving a DictConfig with unpicklable lambda objects and verify pickle fallback'}
```

## File: facebookresearch_banmo/third_party/detectron2/tests/config/test_yacs_config.py

Prompts

```
['test instantiate a TestClass object using LazyCall with nested arguments and interpolation', 'test that instantiate passes through non-LazyCall objects like integers, lists, and dicts unchanged', 'test instantiate a LazyCall where the _target_ itself is a LazyCall result', 'test instantiate a list containing LazyCall objects that get recursively instantiated', 'test instantiate a dataclass using LazyCall and verify field values are correctly set', 'test loading a LazyConfig from a Python config file and verify its values', 'test saving a LazyConfig to YAML and reloading it to verify round-trip equality', 'test applying key=value string overrides to a LazyConfig and verify updated values', 'test converting a LazyConfig with nested LazyCall objects to a Python source string', 'test saving a DictConfig with unpicklable lambda objects and verify pickle fallback', 'test that downgrade_config and upgrade_config preserve custom config fields across version changes', 'test the configurable decorator on a torch.nn.Module class with from_config class method', 'test the configurable decorator on a standalone function with a lambda from_config', 'test get_cfg to create a default config and merge YAML strings into it', 'test build_model with an OmegaConf config loaded from the Detectron2 model zoo']
```

Usage

```
{'test_config_versioning_upgrade_downgrade': 'test that downgrade_config and upgrade_config preserve custom config fields across version changes', 'test_configurable_decorator_on_class': 'test the configurable decorator on a torch.nn.Module class with from_config class method', 'test_configurable_decorator_on_function': 'test the configurable decorator on a standalone function with a lambda from_config', 'test_get_cfg_and_merge': 'test get_cfg to create a default config and merge YAML strings into it', 'test_build_model_with_omegaconf': 'test build_model with an OmegaConf config loaded from the Detectron2 model zoo'}
```


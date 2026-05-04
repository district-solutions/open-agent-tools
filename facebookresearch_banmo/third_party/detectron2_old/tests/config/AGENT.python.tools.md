# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/tests/config/test_instantiate_config.py

Prompts

```
['test the LazyCall constructor to create a deferred object configuration with nested arguments', 'test the instantiate function to resolve a LazyCall config into a real object instance', 'test LazyCall with OmegaConf interpolation syntax to reference sibling arguments in nested configs', 'test instantiate on a LazyCall config containing a list with nested LazyCall entries', 'test serialize a LazyCall config to YAML and then instantiate it back into an object', 'load a Detectron2 LazyConfig from a Python or YAML config file', 'save a Detectron2 LazyConfig object to a YAML file on disk', 'apply key=value string overrides to a Detectron2 LazyConfig object', 'convert a Detectron2 LazyConfig object to a Python source code string', 'create a LazyCall wrapper to defer instantiation of a callable with arguments', 'test that downgrade_config and upgrade_config round-trip a Detectron2 config without data loss', 'test the configurable decorator on a torch.nn.Module subclass with a from_config class method', 'test the configurable decorator on a plain function with a lambda from_config', 'test building a Detectron2 model from an OmegaConf config object via build_model', 'test merging a YAML config string into a Detectron2 cfg via a temporary file']
```

Usage

```
{'test_instantiate_LazyCall': 'test the LazyCall constructor to create a deferred object configuration with nested arguments', 'test_instantiate_function': 'test the instantiate function to resolve a LazyCall config into a real object instance', 'test_LazyCall_interpolation': 'test LazyCall with OmegaConf interpolation syntax to reference sibling arguments in nested configs', 'test_instantiate_recursive_list': 'test instantiate on a LazyCall config containing a list with nested LazyCall entries', 'test_instantiate_serialization': 'test serialize a LazyCall config to YAML and then instantiate it back into an object'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/tests/config/test_lazy_config.py

Prompts

```
['test the LazyCall constructor to create a deferred object configuration with nested arguments', 'test the instantiate function to resolve a LazyCall config into a real object instance', 'test LazyCall with OmegaConf interpolation syntax to reference sibling arguments in nested configs', 'test instantiate on a LazyCall config containing a list with nested LazyCall entries', 'test serialize a LazyCall config to YAML and then instantiate it back into an object', 'load a Detectron2 LazyConfig from a Python or YAML config file', 'save a Detectron2 LazyConfig object to a YAML file on disk', 'apply key=value string overrides to a Detectron2 LazyConfig object', 'convert a Detectron2 LazyConfig object to a Python source code string', 'create a LazyCall wrapper to defer instantiation of a callable with arguments', 'test that downgrade_config and upgrade_config round-trip a Detectron2 config without data loss', 'test the configurable decorator on a torch.nn.Module subclass with a from_config class method', 'test the configurable decorator on a plain function with a lambda from_config', 'test building a Detectron2 model from an OmegaConf config object via build_model', 'test merging a YAML config string into a Detectron2 cfg via a temporary file']
```

Usage

```
{'load_LazyConfig': 'load a Detectron2 LazyConfig from a Python or YAML config file', 'save_LazyConfig': 'save a Detectron2 LazyConfig object to a YAML file on disk', 'apply_overrides_LazyConfig': 'apply key=value string overrides to a Detectron2 LazyConfig object', 'to_py_LazyConfig': 'convert a Detectron2 LazyConfig object to a Python source code string', 'create_LazyCall': 'create a LazyCall wrapper to defer instantiation of a callable with arguments'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/tests/config/test_yacs_config.py

Prompts

```
['test the LazyCall constructor to create a deferred object configuration with nested arguments', 'test the instantiate function to resolve a LazyCall config into a real object instance', 'test LazyCall with OmegaConf interpolation syntax to reference sibling arguments in nested configs', 'test instantiate on a LazyCall config containing a list with nested LazyCall entries', 'test serialize a LazyCall config to YAML and then instantiate it back into an object', 'load a Detectron2 LazyConfig from a Python or YAML config file', 'save a Detectron2 LazyConfig object to a YAML file on disk', 'apply key=value string overrides to a Detectron2 LazyConfig object', 'convert a Detectron2 LazyConfig object to a Python source code string', 'create a LazyCall wrapper to defer instantiation of a callable with arguments', 'test that downgrade_config and upgrade_config round-trip a Detectron2 config without data loss', 'test the configurable decorator on a torch.nn.Module subclass with a from_config class method', 'test the configurable decorator on a plain function with a lambda from_config', 'test building a Detectron2 model from an OmegaConf config object via build_model', 'test merging a YAML config string into a Detectron2 cfg via a temporary file']
```

Usage

```
{'test_config_versioning_upgrade_downgrade': 'test that downgrade_config and upgrade_config round-trip a Detectron2 config without data loss', 'test_configurable_decorator_on_class': 'test the configurable decorator on a torch.nn.Module subclass with a from_config class method', 'test_configurable_decorator_on_function': 'test the configurable decorator on a plain function with a lambda from_config', 'test_build_model_from_omegaconf': 'test building a Detectron2 model from an OmegaConf config object via build_model', 'test_config_merge_from_yaml_string': 'test merging a YAML config string into a Detectron2 cfg via a temporary file'}
```


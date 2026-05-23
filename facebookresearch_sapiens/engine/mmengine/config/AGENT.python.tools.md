# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/engine/mmengine/config/config.py

Prompts

```
['build a Config instance from a Python, JSON, or YAML config file using Config.fromfile', 'build a Config instance from a config string with Config.fromstring specifying the file format', 'diff two config files and print a colored unified diff using Config.diff', 'merge a dictionary of dot-separated keys into an existing Config with merge_from_dict', 'auto generate an argparse parser from a config file using Config.auto_argparser', 'build a LazyObject to lazily import a single module like torch.nn by module name string', 'build a LazyObject to lazily import a specific name from a module using the imported parameter', 'build a LazyObject to lazily import multiple related modules passed as a list of strings', 'build a LazyAttr by accessing an attribute on a LazyObject to defer attribute resolution', 'test the LazyObject build method to resolve the deferred import and return the actual module object', 'get meta information from model-index.yml for a specific experiment config in an external package', 'get the absolute config path of an experiment config file from an external OpenMMLab package', 'get the base config path from the .mim/configs directory of an external package', 'parse an external config path with package:: syntax to extract package name and relative config path', 'transform import statements in config files to LazyObject assignments for lazy loading of modules']
```

Usage

```
{'build_config_from_file': 'build a Config instance from a Python, JSON, or YAML config file using Config.fromfile', 'build_config_from_string': 'build a Config instance from a config string with Config.fromstring specifying the file format', 'diff_two_configs': 'diff two config files and print a colored unified diff using Config.diff', 'merge_dict_into_config': 'merge a dictionary of dot-separated keys into an existing Config with merge_from_dict', 'auto_generate_argparser': 'auto generate an argparse parser from a config file using Config.auto_argparser'}
```

## File: facebookresearch_sapiens/engine/mmengine/config/lazy.py

Prompts

```
['build a Config instance from a Python, JSON, or YAML config file using Config.fromfile', 'build a Config instance from a config string with Config.fromstring specifying the file format', 'diff two config files and print a colored unified diff using Config.diff', 'merge a dictionary of dot-separated keys into an existing Config with merge_from_dict', 'auto generate an argparse parser from a config file using Config.auto_argparser', 'build a LazyObject to lazily import a single module like torch.nn by module name string', 'build a LazyObject to lazily import a specific name from a module using the imported parameter', 'build a LazyObject to lazily import multiple related modules passed as a list of strings', 'build a LazyAttr by accessing an attribute on a LazyObject to defer attribute resolution', 'test the LazyObject build method to resolve the deferred import and return the actual module object', 'get meta information from model-index.yml for a specific experiment config in an external package', 'get the absolute config path of an experiment config file from an external OpenMMLab package', 'get the base config path from the .mim/configs directory of an external package', 'parse an external config path with package:: syntax to extract package name and relative config path', 'transform import statements in config files to LazyObject assignments for lazy loading of modules']
```

Usage

```
{'build_LazyObject_single_module': 'build a LazyObject to lazily import a single module like torch.nn by module name string', 'build_LazyObject_with_imported': 'build a LazyObject to lazily import a specific name from a module using the imported parameter', 'build_LazyObject_multi_module': 'build a LazyObject to lazily import multiple related modules passed as a list of strings', 'build_LazyAttr_from_LazyObject': 'build a LazyAttr by accessing an attribute on a LazyObject to defer attribute resolution', 'test_LazyObject_build': 'test the LazyObject build method to resolve the deferred import and return the actual module object'}
```

## File: facebookresearch_sapiens/engine/mmengine/config/utils.py

Prompts

```
['build a Config instance from a Python, JSON, or YAML config file using Config.fromfile', 'build a Config instance from a config string with Config.fromstring specifying the file format', 'diff two config files and print a colored unified diff using Config.diff', 'merge a dictionary of dot-separated keys into an existing Config with merge_from_dict', 'auto generate an argparse parser from a config file using Config.auto_argparser', 'build a LazyObject to lazily import a single module like torch.nn by module name string', 'build a LazyObject to lazily import a specific name from a module using the imported parameter', 'build a LazyObject to lazily import multiple related modules passed as a list of strings', 'build a LazyAttr by accessing an attribute on a LazyObject to defer attribute resolution', 'test the LazyObject build method to resolve the deferred import and return the actual module object', 'get meta information from model-index.yml for a specific experiment config in an external package', 'get the absolute config path of an experiment config file from an external OpenMMLab package', 'get the base config path from the .mim/configs directory of an external package', 'parse an external config path with package:: syntax to extract package name and relative config path', 'transform import statements in config files to LazyObject assignments for lazy loading of modules']
```

Usage

```
{'get_cfg_metainfo': 'get meta information from model-index.yml for a specific experiment config in an external package', 'get_external_cfg_path': 'get the absolute config path of an experiment config file from an external OpenMMLab package', 'get_external_cfg_base_path': 'get the base config path from the .mim/configs directory of an external package', 'get_package_and_cfg_path': 'parse an external config path with package:: syntax to extract package name and relative config path', 'ImportTransformer': 'transform import statements in config files to LazyObject assignments for lazy loading of modules'}
```


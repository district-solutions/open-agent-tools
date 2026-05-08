# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tools/configen/configen/configen.py

Prompts

```
['initialize a configen configuration directory with a sample configen.yaml file', 'generate a Python module with structured config classes from a given module and class list', 'save generated configen module code to a file path based on the module path pattern', 'check if a Python type annotation is incompatible with OmegaConf structured config requirements', 'extract default flags like _convert_ and _recursive_ from a configen module configuration', 'check if a Python type annotation is a tuple type using is_tuple_annotation', 'convert a set of type objects and string imports into a sorted list of import statements', 'recursively collect all type annotations from a complex type into a set for import generation', 'review the convert_imports function to understand how it generates import statements from type objects', 'refactor the collect_imports function to handle additional generic type annotations like Union']
```

Usage

```
{'init_configen_config_dir': 'initialize a configen configuration directory with a sample configen.yaml file', 'generate_configen_module': 'generate a Python module with structured config classes from a given module and class list', 'save_configen_module': 'save generated configen module code to a file path based on the module path pattern', 'check_type_compatibility': 'check if a Python type annotation is incompatible with OmegaConf structured config requirements', 'get_default_flags': 'extract default flags like _convert_ and _recursive_ from a configen module configuration'}
```

## File: facebookresearch_hydra/tools/configen/configen/utils.py

Prompts

```
['initialize a configen configuration directory with a sample configen.yaml file', 'generate a Python module with structured config classes from a given module and class list', 'save generated configen module code to a file path based on the module path pattern', 'check if a Python type annotation is incompatible with OmegaConf structured config requirements', 'extract default flags like _convert_ and _recursive_ from a configen module configuration', 'check if a Python type annotation is a tuple type using is_tuple_annotation', 'convert a set of type objects and string imports into a sorted list of import statements', 'recursively collect all type annotations from a complex type into a set for import generation', 'review the convert_imports function to understand how it generates import statements from type objects', 'refactor the collect_imports function to handle additional generic type annotations like Union']
```

Usage

```
{'check_tuple_annotation': 'check if a Python type annotation is a tuple type using is_tuple_annotation', 'convert_imports_to_strings': 'convert a set of type objects and string imports into a sorted list of import statements', 'collect_type_imports': 'recursively collect all type annotations from a complex type into a set for import generation', 'review_convert_imports': 'review the convert_imports function to understand how it generates import statements from type objects', 'refactor_collect_imports': 'refactor the collect_imports function to handle additional generic type annotations like Union'}
```


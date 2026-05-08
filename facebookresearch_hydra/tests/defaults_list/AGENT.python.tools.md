# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/defaults_list/test_defaults_list.py

Prompts

```
['test that loading a config file returns the expected list of ConfigDefault and GroupDefault elements', 'test the create_defaults_list function with various config names and overrides to verify correct ResultDefault output', 'test that ConfigDefault and GroupDefault get_group_path and get_config_path return correct paths with parent_base_dir', 'test that InputDefault get_default_package returns the correct package name based on path and parent_base_dir', 'test that InputDefault get_final_package resolves package names including _global_, _group_, and parent package inheritance']
```

Usage

```
{'test_loaded_defaults_list': 'test that loading a config file returns the expected list of ConfigDefault and GroupDefault elements', 'test_create_defaults_list': 'test the create_defaults_list function with various config names and overrides to verify correct ResultDefault output', 'test_get_paths': 'test that ConfigDefault and GroupDefault get_group_path and get_config_path return correct paths with parent_base_dir', 'test_get_default_package': 'test that InputDefault get_default_package returns the correct package name based on path and parent_base_dir', 'test_get_final_package': 'test that InputDefault get_final_package resolves package names including _global_, _group_, and parent package inheritance'}
```


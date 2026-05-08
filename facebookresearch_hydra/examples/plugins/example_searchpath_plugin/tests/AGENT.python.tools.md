# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/plugins/example_searchpath_plugin/tests/test_example_search_path_plugin.py

Prompts

```
['test that ExampleSearchPathPlugin can be discovered via the Hydra plugins subsystem', 'test that my_default_output_dir is installed in the hydra output config group', 'run Plugins.instance().discover to list all registered SearchPathPlugin implementations', 'run GlobalHydra.instance().config_loader to get the active config loader', 'run config_loader.get_group_options to retrieve available options for a config group']
```

Usage

```
{'test_discovery': 'test that ExampleSearchPathPlugin can be discovered via the Hydra plugins subsystem', 'test_config_installed': 'test that my_default_output_dir is installed in the hydra output config group', 'run_Plugins_discover': 'run Plugins.instance().discover to list all registered SearchPathPlugin implementations', 'run_GlobalHydra_config_loader': 'run GlobalHydra.instance().config_loader to get the active config loader', 'run_get_group_options': 'run config_loader.get_group_options to retrieve available options for a config group'}
```


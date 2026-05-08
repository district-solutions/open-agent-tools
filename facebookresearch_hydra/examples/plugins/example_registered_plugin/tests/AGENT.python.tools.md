# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/plugins/example_registered_plugin/tests/test_example_registered_plugin.py

Prompts

```
['test that a Hydra plugin is discoverable after calling register_example_plugin', 'test the ExampleRegisteredPlugin class by creating an instance and calling its add method', 'register the ExampleRegisteredPlugin class with the Hydra Plugins singleton instance', 'discover all registered Hydra Plugin subclasses using Plugins.instance().discover', 'create an ExampleRegisteredPlugin instance with an integer value and use its add method']
```

Usage

```
{'test_discovery': 'test that a Hydra plugin is discoverable after calling register_example_plugin', 'test_example_plugin': 'test the ExampleRegisteredPlugin class by creating an instance and calling its add method', 'register_example_plugin': 'register the ExampleRegisteredPlugin class with the Hydra Plugins singleton instance', 'discover_plugins': 'discover all registered Hydra Plugin subclasses using Plugins.instance().discover', 'create_example_registered_plugin': 'create an ExampleRegisteredPlugin instance with an integer value and use its add method'}
```


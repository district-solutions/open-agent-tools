# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/instantiate/schema_recursive/my_app.py

Prompts

```
['run the Hydra app that instantiates a recursive Tree from config and pretty prints it', 'use hydra utils instantiate to create a Tree object from a TreeConf config node', 'create a TreeConf dataclass with _target_ pointing to Tree and recursive left and right fields', 'recursively pretty print a Tree structure showing each node value with indented left and right children', 'register a Config dataclass with ConfigStore so Hydra can resolve it by name']
```

Usage

```
{'run_my_app': 'run the Hydra app that instantiates a recursive Tree from config and pretty prints it', 'instantiate_tree_from_config': 'use hydra utils instantiate to create a Tree object from a TreeConf config node', 'create_tree_conf': 'create a TreeConf dataclass with _target_ pointing to Tree and recursive left and right fields', 'pretty_print_tree': 'recursively pretty print a Tree structure showing each node value with indented left and right children', 'register_config_schema': 'register a Config dataclass with ConfigStore so Hydra can resolve it by name'}
```


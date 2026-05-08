# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/tutorials/structured_configs/2_static_complex/my_app.py

Prompts

```
['run the Hydra app my_app that prints UI title and size from structured config', 'create a MySQLConfig dataclass with host and port fields for database configuration', 'create a UserInterface dataclass with title, width, and height fields for UI configuration', 'register a MyConfig dataclass node with Hydra ConfigStore using cs.store', 'compose a MyConfig dataclass with nested MySQLConfig and UserInterface using field default_factory']
```

Usage

```
{'run_hydra_app': 'run the Hydra app my_app that prints UI title and size from structured config', 'create_mysql_config': 'create a MySQLConfig dataclass with host and port fields for database configuration', 'create_user_interface_config': 'create a UserInterface dataclass with title, width, and height fields for UI configuration', 'register_config_with_store': 'register a MyConfig dataclass node with Hydra ConfigStore using cs.store', 'compose_nested_config': 'compose a MyConfig dataclass with nested MySQLConfig and UserInterface using field default_factory'}
```


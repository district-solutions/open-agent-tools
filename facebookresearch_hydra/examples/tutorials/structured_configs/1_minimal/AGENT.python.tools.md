# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/tutorials/structured_configs/1_minimal/my_app.py

Prompts

```
['run a Hydra app that prints MySQL host and port from structured config', 'create a MySQLConfig dataclass with host and port fields for Hydra structured configs', 'register a config class with ConfigStore using cs.store with a name and node', 'use the hydra.main decorator with version_base and config_name to create a configurable app', 'review the MySQLConfig dataclass and its default host and port values', 'review the ConfigStore instance that registers MySQLConfig under the name config', 'review the my_app function decorated with hydra.main that checks cfg.pork attribute', 'summarize the type error example where cfg.pork is used instead of cfg.port']
```

Usage

```
{'run_hydra_app': 'run a Hydra app that prints MySQL host and port from structured config', 'create_dataclass_config': 'create a MySQLConfig dataclass with host and port fields for Hydra structured configs', 'register_config_store': 'register a config class with ConfigStore using cs.store with a name and node', 'use_hydra_main_decorator': 'use the hydra.main decorator with version_base and config_name to create a configurable app', 'review_MySQLConfig': 'review the MySQLConfig dataclass and its default host and port values'}
```

## File: facebookresearch_hydra/examples/tutorials/structured_configs/1_minimal/my_app_type_error.py

Prompts

```
['run a Hydra app that prints MySQL host and port from structured config', 'create a MySQLConfig dataclass with host and port fields for Hydra structured configs', 'register a config class with ConfigStore using cs.store with a name and node', 'use the hydra.main decorator with version_base and config_name to create a configurable app', 'review the MySQLConfig dataclass and its default host and port values', 'review the ConfigStore instance that registers MySQLConfig under the name config', 'review the my_app function decorated with hydra.main that checks cfg.pork attribute', 'summarize the type error example where cfg.pork is used instead of cfg.port']
```

Usage

```
{'run_hydra_app': 'run the hydra app my_app that prints a message when cfg.pork equals 80', 'review_MySQLConfig': 'review the MySQLConfig dataclass with host and port fields for database configuration', 'review_ConfigStore': 'review the ConfigStore instance that registers MySQLConfig under the name config', 'review_my_app': 'review the my_app function decorated with hydra.main that checks cfg.pork attribute', 'summarize_type_error_example': 'summarize the type error example where cfg.pork is used instead of cfg.port'}
```


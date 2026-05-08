# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/tests/test_apps/defaults_in_schema_missing/my_app.py

Prompts

```
['run the Hydra app my_app that prints the resolved configuration as YAML', 'create a DBConfig dataclass with driver, host, and port fields using OmegaConf MISSING', 'create a MySQLConfig dataclass that extends DBConfig with mysql driver, port 3306, user, and password', 'store a config node in the Hydra ConfigStore with a group, name, and provider', 'review the Config dataclass that uses a defaults list and db field for Hydra schema-based defaults']
```

Usage

```
{'run_hydra_app': 'run the Hydra app my_app that prints the resolved configuration as YAML', 'create_DBConfig_dataclass': 'create a DBConfig dataclass with driver, host, and port fields using OmegaConf MISSING', 'create_MySQLConfig_dataclass': 'create a MySQLConfig dataclass that extends DBConfig with mysql driver, port 3306, user, and password', 'store_config_in_ConfigStore': 'store a config node in the Hydra ConfigStore with a group, name, and provider', 'review_Config_defaults_list': 'review the Config dataclass that uses a defaults list and db field for Hydra schema-based defaults'}
```


# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/tutorials/structured_configs/5.2_structured_config_schema_different_config_group/database_lib.py

Prompts

```
['create a DBConfig dataclass with driver, host, and port fields for database configuration', 'create a MySQLConfig dataclass extending DBConfig with mysql driver, port 3306, user, and password', 'create a PostGreSQLConfig dataclass extending DBConfig with postgresql driver, port 5432, user, password, and timeout', 'run register_configs to store MySQLConfig and PostGreSQLConfig in the Hydra ConfigStore under database_lib/db group', 'review the DBConfig base class and how MySQLConfig and PostGreSQLConfig override driver and port defaults', 'run the hydra app my_app that prints the resolved config as YAML', "register a dataclass Config as base_config in Hydra's ConfigStore for structured configs", 'call database_lib.register_configs to register external database config schemas from a library', 'print the resolved Hydra config as YAML using OmegaConf.to_yaml', 'review the Config dataclass that defines db and debug fields for structured configuration']
```

Usage

```
{'create_DBConfig_dataclass': 'create a DBConfig dataclass with driver, host, and port fields for database configuration', 'create_MySQLConfig_dataclass': 'create a MySQLConfig dataclass extending DBConfig with mysql driver, port 3306, user, and password', 'create_PostGreSQLConfig_dataclass': 'create a PostGreSQLConfig dataclass extending DBConfig with postgresql driver, port 5432, user, password, and timeout', 'run_register_configs': 'run register_configs to store MySQLConfig and PostGreSQLConfig in the Hydra ConfigStore under database_lib/db group', 'review_DBConfig_inheritance': 'review the DBConfig base class and how MySQLConfig and PostGreSQLConfig override driver and port defaults'}
```

## File: facebookresearch_hydra/examples/tutorials/structured_configs/5.2_structured_config_schema_different_config_group/my_app.py

Prompts

```
['create a DBConfig dataclass with driver, host, and port fields for database configuration', 'create a MySQLConfig dataclass extending DBConfig with mysql driver, port 3306, user, and password', 'create a PostGreSQLConfig dataclass extending DBConfig with postgresql driver, port 5432, user, password, and timeout', 'run register_configs to store MySQLConfig and PostGreSQLConfig in the Hydra ConfigStore under database_lib/db group', 'review the DBConfig base class and how MySQLConfig and PostGreSQLConfig override driver and port defaults', 'run the hydra app my_app that prints the resolved config as YAML', "register a dataclass Config as base_config in Hydra's ConfigStore for structured configs", 'call database_lib.register_configs to register external database config schemas from a library', 'print the resolved Hydra config as YAML using OmegaConf.to_yaml', 'review the Config dataclass that defines db and debug fields for structured configuration']
```

Usage

```
{'run_hydra_app': 'run the hydra app my_app that prints the resolved config as YAML', 'register_config_store': "register a dataclass Config as base_config in Hydra's ConfigStore for structured configs", 'register_external_configs': 'call database_lib.register_configs to register external database config schemas from a library', 'print_config_yaml': 'print the resolved Hydra config as YAML using OmegaConf.to_yaml', 'review_Config_class': 'review the Config dataclass that defines db and debug fields for structured configuration'}
```


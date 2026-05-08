# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/tutorials/structured_configs/3_config_groups/my_app.py

Prompts

```
['run a Hydra app that prints the resolved config as YAML using config groups for db selection', 'create a MySQLConfig dataclass with driver, host, and port default values for database configuration', 'create a PostGreSQLConfig dataclass with driver, host, port, and timeout default values', 'store a Config dataclass and db config group options in the Hydra ConfigStore singleton', 'summarize how Hydra config groups compose MySQL and PostgreSQL database configs into a main Config', 'run the hydra app with a db config group like mysql or postgresql', 'create a DBConfig dataclass with host, port, and driver fields using omegaconf MISSING', 'build a MySQLConfig dataclass inheriting from DBConfig with mysql driver and port 3306', 'build a PostGreSQLConfig dataclass inheriting from DBConfig with postgresql driver and port 5432', 'register config and db group nodes with ConfigStore for mysql and postgresql options']
```

Usage

```
{'run_hydra_app_with_config_groups': 'run a Hydra app that prints the resolved config as YAML using config groups for db selection', 'create_mysql_config_dataclass': 'create a MySQLConfig dataclass with driver, host, and port default values for database configuration', 'create_postgresql_config_dataclass': 'create a PostGreSQLConfig dataclass with driver, host, port, and timeout default values', 'store_config_in_configstore': 'store a Config dataclass and db config group options in the Hydra ConfigStore singleton', 'summarize_hydra_config_groups': 'summarize how Hydra config groups compose MySQL and PostgreSQL database configs into a main Config'}
```

## File: facebookresearch_hydra/examples/tutorials/structured_configs/3_config_groups/my_app_with_inheritance.py

Prompts

```
['run a Hydra app that prints the resolved config as YAML using config groups for db selection', 'create a MySQLConfig dataclass with driver, host, and port default values for database configuration', 'create a PostGreSQLConfig dataclass with driver, host, port, and timeout default values', 'store a Config dataclass and db config group options in the Hydra ConfigStore singleton', 'summarize how Hydra config groups compose MySQL and PostgreSQL database configs into a main Config', 'run the hydra app with a db config group like mysql or postgresql', 'create a DBConfig dataclass with host, port, and driver fields using omegaconf MISSING', 'build a MySQLConfig dataclass inheriting from DBConfig with mysql driver and port 3306', 'build a PostGreSQLConfig dataclass inheriting from DBConfig with postgresql driver and port 5432', 'register config and db group nodes with ConfigStore for mysql and postgresql options']
```

Usage

```
{'run_hydra_app_with_config_group': 'run the hydra app with a db config group like mysql or postgresql', 'create_db_config_dataclass': 'create a DBConfig dataclass with host, port, and driver fields using omegaconf MISSING', 'build_mysql_config_inheritance': 'build a MySQLConfig dataclass inheriting from DBConfig with mysql driver and port 3306', 'build_postgresql_config_inheritance': 'build a PostGreSQLConfig dataclass inheriting from DBConfig with postgresql driver and port 5432', 'register_config_store_groups': 'register config and db group nodes with ConfigStore for mysql and postgresql options'}
```


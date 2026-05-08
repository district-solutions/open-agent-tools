# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/instantiate/schema/my_app.py

Prompts

```
['run the Hydra app that instantiates a MySQL or PostgreSQL DBConnection using config defaults', 'instantiate a DBConnection object from a Hydra config node using hydra.utils.instantiate', 'create a DBConnection class with driver, host, and port attributes and a connect method', 'register MySQLConfig and PostGreSQLConfig dataclasses with Hydra ConfigStore for db group selection', 'review the DBConfig, MySQLConfig, and PostGreSQLConfig dataclass hierarchy with _target_ for instantiation']
```

Usage

```
{'run_hydra_app_with_db_config': 'run the Hydra app that instantiates a MySQL or PostgreSQL DBConnection using config defaults', 'instantiate_DBConnection_from_config': 'instantiate a DBConnection object from a Hydra config node using hydra.utils.instantiate', 'create_DBConnection_class': 'create a DBConnection class with driver, host, and port attributes and a connect method', 'register_config_with_ConfigStore': 'register MySQLConfig and PostGreSQLConfig dataclasses with Hydra ConfigStore for db group selection', 'review_DBConfig_dataclass_hierarchy': 'review the DBConfig, MySQLConfig, and PostGreSQLConfig dataclass hierarchy with _target_ for instantiation'}
```


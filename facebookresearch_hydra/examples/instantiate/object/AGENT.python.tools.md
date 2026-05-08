# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/instantiate/object/my_app.py

Prompts

```
['run the hydra app that instantiates a database connection from config and calls connect', 'create a MySQLConnection object with host, user, and password parameters', 'create a PostgreSQLConnection object with host, user, password, and database parameters', 'review the DBConnection base class and its connect method signature', 'refactor the my_app function to use hydra instantiate with a different config key']
```

Usage

```
{'run_hydra_instantiate_app': 'run the hydra app that instantiates a database connection from config and calls connect', 'create_mysql_connection': 'create a MySQLConnection object with host, user, and password parameters', 'create_postgresql_connection': 'create a PostgreSQLConnection object with host, user, password, and database parameters', 'review_dbconnection_base_class': 'review the DBConnection base class and its connect method signature', 'refactor_instantiate_pattern': 'refactor the my_app function to use hydra instantiate with a different config key'}
```


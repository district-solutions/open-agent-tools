# Agent Python Tools

- repo: huggingface/datasets
- repo_uri: https://github.com/huggingface/datasets

## File: huggingface_datasets/src/datasets/packaged_modules/sql/sql.py

Prompts

```
['build a HuggingFace dataset from a SQL query using the Sql ArrowBasedBuilder with a database connection', 'create a SqlConfig dataclass with sql query string, database connection, chunksize, and parse_dates options', 'generate PyArrow tables from SQL query results by reading chunks via pandas read_sql', 'cast a PyArrow table to match configured HuggingFace dataset features schema', 'create a deterministic config ID from SqlConfig kwargs by stringifying SQLAlchemy Selectable objects']
```

Usage

```
{'build_sql_dataset': 'build a HuggingFace dataset from a SQL query using the Sql ArrowBasedBuilder with a database connection', 'configure_sqlconfig': 'create a SqlConfig dataclass with sql query string, database connection, chunksize, and parse_dates options', 'generate_sql_tables': 'generate PyArrow tables from SQL query results by reading chunks via pandas read_sql', 'cast_sql_table': 'cast a PyArrow table to match configured HuggingFace dataset features schema', 'create_sql_config_id': 'create a deterministic config ID from SqlConfig kwargs by stringifying SQLAlchemy Selectable objects'}
```


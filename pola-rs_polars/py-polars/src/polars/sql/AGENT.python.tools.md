# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/src/polars/sql/context.py

Prompts

```
['create a SQLContext with polars DataFrames, pandas DataFrames, and pyarrow Tables as SQL tables', 'run a SQL query against registered polars and pandas frames in a SQLContext', 'run a SQL query that auto-registers compatible frames from the current globals scope', 'register multiple polars and pandas frames as named SQL tables in a SQLContext', 'list all registered table names in a SQLContext', 'unregister one or more named tables from a SQLContext', 'execute a SQL query against Polars LazyFrame and DataFrame objects in the global namespace', 'join two Polars LazyFrames using SQL with INNER JOIN and WHERE clause filtering', 'apply SQL column transforms and arithmetic expressions then filter results natively', 'run a SQL query joining Polars LazyFrame with Pandas DataFrame and PyArrow Table', 'execute a SQL query and eagerly collect results into a DataFrame instead of LazyFrame']
```

Usage

```
{'create_SQLContext': 'create a SQLContext with polars DataFrames, pandas DataFrames, and pyarrow Tables as SQL tables', 'run_SQLContext_execute': 'run a SQL query against registered polars and pandas frames in a SQLContext', 'run_SQLContext_execute_global': 'run a SQL query that auto-registers compatible frames from the current globals scope', 'register_SQLContext_tables': 'register multiple polars and pandas frames as named SQL tables in a SQLContext', 'list_SQLContext_tables': 'list all registered table names in a SQLContext', 'unregister_SQLContext_tables': 'unregister one or more named tables from a SQLContext'}
```

## File: pola-rs_polars/py-polars/src/polars/sql/functions.py

Prompts

```
['create a SQLContext with polars DataFrames, pandas DataFrames, and pyarrow Tables as SQL tables', 'run a SQL query against registered polars and pandas frames in a SQLContext', 'run a SQL query that auto-registers compatible frames from the current globals scope', 'register multiple polars and pandas frames as named SQL tables in a SQLContext', 'list all registered table names in a SQLContext', 'unregister one or more named tables from a SQLContext', 'execute a SQL query against Polars LazyFrame and DataFrame objects in the global namespace', 'join two Polars LazyFrames using SQL with INNER JOIN and WHERE clause filtering', 'apply SQL column transforms and arithmetic expressions then filter results natively', 'run a SQL query joining Polars LazyFrame with Pandas DataFrame and PyArrow Table', 'execute a SQL query and eagerly collect results into a DataFrame instead of LazyFrame']
```

Usage

```
{'execute_sql_query': 'execute a SQL query against Polars LazyFrame and DataFrame objects in the global namespace', 'join_lazyframes_sql': 'join two Polars LazyFrames using SQL with INNER JOIN and WHERE clause filtering', 'apply_sql_transforms': 'apply SQL column transforms and arithmetic expressions then filter results natively', 'run_sql_with_mixed_engines': 'run a SQL query joining Polars LazyFrame with Pandas DataFrame and PyArrow Table', 'execute_eager_sql': 'execute a SQL query and eagerly collect results into a DataFrame instead of LazyFrame'}
```


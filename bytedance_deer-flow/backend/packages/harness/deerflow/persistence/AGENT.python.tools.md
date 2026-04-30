# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/persistence/base.py

Prompts

```
['create a SQLAlchemy ORM model that inherits from the DeerFlow Base class for automatic serialization', 'convert a DeerFlow ORM model instance to a plain Python dictionary using the to_dict method', 'convert an ORM model to a dictionary while excluding specific sensitive column keys', 'get a readable string representation of an ORM model instance showing all column values', 'build a custom ORM model by subclassing Base to gain automatic to_dict and repr support', 'create an async SQLAlchemy engine and session factory for a SQLite backend with WAL mode enabled', 'create an async SQLAlchemy engine and session factory for a PostgreSQL backend with connection pooling', 'initialize the async database engine from a DatabaseConfig object with the chosen backend', 'retrieve the async session factory singleton for use by repository classes', 'dispose the async engine and release all database connections at shutdown']
```

Usage

```
{'create_orm_model': 'create a SQLAlchemy ORM model that inherits from the DeerFlow Base class for automatic serialization', 'convert_model_to_dict': 'convert a DeerFlow ORM model instance to a plain Python dictionary using the to_dict method', 'exclude_columns_to_dict': 'convert an ORM model to a dictionary while excluding specific sensitive column keys', 'repr_orm_model': 'get a readable string representation of an ORM model instance showing all column values', 'build_model_with_base': 'build a custom ORM model by subclassing Base to gain automatic to_dict and repr support'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/persistence/engine.py

Prompts

```
['create a SQLAlchemy ORM model that inherits from the DeerFlow Base class for automatic serialization', 'convert a DeerFlow ORM model instance to a plain Python dictionary using the to_dict method', 'convert an ORM model to a dictionary while excluding specific sensitive column keys', 'get a readable string representation of an ORM model instance showing all column values', 'build a custom ORM model by subclassing Base to gain automatic to_dict and repr support', 'create an async SQLAlchemy engine and session factory for a SQLite backend with WAL mode enabled', 'create an async SQLAlchemy engine and session factory for a PostgreSQL backend with connection pooling', 'initialize the async database engine from a DatabaseConfig object with the chosen backend', 'retrieve the async session factory singleton for use by repository classes', 'dispose the async engine and release all database connections at shutdown']
```

Usage

```
{'init_engine_sqlite': 'create an async SQLAlchemy engine and session factory for a SQLite backend with WAL mode enabled', 'init_engine_postgres': 'create an async SQLAlchemy engine and session factory for a PostgreSQL backend with connection pooling', 'init_engine_from_config': 'initialize the async database engine from a DatabaseConfig object with the chosen backend', 'get_session_factory': 'retrieve the async session factory singleton for use by repository classes', 'close_engine': 'dispose the async engine and release all database connections at shutdown'}
```


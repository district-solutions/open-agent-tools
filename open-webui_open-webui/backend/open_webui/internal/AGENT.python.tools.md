# Agent Python Tools

- repo: open-webui/open-webui
- repo_uri: https://github.com/open-webui/open-webui

## File: open-webui_open-webui/backend/open_webui/internal/db.py

Prompts

```
['create a SQLAlchemy JSONField TypeDecorator that serializes Python objects to JSON text and deserializes on read', 'run peewee database migrations using the handle_peewee_migration function with a database URL', 'create a SQLAlchemy engine configured for sqlite, sqlcipher, or postgresql with connection pooling', 'test the get_session generator function that yields a scoped database session and closes it afterward', 'summarize the get_db_context context manager that optionally reuses an existing session or creates a new one', 'create a database connection by calling register_connection with a PostgreSQL or SQLite database URL', 'build a ReconnectingPostgresqlDatabase instance that auto-reconnects on psycopg2 and peewee interface errors', 'test the PeeweeConnectionState class for thread-safe database state management using context variables', 'review the CustomReconnectMixin class that extends ReconnectMixin with custom reconnect error handling for psycopg2 and peewee', 'summarize the register_connection function that supports PostgreSQL, SQLite, and SQLCipher encrypted SQLite database URLs']
```

Usage

```
{'create_json_field': 'create a SQLAlchemy JSONField TypeDecorator that serializes Python objects to JSON text and deserializes on read', 'run_handle_peewee_migration': 'run peewee database migrations using the handle_peewee_migration function with a database URL', 'create_sqlalchemy_engine': 'create a SQLAlchemy engine configured for sqlite, sqlcipher, or postgresql with connection pooling', 'test_get_session': 'test the get_session generator function that yields a scoped database session and closes it afterward', 'summarize_get_db_context': 'summarize the get_db_context context manager that optionally reuses an existing session or creates a new one'}
```

## File: open-webui_open-webui/backend/open_webui/internal/wrappers.py

Prompts

```
['create a SQLAlchemy JSONField TypeDecorator that serializes Python objects to JSON text and deserializes on read', 'run peewee database migrations using the handle_peewee_migration function with a database URL', 'create a SQLAlchemy engine configured for sqlite, sqlcipher, or postgresql with connection pooling', 'test the get_session generator function that yields a scoped database session and closes it afterward', 'summarize the get_db_context context manager that optionally reuses an existing session or creates a new one', 'create a database connection by calling register_connection with a PostgreSQL or SQLite database URL', 'build a ReconnectingPostgresqlDatabase instance that auto-reconnects on psycopg2 and peewee interface errors', 'test the PeeweeConnectionState class for thread-safe database state management using context variables', 'review the CustomReconnectMixin class that extends ReconnectMixin with custom reconnect error handling for psycopg2 and peewee', 'summarize the register_connection function that supports PostgreSQL, SQLite, and SQLCipher encrypted SQLite database URLs']
```

Usage

```
{'create_register_connection': 'create a database connection by calling register_connection with a PostgreSQL or SQLite database URL', 'build_reconnecting_postgresql': 'build a ReconnectingPostgresqlDatabase instance that auto-reconnects on psycopg2 and peewee interface errors', 'test_peewee_connection_state': 'test the PeeweeConnectionState class for thread-safe database state management using context variables', 'review_custom_reconnect_mixin': 'review the CustomReconnectMixin class that extends ReconnectMixin with custom reconnect error handling for psycopg2 and peewee', 'summarize_register_connection': 'summarize the register_connection function that supports PostgreSQL, SQLite, and SQLCipher encrypted SQLite database URLs'}
```


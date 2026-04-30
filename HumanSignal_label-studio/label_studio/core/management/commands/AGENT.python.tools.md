# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/core/management/commands/locked_migrate.py

Prompts

```
['run django migrations safely using a postgres advisory transaction lock with retry logic', 'run django migrations with a custom --migrate-lock-id advisory lock identifier', 'test the acquire_lock_with_retry method that retries postgres advisory lock acquisition with timeout', 'refactor the handle method to use a separate database connection for holding the migration lock', 'summarize the locked_migrate command that wraps django migrate with postgres advisory transaction locks', 'run the Django management command show_async_migrations to display all async migration statuses', 'run the Django management command show_async_migrations with an organization id to filter migrations', 'summarize the Django management command Command that displays async migration statuses', 'review the add_arguments method that defines the --organization CLI argument', 'review the handle method that queries and prints AsyncMigrationStatus records']
```

Usage

```
{'run_locked_migrate': 'run django migrations safely using a postgres advisory transaction lock with retry logic', 'run_locked_migrate_custom_id': 'run django migrations with a custom --migrate-lock-id advisory lock identifier', 'test_acquire_lock_with_retry': 'test the acquire_lock_with_retry method that retries postgres advisory lock acquisition with timeout', 'refactor_handle_transaction': 'refactor the handle method to use a separate database connection for holding the migration lock', 'summarize_locked_migrate': 'summarize the locked_migrate command that wraps django migrate with postgres advisory transaction locks'}
```

## File: HumanSignal_label-studio/label_studio/core/management/commands/show_async_migrations.py

Prompts

```
['run django migrations safely using a postgres advisory transaction lock with retry logic', 'run django migrations with a custom --migrate-lock-id advisory lock identifier', 'test the acquire_lock_with_retry method that retries postgres advisory lock acquisition with timeout', 'refactor the handle method to use a separate database connection for holding the migration lock', 'summarize the locked_migrate command that wraps django migrate with postgres advisory transaction locks', 'run the Django management command show_async_migrations to display all async migration statuses', 'run the Django management command show_async_migrations with an organization id to filter migrations', 'summarize the Django management command Command that displays async migration statuses', 'review the add_arguments method that defines the --organization CLI argument', 'review the handle method that queries and prints AsyncMigrationStatus records']
```

Usage

```
{'run_show_async_migrations': 'run the Django management command show_async_migrations to display all async migration statuses', 'run_show_async_migrations_org': 'run the Django management command show_async_migrations with an organization id to filter migrations', 'summarize_Command': 'summarize the Django management command Command that displays async migration statuses', 'review_add_arguments': 'review the add_arguments method that defines the --organization CLI argument', 'review_handle': 'review the handle method that queries and prints AsyncMigrationStatus records'}
```


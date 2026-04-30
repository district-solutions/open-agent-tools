# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/core/tests/test_db_utils.py

Prompts

```
['test the batch_delete function handles empty querysets gracefully and returns 0', 'test the batch_delete function deletes all items when count is less than batch_size', 'test the batch_delete function deletes items across multiple batches correctly', 'test the batch_delete function works correctly inside a Django transaction', 'test the current_db_key function falls back to vendor:unknown on connection errors', 'test execute_sql_job creates an AsyncMigrationStatus record with FINISHED status after executing SQL', 'test execute_sql_job skips SQL execution when a migration already has FINISHED status', 'test execute_sql_job skips SQLite execution when apply_on_sqlite is False', 'test execute_sql_job marks migration status as ERROR and stores error message on exception', 'test make_sql_migration returns callable pairs that execute reverse SQL immediately on rollback', 'test DeletedRow.serialize_and_create for an Organization model instance', 'test DeletedRow.serialize_and_create for a Project model instance', 'test DeletedRow.serialize_and_create for a Task model instance with organization and project context', 'test DeletedRow.bulk_serialize_and_create for multiple Organization, Project, and Task objects', 'test DeletedRow restore workflow serializes, deletes, and rehydrates objects to match originals', 'test is_job_on_worker avoids calling StartedJobRegistry.get_job_ids and uses Redis ZSCORE instead', 'test is_job_on_worker returns False without touching Redis when job_id is None', 'test is_job_on_worker is safe from non-main thread signal errors by using ZSCORE membership check', 'test is_job_on_worker calls Redis connection.zscore with the correct registry key and encoded job id', 'test is_job_on_worker executed in a background thread without raising signal-related exceptions']
```

Usage

```
{'test_batch_delete_empty_queryset': 'test the batch_delete function handles empty querysets gracefully and returns 0', 'test_batch_delete_single_batch': 'test the batch_delete function deletes all items when count is less than batch_size', 'test_batch_delete_multiple_batches': 'test the batch_delete function deletes items across multiple batches correctly', 'test_batch_delete_with_transaction': 'test the batch_delete function works correctly inside a Django transaction', 'test_current_db_key_exception_path': 'test the current_db_key function falls back to vendor:unknown on connection errors'}
```

## File: HumanSignal_label-studio/label_studio/core/tests/test_migration_helpers.py

Prompts

```
['test the batch_delete function handles empty querysets gracefully and returns 0', 'test the batch_delete function deletes all items when count is less than batch_size', 'test the batch_delete function deletes items across multiple batches correctly', 'test the batch_delete function works correctly inside a Django transaction', 'test the current_db_key function falls back to vendor:unknown on connection errors', 'test execute_sql_job creates an AsyncMigrationStatus record with FINISHED status after executing SQL', 'test execute_sql_job skips SQL execution when a migration already has FINISHED status', 'test execute_sql_job skips SQLite execution when apply_on_sqlite is False', 'test execute_sql_job marks migration status as ERROR and stores error message on exception', 'test make_sql_migration returns callable pairs that execute reverse SQL immediately on rollback', 'test DeletedRow.serialize_and_create for an Organization model instance', 'test DeletedRow.serialize_and_create for a Project model instance', 'test DeletedRow.serialize_and_create for a Task model instance with organization and project context', 'test DeletedRow.bulk_serialize_and_create for multiple Organization, Project, and Task objects', 'test DeletedRow restore workflow serializes, deletes, and rehydrates objects to match originals', 'test is_job_on_worker avoids calling StartedJobRegistry.get_job_ids and uses Redis ZSCORE instead', 'test is_job_on_worker returns False without touching Redis when job_id is None', 'test is_job_on_worker is safe from non-main thread signal errors by using ZSCORE membership check', 'test is_job_on_worker calls Redis connection.zscore with the correct registry key and encoded job id', 'test is_job_on_worker executed in a background thread without raising signal-related exceptions']
```

Usage

```
{'test_execute_sql_job_creates_status': 'test execute_sql_job creates an AsyncMigrationStatus record with FINISHED status after executing SQL', 'test_execute_sql_job_skips_finished': 'test execute_sql_job skips SQL execution when a migration already has FINISHED status', 'test_execute_sql_job_handles_sqlite': 'test execute_sql_job skips SQLite execution when apply_on_sqlite is False', 'test_execute_sql_job_marks_errors': 'test execute_sql_job marks migration status as ERROR and stores error message on exception', 'test_make_sql_migration_runs_backwards': 'test make_sql_migration returns callable pairs that execute reverse SQL immediately on rollback'}
```

## File: HumanSignal_label-studio/label_studio/core/tests/test_models.py

Prompts

```
['test the batch_delete function handles empty querysets gracefully and returns 0', 'test the batch_delete function deletes all items when count is less than batch_size', 'test the batch_delete function deletes items across multiple batches correctly', 'test the batch_delete function works correctly inside a Django transaction', 'test the current_db_key function falls back to vendor:unknown on connection errors', 'test execute_sql_job creates an AsyncMigrationStatus record with FINISHED status after executing SQL', 'test execute_sql_job skips SQL execution when a migration already has FINISHED status', 'test execute_sql_job skips SQLite execution when apply_on_sqlite is False', 'test execute_sql_job marks migration status as ERROR and stores error message on exception', 'test make_sql_migration returns callable pairs that execute reverse SQL immediately on rollback', 'test DeletedRow.serialize_and_create for an Organization model instance', 'test DeletedRow.serialize_and_create for a Project model instance', 'test DeletedRow.serialize_and_create for a Task model instance with organization and project context', 'test DeletedRow.bulk_serialize_and_create for multiple Organization, Project, and Task objects', 'test DeletedRow restore workflow serializes, deletes, and rehydrates objects to match originals', 'test is_job_on_worker avoids calling StartedJobRegistry.get_job_ids and uses Redis ZSCORE instead', 'test is_job_on_worker returns False without touching Redis when job_id is None', 'test is_job_on_worker is safe from non-main thread signal errors by using ZSCORE membership check', 'test is_job_on_worker calls Redis connection.zscore with the correct registry key and encoded job id', 'test is_job_on_worker executed in a background thread without raising signal-related exceptions']
```

Usage

```
{'test_DeleteRow_serialize_organization': 'test DeletedRow.serialize_and_create for an Organization model instance', 'test_DeleteRow_serialize_project': 'test DeletedRow.serialize_and_create for a Project model instance', 'test_DeleteRow_serialize_task': 'test DeletedRow.serialize_and_create for a Task model instance with organization and project context', 'test_DeleteRow_bulk_serialize': 'test DeletedRow.bulk_serialize_and_create for multiple Organization, Project, and Task objects', 'test_DeleteRow_restore_after_delete': 'test DeletedRow restore workflow serializes, deletes, and rehydrates objects to match originals'}
```

## File: HumanSignal_label-studio/label_studio/core/tests/test_redis.py

Prompts

```
['test the batch_delete function handles empty querysets gracefully and returns 0', 'test the batch_delete function deletes all items when count is less than batch_size', 'test the batch_delete function deletes items across multiple batches correctly', 'test the batch_delete function works correctly inside a Django transaction', 'test the current_db_key function falls back to vendor:unknown on connection errors', 'test execute_sql_job creates an AsyncMigrationStatus record with FINISHED status after executing SQL', 'test execute_sql_job skips SQL execution when a migration already has FINISHED status', 'test execute_sql_job skips SQLite execution when apply_on_sqlite is False', 'test execute_sql_job marks migration status as ERROR and stores error message on exception', 'test make_sql_migration returns callable pairs that execute reverse SQL immediately on rollback', 'test DeletedRow.serialize_and_create for an Organization model instance', 'test DeletedRow.serialize_and_create for a Project model instance', 'test DeletedRow.serialize_and_create for a Task model instance with organization and project context', 'test DeletedRow.bulk_serialize_and_create for multiple Organization, Project, and Task objects', 'test DeletedRow restore workflow serializes, deletes, and rehydrates objects to match originals', 'test is_job_on_worker avoids calling StartedJobRegistry.get_job_ids and uses Redis ZSCORE instead', 'test is_job_on_worker returns False without touching Redis when job_id is None', 'test is_job_on_worker is safe from non-main thread signal errors by using ZSCORE membership check', 'test is_job_on_worker calls Redis connection.zscore with the correct registry key and encoded job id', 'test is_job_on_worker executed in a background thread without raising signal-related exceptions']
```

Usage

```
{'test_is_job_on_worker_does_not_call_get_job_ids': 'test is_job_on_worker avoids calling StartedJobRegistry.get_job_ids and uses Redis ZSCORE instead', 'test_is_job_on_worker_none_short_circuits': 'test is_job_on_worker returns False without touching Redis when job_id is None', 'test_is_job_on_worker_thread_safe': 'test is_job_on_worker is safe from non-main thread signal errors by using ZSCORE membership check', 'test_is_job_on_worker_uses_zscore': 'test is_job_on_worker calls Redis connection.zscore with the correct registry key and encoded job id', 'test_is_job_on_worker_thread_execution': 'test is_job_on_worker executed in a background thread without raising signal-related exceptions'}
```


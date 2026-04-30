# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/jobs/mongodb_migration/tests/test_deletion_migrations.py

Prompts

```
['test the CacheDeletionMigration class that removes cache entries by kind from MongoDB', 'test the QueueDeletionMigration class that removes jobs by type from the MongoDB queue', 'test the MigrationDeleteJobsByStatus class that deletes queue jobs matching specific statuses', 'test the MigrationRemoveFieldFromJob class that removes a specified field from queue documents', 'test the MigrationRemoveFieldFromCache class that removes a specified field from cache documents', 'test the MigrationsMongoResource by creating a mongo database alias and verifying it is available', 'test that a MigrationsMongoResource instance reports is_available after initialization', 'test that a MigrationsMongoResource can be released after use', 'test a mongoengine Document using a MigrationsMongoResource db_alias in its meta configuration', 'test dropping a mongoengine Document collection after verifying it is empty']
```

Usage

```
{'test_cache_deletion_migration': 'test the CacheDeletionMigration class that removes cache entries by kind from MongoDB', 'test_queue_deletion_migration': 'test the QueueDeletionMigration class that removes jobs by type from the MongoDB queue', 'test_queue_delete_jobs_by_status': 'test the MigrationDeleteJobsByStatus class that deletes queue jobs matching specific statuses', 'test_queue_remove_field': 'test the MigrationRemoveFieldFromJob class that removes a specified field from queue documents', 'test_cache_remove_field': 'test the MigrationRemoveFieldFromCache class that removes a specified field from cache documents'}
```

## File: huggingface_dataset-viewer/jobs/mongodb_migration/tests/test_resources.py

Prompts

```
['test the CacheDeletionMigration class that removes cache entries by kind from MongoDB', 'test the QueueDeletionMigration class that removes jobs by type from the MongoDB queue', 'test the MigrationDeleteJobsByStatus class that deletes queue jobs matching specific statuses', 'test the MigrationRemoveFieldFromJob class that removes a specified field from queue documents', 'test the MigrationRemoveFieldFromCache class that removes a specified field from cache documents', 'test the MigrationsMongoResource by creating a mongo database alias and verifying it is available', 'test that a MigrationsMongoResource instance reports is_available after initialization', 'test that a MigrationsMongoResource can be released after use', 'test a mongoengine Document using a MigrationsMongoResource db_alias in its meta configuration', 'test dropping a mongoengine Document collection after verifying it is empty']
```

Usage

```
{'test_cache_database': 'test the MigrationsMongoResource by creating a mongo database alias and verifying it is available', 'test_MigrationsMongoResource_is_available': 'test that a MigrationsMongoResource instance reports is_available after initialization', 'test_MigrationsMongoResource_release': 'test that a MigrationsMongoResource can be released after use', 'test_MongoEngine_document_with_alias': 'test a mongoengine Document using a MigrationsMongoResource db_alias in its meta configuration', 'test_MongoEngine_drop_collection': 'test dropping a mongoengine Document collection after verifying it is empty'}
```


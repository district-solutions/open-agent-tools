# Agent Python Tools

- repo: HumanSignal/label-studio
- repo_uri: https://github.com/HumanSignal/label-studio

## File: HumanSignal_label-studio/label_studio/io_storages/redis/models.py

Prompts

```
['build a Redis import storage that reads JSON task files from Redis keys matching a path prefix', 'build a Redis export storage that serializes and stores Django annotations as JSON objects in Redis', 'test a Redis storage connection by validating the host, port, password, and database ID configuration', 'create an automatic Redis export pipeline that saves new annotations to Redis on Django post_save signal', 'run Redis key iteration over a storage path prefix and retrieve task data from matching Redis keys', 'create a RedisImportStorageSerializer to validate and serialize Redis import storage configuration', 'create a RedisExportStorageSerializer to serialize Redis export storage configuration', 'test the RedisImportStorageSerializer validate method to verify Redis server connectivity', 'review the to_representation method that removes password from serialized output', 'build a DRF serializer for Redis import/export storage with connection validation and password masking']
```

Usage

```
{'build_redis_import_storage': 'build a Redis import storage that reads JSON task files from Redis keys matching a path prefix', 'build_redis_export_storage': 'build a Redis export storage that serializes and stores Django annotations as JSON objects in Redis', 'test_redis_connection': 'test a Redis storage connection by validating the host, port, password, and database ID configuration', 'create_redis_annotation_export': 'create an automatic Redis export pipeline that saves new annotations to Redis on Django post_save signal', 'run_redis_key_iteration': 'run Redis key iteration over a storage path prefix and retrieve task data from matching Redis keys'}
```

## File: HumanSignal_label-studio/label_studio/io_storages/redis/serializers.py

Prompts

```
['build a Redis import storage that reads JSON task files from Redis keys matching a path prefix', 'build a Redis export storage that serializes and stores Django annotations as JSON objects in Redis', 'test a Redis storage connection by validating the host, port, password, and database ID configuration', 'create an automatic Redis export pipeline that saves new annotations to Redis on Django post_save signal', 'run Redis key iteration over a storage path prefix and retrieve task data from matching Redis keys', 'create a RedisImportStorageSerializer to validate and serialize Redis import storage configuration', 'create a RedisExportStorageSerializer to serialize Redis export storage configuration', 'test the RedisImportStorageSerializer validate method to verify Redis server connectivity', 'review the to_representation method that removes password from serialized output', 'build a DRF serializer for Redis import/export storage with connection validation and password masking']
```

Usage

```
{'create_RedisImportStorageSerializer': 'create a RedisImportStorageSerializer to validate and serialize Redis import storage configuration', 'create_RedisExportStorageSerializer': 'create a RedisExportStorageSerializer to serialize Redis export storage configuration', 'test_validate_connection': 'test the RedisImportStorageSerializer validate method to verify Redis server connectivity', 'review_to_representation': 'review the to_representation method that removes password from serialized output', 'build_redis_storage_serializer': 'build a DRF serializer for Redis import/export storage with connection validation and password masking'}
```


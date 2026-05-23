# Agent Python Tools

- repo: facebookresearch/personal-timeline
- repo_uri: https://github.com/facebookresearch/personal-timeline

## File: facebookresearch_personal-timeline/src/common/persistence/key_value_db.py

Prompts

```
['build a singleton CacheDBConnector that initializes a SQLite database for geo and reverse geo caching', 'create the geo_cache and reverse_geo_cache tables with unique key indexes on startup', 'test the get method to retrieve a cached value by key from a specified table', 'refactor the put method to insert key value pairs into the geo_cache or reverse_geo_cache table', 'review the execute_write method that commits and executes SQL statements with optional parameters', 'initialize the PersonalDataDBConnector singleton to create SQLite tables and bootstrap data sources', 'insert or upsert a record into the personal_data table using a unique key for conflict resolution', 'query the personal_data table with custom select columns and optional where conditions', 'insert a photo record with an LLEntry object including timestamp, filename, and pickled data', 'check if a photo with a given source, filename, and timestamp already exists in the database']
```

Usage

```
{'build_singleton_cache_connector': 'build a singleton CacheDBConnector that initializes a SQLite database for geo and reverse geo caching', 'create_setup_tables': 'create the geo_cache and reverse_geo_cache tables with unique key indexes on startup', 'test_get_value': 'test the get method to retrieve a cached value by key from a specified table', 'refactor_put_method': 'refactor the put method to insert key value pairs into the geo_cache or reverse_geo_cache table', 'review_execute_write': 'review the execute_write method that commits and executes SQL statements with optional parameters'}
```

## File: facebookresearch_personal-timeline/src/common/persistence/personal_data_db.py

Prompts

```
['build a singleton CacheDBConnector that initializes a SQLite database for geo and reverse geo caching', 'create the geo_cache and reverse_geo_cache tables with unique key indexes on startup', 'test the get method to retrieve a cached value by key from a specified table', 'refactor the put method to insert key value pairs into the geo_cache or reverse_geo_cache table', 'review the execute_write method that commits and executes SQL statements with optional parameters', 'initialize the PersonalDataDBConnector singleton to create SQLite tables and bootstrap data sources', 'insert or upsert a record into the personal_data table using a unique key for conflict resolution', 'query the personal_data table with custom select columns and optional where conditions', 'insert a photo record with an LLEntry object including timestamp, filename, and pickled data', 'check if a photo with a given source, filename, and timestamp already exists in the database']
```

Usage

```
{'setup_personal_data_db': 'initialize the PersonalDataDBConnector singleton to create SQLite tables and bootstrap data sources', 'add_or_replace_personal_data': 'insert or upsert a record into the personal_data table using a unique key for conflict resolution', 'search_personal_data': 'query the personal_data table with custom select columns and optional where conditions', 'add_photo': 'insert a photo record with an LLEntry object including timestamp, filename, and pickled data', 'is_same_photo_present': 'check if a photo with a given source, filename, and timestamp already exists in the database'}
```


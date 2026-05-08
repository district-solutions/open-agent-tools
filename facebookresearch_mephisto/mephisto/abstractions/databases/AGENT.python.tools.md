# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/databases/local_database.py

Prompts

```
['create a new project in the local mephisto database with a given project name', 'create a new task in the local mephisto database linked to an existing project', 'create a new task run entry with requester id, provider type, and init params', 'create a new agent assigned to a unit with worker id and task run id', 'create a new unit within an assignment with pay amount and unit index', 'create a MephistoSingletonDB instance with an optional database path for in-memory caching of all data model objects', "shutdown the MephistoSingletonDB by closing the current thread's database connection and removing it from the connection pool", 'cache a loaded data model object in the singleton cache by its class type and db_id for fast subsequent lookups', 'optimized_load a cached data model object by class and db_id from the singleton cache without hitting disk', 'find all units for a given assignment_id using the cached assignment-to-unit mapping for fast lookup']
```

Usage

```
{'create_mephisto_project': 'create a new project in the local mephisto database with a given project name', 'create_mephisto_task': 'create a new task in the local mephisto database linked to an existing project', 'create_mephisto_task_run': 'create a new task run entry with requester id, provider type, and init params', 'create_mephisto_agent': 'create a new agent assigned to a unit with worker id and task run id', 'create_mephisto_unit': 'create a new unit within an assignment with pay amount and unit index'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/databases/local_singleton_database.py

Prompts

```
['create a new project in the local mephisto database with a given project name', 'create a new task in the local mephisto database linked to an existing project', 'create a new task run entry with requester id, provider type, and init params', 'create a new agent assigned to a unit with worker id and task run id', 'create a new unit within an assignment with pay amount and unit index', 'create a MephistoSingletonDB instance with an optional database path for in-memory caching of all data model objects', "shutdown the MephistoSingletonDB by closing the current thread's database connection and removing it from the connection pool", 'cache a loaded data model object in the singleton cache by its class type and db_id for fast subsequent lookups', 'optimized_load a cached data model object by class and db_id from the singleton cache without hitting disk', 'find all units for a given assignment_id using the cached assignment-to-unit mapping for fast lookup']
```

Usage

```
{'create_singleton_db': 'create a MephistoSingletonDB instance with an optional database path for in-memory caching of all data model objects', 'shutdown_db_connections': "shutdown the MephistoSingletonDB by closing the current thread's database connection and removing it from the connection pool", 'cache_load_result': 'cache a loaded data model object in the singleton cache by its class type and db_id for fast subsequent lookups', 'optimized_load_cached': 'optimized_load a cached data model object by class and db_id from the singleton cache without hitting disk', 'find_units_by_assignment': 'find all units for a given assignment_id using the cached assignment-to-unit mapping for fast lookup'}
```


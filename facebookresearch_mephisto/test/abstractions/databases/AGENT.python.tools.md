# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/abstractions/databases/test_local_database.py

Prompts

```
['test the LocalMephistoDB SQLite database implementation using unittest and BaseDatabaseTests', 'run the unit tests for LocalMephistoDB to verify all data model CRUD operations pass', 'review the BaseDatabaseTests parent class to understand inherited test coverage for LocalMephistoDB', 'create a test fixture for LocalMephistoDB using a temporary directory and SQLite database path', 'refactor the TestLocalMephistoDB class to add custom tests beyond inherited BaseDatabaseTests', 'test the MephistoSingletonDB class by running the unit test suite with python unittest', 'run the test that ensures all database tables are empty on initialization', 'test creating, querying, and retrieving projects in the Mephisto singleton database', 'test creating tasks and task runs with the Mephisto singleton database', 'test the full lifecycle of agents, assignments, and units in the singleton database']
```

Usage

```
{'test_LocalMephistoDB': 'test the LocalMephistoDB SQLite database implementation using unittest and BaseDatabaseTests', 'run_test_LocalMephistoDB': 'run the unit tests for LocalMephistoDB to verify all data model CRUD operations pass', 'review_BaseDatabaseTests': 'review the BaseDatabaseTests parent class to understand inherited test coverage for LocalMephistoDB', 'create_test_LocalMephistoDB': 'create a test fixture for LocalMephistoDB using a temporary directory and SQLite database path', 'refactor_TestLocalMephistoDB': 'refactor the TestLocalMephistoDB class to add custom tests beyond inherited BaseDatabaseTests'}
```

## File: facebookresearch_mephisto/test/abstractions/databases/test_singleton_database.py

Prompts

```
['test the LocalMephistoDB SQLite database implementation using unittest and BaseDatabaseTests', 'run the unit tests for LocalMephistoDB to verify all data model CRUD operations pass', 'review the BaseDatabaseTests parent class to understand inherited test coverage for LocalMephistoDB', 'create a test fixture for LocalMephistoDB using a temporary directory and SQLite database path', 'refactor the TestLocalMephistoDB class to add custom tests beyond inherited BaseDatabaseTests', 'test the MephistoSingletonDB class by running the unit test suite with python unittest', 'run the test that ensures all database tables are empty on initialization', 'test creating, querying, and retrieving projects in the Mephisto singleton database', 'test creating tasks and task runs with the Mephisto singleton database', 'test the full lifecycle of agents, assignments, and units in the singleton database']
```

Usage

```
{'test_MephistoSingletonDB': 'test the MephistoSingletonDB class by running the unit test suite with python unittest', 'run_test_all_types_init_empty': 'run the test that ensures all database tables are empty on initialization', 'test_project_crud': 'test creating, querying, and retrieving projects in the Mephisto singleton database', 'test_task_and_task_run': 'test creating tasks and task runs with the Mephisto singleton database', 'test_agent_and_assignment_lifecycle': 'test the full lifecycle of agents, assignments, and units in the singleton database'}
```


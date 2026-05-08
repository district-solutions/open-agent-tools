# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/test/architect_tester.py

Prompts

```
['test that an Architect subclass can be initialized with default arguments and correct type', 'test the server preparation and cleanup lifecycle for an Architect subclass', 'test deploying a server via an Architect and verify it shuts down cleanly', 'test if a server is running by pinging its is_alive endpoint and checking status code', 'review an ArchitectTests subclass implementation to verify server_is_prepared, server_is_cleaned, and server_is_shutdown methods', 'test the BlueprintTests class to ensure all AgentStateClass status values are valid and complete', 'test the BlueprintTests class to verify a Blueprint has required TaskRunnerClass, AgentStateClass, and TaskBuilderClass members', 'test the BlueprintTests class to ensure abstract initialization produces correct TaskRunner and TaskBuilder subclasses', 'test the BlueprintTests class to verify a task can be built from scratch using TaskBuilder.build_in_dir', 'test the BlueprintTests class to ensure a task runner handles agent disconnection and cleanup gracefully', 'test that initializing a crowd provider registers a datastore with the Mephisto database', 'test creating a requester via RequesterClass.new and retrieving it from the database by db_id', 'test requester credential registration and verify available budget matches expected test account balance', 'test creating a worker, blocking and unblocking it for a requester, and verifying block status', 'review the CrowdProviderTests base class to understand the testing interface for crowd provider subclasses', 'test the MephistoDB class by creating, querying, and validating project entities in the database', 'test the MephistoDB class by creating, updating, and querying task entities with project associations', 'test the MephistoDB class by creating task runs and assignments and verifying their relationships', 'test the MephistoDB class by creating units and agents and updating their status states', 'test the MephistoDB class by creating, granting, updating, revoking, and deleting worker qualifications']
```

Usage

```
{'test_architect_initialization': 'test that an Architect subclass can be initialized with default arguments and correct type', 'test_server_prepare_cleanup': 'test the server preparation and cleanup lifecycle for an Architect subclass', 'test_server_deploy_shutdown': 'test deploying a server via an Architect and verify it shuts down cleanly', 'test_server_is_up': 'test if a server is running by pinging its is_alive endpoint and checking status code', 'review_architect_test_subclass': 'review an ArchitectTests subclass implementation to verify server_is_prepared, server_is_cleaned, and server_is_shutdown methods'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/test/blueprint_tester.py

Prompts

```
['test that an Architect subclass can be initialized with default arguments and correct type', 'test the server preparation and cleanup lifecycle for an Architect subclass', 'test deploying a server via an Architect and verify it shuts down cleanly', 'test if a server is running by pinging its is_alive endpoint and checking status code', 'review an ArchitectTests subclass implementation to verify server_is_prepared, server_is_cleaned, and server_is_shutdown methods', 'test the BlueprintTests class to ensure all AgentStateClass status values are valid and complete', 'test the BlueprintTests class to verify a Blueprint has required TaskRunnerClass, AgentStateClass, and TaskBuilderClass members', 'test the BlueprintTests class to ensure abstract initialization produces correct TaskRunner and TaskBuilder subclasses', 'test the BlueprintTests class to verify a task can be built from scratch using TaskBuilder.build_in_dir', 'test the BlueprintTests class to ensure a task runner handles agent disconnection and cleanup gracefully', 'test that initializing a crowd provider registers a datastore with the Mephisto database', 'test creating a requester via RequesterClass.new and retrieving it from the database by db_id', 'test requester credential registration and verify available budget matches expected test account balance', 'test creating a worker, blocking and unblocking it for a requester, and verifying block status', 'review the CrowdProviderTests base class to understand the testing interface for crowd provider subclasses', 'test the MephistoDB class by creating, querying, and validating project entities in the database', 'test the MephistoDB class by creating, updating, and querying task entities with project associations', 'test the MephistoDB class by creating task runs and assignments and verifying their relationships', 'test the MephistoDB class by creating units and agents and updating their status states', 'test the MephistoDB class by creating, granting, updating, revoking, and deleting worker qualifications']
```

Usage

```
{'test_blueprint_agent_statuses': 'test the BlueprintTests class to ensure all AgentStateClass status values are valid and complete', 'test_blueprint_required_members': 'test the BlueprintTests class to verify a Blueprint has required TaskRunnerClass, AgentStateClass, and TaskBuilderClass members', 'test_blueprint_initialization': 'test the BlueprintTests class to ensure abstract initialization produces correct TaskRunner and TaskBuilder subclasses', 'test_blueprint_task_building': 'test the BlueprintTests class to verify a task can be built from scratch using TaskBuilder.build_in_dir', 'test_blueprint_graceful_exit': 'test the BlueprintTests class to ensure a task runner handles agent disconnection and cleanup gracefully'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/test/crowd_provider_tester.py

Prompts

```
['test that an Architect subclass can be initialized with default arguments and correct type', 'test the server preparation and cleanup lifecycle for an Architect subclass', 'test deploying a server via an Architect and verify it shuts down cleanly', 'test if a server is running by pinging its is_alive endpoint and checking status code', 'review an ArchitectTests subclass implementation to verify server_is_prepared, server_is_cleaned, and server_is_shutdown methods', 'test the BlueprintTests class to ensure all AgentStateClass status values are valid and complete', 'test the BlueprintTests class to verify a Blueprint has required TaskRunnerClass, AgentStateClass, and TaskBuilderClass members', 'test the BlueprintTests class to ensure abstract initialization produces correct TaskRunner and TaskBuilder subclasses', 'test the BlueprintTests class to verify a task can be built from scratch using TaskBuilder.build_in_dir', 'test the BlueprintTests class to ensure a task runner handles agent disconnection and cleanup gracefully', 'test that initializing a crowd provider registers a datastore with the Mephisto database', 'test creating a requester via RequesterClass.new and retrieving it from the database by db_id', 'test requester credential registration and verify available budget matches expected test account balance', 'test creating a worker, blocking and unblocking it for a requester, and verifying block status', 'review the CrowdProviderTests base class to understand the testing interface for crowd provider subclasses', 'test the MephistoDB class by creating, querying, and validating project entities in the database', 'test the MephistoDB class by creating, updating, and querying task entities with project associations', 'test the MephistoDB class by creating task runs and assignments and verifying their relationships', 'test the MephistoDB class by creating units and agents and updating their status states', 'test the MephistoDB class by creating, granting, updating, revoking, and deleting worker qualifications']
```

Usage

```
{'test_crowd_provider_datastore_registration': 'test that initializing a crowd provider registers a datastore with the Mephisto database', 'test_requester_creation_and_retrieval': 'test creating a requester via RequesterClass.new and retrieving it from the database by db_id', 'test_requester_registration_and_budget': 'test requester credential registration and verify available budget matches expected test account balance', 'test_worker_creation_and_blocking': 'test creating a worker, blocking and unblocking it for a requester, and verifying block status', 'review_crowd_provider_test_base_class': 'review the CrowdProviderTests base class to understand the testing interface for crowd provider subclasses'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/test/data_model_database_tester.py

Prompts

```
['test that an Architect subclass can be initialized with default arguments and correct type', 'test the server preparation and cleanup lifecycle for an Architect subclass', 'test deploying a server via an Architect and verify it shuts down cleanly', 'test if a server is running by pinging its is_alive endpoint and checking status code', 'review an ArchitectTests subclass implementation to verify server_is_prepared, server_is_cleaned, and server_is_shutdown methods', 'test the BlueprintTests class to ensure all AgentStateClass status values are valid and complete', 'test the BlueprintTests class to verify a Blueprint has required TaskRunnerClass, AgentStateClass, and TaskBuilderClass members', 'test the BlueprintTests class to ensure abstract initialization produces correct TaskRunner and TaskBuilder subclasses', 'test the BlueprintTests class to verify a task can be built from scratch using TaskBuilder.build_in_dir', 'test the BlueprintTests class to ensure a task runner handles agent disconnection and cleanup gracefully', 'test that initializing a crowd provider registers a datastore with the Mephisto database', 'test creating a requester via RequesterClass.new and retrieving it from the database by db_id', 'test requester credential registration and verify available budget matches expected test account balance', 'test creating a worker, blocking and unblocking it for a requester, and verifying block status', 'review the CrowdProviderTests base class to understand the testing interface for crowd provider subclasses', 'test the MephistoDB class by creating, querying, and validating project entities in the database', 'test the MephistoDB class by creating, updating, and querying task entities with project associations', 'test the MephistoDB class by creating task runs and assignments and verifying their relationships', 'test the MephistoDB class by creating units and agents and updating their status states', 'test the MephistoDB class by creating, granting, updating, revoking, and deleting worker qualifications']
```

Usage

```
{'test_MephistoDB_project_crud': 'test the MephistoDB class by creating, querying, and validating project entities in the database', 'test_MephistoDB_task_crud': 'test the MephistoDB class by creating, updating, and querying task entities with project associations', 'test_MephistoDB_task_run_and_assignment': 'test the MephistoDB class by creating task runs and assignments and verifying their relationships', 'test_MephistoDB_agent_and_unit': 'test the MephistoDB class by creating units and agents and updating their status states', 'test_MephistoDB_qualification_lifecycle': 'test the MephistoDB class by creating, granting, updating, revoking, and deleting worker qualifications'}
```


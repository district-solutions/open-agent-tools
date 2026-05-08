# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/architect.py

Prompts

```
['implement a subclass of Architect that overrides prepare, deploy, and shutdown methods for a custom server', 'configure an ArchitectArgs dataclass with server_type and server_source_path for a mephisto task', 'override the get_channels method in an Architect subclass to return custom Channel callback handlers', 'override the download_file method in an Architect subclass to save server files to a local directory', 'override the assert_task_args class method in an Architect subclass to validate task launch arguments', 'create a python subclass of Blueprint that implements get_initialization_data for a custom task type', 'create a python BlueprintMixin subclass that adds custom qualifications and initialization logic to a blueprint', 'extract the unique mixin classes from a Blueprint subclass using BlueprintMixin.extract_unique_mixins', 'validate task arguments by calling Blueprint.assert_task_args with a DictConfig and SharedTaskState', 'get the frontend task configuration dictionary including tips by calling Blueprint.get_frontend_args', 'implement a CrowdProvider subclass that overrides initialize_provider_datastore and setup_resources_for_task_run', 'create a ProviderArgs dataclass subclass with custom fields for a new crowdsourcing vendor', 'test the CrowdProvider is_sandbox classmethod to check if a provider is a sandbox', 'review the CrowdProvider assert_task_args method to add validation for custom task arguments', 'refactor the cleanup_resources_from_task_run method in a CrowdProvider subclass to handle graceful shutdown', 'create a new Mephisto project with a given project name using the database interface', 'find Mephisto tasks by task name or project id using the database find_tasks method', 'create a new task run for a given task with requester and provider type parameters', 'find Mephisto units by task id, assignment id, worker id, or status using the database', 'grant a qualification to a worker by qualification id and worker id with an optional value']
```

Usage

```
{'implement_architect_subclass': 'implement a subclass of Architect that overrides prepare, deploy, and shutdown methods for a custom server', 'configure_architect_args': 'configure an ArchitectArgs dataclass with server_type and server_source_path for a mephisto task', 'override_get_channels': 'override the get_channels method in an Architect subclass to return custom Channel callback handlers', 'override_download_file': 'override the download_file method in an Architect subclass to save server files to a local directory', 'override_assert_task_args': 'override the assert_task_args class method in an Architect subclass to validate task launch arguments'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprint.py

Prompts

```
['implement a subclass of Architect that overrides prepare, deploy, and shutdown methods for a custom server', 'configure an ArchitectArgs dataclass with server_type and server_source_path for a mephisto task', 'override the get_channels method in an Architect subclass to return custom Channel callback handlers', 'override the download_file method in an Architect subclass to save server files to a local directory', 'override the assert_task_args class method in an Architect subclass to validate task launch arguments', 'create a python subclass of Blueprint that implements get_initialization_data for a custom task type', 'create a python BlueprintMixin subclass that adds custom qualifications and initialization logic to a blueprint', 'extract the unique mixin classes from a Blueprint subclass using BlueprintMixin.extract_unique_mixins', 'validate task arguments by calling Blueprint.assert_task_args with a DictConfig and SharedTaskState', 'get the frontend task configuration dictionary including tips by calling Blueprint.get_frontend_args', 'implement a CrowdProvider subclass that overrides initialize_provider_datastore and setup_resources_for_task_run', 'create a ProviderArgs dataclass subclass with custom fields for a new crowdsourcing vendor', 'test the CrowdProvider is_sandbox classmethod to check if a provider is a sandbox', 'review the CrowdProvider assert_task_args method to add validation for custom task arguments', 'refactor the cleanup_resources_from_task_run method in a CrowdProvider subclass to handle graceful shutdown', 'create a new Mephisto project with a given project name using the database interface', 'find Mephisto tasks by task name or project id using the database find_tasks method', 'create a new task run for a given task with requester and provider type parameters', 'find Mephisto units by task id, assignment id, worker id, or status using the database', 'grant a qualification to a worker by qualification id and worker id with an optional value']
```

Usage

```
{'create_blueprint_subclass': 'create a python subclass of Blueprint that implements get_initialization_data for a custom task type', 'create_blueprint_mixin': 'create a python BlueprintMixin subclass that adds custom qualifications and initialization logic to a blueprint', 'extract_unique_mixins': 'extract the unique mixin classes from a Blueprint subclass using BlueprintMixin.extract_unique_mixins', 'validate_task_args': 'validate task arguments by calling Blueprint.assert_task_args with a DictConfig and SharedTaskState', 'get_frontend_args': 'get the frontend task configuration dictionary including tips by calling Blueprint.get_frontend_args'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/crowd_provider.py

Prompts

```
['implement a subclass of Architect that overrides prepare, deploy, and shutdown methods for a custom server', 'configure an ArchitectArgs dataclass with server_type and server_source_path for a mephisto task', 'override the get_channels method in an Architect subclass to return custom Channel callback handlers', 'override the download_file method in an Architect subclass to save server files to a local directory', 'override the assert_task_args class method in an Architect subclass to validate task launch arguments', 'create a python subclass of Blueprint that implements get_initialization_data for a custom task type', 'create a python BlueprintMixin subclass that adds custom qualifications and initialization logic to a blueprint', 'extract the unique mixin classes from a Blueprint subclass using BlueprintMixin.extract_unique_mixins', 'validate task arguments by calling Blueprint.assert_task_args with a DictConfig and SharedTaskState', 'get the frontend task configuration dictionary including tips by calling Blueprint.get_frontend_args', 'implement a CrowdProvider subclass that overrides initialize_provider_datastore and setup_resources_for_task_run', 'create a ProviderArgs dataclass subclass with custom fields for a new crowdsourcing vendor', 'test the CrowdProvider is_sandbox classmethod to check if a provider is a sandbox', 'review the CrowdProvider assert_task_args method to add validation for custom task arguments', 'refactor the cleanup_resources_from_task_run method in a CrowdProvider subclass to handle graceful shutdown', 'create a new Mephisto project with a given project name using the database interface', 'find Mephisto tasks by task name or project id using the database find_tasks method', 'create a new task run for a given task with requester and provider type parameters', 'find Mephisto units by task id, assignment id, worker id, or status using the database', 'grant a qualification to a worker by qualification id and worker id with an optional value']
```

Usage

```
{'implement_crowd_provider_subclass': 'implement a CrowdProvider subclass that overrides initialize_provider_datastore and setup_resources_for_task_run', 'create_provider_args_dataclass': 'create a ProviderArgs dataclass subclass with custom fields for a new crowdsourcing vendor', 'test_is_sandbox_classmethod': 'test the CrowdProvider is_sandbox classmethod to check if a provider is a sandbox', 'review_assert_task_args': 'review the CrowdProvider assert_task_args method to add validation for custom task arguments', 'refactor_cleanup_resources_from_task_run': 'refactor the cleanup_resources_from_task_run method in a CrowdProvider subclass to handle graceful shutdown'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/database.py

Prompts

```
['implement a subclass of Architect that overrides prepare, deploy, and shutdown methods for a custom server', 'configure an ArchitectArgs dataclass with server_type and server_source_path for a mephisto task', 'override the get_channels method in an Architect subclass to return custom Channel callback handlers', 'override the download_file method in an Architect subclass to save server files to a local directory', 'override the assert_task_args class method in an Architect subclass to validate task launch arguments', 'create a python subclass of Blueprint that implements get_initialization_data for a custom task type', 'create a python BlueprintMixin subclass that adds custom qualifications and initialization logic to a blueprint', 'extract the unique mixin classes from a Blueprint subclass using BlueprintMixin.extract_unique_mixins', 'validate task arguments by calling Blueprint.assert_task_args with a DictConfig and SharedTaskState', 'get the frontend task configuration dictionary including tips by calling Blueprint.get_frontend_args', 'implement a CrowdProvider subclass that overrides initialize_provider_datastore and setup_resources_for_task_run', 'create a ProviderArgs dataclass subclass with custom fields for a new crowdsourcing vendor', 'test the CrowdProvider is_sandbox classmethod to check if a provider is a sandbox', 'review the CrowdProvider assert_task_args method to add validation for custom task arguments', 'refactor the cleanup_resources_from_task_run method in a CrowdProvider subclass to handle graceful shutdown', 'create a new Mephisto project with a given project name using the database interface', 'find Mephisto tasks by task name or project id using the database find_tasks method', 'create a new task run for a given task with requester and provider type parameters', 'find Mephisto units by task id, assignment id, worker id, or status using the database', 'grant a qualification to a worker by qualification id and worker id with an optional value']
```

Usage

```
{'create_mephisto_project': 'create a new Mephisto project with a given project name using the database interface', 'find_mephisto_tasks': 'find Mephisto tasks by task name or project id using the database find_tasks method', 'create_mephisto_task_run': 'create a new task run for a given task with requester and provider type parameters', 'find_mephisto_units': 'find Mephisto units by task id, assignment id, worker id, or status using the database', 'grant_worker_qualification': 'grant a qualification to a worker by qualification id and worker id with an optional value'}
```


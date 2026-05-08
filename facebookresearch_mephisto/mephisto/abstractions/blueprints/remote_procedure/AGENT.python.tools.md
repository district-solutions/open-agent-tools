# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/remote_procedure/remote_procedure_agent_state.py

Prompts

```
['create a RemoteRequest dataclass with uuid, target, args_json, response_json, and timestamp fields', 'convert a RemoteRequest dataclass instance to a dictionary using the to_dict method', 'load stored agent state data including requests and submissions from a JSON file', 'update the agent state by appending incoming or outgoing remote procedure call packets', 'get the initial state of an agent including task data and previous sorted requests', 'create a RemoteProcedureBlueprint subclass to define a new task blueprint with remote procedure support', 'configure RemoteProcedureBlueprintArgs to set task_source, extra_source_dir, and units_per_assignment for a task', 'load initialization data from a CSV file into a RemoteProcedureBlueprint for task assignments', 'load initialization data from a JSON or JSONL file into a RemoteProcedureBlueprint for task assignments', 'validate task arguments and function registry using assert_task_args before launching a RemoteProcedureBlueprint task', 'run a task with live remote queries on the local machine using RemoteProcedureTaskRunner', 'execute a registered remote procedure function for an agent based on their live update request', 'run onboarding for an agent with access to remote queries and server timestep processing', 'get initialization data for an agent assigned to a unit including shared assignment data', 'check if an agent is currently in onboarding or live task status']
```

Usage

```
{'create_RemoteRequest_dataclass': 'create a RemoteRequest dataclass with uuid, target, args_json, response_json, and timestamp fields', 'convert_RemoteRequest_to_dict': 'convert a RemoteRequest dataclass instance to a dictionary using the to_dict method', 'load_agent_state_data': 'load stored agent state data including requests and submissions from a JSON file', 'update_agent_state_with_live_data': 'update the agent state by appending incoming or outgoing remote procedure call packets', 'get_agent_initial_state': 'get the initial state of an agent including task data and previous sorted requests'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/remote_procedure/remote_procedure_blueprint.py

Prompts

```
['create a RemoteRequest dataclass with uuid, target, args_json, response_json, and timestamp fields', 'convert a RemoteRequest dataclass instance to a dictionary using the to_dict method', 'load stored agent state data including requests and submissions from a JSON file', 'update the agent state by appending incoming or outgoing remote procedure call packets', 'get the initial state of an agent including task data and previous sorted requests', 'create a RemoteProcedureBlueprint subclass to define a new task blueprint with remote procedure support', 'configure RemoteProcedureBlueprintArgs to set task_source, extra_source_dir, and units_per_assignment for a task', 'load initialization data from a CSV file into a RemoteProcedureBlueprint for task assignments', 'load initialization data from a JSON or JSONL file into a RemoteProcedureBlueprint for task assignments', 'validate task arguments and function registry using assert_task_args before launching a RemoteProcedureBlueprint task', 'run a task with live remote queries on the local machine using RemoteProcedureTaskRunner', 'execute a registered remote procedure function for an agent based on their live update request', 'run onboarding for an agent with access to remote queries and server timestep processing', 'get initialization data for an agent assigned to a unit including shared assignment data', 'check if an agent is currently in onboarding or live task status']
```

Usage

```
{'create_remote_procedure_blueprint': 'create a RemoteProcedureBlueprint subclass to define a new task blueprint with remote procedure support', 'configure_remote_procedure_blueprint_args': 'configure RemoteProcedureBlueprintArgs to set task_source, extra_source_dir, and units_per_assignment for a task', 'load_initialization_data_from_csv': 'load initialization data from a CSV file into a RemoteProcedureBlueprint for task assignments', 'load_initialization_data_from_json': 'load initialization data from a JSON or JSONL file into a RemoteProcedureBlueprint for task assignments', 'validate_task_args_with_registry': 'validate task arguments and function registry using assert_task_args before launching a RemoteProcedureBlueprint task'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/remote_procedure/remote_procedure_task_runner.py

Prompts

```
['create a RemoteRequest dataclass with uuid, target, args_json, response_json, and timestamp fields', 'convert a RemoteRequest dataclass instance to a dictionary using the to_dict method', 'load stored agent state data including requests and submissions from a JSON file', 'update the agent state by appending incoming or outgoing remote procedure call packets', 'get the initial state of an agent including task data and previous sorted requests', 'create a RemoteProcedureBlueprint subclass to define a new task blueprint with remote procedure support', 'configure RemoteProcedureBlueprintArgs to set task_source, extra_source_dir, and units_per_assignment for a task', 'load initialization data from a CSV file into a RemoteProcedureBlueprint for task assignments', 'load initialization data from a JSON or JSONL file into a RemoteProcedureBlueprint for task assignments', 'validate task arguments and function registry using assert_task_args before launching a RemoteProcedureBlueprint task', 'run a task with live remote queries on the local machine using RemoteProcedureTaskRunner', 'execute a registered remote procedure function for an agent based on their live update request', 'run onboarding for an agent with access to remote queries and server timestep processing', 'get initialization data for an agent assigned to a unit including shared assignment data', 'check if an agent is currently in onboarding or live task status']
```

Usage

```
{'run_remote_procedure_task': 'run a task with live remote queries on the local machine using RemoteProcedureTaskRunner', 'execute_remote_procedure_for_agent': 'execute a registered remote procedure function for an agent based on their live update request', 'run_onboarding_with_remote_queries': 'run onboarding for an agent with access to remote queries and server timestep processing', 'get_init_data_for_agent': 'get initialization data for an agent assigned to a unit including shared assignment data', 'check_agent_in_onboarding_or_live': 'check if an agent is currently in onboarding or live task status'}
```


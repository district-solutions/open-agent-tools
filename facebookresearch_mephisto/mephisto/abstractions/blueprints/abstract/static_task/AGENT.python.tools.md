# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/abstract/static_task/empty_task_builder.py

Prompts

```
['review the EmptyStaticTaskBuilder abstract class and its build_in_dir method signature', 'extend EmptyStaticTaskBuilder to implement a custom build_in_dir method for a static frontend', 'refactor EmptyStaticTaskBuilder subclass to pull frontend assets from args.blueprint.extra_source_dir', 'test that EmptyStaticTaskBuilder raises AssertionError when build_in_dir is called directly', 'summarize the EmptyStaticTaskBuilder abstract class purpose and expected subclass behavior', 'create a StaticAgentState instance to manage agent state for static tasks in mephisto', 'get the initial state inputs for a static task agent from StaticAgentState', 'load agent state data from disk using StaticAgentState _load_data method', 'save static agent state data to disk using StaticAgentState _save_data method', 'update the static agent state outputs with submitted task data via _update_submit', 'create a subclass of StaticBlueprint to define a new static task type with custom initialization data loading', 'load task initialization data from a CSV file using the StaticBlueprint data_csv argument', 'load task initialization data from a JSON file using the StaticBlueprint data_json argument', 'load task initialization data from a JSONL file using the StaticBlueprint data_jsonl argument', 'call get_initialization_data on a StaticBlueprint instance to retrieve an iterable of InitializationData objects', 'run a static task unit by awaiting agent submission with a configured timeout duration', 'get initialization data for an agent assigned to a unit including shared assignment data', 'run onboarding for an agent by awaiting their submission within the assignment duration', 'cleanup an incomplete static task unit with no associated cleanup actions required', 'review the StaticTaskRunner class and its methods for handling single-user static task assignments']
```

Usage

```
{'review_EmptyStaticTaskBuilder': 'review the EmptyStaticTaskBuilder abstract class and its build_in_dir method signature', 'extend_EmptyStaticTaskBuilder': 'extend EmptyStaticTaskBuilder to implement a custom build_in_dir method for a static frontend', 'refactor_EmptyStaticTaskBuilder': 'refactor EmptyStaticTaskBuilder subclass to pull frontend assets from args.blueprint.extra_source_dir', 'test_EmptyStaticTaskBuilder': 'test that EmptyStaticTaskBuilder raises AssertionError when build_in_dir is called directly', 'summarize_EmptyStaticTaskBuilder': 'summarize the EmptyStaticTaskBuilder abstract class purpose and expected subclass behavior'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/abstract/static_task/static_agent_state.py

Prompts

```
['review the EmptyStaticTaskBuilder abstract class and its build_in_dir method signature', 'extend EmptyStaticTaskBuilder to implement a custom build_in_dir method for a static frontend', 'refactor EmptyStaticTaskBuilder subclass to pull frontend assets from args.blueprint.extra_source_dir', 'test that EmptyStaticTaskBuilder raises AssertionError when build_in_dir is called directly', 'summarize the EmptyStaticTaskBuilder abstract class purpose and expected subclass behavior', 'create a StaticAgentState instance to manage agent state for static tasks in mephisto', 'get the initial state inputs for a static task agent from StaticAgentState', 'load agent state data from disk using StaticAgentState _load_data method', 'save static agent state data to disk using StaticAgentState _save_data method', 'update the static agent state outputs with submitted task data via _update_submit', 'create a subclass of StaticBlueprint to define a new static task type with custom initialization data loading', 'load task initialization data from a CSV file using the StaticBlueprint data_csv argument', 'load task initialization data from a JSON file using the StaticBlueprint data_json argument', 'load task initialization data from a JSONL file using the StaticBlueprint data_jsonl argument', 'call get_initialization_data on a StaticBlueprint instance to retrieve an iterable of InitializationData objects', 'run a static task unit by awaiting agent submission with a configured timeout duration', 'get initialization data for an agent assigned to a unit including shared assignment data', 'run onboarding for an agent by awaiting their submission within the assignment duration', 'cleanup an incomplete static task unit with no associated cleanup actions required', 'review the StaticTaskRunner class and its methods for handling single-user static task assignments']
```

Usage

```
{'create_static_agent_state': 'create a StaticAgentState instance to manage agent state for static tasks in mephisto', 'get_init_state': 'get the initial state inputs for a static task agent from StaticAgentState', 'load_agent_data': 'load agent state data from disk using StaticAgentState _load_data method', 'save_agent_data': 'save static agent state data to disk using StaticAgentState _save_data method', 'update_submit_outputs': 'update the static agent state outputs with submitted task data via _update_submit'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/abstract/static_task/static_blueprint.py

Prompts

```
['review the EmptyStaticTaskBuilder abstract class and its build_in_dir method signature', 'extend EmptyStaticTaskBuilder to implement a custom build_in_dir method for a static frontend', 'refactor EmptyStaticTaskBuilder subclass to pull frontend assets from args.blueprint.extra_source_dir', 'test that EmptyStaticTaskBuilder raises AssertionError when build_in_dir is called directly', 'summarize the EmptyStaticTaskBuilder abstract class purpose and expected subclass behavior', 'create a StaticAgentState instance to manage agent state for static tasks in mephisto', 'get the initial state inputs for a static task agent from StaticAgentState', 'load agent state data from disk using StaticAgentState _load_data method', 'save static agent state data to disk using StaticAgentState _save_data method', 'update the static agent state outputs with submitted task data via _update_submit', 'create a subclass of StaticBlueprint to define a new static task type with custom initialization data loading', 'load task initialization data from a CSV file using the StaticBlueprint data_csv argument', 'load task initialization data from a JSON file using the StaticBlueprint data_json argument', 'load task initialization data from a JSONL file using the StaticBlueprint data_jsonl argument', 'call get_initialization_data on a StaticBlueprint instance to retrieve an iterable of InitializationData objects', 'run a static task unit by awaiting agent submission with a configured timeout duration', 'get initialization data for an agent assigned to a unit including shared assignment data', 'run onboarding for an agent by awaiting their submission within the assignment duration', 'cleanup an incomplete static task unit with no associated cleanup actions required', 'review the StaticTaskRunner class and its methods for handling single-user static task assignments']
```

Usage

```
{'create_static_blueprint_subclass': 'create a subclass of StaticBlueprint to define a new static task type with custom initialization data loading', 'load_task_data_from_csv': 'load task initialization data from a CSV file using the StaticBlueprint data_csv argument', 'load_task_data_from_json': 'load task initialization data from a JSON file using the StaticBlueprint data_json argument', 'load_task_data_from_jsonl': 'load task initialization data from a JSONL file using the StaticBlueprint data_jsonl argument', 'get_initialization_data': 'call get_initialization_data on a StaticBlueprint instance to retrieve an iterable of InitializationData objects'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/abstract/static_task/static_task_runner.py

Prompts

```
['review the EmptyStaticTaskBuilder abstract class and its build_in_dir method signature', 'extend EmptyStaticTaskBuilder to implement a custom build_in_dir method for a static frontend', 'refactor EmptyStaticTaskBuilder subclass to pull frontend assets from args.blueprint.extra_source_dir', 'test that EmptyStaticTaskBuilder raises AssertionError when build_in_dir is called directly', 'summarize the EmptyStaticTaskBuilder abstract class purpose and expected subclass behavior', 'create a StaticAgentState instance to manage agent state for static tasks in mephisto', 'get the initial state inputs for a static task agent from StaticAgentState', 'load agent state data from disk using StaticAgentState _load_data method', 'save static agent state data to disk using StaticAgentState _save_data method', 'update the static agent state outputs with submitted task data via _update_submit', 'create a subclass of StaticBlueprint to define a new static task type with custom initialization data loading', 'load task initialization data from a CSV file using the StaticBlueprint data_csv argument', 'load task initialization data from a JSON file using the StaticBlueprint data_json argument', 'load task initialization data from a JSONL file using the StaticBlueprint data_jsonl argument', 'call get_initialization_data on a StaticBlueprint instance to retrieve an iterable of InitializationData objects', 'run a static task unit by awaiting agent submission with a configured timeout duration', 'get initialization data for an agent assigned to a unit including shared assignment data', 'run onboarding for an agent by awaiting their submission within the assignment duration', 'cleanup an incomplete static task unit with no associated cleanup actions required', 'review the StaticTaskRunner class and its methods for handling single-user static task assignments']
```

Usage

```
{'run_static_task_unit': 'run a static task unit by awaiting agent submission with a configured timeout duration', 'get_init_data_for_agent': 'get initialization data for an agent assigned to a unit including shared assignment data', 'run_onboarding_agent': 'run onboarding for an agent by awaiting their submission within the assignment duration', 'cleanup_static_task_unit': 'cleanup an incomplete static task unit with no associated cleanup actions required', 'review_static_task_runner': 'review the StaticTaskRunner class and its methods for handling single-user static task assignments'}
```


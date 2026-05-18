# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/mock/mock_agent_state.py

Prompts

```
['create a MockAgentState instance to manage in-memory agent state for testing', 'set the initial state data on a MockAgentState instance using _set_init_state', 'get the initial state dict from a MockAgentState instance using get_init_state', 'get the full agent state dict with inputs and outputs using get_data', 'update the live state of a MockAgentState instance with new data using update_data', 'create a MockBlueprint instance with a TaskRun, DictConfig args, and MockSharedState for testing', 'get mock assignment initialization data by calling get_initialization_data on a MockBlueprint instance', 'validate onboarding for a worker by calling validate_onboarding with a Worker and OnboardingAgent', 'configure MockBlueprintArgs with num_assignments, use_onboarding, timeout_time, and is_concurrent fields', 'create a MockSharedState instance that inherits SharedTaskState, OnboardingSharedState, and ScreenTaskSharedState', 'build a mock task by writing a done.built file into the specified build directory', 'create a MockTaskBuilder instance to simulate task building for testing purposes', 'test the MockTaskBuilder build_in_dir method by verifying the done.built file is written', 'review the MockTaskBuilder class and its build_in_dir method for testing mock tasks', 'refactor the MockTaskBuilder to customize the BUILT_FILE name or BUILT_MESSAGE content', 'run a mock unit task for a single agent using MockTaskRunner.run_unit', 'run a mock assignment with multiple agents using MockTaskRunner.run_assignment', 'run mock onboarding for an agent using MockTaskRunner.run_onboarding', 'get mock initialization data for testing using MockTaskRunner.get_mock_assignment_data', 'cleanup a mock assignment using MockTaskRunner.cleanup_assignment']
```

Usage

```
{'create_mock_agent_state': 'create a MockAgentState instance to manage in-memory agent state for testing', 'set_init_state': 'set the initial state data on a MockAgentState instance using _set_init_state', 'get_init_state': 'get the initial state dict from a MockAgentState instance using get_init_state', 'get_data': 'get the full agent state dict with inputs and outputs using get_data', 'update_data': 'update the live state of a MockAgentState instance with new data using update_data'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/mock/mock_blueprint.py

Prompts

```
['create a MockAgentState instance to manage in-memory agent state for testing', 'set the initial state data on a MockAgentState instance using _set_init_state', 'get the initial state dict from a MockAgentState instance using get_init_state', 'get the full agent state dict with inputs and outputs using get_data', 'update the live state of a MockAgentState instance with new data using update_data', 'create a MockBlueprint instance with a TaskRun, DictConfig args, and MockSharedState for testing', 'get mock assignment initialization data by calling get_initialization_data on a MockBlueprint instance', 'validate onboarding for a worker by calling validate_onboarding with a Worker and OnboardingAgent', 'configure MockBlueprintArgs with num_assignments, use_onboarding, timeout_time, and is_concurrent fields', 'create a MockSharedState instance that inherits SharedTaskState, OnboardingSharedState, and ScreenTaskSharedState', 'build a mock task by writing a done.built file into the specified build directory', 'create a MockTaskBuilder instance to simulate task building for testing purposes', 'test the MockTaskBuilder build_in_dir method by verifying the done.built file is written', 'review the MockTaskBuilder class and its build_in_dir method for testing mock tasks', 'refactor the MockTaskBuilder to customize the BUILT_FILE name or BUILT_MESSAGE content', 'run a mock unit task for a single agent using MockTaskRunner.run_unit', 'run a mock assignment with multiple agents using MockTaskRunner.run_assignment', 'run mock onboarding for an agent using MockTaskRunner.run_onboarding', 'get mock initialization data for testing using MockTaskRunner.get_mock_assignment_data', 'cleanup a mock assignment using MockTaskRunner.cleanup_assignment']
```

Usage

```
{'create_mock_blueprint': 'create a MockBlueprint instance with a TaskRun, DictConfig args, and MockSharedState for testing', 'get_initialization_data': 'get mock assignment initialization data by calling get_initialization_data on a MockBlueprint instance', 'validate_onboarding': 'validate onboarding for a worker by calling validate_onboarding with a Worker and OnboardingAgent', 'configure_mock_blueprint_args': 'configure MockBlueprintArgs with num_assignments, use_onboarding, timeout_time, and is_concurrent fields', 'create_mock_shared_state': 'create a MockSharedState instance that inherits SharedTaskState, OnboardingSharedState, and ScreenTaskSharedState'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/mock/mock_task_builder.py

Prompts

```
['create a MockAgentState instance to manage in-memory agent state for testing', 'set the initial state data on a MockAgentState instance using _set_init_state', 'get the initial state dict from a MockAgentState instance using get_init_state', 'get the full agent state dict with inputs and outputs using get_data', 'update the live state of a MockAgentState instance with new data using update_data', 'create a MockBlueprint instance with a TaskRun, DictConfig args, and MockSharedState for testing', 'get mock assignment initialization data by calling get_initialization_data on a MockBlueprint instance', 'validate onboarding for a worker by calling validate_onboarding with a Worker and OnboardingAgent', 'configure MockBlueprintArgs with num_assignments, use_onboarding, timeout_time, and is_concurrent fields', 'create a MockSharedState instance that inherits SharedTaskState, OnboardingSharedState, and ScreenTaskSharedState', 'build a mock task by writing a done.built file into the specified build directory', 'create a MockTaskBuilder instance to simulate task building for testing purposes', 'test the MockTaskBuilder build_in_dir method by verifying the done.built file is written', 'review the MockTaskBuilder class and its build_in_dir method for testing mock tasks', 'refactor the MockTaskBuilder to customize the BUILT_FILE name or BUILT_MESSAGE content', 'run a mock unit task for a single agent using MockTaskRunner.run_unit', 'run a mock assignment with multiple agents using MockTaskRunner.run_assignment', 'run mock onboarding for an agent using MockTaskRunner.run_onboarding', 'get mock initialization data for testing using MockTaskRunner.get_mock_assignment_data', 'cleanup a mock assignment using MockTaskRunner.cleanup_assignment']
```

Usage

```
{'build_mock_task_in_dir': 'build a mock task by writing a done.built file into the specified build directory', 'create_MockTaskBuilder_instance': 'create a MockTaskBuilder instance to simulate task building for testing purposes', 'test_MockTaskBuilder_build_in_dir': 'test the MockTaskBuilder build_in_dir method by verifying the done.built file is written', 'review_MockTaskBuilder_class': 'review the MockTaskBuilder class and its build_in_dir method for testing mock tasks', 'refactor_MockTaskBuilder_BUILT_FILE': 'refactor the MockTaskBuilder to customize the BUILT_FILE name or BUILT_MESSAGE content'}
```

## File: facebookresearch_mephisto/mephisto/abstractions/blueprints/mock/mock_task_runner.py

Prompts

```
['create a MockAgentState instance to manage in-memory agent state for testing', 'set the initial state data on a MockAgentState instance using _set_init_state', 'get the initial state dict from a MockAgentState instance using get_init_state', 'get the full agent state dict with inputs and outputs using get_data', 'update the live state of a MockAgentState instance with new data using update_data', 'create a MockBlueprint instance with a TaskRun, DictConfig args, and MockSharedState for testing', 'get mock assignment initialization data by calling get_initialization_data on a MockBlueprint instance', 'validate onboarding for a worker by calling validate_onboarding with a Worker and OnboardingAgent', 'configure MockBlueprintArgs with num_assignments, use_onboarding, timeout_time, and is_concurrent fields', 'create a MockSharedState instance that inherits SharedTaskState, OnboardingSharedState, and ScreenTaskSharedState', 'build a mock task by writing a done.built file into the specified build directory', 'create a MockTaskBuilder instance to simulate task building for testing purposes', 'test the MockTaskBuilder build_in_dir method by verifying the done.built file is written', 'review the MockTaskBuilder class and its build_in_dir method for testing mock tasks', 'refactor the MockTaskBuilder to customize the BUILT_FILE name or BUILT_MESSAGE content', 'run a mock unit task for a single agent using MockTaskRunner.run_unit', 'run a mock assignment with multiple agents using MockTaskRunner.run_assignment', 'run mock onboarding for an agent using MockTaskRunner.run_onboarding', 'get mock initialization data for testing using MockTaskRunner.get_mock_assignment_data', 'cleanup a mock assignment using MockTaskRunner.cleanup_assignment']
```

Usage

```
{'run_mock_unit_task': 'run a mock unit task for a single agent using MockTaskRunner.run_unit', 'run_mock_assignment': 'run a mock assignment with multiple agents using MockTaskRunner.run_assignment', 'run_mock_onboarding': 'run mock onboarding for an agent using MockTaskRunner.run_onboarding', 'get_mock_assignment_data': 'get mock initialization data for testing using MockTaskRunner.get_mock_assignment_data', 'cleanup_mock_assignment': 'cleanup a mock assignment using MockTaskRunner.cleanup_assignment'}
```


# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/abstractions/blueprints/test_mixin_core.py

Prompts

```
['run the unittest suite to test BlueprintMixin core functionality including broken, working, and composed mixin scenarios', 'test that a BlueprintMixin without ArgsMixin or SharedStateMixin raises an AttributeError when decorated', 'test that a BlueprintMixin with proper ArgsMixin and SharedStateMixin initializes correctly via the decorator', 'test that a Blueprint with multiple BlueprintMixin decorators calls each mixin init and merges qualifications', 'test that a ComposedMixin combining multiple mixins behaves as a single mixin with merged args and state', 'test the MockBlueprintTests task_is_built method to verify a task build artifact exists and contains the expected message', 'test the assignment_completed_successfully method to validate an assignment reached the COMPLETED state', 'test the get_test_assignment method to create a test assignment with mock workers, units, and agents', 'test the assignment_is_tracked method to check if a MockTaskRunner is currently tracking a given assignment', 'test the prep_mock_agents_to_complete method to enqueue mock live updates and submit events for a list of agents']
```

Usage

```
{'test_blueprint_mixin_core': 'run the unittest suite to test BlueprintMixin core functionality including broken, working, and composed mixin scenarios', 'test_broken_mixin': 'test that a BlueprintMixin without ArgsMixin or SharedStateMixin raises an AttributeError when decorated', 'test_working_mixin': 'test that a BlueprintMixin with proper ArgsMixin and SharedStateMixin initializes correctly via the decorator', 'test_mixin_multi_inheritance': 'test that a Blueprint with multiple BlueprintMixin decorators calls each mixin init and merges qualifications', 'test_composed_mixin_inheritance': 'test that a ComposedMixin combining multiple mixins behaves as a single mixin with merged args and state'}
```

## File: facebookresearch_mephisto/test/abstractions/blueprints/test_mock_blueprint.py

Prompts

```
['run the unittest suite to test BlueprintMixin core functionality including broken, working, and composed mixin scenarios', 'test that a BlueprintMixin without ArgsMixin or SharedStateMixin raises an AttributeError when decorated', 'test that a BlueprintMixin with proper ArgsMixin and SharedStateMixin initializes correctly via the decorator', 'test that a Blueprint with multiple BlueprintMixin decorators calls each mixin init and merges qualifications', 'test that a ComposedMixin combining multiple mixins behaves as a single mixin with merged args and state', 'test the MockBlueprintTests task_is_built method to verify a task build artifact exists and contains the expected message', 'test the assignment_completed_successfully method to validate an assignment reached the COMPLETED state', 'test the get_test_assignment method to create a test assignment with mock workers, units, and agents', 'test the assignment_is_tracked method to check if a MockTaskRunner is currently tracking a given assignment', 'test the prep_mock_agents_to_complete method to enqueue mock live updates and submit events for a list of agents']
```

Usage

```
{'test_MockBlueprintTests_task_is_built': 'test the MockBlueprintTests task_is_built method to verify a task build artifact exists and contains the expected message', 'test_MockBlueprintTests_assignment_completed_successfully': 'test the assignment_completed_successfully method to validate an assignment reached the COMPLETED state', 'test_MockBlueprintTests_get_test_assignment': 'test the get_test_assignment method to create a test assignment with mock workers, units, and agents', 'test_MockBlueprintTests_assignment_is_tracked': 'test the assignment_is_tracked method to check if a MockTaskRunner is currently tracking a given assignment', 'test_MockBlueprintTests_prep_mock_agents_to_complete': 'test the prep_mock_agents_to_complete method to enqueue mock live updates and submit events for a list of agents'}
```


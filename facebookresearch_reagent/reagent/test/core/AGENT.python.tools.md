# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/test/core/aggregators_test.py

Prompts

```
['test the ActionCountAggregator class to verify action counting and distribution calculations', 'test the get_distributions method to verify per-step action distribution percentages', 'test the get_cumulative_distributions method to verify overall cumulative action distribution values', 'review the ActionCountAggregator class and its distribution calculation logic', 'refactor the ActionCountAggregatorTest to add additional test cases for edge conditions', 'test the Config class with default Foo union values and verify foo returns 2', 'test the Config class with custom Foo union parameters and verify foo returns 12', 'test the Config class with Bar union type and verify foo returns 10', 'test that adding a new class to a frozen FooRegistry raises a RuntimeError', 'test that setting SKIP_FROZEN_REGISTRY_CHECK env var allows adding classes to a frozen registry', 'test the embedding_bag_configs_from_feature_configs function with ModelFeatureConfig objects and verify correct aggregation', 'run the TestUtils unit test suite to validate embedding bag config generation from feature configs', 'review the TestUtils class and its test for embedding bag config conversion logic', 'refactor the test_embedding_bag_configs_from_feature_configs test to add additional edge case scenarios', 'summarize how embedding_bag_configs_from_feature_configs aggregates features by table name and validates consistency', 'test the observable decorator that adds observer notification support to a class', 'test the ValueListObserver class that collects observed values into a list', 'test the add_observers method to register multiple observers on an observable instance', 'test that add_observer is idempotent and does not duplicate observer registrations', 'test that decorating a class with observable without values raises an AssertionError']
```

Usage

```
{'test_ActionCountAggregator': 'test the ActionCountAggregator class to verify action counting and distribution calculations', 'test_get_distributions': 'test the get_distributions method to verify per-step action distribution percentages', 'test_get_cumulative_distributions': 'test the get_cumulative_distributions method to verify overall cumulative action distribution values', 'review_ActionCountAggregator': 'review the ActionCountAggregator class and its distribution calculation logic', 'refactor_ActionCountAggregatorTest': 'refactor the ActionCountAggregatorTest to add additional test cases for edge conditions'}
```

## File: facebookresearch_reagent/reagent/test/core/test_config_parsing.py

Prompts

```
['test the ActionCountAggregator class to verify action counting and distribution calculations', 'test the get_distributions method to verify per-step action distribution percentages', 'test the get_cumulative_distributions method to verify overall cumulative action distribution values', 'review the ActionCountAggregator class and its distribution calculation logic', 'refactor the ActionCountAggregatorTest to add additional test cases for edge conditions', 'test the Config class with default Foo union values and verify foo returns 2', 'test the Config class with custom Foo union parameters and verify foo returns 12', 'test the Config class with Bar union type and verify foo returns 10', 'test that adding a new class to a frozen FooRegistry raises a RuntimeError', 'test that setting SKIP_FROZEN_REGISTRY_CHECK env var allows adding classes to a frozen registry', 'test the embedding_bag_configs_from_feature_configs function with ModelFeatureConfig objects and verify correct aggregation', 'run the TestUtils unit test suite to validate embedding bag config generation from feature configs', 'review the TestUtils class and its test for embedding bag config conversion logic', 'refactor the test_embedding_bag_configs_from_feature_configs test to add additional edge case scenarios', 'summarize how embedding_bag_configs_from_feature_configs aggregates features by table name and validates consistency', 'test the observable decorator that adds observer notification support to a class', 'test the ValueListObserver class that collects observed values into a list', 'test the add_observers method to register multiple observers on an observable instance', 'test that add_observer is idempotent and does not duplicate observer registrations', 'test that decorating a class with observable without values raises an AssertionError']
```

Usage

```
{'test_config_parsing_foo_default': 'test the Config class with default Foo union values and verify foo returns 2', 'test_config_parsing_foo_custom': 'test the Config class with custom Foo union parameters and verify foo returns 12', 'test_config_parsing_bar': 'test the Config class with Bar union type and verify foo returns 10', 'test_frozen_registry': 'test that adding a new class to a frozen FooRegistry raises a RuntimeError', 'test_frozen_registry_skip': 'test that setting SKIP_FROZEN_REGISTRY_CHECK env var allows adding classes to a frozen registry'}
```

## File: facebookresearch_reagent/reagent/test/core/test_utils.py

Prompts

```
['test the ActionCountAggregator class to verify action counting and distribution calculations', 'test the get_distributions method to verify per-step action distribution percentages', 'test the get_cumulative_distributions method to verify overall cumulative action distribution values', 'review the ActionCountAggregator class and its distribution calculation logic', 'refactor the ActionCountAggregatorTest to add additional test cases for edge conditions', 'test the Config class with default Foo union values and verify foo returns 2', 'test the Config class with custom Foo union parameters and verify foo returns 12', 'test the Config class with Bar union type and verify foo returns 10', 'test that adding a new class to a frozen FooRegistry raises a RuntimeError', 'test that setting SKIP_FROZEN_REGISTRY_CHECK env var allows adding classes to a frozen registry', 'test the embedding_bag_configs_from_feature_configs function with ModelFeatureConfig objects and verify correct aggregation', 'run the TestUtils unit test suite to validate embedding bag config generation from feature configs', 'review the TestUtils class and its test for embedding bag config conversion logic', 'refactor the test_embedding_bag_configs_from_feature_configs test to add additional edge case scenarios', 'summarize how embedding_bag_configs_from_feature_configs aggregates features by table name and validates consistency', 'test the observable decorator that adds observer notification support to a class', 'test the ValueListObserver class that collects observed values into a list', 'test the add_observers method to register multiple observers on an observable instance', 'test that add_observer is idempotent and does not duplicate observer registrations', 'test that decorating a class with observable without values raises an AssertionError']
```

Usage

```
{'test_embedding_bag_configs_from_feature_configs': 'test the embedding_bag_configs_from_feature_configs function with ModelFeatureConfig objects and verify correct aggregation', 'run_test_utils': 'run the TestUtils unit test suite to validate embedding bag config generation from feature configs', 'review_TestUtils': 'review the TestUtils class and its test for embedding bag config conversion logic', 'refactor_test_embedding_bag_configs': 'refactor the test_embedding_bag_configs_from_feature_configs test to add additional edge case scenarios', 'summarize_embedding_bag_configs': 'summarize how embedding_bag_configs_from_feature_configs aggregates features by table name and validates consistency'}
```

## File: facebookresearch_reagent/reagent/test/core/tracker_test.py

Prompts

```
['test the ActionCountAggregator class to verify action counting and distribution calculations', 'test the get_distributions method to verify per-step action distribution percentages', 'test the get_cumulative_distributions method to verify overall cumulative action distribution values', 'review the ActionCountAggregator class and its distribution calculation logic', 'refactor the ActionCountAggregatorTest to add additional test cases for edge conditions', 'test the Config class with default Foo union values and verify foo returns 2', 'test the Config class with custom Foo union parameters and verify foo returns 12', 'test the Config class with Bar union type and verify foo returns 10', 'test that adding a new class to a frozen FooRegistry raises a RuntimeError', 'test that setting SKIP_FROZEN_REGISTRY_CHECK env var allows adding classes to a frozen registry', 'test the embedding_bag_configs_from_feature_configs function with ModelFeatureConfig objects and verify correct aggregation', 'run the TestUtils unit test suite to validate embedding bag config generation from feature configs', 'review the TestUtils class and its test for embedding bag config conversion logic', 'refactor the test_embedding_bag_configs_from_feature_configs test to add additional edge case scenarios', 'summarize how embedding_bag_configs_from_feature_configs aggregates features by table name and validates consistency', 'test the observable decorator that adds observer notification support to a class', 'test the ValueListObserver class that collects observed values into a list', 'test the add_observers method to register multiple observers on an observable instance', 'test that add_observer is idempotent and does not duplicate observer registrations', 'test that decorating a class with observable without values raises an AssertionError']
```

Usage

```
{'test_observable_decorator': 'test the observable decorator that adds observer notification support to a class', 'test_ValueListObserver': 'test the ValueListObserver class that collects observed values into a list', 'test_add_observers': 'test the add_observers method to register multiple observers on an observable instance', 'test_add_observer_idempotent': 'test that add_observer is idempotent and does not duplicate observer registrations', 'test_no_observable_values_assertion': 'test that decorating a class with observable without values raises an AssertionError'}
```


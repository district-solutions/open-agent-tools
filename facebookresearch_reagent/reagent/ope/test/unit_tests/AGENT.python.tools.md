# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/ope/test/unit_tests/test_contextual_bandit_estimators.py

Prompts

```
['test that SwitchEstimator with max threshold equals IPSEstimator estimated reward', 'test that SwitchDREstimator with max threshold equals DoublyRobustEstimator estimated reward', 'test that SwitchEstimator with min threshold equals DMEstimator estimated reward', 'test that SwitchDREstimator with min threshold equals DMEstimator estimated reward', 'review the TestSwitchEstimators class and its contextual bandit estimator unit tests', 'test the SlateItemProbabilities class to sample slates and compute slate probabilities and expected rewards', 'test the SlateSlotItemProbabilities class to sample slates and compute slot-specific expected rewards', 'test the DCGSlateMetric class to compute discounted cumulative gain for a given slate', 'test the NDCGSlateMetric class to compute normalized discounted cumulative gain for a given slate', 'test constructing Slate objects with SlateItem entries and computing slot values from item rewards', 'test the TypeWrapper class with int values for hashing and equality comparison', 'test the TypeWrapper class with torch tensors for equality and hash behavior', 'test the Values class sort method to return keys and values ordered by descending value', 'test the Values class copy method to ensure deep copy isolation from the original', 'test the ActionDistribution class sample method for probabilistic sampling and greedy selection of top actions', 'test the RunningAverage class by adding values and checking count average and total properties', 'test the Clamper class by clamping lists tensors and numpy arrays within min max bounds', 'create a RunningAverage instance and chain add calls to track a running mean of values', 'create a Clamper with min and max bounds to clamp lists tensors or numpy arrays', 'review the Clamper class that clamps values to a min max range supporting torch and numpy']
```

Usage

```
{'test_switch_equal_to_ips': 'test that SwitchEstimator with max threshold equals IPSEstimator estimated reward', 'test_switch_dr_equal_to_dr': 'test that SwitchDREstimator with max threshold equals DoublyRobustEstimator estimated reward', 'test_switch_equal_to_dm': 'test that SwitchEstimator with min threshold equals DMEstimator estimated reward', 'test_switch_dr_equal_to_dm': 'test that SwitchDREstimator with min threshold equals DMEstimator estimated reward', 'review_TestSwitchEstimators': 'review the TestSwitchEstimators class and its contextual bandit estimator unit tests'}
```

## File: facebookresearch_reagent/reagent/ope/test/unit_tests/test_slate_estimators.py

Prompts

```
['test that SwitchEstimator with max threshold equals IPSEstimator estimated reward', 'test that SwitchDREstimator with max threshold equals DoublyRobustEstimator estimated reward', 'test that SwitchEstimator with min threshold equals DMEstimator estimated reward', 'test that SwitchDREstimator with min threshold equals DMEstimator estimated reward', 'review the TestSwitchEstimators class and its contextual bandit estimator unit tests', 'test the SlateItemProbabilities class to sample slates and compute slate probabilities and expected rewards', 'test the SlateSlotItemProbabilities class to sample slates and compute slot-specific expected rewards', 'test the DCGSlateMetric class to compute discounted cumulative gain for a given slate', 'test the NDCGSlateMetric class to compute normalized discounted cumulative gain for a given slate', 'test constructing Slate objects with SlateItem entries and computing slot values from item rewards', 'test the TypeWrapper class with int values for hashing and equality comparison', 'test the TypeWrapper class with torch tensors for equality and hash behavior', 'test the Values class sort method to return keys and values ordered by descending value', 'test the Values class copy method to ensure deep copy isolation from the original', 'test the ActionDistribution class sample method for probabilistic sampling and greedy selection of top actions', 'test the RunningAverage class by adding values and checking count average and total properties', 'test the Clamper class by clamping lists tensors and numpy arrays within min max bounds', 'create a RunningAverage instance and chain add calls to track a running mean of values', 'create a Clamper with min and max bounds to clamp lists tensors or numpy arrays', 'review the Clamper class that clamps values to a min max range supporting torch and numpy']
```

Usage

```
{'test_slate_item_probabilities': 'test the SlateItemProbabilities class to sample slates and compute slate probabilities and expected rewards', 'test_slate_slot_item_probabilities': 'test the SlateSlotItemProbabilities class to sample slates and compute slot-specific expected rewards', 'test_dcg_metric': 'test the DCGSlateMetric class to compute discounted cumulative gain for a given slate', 'test_ndcg_metric': 'test the NDCGSlateMetric class to compute normalized discounted cumulative gain for a given slate', 'test_slate_construction': 'test constructing Slate objects with SlateItem entries and computing slot values from item rewards'}
```

## File: facebookresearch_reagent/reagent/ope/test/unit_tests/test_types.py

Prompts

```
['test that SwitchEstimator with max threshold equals IPSEstimator estimated reward', 'test that SwitchDREstimator with max threshold equals DoublyRobustEstimator estimated reward', 'test that SwitchEstimator with min threshold equals DMEstimator estimated reward', 'test that SwitchDREstimator with min threshold equals DMEstimator estimated reward', 'review the TestSwitchEstimators class and its contextual bandit estimator unit tests', 'test the SlateItemProbabilities class to sample slates and compute slate probabilities and expected rewards', 'test the SlateSlotItemProbabilities class to sample slates and compute slot-specific expected rewards', 'test the DCGSlateMetric class to compute discounted cumulative gain for a given slate', 'test the NDCGSlateMetric class to compute normalized discounted cumulative gain for a given slate', 'test constructing Slate objects with SlateItem entries and computing slot values from item rewards', 'test the TypeWrapper class with int values for hashing and equality comparison', 'test the TypeWrapper class with torch tensors for equality and hash behavior', 'test the Values class sort method to return keys and values ordered by descending value', 'test the Values class copy method to ensure deep copy isolation from the original', 'test the ActionDistribution class sample method for probabilistic sampling and greedy selection of top actions', 'test the RunningAverage class by adding values and checking count average and total properties', 'test the Clamper class by clamping lists tensors and numpy arrays within min max bounds', 'create a RunningAverage instance and chain add calls to track a running mean of values', 'create a Clamper with min and max bounds to clamp lists tensors or numpy arrays', 'review the Clamper class that clamps values to a min max range supporting torch and numpy']
```

Usage

```
{'test_TypeWrapper_int_hash_eq': 'test the TypeWrapper class with int values for hashing and equality comparison', 'test_TypeWrapper_tensor_equality': 'test the TypeWrapper class with torch tensors for equality and hash behavior', 'test_Values_sort_by_value': 'test the Values class sort method to return keys and values ordered by descending value', 'test_Values_copy_isolation': 'test the Values class copy method to ensure deep copy isolation from the original', 'test_ActionDistribution_sample_and_greedy': 'test the ActionDistribution class sample method for probabilistic sampling and greedy selection of top actions'}
```

## File: facebookresearch_reagent/reagent/ope/test/unit_tests/test_utils.py

Prompts

```
['test that SwitchEstimator with max threshold equals IPSEstimator estimated reward', 'test that SwitchDREstimator with max threshold equals DoublyRobustEstimator estimated reward', 'test that SwitchEstimator with min threshold equals DMEstimator estimated reward', 'test that SwitchDREstimator with min threshold equals DMEstimator estimated reward', 'review the TestSwitchEstimators class and its contextual bandit estimator unit tests', 'test the SlateItemProbabilities class to sample slates and compute slate probabilities and expected rewards', 'test the SlateSlotItemProbabilities class to sample slates and compute slot-specific expected rewards', 'test the DCGSlateMetric class to compute discounted cumulative gain for a given slate', 'test the NDCGSlateMetric class to compute normalized discounted cumulative gain for a given slate', 'test constructing Slate objects with SlateItem entries and computing slot values from item rewards', 'test the TypeWrapper class with int values for hashing and equality comparison', 'test the TypeWrapper class with torch tensors for equality and hash behavior', 'test the Values class sort method to return keys and values ordered by descending value', 'test the Values class copy method to ensure deep copy isolation from the original', 'test the ActionDistribution class sample method for probabilistic sampling and greedy selection of top actions', 'test the RunningAverage class by adding values and checking count average and total properties', 'test the Clamper class by clamping lists tensors and numpy arrays within min max bounds', 'create a RunningAverage instance and chain add calls to track a running mean of values', 'create a Clamper with min and max bounds to clamp lists tensors or numpy arrays', 'review the Clamper class that clamps values to a min max range supporting torch and numpy']
```

Usage

```
{'test_RunningAverage': 'test the RunningAverage class by adding values and checking count average and total properties', 'test_Clamper': 'test the Clamper class by clamping lists tensors and numpy arrays within min max bounds', 'create_RunningAverage': 'create a RunningAverage instance and chain add calls to track a running mean of values', 'create_Clamper': 'create a Clamper with min and max bounds to clamp lists tensors or numpy arrays', 'review_Clamper': 'review the Clamper class that clamps values to a min max range supporting torch and numpy'}
```


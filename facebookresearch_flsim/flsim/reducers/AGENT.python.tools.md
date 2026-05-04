# Agent Python Tools

- repo: facebookresearch/flsim
- repo_uri: https://github.com/facebookresearch/flsim

## File: facebookresearch_flsim/flsim/reducers/base_round_reducer.py

Prompts

```
['create a RoundReducer instance with a global model to aggregate client updates in federated learning', 'collect a model update delta from a client with an associated weight into the reducer', 'reduce all collected client updates and return the aggregated module with total weights', 'reset the round reducer internals and zero out weights for a new aggregation round', 'configure the RoundReducerConfig to use WEIGHTED_AVERAGE, AVERAGE, SUM, or WEIGHTED_SUM reduction', 'create a DPRoundReducer instance with a global model, users per round, and total users for DP federated learning', 'update the reduced module by clipping the delta module with the user update clipper before aggregation', 'reduce client updates by summing weights, adding calibrated noise, and broadcasting the noisy model to all workers', 'get the current privacy budget spent by the DP round reducer after aggregation rounds', 'reset the DP round reducer with a new reference model and reattach the privacy engine', 'build a WeightedDPRoundReducer instance with a global model, num users per round, and total users for weighted DP federated learning', 'create a WeightedDPRoundReducerConfig dataclass with min_weight, max_weight, mean_weight, and estimator_type settings for weighted DP reduction', 'test the sensitivity method of WeightedDPRoundReducer to calculate DP sensitivity using unbiased or biased estimator types', 'review the clamp_weight method to ensure client weights are clamped between min_weight and max_weight boundaries', 'refactor the _biased_estimator method to apply weight modifier via linear combination and return biased sensitivity value']
```

Usage

```
{'create_round_reducer': 'create a RoundReducer instance with a global model to aggregate client updates in federated learning', 'collect_update_from_client': 'collect a model update delta from a client with an associated weight into the reducer', 'reduce_aggregated_updates': 'reduce all collected client updates and return the aggregated module with total weights', 'reset_reducer_state': 'reset the round reducer internals and zero out weights for a new aggregation round', 'configure_reduction_type': 'configure the RoundReducerConfig to use WEIGHTED_AVERAGE, AVERAGE, SUM, or WEIGHTED_SUM reduction'}
```

## File: facebookresearch_flsim/flsim/reducers/dp_round_reducer.py

Prompts

```
['create a RoundReducer instance with a global model to aggregate client updates in federated learning', 'collect a model update delta from a client with an associated weight into the reducer', 'reduce all collected client updates and return the aggregated module with total weights', 'reset the round reducer internals and zero out weights for a new aggregation round', 'configure the RoundReducerConfig to use WEIGHTED_AVERAGE, AVERAGE, SUM, or WEIGHTED_SUM reduction', 'create a DPRoundReducer instance with a global model, users per round, and total users for DP federated learning', 'update the reduced module by clipping the delta module with the user update clipper before aggregation', 'reduce client updates by summing weights, adding calibrated noise, and broadcasting the noisy model to all workers', 'get the current privacy budget spent by the DP round reducer after aggregation rounds', 'reset the DP round reducer with a new reference model and reattach the privacy engine', 'build a WeightedDPRoundReducer instance with a global model, num users per round, and total users for weighted DP federated learning', 'create a WeightedDPRoundReducerConfig dataclass with min_weight, max_weight, mean_weight, and estimator_type settings for weighted DP reduction', 'test the sensitivity method of WeightedDPRoundReducer to calculate DP sensitivity using unbiased or biased estimator types', 'review the clamp_weight method to ensure client weights are clamped between min_weight and max_weight boundaries', 'refactor the _biased_estimator method to apply weight modifier via linear combination and return biased sensitivity value']
```

Usage

```
{'create_dp_round_reducer': 'create a DPRoundReducer instance with a global model, users per round, and total users for DP federated learning', 'update_reduced_module_with_clipping': 'update the reduced module by clipping the delta module with the user update clipper before aggregation', 'reduce_with_dp_noise': 'reduce client updates by summing weights, adding calibrated noise, and broadcasting the noisy model to all workers', 'get_privacy_budget': 'get the current privacy budget spent by the DP round reducer after aggregation rounds', 'reset_dp_round_reducer': 'reset the DP round reducer with a new reference model and reattach the privacy engine'}
```

## File: facebookresearch_flsim/flsim/reducers/weighted_dp_round_reducer.py

Prompts

```
['create a RoundReducer instance with a global model to aggregate client updates in federated learning', 'collect a model update delta from a client with an associated weight into the reducer', 'reduce all collected client updates and return the aggregated module with total weights', 'reset the round reducer internals and zero out weights for a new aggregation round', 'configure the RoundReducerConfig to use WEIGHTED_AVERAGE, AVERAGE, SUM, or WEIGHTED_SUM reduction', 'create a DPRoundReducer instance with a global model, users per round, and total users for DP federated learning', 'update the reduced module by clipping the delta module with the user update clipper before aggregation', 'reduce client updates by summing weights, adding calibrated noise, and broadcasting the noisy model to all workers', 'get the current privacy budget spent by the DP round reducer after aggregation rounds', 'reset the DP round reducer with a new reference model and reattach the privacy engine', 'build a WeightedDPRoundReducer instance with a global model, num users per round, and total users for weighted DP federated learning', 'create a WeightedDPRoundReducerConfig dataclass with min_weight, max_weight, mean_weight, and estimator_type settings for weighted DP reduction', 'test the sensitivity method of WeightedDPRoundReducer to calculate DP sensitivity using unbiased or biased estimator types', 'review the clamp_weight method to ensure client weights are clamped between min_weight and max_weight boundaries', 'refactor the _biased_estimator method to apply weight modifier via linear combination and return biased sensitivity value']
```

Usage

```
{'build_weighted_dp_reducer': 'build a WeightedDPRoundReducer instance with a global model, num users per round, and total users for weighted DP federated learning', 'create_weighted_dp_config': 'create a WeightedDPRoundReducerConfig dataclass with min_weight, max_weight, mean_weight, and estimator_type settings for weighted DP reduction', 'test_sensitivity_calculation': 'test the sensitivity method of WeightedDPRoundReducer to calculate DP sensitivity using unbiased or biased estimator types', 'review_clamp_weight': 'review the clamp_weight method to ensure client weights are clamped between min_weight and max_weight boundaries', 'refactor_biased_estimator': 'refactor the _biased_estimator method to apply weight modifier via linear combination and return biased sensitivity value'}
```


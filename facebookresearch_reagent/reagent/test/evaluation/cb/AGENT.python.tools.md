# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/test/evaluation/cb/test_integration.py

Prompts

```
['test the integration of evaluation into the LinUCB training loop with multiple batches', 'create a CBInput object with context arm features, actions, and rewards tensors', 'run a training step on the LinUCBTrainer with a CBInput batch', 'update the PolicyEvaluator evaluation model from the trained scorer after a batch', 'calculate the LinUCB model coefficients by calling _calculate_coefs on the scorer', 'test the PolicyEvaluator class by ingesting a CBInput batch and aggregating results across instances', 'test the PolicyEvaluator get_avg_reward method to verify correct importance-weighted average reward calculation', 'test the PolicyEvaluator logger integration by attaching a TensorBoardLogger and verifying log_metrics output', 'test the add_importance_weights utility function that computes importance weights from logged and model actions', 'test the PolicyEvaluator update_eval_model method to verify the evaluated model is deep-copied and frozen', 'test the synthetic contextual bandit environment by running the dynamic bandit agent and verifying accumulated rewards and regrets', 'run the dynamic bandit environment with configurable feature dimensions, batch sizes, and number of arms per episode', 'set up the TestSyntheticBandit test class with configurable feature dimension, batch size, and number of arms parameters', 'review the TestSyntheticBandit unittest class that validates model coefficients and accumulated rewards from the dynamic bandit environment', 'summarize the run_dynamic_bandit_env function which returns an agent, accumulated rewards, and accumulated regrets tensors', 'test creating a CBInput batch with context arm features, actions, rewards, weights, and log probabilities', 'test that effective_weight is zeroed where logged action differs from model action and multiplied by inverse probability where they match', 'review the TestCBEvalUtils unittest class and its assertions for contextual bandit evaluation utility functions', 'summarize the add_importance_weights function that computes importance sampling weights for off-policy evaluation of contextual bandit policies']
```

Usage

```
{'test_eval_during_training': 'test the integration of evaluation into the LinUCB training loop with multiple batches', 'create_CBInput': 'create a CBInput object with context arm features, actions, and rewards tensors', 'run_LinUCBTrainer_training_step': 'run a training step on the LinUCBTrainer with a CBInput batch', 'update_PolicyEvaluator_eval_model': 'update the PolicyEvaluator evaluation model from the trained scorer after a batch', 'calculate_LinUCB_coefs': 'calculate the LinUCB model coefficients by calling _calculate_coefs on the scorer'}
```

## File: facebookresearch_reagent/reagent/test/evaluation/cb/test_policy_evaluator.py

Prompts

```
['test the integration of evaluation into the LinUCB training loop with multiple batches', 'create a CBInput object with context arm features, actions, and rewards tensors', 'run a training step on the LinUCBTrainer with a CBInput batch', 'update the PolicyEvaluator evaluation model from the trained scorer after a batch', 'calculate the LinUCB model coefficients by calling _calculate_coefs on the scorer', 'test the PolicyEvaluator class by ingesting a CBInput batch and aggregating results across instances', 'test the PolicyEvaluator get_avg_reward method to verify correct importance-weighted average reward calculation', 'test the PolicyEvaluator logger integration by attaching a TensorBoardLogger and verifying log_metrics output', 'test the add_importance_weights utility function that computes importance weights from logged and model actions', 'test the PolicyEvaluator update_eval_model method to verify the evaluated model is deep-copied and frozen', 'test the synthetic contextual bandit environment by running the dynamic bandit agent and verifying accumulated rewards and regrets', 'run the dynamic bandit environment with configurable feature dimensions, batch sizes, and number of arms per episode', 'set up the TestSyntheticBandit test class with configurable feature dimension, batch size, and number of arms parameters', 'review the TestSyntheticBandit unittest class that validates model coefficients and accumulated rewards from the dynamic bandit environment', 'summarize the run_dynamic_bandit_env function which returns an agent, accumulated rewards, and accumulated regrets tensors', 'test creating a CBInput batch with context arm features, actions, rewards, weights, and log probabilities', 'test that effective_weight is zeroed where logged action differs from model action and multiplied by inverse probability where they match', 'review the TestCBEvalUtils unittest class and its assertions for contextual bandit evaluation utility functions', 'summarize the add_importance_weights function that computes importance sampling weights for off-policy evaluation of contextual bandit policies']
```

Usage

```
{'test_PolicyEvaluator_ingest_batch': 'test the PolicyEvaluator class by ingesting a CBInput batch and aggregating results across instances', 'test_PolicyEvaluator_get_avg_reward': 'test the PolicyEvaluator get_avg_reward method to verify correct importance-weighted average reward calculation', 'test_PolicyEvaluator_logger_integration': 'test the PolicyEvaluator logger integration by attaching a TensorBoardLogger and verifying log_metrics output', 'test_add_importance_weights': 'test the add_importance_weights utility function that computes importance weights from logged and model actions', 'test_PolicyEvaluator_update_eval_model': 'test the PolicyEvaluator update_eval_model method to verify the evaluated model is deep-copied and frozen'}
```

## File: facebookresearch_reagent/reagent/test/evaluation/cb/test_synthetic_contextual_bandit.py

Prompts

```
['test the integration of evaluation into the LinUCB training loop with multiple batches', 'create a CBInput object with context arm features, actions, and rewards tensors', 'run a training step on the LinUCBTrainer with a CBInput batch', 'update the PolicyEvaluator evaluation model from the trained scorer after a batch', 'calculate the LinUCB model coefficients by calling _calculate_coefs on the scorer', 'test the PolicyEvaluator class by ingesting a CBInput batch and aggregating results across instances', 'test the PolicyEvaluator get_avg_reward method to verify correct importance-weighted average reward calculation', 'test the PolicyEvaluator logger integration by attaching a TensorBoardLogger and verifying log_metrics output', 'test the add_importance_weights utility function that computes importance weights from logged and model actions', 'test the PolicyEvaluator update_eval_model method to verify the evaluated model is deep-copied and frozen', 'test the synthetic contextual bandit environment by running the dynamic bandit agent and verifying accumulated rewards and regrets', 'run the dynamic bandit environment with configurable feature dimensions, batch sizes, and number of arms per episode', 'set up the TestSyntheticBandit test class with configurable feature dimension, batch size, and number of arms parameters', 'review the TestSyntheticBandit unittest class that validates model coefficients and accumulated rewards from the dynamic bandit environment', 'summarize the run_dynamic_bandit_env function which returns an agent, accumulated rewards, and accumulated regrets tensors', 'test creating a CBInput batch with context arm features, actions, rewards, weights, and log probabilities', 'test that effective_weight is zeroed where logged action differs from model action and multiplied by inverse probability where they match', 'review the TestCBEvalUtils unittest class and its assertions for contextual bandit evaluation utility functions', 'summarize the add_importance_weights function that computes importance sampling weights for off-policy evaluation of contextual bandit policies']
```

Usage

```
{'test_run_synthetic_bandit': 'test the synthetic contextual bandit environment by running the dynamic bandit agent and verifying accumulated rewards and regrets', 'run_dynamic_bandit_env': 'run the dynamic bandit environment with configurable feature dimensions, batch sizes, and number of arms per episode', 'setUp_TestSyntheticBandit': 'set up the TestSyntheticBandit test class with configurable feature dimension, batch size, and number of arms parameters', 'review_TestSyntheticBandit_class': 'review the TestSyntheticBandit unittest class that validates model coefficients and accumulated rewards from the dynamic bandit environment', 'summarize_run_dynamic_bandit_env': 'summarize the run_dynamic_bandit_env function which returns an agent, accumulated rewards, and accumulated regrets tensors'}
```

## File: facebookresearch_reagent/reagent/test/evaluation/cb/test_utils.py

Prompts

```
['test the integration of evaluation into the LinUCB training loop with multiple batches', 'create a CBInput object with context arm features, actions, and rewards tensors', 'run a training step on the LinUCBTrainer with a CBInput batch', 'update the PolicyEvaluator evaluation model from the trained scorer after a batch', 'calculate the LinUCB model coefficients by calling _calculate_coefs on the scorer', 'test the PolicyEvaluator class by ingesting a CBInput batch and aggregating results across instances', 'test the PolicyEvaluator get_avg_reward method to verify correct importance-weighted average reward calculation', 'test the PolicyEvaluator logger integration by attaching a TensorBoardLogger and verifying log_metrics output', 'test the add_importance_weights utility function that computes importance weights from logged and model actions', 'test the PolicyEvaluator update_eval_model method to verify the evaluated model is deep-copied and frozen', 'test the synthetic contextual bandit environment by running the dynamic bandit agent and verifying accumulated rewards and regrets', 'run the dynamic bandit environment with configurable feature dimensions, batch sizes, and number of arms per episode', 'set up the TestSyntheticBandit test class with configurable feature dimension, batch size, and number of arms parameters', 'review the TestSyntheticBandit unittest class that validates model coefficients and accumulated rewards from the dynamic bandit environment', 'summarize the run_dynamic_bandit_env function which returns an agent, accumulated rewards, and accumulated regrets tensors', 'test creating a CBInput batch with context arm features, actions, rewards, weights, and log probabilities', 'test that effective_weight is zeroed where logged action differs from model action and multiplied by inverse probability where they match', 'review the TestCBEvalUtils unittest class and its assertions for contextual bandit evaluation utility functions', 'summarize the add_importance_weights function that computes importance sampling weights for off-policy evaluation of contextual bandit policies']
```

Usage

```
{'test_add_importance_weights': 'test the add_importance_weights function to verify importance weights are computed correctly for CBInput batches', 'test_CBInput_batch_setup': 'test creating a CBInput batch with context arm features, actions, rewards, weights, and log probabilities', 'test_effective_weight_calculation': 'test that effective_weight is zeroed where logged action differs from model action and multiplied by inverse probability where they match', 'review_TestCBEvalUtils_class': 'review the TestCBEvalUtils unittest class and its assertions for contextual bandit evaluation utility functions', 'summarize_add_importance_weights': 'summarize the add_importance_weights function that computes importance sampling weights for off-policy evaluation of contextual bandit policies'}
```


# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_cl/frameworks/baselines.py

Prompts

```
['create a OneStep framework instance with seed and params to run a single algorithm for continual learning', 'create a TwoSteps framework instance that runs two algorithms sequentially for regularization in continual learning', 'run get_checkpoint to find the latest policy checkpoint file in a directory and return its path and stage number', 'train a policy agent using the OneStep framework by calling _train with a task and logger', 'get an evaluation agent from OneStep by calling get_evaluation_agent with a task_id to set and return the policy agent', 'create a Subspace framework instance with seed and params config for continual learning', 'get the latest policy checkpoint file path and next stage number from a directory', 'train the Subspace policy and critic agents on a task with configurable learning rate scaling', 'evaluate the Subspace model over a set of test tasks and return average reward metrics']
```

Usage

```
{'create_OneStep_framework': 'create a OneStep framework instance with seed and params to run a single algorithm for continual learning', 'create_TwoSteps_framework': 'create a TwoSteps framework instance that runs two algorithms sequentially for regularization in continual learning', 'run_get_checkpoint': 'run get_checkpoint to find the latest policy checkpoint file in a directory and return its path and stage number', 'train_OneStep_policy': 'train a policy agent using the OneStep framework by calling _train with a task and logger', 'get_evaluation_agent': 'get an evaluation agent from OneStep by calling get_evaluation_agent with a task_id to set and return the policy agent'}
```

## File: facebookresearch_salina/salina_cl/frameworks/subspaces.py

Prompts

```
['create a OneStep framework instance with seed and params to run a single algorithm for continual learning', 'create a TwoSteps framework instance that runs two algorithms sequentially for regularization in continual learning', 'run get_checkpoint to find the latest policy checkpoint file in a directory and return its path and stage number', 'train a policy agent using the OneStep framework by calling _train with a task and logger', 'get an evaluation agent from OneStep by calling get_evaluation_agent with a task_id to set and return the policy agent', 'create a Subspace framework instance with seed and params config for continual learning', 'get the latest policy checkpoint file path and next stage number from a directory', 'train the Subspace policy and critic agents on a task with configurable learning rate scaling', 'evaluate the Subspace model over a set of test tasks and return average reward metrics']
```

Usage

```
{'create_subspace_framework': 'create a Subspace framework instance with seed and params config for continual learning', 'get_checkpoint_latest': 'get the latest policy checkpoint file path and next stage number from a directory', 'train_subspace_policy': 'train the Subspace policy and critic agents on a task with configurable learning rate scaling', 'evaluate_subspace_model': 'evaluate the Subspace model over a set of test tasks and return average reward metrics', 'get_evaluation_agent': 'get a deep copy of the policy agent for evaluation on a specific task ID'}
```


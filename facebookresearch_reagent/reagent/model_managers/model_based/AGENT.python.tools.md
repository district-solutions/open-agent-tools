# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/model_managers/model_based/cross_entropy_method.py

Prompts

```
['build a CrossEntropyMethod trainer with world model ensemble and CEM planner network for RL planning', 'create a CEMPolicy from a CEMTrainer module to act on observations with greedy planning', 'run the CEMPolicy act method on feature data observations to get greedy action outputs', 'review the CrossEntropyMethod build_trainer method that constructs world model trainers and CEM planner networks', 'refactor the CEMPolicy act method to support possible actions mask for discrete action filtering', 'build a Seq2RewardTrainer from a Seq2RewardModel using normalization data and GPU settings', 'create a Seq2RewardModel dataclass with default Seq2RewardNetBuilder and FullyConnected compress net builder', 'get a Seq2RewardReporter instance from a Seq2RewardModel using action names from trainer params', 'review the Seq2RewardModel class and its build_trainer and get_reporter methods', 'refactor the Seq2RewardModel to use a custom ValueNetBuilder instead of the default Seq2RewardNetBuilder', 'build a SyntheticReward model manager to train models that attribute single step rewards from sparse delayed rewards', 'create a RewardNetTrainer using the SyntheticReward build_trainer method with normalization data and GPU settings', 'build a TorchScript predictor module from a trained RewardNetTrainer using the build_serving_module method', 'run feature identification on input table spec to identify dense state and action normalization parameters', 'query synthetic reward training data using the SyntheticRewardDataModule query_data method with a data fetcher', 'build an MDNRNNTrainer from a WorldModel instance with normalization data and GPU support', 'create a WorldModel dataclass instance with MDNRNNTrainerParameters for world model training', 'review the WorldModel class that extends WorldModelBase for model-based RL training', 'summarize the build_trainer method that constructs a MemoryNetwork and MDNRNNTrainer', 'test the WorldModel param_hash implementation for consistent parameter-based hashing']
```

Usage

```
{'build_CrossEntropyMethod_trainer': 'build a CrossEntropyMethod trainer with world model ensemble and CEM planner network for RL planning', 'create_CEMPolicy_from_trainer': 'create a CEMPolicy from a CEMTrainer module to act on observations with greedy planning', 'run_CEMPolicy_act': 'run the CEMPolicy act method on feature data observations to get greedy action outputs', 'review_CrossEntropyMethod_build_trainer': 'review the CrossEntropyMethod build_trainer method that constructs world model trainers and CEM planner networks', 'refactor_CEMPolicy_act': 'refactor the CEMPolicy act method to support possible actions mask for discrete action filtering'}
```

## File: facebookresearch_reagent/reagent/model_managers/model_based/seq2reward_model.py

Prompts

```
['build a CrossEntropyMethod trainer with world model ensemble and CEM planner network for RL planning', 'create a CEMPolicy from a CEMTrainer module to act on observations with greedy planning', 'run the CEMPolicy act method on feature data observations to get greedy action outputs', 'review the CrossEntropyMethod build_trainer method that constructs world model trainers and CEM planner networks', 'refactor the CEMPolicy act method to support possible actions mask for discrete action filtering', 'build a Seq2RewardTrainer from a Seq2RewardModel using normalization data and GPU settings', 'create a Seq2RewardModel dataclass with default Seq2RewardNetBuilder and FullyConnected compress net builder', 'get a Seq2RewardReporter instance from a Seq2RewardModel using action names from trainer params', 'review the Seq2RewardModel class and its build_trainer and get_reporter methods', 'refactor the Seq2RewardModel to use a custom ValueNetBuilder instead of the default Seq2RewardNetBuilder', 'build a SyntheticReward model manager to train models that attribute single step rewards from sparse delayed rewards', 'create a RewardNetTrainer using the SyntheticReward build_trainer method with normalization data and GPU settings', 'build a TorchScript predictor module from a trained RewardNetTrainer using the build_serving_module method', 'run feature identification on input table spec to identify dense state and action normalization parameters', 'query synthetic reward training data using the SyntheticRewardDataModule query_data method with a data fetcher', 'build an MDNRNNTrainer from a WorldModel instance with normalization data and GPU support', 'create a WorldModel dataclass instance with MDNRNNTrainerParameters for world model training', 'review the WorldModel class that extends WorldModelBase for model-based RL training', 'summarize the build_trainer method that constructs a MemoryNetwork and MDNRNNTrainer', 'test the WorldModel param_hash implementation for consistent parameter-based hashing']
```

Usage

```
{'build_seq2reward_trainer': 'build a Seq2RewardTrainer from a Seq2RewardModel using normalization data and GPU settings', 'create_seq2reward_model': 'create a Seq2RewardModel dataclass with default Seq2RewardNetBuilder and FullyConnected compress net builder', 'get_seq2reward_reporter': 'get a Seq2RewardReporter instance from a Seq2RewardModel using action names from trainer params', 'review_seq2reward_model_class': 'review the Seq2RewardModel class and its build_trainer and get_reporter methods', 'refactor_seq2reward_net_builder': 'refactor the Seq2RewardModel to use a custom ValueNetBuilder instead of the default Seq2RewardNetBuilder'}
```

## File: facebookresearch_reagent/reagent/model_managers/model_based/synthetic_reward.py

Prompts

```
['build a CrossEntropyMethod trainer with world model ensemble and CEM planner network for RL planning', 'create a CEMPolicy from a CEMTrainer module to act on observations with greedy planning', 'run the CEMPolicy act method on feature data observations to get greedy action outputs', 'review the CrossEntropyMethod build_trainer method that constructs world model trainers and CEM planner networks', 'refactor the CEMPolicy act method to support possible actions mask for discrete action filtering', 'build a Seq2RewardTrainer from a Seq2RewardModel using normalization data and GPU settings', 'create a Seq2RewardModel dataclass with default Seq2RewardNetBuilder and FullyConnected compress net builder', 'get a Seq2RewardReporter instance from a Seq2RewardModel using action names from trainer params', 'review the Seq2RewardModel class and its build_trainer and get_reporter methods', 'refactor the Seq2RewardModel to use a custom ValueNetBuilder instead of the default Seq2RewardNetBuilder', 'build a SyntheticReward model manager to train models that attribute single step rewards from sparse delayed rewards', 'create a RewardNetTrainer using the SyntheticReward build_trainer method with normalization data and GPU settings', 'build a TorchScript predictor module from a trained RewardNetTrainer using the build_serving_module method', 'run feature identification on input table spec to identify dense state and action normalization parameters', 'query synthetic reward training data using the SyntheticRewardDataModule query_data method with a data fetcher', 'build an MDNRNNTrainer from a WorldModel instance with normalization data and GPU support', 'create a WorldModel dataclass instance with MDNRNNTrainerParameters for world model training', 'review the WorldModel class that extends WorldModelBase for model-based RL training', 'summarize the build_trainer method that constructs a MemoryNetwork and MDNRNNTrainer', 'test the WorldModel param_hash implementation for consistent parameter-based hashing']
```

Usage

```
{'build_synthetic_reward_model_manager': 'build a SyntheticReward model manager to train models that attribute single step rewards from sparse delayed rewards', 'create_reward_net_trainer': 'create a RewardNetTrainer using the SyntheticReward build_trainer method with normalization data and GPU settings', 'build_serving_module': 'build a TorchScript predictor module from a trained RewardNetTrainer using the build_serving_module method', 'run_feature_identification': 'run feature identification on input table spec to identify dense state and action normalization parameters', 'query_synthetic_reward_data': 'query synthetic reward training data using the SyntheticRewardDataModule query_data method with a data fetcher'}
```

## File: facebookresearch_reagent/reagent/model_managers/model_based/world_model.py

Prompts

```
['build a CrossEntropyMethod trainer with world model ensemble and CEM planner network for RL planning', 'create a CEMPolicy from a CEMTrainer module to act on observations with greedy planning', 'run the CEMPolicy act method on feature data observations to get greedy action outputs', 'review the CrossEntropyMethod build_trainer method that constructs world model trainers and CEM planner networks', 'refactor the CEMPolicy act method to support possible actions mask for discrete action filtering', 'build a Seq2RewardTrainer from a Seq2RewardModel using normalization data and GPU settings', 'create a Seq2RewardModel dataclass with default Seq2RewardNetBuilder and FullyConnected compress net builder', 'get a Seq2RewardReporter instance from a Seq2RewardModel using action names from trainer params', 'review the Seq2RewardModel class and its build_trainer and get_reporter methods', 'refactor the Seq2RewardModel to use a custom ValueNetBuilder instead of the default Seq2RewardNetBuilder', 'build a SyntheticReward model manager to train models that attribute single step rewards from sparse delayed rewards', 'create a RewardNetTrainer using the SyntheticReward build_trainer method with normalization data and GPU settings', 'build a TorchScript predictor module from a trained RewardNetTrainer using the build_serving_module method', 'run feature identification on input table spec to identify dense state and action normalization parameters', 'query synthetic reward training data using the SyntheticRewardDataModule query_data method with a data fetcher', 'build an MDNRNNTrainer from a WorldModel instance with normalization data and GPU support', 'create a WorldModel dataclass instance with MDNRNNTrainerParameters for world model training', 'review the WorldModel class that extends WorldModelBase for model-based RL training', 'summarize the build_trainer method that constructs a MemoryNetwork and MDNRNNTrainer', 'test the WorldModel param_hash implementation for consistent parameter-based hashing']
```

Usage

```
{'build_world_model_trainer': 'build an MDNRNNTrainer from a WorldModel instance with normalization data and GPU support', 'create_world_model_dataclass': 'create a WorldModel dataclass instance with MDNRNNTrainerParameters for world model training', 'review_world_model_class': 'review the WorldModel class that extends WorldModelBase for model-based RL training', 'summarize_build_trainer_method': 'summarize the build_trainer method that constructs a MemoryNetwork and MDNRNNTrainer', 'test_world_model_hash': 'test the WorldModel param_hash implementation for consistent parameter-based hashing'}
```


# Agent Python Tools

- repo: facebookresearch/mbrl-lib
- repo_uri: https://github.com/facebookresearch/mbrl-lib

## File: facebookresearch_mbrl-lib/mbrl/algorithms/mbpo.py

Prompts

```
['run the MBPO train function to train a SAC agent on a gymnasium environment with model-based rollouts', 'run rollout_model_and_populate_sac_buffer to generate imagined trajectories from a learned dynamics model and populate the SAC replay buffer', 'evaluate a SAC agent on a test environment over multiple episodes and return the average episode reward', 'create or resize a SAC replay buffer with maybe_replace_sac_buffer preserving existing transitions when capacity changes', 'review the MBPO train function to understand the training loop with alternating real environment steps and model-based imagined rollouts', 'run the PETS algorithm training loop on a Gym environment with a dynamics model and trajectory optimization agent', 'train a transition reward dynamics model using the PETS algorithm with periodic model updates during environment interaction', 'create and populate a replay buffer with initial random exploration trajectories for model-based RL training', 'review the train function that implements PETS model-based RL with ensemble dynamics models and trajectory sampling', 'summarize the PETS training loop that alternates between model training and agent environment interaction steps', 'run the PlaNet model-based RL training loop on a gymnasium environment with a config', 'summarize the METRICS_LOG_FORMAT constant that defines observation loss, reward loss, gradient norm, and KL loss', 'test the PlaNet training loop that alternates between model gradient updates and environment rollouts', 'refactor the batch_callback inner function to customize how training metrics are accumulated per batch']
```

Usage

```
{'run_mbpo_training': 'run the MBPO train function to train a SAC agent on a gymnasium environment with model-based rollouts', 'run_model_rollout': 'run rollout_model_and_populate_sac_buffer to generate imagined trajectories from a learned dynamics model and populate the SAC replay buffer', 'evaluate_sac_agent': 'evaluate a SAC agent on a test environment over multiple episodes and return the average episode reward', 'create_sac_buffer': 'create or resize a SAC replay buffer with maybe_replace_sac_buffer preserving existing transitions when capacity changes', 'review_mbpo_train': 'review the MBPO train function to understand the training loop with alternating real environment steps and model-based imagined rollouts'}
```

## File: facebookresearch_mbrl-lib/mbrl/algorithms/pets.py

Prompts

```
['run the MBPO train function to train a SAC agent on a gymnasium environment with model-based rollouts', 'run rollout_model_and_populate_sac_buffer to generate imagined trajectories from a learned dynamics model and populate the SAC replay buffer', 'evaluate a SAC agent on a test environment over multiple episodes and return the average episode reward', 'create or resize a SAC replay buffer with maybe_replace_sac_buffer preserving existing transitions when capacity changes', 'review the MBPO train function to understand the training loop with alternating real environment steps and model-based imagined rollouts', 'run the PETS algorithm training loop on a Gym environment with a dynamics model and trajectory optimization agent', 'train a transition reward dynamics model using the PETS algorithm with periodic model updates during environment interaction', 'create and populate a replay buffer with initial random exploration trajectories for model-based RL training', 'review the train function that implements PETS model-based RL with ensemble dynamics models and trajectory sampling', 'summarize the PETS training loop that alternates between model training and agent environment interaction steps', 'run the PlaNet model-based RL training loop on a gymnasium environment with a config', 'summarize the METRICS_LOG_FORMAT constant that defines observation loss, reward loss, gradient norm, and KL loss', 'test the PlaNet training loop that alternates between model gradient updates and environment rollouts', 'refactor the batch_callback inner function to customize how training metrics are accumulated per batch']
```

Usage

```
{'run_pets_training': 'run the PETS algorithm training loop on a Gym environment with a dynamics model and trajectory optimization agent', 'train_dynamics_model': 'train a transition reward dynamics model using the PETS algorithm with periodic model updates during environment interaction', 'create_replay_buffer': 'create and populate a replay buffer with initial random exploration trajectories for model-based RL training', 'review_train_function': 'review the train function that implements PETS model-based RL with ensemble dynamics models and trajectory sampling', 'summarize_pets_algorithm': 'summarize the PETS training loop that alternates between model training and agent environment interaction steps'}
```

## File: facebookresearch_mbrl-lib/mbrl/algorithms/planet.py

Prompts

```
['run the MBPO train function to train a SAC agent on a gymnasium environment with model-based rollouts', 'run rollout_model_and_populate_sac_buffer to generate imagined trajectories from a learned dynamics model and populate the SAC replay buffer', 'evaluate a SAC agent on a test environment over multiple episodes and return the average episode reward', 'create or resize a SAC replay buffer with maybe_replace_sac_buffer preserving existing transitions when capacity changes', 'review the MBPO train function to understand the training loop with alternating real environment steps and model-based imagined rollouts', 'run the PETS algorithm training loop on a Gym environment with a dynamics model and trajectory optimization agent', 'train a transition reward dynamics model using the PETS algorithm with periodic model updates during environment interaction', 'create and populate a replay buffer with initial random exploration trajectories for model-based RL training', 'review the train function that implements PETS model-based RL with ensemble dynamics models and trajectory sampling', 'summarize the PETS training loop that alternates between model training and agent environment interaction steps', 'run the PlaNet model-based RL training loop on a gymnasium environment with a config', 'summarize the METRICS_LOG_FORMAT constant that defines observation loss, reward loss, gradient norm, and KL loss', 'test the PlaNet training loop that alternates between model gradient updates and environment rollouts', 'refactor the batch_callback inner function to customize how training metrics are accumulated per batch']
```

Usage

```
{'run_planet_training': 'run the PlaNet model-based RL training loop on a gymnasium environment with a config', 'review_train_function': 'review the train function that runs PlaNet MBRL episodes with model training and CEM planning', 'summarize_metrics_log_format': 'summarize the METRICS_LOG_FORMAT constant that defines observation loss, reward loss, gradient norm, and KL loss', 'test_planet_training_loop': 'test the PlaNet training loop that alternates between model gradient updates and environment rollouts', 'refactor_batch_callback': 'refactor the batch_callback inner function to customize how training metrics are accumulated per batch'}
```


# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/rlBreakoutMinAtar/src/helpers.py

Prompts

```
['load a YAML training config file with a custom seed and optional learning rate into a DotMap', 'save a Python object as a pickle file to the specified path, creating parent directories if needed', 'load and return a pickled Python object from the given file path', 'review the load_config function to understand how it parses YAML configs and overrides seed and learning rate', 'refactor save_pkl_object to support compression or alternative serialization formats beyond pickle', 'build a split actor-critic MLP model for the Breakout MinAtar environment using Flax and JAX', 'create a Model instance with configurable hidden units and layers for PPO reinforcement learning', 'test the get_model_ready function to instantiate and initialize a model with random keys', 'refactor the Model class to support flattening 2D or 3D image observations before processing', 'review the default_mlp_init function that returns a uniform weight initializer with configurable scale', 'run the PPO training loop for Breakout-MinAtar with a given config, model, and parameters', 'create a BatchManager to manage rollout buffers with GAE lambda, discount, and environment count', 'calculate generalized advantage estimation from value predictions, rewards, and done flags', 'evaluate a trained policy by running batch rollouts and computing mean cumulative return', 'compute the combined PPO actor and critic loss with clipping, entropy bonus, and value targets']
```

Usage

```
{'load_config_from_yaml': 'load a YAML training config file with a custom seed and optional learning rate into a DotMap', 'save_pkl_object_to_file': 'save a Python object as a pickle file to the specified path, creating parent directories if needed', 'load_pkl_object_from_file': 'load and return a pickled Python object from the given file path', 'review_load_config': 'review the load_config function to understand how it parses YAML configs and overrides seed and learning rate', 'refactor_save_pkl_object': 'refactor save_pkl_object to support compression or alternative serialization formats beyond pickle'}
```

## File: facebookresearch_mlgym/data/rlBreakoutMinAtar/src/networks.py

Prompts

```
['load a YAML training config file with a custom seed and optional learning rate into a DotMap', 'save a Python object as a pickle file to the specified path, creating parent directories if needed', 'load and return a pickled Python object from the given file path', 'review the load_config function to understand how it parses YAML configs and overrides seed and learning rate', 'refactor save_pkl_object to support compression or alternative serialization formats beyond pickle', 'build a split actor-critic MLP model for the Breakout MinAtar environment using Flax and JAX', 'create a Model instance with configurable hidden units and layers for PPO reinforcement learning', 'test the get_model_ready function to instantiate and initialize a model with random keys', 'refactor the Model class to support flattening 2D or 3D image observations before processing', 'review the default_mlp_init function that returns a uniform weight initializer with configurable scale', 'run the PPO training loop for Breakout-MinAtar with a given config, model, and parameters', 'create a BatchManager to manage rollout buffers with GAE lambda, discount, and environment count', 'calculate generalized advantage estimation from value predictions, rewards, and done flags', 'evaluate a trained policy by running batch rollouts and computing mean cumulative return', 'compute the combined PPO actor and critic loss with clipping, entropy bonus, and value targets']
```

Usage

```
{'build_model_for_breakout': 'build a split actor-critic MLP model for the Breakout MinAtar environment using Flax and JAX', 'create_model_instance': 'create a Model instance with configurable hidden units and layers for PPO reinforcement learning', 'test_get_model_ready': 'test the get_model_ready function to instantiate and initialize a model with random keys', 'refactor_model_flatten': 'refactor the Model class to support flattening 2D or 3D image observations before processing', 'review_default_mlp_init': 'review the default_mlp_init function that returns a uniform weight initializer with configurable scale'}
```

## File: facebookresearch_mlgym/data/rlBreakoutMinAtar/src/policy.py

Prompts

```
['load a YAML training config file with a custom seed and optional learning rate into a DotMap', 'save a Python object as a pickle file to the specified path, creating parent directories if needed', 'load and return a pickled Python object from the given file path', 'review the load_config function to understand how it parses YAML configs and overrides seed and learning rate', 'refactor save_pkl_object to support compression or alternative serialization formats beyond pickle', 'build a split actor-critic MLP model for the Breakout MinAtar environment using Flax and JAX', 'create a Model instance with configurable hidden units and layers for PPO reinforcement learning', 'test the get_model_ready function to instantiate and initialize a model with random keys', 'refactor the Model class to support flattening 2D or 3D image observations before processing', 'review the default_mlp_init function that returns a uniform weight initializer with configurable scale', 'run the PPO training loop for Breakout-MinAtar with a given config, model, and parameters', 'create a BatchManager to manage rollout buffers with GAE lambda, discount, and environment count', 'calculate generalized advantage estimation from value predictions, rewards, and done flags', 'evaluate a trained policy by running batch rollouts and computing mean cumulative return', 'compute the combined PPO actor and critic loss with clipping, entropy bonus, and value targets']
```

Usage

```
{'run_train_ppo': 'run the PPO training loop for Breakout-MinAtar with a given config, model, and parameters', 'create_batch_manager': 'create a BatchManager to manage rollout buffers with GAE lambda, discount, and environment count', 'calculate_gae_advantages': 'calculate generalized advantage estimation from value predictions, rewards, and done flags', 'evaluate_rollout': 'evaluate a trained policy by running batch rollouts and computing mean cumulative return', 'compute_actor_critic_loss': 'compute the combined PPO actor and critic loss with clipping, entropy bonus, and value targets'}
```


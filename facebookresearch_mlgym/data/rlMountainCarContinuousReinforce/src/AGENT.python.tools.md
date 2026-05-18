# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/rlMountainCarContinuousReinforce/src/helpers.py

Prompts

```
['load a YAML training config file with optional seed and learning rate overrides into a DotMap', 'save a Python object to a pickle file, creating parent directories as needed', 'load a pickled Python object from a file and return it', 'review the load_config function to understand how YAML configs are parsed and overridden', 'test saving and loading a Python object via pickle using save_pkl_object and load_pkl_object', 'build a split actor-critic Model for MountainCarContinuous-v0 using Flax and JAX', 'create a Model instance with configurable hidden units and layers for PPO reinforcement learning', 'test the get_model_ready function to instantiate and initialize a Model with a given RNG and config', 'review the Model __call__ method that returns value estimates and a MultivariateNormalDiag policy distribution', 'refactor the default_mlp_init function to use a different Flax initializer scale for weight initialization', 'run the REINFORCE training loop for MountainCarContinuous-v0 using JAX and gymnax', 'create a BatchManager to collect rollout transitions and compute GAE advantage estimates', 'create a RolloutManager to perform vectorized batch rollouts in the MountainCarContinuous environment', 'compute the REINFORCE policy loss using log probabilities and GAE advantage estimates', 'update the policy network parameters using minibatch gradient descent over flattened rollout data']
```

Usage

```
{'load_config_yaml': 'load a YAML training config file with optional seed and learning rate overrides into a DotMap', 'save_pkl_object': 'save a Python object to a pickle file, creating parent directories as needed', 'load_pkl_object': 'load a pickled Python object from a file and return it', 'review_load_config': 'review the load_config function to understand how YAML configs are parsed and overridden', 'test_save_and_load_pkl': 'test saving and loading a Python object via pickle using save_pkl_object and load_pkl_object'}
```

## File: facebookresearch_mlgym/data/rlMountainCarContinuousReinforce/src/networks.py

Prompts

```
['load a YAML training config file with optional seed and learning rate overrides into a DotMap', 'save a Python object to a pickle file, creating parent directories as needed', 'load a pickled Python object from a file and return it', 'review the load_config function to understand how YAML configs are parsed and overridden', 'test saving and loading a Python object via pickle using save_pkl_object and load_pkl_object', 'build a split actor-critic Model for MountainCarContinuous-v0 using Flax and JAX', 'create a Model instance with configurable hidden units and layers for PPO reinforcement learning', 'test the get_model_ready function to instantiate and initialize a Model with a given RNG and config', 'review the Model __call__ method that returns value estimates and a MultivariateNormalDiag policy distribution', 'refactor the default_mlp_init function to use a different Flax initializer scale for weight initialization', 'run the REINFORCE training loop for MountainCarContinuous-v0 using JAX and gymnax', 'create a BatchManager to collect rollout transitions and compute GAE advantage estimates', 'create a RolloutManager to perform vectorized batch rollouts in the MountainCarContinuous environment', 'compute the REINFORCE policy loss using log probabilities and GAE advantage estimates', 'update the policy network parameters using minibatch gradient descent over flattened rollout data']
```

Usage

```
{'build_model_for_mountain_car': 'build a split actor-critic Model for MountainCarContinuous-v0 using Flax and JAX', 'create_model_instance': 'create a Model instance with configurable hidden units and layers for PPO reinforcement learning', 'test_get_model_ready': 'test the get_model_ready function to instantiate and initialize a Model with a given RNG and config', 'review_model_call': 'review the Model __call__ method that returns value estimates and a MultivariateNormalDiag policy distribution', 'refactor_default_mlp_init': 'refactor the default_mlp_init function to use a different Flax initializer scale for weight initialization'}
```

## File: facebookresearch_mlgym/data/rlMountainCarContinuousReinforce/src/policy.py

Prompts

```
['load a YAML training config file with optional seed and learning rate overrides into a DotMap', 'save a Python object to a pickle file, creating parent directories as needed', 'load a pickled Python object from a file and return it', 'review the load_config function to understand how YAML configs are parsed and overridden', 'test saving and loading a Python object via pickle using save_pkl_object and load_pkl_object', 'build a split actor-critic Model for MountainCarContinuous-v0 using Flax and JAX', 'create a Model instance with configurable hidden units and layers for PPO reinforcement learning', 'test the get_model_ready function to instantiate and initialize a Model with a given RNG and config', 'review the Model __call__ method that returns value estimates and a MultivariateNormalDiag policy distribution', 'refactor the default_mlp_init function to use a different Flax initializer scale for weight initialization', 'run the REINFORCE training loop for MountainCarContinuous-v0 using JAX and gymnax', 'create a BatchManager to collect rollout transitions and compute GAE advantage estimates', 'create a RolloutManager to perform vectorized batch rollouts in the MountainCarContinuous environment', 'compute the REINFORCE policy loss using log probabilities and GAE advantage estimates', 'update the policy network parameters using minibatch gradient descent over flattened rollout data']
```

Usage

```
{'train_rl_mountain_car': 'run the REINFORCE training loop for MountainCarContinuous-v0 using JAX and gymnax', 'create_batch_manager': 'create a BatchManager to collect rollout transitions and compute GAE advantage estimates', 'create_rollout_manager': 'create a RolloutManager to perform vectorized batch rollouts in the MountainCarContinuous environment', 'compute_reinforce_loss': 'compute the REINFORCE policy loss using log probabilities and GAE advantage estimates', 'update_policy_network': 'update the policy network parameters using minibatch gradient descent over flattened rollout data'}
```


# Agent Python Tools

- repo: google-deepmind/discorl
- repo_uri: https://github.com/google-deepmind/disco_rl

## File: google-deepmind_discorl/disco_rl/agent.py

Prompts

```
['create an Agent instance using the disco update rule with observation and action specs', 'create an Agent instance using the actor_critic update rule with observation and action specs', 'run a single actor step to sample actions from the agent network for a timestep', 'run a learner training step that computes gradients and updates agent parameters from a rollout', 'get the default Disco-103 configuration settings as a ConfigDict for agent initialization', 'build an optax Adam optimizer where the second moment denominator blocks gradient flow for meta-learning', 'create a GradientTransformation that rescales gradients using Adam with stop_gradient on the second moment estimate', 'test the scale_by_adam_sg_denom function by initializing state and applying gradient updates to model parameters', 'refactor an existing Adam optimizer to add stop_gradient on the second moment for meta-gradient isolation', 'review the scale_by_adam_sg_denom function and its use of jax.lax.stop_gradient on nu_hat for meta-learning stability', 'create a ValueFnConfig dataclass to configure value function network, learning rate, discount, and EMA settings', 'create an UpdateRuleInputs dataclass to hold observations, actions, rewards, and terminal flags for the update rule', 'convert an ActorRollout into an ActorTimestep using the from_rollout classmethod', 'convert an ActorTimestep into an EnvironmentTimestep using the to_env_timestep method', 'compute forward and backward RNN reset masks from UpdateRuleInputs using should_reset_mask_fwd and should_reset_mask_bwd properties', 'shard a pytree of numpy arrays across multiple JAX devices using device_put_sharded', 'gather sharded data from JAX devices and reshape into a single flattened batch array', 'perform a batched index lookup into a lookup table using Haiku BatchApply and vmap', 'prepend a batch dimension to a tree of ArraySpec or specs.Array shapes', 'initialize a MovingAverage tracker, update EMA state, and normalize a pytree of values by mean and variance']
```

Usage

```
{'create_agent_with_disco_update_rule': 'create an Agent instance using the disco update rule with observation and action specs', 'create_agent_with_actor_critic_update_rule': 'create an Agent instance using the actor_critic update rule with observation and action specs', 'run_actor_step': 'run a single actor step to sample actions from the agent network for a timestep', 'run_learner_step': 'run a learner training step that computes gradients and updates agent parameters from a rollout', 'get_settings_disco': 'get the default Disco-103 configuration settings as a ConfigDict for agent initialization'}
```

## File: google-deepmind_discorl/disco_rl/optimizers.py

Prompts

```
['create an Agent instance using the disco update rule with observation and action specs', 'create an Agent instance using the actor_critic update rule with observation and action specs', 'run a single actor step to sample actions from the agent network for a timestep', 'run a learner training step that computes gradients and updates agent parameters from a rollout', 'get the default Disco-103 configuration settings as a ConfigDict for agent initialization', 'build an optax Adam optimizer where the second moment denominator blocks gradient flow for meta-learning', 'create a GradientTransformation that rescales gradients using Adam with stop_gradient on the second moment estimate', 'test the scale_by_adam_sg_denom function by initializing state and applying gradient updates to model parameters', 'refactor an existing Adam optimizer to add stop_gradient on the second moment for meta-gradient isolation', 'review the scale_by_adam_sg_denom function and its use of jax.lax.stop_gradient on nu_hat for meta-learning stability', 'create a ValueFnConfig dataclass to configure value function network, learning rate, discount, and EMA settings', 'create an UpdateRuleInputs dataclass to hold observations, actions, rewards, and terminal flags for the update rule', 'convert an ActorRollout into an ActorTimestep using the from_rollout classmethod', 'convert an ActorTimestep into an EnvironmentTimestep using the to_env_timestep method', 'compute forward and backward RNN reset masks from UpdateRuleInputs using should_reset_mask_fwd and should_reset_mask_bwd properties', 'shard a pytree of numpy arrays across multiple JAX devices using device_put_sharded', 'gather sharded data from JAX devices and reshape into a single flattened batch array', 'perform a batched index lookup into a lookup table using Haiku BatchApply and vmap', 'prepend a batch dimension to a tree of ArraySpec or specs.Array shapes', 'initialize a MovingAverage tracker, update EMA state, and normalize a pytree of values by mean and variance']
```

Usage

```
{'build_optimizer_adam_sg': 'build an optax Adam optimizer where the second moment denominator blocks gradient flow for meta-learning', 'create_gradient_transformation': 'create a GradientTransformation that rescales gradients using Adam with stop_gradient on the second moment estimate', 'test_scale_by_adam_sg_denom': 'test the scale_by_adam_sg_denom function by initializing state and applying gradient updates to model parameters', 'refactor_optimizer_stop_gradient': 'refactor an existing Adam optimizer to add stop_gradient on the second moment for meta-gradient isolation', 'review_adam_sg_denom': 'review the scale_by_adam_sg_denom function and its use of jax.lax.stop_gradient on nu_hat for meta-learning stability'}
```

## File: google-deepmind_discorl/disco_rl/types.py

Prompts

```
['create an Agent instance using the disco update rule with observation and action specs', 'create an Agent instance using the actor_critic update rule with observation and action specs', 'run a single actor step to sample actions from the agent network for a timestep', 'run a learner training step that computes gradients and updates agent parameters from a rollout', 'get the default Disco-103 configuration settings as a ConfigDict for agent initialization', 'build an optax Adam optimizer where the second moment denominator blocks gradient flow for meta-learning', 'create a GradientTransformation that rescales gradients using Adam with stop_gradient on the second moment estimate', 'test the scale_by_adam_sg_denom function by initializing state and applying gradient updates to model parameters', 'refactor an existing Adam optimizer to add stop_gradient on the second moment for meta-gradient isolation', 'review the scale_by_adam_sg_denom function and its use of jax.lax.stop_gradient on nu_hat for meta-learning stability', 'create a ValueFnConfig dataclass to configure value function network, learning rate, discount, and EMA settings', 'create an UpdateRuleInputs dataclass to hold observations, actions, rewards, and terminal flags for the update rule', 'convert an ActorRollout into an ActorTimestep using the from_rollout classmethod', 'convert an ActorTimestep into an EnvironmentTimestep using the to_env_timestep method', 'compute forward and backward RNN reset masks from UpdateRuleInputs using should_reset_mask_fwd and should_reset_mask_bwd properties', 'shard a pytree of numpy arrays across multiple JAX devices using device_put_sharded', 'gather sharded data from JAX devices and reshape into a single flattened batch array', 'perform a batched index lookup into a lookup table using Haiku BatchApply and vmap', 'prepend a batch dimension to a tree of ArraySpec or specs.Array shapes', 'initialize a MovingAverage tracker, update EMA state, and normalize a pytree of values by mean and variance']
```

Usage

```
{'create_ValueFnConfig': 'create a ValueFnConfig dataclass to configure value function network, learning rate, discount, and EMA settings', 'create_UpdateRuleInputs': 'create an UpdateRuleInputs dataclass to hold observations, actions, rewards, and terminal flags for the update rule', 'convert_ActorTimestep_from_rollout': 'convert an ActorRollout into an ActorTimestep using the from_rollout classmethod', 'convert_ActorTimestep_to_env_timestep': 'convert an ActorTimestep into an EnvironmentTimestep using the to_env_timestep method', 'compute_UpdateRuleInputs_reset_masks': 'compute forward and backward RNN reset masks from UpdateRuleInputs using should_reset_mask_fwd and should_reset_mask_bwd properties'}
```

## File: google-deepmind_discorl/disco_rl/utils.py

Prompts

```
['create an Agent instance using the disco update rule with observation and action specs', 'create an Agent instance using the actor_critic update rule with observation and action specs', 'run a single actor step to sample actions from the agent network for a timestep', 'run a learner training step that computes gradients and updates agent parameters from a rollout', 'get the default Disco-103 configuration settings as a ConfigDict for agent initialization', 'build an optax Adam optimizer where the second moment denominator blocks gradient flow for meta-learning', 'create a GradientTransformation that rescales gradients using Adam with stop_gradient on the second moment estimate', 'test the scale_by_adam_sg_denom function by initializing state and applying gradient updates to model parameters', 'refactor an existing Adam optimizer to add stop_gradient on the second moment for meta-gradient isolation', 'review the scale_by_adam_sg_denom function and its use of jax.lax.stop_gradient on nu_hat for meta-learning stability', 'create a ValueFnConfig dataclass to configure value function network, learning rate, discount, and EMA settings', 'create an UpdateRuleInputs dataclass to hold observations, actions, rewards, and terminal flags for the update rule', 'convert an ActorRollout into an ActorTimestep using the from_rollout classmethod', 'convert an ActorTimestep into an EnvironmentTimestep using the to_env_timestep method', 'compute forward and backward RNN reset masks from UpdateRuleInputs using should_reset_mask_fwd and should_reset_mask_bwd properties', 'shard a pytree of numpy arrays across multiple JAX devices using device_put_sharded', 'gather sharded data from JAX devices and reshape into a single flattened batch array', 'perform a batched index lookup into a lookup table using Haiku BatchApply and vmap', 'prepend a batch dimension to a tree of ArraySpec or specs.Array shapes', 'initialize a MovingAverage tracker, update EMA state, and normalize a pytree of values by mean and variance']
```

Usage

```
{'shard_data_across_devices': 'shard a pytree of numpy arrays across multiple JAX devices using device_put_sharded', 'gather_sharded_data_from_devices': 'gather sharded data from JAX devices and reshape into a single flattened batch array', 'batch_lookup_table_values': 'perform a batched index lookup into a lookup table using Haiku BatchApply and vmap', 'broadcast_array_specs_with_batch_dim': 'prepend a batch dimension to a tree of ArraySpec or specs.Array shapes', 'normalize_values_with_moving_average': 'initialize a MovingAverage tracker, update EMA state, and normalize a pytree of values by mean and variance'}
```


# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/d4pg/builder.py

Prompts

```
['build a D4PG learner with Adam optimizer and optional gradient clipping for policy and critic networks', 'build Reverb replay tables with uniform sampling and configurable rate limiter for D4PG training', 'build a multi-device dataset iterator from Reverb replay client with n-step trajectory postprocessing', 'build a structured adder to record actor-environment transitions into the Reverb replay buffer', 'build a CPU-based GenericActor with variable client for D4PG policy inference and data collection', 'create a TrainingState namedtuple to hold policy, critic, and optimizer parameters for D4PG', 'run an SGD step that computes policy and critic losses and updates network parameters', 'compute the discrete policy gradient loss using DPG loss with critic gradient clipping', 'compute the distributional critic loss using categorical TD learning with target networks', 'build a D4PG agent with policy and critic networks using make_networks and an environment spec', 'create a behavior policy with Gaussian noise exploration using get_default_behavior_policy and a D4PG config', 'create a deterministic evaluation policy without noise using get_default_eval_policy for the D4PG agent', 'review the D4PGNetworks dataclass holding policy_network and critic_network FeedForwardNetwork fields', 'refactor make_networks to customize policy layer sizes, critic layer sizes, or distributional atoms']
```

Usage

```
{'build_d4pg_learner': 'build a D4PG learner with Adam optimizer and optional gradient clipping for policy and critic networks', 'build_replay_tables': 'build Reverb replay tables with uniform sampling and configurable rate limiter for D4PG training', 'build_dataset_iterator': 'build a multi-device dataset iterator from Reverb replay client with n-step trajectory postprocessing', 'build_d4pg_adder': 'build a structured adder to record actor-environment transitions into the Reverb replay buffer', 'build_d4pg_actor': 'build a CPU-based GenericActor with variable client for D4PG policy inference and data collection'}
```

## File: google-deepmind_acme/acme/agents/jax/d4pg/learning.py

Prompts

```
['build a D4PG learner with Adam optimizer and optional gradient clipping for policy and critic networks', 'build Reverb replay tables with uniform sampling and configurable rate limiter for D4PG training', 'build a multi-device dataset iterator from Reverb replay client with n-step trajectory postprocessing', 'build a structured adder to record actor-environment transitions into the Reverb replay buffer', 'build a CPU-based GenericActor with variable client for D4PG policy inference and data collection', 'create a TrainingState namedtuple to hold policy, critic, and optimizer parameters for D4PG', 'run an SGD step that computes policy and critic losses and updates network parameters', 'compute the discrete policy gradient loss using DPG loss with critic gradient clipping', 'compute the distributional critic loss using categorical TD learning with target networks', 'build a D4PG agent with policy and critic networks using make_networks and an environment spec', 'create a behavior policy with Gaussian noise exploration using get_default_behavior_policy and a D4PG config', 'create a deterministic evaluation policy without noise using get_default_eval_policy for the D4PG agent', 'review the D4PGNetworks dataclass holding policy_network and critic_network FeedForwardNetwork fields', 'refactor make_networks to customize policy layer sizes, critic layer sizes, or distributional atoms']
```

Usage

```
{'build_d4pg_learner': 'build a D4PG learner with policy and critic networks for reinforcement learning training', 'create_training_state': 'create a TrainingState namedtuple to hold policy, critic, and optimizer parameters for D4PG', 'run_sgd_step': 'run an SGD step that computes policy and critic losses and updates network parameters', 'compute_policy_loss': 'compute the discrete policy gradient loss using DPG loss with critic gradient clipping', 'compute_critic_loss': 'compute the distributional critic loss using categorical TD learning with target networks'}
```

## File: google-deepmind_acme/acme/agents/jax/d4pg/networks.py

Prompts

```
['build a D4PG learner with Adam optimizer and optional gradient clipping for policy and critic networks', 'build Reverb replay tables with uniform sampling and configurable rate limiter for D4PG training', 'build a multi-device dataset iterator from Reverb replay client with n-step trajectory postprocessing', 'build a structured adder to record actor-environment transitions into the Reverb replay buffer', 'build a CPU-based GenericActor with variable client for D4PG policy inference and data collection', 'create a TrainingState namedtuple to hold policy, critic, and optimizer parameters for D4PG', 'run an SGD step that computes policy and critic losses and updates network parameters', 'compute the discrete policy gradient loss using DPG loss with critic gradient clipping', 'compute the distributional critic loss using categorical TD learning with target networks', 'build a D4PG agent with policy and critic networks using make_networks and an environment spec', 'create a behavior policy with Gaussian noise exploration using get_default_behavior_policy and a D4PG config', 'create a deterministic evaluation policy without noise using get_default_eval_policy for the D4PG agent', 'review the D4PGNetworks dataclass holding policy_network and critic_network FeedForwardNetwork fields', 'refactor make_networks to customize policy layer sizes, critic layer sizes, or distributional atoms']
```

Usage

```
{'build_d4pg_networks': 'build a D4PG agent with policy and critic networks using make_networks and an environment spec', 'create_behavior_policy': 'create a behavior policy with Gaussian noise exploration using get_default_behavior_policy and a D4PG config', 'create_eval_policy': 'create a deterministic evaluation policy without noise using get_default_eval_policy for the D4PG agent', 'review_d4pgnetworks_dataclass': 'review the D4PGNetworks dataclass holding policy_network and critic_network FeedForwardNetwork fields', 'refactor_make_networks': 'refactor make_networks to customize policy layer sizes, critic layer sizes, or distributional atoms'}
```


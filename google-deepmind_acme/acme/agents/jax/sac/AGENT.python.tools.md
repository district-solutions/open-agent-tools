# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/sac/builder.py

Prompts

```
['build a SAC learner with Adam optimizers for policy and Q-network training using SACBuilder.make_learner', 'build a GenericActor with a feed-forward policy and variable client using SACBuilder.make_actor', 'build Reverb replay tables with uniform sampling and FIFO removal using SACBuilder.make_replay_tables', 'build a dataset iterator from a Reverb client for SAC learning using SACBuilder.make_dataset_iterator', 'build an NStepTransitionAdder to record actor environment transitions using SACBuilder.make_adder', 'build a SACConfig dataclass with custom batch size learning rate and discount for SAC agent', 'create a SACConfig with custom replay buffer size and samples per insert ratio settings', 'compute the target entropy from an environment spec using target_entropy_from_env_spec function', 'configure SAC agent entropy coefficient and target entropy via SACConfig for adaptive entropy control', 'review the SACConfig dataclass fields and default values for SAC reinforcement learning agent tuning', 'run a single training step on the SAC learner using sampled replay transitions', 'create a TrainingState namedtuple with policy and Q optimizer states and network parameters', 'save the current SAC learner TrainingState to persist policy and critic parameters', 'restore a previously saved TrainingState to resume SAC learner training from checkpoint', 'create SAC policy and critic networks from an environment spec with configurable hidden layer sizes', 'instantiate a SACNetworks dataclass with policy network, Q network, log probability, and sample functions', 'define default Q network, training actor, and eval actor models to snapshot from a variable source', 'return a feed-forward policy function that applies the policy network and samples actions for training or eval', 'review the SAC actor MLP with NormalTanh distribution and twin critic network architecture']
```

Usage

```
{'build_sac_learner': 'build a SAC learner with Adam optimizers for policy and Q-network training using SACBuilder.make_learner', 'build_sac_actor': 'build a GenericActor with a feed-forward policy and variable client using SACBuilder.make_actor', 'build_replay_tables': 'build Reverb replay tables with uniform sampling and FIFO removal using SACBuilder.make_replay_tables', 'build_dataset_iterator': 'build a dataset iterator from a Reverb client for SAC learning using SACBuilder.make_dataset_iterator', 'build_sac_adder': 'build an NStepTransitionAdder to record actor environment transitions using SACBuilder.make_adder'}
```

## File: google-deepmind_acme/acme/agents/jax/sac/config.py

Prompts

```
['build a SAC learner with Adam optimizers for policy and Q-network training using SACBuilder.make_learner', 'build a GenericActor with a feed-forward policy and variable client using SACBuilder.make_actor', 'build Reverb replay tables with uniform sampling and FIFO removal using SACBuilder.make_replay_tables', 'build a dataset iterator from a Reverb client for SAC learning using SACBuilder.make_dataset_iterator', 'build an NStepTransitionAdder to record actor environment transitions using SACBuilder.make_adder', 'build a SACConfig dataclass with custom batch size learning rate and discount for SAC agent', 'create a SACConfig with custom replay buffer size and samples per insert ratio settings', 'compute the target entropy from an environment spec using target_entropy_from_env_spec function', 'configure SAC agent entropy coefficient and target entropy via SACConfig for adaptive entropy control', 'review the SACConfig dataclass fields and default values for SAC reinforcement learning agent tuning', 'run a single training step on the SAC learner using sampled replay transitions', 'create a TrainingState namedtuple with policy and Q optimizer states and network parameters', 'save the current SAC learner TrainingState to persist policy and critic parameters', 'restore a previously saved TrainingState to resume SAC learner training from checkpoint', 'create SAC policy and critic networks from an environment spec with configurable hidden layer sizes', 'instantiate a SACNetworks dataclass with policy network, Q network, log probability, and sample functions', 'define default Q network, training actor, and eval actor models to snapshot from a variable source', 'return a feed-forward policy function that applies the policy network and samples actions for training or eval', 'review the SAC actor MLP with NormalTanh distribution and twin critic network architecture']
```

Usage

```
{'build_sac_config': 'build a SACConfig dataclass with custom batch size learning rate and discount for SAC agent', 'create_sac_config_replay': 'create a SACConfig with custom replay buffer size and samples per insert ratio settings', 'compute_target_entropy': 'compute the target entropy from an environment spec using target_entropy_from_env_spec function', 'configure_entropy_coefficient': 'configure SAC agent entropy coefficient and target entropy via SACConfig for adaptive entropy control', 'review_sac_config': 'review the SACConfig dataclass fields and default values for SAC reinforcement learning agent tuning'}
```

## File: google-deepmind_acme/acme/agents/jax/sac/learning.py

Prompts

```
['build a SAC learner with Adam optimizers for policy and Q-network training using SACBuilder.make_learner', 'build a GenericActor with a feed-forward policy and variable client using SACBuilder.make_actor', 'build Reverb replay tables with uniform sampling and FIFO removal using SACBuilder.make_replay_tables', 'build a dataset iterator from a Reverb client for SAC learning using SACBuilder.make_dataset_iterator', 'build an NStepTransitionAdder to record actor environment transitions using SACBuilder.make_adder', 'build a SACConfig dataclass with custom batch size learning rate and discount for SAC agent', 'create a SACConfig with custom replay buffer size and samples per insert ratio settings', 'compute the target entropy from an environment spec using target_entropy_from_env_spec function', 'configure SAC agent entropy coefficient and target entropy via SACConfig for adaptive entropy control', 'review the SACConfig dataclass fields and default values for SAC reinforcement learning agent tuning', 'run a single training step on the SAC learner using sampled replay transitions', 'create a TrainingState namedtuple with policy and Q optimizer states and network parameters', 'save the current SAC learner TrainingState to persist policy and critic parameters', 'restore a previously saved TrainingState to resume SAC learner training from checkpoint', 'create SAC policy and critic networks from an environment spec with configurable hidden layer sizes', 'instantiate a SACNetworks dataclass with policy network, Q network, log probability, and sample functions', 'define default Q network, training actor, and eval actor models to snapshot from a variable source', 'return a feed-forward policy function that applies the policy network and samples actions for training or eval', 'review the SAC actor MLP with NormalTanh distribution and twin critic network architecture']
```

Usage

```
{'build_sac_learner': 'build a SAC learner with SACNetworks, optimizers, and a replay buffer iterator for training', 'run_sac_training_step': 'run a single training step on the SAC learner using sampled replay transitions', 'create_training_state': 'create a TrainingState namedtuple with policy and Q optimizer states and network parameters', 'save_sac_learner_state': 'save the current SAC learner TrainingState to persist policy and critic parameters', 'restore_sac_learner_state': 'restore a previously saved TrainingState to resume SAC learner training from checkpoint'}
```

## File: google-deepmind_acme/acme/agents/jax/sac/networks.py

Prompts

```
['build a SAC learner with Adam optimizers for policy and Q-network training using SACBuilder.make_learner', 'build a GenericActor with a feed-forward policy and variable client using SACBuilder.make_actor', 'build Reverb replay tables with uniform sampling and FIFO removal using SACBuilder.make_replay_tables', 'build a dataset iterator from a Reverb client for SAC learning using SACBuilder.make_dataset_iterator', 'build an NStepTransitionAdder to record actor environment transitions using SACBuilder.make_adder', 'build a SACConfig dataclass with custom batch size learning rate and discount for SAC agent', 'create a SACConfig with custom replay buffer size and samples per insert ratio settings', 'compute the target entropy from an environment spec using target_entropy_from_env_spec function', 'configure SAC agent entropy coefficient and target entropy via SACConfig for adaptive entropy control', 'review the SACConfig dataclass fields and default values for SAC reinforcement learning agent tuning', 'run a single training step on the SAC learner using sampled replay transitions', 'create a TrainingState namedtuple with policy and Q optimizer states and network parameters', 'save the current SAC learner TrainingState to persist policy and critic parameters', 'restore a previously saved TrainingState to resume SAC learner training from checkpoint', 'create SAC policy and critic networks from an environment spec with configurable hidden layer sizes', 'instantiate a SACNetworks dataclass with policy network, Q network, log probability, and sample functions', 'define default Q network, training actor, and eval actor models to snapshot from a variable source', 'return a feed-forward policy function that applies the policy network and samples actions for training or eval', 'review the SAC actor MLP with NormalTanh distribution and twin critic network architecture']
```

Usage

```
{'build_sac_networks': 'create SAC policy and critic networks from an environment spec with configurable hidden layer sizes', 'create_sac_networks_dataclass': 'instantiate a SACNetworks dataclass with policy network, Q network, log probability, and sample functions', 'build_models_to_snapshot': 'define default Q network, training actor, and eval actor models to snapshot from a variable source', 'apply_policy_and_sample': 'return a feed-forward policy function that applies the policy network and samples actions for training or eval', 'review_sac_network_architecture': 'review the SAC actor MLP with NormalTanh distribution and twin critic network architecture'}
```


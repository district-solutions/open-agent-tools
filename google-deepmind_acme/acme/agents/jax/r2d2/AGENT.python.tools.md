# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/r2d2/actor.py

Prompts

```
['build an R2D2 ActorCore policy using get_actor_core with networks and epsilon configuration', 'create an R2D2ActorState dataclass instance with rng, epsilon, and recurrent state fields', 'build an epsilon-greedy behavior policy using make_behavior_policy with R2D2 networks and config', 'review the R2D2ActorState frozen dataclass structure for recurrent RL agent state management', 'refactor get_actor_core to customize epsilon selection or action sampling logic for R2D2', 'build an R2D2 learner with networks, dataset iterator, and Adam optimizer for recurrent experience replay', 'build Reverb replay tables with prioritized sampling and FIFO removal for R2D2 experience storage', 'build a multi-device dataset iterator from a Reverb client with zero padding for sequence samples', 'build a structured adder to record actor environment data into Reverb replay with sequence configs', 'build a generic actor with a policy, variable client, and optional adder for R2D2 reinforcement learning', 'run a pmap-parallelized SGD step on replay samples to update online and target network parameters', 'compute the transformed N-step Q-learning loss with importance sampling weights and priority scores', 'update replay buffer priorities asynchronously using a mixture of max and mean TD errors', 'save the TrainingState to disk or restore a checkpoint to resume R2D2 training', 'build default R2D2 networks for Atari games using an environment spec', 'create an UnrollableNetwork type alias for R2D2 agent networks', 'review the make_atari_networks function that builds R2D2 Atari networks from an env spec', 'summarize the R2D2 networks module and its Atari network factory function', 'test the make_atari_networks function with a sample Atari environment spec']
```

Usage

```
{'build_r2d2_actor_core': 'build an R2D2 ActorCore policy using get_actor_core with networks and epsilon configuration', 'create_r2d2_actor_state': 'create an R2D2ActorState dataclass instance with rng, epsilon, and recurrent state fields', 'build_behavior_policy': 'build an epsilon-greedy behavior policy using make_behavior_policy with R2D2 networks and config', 'review_r2d2_actor_state': 'review the R2D2ActorState frozen dataclass structure for recurrent RL agent state management', 'refactor_get_actor_core': 'refactor get_actor_core to customize epsilon selection or action sampling logic for R2D2'}
```

## File: google-deepmind_acme/acme/agents/jax/r2d2/builder.py

Prompts

```
['build an R2D2 ActorCore policy using get_actor_core with networks and epsilon configuration', 'create an R2D2ActorState dataclass instance with rng, epsilon, and recurrent state fields', 'build an epsilon-greedy behavior policy using make_behavior_policy with R2D2 networks and config', 'review the R2D2ActorState frozen dataclass structure for recurrent RL agent state management', 'refactor get_actor_core to customize epsilon selection or action sampling logic for R2D2', 'build an R2D2 learner with networks, dataset iterator, and Adam optimizer for recurrent experience replay', 'build Reverb replay tables with prioritized sampling and FIFO removal for R2D2 experience storage', 'build a multi-device dataset iterator from a Reverb client with zero padding for sequence samples', 'build a structured adder to record actor environment data into Reverb replay with sequence configs', 'build a generic actor with a policy, variable client, and optional adder for R2D2 reinforcement learning', 'run a pmap-parallelized SGD step on replay samples to update online and target network parameters', 'compute the transformed N-step Q-learning loss with importance sampling weights and priority scores', 'update replay buffer priorities asynchronously using a mixture of max and mean TD errors', 'save the TrainingState to disk or restore a checkpoint to resume R2D2 training', 'build default R2D2 networks for Atari games using an environment spec', 'create an UnrollableNetwork type alias for R2D2 agent networks', 'review the make_atari_networks function that builds R2D2 Atari networks from an env spec', 'summarize the R2D2 networks module and its Atari network factory function', 'test the make_atari_networks function with a sample Atari environment spec']
```

Usage

```
{'build_r2d2_learner': 'build an R2D2 learner with networks, dataset iterator, and Adam optimizer for recurrent experience replay', 'build_r2d2_replay_tables': 'build Reverb replay tables with prioritized sampling and FIFO removal for R2D2 experience storage', 'build_r2d2_dataset_iterator': 'build a multi-device dataset iterator from a Reverb client with zero padding for sequence samples', 'build_r2d2_adder': 'build a structured adder to record actor environment data into Reverb replay with sequence configs', 'build_r2d2_actor': 'build a generic actor with a policy, variable client, and optional adder for R2D2 reinforcement learning'}
```

## File: google-deepmind_acme/acme/agents/jax/r2d2/learning.py

Prompts

```
['build an R2D2 ActorCore policy using get_actor_core with networks and epsilon configuration', 'create an R2D2ActorState dataclass instance with rng, epsilon, and recurrent state fields', 'build an epsilon-greedy behavior policy using make_behavior_policy with R2D2 networks and config', 'review the R2D2ActorState frozen dataclass structure for recurrent RL agent state management', 'refactor get_actor_core to customize epsilon selection or action sampling logic for R2D2', 'build an R2D2 learner with networks, dataset iterator, and Adam optimizer for recurrent experience replay', 'build Reverb replay tables with prioritized sampling and FIFO removal for R2D2 experience storage', 'build a multi-device dataset iterator from a Reverb client with zero padding for sequence samples', 'build a structured adder to record actor environment data into Reverb replay with sequence configs', 'build a generic actor with a policy, variable client, and optional adder for R2D2 reinforcement learning', 'run a pmap-parallelized SGD step on replay samples to update online and target network parameters', 'compute the transformed N-step Q-learning loss with importance sampling weights and priority scores', 'update replay buffer priorities asynchronously using a mixture of max and mean TD errors', 'save the TrainingState to disk or restore a checkpoint to resume R2D2 training', 'build default R2D2 networks for Atari games using an environment spec', 'create an UnrollableNetwork type alias for R2D2 agent networks', 'review the make_atari_networks function that builds R2D2 Atari networks from an env spec', 'summarize the R2D2 networks module and its Atari network factory function', 'test the make_atari_networks function with a sample Atari environment spec']
```

Usage

```
{'build_r2d2_learner': 'build an R2D2Learner with networks, optimizer, replay iterator, and hyperparameters for recurrent DQN training', 'run_sgd_step': 'run a pmap-parallelized SGD step on replay samples to update online and target network parameters', 'compute_loss': 'compute the transformed N-step Q-learning loss with importance sampling weights and priority scores', 'update_priorities': 'update replay buffer priorities asynchronously using a mixture of max and mean TD errors', 'save_restore_state': 'save the TrainingState to disk or restore a checkpoint to resume R2D2 training'}
```

## File: google-deepmind_acme/acme/agents/jax/r2d2/networks.py

Prompts

```
['build an R2D2 ActorCore policy using get_actor_core with networks and epsilon configuration', 'create an R2D2ActorState dataclass instance with rng, epsilon, and recurrent state fields', 'build an epsilon-greedy behavior policy using make_behavior_policy with R2D2 networks and config', 'review the R2D2ActorState frozen dataclass structure for recurrent RL agent state management', 'refactor get_actor_core to customize epsilon selection or action sampling logic for R2D2', 'build an R2D2 learner with networks, dataset iterator, and Adam optimizer for recurrent experience replay', 'build Reverb replay tables with prioritized sampling and FIFO removal for R2D2 experience storage', 'build a multi-device dataset iterator from a Reverb client with zero padding for sequence samples', 'build a structured adder to record actor environment data into Reverb replay with sequence configs', 'build a generic actor with a policy, variable client, and optional adder for R2D2 reinforcement learning', 'run a pmap-parallelized SGD step on replay samples to update online and target network parameters', 'compute the transformed N-step Q-learning loss with importance sampling weights and priority scores', 'update replay buffer priorities asynchronously using a mixture of max and mean TD errors', 'save the TrainingState to disk or restore a checkpoint to resume R2D2 training', 'build default R2D2 networks for Atari games using an environment spec', 'create an UnrollableNetwork type alias for R2D2 agent networks', 'review the make_atari_networks function that builds R2D2 Atari networks from an env spec', 'summarize the R2D2 networks module and its Atari network factory function', 'test the make_atari_networks function with a sample Atari environment spec']
```

Usage

```
{'build_atari_networks': 'build default R2D2 networks for Atari games using an environment spec', 'create_r2d2_networks_type': 'create an UnrollableNetwork type alias for R2D2 agent networks', 'review_make_atari_networks': 'review the make_atari_networks function that builds R2D2 Atari networks from an env spec', 'summarize_r2d2_networks': 'summarize the R2D2 networks module and its Atari network factory function', 'test_make_atari_networks': 'test the make_atari_networks function with a sample Atari environment spec'}
```


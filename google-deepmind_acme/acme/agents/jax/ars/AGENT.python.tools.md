# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/ars/builder.py

Prompts

```
['build an ARSBuilder instance with an ARSConfig and environment spec for reinforcement learning', 'create an ARS learner from a network, dataset, and logger using make_learner', 'create a GenericActor with policy normalization and variable client using make_actor', 'build a reverb replay table queue with episode adder signature using make_replay_tables', 'create a trajectory dataset iterator from a reverb client using make_dataset_iterator', 'build an ARSLearner instance with environment spec, networks, config, and replay iterator for evolutionary RL training', 'run a single ARS training step that generates perturbations, reads results, and updates the policy model', 'create a PerturbationKey NamedTuple with training iteration, perturbation ID, and opposite direction flag for tracking evaluations', 'save the current TrainingState or restore a previous TrainingState to checkpoint ARS learner progress', 'get behavior or evaluation parameters from the ARSLearner including policy params and normalizer params', 'build a clipped linear FeedForwardNetwork from an environment spec using make_networks', 'create a policy network tuple with eval params using make_policy_network in eval mode', 'create a policy network tuple with behavior params using make_policy_network in non-eval mode', 'review the make_networks function that creates a clipped linear model for ARS agents', 'summarize the BEHAVIOR_PARAMS_NAME and EVAL_PARAMS_NAME constants used for parameter naming']
```

Usage

```
{'build_ars_builder': 'build an ARSBuilder instance with an ARSConfig and environment spec for reinforcement learning', 'create_learner_make_learner': 'create an ARS learner from a network, dataset, and logger using make_learner', 'create_actor_make_actor': 'create a GenericActor with policy normalization and variable client using make_actor', 'build_replay_tables_make_replay_tables': 'build a reverb replay table queue with episode adder signature using make_replay_tables', 'create_dataset_iterator_make_dataset_iterator': 'create a trajectory dataset iterator from a reverb client using make_dataset_iterator'}
```

## File: google-deepmind_acme/acme/agents/jax/ars/learning.py

Prompts

```
['build an ARSBuilder instance with an ARSConfig and environment spec for reinforcement learning', 'create an ARS learner from a network, dataset, and logger using make_learner', 'create a GenericActor with policy normalization and variable client using make_actor', 'build a reverb replay table queue with episode adder signature using make_replay_tables', 'create a trajectory dataset iterator from a reverb client using make_dataset_iterator', 'build an ARSLearner instance with environment spec, networks, config, and replay iterator for evolutionary RL training', 'run a single ARS training step that generates perturbations, reads results, and updates the policy model', 'create a PerturbationKey NamedTuple with training iteration, perturbation ID, and opposite direction flag for tracking evaluations', 'save the current TrainingState or restore a previous TrainingState to checkpoint ARS learner progress', 'get behavior or evaluation parameters from the ARSLearner including policy params and normalizer params', 'build a clipped linear FeedForwardNetwork from an environment spec using make_networks', 'create a policy network tuple with eval params using make_policy_network in eval mode', 'create a policy network tuple with behavior params using make_policy_network in non-eval mode', 'review the make_networks function that creates a clipped linear model for ARS agents', 'summarize the BEHAVIOR_PARAMS_NAME and EVAL_PARAMS_NAME constants used for parameter naming']
```

Usage

```
{'build_ars_learner': 'build an ARSLearner instance with environment spec, networks, config, and replay iterator for evolutionary RL training', 'run_ars_training_step': 'run a single ARS training step that generates perturbations, reads results, and updates the policy model', 'create_perturbation_key': 'create a PerturbationKey NamedTuple with training iteration, perturbation ID, and opposite direction flag for tracking evaluations', 'save_restore_training_state': 'save the current TrainingState or restore a previous TrainingState to checkpoint ARS learner progress', 'get_ars_variables': 'get behavior or evaluation parameters from the ARSLearner including policy params and normalizer params'}
```

## File: google-deepmind_acme/acme/agents/jax/ars/networks.py

Prompts

```
['build an ARSBuilder instance with an ARSConfig and environment spec for reinforcement learning', 'create an ARS learner from a network, dataset, and logger using make_learner', 'create a GenericActor with policy normalization and variable client using make_actor', 'build a reverb replay table queue with episode adder signature using make_replay_tables', 'create a trajectory dataset iterator from a reverb client using make_dataset_iterator', 'build an ARSLearner instance with environment spec, networks, config, and replay iterator for evolutionary RL training', 'run a single ARS training step that generates perturbations, reads results, and updates the policy model', 'create a PerturbationKey NamedTuple with training iteration, perturbation ID, and opposite direction flag for tracking evaluations', 'save the current TrainingState or restore a previous TrainingState to checkpoint ARS learner progress', 'get behavior or evaluation parameters from the ARSLearner including policy params and normalizer params', 'build a clipped linear FeedForwardNetwork from an environment spec using make_networks', 'create a policy network tuple with eval params using make_policy_network in eval mode', 'create a policy network tuple with behavior params using make_policy_network in non-eval mode', 'review the make_networks function that creates a clipped linear model for ARS agents', 'summarize the BEHAVIOR_PARAMS_NAME and EVAL_PARAMS_NAME constants used for parameter naming']
```

Usage

```
{'build_ars_clipped_linear_network': 'build a clipped linear FeedForwardNetwork from an environment spec using make_networks', 'create_policy_network_for_eval': 'create a policy network tuple with eval params using make_policy_network in eval mode', 'create_policy_network_for_behavior': 'create a policy network tuple with behavior params using make_policy_network in non-eval mode', 'review_make_networks_function': 'review the make_networks function that creates a clipped linear model for ARS agents', 'summarize_ars_network_constants': 'summarize the BEHAVIOR_PARAMS_NAME and EVAL_PARAMS_NAME constants used for parameter naming'}
```


# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/impala/acting.py

Prompts

```
['build an IMPALA ActorCore using get_actor_core with networks and environment spec', 'create an ImpalaActorState dataclass with rng, logits, and recurrent state fields', 'review the select_action function that chooses actions via argmax or categorical sampling', 'summarize the get_extras function that returns logits and previous recurrent core state', 'test the ImpalaPolicy type alias for ActorCore with ImpalaActorState and ImpalaExtras', 'build a Reverb replay table with uniform sampling and FIFO removal for IMPALA training', 'build a multi-device dataset iterator from a Reverb client for IMPALA learner updates', 'build a SequenceAdder to insert environment transitions into the Reverb replay buffer', 'build an IMPALA learner with an Adam optimizer and gradient clipping for training', 'build a GenericActor with a variable client that periodically syncs policy parameters', 'run a single SGD training step on replay samples using the IMPALA learner and log results', 'create a TrainingState namedtuple holding network parameters and optax optimizer state for IMPALA', 'save the IMPALA learner training state including parameters and optimizer state for checkpointing', 'restore an IMPALA learner from a saved TrainingState and replicate across all devices', 'build default IMPALA networks for Atari games using an environment spec', 'create an unrollable IMPALA network from an environment spec with DeepIMPALAAtariNetwork core', 'review the make_atari_networks function that constructs Atari networks from an environment spec', 'summarize the IMPALANetworks type alias pointing to UnrollableNetwork', 'test the make_atari_networks function with a sample Atari environment spec']
```

Usage

```
{'build_impala_actor_core': 'build an IMPALA ActorCore using get_actor_core with networks and environment spec', 'create_impala_actor_state': 'create an ImpalaActorState dataclass with rng, logits, and recurrent state fields', 'review_select_action': 'review the select_action function that chooses actions via argmax or categorical sampling', 'summarize_get_extras': 'summarize the get_extras function that returns logits and previous recurrent core state', 'test_impala_policy': 'test the ImpalaPolicy type alias for ActorCore with ImpalaActorState and ImpalaExtras'}
```

## File: google-deepmind_acme/acme/agents/jax/impala/builder.py

Prompts

```
['build an IMPALA ActorCore using get_actor_core with networks and environment spec', 'create an ImpalaActorState dataclass with rng, logits, and recurrent state fields', 'review the select_action function that chooses actions via argmax or categorical sampling', 'summarize the get_extras function that returns logits and previous recurrent core state', 'test the ImpalaPolicy type alias for ActorCore with ImpalaActorState and ImpalaExtras', 'build a Reverb replay table with uniform sampling and FIFO removal for IMPALA training', 'build a multi-device dataset iterator from a Reverb client for IMPALA learner updates', 'build a SequenceAdder to insert environment transitions into the Reverb replay buffer', 'build an IMPALA learner with an Adam optimizer and gradient clipping for training', 'build a GenericActor with a variable client that periodically syncs policy parameters', 'run a single SGD training step on replay samples using the IMPALA learner and log results', 'create a TrainingState namedtuple holding network parameters and optax optimizer state for IMPALA', 'save the IMPALA learner training state including parameters and optimizer state for checkpointing', 'restore an IMPALA learner from a saved TrainingState and replicate across all devices', 'build default IMPALA networks for Atari games using an environment spec', 'create an unrollable IMPALA network from an environment spec with DeepIMPALAAtariNetwork core', 'review the make_atari_networks function that constructs Atari networks from an environment spec', 'summarize the IMPALANetworks type alias pointing to UnrollableNetwork', 'test the make_atari_networks function with a sample Atari environment spec']
```

Usage

```
{'build_impala_replay_table': 'build a Reverb replay table with uniform sampling and FIFO removal for IMPALA training', 'build_impala_dataset_iterator': 'build a multi-device dataset iterator from a Reverb client for IMPALA learner updates', 'build_impala_adder': 'build a SequenceAdder to insert environment transitions into the Reverb replay buffer', 'build_impala_learner': 'build an IMPALA learner with an Adam optimizer and gradient clipping for training', 'build_impala_actor': 'build a GenericActor with a variable client that periodically syncs policy parameters'}
```

## File: google-deepmind_acme/acme/agents/jax/impala/learning.py

Prompts

```
['build an IMPALA ActorCore using get_actor_core with networks and environment spec', 'create an ImpalaActorState dataclass with rng, logits, and recurrent state fields', 'review the select_action function that chooses actions via argmax or categorical sampling', 'summarize the get_extras function that returns logits and previous recurrent core state', 'test the ImpalaPolicy type alias for ActorCore with ImpalaActorState and ImpalaExtras', 'build a Reverb replay table with uniform sampling and FIFO removal for IMPALA training', 'build a multi-device dataset iterator from a Reverb client for IMPALA learner updates', 'build a SequenceAdder to insert environment transitions into the Reverb replay buffer', 'build an IMPALA learner with an Adam optimizer and gradient clipping for training', 'build a GenericActor with a variable client that periodically syncs policy parameters', 'run a single SGD training step on replay samples using the IMPALA learner and log results', 'create a TrainingState namedtuple holding network parameters and optax optimizer state for IMPALA', 'save the IMPALA learner training state including parameters and optimizer state for checkpointing', 'restore an IMPALA learner from a saved TrainingState and replicate across all devices', 'build default IMPALA networks for Atari games using an environment spec', 'create an unrollable IMPALA network from an environment spec with DeepIMPALAAtariNetwork core', 'review the make_atari_networks function that constructs Atari networks from an environment spec', 'summarize the IMPALANetworks type alias pointing to UnrollableNetwork', 'test the make_atari_networks function with a sample Atari environment spec']
```

Usage

```
{'build_impala_learner': 'build an IMPALA actor-critic learner with networks, replay iterator, and optax optimizer for multi-device training', 'run_sgd_step': 'run a single SGD training step on replay samples using the IMPALA learner and log results', 'create_training_state': 'create a TrainingState namedtuple holding network parameters and optax optimizer state for IMPALA', 'save_learner_state': 'save the IMPALA learner training state including parameters and optimizer state for checkpointing', 'restore_learner_state': 'restore an IMPALA learner from a saved TrainingState and replicate across all devices'}
```

## File: google-deepmind_acme/acme/agents/jax/impala/networks.py

Prompts

```
['build an IMPALA ActorCore using get_actor_core with networks and environment spec', 'create an ImpalaActorState dataclass with rng, logits, and recurrent state fields', 'review the select_action function that chooses actions via argmax or categorical sampling', 'summarize the get_extras function that returns logits and previous recurrent core state', 'test the ImpalaPolicy type alias for ActorCore with ImpalaActorState and ImpalaExtras', 'build a Reverb replay table with uniform sampling and FIFO removal for IMPALA training', 'build a multi-device dataset iterator from a Reverb client for IMPALA learner updates', 'build a SequenceAdder to insert environment transitions into the Reverb replay buffer', 'build an IMPALA learner with an Adam optimizer and gradient clipping for training', 'build a GenericActor with a variable client that periodically syncs policy parameters', 'run a single SGD training step on replay samples using the IMPALA learner and log results', 'create a TrainingState namedtuple holding network parameters and optax optimizer state for IMPALA', 'save the IMPALA learner training state including parameters and optimizer state for checkpointing', 'restore an IMPALA learner from a saved TrainingState and replicate across all devices', 'build default IMPALA networks for Atari games using an environment spec', 'create an unrollable IMPALA network from an environment spec with DeepIMPALAAtariNetwork core', 'review the make_atari_networks function that constructs Atari networks from an environment spec', 'summarize the IMPALANetworks type alias pointing to UnrollableNetwork', 'test the make_atari_networks function with a sample Atari environment spec']
```

Usage

```
{'build_atari_networks': 'build default IMPALA networks for Atari games using an environment spec', 'create_impala_network': 'create an unrollable IMPALA network from an environment spec with DeepIMPALAAtariNetwork core', 'review_make_atari_networks': 'review the make_atari_networks function that constructs Atari networks from an environment spec', 'summarize_impala_networks_type': 'summarize the IMPALANetworks type alias pointing to UnrollableNetwork', 'test_make_atari_networks': 'test the make_atari_networks function with a sample Atari environment spec'}
```


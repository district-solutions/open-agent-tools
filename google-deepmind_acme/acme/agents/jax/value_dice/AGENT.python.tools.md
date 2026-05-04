# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/value_dice/builder.py

Prompts

```
['build a ValueDiceLearner with Adam optimizers for policy and nu networks using the make_learner method', 'create Reverb replay tables with uniform sampling and FIFO removal using make_replay_tables', 'build a device-placed dataset iterator from a Reverb client for learning using make_dataset_iterator', 'create an NStepTransitionAdder for inserting transitions into the replay buffer using make_adder', 'build a CPU-based GenericActor with a feed-forward policy and variable client using make_actor', 'run a single SGD training step on the ValueDiceLearner using replay and demonstration transitions', 'compute the orthogonal regularization loss for network parameters to prevent weight correlation', 'save the current TrainingState or restore a previous TrainingState for the ValueDiceLearner', 'get the policy or nu network parameters from the ValueDiceLearner by name', 'build a python module to create ValueDice policy and nu networks from an environment spec using make_networks', 'create a python module that instantiates a ValueDiceNetworks dataclass with policy and nu feed-forward networks', 'apply a ValueDice policy network and sample actions from it using apply_policy_and_sample', 'review the ValueDiceNetworks dataclass to understand its policy network, nu network, and sample function fields', 'summarize the make_networks function which builds MLP-based policy and nu networks with NormalTanhDistribution']
```

Usage

```
{'build_valuedice_learner': 'build a ValueDiceLearner with Adam optimizers for policy and nu networks using the make_learner method', 'create_replay_tables': 'create Reverb replay tables with uniform sampling and FIFO removal using make_replay_tables', 'build_dataset_iterator': 'build a device-placed dataset iterator from a Reverb client for learning using make_dataset_iterator', 'create_transition_adder': 'create an NStepTransitionAdder for inserting transitions into the replay buffer using make_adder', 'build_generic_actor': 'build a CPU-based GenericActor with a feed-forward policy and variable client using make_actor'}
```

## File: google-deepmind_acme/acme/agents/jax/value_dice/learning.py

Prompts

```
['build a ValueDiceLearner with Adam optimizers for policy and nu networks using the make_learner method', 'create Reverb replay tables with uniform sampling and FIFO removal using make_replay_tables', 'build a device-placed dataset iterator from a Reverb client for learning using make_dataset_iterator', 'create an NStepTransitionAdder for inserting transitions into the replay buffer using make_adder', 'build a CPU-based GenericActor with a feed-forward policy and variable client using make_actor', 'run a single SGD training step on the ValueDiceLearner using replay and demonstration transitions', 'compute the orthogonal regularization loss for network parameters to prevent weight correlation', 'save the current TrainingState or restore a previous TrainingState for the ValueDiceLearner', 'get the policy or nu network parameters from the ValueDiceLearner by name', 'build a python module to create ValueDice policy and nu networks from an environment spec using make_networks', 'create a python module that instantiates a ValueDiceNetworks dataclass with policy and nu feed-forward networks', 'apply a ValueDice policy network and sample actions from it using apply_policy_and_sample', 'review the ValueDiceNetworks dataclass to understand its policy network, nu network, and sample function fields', 'summarize the make_networks function which builds MLP-based policy and nu networks with NormalTanhDistribution']
```

Usage

```
{'build_valuedice_learner': 'build a ValueDiceLearner with policy and nu networks, optimizers, replay buffer, and demonstration iterators', 'run_training_step': 'run a single SGD training step on the ValueDiceLearner using replay and demonstration transitions', 'compute_orthogonal_regularization_loss': 'compute the orthogonal regularization loss for network parameters to prevent weight correlation', 'save_restore_training_state': 'save the current TrainingState or restore a previous TrainingState for the ValueDiceLearner', 'get_learner_variables': 'get the policy or nu network parameters from the ValueDiceLearner by name'}
```

## File: google-deepmind_acme/acme/agents/jax/value_dice/networks.py

Prompts

```
['build a ValueDiceLearner with Adam optimizers for policy and nu networks using the make_learner method', 'create Reverb replay tables with uniform sampling and FIFO removal using make_replay_tables', 'build a device-placed dataset iterator from a Reverb client for learning using make_dataset_iterator', 'create an NStepTransitionAdder for inserting transitions into the replay buffer using make_adder', 'build a CPU-based GenericActor with a feed-forward policy and variable client using make_actor', 'run a single SGD training step on the ValueDiceLearner using replay and demonstration transitions', 'compute the orthogonal regularization loss for network parameters to prevent weight correlation', 'save the current TrainingState or restore a previous TrainingState for the ValueDiceLearner', 'get the policy or nu network parameters from the ValueDiceLearner by name', 'build a python module to create ValueDice policy and nu networks from an environment spec using make_networks', 'create a python module that instantiates a ValueDiceNetworks dataclass with policy and nu feed-forward networks', 'apply a ValueDice policy network and sample actions from it using apply_policy_and_sample', 'review the ValueDiceNetworks dataclass to understand its policy network, nu network, and sample function fields', 'summarize the make_networks function which builds MLP-based policy and nu networks with NormalTanhDistribution']
```

Usage

```
{'build_valuedice_networks': 'build a python module to create ValueDice policy and nu networks from an environment spec using make_networks', 'create_valuedicenetworks_dataclass': 'create a python module that instantiates a ValueDiceNetworks dataclass with policy and nu feed-forward networks', 'apply_policy_and_sample_actions': 'apply a ValueDice policy network and sample actions from it using apply_policy_and_sample', 'review_valuedicenetworks_dataclass': 'review the ValueDiceNetworks dataclass to understand its policy network, nu network, and sample function fields', 'summarize_make_networks': 'summarize the make_networks function which builds MLP-based policy and nu networks with NormalTanhDistribution'}
```


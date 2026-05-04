# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/cql/agent_test.py

Prompts

```
['test the CQLLearner by creating networks and stepping the learner for multiple iterations', 'create a CQLLearner with adam optimizers, a fixed CQL coefficient, and demonstration data', 'build CQL networks using make_networks with an environment spec and hidden layer sizes', 'run a CQL training loop by calling learner.step repeatedly for a set number of iterations', 'review the CQLTest class that tests training a CQL agent with a fake continuous environment', 'build a CQL learner with Adam optimizers for policy and critic networks using configurable hyperparameters', 'create a GenericActor with a feed-forward policy and variable client for CPU-based actor execution', "construct an evaluation policy that samples actions from the CQL network's policy distribution", 'review the CQLBuilder class to understand how it constructs learners, actors, and policies for offline RL', 'refactor the CQLBuilder to support additional optimizer types beyond optax.adam for policy and critic', 'run a single training step of the CQLLearner on a batch of transitions', 'create a TrainingState namedtuple holding policy and critic optimizer states and parameters', 'save the current CQLLearner TrainingState for later checkpointing and restoration', 'restore a CQLLearner from a previously saved TrainingState checkpoint', 'apply the policy network and sample N actions with their log probabilities', 'create a CQLNetworks dataclass instance with policy, critic, and sampling functions', 'review the CQLNetworks dataclass fields including policy_network, critic_network, log_prob, sample, and sample_eval', 'summarize how make_networks wraps SAC networks into a CQLNetworks dataclass for the CQL agent']
```

Usage

```
{'test_CQLLearner_train': 'test the CQLLearner by creating networks and stepping the learner for multiple iterations', 'create_CQLLearner': 'create a CQLLearner with adam optimizers, a fixed CQL coefficient, and demonstration data', 'build_cql_networks': 'build CQL networks using make_networks with an environment spec and hidden layer sizes', 'run_cql_training_loop': 'run a CQL training loop by calling learner.step repeatedly for a set number of iterations', 'review_CQLTest': 'review the CQLTest class that tests training a CQL agent with a fake continuous environment'}
```

## File: google-deepmind_acme/acme/agents/jax/cql/builder.py

Prompts

```
['test the CQLLearner by creating networks and stepping the learner for multiple iterations', 'create a CQLLearner with adam optimizers, a fixed CQL coefficient, and demonstration data', 'build CQL networks using make_networks with an environment spec and hidden layer sizes', 'run a CQL training loop by calling learner.step repeatedly for a set number of iterations', 'review the CQLTest class that tests training a CQL agent with a fake continuous environment', 'build a CQL learner with Adam optimizers for policy and critic networks using configurable hyperparameters', 'create a GenericActor with a feed-forward policy and variable client for CPU-based actor execution', "construct an evaluation policy that samples actions from the CQL network's policy distribution", 'review the CQLBuilder class to understand how it constructs learners, actors, and policies for offline RL', 'refactor the CQLBuilder to support additional optimizer types beyond optax.adam for policy and critic', 'run a single training step of the CQLLearner on a batch of transitions', 'create a TrainingState namedtuple holding policy and critic optimizer states and parameters', 'save the current CQLLearner TrainingState for later checkpointing and restoration', 'restore a CQLLearner from a previously saved TrainingState checkpoint', 'apply the policy network and sample N actions with their log probabilities', 'create a CQLNetworks dataclass instance with policy, critic, and sampling functions', 'review the CQLNetworks dataclass fields including policy_network, critic_network, log_prob, sample, and sample_eval', 'summarize how make_networks wraps SAC networks into a CQLNetworks dataclass for the CQL agent']
```

Usage

```
{'build_cql_learner': 'build a CQL learner with Adam optimizers for policy and critic networks using configurable hyperparameters', 'create_cql_actor': 'create a GenericActor with a feed-forward policy and variable client for CPU-based actor execution', 'construct_cql_policy': "construct an evaluation policy that samples actions from the CQL network's policy distribution", 'review_cqlbuilder_class': 'review the CQLBuilder class to understand how it constructs learners, actors, and policies for offline RL', 'refactor_cql_config': 'refactor the CQLBuilder to support additional optimizer types beyond optax.adam for policy and critic'}
```

## File: google-deepmind_acme/acme/agents/jax/cql/learning.py

Prompts

```
['test the CQLLearner by creating networks and stepping the learner for multiple iterations', 'create a CQLLearner with adam optimizers, a fixed CQL coefficient, and demonstration data', 'build CQL networks using make_networks with an environment spec and hidden layer sizes', 'run a CQL training loop by calling learner.step repeatedly for a set number of iterations', 'review the CQLTest class that tests training a CQL agent with a fake continuous environment', 'build a CQL learner with Adam optimizers for policy and critic networks using configurable hyperparameters', 'create a GenericActor with a feed-forward policy and variable client for CPU-based actor execution', "construct an evaluation policy that samples actions from the CQL network's policy distribution", 'review the CQLBuilder class to understand how it constructs learners, actors, and policies for offline RL', 'refactor the CQLBuilder to support additional optimizer types beyond optax.adam for policy and critic', 'run a single training step of the CQLLearner on a batch of transitions', 'create a TrainingState namedtuple holding policy and critic optimizer states and parameters', 'save the current CQLLearner TrainingState for later checkpointing and restoration', 'restore a CQLLearner from a previously saved TrainingState checkpoint', 'apply the policy network and sample N actions with their log probabilities', 'create a CQLNetworks dataclass instance with policy, critic, and sampling functions', 'review the CQLNetworks dataclass fields including policy_network, critic_network, log_prob, sample, and sample_eval', 'summarize how make_networks wraps SAC networks into a CQLNetworks dataclass for the CQL agent']
```

Usage

```
{'build_cql_learner': 'build a CQLLearner with JAX networks and optax optimizers for conservative Q-learning', 'run_cql_training_step': 'run a single training step of the CQLLearner on a batch of transitions', 'create_training_state': 'create a TrainingState namedtuple holding policy and critic optimizer states and parameters', 'save_cql_learner_state': 'save the current CQLLearner TrainingState for later checkpointing and restoration', 'restore_cql_learner_state': 'restore a CQLLearner from a previously saved TrainingState checkpoint'}
```

## File: google-deepmind_acme/acme/agents/jax/cql/networks.py

Prompts

```
['test the CQLLearner by creating networks and stepping the learner for multiple iterations', 'create a CQLLearner with adam optimizers, a fixed CQL coefficient, and demonstration data', 'build CQL networks using make_networks with an environment spec and hidden layer sizes', 'run a CQL training loop by calling learner.step repeatedly for a set number of iterations', 'review the CQLTest class that tests training a CQL agent with a fake continuous environment', 'build a CQL learner with Adam optimizers for policy and critic networks using configurable hyperparameters', 'create a GenericActor with a feed-forward policy and variable client for CPU-based actor execution', "construct an evaluation policy that samples actions from the CQL network's policy distribution", 'review the CQLBuilder class to understand how it constructs learners, actors, and policies for offline RL', 'refactor the CQLBuilder to support additional optimizer types beyond optax.adam for policy and critic', 'run a single training step of the CQLLearner on a batch of transitions', 'create a TrainingState namedtuple holding policy and critic optimizer states and parameters', 'save the current CQLLearner TrainingState for later checkpointing and restoration', 'restore a CQLLearner from a previously saved TrainingState checkpoint', 'apply the policy network and sample N actions with their log probabilities', 'create a CQLNetworks dataclass instance with policy, critic, and sampling functions', 'review the CQLNetworks dataclass fields including policy_network, critic_network, log_prob, sample, and sample_eval', 'summarize how make_networks wraps SAC networks into a CQLNetworks dataclass for the CQL agent']
```

Usage

```
{'build_cql_networks': 'build a CQL agent network by calling make_networks with an environment spec', 'apply_and_sample_actions': 'apply the policy network and sample N actions with their log probabilities', 'create_cql_networks_dataclass': 'create a CQLNetworks dataclass instance with policy, critic, and sampling functions', 'review_cql_networks_dataclass': 'review the CQLNetworks dataclass fields including policy_network, critic_network, log_prob, sample, and sample_eval', 'summarize_make_networks': 'summarize how make_networks wraps SAC networks into a CQLNetworks dataclass for the CQL agent'}
```


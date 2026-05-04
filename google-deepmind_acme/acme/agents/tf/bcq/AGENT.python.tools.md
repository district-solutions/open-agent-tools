# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/bcq/discrete_learning.py

Prompts

```
['build a DiscreteBCQLearner combining BC and Q-learning for discrete action reinforcement learning', 'create an _InternalBCQLearner with a DiscreteFilteredQNetwork, discount, learning rate, and dataset', 'run a training step on the DiscreteBCQLearner that updates both BC and BCQ networks', 'get the trainable variables from the BCQ learner by name for inspection or debugging', 'checkpoint the learner state including network, target network, optimizer, and step count', 'test the DiscreteBCQLearner by running a full learner step and verifying bc_steps and bcq_steps counts', 'build a DiscreteFilteredQNetwork with g_network, q_network, and threshold for discrete action BCQ learning', 'create a fake DiscreteEnvironment with configurable num_actions, num_observations, and episode_length for testing', 'make an MLP network using Sonnet with Flatten and MLP layers for discrete action prediction']
```

Usage

```
{'build_discrete_bcq_learner': 'build a DiscreteBCQLearner combining BC and Q-learning for discrete action reinforcement learning', 'create_internal_bcq_learner': 'create an _InternalBCQLearner with a DiscreteFilteredQNetwork, discount, learning rate, and dataset', 'run_learner_step': 'run a training step on the DiscreteBCQLearner that updates both BC and BCQ networks', 'get_learner_variables': 'get the trainable variables from the BCQ learner by name for inspection or debugging', 'checkpoint_learner_state': 'checkpoint the learner state including network, target network, optimizer, and step count'}
```

## File: google-deepmind_acme/acme/agents/tf/bcq/discrete_learning_test.py

Prompts

```
['build a DiscreteBCQLearner combining BC and Q-learning for discrete action reinforcement learning', 'create an _InternalBCQLearner with a DiscreteFilteredQNetwork, discount, learning rate, and dataset', 'run a training step on the DiscreteBCQLearner that updates both BC and BCQ networks', 'get the trainable variables from the BCQ learner by name for inspection or debugging', 'checkpoint the learner state including network, target network, optimizer, and step count', 'test the DiscreteBCQLearner by running a full learner step and verifying bc_steps and bcq_steps counts', 'build a DiscreteFilteredQNetwork with g_network, q_network, and threshold for discrete action BCQ learning', 'create a fake DiscreteEnvironment with configurable num_actions, num_observations, and episode_length for testing', 'make an MLP network using Sonnet with Flatten and MLP layers for discrete action prediction']
```

Usage

```
{'test_discrete_bcq_learner': 'test the DiscreteBCQLearner by running a full learner step and verifying bc_steps and bcq_steps counts', 'build_discrete_filtered_q_network': 'build a DiscreteFilteredQNetwork with g_network, q_network, and threshold for discrete action BCQ learning', 'create_fake_discrete_environment': 'create a fake DiscreteEnvironment with configurable num_actions, num_observations, and episode_length for testing', 'run_learner_step': 'run a single learning step on the DiscreteBCQLearner and check the bc_num_steps and bcq_num_steps state', 'make_mlp_network': 'make an MLP network using Sonnet with Flatten and MLP layers for discrete action prediction'}
```


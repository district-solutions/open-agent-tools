# Agent Python Tools

- repo: google-deepmind/dqnzoo
- repo_uri: https://github.com/google-deepmind/dqn_zoo

## File: google-deepmind_dqnzoo/dqn_zoo/double_q/agent.py

Prompts

```
['build a DoubleDQN agent with a network, optimizer, replay buffer, and epsilon-greedy exploration policy', 'create a step call that selects an epsilon-greedy action and optionally learns from replay transitions', 'test the DoubleDQN agent learning update by sampling replay transitions and applying gradient descent', 'review the DoubleDQN loss function that computes TD errors using double Q-learning with gradient clipping', 'summarize the get_state and set_state methods for serializing and restoring the DoubleDQN agent state', 'run the Double DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'run the Double DQN Atari training with a custom environment name via the environment_name flag', 'run the Double DQN Atari training with a custom random seed for reproducibility', 'run the Double DQN Atari training and log results to a custom CSV file path', 'run the Double DQN Atari training with a custom number of training iterations', 'run the Double DQN Atari test suite using absltest.main with JAX rank promotion enabled', 'test the Double DQN agent on the Pong environment with configurable replay capacity and training frames', 'review the RunAtariTest class that validates Double DQN agent execution with minimal training iterations', 'refactor the test_can_run_agent method to adjust FLAGS like batch size, learn period, or eval frames', 'summarize the Double DQN test module that runs a short Atari agent evaluation using absl flags']
```

Usage

```
{'build_doubledqn_agent': 'build a DoubleDQN agent with a network, optimizer, replay buffer, and epsilon-greedy exploration policy', 'create_step_action': 'create a step call that selects an epsilon-greedy action and optionally learns from replay transitions', 'test_learn_update': 'test the DoubleDQN agent learning update by sampling replay transitions and applying gradient descent', 'review_double_q_loss': 'review the DoubleDQN loss function that computes TD errors using double Q-learning with gradient clipping', 'summarize_get_set_state': 'summarize the get_state and set_state methods for serializing and restoring the DoubleDQN agent state'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/double_q/run_atari.py

Prompts

```
['build a DoubleDQN agent with a network, optimizer, replay buffer, and epsilon-greedy exploration policy', 'create a step call that selects an epsilon-greedy action and optionally learns from replay transitions', 'test the DoubleDQN agent learning update by sampling replay transitions and applying gradient descent', 'review the DoubleDQN loss function that computes TD errors using double Q-learning with gradient clipping', 'summarize the get_state and set_state methods for serializing and restoring the DoubleDQN agent state', 'run the Double DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'run the Double DQN Atari training with a custom environment name via the environment_name flag', 'run the Double DQN Atari training with a custom random seed for reproducibility', 'run the Double DQN Atari training and log results to a custom CSV file path', 'run the Double DQN Atari training with a custom number of training iterations', 'run the Double DQN Atari test suite using absltest.main with JAX rank promotion enabled', 'test the Double DQN agent on the Pong environment with configurable replay capacity and training frames', 'review the RunAtariTest class that validates Double DQN agent execution with minimal training iterations', 'refactor the test_can_run_agent method to adjust FLAGS like batch size, learn period, or eval frames', 'summarize the Double DQN test module that runs a short Atari agent evaluation using absl flags']
```

Usage

```
{'run_double_dqn_atari_training': 'run the Double DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'run_atari_training_with_custom_env': 'run the Double DQN Atari training with a custom environment name via the environment_name flag', 'run_atari_training_with_custom_seed': 'run the Double DQN Atari training with a custom random seed for reproducibility', 'run_atari_training_with_results_csv': 'run the Double DQN Atari training and log results to a custom CSV file path', 'run_atari_training_with_custom_iterations': 'run the Double DQN Atari training with a custom number of training iterations'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/double_q/run_atari_test.py

Prompts

```
['build a DoubleDQN agent with a network, optimizer, replay buffer, and epsilon-greedy exploration policy', 'create a step call that selects an epsilon-greedy action and optionally learns from replay transitions', 'test the DoubleDQN agent learning update by sampling replay transitions and applying gradient descent', 'review the DoubleDQN loss function that computes TD errors using double Q-learning with gradient clipping', 'summarize the get_state and set_state methods for serializing and restoring the DoubleDQN agent state', 'run the Double DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'run the Double DQN Atari training with a custom environment name via the environment_name flag', 'run the Double DQN Atari training with a custom random seed for reproducibility', 'run the Double DQN Atari training and log results to a custom CSV file path', 'run the Double DQN Atari training with a custom number of training iterations', 'run the Double DQN Atari test suite using absltest.main with JAX rank promotion enabled', 'test the Double DQN agent on the Pong environment with configurable replay capacity and training frames', 'review the RunAtariTest class that validates Double DQN agent execution with minimal training iterations', 'refactor the test_can_run_agent method to adjust FLAGS like batch size, learn period, or eval frames', 'summarize the Double DQN test module that runs a short Atari agent evaluation using absl flags']
```

Usage

```
{'run_double_dqn_atari_test': 'run the Double DQN Atari test suite using absltest.main with JAX rank promotion enabled', 'test_run_atari_agent': 'test the Double DQN agent on the Pong environment with configurable replay capacity and training frames', 'review_RunAtariTest_class': 'review the RunAtariTest class that validates Double DQN agent execution with minimal training iterations', 'refactor_test_can_run_agent': 'refactor the test_can_run_agent method to adjust FLAGS like batch size, learn period, or eval frames', 'summarize_double_dqn_test': 'summarize the Double DQN test module that runs a short Atari agent evaluation using absl flags'}
```


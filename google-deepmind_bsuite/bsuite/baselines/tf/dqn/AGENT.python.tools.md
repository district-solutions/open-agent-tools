# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/tf/dqn/agent.py

Prompts

```
['build a DQN agent with a Sonnet network, Adam optimizer, and epsilon-greedy policy for reinforcement learning', 'create a default DQN agent using default_agent with an MLP network and standard hyperparameters', 'run the DQN agent select_action method to get an epsilon-greedy action from a timestep observation', 'test the DQN agent update method to add transitions to replay and perform SGD training steps', 'review the DQN _training_step method that computes Q-learning loss and updates the online network via gradient descent', 'run a DQN agent on a bsuite environment and log results to CSV', 'run a DQN agent across a sweep of bsuite experiments using MPI parallelism', 'build an MLP network with configurable hidden layers for the DQN agent', 'review the DQN agent configuration including replay buffer size and learning rate', 'summarize the absl flags controlling DQN hyperparameters like epsilon and discount', 'test the DQN agent training across bsuite environments using parameterized test cases', 'run a DQN agent experiment against a bsuite environment for a fixed number of episodes', 'create a default DQN agent using observation and action specs from a bsuite environment', 'load a bsuite environment by its ID string for agent training and evaluation', 'review the RunTest class that parameterizes DQN agent tests across bsuite sweep environments']
```

Usage

```
{'build_dqn_agent': 'build a DQN agent with a Sonnet network, Adam optimizer, and epsilon-greedy policy for reinforcement learning', 'create_default_dqn_agent': 'create a default DQN agent using default_agent with an MLP network and standard hyperparameters', 'run_select_action': 'run the DQN agent select_action method to get an epsilon-greedy action from a timestep observation', 'test_dqn_update': 'test the DQN agent update method to add transitions to replay and perform SGD training steps', 'review_training_step': 'review the DQN _training_step method that computes Q-learning loss and updates the online network via gradient descent'}
```

## File: google-deepmind_bsuite/bsuite/baselines/tf/dqn/run.py

Prompts

```
['build a DQN agent with a Sonnet network, Adam optimizer, and epsilon-greedy policy for reinforcement learning', 'create a default DQN agent using default_agent with an MLP network and standard hyperparameters', 'run the DQN agent select_action method to get an epsilon-greedy action from a timestep observation', 'test the DQN agent update method to add transitions to replay and perform SGD training steps', 'review the DQN _training_step method that computes Q-learning loss and updates the online network via gradient descent', 'run a DQN agent on a bsuite environment and log results to CSV', 'run a DQN agent across a sweep of bsuite experiments using MPI parallelism', 'build an MLP network with configurable hidden layers for the DQN agent', 'review the DQN agent configuration including replay buffer size and learning rate', 'summarize the absl flags controlling DQN hyperparameters like epsilon and discount', 'test the DQN agent training across bsuite environments using parameterized test cases', 'run a DQN agent experiment against a bsuite environment for a fixed number of episodes', 'create a default DQN agent using observation and action specs from a bsuite environment', 'load a bsuite environment by its ID string for agent training and evaluation', 'review the RunTest class that parameterizes DQN agent tests across bsuite sweep environments']
```

Usage

```
{'run_dqn_on_bsuite_env': 'run a DQN agent on a bsuite environment and log results to CSV', 'run_dqn_sweep': 'run a DQN agent across a sweep of bsuite experiments using MPI parallelism', 'build_dqn_network': 'build an MLP network with configurable hidden layers for the DQN agent', 'review_dqn_agent_config': 'review the DQN agent configuration including replay buffer size and learning rate', 'summarize_dqn_run_flags': 'summarize the absl flags controlling DQN hyperparameters like epsilon and discount'}
```

## File: google-deepmind_bsuite/bsuite/baselines/tf/dqn/run_test.py

Prompts

```
['build a DQN agent with a Sonnet network, Adam optimizer, and epsilon-greedy policy for reinforcement learning', 'create a default DQN agent using default_agent with an MLP network and standard hyperparameters', 'run the DQN agent select_action method to get an epsilon-greedy action from a timestep observation', 'test the DQN agent update method to add transitions to replay and perform SGD training steps', 'review the DQN _training_step method that computes Q-learning loss and updates the online network via gradient descent', 'run a DQN agent on a bsuite environment and log results to CSV', 'run a DQN agent across a sweep of bsuite experiments using MPI parallelism', 'build an MLP network with configurable hidden layers for the DQN agent', 'review the DQN agent configuration including replay buffer size and learning rate', 'summarize the absl flags controlling DQN hyperparameters like epsilon and discount', 'test the DQN agent training across bsuite environments using parameterized test cases', 'run a DQN agent experiment against a bsuite environment for a fixed number of episodes', 'create a default DQN agent using observation and action specs from a bsuite environment', 'load a bsuite environment by its ID string for agent training and evaluation', 'review the RunTest class that parameterizes DQN agent tests across bsuite sweep environments']
```

Usage

```
{'test_dqn_agent_training': 'test the DQN agent training across bsuite environments using parameterized test cases', 'run_dqn_experiment': 'run a DQN agent experiment against a bsuite environment for a fixed number of episodes', 'create_dqn_default_agent': 'create a default DQN agent using observation and action specs from a bsuite environment', 'load_bsuite_environment': 'load a bsuite environment by its ID string for agent training and evaluation', 'review_runtest_class': 'review the RunTest class that parameterizes DQN agent tests across bsuite sweep environments'}
```


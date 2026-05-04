# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/jax/dqn/agent.py

Prompts

```
['build a JAX-based DQN agent with custom network, optimizer, and replay buffer hyperparameters', 'create a default DQN agent with an MLP network and Adam optimizer using default_agent', 'run epsilon-greedy action selection on a dm_env timestep using the DQN agent', 'test the DQN agent update method that adds transitions to replay and performs SGD steps', 'review the TrainingState namedtuple holding params, target_params, optimizer state, and step count', 'run a DQN agent on a given bsuite environment and log results to CSV', 'run a single bsuite experiment with a specific bsuite_id using the DQN baseline', 'run a multiprocess sweep of DQN experiments across multiple bsuite environments', 'review the run function that loads a bsuite environment and executes a DQN agent', 'review the main entry point that parses flags and dispatches single or sweep runs', 'test the DQN agent training by running parameterized test cases across bsuite environments', 'run an experiment using a DQN agent with a bsuite environment for 5 episodes', 'create a default DQN agent using observation and action specs from a bsuite environment', 'load a bsuite environment from its ID string for agent training tests', 'review the RunTest class that parameterizes DQN agent training tests across bsuite environments']
```

Usage

```
{'build_dqn_agent': 'build a JAX-based DQN agent with custom network, optimizer, and replay buffer hyperparameters', 'create_default_dqn_agent': 'create a default DQN agent with an MLP network and Adam optimizer using default_agent', 'run_select_action': 'run epsilon-greedy action selection on a dm_env timestep using the DQN agent', 'test_dqn_update': 'test the DQN agent update method that adds transitions to replay and performs SGD steps', 'review_training_state': 'review the TrainingState namedtuple holding params, target_params, optimizer state, and step count'}
```

## File: google-deepmind_bsuite/bsuite/baselines/jax/dqn/run.py

Prompts

```
['build a JAX-based DQN agent with custom network, optimizer, and replay buffer hyperparameters', 'create a default DQN agent with an MLP network and Adam optimizer using default_agent', 'run epsilon-greedy action selection on a dm_env timestep using the DQN agent', 'test the DQN agent update method that adds transitions to replay and performs SGD steps', 'review the TrainingState namedtuple holding params, target_params, optimizer state, and step count', 'run a DQN agent on a given bsuite environment and log results to CSV', 'run a single bsuite experiment with a specific bsuite_id using the DQN baseline', 'run a multiprocess sweep of DQN experiments across multiple bsuite environments', 'review the run function that loads a bsuite environment and executes a DQN agent', 'review the main entry point that parses flags and dispatches single or sweep runs', 'test the DQN agent training by running parameterized test cases across bsuite environments', 'run an experiment using a DQN agent with a bsuite environment for 5 episodes', 'create a default DQN agent using observation and action specs from a bsuite environment', 'load a bsuite environment from its ID string for agent training tests', 'review the RunTest class that parameterizes DQN agent training tests across bsuite environments']
```

Usage

```
{'run_dqn_agent_on_bsuite_env': 'run a DQN agent on a given bsuite environment and log results to CSV', 'run_single_bsuite_experiment': 'run a single bsuite experiment with a specific bsuite_id using the DQN baseline', 'run_bsuite_sweep_multiprocess': 'run a multiprocess sweep of DQN experiments across multiple bsuite environments', 'review_run_function': 'review the run function that loads a bsuite environment and executes a DQN agent', 'review_main_entry_point': 'review the main entry point that parses flags and dispatches single or sweep runs'}
```

## File: google-deepmind_bsuite/bsuite/baselines/jax/dqn/run_test.py

Prompts

```
['build a JAX-based DQN agent with custom network, optimizer, and replay buffer hyperparameters', 'create a default DQN agent with an MLP network and Adam optimizer using default_agent', 'run epsilon-greedy action selection on a dm_env timestep using the DQN agent', 'test the DQN agent update method that adds transitions to replay and performs SGD steps', 'review the TrainingState namedtuple holding params, target_params, optimizer state, and step count', 'run a DQN agent on a given bsuite environment and log results to CSV', 'run a single bsuite experiment with a specific bsuite_id using the DQN baseline', 'run a multiprocess sweep of DQN experiments across multiple bsuite environments', 'review the run function that loads a bsuite environment and executes a DQN agent', 'review the main entry point that parses flags and dispatches single or sweep runs', 'test the DQN agent training by running parameterized test cases across bsuite environments', 'run an experiment using a DQN agent with a bsuite environment for 5 episodes', 'create a default DQN agent using observation and action specs from a bsuite environment', 'load a bsuite environment from its ID string for agent training tests', 'review the RunTest class that parameterizes DQN agent training tests across bsuite environments']
```

Usage

```
{'test_dqn_agent_training': 'test the DQN agent training by running parameterized test cases across bsuite environments', 'run_experiment_with_dqn': 'run an experiment using a DQN agent with a bsuite environment for 5 episodes', 'create_dqn_default_agent': 'create a default DQN agent using observation and action specs from a bsuite environment', 'load_bsuite_environment': 'load a bsuite environment from its ID string for agent training tests', 'review_RunTest_class': 'review the RunTest class that parameterizes DQN agent training tests across bsuite environments'}
```


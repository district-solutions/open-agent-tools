# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/tf/boot_dqn/agent.py

Prompts

```
['create a bootstrapped DQN agent with default hyperparameters using the default_agent factory function', 'build an ensemble of networks with additive prior functions using make_ensemble for deep RL exploration', 'initialize a BootstrappedDqn agent with a custom ensemble, optimizer, replay buffer, and exploration hyperparameters', 'select an action using Thompson sampling with epsilon-greedy policy from the active ensemble head', 'update the agent by adding a transition to replay memory and performing SGD on a sampled minibatch', 'run a bootstrapped DQN agent on a single bsuite environment like catch/0 and log results to CSV', 'run a bootstrapped DQN agent across a sweep of bsuite experiments using MPI parallel execution', 'review the run function that creates a BootstrappedDQN agent with an ensemble network and executes it on a bsuite environment', 'review the main function that dispatches single experiments or multiprocess sweeps based on the bsuite_id flag', 'refactor the run function to support custom optimizer or ensemble hyperparameters beyond absl flags', 'test the RunTest class to run BootDQN agent training across bsuite environments with parameterized test cases', 'run an experiment using the BootDQN agent with a bsuite environment for a specified number of episodes', 'create a BootDQN agent using default_agent with observation spec, action spec, and ensemble size parameters', 'load a bsuite environment from its ID string using bsuite.load_from_id for agent testing', 'review the RunTest parameterized test class that validates BootDQN agent training across multiple bsuite environments']
```

Usage

```
{'create_default_bootstrapped_dqn_agent': 'create a bootstrapped DQN agent with default hyperparameters using the default_agent factory function', 'build_ensemble_with_prior_networks': 'build an ensemble of networks with additive prior functions using make_ensemble for deep RL exploration', 'initialize_bootstrapped_dqn_class': 'initialize a BootstrappedDqn agent with a custom ensemble, optimizer, replay buffer, and exploration hyperparameters', 'select_action_thompson_sampling': 'select an action using Thompson sampling with epsilon-greedy policy from the active ensemble head', 'update_agent_with_transition': 'update the agent by adding a transition to replay memory and performing SGD on a sampled minibatch'}
```

## File: google-deepmind_bsuite/bsuite/baselines/tf/boot_dqn/run.py

Prompts

```
['create a bootstrapped DQN agent with default hyperparameters using the default_agent factory function', 'build an ensemble of networks with additive prior functions using make_ensemble for deep RL exploration', 'initialize a BootstrappedDqn agent with a custom ensemble, optimizer, replay buffer, and exploration hyperparameters', 'select an action using Thompson sampling with epsilon-greedy policy from the active ensemble head', 'update the agent by adding a transition to replay memory and performing SGD on a sampled minibatch', 'run a bootstrapped DQN agent on a single bsuite environment like catch/0 and log results to CSV', 'run a bootstrapped DQN agent across a sweep of bsuite experiments using MPI parallel execution', 'review the run function that creates a BootstrappedDQN agent with an ensemble network and executes it on a bsuite environment', 'review the main function that dispatches single experiments or multiprocess sweeps based on the bsuite_id flag', 'refactor the run function to support custom optimizer or ensemble hyperparameters beyond absl flags', 'test the RunTest class to run BootDQN agent training across bsuite environments with parameterized test cases', 'run an experiment using the BootDQN agent with a bsuite environment for a specified number of episodes', 'create a BootDQN agent using default_agent with observation spec, action spec, and ensemble size parameters', 'load a bsuite environment from its ID string using bsuite.load_from_id for agent testing', 'review the RunTest parameterized test class that validates BootDQN agent training across multiple bsuite environments']
```

Usage

```
{'run_boot_dqn_single_experiment': 'run a bootstrapped DQN agent on a single bsuite environment like catch/0 and log results to CSV', 'run_boot_dqn_sweep': 'run a bootstrapped DQN agent across a sweep of bsuite experiments using MPI parallel execution', 'review_run_function': 'review the run function that creates a BootstrappedDQN agent with an ensemble network and executes it on a bsuite environment', 'review_main_function': 'review the main function that dispatches single experiments or multiprocess sweeps based on the bsuite_id flag', 'refactor_run_function': 'refactor the run function to support custom optimizer or ensemble hyperparameters beyond absl flags'}
```

## File: google-deepmind_bsuite/bsuite/baselines/tf/boot_dqn/run_test.py

Prompts

```
['create a bootstrapped DQN agent with default hyperparameters using the default_agent factory function', 'build an ensemble of networks with additive prior functions using make_ensemble for deep RL exploration', 'initialize a BootstrappedDqn agent with a custom ensemble, optimizer, replay buffer, and exploration hyperparameters', 'select an action using Thompson sampling with epsilon-greedy policy from the active ensemble head', 'update the agent by adding a transition to replay memory and performing SGD on a sampled minibatch', 'run a bootstrapped DQN agent on a single bsuite environment like catch/0 and log results to CSV', 'run a bootstrapped DQN agent across a sweep of bsuite experiments using MPI parallel execution', 'review the run function that creates a BootstrappedDQN agent with an ensemble network and executes it on a bsuite environment', 'review the main function that dispatches single experiments or multiprocess sweeps based on the bsuite_id flag', 'refactor the run function to support custom optimizer or ensemble hyperparameters beyond absl flags', 'test the RunTest class to run BootDQN agent training across bsuite environments with parameterized test cases', 'run an experiment using the BootDQN agent with a bsuite environment for a specified number of episodes', 'create a BootDQN agent using default_agent with observation spec, action spec, and ensemble size parameters', 'load a bsuite environment from its ID string using bsuite.load_from_id for agent testing', 'review the RunTest parameterized test class that validates BootDQN agent training across multiple bsuite environments']
```

Usage

```
{'test_run_boot_dqn_agent': 'test the RunTest class to run BootDQN agent training across bsuite environments with parameterized test cases', 'run_experiment_with_boot_dqn': 'run an experiment using the BootDQN agent with a bsuite environment for a specified number of episodes', 'create_boot_dqn_agent': 'create a BootDQN agent using default_agent with observation spec, action spec, and ensemble size parameters', 'load_bsuite_environment': 'load a bsuite environment from its ID string using bsuite.load_from_id for agent testing', 'review_RunTest_class': 'review the RunTest parameterized test class that validates BootDQN agent training across multiple bsuite environments'}
```


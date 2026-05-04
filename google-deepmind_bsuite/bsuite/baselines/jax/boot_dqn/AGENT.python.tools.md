# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/jax/boot_dqn/agent.py

Prompts

```
['build a BootstrappedDQN agent with an ensemble of Q-networks using Haiku and JAX', 'create a default Bootstrapped DQN agent with randomized prior functions and Adam optimizer', 'select an action using Thompson sampling with epsilon-greedy policy from the active Q-network', 'update the agent by adding transitions to replay buffer and performing periodic SGD steps', 'review the TrainingState NamedTuple holding params, target_params, optimizer state, and step count', 'run a bootstrapped DQN agent on a bsuite environment with CSV logging', 'run a single bsuite experiment by passing a bsuite_id to the run function', 'run a multiprocess sweep over multiple bsuite experiments using pool.map_mpi', 'create a Q-network with randomized prior function using Haiku MLPs and JAX', 'build a BootstrappedDQN agent with an ensemble of networks and Adam optimizer', 'test the RunTest class to run a boot_dqn agent against bsuite environments for 5 episodes', 'run the parameterized test_run method across all bsuite testing environments using sweep.TESTING', 'create a boot_dqn default agent with num_ensemble=2 using observation and action specs', 'review the RunTest class and its parameterized test_run method for agent training coverage', 'summarize the basic test coverage for boot_dqn agent training across bsuite environments']
```

Usage

```
{'build_bootstrapped_dqn_agent': 'build a BootstrappedDQN agent with an ensemble of Q-networks using Haiku and JAX', 'create_default_dqn_agent': 'create a default Bootstrapped DQN agent with randomized prior functions and Adam optimizer', 'select_action_thompson_sampling': 'select an action using Thompson sampling with epsilon-greedy policy from the active Q-network', 'update_agent_replay_sgd': 'update the agent by adding transitions to replay buffer and performing periodic SGD steps', 'review_training_state_namedtuple': 'review the TrainingState NamedTuple holding params, target_params, optimizer state, and step count'}
```

## File: google-deepmind_bsuite/bsuite/baselines/jax/boot_dqn/run.py

Prompts

```
['build a BootstrappedDQN agent with an ensemble of Q-networks using Haiku and JAX', 'create a default Bootstrapped DQN agent with randomized prior functions and Adam optimizer', 'select an action using Thompson sampling with epsilon-greedy policy from the active Q-network', 'update the agent by adding transitions to replay buffer and performing periodic SGD steps', 'review the TrainingState NamedTuple holding params, target_params, optimizer state, and step count', 'run a bootstrapped DQN agent on a bsuite environment with CSV logging', 'run a single bsuite experiment by passing a bsuite_id to the run function', 'run a multiprocess sweep over multiple bsuite experiments using pool.map_mpi', 'create a Q-network with randomized prior function using Haiku MLPs and JAX', 'build a BootstrappedDQN agent with an ensemble of networks and Adam optimizer', 'test the RunTest class to run a boot_dqn agent against bsuite environments for 5 episodes', 'run the parameterized test_run method across all bsuite testing environments using sweep.TESTING', 'create a boot_dqn default agent with num_ensemble=2 using observation and action specs', 'review the RunTest class and its parameterized test_run method for agent training coverage', 'summarize the basic test coverage for boot_dqn agent training across bsuite environments']
```

Usage

```
{'run_boot_dqn_agent': 'run a bootstrapped DQN agent on a bsuite environment with CSV logging', 'run_single_experiment': 'run a single bsuite experiment by passing a bsuite_id to the run function', 'run_sweep': 'run a multiprocess sweep over multiple bsuite experiments using pool.map_mpi', 'create_q_network': 'create a Q-network with randomized prior function using Haiku MLPs and JAX', 'build_bootstrapped_dqn': 'build a BootstrappedDQN agent with an ensemble of networks and Adam optimizer'}
```

## File: google-deepmind_bsuite/bsuite/baselines/jax/boot_dqn/run_test.py

Prompts

```
['build a BootstrappedDQN agent with an ensemble of Q-networks using Haiku and JAX', 'create a default Bootstrapped DQN agent with randomized prior functions and Adam optimizer', 'select an action using Thompson sampling with epsilon-greedy policy from the active Q-network', 'update the agent by adding transitions to replay buffer and performing periodic SGD steps', 'review the TrainingState NamedTuple holding params, target_params, optimizer state, and step count', 'run a bootstrapped DQN agent on a bsuite environment with CSV logging', 'run a single bsuite experiment by passing a bsuite_id to the run function', 'run a multiprocess sweep over multiple bsuite experiments using pool.map_mpi', 'create a Q-network with randomized prior function using Haiku MLPs and JAX', 'build a BootstrappedDQN agent with an ensemble of networks and Adam optimizer', 'test the RunTest class to run a boot_dqn agent against bsuite environments for 5 episodes', 'run the parameterized test_run method across all bsuite testing environments using sweep.TESTING', 'create a boot_dqn default agent with num_ensemble=2 using observation and action specs', 'review the RunTest class and its parameterized test_run method for agent training coverage', 'summarize the basic test coverage for boot_dqn agent training across bsuite environments']
```

Usage

```
{'test_run_boot_dqn_agent': 'test the RunTest class to run a boot_dqn agent against bsuite environments for 5 episodes', 'run_parameterized_test': 'run the parameterized test_run method across all bsuite testing environments using sweep.TESTING', 'create_boot_dqn_agent': 'create a boot_dqn default agent with num_ensemble=2 using observation and action specs', 'review_RunTest_class': 'review the RunTest class and its parameterized test_run method for agent training coverage', 'summarize_test_coverage': 'summarize the basic test coverage for boot_dqn agent training across bsuite environments'}
```


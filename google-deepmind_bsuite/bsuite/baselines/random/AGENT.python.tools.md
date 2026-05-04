# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/random/agent.py

Prompts

```
['create a Random agent that selects uniformly random actions from a discrete action space', 'create a Random agent with a fixed random seed for reproducible action selection', 'call select_action on a Random agent to get a random action for the current timestep', 'call update on a Random agent with timestep and action transitions (no-op for random policy)', 'use default_agent factory function to create a Random agent from observation and action specs', 'run a random agent on a single bsuite environment and log results to CSV', 'run a random agent across a sweep of bsuite environments using MPI parallelism', 'run a random agent on a bsuite environment with a custom number of episodes', 'run a random agent on a bsuite environment and log results to SQLite', 'run a random agent on a bsuite environment with a specific random seed', 'test running a random agent against a bsuite environment for a fixed number of episodes', 'run an experiment using a random default agent with a loaded bsuite environment', 'load a bsuite environment from its string identifier using bsuite.load_from_id', 'create a random default agent using observation and action specs from a bsuite environment', 'review the RunTest parameterized test class that validates random agent behavior across bsuite tasks']
```

Usage

```
{'create_random_agent': 'create a Random agent that selects uniformly random actions from a discrete action space', 'create_random_agent_with_seed': 'create a Random agent with a fixed random seed for reproducible action selection', 'select_random_action': 'call select_action on a Random agent to get a random action for the current timestep', 'update_random_agent': 'call update on a Random agent with timestep and action transitions (no-op for random policy)', 'create_default_random_agent': 'use default_agent factory function to create a Random agent from observation and action specs'}
```

## File: google-deepmind_bsuite/bsuite/baselines/random/run.py

Prompts

```
['create a Random agent that selects uniformly random actions from a discrete action space', 'create a Random agent with a fixed random seed for reproducible action selection', 'call select_action on a Random agent to get a random action for the current timestep', 'call update on a Random agent with timestep and action transitions (no-op for random policy)', 'use default_agent factory function to create a Random agent from observation and action specs', 'run a random agent on a single bsuite environment and log results to CSV', 'run a random agent across a sweep of bsuite environments using MPI parallelism', 'run a random agent on a bsuite environment with a custom number of episodes', 'run a random agent on a bsuite environment and log results to SQLite', 'run a random agent on a bsuite environment with a specific random seed', 'test running a random agent against a bsuite environment for a fixed number of episodes', 'run an experiment using a random default agent with a loaded bsuite environment', 'load a bsuite environment from its string identifier using bsuite.load_from_id', 'create a random default agent using observation and action specs from a bsuite environment', 'review the RunTest parameterized test class that validates random agent behavior across bsuite tasks']
```

Usage

```
{'run_random_agent_single': 'run a random agent on a single bsuite environment and log results to CSV', 'run_random_agent_sweep': 'run a random agent across a sweep of bsuite environments using MPI parallelism', 'run_random_agent_custom_episodes': 'run a random agent on a bsuite environment with a custom number of episodes', 'run_random_agent_sqlite': 'run a random agent on a bsuite environment and log results to SQLite', 'run_random_agent_seed': 'run a random agent on a bsuite environment with a specific random seed'}
```

## File: google-deepmind_bsuite/bsuite/baselines/random/run_test.py

Prompts

```
['create a Random agent that selects uniformly random actions from a discrete action space', 'create a Random agent with a fixed random seed for reproducible action selection', 'call select_action on a Random agent to get a random action for the current timestep', 'call update on a Random agent with timestep and action transitions (no-op for random policy)', 'use default_agent factory function to create a Random agent from observation and action specs', 'run a random agent on a single bsuite environment and log results to CSV', 'run a random agent across a sweep of bsuite environments using MPI parallelism', 'run a random agent on a bsuite environment with a custom number of episodes', 'run a random agent on a bsuite environment and log results to SQLite', 'run a random agent on a bsuite environment with a specific random seed', 'test running a random agent against a bsuite environment for a fixed number of episodes', 'run an experiment using a random default agent with a loaded bsuite environment', 'load a bsuite environment from its string identifier using bsuite.load_from_id', 'create a random default agent using observation and action specs from a bsuite environment', 'review the RunTest parameterized test class that validates random agent behavior across bsuite tasks']
```

Usage

```
{'test_run_random_agent': 'test running a random agent against a bsuite environment for a fixed number of episodes', 'run_experiment_with_random_agent': 'run an experiment using a random default agent with a loaded bsuite environment', 'load_bsuite_env_by_id': 'load a bsuite environment from its string identifier using bsuite.load_from_id', 'create_random_default_agent': 'create a random default agent using observation and action specs from a bsuite environment', 'review_RunTest_class': 'review the RunTest parameterized test class that validates random agent behavior across bsuite tasks'}
```


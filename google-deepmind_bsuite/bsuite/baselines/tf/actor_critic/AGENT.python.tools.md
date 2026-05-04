# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/tf/actor_critic/agent.py

Prompts

```
['build an actor-critic agent using default_agent with observation and action specs for reinforcement learning', 'create a PolicyValueNet with custom hidden sizes and a discrete action spec for policy and value heads', 'run select_action on an ActorCritic agent to sample an action from the current softmax policy', 'test the update method of ActorCritic by feeding transitions and verifying the buffer triggers SGD', 'refactor the _step method to adjust the td_lambda or discount hyperparameters for the critic loss', 'run an A2C actor-critic agent on a single bsuite environment with CSV logging', 'run a multiprocess sweep of actor-critic experiments across multiple bsuite environments using MPI', 'configure a PolicyValueNet with hidden layers and units for the actor-critic agent', 'review the run function that loads a bsuite environment and executes the actor-critic agent', 'review the main entry point that supports single experiment or sweep modes via flags', 'test running an actor-critic agent on a bsuite environment for 5 episodes', 'run an experiment using the default actor-critic agent on a bsuite environment', 'test actor-critic agent across multiple bsuite environments using parameterized test cases', 'create a default actor-critic agent using observation and action specs from a bsuite environment', 'load a bsuite environment by ID and run an actor-critic agent on it']
```

Usage

```
{'build_actor_critic_agent': 'build an actor-critic agent using default_agent with observation and action specs for reinforcement learning', 'create_policy_value_net': 'create a PolicyValueNet with custom hidden sizes and a discrete action spec for policy and value heads', 'run_select_action': 'run select_action on an ActorCritic agent to sample an action from the current softmax policy', 'test_update_method': 'test the update method of ActorCritic by feeding transitions and verifying the buffer triggers SGD', 'refactor_tdlambda_step': 'refactor the _step method to adjust the td_lambda or discount hyperparameters for the critic loss'}
```

## File: google-deepmind_bsuite/bsuite/baselines/tf/actor_critic/run.py

Prompts

```
['build an actor-critic agent using default_agent with observation and action specs for reinforcement learning', 'create a PolicyValueNet with custom hidden sizes and a discrete action spec for policy and value heads', 'run select_action on an ActorCritic agent to sample an action from the current softmax policy', 'test the update method of ActorCritic by feeding transitions and verifying the buffer triggers SGD', 'refactor the _step method to adjust the td_lambda or discount hyperparameters for the critic loss', 'run an A2C actor-critic agent on a single bsuite environment with CSV logging', 'run a multiprocess sweep of actor-critic experiments across multiple bsuite environments using MPI', 'configure a PolicyValueNet with hidden layers and units for the actor-critic agent', 'review the run function that loads a bsuite environment and executes the actor-critic agent', 'review the main entry point that supports single experiment or sweep modes via flags', 'test running an actor-critic agent on a bsuite environment for 5 episodes', 'run an experiment using the default actor-critic agent on a bsuite environment', 'test actor-critic agent across multiple bsuite environments using parameterized test cases', 'create a default actor-critic agent using observation and action specs from a bsuite environment', 'load a bsuite environment by ID and run an actor-critic agent on it']
```

Usage

```
{'run_actor_critic_agent': 'run an A2C actor-critic agent on a single bsuite environment with CSV logging', 'run_sweep_multiprocess': 'run a multiprocess sweep of actor-critic experiments across multiple bsuite environments using MPI', 'configure_actor_critic_network': 'configure a PolicyValueNet with hidden layers and units for the actor-critic agent', 'review_run_function': 'review the run function that loads a bsuite environment and executes the actor-critic agent', 'review_main_entry': 'review the main entry point that supports single experiment or sweep modes via flags'}
```

## File: google-deepmind_bsuite/bsuite/baselines/tf/actor_critic/run_test.py

Prompts

```
['build an actor-critic agent using default_agent with observation and action specs for reinforcement learning', 'create a PolicyValueNet with custom hidden sizes and a discrete action spec for policy and value heads', 'run select_action on an ActorCritic agent to sample an action from the current softmax policy', 'test the update method of ActorCritic by feeding transitions and verifying the buffer triggers SGD', 'refactor the _step method to adjust the td_lambda or discount hyperparameters for the critic loss', 'run an A2C actor-critic agent on a single bsuite environment with CSV logging', 'run a multiprocess sweep of actor-critic experiments across multiple bsuite environments using MPI', 'configure a PolicyValueNet with hidden layers and units for the actor-critic agent', 'review the run function that loads a bsuite environment and executes the actor-critic agent', 'review the main entry point that supports single experiment or sweep modes via flags', 'test running an actor-critic agent on a bsuite environment for 5 episodes', 'run an experiment using the default actor-critic agent on a bsuite environment', 'test actor-critic agent across multiple bsuite environments using parameterized test cases', 'create a default actor-critic agent using observation and action specs from a bsuite environment', 'load a bsuite environment by ID and run an actor-critic agent on it']
```

Usage

```
{'test_run_actor_critic_agent': 'test running an actor-critic agent on a bsuite environment for 5 episodes', 'run_experiment_with_default_agent': 'run an experiment using the default actor-critic agent on a bsuite environment', 'test_parameterized_bsuite_environments': 'test actor-critic agent across multiple bsuite environments using parameterized test cases', 'create_default_actor_critic_agent': 'create a default actor-critic agent using observation and action specs from a bsuite environment', 'load_and_test_bsuite_env': 'load a bsuite environment by ID and run an actor-critic agent on it'}
```


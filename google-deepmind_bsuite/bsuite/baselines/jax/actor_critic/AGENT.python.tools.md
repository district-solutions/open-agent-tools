# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/jax/actor_critic/agent.py

Prompts

```
['build a JAX Haiku actor-critic agent with an MLP network and Adam optimizer for reinforcement learning', 'create a default actor-critic agent with preconfigured hyperparameters using the default_agent factory function', 'select an action from the actor-critic agent using softmax policy over network logits', 'update the actor-critic agent by appending transitions and performing SGD when the buffer is full', 'define a TrainingState namedtuple to hold Haiku network parameters and Optax optimizer state', 'run an A2C agent on a bsuite environment by calling run with a bsuite_id string', 'run a single bsuite experiment using the main function with a specific bsuite_id flag', 'run a multiprocess sweep of bsuite experiments using pool.map_mpi over a sweep list', 'load a bsuite environment with recording enabled via bsuite.load_and_record with save_path and logging_mode', 'create a default actor-critic agent using actor_critic.default_agent with observation and action specs', 'test the actor_critic agent by running it against bsuite environments for 5 episodes', 'run the RunTest class with parameterized bsuite IDs from sweep.TESTING to validate agent training', 'test the default_agent function from actor_critic using observation and action specs from a bsuite environment', 'review the RunTest class that uses parameterized.TestCase to test agent training across multiple bsuite environments', 'summarize how experiment.run executes an agent against a bsuite environment for a fixed number of episodes']
```

Usage

```
{'build_actor_critic_agent': 'build a JAX Haiku actor-critic agent with an MLP network and Adam optimizer for reinforcement learning', 'create_default_agent': 'create a default actor-critic agent with preconfigured hyperparameters using the default_agent factory function', 'select_action_softmax': 'select an action from the actor-critic agent using softmax policy over network logits', 'update_agent_state': 'update the actor-critic agent by appending transitions and performing SGD when the buffer is full', 'define_training_state': 'define a TrainingState namedtuple to hold Haiku network parameters and Optax optimizer state'}
```

## File: google-deepmind_bsuite/bsuite/baselines/jax/actor_critic/run.py

Prompts

```
['build a JAX Haiku actor-critic agent with an MLP network and Adam optimizer for reinforcement learning', 'create a default actor-critic agent with preconfigured hyperparameters using the default_agent factory function', 'select an action from the actor-critic agent using softmax policy over network logits', 'update the actor-critic agent by appending transitions and performing SGD when the buffer is full', 'define a TrainingState namedtuple to hold Haiku network parameters and Optax optimizer state', 'run an A2C agent on a bsuite environment by calling run with a bsuite_id string', 'run a single bsuite experiment using the main function with a specific bsuite_id flag', 'run a multiprocess sweep of bsuite experiments using pool.map_mpi over a sweep list', 'load a bsuite environment with recording enabled via bsuite.load_and_record with save_path and logging_mode', 'create a default actor-critic agent using actor_critic.default_agent with observation and action specs', 'test the actor_critic agent by running it against bsuite environments for 5 episodes', 'run the RunTest class with parameterized bsuite IDs from sweep.TESTING to validate agent training', 'test the default_agent function from actor_critic using observation and action specs from a bsuite environment', 'review the RunTest class that uses parameterized.TestCase to test agent training across multiple bsuite environments', 'summarize how experiment.run executes an agent against a bsuite environment for a fixed number of episodes']
```

Usage

```
{'run_actor_critic_experiment': 'run an A2C agent on a bsuite environment by calling run with a bsuite_id string', 'run_single_experiment': 'run a single bsuite experiment using the main function with a specific bsuite_id flag', 'run_sweep_multiprocess': 'run a multiprocess sweep of bsuite experiments using pool.map_mpi over a sweep list', 'load_and_record_environment': 'load a bsuite environment with recording enabled via bsuite.load_and_record with save_path and logging_mode', 'create_default_actor_critic_agent': 'create a default actor-critic agent using actor_critic.default_agent with observation and action specs'}
```

## File: google-deepmind_bsuite/bsuite/baselines/jax/actor_critic/run_test.py

Prompts

```
['build a JAX Haiku actor-critic agent with an MLP network and Adam optimizer for reinforcement learning', 'create a default actor-critic agent with preconfigured hyperparameters using the default_agent factory function', 'select an action from the actor-critic agent using softmax policy over network logits', 'update the actor-critic agent by appending transitions and performing SGD when the buffer is full', 'define a TrainingState namedtuple to hold Haiku network parameters and Optax optimizer state', 'run an A2C agent on a bsuite environment by calling run with a bsuite_id string', 'run a single bsuite experiment using the main function with a specific bsuite_id flag', 'run a multiprocess sweep of bsuite experiments using pool.map_mpi over a sweep list', 'load a bsuite environment with recording enabled via bsuite.load_and_record with save_path and logging_mode', 'create a default actor-critic agent using actor_critic.default_agent with observation and action specs', 'test the actor_critic agent by running it against bsuite environments for 5 episodes', 'run the RunTest class with parameterized bsuite IDs from sweep.TESTING to validate agent training', 'test the default_agent function from actor_critic using observation and action specs from a bsuite environment', 'review the RunTest class that uses parameterized.TestCase to test agent training across multiple bsuite environments', 'summarize how experiment.run executes an agent against a bsuite environment for a fixed number of episodes']
```

Usage

```
{'test_run_actor_critic': 'test the actor_critic agent by running it against bsuite environments for 5 episodes', 'run_parameterized_test': 'run the RunTest class with parameterized bsuite IDs from sweep.TESTING to validate agent training', 'test_default_agent': 'test the default_agent function from actor_critic using observation and action specs from a bsuite environment', 'review_RunTest_class': 'review the RunTest class that uses parameterized.TestCase to test agent training across multiple bsuite environments', 'summarize_experiment_run': 'summarize how experiment.run executes an agent against a bsuite environment for a fixed number of episodes'}
```


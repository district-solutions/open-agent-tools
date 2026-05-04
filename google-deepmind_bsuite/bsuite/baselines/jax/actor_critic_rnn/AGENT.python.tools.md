# Agent Python Tools

- repo: google-deepmind/bsuite
- repo_uri: https://github.com/google-deepmind/bsuite

## File: google-deepmind_bsuite/bsuite/baselines/jax/actor_critic_rnn/agent.py

Prompts

```
['create an ActorCriticRNN agent with a custom network, optimizer, and hyperparameters for reinforcement learning', 'create a default actor-critic RNN agent with Adam optimizer and LSTM using default hyperparameters', 'run select_action on the agent to get a softmax policy action from a timestep observation', 'run update on the agent to add a transition to the buffer and perform SGD when full', 'review the AgentState NamedTuple holding network parameters, optimizer state, and RNN states', 'run an actor-critic agent on a single bsuite environment like catch/0 and log results to CSV', 'run an actor-critic agent across a sweep of bsuite experiments using multiprocess MPI parallel execution', 'run an actor-critic agent on a bsuite environment with a custom number of training episodes', 'run an actor-critic agent on a bsuite environment and save results using sqlite logging mode', 'run an actor-critic agent on a bsuite environment with verbose stdout logging enabled', 'run the parameterized test that trains an actor-critic RNN agent on bsuite environments for 5 episodes', 'test the RunTest.test_run method to verify agent training works across bsuite test environments', 'run an experiment with a given agent and environment for a specified number of episodes', 'load a bsuite environment by its ID string using bsuite.load_from_id']
```

Usage

```
{'create_actor_critic_rnn_agent': 'create an ActorCriticRNN agent with a custom network, optimizer, and hyperparameters for reinforcement learning', 'create_default_agent': 'create a default actor-critic RNN agent with Adam optimizer and LSTM using default hyperparameters', 'run_select_action': 'run select_action on the agent to get a softmax policy action from a timestep observation', 'run_update_agent': 'run update on the agent to add a transition to the buffer and perform SGD when full', 'review_agent_state': 'review the AgentState NamedTuple holding network parameters, optimizer state, and RNN states'}
```

## File: google-deepmind_bsuite/bsuite/baselines/jax/actor_critic_rnn/run.py

Prompts

```
['create an ActorCriticRNN agent with a custom network, optimizer, and hyperparameters for reinforcement learning', 'create a default actor-critic RNN agent with Adam optimizer and LSTM using default hyperparameters', 'run select_action on the agent to get a softmax policy action from a timestep observation', 'run update on the agent to add a transition to the buffer and perform SGD when full', 'review the AgentState NamedTuple holding network parameters, optimizer state, and RNN states', 'run an actor-critic agent on a single bsuite environment like catch/0 and log results to CSV', 'run an actor-critic agent across a sweep of bsuite experiments using multiprocess MPI parallel execution', 'run an actor-critic agent on a bsuite environment with a custom number of training episodes', 'run an actor-critic agent on a bsuite environment and save results using sqlite logging mode', 'run an actor-critic agent on a bsuite environment with verbose stdout logging enabled', 'run the parameterized test that trains an actor-critic RNN agent on bsuite environments for 5 episodes', 'test the RunTest.test_run method to verify agent training works across bsuite test environments', 'run an experiment with a given agent and environment for a specified number of episodes', 'load a bsuite environment by its ID string using bsuite.load_from_id']
```

Usage

```
{'run_actor_critic_single': 'run an actor-critic agent on a single bsuite environment like catch/0 and log results to CSV', 'run_actor_critic_sweep': 'run an actor-critic agent across a sweep of bsuite experiments using multiprocess MPI parallel execution', 'run_with_custom_episodes': 'run an actor-critic agent on a bsuite environment with a custom number of training episodes', 'run_with_sqlite_logging': 'run an actor-critic agent on a bsuite environment and save results using sqlite logging mode', 'run_verbose_actor_critic': 'run an actor-critic agent on a bsuite environment with verbose stdout logging enabled'}
```

## File: google-deepmind_bsuite/bsuite/baselines/jax/actor_critic_rnn/run_test.py

Prompts

```
['create an ActorCriticRNN agent with a custom network, optimizer, and hyperparameters for reinforcement learning', 'create a default actor-critic RNN agent with Adam optimizer and LSTM using default hyperparameters', 'run select_action on the agent to get a softmax policy action from a timestep observation', 'run update on the agent to add a transition to the buffer and perform SGD when full', 'review the AgentState NamedTuple holding network parameters, optimizer state, and RNN states', 'run an actor-critic agent on a single bsuite environment like catch/0 and log results to CSV', 'run an actor-critic agent across a sweep of bsuite experiments using multiprocess MPI parallel execution', 'run an actor-critic agent on a bsuite environment with a custom number of training episodes', 'run an actor-critic agent on a bsuite environment and save results using sqlite logging mode', 'run an actor-critic agent on a bsuite environment with verbose stdout logging enabled', 'run the parameterized test that trains an actor-critic RNN agent on bsuite environments for 5 episodes', 'test the RunTest.test_run method to verify agent training works across bsuite test environments', 'run an experiment with a given agent and environment for a specified number of episodes', 'load a bsuite environment by its ID string using bsuite.load_from_id']
```

Usage

```
{'run_actor_critic_rnn_test': 'run the parameterized test that trains an actor-critic RNN agent on bsuite environments for 5 episodes', 'test_run_method': 'test the RunTest.test_run method to verify agent training works across bsuite test environments', 'create_default_agent': 'create a default actor-critic RNN agent using observation and action specs from a bsuite environment', 'run_experiment': 'run an experiment with a given agent and environment for a specified number of episodes', 'load_bsuite_environment': 'load a bsuite environment by its ID string using bsuite.load_from_id'}
```


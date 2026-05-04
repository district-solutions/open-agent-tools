# Agent Python Tools

- repo: google-deepmind/dqnzoo
- repo_uri: https://github.com/google-deepmind/dqn_zoo

## File: google-deepmind_dqnzoo/dqn_zoo/c51/agent.py

Prompts

```
['create a C51 agent instance with a network, optimizer, replay buffer, and epsilon schedule', 'run a C51 agent step to select an action given a dm_env timestep and optionally learn', 'review the C51 agent loss function that computes categorical Q-learning loss over a batch of transitions', 'test the C51 agent update method that computes gradients and applies optimizer updates via JAX JIT', 'summarize the C51 agent epsilon-greedy action selection policy using the online network Q-values', 'run the C51 agent training loop on an Atari environment with configurable hyperparameters', 'create a GymAtari environment wrapped with random noops for the specified game name', 'build a C51 Atari network with a support vector for distributional RL', 'configure a linear epsilon decay schedule for exploration during training iterations', 'compress and decompress replay buffer transition states to reduce memory usage', 'test the C51 Atari agent by running RunAtariTest with pong environment and minimal training frames', 'run the C51 Atari test suite using absltest.main with JAX numpy rank promotion enabled', 'test run_atari.main by setting FLAGS for environment name, replay capacity, batch size, and learn period', 'review the RunAtariTest class and its test_can_run_agent method for C51 Atari agent validation', 'refactor test_can_run_agent to add new Atari environments or adjust training hyperparameters']
```

Usage

```
{'create_C51_agent': 'create a C51 agent instance with a network, optimizer, replay buffer, and epsilon schedule', 'run_C51_step': 'run a C51 agent step to select an action given a dm_env timestep and optionally learn', 'review_C51_loss_fn': 'review the C51 agent loss function that computes categorical Q-learning loss over a batch of transitions', 'test_C51_update': 'test the C51 agent update method that computes gradients and applies optimizer updates via JAX JIT', 'summarize_C51_select_action': 'summarize the C51 agent epsilon-greedy action selection policy using the online network Q-values'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/c51/run_atari.py

Prompts

```
['create a C51 agent instance with a network, optimizer, replay buffer, and epsilon schedule', 'run a C51 agent step to select an action given a dm_env timestep and optionally learn', 'review the C51 agent loss function that computes categorical Q-learning loss over a batch of transitions', 'test the C51 agent update method that computes gradients and applies optimizer updates via JAX JIT', 'summarize the C51 agent epsilon-greedy action selection policy using the online network Q-values', 'run the C51 agent training loop on an Atari environment with configurable hyperparameters', 'create a GymAtari environment wrapped with random noops for the specified game name', 'build a C51 Atari network with a support vector for distributional RL', 'configure a linear epsilon decay schedule for exploration during training iterations', 'compress and decompress replay buffer transition states to reduce memory usage', 'test the C51 Atari agent by running RunAtariTest with pong environment and minimal training frames', 'run the C51 Atari test suite using absltest.main with JAX numpy rank promotion enabled', 'test run_atari.main by setting FLAGS for environment name, replay capacity, batch size, and learn period', 'review the RunAtariTest class and its test_can_run_agent method for C51 Atari agent validation', 'refactor test_can_run_agent to add new Atari environments or adjust training hyperparameters']
```

Usage

```
{'run_C51_atari_training': 'run the C51 agent training loop on an Atari environment with configurable hyperparameters', 'create_atari_environment': 'create a GymAtari environment wrapped with random noops for the specified game name', 'build_C51_network': 'build a C51 Atari network with a support vector for distributional RL', 'configure_exploration_schedule': 'configure a linear epsilon decay schedule for exploration during training iterations', 'compress_replay_transitions': 'compress and decompress replay buffer transition states to reduce memory usage'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/c51/run_atari_test.py

Prompts

```
['create a C51 agent instance with a network, optimizer, replay buffer, and epsilon schedule', 'run a C51 agent step to select an action given a dm_env timestep and optionally learn', 'review the C51 agent loss function that computes categorical Q-learning loss over a batch of transitions', 'test the C51 agent update method that computes gradients and applies optimizer updates via JAX JIT', 'summarize the C51 agent epsilon-greedy action selection policy using the online network Q-values', 'run the C51 agent training loop on an Atari environment with configurable hyperparameters', 'create a GymAtari environment wrapped with random noops for the specified game name', 'build a C51 Atari network with a support vector for distributional RL', 'configure a linear epsilon decay schedule for exploration during training iterations', 'compress and decompress replay buffer transition states to reduce memory usage', 'test the C51 Atari agent by running RunAtariTest with pong environment and minimal training frames', 'run the C51 Atari test suite using absltest.main with JAX numpy rank promotion enabled', 'test run_atari.main by setting FLAGS for environment name, replay capacity, batch size, and learn period', 'review the RunAtariTest class and its test_can_run_agent method for C51 Atari agent validation', 'refactor test_can_run_agent to add new Atari environments or adjust training hyperparameters']
```

Usage

```
{'test_C51_atari_agent': 'test the C51 Atari agent by running RunAtariTest with pong environment and minimal training frames', 'run_atari_test_main': 'run the C51 Atari test suite using absltest.main with JAX numpy rank promotion enabled', 'test_run_atari_with_flags': 'test run_atari.main by setting FLAGS for environment name, replay capacity, batch size, and learn period', 'review_RunAtariTest_class': 'review the RunAtariTest class and its test_can_run_agent method for C51 Atari agent validation', 'refactor_test_can_run_agent': 'refactor test_can_run_agent to add new Atari environments or adjust training hyperparameters'}
```


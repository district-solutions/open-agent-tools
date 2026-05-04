# Agent Python Tools

- repo: google-deepmind/dqnzoo
- repo_uri: https://github.com/google-deepmind/dqn_zoo

## File: google-deepmind_dqnzoo/dqn_zoo/rainbow/agent.py

Prompts

```
['create a Rainbow agent with a network, optimizer, replay buffer, and preprocessor', 'run a Rainbow agent step to select an action and optionally learn from a timestep', 'run the Rainbow agent learning update by sampling transitions from prioritized replay and updating network parameters', 'reset the Rainbow agent episodic state including the transition accumulator and preprocessor', 'summarize the Rainbow agent loss function that computes categorical double Q-learning loss over a batch', 'run the Rainbow DQN agent training loop on an Atari environment like Pong', 'run the Rainbow agent training on a custom Atari environment by setting the environment_name flag', 'run the Rainbow agent training loop with CSV logging and checkpointing enabled', 'review the main function that sets up and trains a Rainbow DQN agent on Atari', 'review the environment_builder function that creates a GymAtari environment with random no-ops wrapping', 'test the Rainbow DQN agent on an Atari environment like Pong with small replay capacity', 'run the Rainbow Atari test suite using absltest.main entry point', 'test run_atari.main by setting environment name, replay capacity, and batch size flags', 'review the RunAtariTest class and its test_can_run_agent method for Atari DQN testing', 'summarize the absl flags used in the Rainbow Atari test including environment name and train frames']
```

Usage

```
{'create_rainbow_agent': 'create a Rainbow agent with a network, optimizer, replay buffer, and preprocessor', 'run_rainbow_step': 'run a Rainbow agent step to select an action and optionally learn from a timestep', 'run_rainbow_learn': 'run the Rainbow agent learning update by sampling transitions from prioritized replay and updating network parameters', 'reset_rainbow_agent': 'reset the Rainbow agent episodic state including the transition accumulator and preprocessor', 'summarize_rainbow_loss_fn': 'summarize the Rainbow agent loss function that computes categorical double Q-learning loss over a batch'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/rainbow/run_atari.py

Prompts

```
['create a Rainbow agent with a network, optimizer, replay buffer, and preprocessor', 'run a Rainbow agent step to select an action and optionally learn from a timestep', 'run the Rainbow agent learning update by sampling transitions from prioritized replay and updating network parameters', 'reset the Rainbow agent episodic state including the transition accumulator and preprocessor', 'summarize the Rainbow agent loss function that computes categorical double Q-learning loss over a batch', 'run the Rainbow DQN agent training loop on an Atari environment like Pong', 'run the Rainbow agent training on a custom Atari environment by setting the environment_name flag', 'run the Rainbow agent training loop with CSV logging and checkpointing enabled', 'review the main function that sets up and trains a Rainbow DQN agent on Atari', 'review the environment_builder function that creates a GymAtari environment with random no-ops wrapping', 'test the Rainbow DQN agent on an Atari environment like Pong with small replay capacity', 'run the Rainbow Atari test suite using absltest.main entry point', 'test run_atari.main by setting environment name, replay capacity, and batch size flags', 'review the RunAtariTest class and its test_can_run_agent method for Atari DQN testing', 'summarize the absl flags used in the Rainbow Atari test including environment name and train frames']
```

Usage

```
{'run_rainbow_atari_training': 'run the Rainbow DQN agent training loop on an Atari environment like Pong', 'run_rainbow_with_custom_env': 'run the Rainbow agent training on a custom Atari environment by setting the environment_name flag', 'run_rainbow_with_checkpoints': 'run the Rainbow agent training loop with CSV logging and checkpointing enabled', 'review_rainbow_main': 'review the main function that sets up and trains a Rainbow DQN agent on Atari', 'review_rainbow_environment_builder': 'review the environment_builder function that creates a GymAtari environment with random no-ops wrapping'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/rainbow/run_atari_test.py

Prompts

```
['create a Rainbow agent with a network, optimizer, replay buffer, and preprocessor', 'run a Rainbow agent step to select an action and optionally learn from a timestep', 'run the Rainbow agent learning update by sampling transitions from prioritized replay and updating network parameters', 'reset the Rainbow agent episodic state including the transition accumulator and preprocessor', 'summarize the Rainbow agent loss function that computes categorical double Q-learning loss over a batch', 'run the Rainbow DQN agent training loop on an Atari environment like Pong', 'run the Rainbow agent training on a custom Atari environment by setting the environment_name flag', 'run the Rainbow agent training loop with CSV logging and checkpointing enabled', 'review the main function that sets up and trains a Rainbow DQN agent on Atari', 'review the environment_builder function that creates a GymAtari environment with random no-ops wrapping', 'test the Rainbow DQN agent on an Atari environment like Pong with small replay capacity', 'run the Rainbow Atari test suite using absltest.main entry point', 'test run_atari.main by setting environment name, replay capacity, and batch size flags', 'review the RunAtariTest class and its test_can_run_agent method for Atari DQN testing', 'summarize the absl flags used in the Rainbow Atari test including environment name and train frames']
```

Usage

```
{'test_rainbow_agent_on_atari': 'test the Rainbow DQN agent on an Atari environment like Pong with small replay capacity', 'run_atari_test_main': 'run the Rainbow Atari test suite using absltest.main entry point', 'test_run_atari_with_flags': 'test run_atari.main by setting environment name, replay capacity, and batch size flags', 'review_RunAtariTest_class': 'review the RunAtariTest class and its test_can_run_agent method for Atari DQN testing', 'summarize_rainbow_test_flags': 'summarize the absl flags used in the Rainbow Atari test including environment name and train frames'}
```


# Agent Python Tools

- repo: google-deepmind/dqnzoo
- repo_uri: https://github.com/google-deepmind/dqn_zoo

## File: google-deepmind_dqnzoo/dqn_zoo/qrdqn/agent.py

Prompts

```
['create a QR-DQN agent with a network, optimizer, replay buffer, and epsilon schedule', 'run a single step of the QR-DQN agent given a dm_env timestep to select an action', 'reset the QR-DQN agent episodic state including frame stack and action repeat', 'serialize the QR-DQN agent state including params, optimizer, and replay buffer to a dictionary', 'restore the QR-DQN agent state from a deserialized dictionary with params and replay buffer', 'run the QR-DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'create a GymAtari environment wrapped with random noops for the specified Atari game', 'build a quantile regression Atari network with Haiku for distributional reinforcement learning', 'configure a TransitionReplay buffer with optional state compression for experience replay', 'evaluate a trained QR-DQN agent using an EpsilonGreedyActor with a fixed exploration rate', 'test the QR-DQN agent by running it on the pong Atari environment with minimal frames', 'run the QR-DQN test suite using absltest to verify the agent can execute on Atari games', 'test the run_atari main function with custom flags for replay capacity, batch size, and iterations', 'review the RunAtariTest class and its flagsaver-decorated test_can_run_agent method for QR-DQN validation', 'summarize the absl flags used in the QR-DQN Atari test including environment name, train frames, and eval frames']
```

Usage

```
{'create_qrdqn_agent': 'create a QR-DQN agent with a network, optimizer, replay buffer, and epsilon schedule', 'run_qrdqn_step': 'run a single step of the QR-DQN agent given a dm_env timestep to select an action', 'reset_qrdqn_agent': 'reset the QR-DQN agent episodic state including frame stack and action repeat', 'serialize_qrdqn_state': 'serialize the QR-DQN agent state including params, optimizer, and replay buffer to a dictionary', 'restore_qrdqn_state': 'restore the QR-DQN agent state from a deserialized dictionary with params and replay buffer'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/qrdqn/run_atari.py

Prompts

```
['create a QR-DQN agent with a network, optimizer, replay buffer, and epsilon schedule', 'run a single step of the QR-DQN agent given a dm_env timestep to select an action', 'reset the QR-DQN agent episodic state including frame stack and action repeat', 'serialize the QR-DQN agent state including params, optimizer, and replay buffer to a dictionary', 'restore the QR-DQN agent state from a deserialized dictionary with params and replay buffer', 'run the QR-DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'create a GymAtari environment wrapped with random noops for the specified Atari game', 'build a quantile regression Atari network with Haiku for distributional reinforcement learning', 'configure a TransitionReplay buffer with optional state compression for experience replay', 'evaluate a trained QR-DQN agent using an EpsilonGreedyActor with a fixed exploration rate', 'test the QR-DQN agent by running it on the pong Atari environment with minimal frames', 'run the QR-DQN test suite using absltest to verify the agent can execute on Atari games', 'test the run_atari main function with custom flags for replay capacity, batch size, and iterations', 'review the RunAtariTest class and its flagsaver-decorated test_can_run_agent method for QR-DQN validation', 'summarize the absl flags used in the QR-DQN Atari test including environment name, train frames, and eval frames']
```

Usage

```
{'run_qrdqn_atari_training': 'run the QR-DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'create_atari_environment': 'create a GymAtari environment wrapped with random noops for the specified Atari game', 'build_qr_atari_network': 'build a quantile regression Atari network with Haiku for distributional reinforcement learning', 'configure_replay_buffer': 'configure a TransitionReplay buffer with optional state compression for experience replay', 'evaluate_epsilon_greedy_actor': 'evaluate a trained QR-DQN agent using an EpsilonGreedyActor with a fixed exploration rate'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/qrdqn/run_atari_test.py

Prompts

```
['create a QR-DQN agent with a network, optimizer, replay buffer, and epsilon schedule', 'run a single step of the QR-DQN agent given a dm_env timestep to select an action', 'reset the QR-DQN agent episodic state including frame stack and action repeat', 'serialize the QR-DQN agent state including params, optimizer, and replay buffer to a dictionary', 'restore the QR-DQN agent state from a deserialized dictionary with params and replay buffer', 'run the QR-DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'create a GymAtari environment wrapped with random noops for the specified Atari game', 'build a quantile regression Atari network with Haiku for distributional reinforcement learning', 'configure a TransitionReplay buffer with optional state compression for experience replay', 'evaluate a trained QR-DQN agent using an EpsilonGreedyActor with a fixed exploration rate', 'test the QR-DQN agent by running it on the pong Atari environment with minimal frames', 'run the QR-DQN test suite using absltest to verify the agent can execute on Atari games', 'test the run_atari main function with custom flags for replay capacity, batch size, and iterations', 'review the RunAtariTest class and its flagsaver-decorated test_can_run_agent method for QR-DQN validation', 'summarize the absl flags used in the QR-DQN Atari test including environment name, train frames, and eval frames']
```

Usage

```
{'test_qrdqn_agent_on_atari': 'test the QR-DQN agent by running it on the pong Atari environment with minimal frames', 'run_qrdqn_test_suite': 'run the QR-DQN test suite using absltest to verify the agent can execute on Atari games', 'test_run_atari_main': 'test the run_atari main function with custom flags for replay capacity, batch size, and iterations', 'review_RunAtariTest_class': 'review the RunAtariTest class and its flagsaver-decorated test_can_run_agent method for QR-DQN validation', 'summarize_qrdqn_test_flags': 'summarize the absl flags used in the QR-DQN Atari test including environment name, train frames, and eval frames'}
```


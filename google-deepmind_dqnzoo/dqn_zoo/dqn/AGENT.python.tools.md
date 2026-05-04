# Agent Python Tools

- repo: google-deepmind/dqnzoo
- repo_uri: https://github.com/google-deepmind/dqn_zoo

## File: google-deepmind_dqnzoo/dqn_zoo/dqn/agent.py

Prompts

```
['create a DQN agent with a network, optimizer, replay buffer, and epsilon-greedy exploration policy', 'run a single environment step that selects an action, accumulates transitions, and learns periodically', 'build a loss function that computes TD errors using batched Q-learning with clipped gradients', 'test the epsilon-greedy action selection method that samples actions from Q-values with exploration noise', 'review the JIT-compiled update function that computes gradients and applies optimizer updates to online network parameters', 'run the DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'create a GymAtari environment wrapped with random no-ops for Atari game training', 'build an Atari observation preprocessor that stacks frames, grayscales, and clips rewards', 'configure a transition replay buffer with optional state compression for experience replay', 'evaluate a trained DQN agent on Atari and compute human-normalized scores', 'test the DQN agent on the Pong Atari environment with minimal training frames', 'run the RunAtariTest test case to verify the DQN agent can train and evaluate', 'test run_atari.main by setting FLAGS for environment, replay capacity, and training parameters', 'review the RunAtariTest class and its test_can_run_agent method for DQN Atari testing', 'summarize the DQN Atari test module that validates agent training with absl flags']
```

Usage

```
{'create_dqn_agent': 'create a DQN agent with a network, optimizer, replay buffer, and epsilon-greedy exploration policy', 'run_dqn_step': 'run a single environment step that selects an action, accumulates transitions, and learns periodically', 'build_loss_fn': 'build a loss function that computes TD errors using batched Q-learning with clipped gradients', 'test_select_action': 'test the epsilon-greedy action selection method that samples actions from Q-values with exploration noise', 'review_update': 'review the JIT-compiled update function that computes gradients and applies optimizer updates to online network parameters'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/dqn/run_atari.py

Prompts

```
['create a DQN agent with a network, optimizer, replay buffer, and epsilon-greedy exploration policy', 'run a single environment step that selects an action, accumulates transitions, and learns periodically', 'build a loss function that computes TD errors using batched Q-learning with clipped gradients', 'test the epsilon-greedy action selection method that samples actions from Q-values with exploration noise', 'review the JIT-compiled update function that computes gradients and applies optimizer updates to online network parameters', 'run the DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'create a GymAtari environment wrapped with random no-ops for Atari game training', 'build an Atari observation preprocessor that stacks frames, grayscales, and clips rewards', 'configure a transition replay buffer with optional state compression for experience replay', 'evaluate a trained DQN agent on Atari and compute human-normalized scores', 'test the DQN agent on the Pong Atari environment with minimal training frames', 'run the RunAtariTest test case to verify the DQN agent can train and evaluate', 'test run_atari.main by setting FLAGS for environment, replay capacity, and training parameters', 'review the RunAtariTest class and its test_can_run_agent method for DQN Atari testing', 'summarize the DQN Atari test module that validates agent training with absl flags']
```

Usage

```
{'run_dqn_atari_training': 'run the DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'create_atari_environment': 'create a GymAtari environment wrapped with random no-ops for Atari game training', 'build_atari_preprocessor': 'build an Atari observation preprocessor that stacks frames, grayscales, and clips rewards', 'configure_replay_buffer': 'configure a transition replay buffer with optional state compression for experience replay', 'evaluate_dqn_agent': 'evaluate a trained DQN agent on Atari and compute human-normalized scores'}
```

## File: google-deepmind_dqnzoo/dqn_zoo/dqn/run_atari_test.py

Prompts

```
['create a DQN agent with a network, optimizer, replay buffer, and epsilon-greedy exploration policy', 'run a single environment step that selects an action, accumulates transitions, and learns periodically', 'build a loss function that computes TD errors using batched Q-learning with clipped gradients', 'test the epsilon-greedy action selection method that samples actions from Q-values with exploration noise', 'review the JIT-compiled update function that computes gradients and applies optimizer updates to online network parameters', 'run the DQN agent training loop on an Atari environment like Pong with configurable hyperparameters', 'create a GymAtari environment wrapped with random no-ops for Atari game training', 'build an Atari observation preprocessor that stacks frames, grayscales, and clips rewards', 'configure a transition replay buffer with optional state compression for experience replay', 'evaluate a trained DQN agent on Atari and compute human-normalized scores', 'test the DQN agent on the Pong Atari environment with minimal training frames', 'run the RunAtariTest test case to verify the DQN agent can train and evaluate', 'test run_atari.main by setting FLAGS for environment, replay capacity, and training parameters', 'review the RunAtariTest class and its test_can_run_agent method for DQN Atari testing', 'summarize the DQN Atari test module that validates agent training with absl flags']
```

Usage

```
{'test_run_atari_agent': 'test the DQN agent on the Pong Atari environment with minimal training frames', 'run_DQN_test': 'run the RunAtariTest test case to verify the DQN agent can train and evaluate', 'test_run_atari_main': 'test run_atari.main by setting FLAGS for environment, replay capacity, and training parameters', 'review_RunAtariTest': 'review the RunAtariTest class and its test_can_run_agent method for DQN Atari testing', 'summarize_run_atari_test': 'summarize the DQN Atari test module that validates agent training with absl flags'}
```


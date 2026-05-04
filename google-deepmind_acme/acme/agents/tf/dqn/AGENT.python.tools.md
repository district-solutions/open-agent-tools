# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/dqn/agent.py

Prompts

```
['build a DQN agent with a Sonnet network, environment spec, and configurable replay buffer size', 'create a DQN agent using a custom policy network instead of the default epsilon greedy policy', 'run the DQN agent update method to perform a learner step and save a checkpoint', 'configure the DQN agent replay buffer with prioritized sampling and N-step transition adder', 'initialize a DQN agent that creates a deep-copied target network for stable Q-learning updates', 'build a distributed DQN agent topology using Launchpad with replay, learner, actors, and evaluator nodes', 'create a DQN learner with a network, target network, and Reverb replay dataset for training', 'create a DQN actor with an epsilon-greedy policy network that interacts with the environment and adds transitions to replay', 'create a DQN evaluator process that runs a policy network against the environment for evaluation', 'configure a Reverb replay table with prioritized sampling and a sample-to-insert rate limiter for DQN training', 'build a launchpad program from a DistributedDQN agent using the build method', 'test the distributed DQN agent runs for steps without crashing on Atari', 'launch a distributed agent program in multi-threaded test mode with launchpad', 'step the learner node forward to process replay buffer updates', 'build a sonnet MLP network with flatten layer for a discrete action space', 'test the DQN agent by running an environment loop with a fake discrete environment', 'create a fake discrete environment with configurable actions, observations, and episode length', 'construct a DQN agent with an environment spec, neural network, and replay buffer settings', 'run an acme environment loop with a DQN agent for a specified number of episodes', 'build a DQNLearner instance with online and target networks, discount, learning rate, and a TensorFlow dataset', 'run a single learning step on the DQNLearner to perform SGD and update replay buffer priorities', 'create an Adam optimizer for the DQN network using sonnet with a specified learning rate', 'review the double Q-learning loss computation using trfl with Huber loss and importance sampling weights', 'summarize the DQNLearner checkpointable state including network, target network, optimizer, and step count']
```

Usage

```
{'build_dqn_agent': 'build a DQN agent with a Sonnet network, environment spec, and configurable replay buffer size', 'create_dqn_with_custom_policy': 'create a DQN agent using a custom policy network instead of the default epsilon greedy policy', 'run_dqn_update': 'run the DQN agent update method to perform a learner step and save a checkpoint', 'configure_dqn_replay_buffer': 'configure the DQN agent replay buffer with prioritized sampling and N-step transition adder', 'initialize_dqn_target_network': 'initialize a DQN agent that creates a deep-copied target network for stable Q-learning updates'}
```

## File: google-deepmind_acme/acme/agents/tf/dqn/agent_distributed.py

Prompts

```
['build a DQN agent with a Sonnet network, environment spec, and configurable replay buffer size', 'create a DQN agent using a custom policy network instead of the default epsilon greedy policy', 'run the DQN agent update method to perform a learner step and save a checkpoint', 'configure the DQN agent replay buffer with prioritized sampling and N-step transition adder', 'initialize a DQN agent that creates a deep-copied target network for stable Q-learning updates', 'build a distributed DQN agent topology using Launchpad with replay, learner, actors, and evaluator nodes', 'create a DQN learner with a network, target network, and Reverb replay dataset for training', 'create a DQN actor with an epsilon-greedy policy network that interacts with the environment and adds transitions to replay', 'create a DQN evaluator process that runs a policy network against the environment for evaluation', 'configure a Reverb replay table with prioritized sampling and a sample-to-insert rate limiter for DQN training', 'build a launchpad program from a DistributedDQN agent using the build method', 'test the distributed DQN agent runs for steps without crashing on Atari', 'launch a distributed agent program in multi-threaded test mode with launchpad', 'step the learner node forward to process replay buffer updates', 'build a sonnet MLP network with flatten layer for a discrete action space', 'test the DQN agent by running an environment loop with a fake discrete environment', 'create a fake discrete environment with configurable actions, observations, and episode length', 'construct a DQN agent with an environment spec, neural network, and replay buffer settings', 'run an acme environment loop with a DQN agent for a specified number of episodes', 'build a DQNLearner instance with online and target networks, discount, learning rate, and a TensorFlow dataset', 'run a single learning step on the DQNLearner to perform SGD and update replay buffer priorities', 'create an Adam optimizer for the DQN network using sonnet with a specified learning rate', 'review the double Q-learning loss computation using trfl with Huber loss and importance sampling weights', 'summarize the DQNLearner checkpointable state including network, target network, optimizer, and step count']
```

Usage

```
{'build_distributed_dqn_agent': 'build a distributed DQN agent topology using Launchpad with replay, learner, actors, and evaluator nodes', 'create_dqn_learner': 'create a DQN learner with a network, target network, and Reverb replay dataset for training', 'create_dqn_actor': 'create a DQN actor with an epsilon-greedy policy network that interacts with the environment and adds transitions to replay', 'create_dqn_evaluator': 'create a DQN evaluator process that runs a policy network against the environment for evaluation', 'configure_replay_storage': 'configure a Reverb replay table with prioritized sampling and a sample-to-insert rate limiter for DQN training'}
```

## File: google-deepmind_acme/acme/agents/tf/dqn/agent_distributed_test.py

Prompts

```
['build a DQN agent with a Sonnet network, environment spec, and configurable replay buffer size', 'create a DQN agent using a custom policy network instead of the default epsilon greedy policy', 'run the DQN agent update method to perform a learner step and save a checkpoint', 'configure the DQN agent replay buffer with prioritized sampling and N-step transition adder', 'initialize a DQN agent that creates a deep-copied target network for stable Q-learning updates', 'build a distributed DQN agent topology using Launchpad with replay, learner, actors, and evaluator nodes', 'create a DQN learner with a network, target network, and Reverb replay dataset for training', 'create a DQN actor with an epsilon-greedy policy network that interacts with the environment and adds transitions to replay', 'create a DQN evaluator process that runs a policy network against the environment for evaluation', 'configure a Reverb replay table with prioritized sampling and a sample-to-insert rate limiter for DQN training', 'build a launchpad program from a DistributedDQN agent using the build method', 'test the distributed DQN agent runs for steps without crashing on Atari', 'launch a distributed agent program in multi-threaded test mode with launchpad', 'step the learner node forward to process replay buffer updates', 'build a sonnet MLP network with flatten layer for a discrete action space', 'test the DQN agent by running an environment loop with a fake discrete environment', 'create a fake discrete environment with configurable actions, observations, and episode length', 'construct a DQN agent with an environment spec, neural network, and replay buffer settings', 'run an acme environment loop with a DQN agent for a specified number of episodes', 'build a DQNLearner instance with online and target networks, discount, learning rate, and a TensorFlow dataset', 'run a single learning step on the DQNLearner to perform SGD and update replay buffer priorities', 'create an Adam optimizer for the DQN network using sonnet with a specified learning rate', 'review the double Q-learning loss computation using trfl with Huber loss and importance sampling weights', 'summarize the DQNLearner checkpointable state including network, target network, optimizer, and step count']
```

Usage

```
{'build_distributed_dqn_agent': 'build a DistributedDQN agent with environment and network factories for Atari training', 'build_program_from_agent': 'build a launchpad program from a DistributedDQN agent using the build method', 'test_distributed_agent_atari': 'test the distributed DQN agent runs for steps without crashing on Atari', 'launch_program_test_mt': 'launch a distributed agent program in multi-threaded test mode with launchpad', 'step_learner': 'step the learner node forward to process replay buffer updates'}
```

## File: google-deepmind_acme/acme/agents/tf/dqn/agent_test.py

Prompts

```
['build a DQN agent with a Sonnet network, environment spec, and configurable replay buffer size', 'create a DQN agent using a custom policy network instead of the default epsilon greedy policy', 'run the DQN agent update method to perform a learner step and save a checkpoint', 'configure the DQN agent replay buffer with prioritized sampling and N-step transition adder', 'initialize a DQN agent that creates a deep-copied target network for stable Q-learning updates', 'build a distributed DQN agent topology using Launchpad with replay, learner, actors, and evaluator nodes', 'create a DQN learner with a network, target network, and Reverb replay dataset for training', 'create a DQN actor with an epsilon-greedy policy network that interacts with the environment and adds transitions to replay', 'create a DQN evaluator process that runs a policy network against the environment for evaluation', 'configure a Reverb replay table with prioritized sampling and a sample-to-insert rate limiter for DQN training', 'build a launchpad program from a DistributedDQN agent using the build method', 'test the distributed DQN agent runs for steps without crashing on Atari', 'launch a distributed agent program in multi-threaded test mode with launchpad', 'step the learner node forward to process replay buffer updates', 'build a sonnet MLP network with flatten layer for a discrete action space', 'test the DQN agent by running an environment loop with a fake discrete environment', 'create a fake discrete environment with configurable actions, observations, and episode length', 'construct a DQN agent with an environment spec, neural network, and replay buffer settings', 'run an acme environment loop with a DQN agent for a specified number of episodes', 'build a DQNLearner instance with online and target networks, discount, learning rate, and a TensorFlow dataset', 'run a single learning step on the DQNLearner to perform SGD and update replay buffer priorities', 'create an Adam optimizer for the DQN network using sonnet with a specified learning rate', 'review the double Q-learning loss computation using trfl with Huber loss and importance sampling weights', 'summarize the DQNLearner checkpointable state including network, target network, optimizer, and step count']
```

Usage

```
{'build_dqn_network': 'build a sonnet MLP network with flatten layer for a discrete action space', 'test_dqn_agent': 'test the DQN agent by running an environment loop with a fake discrete environment', 'create_discrete_environment': 'create a fake discrete environment with configurable actions, observations, and episode length', 'construct_dqn_agent': 'construct a DQN agent with an environment spec, neural network, and replay buffer settings', 'run_environment_loop': 'run an acme environment loop with a DQN agent for a specified number of episodes'}
```

## File: google-deepmind_acme/acme/agents/tf/dqn/learning.py

Prompts

```
['build a DQN agent with a Sonnet network, environment spec, and configurable replay buffer size', 'create a DQN agent using a custom policy network instead of the default epsilon greedy policy', 'run the DQN agent update method to perform a learner step and save a checkpoint', 'configure the DQN agent replay buffer with prioritized sampling and N-step transition adder', 'initialize a DQN agent that creates a deep-copied target network for stable Q-learning updates', 'build a distributed DQN agent topology using Launchpad with replay, learner, actors, and evaluator nodes', 'create a DQN learner with a network, target network, and Reverb replay dataset for training', 'create a DQN actor with an epsilon-greedy policy network that interacts with the environment and adds transitions to replay', 'create a DQN evaluator process that runs a policy network against the environment for evaluation', 'configure a Reverb replay table with prioritized sampling and a sample-to-insert rate limiter for DQN training', 'build a launchpad program from a DistributedDQN agent using the build method', 'test the distributed DQN agent runs for steps without crashing on Atari', 'launch a distributed agent program in multi-threaded test mode with launchpad', 'step the learner node forward to process replay buffer updates', 'build a sonnet MLP network with flatten layer for a discrete action space', 'test the DQN agent by running an environment loop with a fake discrete environment', 'create a fake discrete environment with configurable actions, observations, and episode length', 'construct a DQN agent with an environment spec, neural network, and replay buffer settings', 'run an acme environment loop with a DQN agent for a specified number of episodes', 'build a DQNLearner instance with online and target networks, discount, learning rate, and a TensorFlow dataset', 'run a single learning step on the DQNLearner to perform SGD and update replay buffer priorities', 'create an Adam optimizer for the DQN network using sonnet with a specified learning rate', 'review the double Q-learning loss computation using trfl with Huber loss and importance sampling weights', 'summarize the DQNLearner checkpointable state including network, target network, optimizer, and step count']
```

Usage

```
{'build_dqn_learner': 'build a DQNLearner instance with online and target networks, discount, learning rate, and a TensorFlow dataset', 'run_dqn_step': 'run a single learning step on the DQNLearner to perform SGD and update replay buffer priorities', 'create_dqn_optimizer': 'create an Adam optimizer for the DQN network using sonnet with a specified learning rate', 'review_double_qlearning': 'review the double Q-learning loss computation using trfl with Huber loss and importance sampling weights', 'summarize_dqn_state': 'summarize the DQNLearner checkpointable state including network, target network, optimizer, and step count'}
```


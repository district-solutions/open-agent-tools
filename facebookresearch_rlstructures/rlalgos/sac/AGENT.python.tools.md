# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlalgos/sac/agent.py

Prompts

```
['create a SACAgent with a policy model and action dimension for reinforcement learning', 'run one step of the SACAgent to sample stochastic or greedy actions from observations', 'build a SACPolicy neural network that outputs mean and std for a diagonal Gaussian actor', 'build a SACQ critic network that estimates Q-values from state-action pairs', 'create a SquashedNormal distribution that applies tanh transform to a base Normal distribution', 'create a ContinuousCartPoleEnv instance to simulate a continuous action space cart-pole environment', 'step the ContinuousCartPoleEnv with a continuous action value between -1.0 and 1.0', 'reset the ContinuousCartPoleEnv to a random initial state within small bounds', 'render the ContinuousCartPoleEnv in human or rgb_array mode using gym rendering', 'seed the ContinuousCartPoleEnv with a random seed for reproducible simulations', 'run the SAC reinforcement learning experiment on the ContinuousCartPole environment with configurable hyperparameters', 'create a ContinuousCartPole Gym environment instance for reinforcement learning training', 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnv container', 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnvInf container for training', 'create an SACAgent instance with a given policy and optional action dimension', 'create a SAC agent with config, environment creators, and policy model for continuous control', 'run the SAC training loop with replay buffer, Q-networks, and policy optimization', 'create a ReplayBuffer to store and sample temporal transitions for experience replay', 'compute the Q-network loss using target Q-values and soft update for twin critics', 'compute the policy loss using reparameterization trick and entropy regularization for SAC']
```

Usage

```
{'create_SACAgent': 'create a SACAgent with a policy model and action dimension for reinforcement learning', 'run_SACAgent_call': 'run one step of the SACAgent to sample stochastic or greedy actions from observations', 'build_SACPolicy': 'build a SACPolicy neural network that outputs mean and std for a diagonal Gaussian actor', 'build_SACQ': 'build a SACQ critic network that estimates Q-values from state-action pairs', 'create_SquashedNormal': 'create a SquashedNormal distribution that applies tanh transform to a base Normal distribution'}
```

## File: facebookresearch_rlstructures/rlalgos/sac/continuouscartopole.py

Prompts

```
['create a SACAgent with a policy model and action dimension for reinforcement learning', 'run one step of the SACAgent to sample stochastic or greedy actions from observations', 'build a SACPolicy neural network that outputs mean and std for a diagonal Gaussian actor', 'build a SACQ critic network that estimates Q-values from state-action pairs', 'create a SquashedNormal distribution that applies tanh transform to a base Normal distribution', 'create a ContinuousCartPoleEnv instance to simulate a continuous action space cart-pole environment', 'step the ContinuousCartPoleEnv with a continuous action value between -1.0 and 1.0', 'reset the ContinuousCartPoleEnv to a random initial state within small bounds', 'render the ContinuousCartPoleEnv in human or rgb_array mode using gym rendering', 'seed the ContinuousCartPoleEnv with a random seed for reproducible simulations', 'run the SAC reinforcement learning experiment on the ContinuousCartPole environment with configurable hyperparameters', 'create a ContinuousCartPole Gym environment instance for reinforcement learning training', 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnv container', 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnvInf container for training', 'create an SACAgent instance with a given policy and optional action dimension', 'create a SAC agent with config, environment creators, and policy model for continuous control', 'run the SAC training loop with replay buffer, Q-networks, and policy optimization', 'create a ReplayBuffer to store and sample temporal transitions for experience replay', 'compute the Q-network loss using target Q-values and soft update for twin critics', 'compute the policy loss using reparameterization trick and entropy regularization for SAC']
```

Usage

```
{'create_continuous_cartpole_env': 'create a ContinuousCartPoleEnv instance to simulate a continuous action space cart-pole environment', 'step_cartpole_env': 'step the ContinuousCartPoleEnv with a continuous action value between -1.0 and 1.0', 'reset_cartpole_env': 'reset the ContinuousCartPoleEnv to a random initial state within small bounds', 'render_cartpole_env': 'render the ContinuousCartPoleEnv in human or rgb_array mode using gym rendering', 'seed_cartpole_env': 'seed the ContinuousCartPoleEnv with a random seed for reproducible simulations'}
```

## File: facebookresearch_rlstructures/rlalgos/sac/run_cartpole.py

Prompts

```
['create a SACAgent with a policy model and action dimension for reinforcement learning', 'run one step of the SACAgent to sample stochastic or greedy actions from observations', 'build a SACPolicy neural network that outputs mean and std for a diagonal Gaussian actor', 'build a SACQ critic network that estimates Q-values from state-action pairs', 'create a SquashedNormal distribution that applies tanh transform to a base Normal distribution', 'create a ContinuousCartPoleEnv instance to simulate a continuous action space cart-pole environment', 'step the ContinuousCartPoleEnv with a continuous action value between -1.0 and 1.0', 'reset the ContinuousCartPoleEnv to a random initial state within small bounds', 'render the ContinuousCartPoleEnv in human or rgb_array mode using gym rendering', 'seed the ContinuousCartPoleEnv with a random seed for reproducible simulations', 'run the SAC reinforcement learning experiment on the ContinuousCartPole environment with configurable hyperparameters', 'create a ContinuousCartPole Gym environment instance for reinforcement learning training', 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnv container', 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnvInf container for training', 'create an SACAgent instance with a given policy and optional action dimension', 'create a SAC agent with config, environment creators, and policy model for continuous control', 'run the SAC training loop with replay buffer, Q-networks, and policy optimization', 'create a ReplayBuffer to store and sample temporal transitions for experience replay', 'compute the Q-network loss using target Q-values and soft update for twin critics', 'compute the policy loss using reparameterization trick and entropy regularization for SAC']
```

Usage

```
{'run_sac_cartpole_experiment': 'run the SAC reinforcement learning experiment on the ContinuousCartPole environment with configurable hyperparameters', 'create_gym_env': 'create a ContinuousCartPole Gym environment instance for reinforcement learning training', 'create_env': 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnv container', 'create_train_env': 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnvInf container for training', 'create_agent': 'create an SACAgent instance with a given policy and optional action dimension'}
```

## File: facebookresearch_rlstructures/rlalgos/sac/sac.py

Prompts

```
['create a SACAgent with a policy model and action dimension for reinforcement learning', 'run one step of the SACAgent to sample stochastic or greedy actions from observations', 'build a SACPolicy neural network that outputs mean and std for a diagonal Gaussian actor', 'build a SACQ critic network that estimates Q-values from state-action pairs', 'create a SquashedNormal distribution that applies tanh transform to a base Normal distribution', 'create a ContinuousCartPoleEnv instance to simulate a continuous action space cart-pole environment', 'step the ContinuousCartPoleEnv with a continuous action value between -1.0 and 1.0', 'reset the ContinuousCartPoleEnv to a random initial state within small bounds', 'render the ContinuousCartPoleEnv in human or rgb_array mode using gym rendering', 'seed the ContinuousCartPoleEnv with a random seed for reproducible simulations', 'run the SAC reinforcement learning experiment on the ContinuousCartPole environment with configurable hyperparameters', 'create a ContinuousCartPole Gym environment instance for reinforcement learning training', 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnv container', 'create a batch of TimeLimit-wrapped Gym environments wrapped in a GymEnvInf container for training', 'create an SACAgent instance with a given policy and optional action dimension', 'create a SAC agent with config, environment creators, and policy model for continuous control', 'run the SAC training loop with replay buffer, Q-networks, and policy optimization', 'create a ReplayBuffer to store and sample temporal transitions for experience replay', 'compute the Q-network loss using target Q-values and soft update for twin critics', 'compute the policy loss using reparameterization trick and entropy regularization for SAC']
```

Usage

```
{'create_sac_agent': 'create a SAC agent with config, environment creators, and policy model for continuous control', 'run_sac_training': 'run the SAC training loop with replay buffer, Q-networks, and policy optimization', 'create_replay_buffer': 'create a ReplayBuffer to store and sample temporal transitions for experience replay', 'compute_q_loss': 'compute the Q-network loss using target Q-values and soft update for twin critics', 'compute_policy_loss': 'compute the policy loss using reparameterization trick and entropy regularization for SAC'}
```


# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/rl/ddpg/agents.py

Prompts

```
['create an ActionMLPAgent that outputs clipped tanh actions with epsilon noise for DDPG policy', 'create a QMLPAgent that computes Q-values from concatenated observation and action inputs', 'create an OUNoise process to generate correlated Gaussian noise for DDPG exploration', 'build a multi-layer perceptron network with configurable sizes and activation functions', 'create a Gym environment wrapped with TimeLimit for a given env name and max steps', 'run the DDPG training loop with a Q agent, action agent, logger, and config', 'soft update target network parameters using a tau interpolation factor', 'move an agent state dict to a specified device like cpu or cuda', 'run the Hydra main entry point to instantiate agents and start DDPG training', 'review the run_ddpg function to understand the DDPG training loop and loss computation']
```

Usage

```
{'create_action_mlp_agent': 'create an ActionMLPAgent that outputs clipped tanh actions with epsilon noise for DDPG policy', 'create_q_mlp_agent': 'create a QMLPAgent that computes Q-values from concatenated observation and action inputs', 'create_ou_noise': 'create an OUNoise process to generate correlated Gaussian noise for DDPG exploration', 'build_mlp_network': 'build a multi-layer perceptron network with configurable sizes and activation functions', 'create_gym_env': 'create a Gym environment wrapped with TimeLimit for a given env name and max steps'}
```

## File: facebookresearch_salina/salina_examples/rl/ddpg/ddpg.py

Prompts

```
['create an ActionMLPAgent that outputs clipped tanh actions with epsilon noise for DDPG policy', 'create a QMLPAgent that computes Q-values from concatenated observation and action inputs', 'create an OUNoise process to generate correlated Gaussian noise for DDPG exploration', 'build a multi-layer perceptron network with configurable sizes and activation functions', 'create a Gym environment wrapped with TimeLimit for a given env name and max steps', 'run the DDPG training loop with a Q agent, action agent, logger, and config', 'soft update target network parameters using a tau interpolation factor', 'move an agent state dict to a specified device like cpu or cuda', 'run the Hydra main entry point to instantiate agents and start DDPG training', 'review the run_ddpg function to understand the DDPG training loop and loss computation']
```

Usage

```
{'run_ddpg_training': 'run the DDPG training loop with a Q agent, action agent, logger, and config', 'soft_update_params': 'soft update target network parameters using a tau interpolation factor', 'state_dict_device': 'move an agent state dict to a specified device like cpu or cuda', 'main_entry': 'run the Hydra main entry point to instantiate agents and start DDPG training', 'review_run_ddpg': 'review the run_ddpg function to understand the DDPG training loop and loss computation'}
```


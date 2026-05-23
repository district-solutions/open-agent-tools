# Agent Python Tools

- repo: facebookresearch/salina
- repo_uri: https://github.com/facebookresearch/salina

## File: facebookresearch_salina/salina_examples/offline_rl/bc/agents.py

Prompts

```
['create a gym environment from a d4rl env name with a time limit wrapper', 'create a d4rl Atari gym environment with stacked observations and a time limit', 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'create an ActionMLPAgent that predicts continuous actions from observations using an MLP and tanh output', 'create an AtariAgent that samples discrete actions from a Dueling CNN DQN network', 'run behavior cloning training on a d4rl offline RL dataset using MSE loss', 'run the BC offline RL training pipeline via hydra config and multiprocessing spawn', 'review the run_bc function to understand the BC training loop with async evaluation', 'review the _state_dict helper that moves agent state dict tensors to a target device', 'refactor the run_bc function to support a different loss function beyond MSE', 'run behavior cloning with discrete actions on a D4RL Atari environment using Hydra config', 'run the behavior cloning training loop with an action agent, logger, and config object', 'run the main entry point that instantiates a logger and action agent then calls run_bc']
```

Usage

```
{'create_d4rl_env': 'create a gym environment from a d4rl env name with a time limit wrapper', 'create_d4rl_atari_env': 'create a d4rl Atari gym environment with stacked observations and a time limit', 'build_mlp_network': 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'create_action_mlp_agent': 'create an ActionMLPAgent that predicts continuous actions from observations using an MLP and tanh output', 'create_atari_agent': 'create an AtariAgent that samples discrete actions from a Dueling CNN DQN network'}
```

## File: facebookresearch_salina/salina_examples/offline_rl/bc/bc.py

Prompts

```
['create a gym environment from a d4rl env name with a time limit wrapper', 'create a d4rl Atari gym environment with stacked observations and a time limit', 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'create an ActionMLPAgent that predicts continuous actions from observations using an MLP and tanh output', 'create an AtariAgent that samples discrete actions from a Dueling CNN DQN network', 'run behavior cloning training on a d4rl offline RL dataset using MSE loss', 'run the BC offline RL training pipeline via hydra config and multiprocessing spawn', 'review the run_bc function to understand the BC training loop with async evaluation', 'review the _state_dict helper that moves agent state dict tensors to a target device', 'refactor the run_bc function to support a different loss function beyond MSE', 'run behavior cloning with discrete actions on a D4RL Atari environment using Hydra config', 'run the behavior cloning training loop with an action agent, logger, and config object', 'run the main entry point that instantiates a logger and action agent then calls run_bc']
```

Usage

```
{'run_bc_training': 'run behavior cloning training on a d4rl offline RL dataset using MSE loss', 'run_main_entry': 'run the BC offline RL training pipeline via hydra config and multiprocessing spawn', 'review_run_bc': 'review the run_bc function to understand the BC training loop with async evaluation', 'review_state_dict': 'review the _state_dict helper that moves agent state dict tensors to a target device', 'refactor_run_bc': 'refactor the run_bc function to support a different loss function beyond MSE'}
```

## File: facebookresearch_salina/salina_examples/offline_rl/bc/bc_discrete.py

Prompts

```
['create a gym environment from a d4rl env name with a time limit wrapper', 'create a d4rl Atari gym environment with stacked observations and a time limit', 'build a multi-layer perceptron with configurable layer sizes and activation functions', 'create an ActionMLPAgent that predicts continuous actions from observations using an MLP and tanh output', 'create an AtariAgent that samples discrete actions from a Dueling CNN DQN network', 'run behavior cloning training on a d4rl offline RL dataset using MSE loss', 'run the BC offline RL training pipeline via hydra config and multiprocessing spawn', 'review the run_bc function to understand the BC training loop with async evaluation', 'review the _state_dict helper that moves agent state dict tensors to a target device', 'refactor the run_bc function to support a different loss function beyond MSE', 'run behavior cloning with discrete actions on a D4RL Atari environment using Hydra config', 'run the behavior cloning training loop with an action agent, logger, and config object', 'run the main entry point that instantiates a logger and action agent then calls run_bc']
```

Usage

```
{'run_bc_discrete': 'run behavior cloning with discrete actions on a D4RL Atari environment using Hydra config', 'run_run_bc': 'run the behavior cloning training loop with an action agent, logger, and config object', 'run_main': 'run the main entry point that instantiates a logger and action agent then calls run_bc', 'review_run_bc': 'review the run_bc function that trains a behavior cloning agent using cross-entropy loss on replay buffer data', 'review_state_dict': 'review the _state_dict helper that moves an agent state dict tensors to a specified device'}
```


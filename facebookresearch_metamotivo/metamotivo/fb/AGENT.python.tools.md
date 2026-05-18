# Agent Python Tools

- repo: facebookresearch/metamotivo
- repo_uri: https://github.com/facebookresearch/metamotivo

## File: facebookresearch_metamotivo/metamotivo/fb/agent.py

Prompts

```
['create an FBAgent instance by passing config kwargs for forward-backward model training', 'call FBAgent.act with an observation tensor and z latent to get the agent action', 'run one training step by calling FBAgent.update with a replay buffer and step count', 'load a saved FBAgent from a directory path using the FBAgent.load class method', 'save the FBAgent model and optimizer state to an output folder using FBAgent.save', 'create an FBModel instance with obs_dim and action_dim kwargs to initialize backward, forward, and actor networks', 'load a pretrained FBModel from a directory path using the FBModel.load class method', 'save an FBModel to a folder as safetensors along with its config as JSON', 'run reward-weighted backward inference on next observations to compute a goal vector z', 'run goal inference on next observations to extract and project a latent goal vector z']
```

Usage

```
{'create_FBAgent': 'create an FBAgent instance by passing config kwargs for forward-backward model training', 'act_FBAgent': 'call FBAgent.act with an observation tensor and z latent to get the agent action', 'update_FBAgent': 'run one training step by calling FBAgent.update with a replay buffer and step count', 'load_FBAgent': 'load a saved FBAgent from a directory path using the FBAgent.load class method', 'save_FBAgent': 'save the FBAgent model and optimizer state to an output folder using FBAgent.save'}
```

## File: facebookresearch_metamotivo/metamotivo/fb/model.py

Prompts

```
['create an FBAgent instance by passing config kwargs for forward-backward model training', 'call FBAgent.act with an observation tensor and z latent to get the agent action', 'run one training step by calling FBAgent.update with a replay buffer and step count', 'load a saved FBAgent from a directory path using the FBAgent.load class method', 'save the FBAgent model and optimizer state to an output folder using FBAgent.save', 'create an FBModel instance with obs_dim and action_dim kwargs to initialize backward, forward, and actor networks', 'load a pretrained FBModel from a directory path using the FBModel.load class method', 'save an FBModel to a folder as safetensors along with its config as JSON', 'run reward-weighted backward inference on next observations to compute a goal vector z', 'run goal inference on next observations to extract and project a latent goal vector z']
```

Usage

```
{'create_FBModel': 'create an FBModel instance with obs_dim and action_dim kwargs to initialize backward, forward, and actor networks', 'load_FBModel': 'load a pretrained FBModel from a directory path using the FBModel.load class method', 'save_FBModel': 'save an FBModel to a folder as safetensors along with its config as JSON', 'run_reward_inference': 'run reward-weighted backward inference on next observations to compute a goal vector z', 'run_goal_inference': 'run goal inference on next observations to extract and project a latent goal vector z'}
```


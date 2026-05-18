# Agent Python Tools

- repo: facebookresearch/metamotivo
- repo_uri: https://github.com/facebookresearch/metamotivo

## File: facebookresearch_metamotivo/examples/fb_train_dmc.py

Prompts

```
['run the FB agent training loop for DMC domains like walker, cheetah, or quadruped using tyro CLI', 'create an FBAgentConfig with architecture and optimizer hyperparameters for a given DMC domain and task', 'load episode data from NPZ buffer files into a dictionary of observation, action, and physics arrays', 'evaluate a trained FB agent on DMC tasks by running episodes and computing mean and std reward', 'infer latent z codes from replay buffer samples by simulating physics and computing task rewards', 'run the FBcprAgent training loop on Humenv with expert trajectories and online parallel environments', 'load expert motion trajectories from H5 files into a TrajectoryBuffer for offline RL training', 'configure training hyperparameters including buffer size, parallel envs, evaluation tasks, and W&B logging', 'evaluate the trained agent with reward and tracking evaluations on Humenv benchmark tasks', 'set random seeds across PyTorch, CUDA, NumPy, and Python random for reproducibility']
```

Usage

```
{'run_fb_train_dmc': 'run the FB agent training loop for DMC domains like walker, cheetah, or quadruped using tyro CLI', 'create_agent_config': 'create an FBAgentConfig with architecture and optimizer hyperparameters for a given DMC domain and task', 'load_data_from_buffer': 'load episode data from NPZ buffer files into a dictionary of observation, action, and physics arrays', 'eval_workspace_agent': 'evaluate a trained FB agent on DMC tasks by running episodes and computing mean and std reward', 'reward_inference_workspace': 'infer latent z codes from replay buffer samples by simulating physics and computing task rewards'}
```

## File: facebookresearch_metamotivo/examples/fbcpr_train_humenv.py

Prompts

```
['run the FB agent training loop for DMC domains like walker, cheetah, or quadruped using tyro CLI', 'create an FBAgentConfig with architecture and optimizer hyperparameters for a given DMC domain and task', 'load episode data from NPZ buffer files into a dictionary of observation, action, and physics arrays', 'evaluate a trained FB agent on DMC tasks by running episodes and computing mean and std reward', 'infer latent z codes from replay buffer samples by simulating physics and computing task rewards', 'run the FBcprAgent training loop on Humenv with expert trajectories and online parallel environments', 'load expert motion trajectories from H5 files into a TrajectoryBuffer for offline RL training', 'configure training hyperparameters including buffer size, parallel envs, evaluation tasks, and W&B logging', 'evaluate the trained agent with reward and tracking evaluations on Humenv benchmark tasks', 'set random seeds across PyTorch, CUDA, NumPy, and Python random for reproducibility']
```

Usage

```
{'run_fbcpr_training': 'run the FBcprAgent training loop on Humenv with expert trajectories and online parallel environments', 'load_expert_trajectories': 'load expert motion trajectories from H5 files into a TrajectoryBuffer for offline RL training', 'configure_trainconfig': 'configure training hyperparameters including buffer size, parallel envs, evaluation tasks, and W&B logging', 'evaluate_workspace': 'evaluate the trained agent with reward and tracking evaluations on Humenv benchmark tasks', 'set_seed_everywhere': 'set random seeds across PyTorch, CUDA, NumPy, and Python random for reproducibility'}
```


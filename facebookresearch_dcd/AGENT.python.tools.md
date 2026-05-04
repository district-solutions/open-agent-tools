# Agent Python Tools

- repo: facebookresearch/dcd
- repo_uri: https://github.com/facebookresearch/dcd

## File: facebookresearch_dcd/eval.py

Prompts

```
['run the eval module with python -m eval --env_names MultiGrid-Labyrinth-v0 --xpid latest --base_path ~/logs/dcd', 'create an Evaluator instance with env_names, num_processes, and num_episodes then call evaluate with an agent', 'call Evaluator.make_env with an env_name string to create a wrapped gym environment for evaluation', 'call Evaluator.wrap_venv on a vectorized env to add VecMonitor and VecPreprocessImageWrapper', 'call parse_args to get an argparse namespace with evaluation flags like benchmark, xpid, and num_episodes', 'run the adversarial reinforcement learning training loop with configurable agents and environments', 'create parallel vectorized gym environments for multi-process training using create_parallel_env', 'create an RL agent with make_agent given an environment, args, and device', 'save and load training checkpoints using safe_checkpoint to persist runner state', 'evaluate a trained agent across test environments using the Evaluator class']
```

Usage

```
{'run_eval_cli': 'run the eval module with python -m eval --env_names MultiGrid-Labyrinth-v0 --xpid latest --base_path ~/logs/dcd', 'run_evaluator_class': 'create an Evaluator instance with env_names, num_processes, and num_episodes then call evaluate with an agent', 'run_make_env': 'call Evaluator.make_env with an env_name string to create a wrapped gym environment for evaluation', 'run_wrap_venv': 'call Evaluator.wrap_venv on a vectorized env to add VecMonitor and VecPreprocessImageWrapper', 'run_parse_args': 'call parse_args to get an argparse namespace with evaluation flags like benchmark, xpid, and num_episodes'}
```

## File: facebookresearch_dcd/train.py

Prompts

```
['run the eval module with python -m eval --env_names MultiGrid-Labyrinth-v0 --xpid latest --base_path ~/logs/dcd', 'create an Evaluator instance with env_names, num_processes, and num_episodes then call evaluate with an agent', 'call Evaluator.make_env with an env_name string to create a wrapped gym environment for evaluation', 'call Evaluator.wrap_venv on a vectorized env to add VecMonitor and VecPreprocessImageWrapper', 'call parse_args to get an argparse namespace with evaluation flags like benchmark, xpid, and num_episodes', 'run the adversarial reinforcement learning training loop with configurable agents and environments', 'create parallel vectorized gym environments for multi-process training using create_parallel_env', 'create an RL agent with make_agent given an environment, args, and device', 'save and load training checkpoints using safe_checkpoint to persist runner state', 'evaluate a trained agent across test environments using the Evaluator class']
```

Usage

```
{'run_adversarial_rl_training': 'run the adversarial reinforcement learning training loop with configurable agents and environments', 'create_parallel_env': 'create parallel vectorized gym environments for multi-process training using create_parallel_env', 'make_agent': 'create an RL agent with make_agent given an environment, args, and device', 'checkpoint_model': 'save and load training checkpoints using safe_checkpoint to persist runner state', 'evaluate_agent': 'evaluate a trained agent across test environments using the Evaluator class'}
```


# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/examples/on_policy_files/nocturne_runner.py

Prompts

```
['run the PPO training loop for Nocturne multi-agent environments using the main function with a Hydra config', 'create a NocturneSharedRunner instance with a config dict containing envs, eval_envs, render_envs, num_agents, device, and logdir', 'build a vectorized training environment using make_train_env with a config that sets n_rollout_threads for parallel rollouts', 'build a vectorized evaluation environment using make_eval_env with a config that sets n_eval_rollout_threads for parallel eval rollouts', 'review the NocturneSharedRunner run method which handles warmup, data collection, buffer insertion, training updates, logging, eval, and rendering']
```

Usage

```
{'run_PPO_training': 'run the PPO training loop for Nocturne multi-agent environments using the main function with a Hydra config', 'create_NocturneSharedRunner': 'create a NocturneSharedRunner instance with a config dict containing envs, eval_envs, render_envs, num_agents, device, and logdir', 'build_train_env': 'build a vectorized training environment using make_train_env with a config that sets n_rollout_threads for parallel rollouts', 'build_eval_env': 'build a vectorized evaluation environment using make_eval_env with a config that sets n_eval_rollout_threads for parallel eval rollouts', 'review_NocturneSharedRunner_run': 'review the NocturneSharedRunner run method which handles warmup, data collection, buffer insertion, training updates, logging, eval, and rendering'}
```


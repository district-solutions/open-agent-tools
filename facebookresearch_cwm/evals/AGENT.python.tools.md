# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/evals/args.py

Prompts

```
['create an RLEvalArgs dataclass to configure RL evaluation with dump directory, seed, and rollout threads', 'create a FastGenArgs dataclass to configure fast generation with temperature, top_p, and batch size', 'create a SetupArgs dataclass to configure PyTorch spawn method, CUDA precision, and autograd anomaly detection', 'create a TokenizerArgs dataclass to configure tokenizer name and file path for evaluation', 'build a JsonlMetricsLogger instance from a dump directory path and tag string', 'run RL evaluation rollouts across multiple tasks using ImpGen and FastGen with distributed generation', 'evaluate a model from a checkpoint directory by running RL rollouts and aggregating metrics', 'aggregate terminal rewards and outcome metrics for a single task across all data sources', 'aggregate evaluation metrics per task from dumped samples and log results to the metrics logger', 'setup a 2D device mesh with data parallel and tensor parallel dimensions for distributed evaluation']
```

Usage

```
{'create_RLEvalArgs': 'create an RLEvalArgs dataclass to configure RL evaluation with dump directory, seed, and rollout threads', 'create_FastGenArgs': 'create a FastGenArgs dataclass to configure fast generation with temperature, top_p, and batch size', 'create_SetupArgs': 'create a SetupArgs dataclass to configure PyTorch spawn method, CUDA precision, and autograd anomaly detection', 'create_TokenizerArgs': 'create a TokenizerArgs dataclass to configure tokenizer name and file path for evaluation', 'build_metrics_logger': 'build a JsonlMetricsLogger instance from a dump directory path and tag string'}
```

## File: facebookresearch_cwm/evals/main.py

Prompts

```
['create an RLEvalArgs dataclass to configure RL evaluation with dump directory, seed, and rollout threads', 'create a FastGenArgs dataclass to configure fast generation with temperature, top_p, and batch size', 'create a SetupArgs dataclass to configure PyTorch spawn method, CUDA precision, and autograd anomaly detection', 'create a TokenizerArgs dataclass to configure tokenizer name and file path for evaluation', 'build a JsonlMetricsLogger instance from a dump directory path and tag string', 'run RL evaluation rollouts across multiple tasks using ImpGen and FastGen with distributed generation', 'evaluate a model from a checkpoint directory by running RL rollouts and aggregating metrics', 'aggregate terminal rewards and outcome metrics for a single task across all data sources', 'aggregate evaluation metrics per task from dumped samples and log results to the metrics logger', 'setup a 2D device mesh with data parallel and tensor parallel dimensions for distributed evaluation']
```

Usage

```
{'run_rl_evals': 'run RL evaluation rollouts across multiple tasks using ImpGen and FastGen with distributed generation', 'eval_model_from_checkpoint': 'evaluate a model from a checkpoint directory by running RL rollouts and aggregating metrics', 'aggregate_metrics': 'aggregate terminal rewards and outcome metrics for a single task across all data sources', 'aggregate_by_task': 'aggregate evaluation metrics per task from dumped samples and log results to the metrics logger', 'setup_mesh': 'setup a 2D device mesh with data parallel and tensor parallel dimensions for distributed evaluation'}
```


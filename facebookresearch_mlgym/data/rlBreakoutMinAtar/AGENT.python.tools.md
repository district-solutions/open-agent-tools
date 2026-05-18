# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/rlBreakoutMinAtar/evaluate.py

Prompts

```
['run the evaluation script to evaluate RL agent checkpoints on Breakout-MinAtar and print reward metrics', 'load a trained neural network model and parameters from a pickle checkpoint file', 'run a batched rollout of 256 parallel environment episodes using a JAX JIT-compiled policy', 'review the rollout_batch function that uses jax.lax.scan to step environments and accumulate rewards', 'refactor load_neural_network to support loading models from different checkpoint formats']
```

Usage

```
{'run_evaluation': 'run the evaluation script to evaluate RL agent checkpoints on Breakout-MinAtar and print reward metrics', 'load_neural_network': 'load a trained neural network model and parameters from a pickle checkpoint file', 'rollout_batch': 'run a batched rollout of 256 parallel environment episodes using a JAX JIT-compiled policy', 'review_rollout_batch': 'review the rollout_batch function that uses jax.lax.scan to step environments and accumulate rewards', 'refactor_load_neural_network': 'refactor load_neural_network to support loading models from different checkpoint formats'}
```


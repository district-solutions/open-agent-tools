# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/rlMountainCarContinuousReinforce/evaluate.py

Prompts

```
['run the evaluate module to evaluate RL MountainCarContinuous checkpoints and print reward metrics', 'load a neural network model and parameters from a saved checkpoint pickle file', 'run a batched rollout of 256 parallel MountainCarContinuous episodes using JAX JIT compilation', 'review the rollout_batch function that uses jax.lax.scan to step environments and accumulate rewards', 'refactor load_neural_network to support loading models from different checkpoint formats']
```

Usage

```
{'run_evaluation': 'run the evaluate module to evaluate RL MountainCarContinuous checkpoints and print reward metrics', 'load_neural_network': 'load a neural network model and parameters from a saved checkpoint pickle file', 'rollout_batch': 'run a batched rollout of 256 parallel MountainCarContinuous episodes using JAX JIT compilation', 'review_rollout_batch': 'review the rollout_batch function that uses jax.lax.scan to step environments and accumulate rewards', 'refactor_load_neural_network': 'refactor load_neural_network to support loading models from different checkpoint formats'}
```


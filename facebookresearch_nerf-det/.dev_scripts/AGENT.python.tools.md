# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/.dev_scripts/gather_models.py

Prompts

```
['run the script to gather benchmarked models from a root directory and prepare them for upload', 'process a PyTorch checkpoint by removing the optimizer and renaming with a SHA256 hash', 'parse a training log JSON file to extract the best validation results and peak memory usage', 'determine the final training epoch number from a config filename using schedule lookup patterns', 'identify which dataset a model was trained on by matching keywords in the log file path']
```

Usage

```
{'run_gather_models': 'run the script to gather benchmarked models from a root directory and prepare them for upload', 'process_checkpoint': 'process a PyTorch checkpoint by removing the optimizer and renaming with a SHA256 hash', 'get_best_results': 'parse a training log JSON file to extract the best validation results and peak memory usage', 'get_final_epoch': 'determine the final training epoch number from a config filename using schedule lookup patterns', 'get_model_dataset': 'identify which dataset a model was trained on by matching keywords in the log file path'}
```


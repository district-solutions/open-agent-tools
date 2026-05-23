# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/_internal_patches.py

Prompts

```
['create a ModelCheckpoint callback that strips Meta-internal kwargs before delegating to PyTorch Lightning', 'create a TensorBoardLogger that strips Meta-internal kwargs before delegating to PyTorch Lightning', 'call the log_run no-op stub function to conditionally log a training run', 'review the ModelCheckpoint wrapper to understand how it filters internal-only arguments', 'review the TensorBoardLogger wrapper to understand how it filters internal-only arguments']
```

Usage

```
{'create_modelcheckpoint': 'create a ModelCheckpoint callback that strips Meta-internal kwargs before delegating to PyTorch Lightning', 'create_tensorboardlogger': 'create a TensorBoardLogger that strips Meta-internal kwargs before delegating to PyTorch Lightning', 'call_log_run': 'call the log_run no-op stub function to conditionally log a training run', 'review_modelcheckpoint': 'review the ModelCheckpoint wrapper to understand how it filters internal-only arguments', 'review_tensorboardlogger': 'review the TensorBoardLogger wrapper to understand how it filters internal-only arguments'}
```


# Agent Python Tools

- repo: facebookresearch/dci
- repo_uri: https://github.com/facebookresearch/dci

## File: facebookresearch_dci/reproduction/densely_captioned_images/repro/train/sweeps/train_sweep.py

Prompts

```
['run the CLIP training hyperparameter sweep across multiple configurations on a SLURM cluster', 'run makeGrid to compute the Cartesian product of a dictionary of parameter lists into a list of dicts', 'create a CLIPAndNegConfig object with LoRA, learning rate, batch size, and loss parameters for training', 'submit a CLIPTrainJob to a submitit AutoExecutor with SLURM GPU node parameters', 'review the train_sweep module to understand the hyperparameter grid and SLURM job submission logic']
```

Usage

```
{'run_train_sweep': 'run the CLIP training hyperparameter sweep across multiple configurations on a SLURM cluster', 'run_makeGrid': 'run makeGrid to compute the Cartesian product of a dictionary of parameter lists into a list of dicts', 'create_train_sweep_config': 'create a CLIPAndNegConfig object with LoRA, learning rate, batch size, and loss parameters for training', 'submit_CLIPTrainJob': 'submit a CLIPTrainJob to a submitit AutoExecutor with SLURM GPU node parameters', 'review_train_sweep': 'review the train_sweep module to understand the hyperparameter grid and SLURM job submission logic'}
```


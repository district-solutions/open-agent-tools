# Agent Python Tools

- repo: facebookresearch/adjointsampling
- repo_uri: https://github.com/facebookresearch/adjoint_sampling

## File: facebookresearch_adjointsampling/adjoint_sampling/eval_loop.py

Prompts

```
['run the evaluation function to integrate SDE, compute SOC loss, and return energy visualization', 'save generated molecule batches and outputs to XYZ files with atomic symbols and positions', 'compute the SOC loss for controls, graph states, and energy outputs using noise schedule', 'visualize up to 16 molecule conformations from graph states using the atomic number table', 'evaluate batch recall and coverage metrics for generated states against conformer reference data', 'run one training epoch of the adjoint sampling controller with noise schedule and optimizer', 'run one training epoch in pretrain mode using only the Brownian motion loss', 'run one training epoch learning torsion angles using adjoint score target torsion', 'get the current learning rate from the first param group of a PyTorch optimizer', 'review the train_one_epoch function which computes adjoint loss and BM loss for score matching']
```

Usage

```
{'run_evaluation_loop': 'run the evaluation function to integrate SDE, compute SOC loss, and return energy visualization', 'save_molecule_conformations_to_xyz': 'save generated molecule batches and outputs to XYZ files with atomic symbols and positions', 'compute_SOC_loss': 'compute the SOC loss for controls, graph states, and energy outputs using noise schedule', 'visualize_molecule_conformations': 'visualize up to 16 molecule conformations from graph states using the atomic number table', 'evaluate_batch_coverage': 'evaluate batch recall and coverage metrics for generated states against conformer reference data'}
```

## File: facebookresearch_adjointsampling/adjoint_sampling/train_loop.py

Prompts

```
['run the evaluation function to integrate SDE, compute SOC loss, and return energy visualization', 'save generated molecule batches and outputs to XYZ files with atomic symbols and positions', 'compute the SOC loss for controls, graph states, and energy outputs using noise schedule', 'visualize up to 16 molecule conformations from graph states using the atomic number table', 'evaluate batch recall and coverage metrics for generated states against conformer reference data', 'run one training epoch of the adjoint sampling controller with noise schedule and optimizer', 'run one training epoch in pretrain mode using only the Brownian motion loss', 'run one training epoch learning torsion angles using adjoint score target torsion', 'get the current learning rate from the first param group of a PyTorch optimizer', 'review the train_one_epoch function which computes adjoint loss and BM loss for score matching']
```

Usage

```
{'run_train_one_epoch': 'run one training epoch of the adjoint sampling controller with noise schedule and optimizer', 'run_train_one_epoch_pretrain': 'run one training epoch in pretrain mode using only the Brownian motion loss', 'run_train_one_epoch_torsions': 'run one training epoch learning torsion angles using adjoint score target torsion', 'get_lr': 'get the current learning rate from the first param group of a PyTorch optimizer', 'review_train_one_epoch': 'review the train_one_epoch function which computes adjoint loss and BM loss for score matching'}
```


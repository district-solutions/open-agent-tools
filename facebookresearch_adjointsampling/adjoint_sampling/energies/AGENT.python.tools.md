# Agent Python Tools

- repo: facebookresearch/adjointsampling
- repo_uri: https://github.com/facebookresearch/adjoint_sampling

## File: facebookresearch_adjointsampling/adjoint_sampling/energies/fairchem_energy.py

Prompts

```
['create a FairChemEnergy module with a custom model checkpoint, tau, alpha, and device settings', 'call the FairChemEnergy module on a batch to compute energy and forces with optional regularization', 'use the wandb_mode_disabled context manager to temporarily disable WANDB_MODE during model initialization', 'run the bond_regularizer method on a batch to compute regularization energy and gradient forces', 'review the FairChemEnergy __call__ method to understand batch preprocessing and prediction denormalization', 'run bond_structure_regularizer to compute bond and no-bond constraint penalties for molecular positions', 'create a bond constraint penalty using relu on bond norms exceeding bond limits', 'create a no-bond constraint penalty using relu on bond norms below bond limits', 'compute per-system regularization energy by scattering bond constraints across batched molecular graphs', 'refactor bond_structure_regularizer to use huber_loss instead of relu for smoother constraint penalties']
```

Usage

```
{'create_FairChemEnergy': 'create a FairChemEnergy module with a custom model checkpoint, tau, alpha, and device settings', 'call_FairChemEnergy': 'call the FairChemEnergy module on a batch to compute energy and forces with optional regularization', 'use_wandb_mode_disabled': 'use the wandb_mode_disabled context manager to temporarily disable WANDB_MODE during model initialization', 'run_bond_regularizer': 'run the bond_regularizer method on a batch to compute regularization energy and gradient forces', 'review_FairChemEnergy_call': 'review the FairChemEnergy __call__ method to understand batch preprocessing and prediction denormalization'}
```

## File: facebookresearch_adjointsampling/adjoint_sampling/energies/regularizers.py

Prompts

```
['create a FairChemEnergy module with a custom model checkpoint, tau, alpha, and device settings', 'call the FairChemEnergy module on a batch to compute energy and forces with optional regularization', 'use the wandb_mode_disabled context manager to temporarily disable WANDB_MODE during model initialization', 'run the bond_regularizer method on a batch to compute regularization energy and gradient forces', 'review the FairChemEnergy __call__ method to understand batch preprocessing and prediction denormalization', 'run bond_structure_regularizer to compute bond and no-bond constraint penalties for molecular positions', 'create a bond constraint penalty using relu on bond norms exceeding bond limits', 'create a no-bond constraint penalty using relu on bond norms below bond limits', 'compute per-system regularization energy by scattering bond constraints across batched molecular graphs', 'refactor bond_structure_regularizer to use huber_loss instead of relu for smoother constraint penalties']
```

Usage

```
{'run_bond_structure_regularizer': 'run bond_structure_regularizer to compute bond and no-bond constraint penalties for molecular positions', 'create_bond_constraint_penalty': 'create a bond constraint penalty using relu on bond norms exceeding bond limits', 'create_no_bond_constraint_penalty': 'create a no-bond constraint penalty using relu on bond norms below bond limits', 'compute_molecular_regularization': 'compute per-system regularization energy by scattering bond constraints across batched molecular graphs', 'refactor_regularizer_to_huber_loss': 'refactor bond_structure_regularizer to use huber_loss instead of relu for smoother constraint penalties'}
```


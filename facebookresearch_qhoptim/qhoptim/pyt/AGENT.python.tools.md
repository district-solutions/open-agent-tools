# Agent Python Tools

- repo: facebookresearch/qhoptim
- repo_uri: https://github.com/facebookresearch/qhoptim

## File: facebookresearch_qhoptim/qhoptim/pyt/qhadam.py

Prompts

```
['create a QHAdam optimizer for model parameters with custom learning rate, betas, and nus hyperparameters', 'run a single optimization step with the QHAdam optimizer after computing gradients', 'create a QHAdamW optimizer with decoupled weight decay for model parameters', 'review the QHAdam from_nadam class method to get hyperparameters that recover NAdam behavior', 'test the QHAdam optimizer with coupled or decoupled weight decay on model parameters', 'create a QHM optimizer with model parameters, learning rate, momentum, and nu discount factor', 'run a single QHM optimization step on model parameters with optional closure for loss evaluation', 'build QHM hyperparameters from PID controller gains k_p, k_i, and k_d values', 'build QHM hyperparameters from AccSGD optimizer parameters delta, kappa, xi, and eps', 'build QHM hyperparameters from robust momentum or triple momentum using Lipschitz constant and condition ratio']
```

Usage

```
{'create_QHAdam_optimizer': 'create a QHAdam optimizer for model parameters with custom learning rate, betas, and nus hyperparameters', 'run_QHAdam_step': 'run a single optimization step with the QHAdam optimizer after computing gradients', 'create_QHAdamW_optimizer': 'create a QHAdamW optimizer with decoupled weight decay for model parameters', 'review_QHAdam_from_nadam': 'review the QHAdam from_nadam class method to get hyperparameters that recover NAdam behavior', 'test_QHAdam_weight_decay': 'test the QHAdam optimizer with coupled or decoupled weight decay on model parameters'}
```

## File: facebookresearch_qhoptim/qhoptim/pyt/qhm.py

Prompts

```
['create a QHAdam optimizer for model parameters with custom learning rate, betas, and nus hyperparameters', 'run a single optimization step with the QHAdam optimizer after computing gradients', 'create a QHAdamW optimizer with decoupled weight decay for model parameters', 'review the QHAdam from_nadam class method to get hyperparameters that recover NAdam behavior', 'test the QHAdam optimizer with coupled or decoupled weight decay on model parameters', 'create a QHM optimizer with model parameters, learning rate, momentum, and nu discount factor', 'run a single QHM optimization step on model parameters with optional closure for loss evaluation', 'build QHM hyperparameters from PID controller gains k_p, k_i, and k_d values', 'build QHM hyperparameters from AccSGD optimizer parameters delta, kappa, xi, and eps', 'build QHM hyperparameters from robust momentum or triple momentum using Lipschitz constant and condition ratio']
```

Usage

```
{'create_QHM_optimizer': 'create a QHM optimizer with model parameters, learning rate, momentum, and nu discount factor', 'run_QHM_step': 'run a single QHM optimization step on model parameters with optional closure for loss evaluation', 'build_QHM_from_pid': 'build QHM hyperparameters from PID controller gains k_p, k_i, and k_d values', 'build_QHM_from_accsgd': 'build QHM hyperparameters from AccSGD optimizer parameters delta, kappa, xi, and eps', 'build_QHM_from_robust_momentum': 'build QHM hyperparameters from robust momentum or triple momentum using Lipschitz constant and condition ratio'}
```


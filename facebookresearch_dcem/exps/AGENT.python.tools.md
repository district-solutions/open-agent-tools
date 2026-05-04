# Agent Python Tools

- repo: facebookresearch/dcem
- repo_uri: https://github.com/facebookresearch/dcem

## File: facebookresearch_dcem/exps/cartpole_emb.py

Prompts

```
['run the CartpoleEmbExp experiment to train an embedded control policy for cartpole', 'create a DCEM controller that optimizes latent embeddings for cartpole control', 'create a GD controller that uses inner gradient descent for cartpole control', 'build a Decode neural network to map latent embeddings to control action sequences', 'compute the nominal reward for a cartpole trajectory given initial states and controls', 'run the RegressionExp class to train an energy-based regression model on x*sin(x) data', 'create an EnergyNet neural network module that computes energy values from input x and output y pairs', 'build an UnrollEnergyGD module that unrolls gradient descent steps to minimize energy for regression prediction', 'build an UnrollEnergyCEM module that uses cross-entropy method sampling to minimize energy for regression prediction', 'run the main entry point to start a regression experiment using hydra configuration and the specified model']
```

Usage

```
{'run_cartpole_emb_experiment': 'run the CartpoleEmbExp experiment to train an embedded control policy for cartpole', 'create_dcem_controller': 'create a DCEM controller that optimizes latent embeddings for cartpole control', 'create_gd_controller': 'create a GD controller that uses inner gradient descent for cartpole control', 'build_decode_network': 'build a Decode neural network to map latent embeddings to control action sequences', 'compute_cartpole_reward': 'compute the nominal reward for a cartpole trajectory given initial states and controls'}
```

## File: facebookresearch_dcem/exps/regression.py

Prompts

```
['run the CartpoleEmbExp experiment to train an embedded control policy for cartpole', 'create a DCEM controller that optimizes latent embeddings for cartpole control', 'create a GD controller that uses inner gradient descent for cartpole control', 'build a Decode neural network to map latent embeddings to control action sequences', 'compute the nominal reward for a cartpole trajectory given initial states and controls', 'run the RegressionExp class to train an energy-based regression model on x*sin(x) data', 'create an EnergyNet neural network module that computes energy values from input x and output y pairs', 'build an UnrollEnergyGD module that unrolls gradient descent steps to minimize energy for regression prediction', 'build an UnrollEnergyCEM module that uses cross-entropy method sampling to minimize energy for regression prediction', 'run the main entry point to start a regression experiment using hydra configuration and the specified model']
```

Usage

```
{'run_regression_experiment': 'run the RegressionExp class to train an energy-based regression model on x*sin(x) data', 'create_energy_net': 'create an EnergyNet neural network module that computes energy values from input x and output y pairs', 'build_unroll_energy_gd': 'build an UnrollEnergyGD module that unrolls gradient descent steps to minimize energy for regression prediction', 'build_unroll_energy_cem': 'build an UnrollEnergyCEM module that uses cross-entropy method sampling to minimize energy for regression prediction', 'run_main_entry': 'run the main entry point to start a regression experiment using hydra configuration and the specified model'}
```


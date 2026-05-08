# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/examples/tfe_benchmarks/tfe_benchmarks.py

Prompts

```
['run the TFE benchmark training loop on MNIST with a chosen network and number of epochs', 'create a PyTorch benchmark model (NetworkA, NetworkB, or NetworkC) by name', 'create an encrypted Crypten private model from an existing PyTorch benchmark model', 'validate a model on the MNIST test set and return top-1 accuracy', 'train a model for one epoch on the MNIST training set with SGD and logging']
```

Usage

```
{'run_tfe_benchmarks': 'run the TFE benchmark training loop on MNIST with a chosen network and number of epochs', 'create_benchmark_model': 'create a PyTorch benchmark model (NetworkA, NetworkB, or NetworkC) by name', 'create_private_benchmark_model': 'create an encrypted Crypten private model from an existing PyTorch benchmark model', 'validate': 'validate a model on the MNIST test set and return top-1 accuracy', 'train': 'train a model for one epoch on the MNIST training set with SGD and logging'}
```


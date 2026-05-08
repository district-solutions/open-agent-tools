# Agent Python Tools

- repo: facebookresearch/ppuda
- repo_uri: https://github.com/facebookresearch/ppuda

## File: facebookresearch_ppuda/experiments/net_generator.py

Prompts

```
['run the net generator to create a train split of N random neural network architectures saved as HDF5', 'run the net generator to create an out-of-distribution split like deep, dense, or bnfree', 'run the net generator to create a search split with larger networks for architecture search', 'merge all evaluation split HDF5 and JSON files into a single combined eval file', 'review the genotype sampling logic that generates random neural cell topologies with configurable steps and operations', 'run the property prediction experiment on cifar10 or imagenet using a GHN checkpoint', 'extract graph embeddings from neural network architectures using a loaded GHN model', 'train an SVR regression model with grid search cross-validation on graph embeddings', 'evaluate rank correlation between predicted and actual architecture properties using kendalltau', 'find the best architecture in the search split by predicting a given property']
```

Usage

```
{'generate_deepnets1m_train_split': 'run the net generator to create a train split of N random neural network architectures saved as HDF5', 'generate_deepnets1m_ood_split': 'run the net generator to create an out-of-distribution split like deep, dense, or bnfree', 'generate_deepnets1m_search_split': 'run the net generator to create a search split with larger networks for architecture search', 'merge_eval_splits': 'merge all evaluation split HDF5 and JSON files into a single combined eval file', 'review_genotype_sampling': 'review the genotype sampling logic that generates random neural cell topologies with configurable steps and operations'}
```

## File: facebookresearch_ppuda/experiments/property_prediction.py

Prompts

```
['run the net generator to create a train split of N random neural network architectures saved as HDF5', 'run the net generator to create an out-of-distribution split like deep, dense, or bnfree', 'run the net generator to create a search split with larger networks for architecture search', 'merge all evaluation split HDF5 and JSON files into a single combined eval file', 'review the genotype sampling logic that generates random neural cell topologies with configurable steps and operations', 'run the property prediction experiment on cifar10 or imagenet using a GHN checkpoint', 'extract graph embeddings from neural network architectures using a loaded GHN model', 'train an SVR regression model with grid search cross-validation on graph embeddings', 'evaluate rank correlation between predicted and actual architecture properties using kendalltau', 'find the best architecture in the search split by predicting a given property']
```

Usage

```
{'run_property_prediction_experiment': 'run the property prediction experiment on cifar10 or imagenet using a GHN checkpoint', 'extract_graph_embeddings': 'extract graph embeddings from neural network architectures using a loaded GHN model', 'train_svr_regression_model': 'train an SVR regression model with grid search cross-validation on graph embeddings', 'evaluate_kendall_tau_correlation': 'evaluate rank correlation between predicted and actual architecture properties using kendalltau', 'find_best_architecture': 'find the best architecture in the search split by predicting a given property'}
```


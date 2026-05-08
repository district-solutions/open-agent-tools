# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/train/workloads/dlrm/tricks/md_embedding_bag.py

Prompts

```
['run md_solver to compute mixed-dimension embedding sizes using the alpha power temperature heuristic', 'run alpha_power_rule to calculate embedding dimensions based on cardinality and alpha skew parameter', 'run pow_2_round to round embedding dimensions to the nearest power of 2', 'create a PrEmbeddingBag module with projection from a smaller embedding dimension to a base dimension', 'review the PrEmbeddingBag forward method that projects embedding bag outputs to a uniform base dimension', 'create a QREmbeddingBag module using the mult operation to compose quotient and remainder embeddings', 'create a QREmbeddingBag module using the concat operation to concatenate quotient and remainder embeddings', 'create a QREmbeddingBag module using the add operation to sum quotient and remainder embeddings', 'run the QREmbeddingBag forward pass with input indices and optional per sample weights', 'reset the QREmbeddingBag weight parameters using uniform initialization based on num categories']
```

Usage

```
{'run_md_solver': 'run md_solver to compute mixed-dimension embedding sizes using the alpha power temperature heuristic', 'run_alpha_power_rule': 'run alpha_power_rule to calculate embedding dimensions based on cardinality and alpha skew parameter', 'run_pow_2_round': 'run pow_2_round to round embedding dimensions to the nearest power of 2', 'create_PrEmbeddingBag': 'create a PrEmbeddingBag module with projection from a smaller embedding dimension to a base dimension', 'review_PrEmbeddingBag_forward': 'review the PrEmbeddingBag forward method that projects embedding bag outputs to a uniform base dimension'}
```

## File: facebookresearch_param/train/workloads/dlrm/tricks/qr_embedding_bag.py

Prompts

```
['run md_solver to compute mixed-dimension embedding sizes using the alpha power temperature heuristic', 'run alpha_power_rule to calculate embedding dimensions based on cardinality and alpha skew parameter', 'run pow_2_round to round embedding dimensions to the nearest power of 2', 'create a PrEmbeddingBag module with projection from a smaller embedding dimension to a base dimension', 'review the PrEmbeddingBag forward method that projects embedding bag outputs to a uniform base dimension', 'create a QREmbeddingBag module using the mult operation to compose quotient and remainder embeddings', 'create a QREmbeddingBag module using the concat operation to concatenate quotient and remainder embeddings', 'create a QREmbeddingBag module using the add operation to sum quotient and remainder embeddings', 'run the QREmbeddingBag forward pass with input indices and optional per sample weights', 'reset the QREmbeddingBag weight parameters using uniform initialization based on num categories']
```

Usage

```
{'create_QREmbeddingBag_mult': 'create a QREmbeddingBag module using the mult operation to compose quotient and remainder embeddings', 'create_QREmbeddingBag_concat': 'create a QREmbeddingBag module using the concat operation to concatenate quotient and remainder embeddings', 'create_QREmbeddingBag_add': 'create a QREmbeddingBag module using the add operation to sum quotient and remainder embeddings', 'run_QREmbeddingBag_forward': 'run the QREmbeddingBag forward pass with input indices and optional per sample weights', 'reset_QREmbeddingBag_parameters': 'reset the QREmbeddingBag weight parameters using uniform initialization based on num categories'}
```


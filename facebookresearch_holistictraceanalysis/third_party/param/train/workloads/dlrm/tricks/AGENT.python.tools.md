# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/third_party/param/train/workloads/dlrm/tricks/md_embedding_bag.py

Prompts

```
['run md_solver to compute mixed-dimension embedding sizes using the alpha power temperature heuristic', 'run alpha_power_rule to calculate embedding dimensions based on cardinality and alpha skew parameter', 'run pow_2_round to round embedding dimensions to the nearest power of 2', 'create a PrEmbeddingBag module with projection from a smaller embedding dimension to a base dimension', 'review the PrEmbeddingBag forward method that applies embedding bag lookup then linear projection', 'create a QREmbeddingBag module with mult operation to compose quotient and remainder embeddings for memory-efficient recommendations', 'create a QREmbeddingBag module with concat operation to concatenate quotient and remainder embedding vectors', 'create a QREmbeddingBag module with add operation to sum quotient and remainder embedding vectors', 'run the QREmbeddingBag forward pass with input indices and optional offsets to compute aggregated embeddings', 'reset the QREmbeddingBag weight parameters using uniform initialization based on the number of categories']
```

Usage

```
{'run_md_solver': 'run md_solver to compute mixed-dimension embedding sizes using the alpha power temperature heuristic', 'run_alpha_power_rule': 'run alpha_power_rule to calculate embedding dimensions based on cardinality and alpha skew parameter', 'run_pow_2_round': 'run pow_2_round to round embedding dimensions to the nearest power of 2', 'create_PrEmbeddingBag': 'create a PrEmbeddingBag module with projection from a smaller embedding dimension to a base dimension', 'review_PrEmbeddingBag_forward': 'review the PrEmbeddingBag forward method that applies embedding bag lookup then linear projection'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/train/workloads/dlrm/tricks/qr_embedding_bag.py

Prompts

```
['run md_solver to compute mixed-dimension embedding sizes using the alpha power temperature heuristic', 'run alpha_power_rule to calculate embedding dimensions based on cardinality and alpha skew parameter', 'run pow_2_round to round embedding dimensions to the nearest power of 2', 'create a PrEmbeddingBag module with projection from a smaller embedding dimension to a base dimension', 'review the PrEmbeddingBag forward method that applies embedding bag lookup then linear projection', 'create a QREmbeddingBag module with mult operation to compose quotient and remainder embeddings for memory-efficient recommendations', 'create a QREmbeddingBag module with concat operation to concatenate quotient and remainder embedding vectors', 'create a QREmbeddingBag module with add operation to sum quotient and remainder embedding vectors', 'run the QREmbeddingBag forward pass with input indices and optional offsets to compute aggregated embeddings', 'reset the QREmbeddingBag weight parameters using uniform initialization based on the number of categories']
```

Usage

```
{'create_QREmbeddingBag_mult': 'create a QREmbeddingBag module with mult operation to compose quotient and remainder embeddings for memory-efficient recommendations', 'create_QREmbeddingBag_concat': 'create a QREmbeddingBag module with concat operation to concatenate quotient and remainder embedding vectors', 'create_QREmbeddingBag_add': 'create a QREmbeddingBag module with add operation to sum quotient and remainder embedding vectors', 'forward_QREmbeddingBag': 'run the QREmbeddingBag forward pass with input indices and optional offsets to compute aggregated embeddings', 'reset_QREmbeddingBag_parameters': 'reset the QREmbeddingBag weight parameters using uniform initialization based on the number of categories'}
```


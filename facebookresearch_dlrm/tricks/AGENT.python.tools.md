# Agent Python Tools

- repo: facebookresearch/dlrm
- repo_uri: https://github.com/facebookresearch/dlrm

## File: facebookresearch_dlrm/tricks/md_embedding_bag.py

Prompts

```
['run md_solver to compute mixed-dimension embedding sizes using the alpha power temperature heuristic', 'run alpha_power_rule to calculate embedding dimensions based on a parameter budget or baseline dimension', 'run pow_2_round to round embedding dimensions to the nearest power of 2', 'create a PrEmbeddingBag module with a sparse embedding bag and optional linear projection to base dimension', 'review the PrEmbeddingBag forward method to understand how it applies projection after the embedding bag lookup', 'build a QREmbeddingBag module using the mult operation to compose quotient and remainder embeddings for memory-efficient recommendations', 'build a QREmbeddingBag module using the concat operation to concatenate quotient and remainder embedding vectors', 'build a QREmbeddingBag module using the add operation to sum quotient and remainder embedding vectors', 'test the QREmbeddingBag forward pass with input indices offsets and per_sample_weights arguments', 'review the QREmbeddingBag reset_parameters method that initializes weight tensors with a uniform distribution']
```

Usage

```
{'run_md_solver': 'run md_solver to compute mixed-dimension embedding sizes using the alpha power temperature heuristic', 'run_alpha_power_rule': 'run alpha_power_rule to calculate embedding dimensions based on a parameter budget or baseline dimension', 'run_pow_2_round': 'run pow_2_round to round embedding dimensions to the nearest power of 2', 'create_PrEmbeddingBag': 'create a PrEmbeddingBag module with a sparse embedding bag and optional linear projection to base dimension', 'review_PrEmbeddingBag_forward': 'review the PrEmbeddingBag forward method to understand how it applies projection after the embedding bag lookup'}
```

## File: facebookresearch_dlrm/tricks/qr_embedding_bag.py

Prompts

```
['run md_solver to compute mixed-dimension embedding sizes using the alpha power temperature heuristic', 'run alpha_power_rule to calculate embedding dimensions based on a parameter budget or baseline dimension', 'run pow_2_round to round embedding dimensions to the nearest power of 2', 'create a PrEmbeddingBag module with a sparse embedding bag and optional linear projection to base dimension', 'review the PrEmbeddingBag forward method to understand how it applies projection after the embedding bag lookup', 'build a QREmbeddingBag module using the mult operation to compose quotient and remainder embeddings for memory-efficient recommendations', 'build a QREmbeddingBag module using the concat operation to concatenate quotient and remainder embedding vectors', 'build a QREmbeddingBag module using the add operation to sum quotient and remainder embedding vectors', 'test the QREmbeddingBag forward pass with input indices offsets and per_sample_weights arguments', 'review the QREmbeddingBag reset_parameters method that initializes weight tensors with a uniform distribution']
```

Usage

```
{'build_QREmbeddingBag_mult': 'build a QREmbeddingBag module using the mult operation to compose quotient and remainder embeddings for memory-efficient recommendations', 'build_QREmbeddingBag_concat': 'build a QREmbeddingBag module using the concat operation to concatenate quotient and remainder embedding vectors', 'build_QREmbeddingBag_add': 'build a QREmbeddingBag module using the add operation to sum quotient and remainder embedding vectors', 'test_QREmbeddingBag_forward': 'test the QREmbeddingBag forward pass with input indices offsets and per_sample_weights arguments', 'review_QREmbeddingBag_reset_parameters': 'review the QREmbeddingBag reset_parameters method that initializes weight tensors with a uniform distribution'}
```


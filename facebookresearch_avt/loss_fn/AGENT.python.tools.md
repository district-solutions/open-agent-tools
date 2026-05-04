# Agent Python Tools

- repo: facebookresearch/avt
- repo_uri: https://github.com/facebookresearch/avt

## File: facebookresearch_avt/loss_fn/mse.py

Prompts

```
['create a NormedMSE loss instance that L2-normalizes inputs before computing MSE', 'use NormedMSE forward pass to compute normalized MSE between input and target tensors', 'review the NormedMSE class that extends nn.MSELoss with L2 normalization on the last dimension', 'refactor the NormedMSE forward method to use a different normalization strategy instead of L2', 'test the NormedMSE forward method with input and target tensors of shape (*, C)', 'build a MultiDimCrossEntropy loss that computes cross entropy on multi-dimensional input tensors with automatic reshaping', 'create a QuantizeAndCrossEntropy loss that projects features to k-means centroids before computing cross entropy', 'test the MultiDimCrossEntropy forward pass with multi-dimensional input and target tensors of matching shape', 'review the QuantizeAndCrossEntropy forward method that L2-normalizes inputs and assigns targets to cluster centroids', 'refactor the QuantizeAndCrossEntropy centroid projection logic to support dynamic centroid loading from file paths', 'create a MILCrossEntropyLoss with sum type to compute multiple instance learning NCE loss using logsumexp over positive predictions', 'create a MILCrossEntropyLoss with max type to compute MIL NCE loss using max aggregation over positive predictions', 'create a DistributedSimclrInfoNCELoss module to compute contrastive loss with distributed embedding gathering across GPUs', 'use MultiDimDistributedSimclrInfoNCELoss to compute NCE loss on multi-dimensional tensors by flattening initial dimensions', 'review the gather_embeddings method to understand how it collects embeddings from all GPUs for distributed loss computation']
```

Usage

```
{'create_normed_mse_loss': 'create a NormedMSE loss instance that L2-normalizes inputs before computing MSE', 'use_normed_mse_forward': 'use NormedMSE forward pass to compute normalized MSE between input and target tensors', 'review_normed_mse_class': 'review the NormedMSE class that extends nn.MSELoss with L2 normalization on the last dimension', 'refactor_normed_mse_normalization': 'refactor the NormedMSE forward method to use a different normalization strategy instead of L2', 'test_normed_mse_forward': 'test the NormedMSE forward method with input and target tensors of shape (*, C)'}
```

## File: facebookresearch_avt/loss_fn/multidim_xentropy.py

Prompts

```
['create a NormedMSE loss instance that L2-normalizes inputs before computing MSE', 'use NormedMSE forward pass to compute normalized MSE between input and target tensors', 'review the NormedMSE class that extends nn.MSELoss with L2 normalization on the last dimension', 'refactor the NormedMSE forward method to use a different normalization strategy instead of L2', 'test the NormedMSE forward method with input and target tensors of shape (*, C)', 'build a MultiDimCrossEntropy loss that computes cross entropy on multi-dimensional input tensors with automatic reshaping', 'create a QuantizeAndCrossEntropy loss that projects features to k-means centroids before computing cross entropy', 'test the MultiDimCrossEntropy forward pass with multi-dimensional input and target tensors of matching shape', 'review the QuantizeAndCrossEntropy forward method that L2-normalizes inputs and assigns targets to cluster centroids', 'refactor the QuantizeAndCrossEntropy centroid projection logic to support dynamic centroid loading from file paths', 'create a MILCrossEntropyLoss with sum type to compute multiple instance learning NCE loss using logsumexp over positive predictions', 'create a MILCrossEntropyLoss with max type to compute MIL NCE loss using max aggregation over positive predictions', 'create a DistributedSimclrInfoNCELoss module to compute contrastive loss with distributed embedding gathering across GPUs', 'use MultiDimDistributedSimclrInfoNCELoss to compute NCE loss on multi-dimensional tensors by flattening initial dimensions', 'review the gather_embeddings method to understand how it collects embeddings from all GPUs for distributed loss computation']
```

Usage

```
{'build_multidim_cross_entropy': 'build a MultiDimCrossEntropy loss that computes cross entropy on multi-dimensional input tensors with automatic reshaping', 'create_quantize_and_cross_entropy': 'create a QuantizeAndCrossEntropy loss that projects features to k-means centroids before computing cross entropy', 'test_multidim_forward': 'test the MultiDimCrossEntropy forward pass with multi-dimensional input and target tensors of matching shape', 'review_quantize_forward': 'review the QuantizeAndCrossEntropy forward method that L2-normalizes inputs and assigns targets to cluster centroids', 'refactor_centroid_projection': 'refactor the QuantizeAndCrossEntropy centroid projection logic to support dynamic centroid loading from file paths'}
```

## File: facebookresearch_avt/loss_fn/simclr_infonce.py

Prompts

```
['create a NormedMSE loss instance that L2-normalizes inputs before computing MSE', 'use NormedMSE forward pass to compute normalized MSE between input and target tensors', 'review the NormedMSE class that extends nn.MSELoss with L2 normalization on the last dimension', 'refactor the NormedMSE forward method to use a different normalization strategy instead of L2', 'test the NormedMSE forward method with input and target tensors of shape (*, C)', 'build a MultiDimCrossEntropy loss that computes cross entropy on multi-dimensional input tensors with automatic reshaping', 'create a QuantizeAndCrossEntropy loss that projects features to k-means centroids before computing cross entropy', 'test the MultiDimCrossEntropy forward pass with multi-dimensional input and target tensors of matching shape', 'review the QuantizeAndCrossEntropy forward method that L2-normalizes inputs and assigns targets to cluster centroids', 'refactor the QuantizeAndCrossEntropy centroid projection logic to support dynamic centroid loading from file paths', 'create a MILCrossEntropyLoss with sum type to compute multiple instance learning NCE loss using logsumexp over positive predictions', 'create a MILCrossEntropyLoss with max type to compute MIL NCE loss using max aggregation over positive predictions', 'create a DistributedSimclrInfoNCELoss module to compute contrastive loss with distributed embedding gathering across GPUs', 'use MultiDimDistributedSimclrInfoNCELoss to compute NCE loss on multi-dimensional tensors by flattening initial dimensions', 'review the gather_embeddings method to understand how it collects embeddings from all GPUs for distributed loss computation']
```

Usage

```
{'create_MILCrossEntropyLoss_sum': 'create a MILCrossEntropyLoss with sum type to compute multiple instance learning NCE loss using logsumexp over positive predictions', 'create_MILCrossEntropyLoss_max': 'create a MILCrossEntropyLoss with max type to compute MIL NCE loss using max aggregation over positive predictions', 'create_DistributedSimclrInfoNCELoss': 'create a DistributedSimclrInfoNCELoss module to compute contrastive loss with distributed embedding gathering across GPUs', 'use_MultiDimDistributedSimclrInfoNCELoss': 'use MultiDimDistributedSimclrInfoNCELoss to compute NCE loss on multi-dimensional tensors by flattening initial dimensions', 'review_gather_embeddings': 'review the gather_embeddings method to understand how it collects embeddings from all GPUs for distributed loss computation'}
```


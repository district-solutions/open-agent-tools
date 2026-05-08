# Agent Python Tools

- repo: facebookresearch/libri-light
- repo_uri: https://github.com/facebookresearch/libri-light

## File: facebookresearch_libri-light/eval/ABX_src/abx_group_computation.py

Prompts

```
['get a distance function by name such as euclidian, cosine, kl, or kl_symmetric', 'compute the KL divergence distance between two batched sequence tensors with epsilon smoothing', 'compute the cosine distance between two normalized batched sequence tensors', 'compute the ABX theta score using DTW distances between groups a, b, and x', 'compute ABX scores across all groups in an iterator using DTW and return a sparse tensor', 'create an ABXFeatureLoader to load speech features from an item file and sequence list for ABX scoring', 'load a .item file to parse ABX triplet definitions with phone, context, and speaker mappings', 'normalize a feature tensor across channels with singularity handling for zero-norm vectors', 'group feature entries by context, speaker, and phone indices for hierarchical ABX triplet iteration', 'create an ABXWithinGroupIterator to yield within-speaker ABX triplets for computing the ABX within score', 'test the DTW distance computation between two tensor groups using get_distance_group_dtw', 'test the symmetric theta similarity score between tensor groups using get_theta_group_dtw', 'test batch cosine distance computation between normalized feature tensors', 'test singularity-aware normalization of feature tensors before cosine distance calculation', 'test multi-dimensional feature grouping and sorting by specified column order']
```

Usage

```
{'get_distance_function_from_name': 'get a distance function by name such as euclidian, cosine, kl, or kl_symmetric', 'get_kl_distance_batch': 'compute the KL divergence distance between two batched sequence tensors with epsilon smoothing', 'get_cosine_distance_batch': 'compute the cosine distance between two normalized batched sequence tensors', 'get_theta_group_dtw': 'compute the ABX theta score using DTW distances between groups a, b, and x', 'get_abx_scores_dtw_on_group': 'compute ABX scores across all groups in an iterator using DTW and return a sparse tensor'}
```

## File: facebookresearch_libri-light/eval/ABX_src/abx_iterators.py

Prompts

```
['get a distance function by name such as euclidian, cosine, kl, or kl_symmetric', 'compute the KL divergence distance between two batched sequence tensors with epsilon smoothing', 'compute the cosine distance between two normalized batched sequence tensors', 'compute the ABX theta score using DTW distances between groups a, b, and x', 'compute ABX scores across all groups in an iterator using DTW and return a sparse tensor', 'create an ABXFeatureLoader to load speech features from an item file and sequence list for ABX scoring', 'load a .item file to parse ABX triplet definitions with phone, context, and speaker mappings', 'normalize a feature tensor across channels with singularity handling for zero-norm vectors', 'group feature entries by context, speaker, and phone indices for hierarchical ABX triplet iteration', 'create an ABXWithinGroupIterator to yield within-speaker ABX triplets for computing the ABX within score', 'test the DTW distance computation between two tensor groups using get_distance_group_dtw', 'test the symmetric theta similarity score between tensor groups using get_theta_group_dtw', 'test batch cosine distance computation between normalized feature tensors', 'test singularity-aware normalization of feature tensors before cosine distance calculation', 'test multi-dimensional feature grouping and sorting by specified column order']
```

Usage

```
{'create_ABXFeatureLoader': 'create an ABXFeatureLoader to load speech features from an item file and sequence list for ABX scoring', 'load_item_file': 'load a .item file to parse ABX triplet definitions with phone, context, and speaker mappings', 'normalize_with_singularity': 'normalize a feature tensor across channels with singularity handling for zero-norm vectors', 'get_features_group': 'group feature entries by context, speaker, and phone indices for hierarchical ABX triplet iteration', 'create_ABXWithinGroupIterator': 'create an ABXWithinGroupIterator to yield within-speaker ABX triplets for computing the ABX within score'}
```

## File: facebookresearch_libri-light/eval/ABX_src/unit_tests.py

Prompts

```
['get a distance function by name such as euclidian, cosine, kl, or kl_symmetric', 'compute the KL divergence distance between two batched sequence tensors with epsilon smoothing', 'compute the cosine distance between two normalized batched sequence tensors', 'compute the ABX theta score using DTW distances between groups a, b, and x', 'compute ABX scores across all groups in an iterator using DTW and return a sparse tensor', 'create an ABXFeatureLoader to load speech features from an item file and sequence list for ABX scoring', 'load a .item file to parse ABX triplet definitions with phone, context, and speaker mappings', 'normalize a feature tensor across channels with singularity handling for zero-norm vectors', 'group feature entries by context, speaker, and phone indices for hierarchical ABX triplet iteration', 'create an ABXWithinGroupIterator to yield within-speaker ABX triplets for computing the ABX within score', 'test the DTW distance computation between two tensor groups using get_distance_group_dtw', 'test the symmetric theta similarity score between tensor groups using get_theta_group_dtw', 'test batch cosine distance computation between normalized feature tensors', 'test singularity-aware normalization of feature tensors before cosine distance calculation', 'test multi-dimensional feature grouping and sorting by specified column order']
```

Usage

```
{'test_DTW_distance_computation': 'test the DTW distance computation between two tensor groups using get_distance_group_dtw', 'test_theta_DTW_symmetric': 'test the symmetric theta similarity score between tensor groups using get_theta_group_dtw', 'test_cosine_distance_batch': 'test batch cosine distance computation between normalized feature tensors', 'test_normalize_with_singularity': 'test singularity-aware normalization of feature tensors before cosine distance calculation', 'test_get_features_group': 'test multi-dimensional feature grouping and sorting by specified column order'}
```


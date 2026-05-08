# Agent Python Tools

- repo: facebookresearch/classifier-balancing
- repo_uri: https://github.com/facebookresearch/classifier-balancing

## File: facebookresearch_classifier-balancing/data/ClassAwareSampler.py

Prompts

```
['create a ClassAwareSampler instance from a data source with labels for balanced class sampling', 'create a RandomCycleIter to cycle through data with optional shuffling between epochs', 'use class_aware_sample_generator to yield balanced samples across classes in a PyTorch DataLoader', 'get the ClassAwareSampler class via get_sampler for use with PyTorch DataLoader', 'review the ClassAwareSampler class to understand class-balanced sampling logic for imbalanced datasets', 'create a ClassPrioritySampler instance with a dataset, balance_scale, fixed_scale, and lam parameters for class-balanced sampling', 'build a PriorityTree with capacity, init_weights, fixed_weights, and alpha for prioritized sampling with a segment tree', 'update the priority weights of a ClassPrioritySampler using batch indices, weights, and labels during training', 'reset the manual weights of a ClassPrioritySampler for a given epoch using linear or periodic shifting strategies', 'get the ClassPrioritySampler class by calling the get_sampler factory function for use in PyTorch data loading', 'create a PriorityTree with a given capacity and optional fixed weights for priority sampling', 'update a single leaf node priority in the PriorityTree and propagate changes up the tree', 'sample a data index from the PriorityTree by traversing from root to leaf with a random value', 'create a MixedPrioritizedSampler for a dataset combining balanced class weights with priority-based sampling', 'reset the sampler weights for a given epoch using linear, periodic, or cosine shifting strategies', 'create a PyTorch DataLoader from a dataset text file with configurable batch size and sampler', 'load a concatenated dataset combining standard and open-set test images for evaluation', 'build a torchvision transform pipeline with random crop, flip, and color jitter for training', 'build a torchvision transform pipeline with resize and center crop for validation or testing', 'create a PyTorch Dataset that reads image paths and labels from a text file']
```

Usage

```
{'create_class_aware_sampler': 'create a ClassAwareSampler instance from a data source with labels for balanced class sampling', 'create_random_cycle_iterator': 'create a RandomCycleIter to cycle through data with optional shuffling between epochs', 'use_class_aware_sample_generator': 'use class_aware_sample_generator to yield balanced samples across classes in a PyTorch DataLoader', 'get_sampler_class': 'get the ClassAwareSampler class via get_sampler for use with PyTorch DataLoader', 'review_class_aware_sampler': 'review the ClassAwareSampler class to understand class-balanced sampling logic for imbalanced datasets'}
```

## File: facebookresearch_classifier-balancing/data/ClassPrioritySampler.py

Prompts

```
['create a ClassAwareSampler instance from a data source with labels for balanced class sampling', 'create a RandomCycleIter to cycle through data with optional shuffling between epochs', 'use class_aware_sample_generator to yield balanced samples across classes in a PyTorch DataLoader', 'get the ClassAwareSampler class via get_sampler for use with PyTorch DataLoader', 'review the ClassAwareSampler class to understand class-balanced sampling logic for imbalanced datasets', 'create a ClassPrioritySampler instance with a dataset, balance_scale, fixed_scale, and lam parameters for class-balanced sampling', 'build a PriorityTree with capacity, init_weights, fixed_weights, and alpha for prioritized sampling with a segment tree', 'update the priority weights of a ClassPrioritySampler using batch indices, weights, and labels during training', 'reset the manual weights of a ClassPrioritySampler for a given epoch using linear or periodic shifting strategies', 'get the ClassPrioritySampler class by calling the get_sampler factory function for use in PyTorch data loading', 'create a PriorityTree with a given capacity and optional fixed weights for priority sampling', 'update a single leaf node priority in the PriorityTree and propagate changes up the tree', 'sample a data index from the PriorityTree by traversing from root to leaf with a random value', 'create a MixedPrioritizedSampler for a dataset combining balanced class weights with priority-based sampling', 'reset the sampler weights for a given epoch using linear, periodic, or cosine shifting strategies', 'create a PyTorch DataLoader from a dataset text file with configurable batch size and sampler', 'load a concatenated dataset combining standard and open-set test images for evaluation', 'build a torchvision transform pipeline with random crop, flip, and color jitter for training', 'build a torchvision transform pipeline with resize and center crop for validation or testing', 'create a PyTorch Dataset that reads image paths and labels from a text file']
```

Usage

```
{'create_ClassPrioritySampler': 'create a ClassPrioritySampler instance with a dataset, balance_scale, fixed_scale, and lam parameters for class-balanced sampling', 'build_PriorityTree': 'build a PriorityTree with capacity, init_weights, fixed_weights, and alpha for prioritized sampling with a segment tree', 'update_weights_ClassPrioritySampler': 'update the priority weights of a ClassPrioritySampler using batch indices, weights, and labels during training', 'reset_weights_ClassPrioritySampler': 'reset the manual weights of a ClassPrioritySampler for a given epoch using linear or periodic shifting strategies', 'get_sampler': 'get the ClassPrioritySampler class by calling the get_sampler factory function for use in PyTorch data loading'}
```

## File: facebookresearch_classifier-balancing/data/MixedPrioritizedSampler.py

Prompts

```
['create a ClassAwareSampler instance from a data source with labels for balanced class sampling', 'create a RandomCycleIter to cycle through data with optional shuffling between epochs', 'use class_aware_sample_generator to yield balanced samples across classes in a PyTorch DataLoader', 'get the ClassAwareSampler class via get_sampler for use with PyTorch DataLoader', 'review the ClassAwareSampler class to understand class-balanced sampling logic for imbalanced datasets', 'create a ClassPrioritySampler instance with a dataset, balance_scale, fixed_scale, and lam parameters for class-balanced sampling', 'build a PriorityTree with capacity, init_weights, fixed_weights, and alpha for prioritized sampling with a segment tree', 'update the priority weights of a ClassPrioritySampler using batch indices, weights, and labels during training', 'reset the manual weights of a ClassPrioritySampler for a given epoch using linear or periodic shifting strategies', 'get the ClassPrioritySampler class by calling the get_sampler factory function for use in PyTorch data loading', 'create a PriorityTree with a given capacity and optional fixed weights for priority sampling', 'update a single leaf node priority in the PriorityTree and propagate changes up the tree', 'sample a data index from the PriorityTree by traversing from root to leaf with a random value', 'create a MixedPrioritizedSampler for a dataset combining balanced class weights with priority-based sampling', 'reset the sampler weights for a given epoch using linear, periodic, or cosine shifting strategies', 'create a PyTorch DataLoader from a dataset text file with configurable batch size and sampler', 'load a concatenated dataset combining standard and open-set test images for evaluation', 'build a torchvision transform pipeline with random crop, flip, and color jitter for training', 'build a torchvision transform pipeline with resize and center crop for validation or testing', 'create a PyTorch Dataset that reads image paths and labels from a text file']
```

Usage

```
{'create_priority_tree': 'create a PriorityTree with a given capacity and optional fixed weights for priority sampling', 'update_priority_tree_leaf': 'update a single leaf node priority in the PriorityTree and propagate changes up the tree', 'sample_from_priority_tree': 'sample a data index from the PriorityTree by traversing from root to leaf with a random value', 'create_mixed_prioritized_sampler': 'create a MixedPrioritizedSampler for a dataset combining balanced class weights with priority-based sampling', 'reset_sampler_weights': 'reset the sampler weights for a given epoch using linear, periodic, or cosine shifting strategies'}
```

## File: facebookresearch_classifier-balancing/data/dataloader.py

Prompts

```
['create a ClassAwareSampler instance from a data source with labels for balanced class sampling', 'create a RandomCycleIter to cycle through data with optional shuffling between epochs', 'use class_aware_sample_generator to yield balanced samples across classes in a PyTorch DataLoader', 'get the ClassAwareSampler class via get_sampler for use with PyTorch DataLoader', 'review the ClassAwareSampler class to understand class-balanced sampling logic for imbalanced datasets', 'create a ClassPrioritySampler instance with a dataset, balance_scale, fixed_scale, and lam parameters for class-balanced sampling', 'build a PriorityTree with capacity, init_weights, fixed_weights, and alpha for prioritized sampling with a segment tree', 'update the priority weights of a ClassPrioritySampler using batch indices, weights, and labels during training', 'reset the manual weights of a ClassPrioritySampler for a given epoch using linear or periodic shifting strategies', 'get the ClassPrioritySampler class by calling the get_sampler factory function for use in PyTorch data loading', 'create a PriorityTree with a given capacity and optional fixed weights for priority sampling', 'update a single leaf node priority in the PriorityTree and propagate changes up the tree', 'sample a data index from the PriorityTree by traversing from root to leaf with a random value', 'create a MixedPrioritizedSampler for a dataset combining balanced class weights with priority-based sampling', 'reset the sampler weights for a given epoch using linear, periodic, or cosine shifting strategies', 'create a PyTorch DataLoader from a dataset text file with configurable batch size and sampler', 'load a concatenated dataset combining standard and open-set test images for evaluation', 'build a torchvision transform pipeline with random crop, flip, and color jitter for training', 'build a torchvision transform pipeline with resize and center crop for validation or testing', 'create a PyTorch Dataset that reads image paths and labels from a text file']
```

Usage

```
{'load_data_dataloader': 'create a PyTorch DataLoader from a dataset text file with configurable batch size and sampler', 'load_data_openset': 'load a concatenated dataset combining standard and open-set test images for evaluation', 'get_data_transform_train': 'build a torchvision transform pipeline with random crop, flip, and color jitter for training', 'get_data_transform_test': 'build a torchvision transform pipeline with resize and center crop for validation or testing', 'LT_Dataset_init': 'create a PyTorch Dataset that reads image paths and labels from a text file'}
```


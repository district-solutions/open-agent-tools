# Agent Python Tools

- repo: google-deepmind/enn
- repo_uri: https://github.com/google-deepmind/enn

## File: google-deepmind_enn/enn/datasets/transforms/local_sample.py

Prompts

```
['create a dataset transformer that repeats each entry num_repeat times with a perturbation function applied', 'create a dataset transformer that applies random crop and flip augmentations to image batches', 'test the make_repeat_sample_transform function with a custom perturbation function and verify repeated entries', 'test the make_dyadic_transform function with image data and verify crop and flip augmentations', 'review the local_sample module for dataset transformation logic and perturbation function patterns', 'create OOD transformers for train and eval datasets given a number of classes and OOD fraction', 'sample a random subset of class labels from a given range using a fixed seed', 'get a dataset transformation function for in-distribution, out-of-distribution, or whole dataset variants', 'build a TensorFlow dataset filter that mixes in-distribution and out-of-distribution samples at a specified proportion', 'review the OOD dataset transformation logic that filters batches based on out-of-distribution labels']
```

Usage

```
{'create_repeat_sample_transform': 'create a dataset transformer that repeats each entry num_repeat times with a perturbation function applied', 'create_dyadic_transform': 'create a dataset transformer that applies random crop and flip augmentations to image batches', 'test_make_repeat_sample_transform': 'test the make_repeat_sample_transform function with a custom perturbation function and verify repeated entries', 'test_make_dyadic_transform': 'test the make_dyadic_transform function with image data and verify crop and flip augmentations', 'review_local_sample_module': 'review the local_sample module for dataset transformation logic and perturbation function patterns'}
```

## File: google-deepmind_enn/enn/datasets/transforms/ood.py

Prompts

```
['create a dataset transformer that repeats each entry num_repeat times with a perturbation function applied', 'create a dataset transformer that applies random crop and flip augmentations to image batches', 'test the make_repeat_sample_transform function with a custom perturbation function and verify repeated entries', 'test the make_dyadic_transform function with image data and verify crop and flip augmentations', 'review the local_sample module for dataset transformation logic and perturbation function patterns', 'create OOD transformers for train and eval datasets given a number of classes and OOD fraction', 'sample a random subset of class labels from a given range using a fixed seed', 'get a dataset transformation function for in-distribution, out-of-distribution, or whole dataset variants', 'build a TensorFlow dataset filter that mixes in-distribution and out-of-distribution samples at a specified proportion', 'review the OOD dataset transformation logic that filters batches based on out-of-distribution labels']
```

Usage

```
{'create_ood_transformers': 'create OOD transformers for train and eval datasets given a number of classes and OOD fraction', 'sample_classes': 'sample a random subset of class labels from a given range using a fixed seed', 'get_dataset_transform_from_type': 'get a dataset transformation function for in-distribution, out-of-distribution, or whole dataset variants', 'build_partial_ood_filter': 'build a TensorFlow dataset filter that mixes in-distribution and out-of-distribution samples at a specified proportion', 'review_ood_transform': 'review the OOD dataset transformation logic that filters batches based on out-of-distribution labels'}
```


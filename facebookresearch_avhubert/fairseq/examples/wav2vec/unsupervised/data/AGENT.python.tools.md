# Agent Python Tools

- repo: facebookresearch/avhubert
- repo_uri: https://github.com/facebookresearch/av_hubert

## File: facebookresearch_avhubert/fairseq/examples/wav2vec/unsupervised/data/extracted_features_dataset.py

Prompts

```
['create an ExtractedFeaturesDataset from a .npy features file with length filtering and optional labels', 'retrieve a single sample with features and optional target labels by index', 'collate a batch of samples into padded feature tensors with padding masks', 'get an ordered list of indices for batching with optional shuffle and length sorting', 'get the feature sequence length for a given sample index in the dataset', 'create a RandomInputDataset that wraps a dataset and replaces input features with random samples', 'review the RandomInputDataset get_target method that navigates nested dicts via input_key_path', 'review the RandomInputDataset get_target_value method that retrieves the value at the target key path', 'review the RandomInputDataset __getitem__ method that replaces input features with a random sample', 'review the RandomInputDataset collater method that collates samples and injects random inputs into the batch']
```

Usage

```
{'init_ExtractedFeaturesDataset': 'create an ExtractedFeaturesDataset from a .npy features file with length filtering and optional labels', 'getitem_ExtractedFeaturesDataset': 'retrieve a single sample with features and optional target labels by index', 'collater_ExtractedFeaturesDataset': 'collate a batch of samples into padded feature tensors with padding masks', 'ordered_indices_ExtractedFeaturesDataset': 'get an ordered list of indices for batching with optional shuffle and length sorting', 'size_ExtractedFeaturesDataset': 'get the feature sequence length for a given sample index in the dataset'}
```

## File: facebookresearch_avhubert/fairseq/examples/wav2vec/unsupervised/data/random_input_dataset.py

Prompts

```
['create an ExtractedFeaturesDataset from a .npy features file with length filtering and optional labels', 'retrieve a single sample with features and optional target labels by index', 'collate a batch of samples into padded feature tensors with padding masks', 'get an ordered list of indices for batching with optional shuffle and length sorting', 'get the feature sequence length for a given sample index in the dataset', 'create a RandomInputDataset that wraps a dataset and replaces input features with random samples', 'review the RandomInputDataset get_target method that navigates nested dicts via input_key_path', 'review the RandomInputDataset get_target_value method that retrieves the value at the target key path', 'review the RandomInputDataset __getitem__ method that replaces input features with a random sample', 'review the RandomInputDataset collater method that collates samples and injects random inputs into the batch']
```

Usage

```
{'create_random_input_dataset': 'create a RandomInputDataset that wraps a dataset and replaces input features with random samples', 'review_get_target': 'review the RandomInputDataset get_target method that navigates nested dicts via input_key_path', 'review_get_target_value': 'review the RandomInputDataset get_target_value method that retrieves the value at the target key path', 'review_getitem': 'review the RandomInputDataset __getitem__ method that replaces input features with a random sample', 'review_collater': 'review the RandomInputDataset collater method that collates samples and injects random inputs into the batch'}
```


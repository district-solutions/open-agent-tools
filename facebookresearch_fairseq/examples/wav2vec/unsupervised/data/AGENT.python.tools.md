# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/wav2vec/unsupervised/data/extracted_features_dataset.py

Prompts

```
['create an ExtractedFeaturesDataset from pre-extracted wav2vec feature NPY files with length filtering', 'load extracted features dataset with optional label files and auxiliary target postfix for supervised training', 'collate a batch of feature samples into padded tensors with padding masks for model input', 'retrieve a single feature sample by index with optional target labels and auxiliary targets', 'generate ordered indices for batching samples by length with optional shuffling enabled', 'create a RandomInputDataset that wraps a fairseq dataset and replaces inputs with random samples', 'review the RandomInputDataset get_target method that navigates nested dicts via input_key_path', 'review the RandomInputDataset get_target_value method that extracts the value at the target key path', 'review the RandomInputDataset __getitem__ method that replaces input values with random choices from random_input_dataset', 'review the RandomInputDataset collater method that collates samples and replaces input tokens with random_inputs']
```

Usage

```
{'create_dataset_from_features': 'create an ExtractedFeaturesDataset from pre-extracted wav2vec feature NPY files with length filtering', 'load_features_with_labels': 'load extracted features dataset with optional label files and auxiliary target postfix for supervised training', 'collate_feature_samples': 'collate a batch of feature samples into padded tensors with padding masks for model input', 'get_feature_item': 'retrieve a single feature sample by index with optional target labels and auxiliary targets', 'order_indices_by_length': 'generate ordered indices for batching samples by length with optional shuffling enabled'}
```

## File: facebookresearch_fairseq/examples/wav2vec/unsupervised/data/random_input_dataset.py

Prompts

```
['create an ExtractedFeaturesDataset from pre-extracted wav2vec feature NPY files with length filtering', 'load extracted features dataset with optional label files and auxiliary target postfix for supervised training', 'collate a batch of feature samples into padded tensors with padding masks for model input', 'retrieve a single feature sample by index with optional target labels and auxiliary targets', 'generate ordered indices for batching samples by length with optional shuffling enabled', 'create a RandomInputDataset that wraps a fairseq dataset and replaces inputs with random samples', 'review the RandomInputDataset get_target method that navigates nested dicts via input_key_path', 'review the RandomInputDataset get_target_value method that extracts the value at the target key path', 'review the RandomInputDataset __getitem__ method that replaces input values with random choices from random_input_dataset', 'review the RandomInputDataset collater method that collates samples and replaces input tokens with random_inputs']
```

Usage

```
{'create_random_input_dataset': 'create a RandomInputDataset that wraps a fairseq dataset and replaces inputs with random samples', 'review_get_target': 'review the RandomInputDataset get_target method that navigates nested dicts via input_key_path', 'review_get_target_value': 'review the RandomInputDataset get_target_value method that extracts the value at the target key path', 'review_getitem': 'review the RandomInputDataset __getitem__ method that replaces input values with random choices from random_input_dataset', 'review_collater': 'review the RandomInputDataset collater method that collates samples and replaces input tokens with random_inputs'}
```


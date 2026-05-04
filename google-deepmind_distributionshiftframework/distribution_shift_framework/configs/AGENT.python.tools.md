# Agent Python Tools

- repo: google-deepmind/distributionshiftframework
- repo_uri: https://github.com/google-deepmind/distribution_shift_framework

## File: google-deepmind_distributionshiftframework/distribution_shift_framework/configs/disentanglement_config.py

Prompts

```
['create a ConfigDict for a disentanglement dataset with specified label and property label for train and test splits', 'create a ConfigDict to load the full training and test dataset without filtering or subsampling', 'create a base disentanglement dataset config with no filtering and full data for the given label and property', 'create an out-of-distribution dataset config that filters training data to a subset of property values', 'create a correlated dataset config where label and property values are equal with balanced sampling weights']
```

Usage

```
{'get_data_config': 'create a ConfigDict for a disentanglement dataset with specified label and property label for train and test splits', 'get_alldata_config': 'create a ConfigDict to load the full training and test dataset without filtering or subsampling', 'get_base_renderers': 'create a base disentanglement dataset config with no filtering and full data for the given label and property', 'get_ood_renderers': 'create an out-of-distribution dataset config that filters training data to a subset of property values', 'get_correlated_renderers': 'create a correlated dataset config where label and property values are equal with balanced sampling weights'}
```


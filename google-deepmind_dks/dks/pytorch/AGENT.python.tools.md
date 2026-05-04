# Agent Python Tools

- repo: google-deepmind/dks
- repo_uri: https://github.com/google-deepmind/dks

## File: google-deepmind_dks/dks/pytorch/activation_transform.py

Prompts

```
['apply activation transformations to PyTorch tensors using the DKS/TAT framework with named activation functions', 'look up a PyTorch activation function by string name such as gelu relu or bentid', 'compute the GELU approximation formula on a PyTorch tensor using the tanh-based approach', 'apply the bentid activation function which computes sqrt(x^2+1)-1 over 2 plus x', 'review the PyTorch activation transform module that wraps DKS base transformations with PyTorch-specific activation lookups', 'apply per-location normalization to a PyTorch tensor using default homog_mode one', 'apply per-location normalization to a PyTorch tensor using homog_mode avg_q for mean-squared homogeneous coordinate', 'apply per-location normalization to a PyTorch tensor with homog_mode off to skip homogeneous coordinate', 'apply per-location normalization to a PyTorch tensor with a custom homog_scale value', 'apply per-location normalization to a single-sample PyTorch tensor without a batch dimension', 'initialize convolutional filter bank weights using the SUO distribution with Delta initialization', 'initialize fully-connected layer weights using the SUO distribution with orthogonal initialization', 'rescale sampled weights by max(sqrt(out_dim / in_dim), 1) to preserve q values at initialization', 'apply an additional gain scale factor on top of the standard SUO rescaling for weight initialization', 'zero out all convolutional weights except those at the central location of the filter bank']
```

Usage

```
{'get_transformed_activations': 'apply activation transformations to PyTorch tensors using the DKS/TAT framework with named activation functions', 'get_pytorch_activation_by_name': 'look up a PyTorch activation function by string name such as gelu relu or bentid', 'apply_gelu_approximation': 'compute the GELU approximation formula on a PyTorch tensor using the tanh-based approach', 'use_bentid_activation': 'apply the bentid activation function which computes sqrt(x^2+1)-1 over 2 plus x', 'review_activation_transform_module': 'review the PyTorch activation transform module that wraps DKS base transformations with PyTorch-specific activation lookups'}
```

## File: google-deepmind_dks/dks/pytorch/data_preprocessing.py

Prompts

```
['apply activation transformations to PyTorch tensors using the DKS/TAT framework with named activation functions', 'look up a PyTorch activation function by string name such as gelu relu or bentid', 'compute the GELU approximation formula on a PyTorch tensor using the tanh-based approach', 'apply the bentid activation function which computes sqrt(x^2+1)-1 over 2 plus x', 'review the PyTorch activation transform module that wraps DKS base transformations with PyTorch-specific activation lookups', 'apply per-location normalization to a PyTorch tensor using default homog_mode one', 'apply per-location normalization to a PyTorch tensor using homog_mode avg_q for mean-squared homogeneous coordinate', 'apply per-location normalization to a PyTorch tensor with homog_mode off to skip homogeneous coordinate', 'apply per-location normalization to a PyTorch tensor with a custom homog_scale value', 'apply per-location normalization to a single-sample PyTorch tensor without a batch dimension', 'initialize convolutional filter bank weights using the SUO distribution with Delta initialization', 'initialize fully-connected layer weights using the SUO distribution with orthogonal initialization', 'rescale sampled weights by max(sqrt(out_dim / in_dim), 1) to preserve q values at initialization', 'apply an additional gain scale factor on top of the standard SUO rescaling for weight initialization', 'zero out all convolutional weights except those at the central location of the filter bank']
```

Usage

```
{'apply_per_location_normalization_default': 'apply per-location normalization to a PyTorch tensor using default homog_mode one', 'apply_per_location_normalization_avg_q': 'apply per-location normalization to a PyTorch tensor using homog_mode avg_q for mean-squared homogeneous coordinate', 'apply_per_location_normalization_no_homog': 'apply per-location normalization to a PyTorch tensor with homog_mode off to skip homogeneous coordinate', 'apply_per_location_normalization_scaled': 'apply per-location normalization to a PyTorch tensor with a custom homog_scale value', 'apply_per_location_normalization_no_batch': 'apply per-location normalization to a single-sample PyTorch tensor without a batch dimension'}
```

## File: google-deepmind_dks/dks/pytorch/parameter_sampling_functions.py

Prompts

```
['apply activation transformations to PyTorch tensors using the DKS/TAT framework with named activation functions', 'look up a PyTorch activation function by string name such as gelu relu or bentid', 'compute the GELU approximation formula on a PyTorch tensor using the tanh-based approach', 'apply the bentid activation function which computes sqrt(x^2+1)-1 over 2 plus x', 'review the PyTorch activation transform module that wraps DKS base transformations with PyTorch-specific activation lookups', 'apply per-location normalization to a PyTorch tensor using default homog_mode one', 'apply per-location normalization to a PyTorch tensor using homog_mode avg_q for mean-squared homogeneous coordinate', 'apply per-location normalization to a PyTorch tensor with homog_mode off to skip homogeneous coordinate', 'apply per-location normalization to a PyTorch tensor with a custom homog_scale value', 'apply per-location normalization to a single-sample PyTorch tensor without a batch dimension', 'initialize convolutional filter bank weights using the SUO distribution with Delta initialization', 'initialize fully-connected layer weights using the SUO distribution with orthogonal initialization', 'rescale sampled weights by max(sqrt(out_dim / in_dim), 1) to preserve q values at initialization', 'apply an additional gain scale factor on top of the standard SUO rescaling for weight initialization', 'zero out all convolutional weights except those at the central location of the filter bank']
```

Usage

```
{'init_conv_weights_delta': 'initialize convolutional filter bank weights using the SUO distribution with Delta initialization', 'init_fc_weights_orthogonal': 'initialize fully-connected layer weights using the SUO distribution with orthogonal initialization', 'rescale_weights_by_dim_ratio': 'rescale sampled weights by max(sqrt(out_dim / in_dim), 1) to preserve q values at initialization', 'apply_gain_to_suo_weights': 'apply an additional gain scale factor on top of the standard SUO rescaling for weight initialization', 'zero_noncentral_conv_weights': 'zero out all convolutional weights except those at the central location of the filter bank'}
```


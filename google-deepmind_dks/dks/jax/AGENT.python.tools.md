# Agent Python Tools

- repo: google-deepmind/dks
- repo_uri: https://github.com/google-deepmind/dks

## File: google-deepmind_dks/dks/jax/activation_transform.py

Prompts

```
['get a JAX activation function by name such as bentid, softsign, gelu, or gelu_exact', 'get transformed activation functions for a list of activation names using JAX tensors', 'lookup an activation function from jax.numpy by its attribute name', 'lookup an activation function from jax.nn by its attribute name', 'lookup an activation function from jax.lax by its attribute name', 'apply per-location normalization to a JAX array with default homogeneous coordinate mode set to one', 'apply per-location normalization using avg_q homogeneous mode to preserve mean squared values across non-batch axes', 'apply per-location normalization with homogeneous coordinate mode off for datasets with large feature dimensions', 'apply per-location normalization with a custom homog_scale factor to rescale the appended homogeneous coordinate', 'apply per-location normalization to a single sample JAX array without a batch dimension', 'sample an orthogonal matrix from the Haar distribution using _uniform_orthogonal with a JAX PRNG key', 'initialize fully-connected layer weights using scaled_uniform_orthogonal with the SUO distribution and a PRNG key', 'initialize convolutional filter bank weights with Delta initialization using scaled_uniform_orthogonal and delta=True', 'review the scaled_uniform_orthogonal function to understand SUO distribution rescaling and Delta initialization logic', 'summarize the parameter_sampling_functions module and its SUO weight initialization approach for DKS/TAT']
```

Usage

```
{'get_jax_activation_by_name': 'get a JAX activation function by name such as bentid, softsign, gelu, or gelu_exact', 'get_transformed_activations_jax': 'get transformed activation functions for a list of activation names using JAX tensors', 'lookup_activation_jnp': 'lookup an activation function from jax.numpy by its attribute name', 'lookup_activation_jax_nn': 'lookup an activation function from jax.nn by its attribute name', 'lookup_activation_jax_lax': 'lookup an activation function from jax.lax by its attribute name'}
```

## File: google-deepmind_dks/dks/jax/data_preprocessing.py

Prompts

```
['get a JAX activation function by name such as bentid, softsign, gelu, or gelu_exact', 'get transformed activation functions for a list of activation names using JAX tensors', 'lookup an activation function from jax.numpy by its attribute name', 'lookup an activation function from jax.nn by its attribute name', 'lookup an activation function from jax.lax by its attribute name', 'apply per-location normalization to a JAX array with default homogeneous coordinate mode set to one', 'apply per-location normalization using avg_q homogeneous mode to preserve mean squared values across non-batch axes', 'apply per-location normalization with homogeneous coordinate mode off for datasets with large feature dimensions', 'apply per-location normalization with a custom homog_scale factor to rescale the appended homogeneous coordinate', 'apply per-location normalization to a single sample JAX array without a batch dimension', 'sample an orthogonal matrix from the Haar distribution using _uniform_orthogonal with a JAX PRNG key', 'initialize fully-connected layer weights using scaled_uniform_orthogonal with the SUO distribution and a PRNG key', 'initialize convolutional filter bank weights with Delta initialization using scaled_uniform_orthogonal and delta=True', 'review the scaled_uniform_orthogonal function to understand SUO distribution rescaling and Delta initialization logic', 'summarize the parameter_sampling_functions module and its SUO weight initialization approach for DKS/TAT']
```

Usage

```
{'apply_per_location_normalization_default': 'apply per-location normalization to a JAX array with default homogeneous coordinate mode set to one', 'apply_per_location_normalization_avg_q': 'apply per-location normalization using avg_q homogeneous mode to preserve mean squared values across non-batch axes', 'apply_per_location_normalization_no_homog': 'apply per-location normalization with homogeneous coordinate mode off for datasets with large feature dimensions', 'apply_per_location_normalization_scaled': 'apply per-location normalization with a custom homog_scale factor to rescale the appended homogeneous coordinate', 'apply_per_location_normalization_no_batch': 'apply per-location normalization to a single sample JAX array without a batch dimension'}
```

## File: google-deepmind_dks/dks/jax/parameter_sampling_functions.py

Prompts

```
['get a JAX activation function by name such as bentid, softsign, gelu, or gelu_exact', 'get transformed activation functions for a list of activation names using JAX tensors', 'lookup an activation function from jax.numpy by its attribute name', 'lookup an activation function from jax.nn by its attribute name', 'lookup an activation function from jax.lax by its attribute name', 'apply per-location normalization to a JAX array with default homogeneous coordinate mode set to one', 'apply per-location normalization using avg_q homogeneous mode to preserve mean squared values across non-batch axes', 'apply per-location normalization with homogeneous coordinate mode off for datasets with large feature dimensions', 'apply per-location normalization with a custom homog_scale factor to rescale the appended homogeneous coordinate', 'apply per-location normalization to a single sample JAX array without a batch dimension', 'sample an orthogonal matrix from the Haar distribution using _uniform_orthogonal with a JAX PRNG key', 'initialize fully-connected layer weights using scaled_uniform_orthogonal with the SUO distribution and a PRNG key', 'initialize convolutional filter bank weights with Delta initialization using scaled_uniform_orthogonal and delta=True', 'review the scaled_uniform_orthogonal function to understand SUO distribution rescaling and Delta initialization logic', 'summarize the parameter_sampling_functions module and its SUO weight initialization approach for DKS/TAT']
```

Usage

```
{'sample_uniform_orthogonal_matrix': 'sample an orthogonal matrix from the Haar distribution using _uniform_orthogonal with a JAX PRNG key', 'init_suo_weights': 'initialize fully-connected layer weights using scaled_uniform_orthogonal with the SUO distribution and a PRNG key', 'init_delta_conv_weights': 'initialize convolutional filter bank weights with Delta initialization using scaled_uniform_orthogonal and delta=True', 'review_scaled_uniform_orthogonal': 'review the scaled_uniform_orthogonal function to understand SUO distribution rescaling and Delta initialization logic', 'summarize_parameter_sampling': 'summarize the parameter_sampling_functions module and its SUO weight initialization approach for DKS/TAT'}
```


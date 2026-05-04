# Agent Python Tools

- repo: google-deepmind/dks
- repo_uri: https://github.com/google-deepmind/dks

## File: google-deepmind_dks/dks/tensorflow/activation_transform.py

Prompts

```
['get a TensorFlow activation function by name such as bentid, erf, atan, asinh, leaky_relu, gelu, or gelu_exact', 'get a dictionary of transformed activation functions for DKS or TAT methods using TensorFlow', 'use the bentid activation function which computes (sqrt(x^2+1)-1)/2 + x in TensorFlow', 'use the gelu activation function with approximate or exact mode via the TensorFlow activation getter', 'use any standard tf.nn activation function by name through the TensorFlow activation getter', 'apply Per-Location Normalization to a TensorFlow tensor for DKS/TAT preprocessing', 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to one', 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to avg_q', 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to off', 'normalize a TensorFlow tensor using per-location normalization with a custom homog_scale value', 'build a TensorFlow weight initializer using stateless_scaled_uniform_orthogonal for DKS/TAT neural network layers', 'create convolutional filter bank weights with Delta initialization using stateless_scaled_uniform_orthogonal', 'sample a stateless orthogonal matrix from the Haar distribution using _stateless_uniform_orthogonal', 'review the stateless_scaled_uniform_orthogonal function to understand SUO distribution and Delta initialization logic', 'test the _stateless_uniform_orthogonal function QR factorization and uniform sign correction steps']
```

Usage

```
{'get_tf_activation_by_name': 'get a TensorFlow activation function by name such as bentid, erf, atan, asinh, leaky_relu, gelu, or gelu_exact', 'get_transformed_activations': 'get a dictionary of transformed activation functions for DKS or TAT methods using TensorFlow', 'use_bentid_activation': 'use the bentid activation function which computes (sqrt(x^2+1)-1)/2 + x in TensorFlow', 'use_gelu_activation': 'use the gelu activation function with approximate or exact mode via the TensorFlow activation getter', 'use_standard_tf_activation': 'use any standard tf.nn activation function by name through the TensorFlow activation getter'}
```

## File: google-deepmind_dks/dks/tensorflow/data_preprocessing.py

Prompts

```
['get a TensorFlow activation function by name such as bentid, erf, atan, asinh, leaky_relu, gelu, or gelu_exact', 'get a dictionary of transformed activation functions for DKS or TAT methods using TensorFlow', 'use the bentid activation function which computes (sqrt(x^2+1)-1)/2 + x in TensorFlow', 'use the gelu activation function with approximate or exact mode via the TensorFlow activation getter', 'use any standard tf.nn activation function by name through the TensorFlow activation getter', 'apply Per-Location Normalization to a TensorFlow tensor for DKS/TAT preprocessing', 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to one', 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to avg_q', 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to off', 'normalize a TensorFlow tensor using per-location normalization with a custom homog_scale value', 'build a TensorFlow weight initializer using stateless_scaled_uniform_orthogonal for DKS/TAT neural network layers', 'create convolutional filter bank weights with Delta initialization using stateless_scaled_uniform_orthogonal', 'sample a stateless orthogonal matrix from the Haar distribution using _stateless_uniform_orthogonal', 'review the stateless_scaled_uniform_orthogonal function to understand SUO distribution and Delta initialization logic', 'test the _stateless_uniform_orthogonal function QR factorization and uniform sign correction steps']
```

Usage

```
{'apply_per_location_normalization': 'apply Per-Location Normalization to a TensorFlow tensor for DKS/TAT preprocessing', 'normalize_tensor_with_homog_one': 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to one', 'normalize_tensor_with_avg_q': 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to avg_q', 'normalize_tensor_no_homog': 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to off', 'normalize_tensor_with_scale': 'normalize a TensorFlow tensor using per-location normalization with a custom homog_scale value'}
```

## File: google-deepmind_dks/dks/tensorflow/parameter_sampling_functions.py

Prompts

```
['get a TensorFlow activation function by name such as bentid, erf, atan, asinh, leaky_relu, gelu, or gelu_exact', 'get a dictionary of transformed activation functions for DKS or TAT methods using TensorFlow', 'use the bentid activation function which computes (sqrt(x^2+1)-1)/2 + x in TensorFlow', 'use the gelu activation function with approximate or exact mode via the TensorFlow activation getter', 'use any standard tf.nn activation function by name through the TensorFlow activation getter', 'apply Per-Location Normalization to a TensorFlow tensor for DKS/TAT preprocessing', 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to one', 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to avg_q', 'normalize a TensorFlow tensor using per-location normalization with homog_mode set to off', 'normalize a TensorFlow tensor using per-location normalization with a custom homog_scale value', 'build a TensorFlow weight initializer using stateless_scaled_uniform_orthogonal for DKS/TAT neural network layers', 'create convolutional filter bank weights with Delta initialization using stateless_scaled_uniform_orthogonal', 'sample a stateless orthogonal matrix from the Haar distribution using _stateless_uniform_orthogonal', 'review the stateless_scaled_uniform_orthogonal function to understand SUO distribution and Delta initialization logic', 'test the _stateless_uniform_orthogonal function QR factorization and uniform sign correction steps']
```

Usage

```
{'build_suo_weight_initializer': 'build a TensorFlow weight initializer using stateless_scaled_uniform_orthogonal for DKS/TAT neural network layers', 'create_delta_conv_weights': 'create convolutional filter bank weights with Delta initialization using stateless_scaled_uniform_orthogonal', 'sample_orthogonal_matrix': 'sample a stateless orthogonal matrix from the Haar distribution using _stateless_uniform_orthogonal', 'review_suo_distribution': 'review the stateless_scaled_uniform_orthogonal function to understand SUO distribution and Delta initialization logic', 'test_orthogonal_qr_factorization': 'test the _stateless_uniform_orthogonal function QR factorization and uniform sign correction steps'}
```


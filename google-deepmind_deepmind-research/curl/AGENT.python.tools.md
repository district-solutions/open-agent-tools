# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/curl/model.py

Prompts

```
['build a CURL model instance with shared encoder, cluster encoder, latent encoder, and data decoder components', 'create a SharedEncoder module that maps input tensors to hidden representations using conv or mlp encoder types', 'run the Curl sample method to draw samples from the learned generative distribution p(x)', 'run the Curl reconstruct method to reconstruct observed inputs through the encoder-decoder pipeline', 'build an UpsampleModule convolutional decoder with transposed convolutions or resize-based upsampling for image generation', 'run the CURL training script on MNIST or Omniglot datasets with configurable hyperparameters', 'create dataset iterators for training validation and test splits from a TensorFlow dataset', 'build TensorFlow graph ops for ELBO loss confusion matrix and purity metrics', 'process a dataset by computing TensorFlow ops batch by batch and aggregating results', 'set up TensorFlow ops to dynamically copy mixture component weights for expansion', 'run training on MNIST dataset with a multi-layer encoder and single-layer decoder for continual learning', 'test the run_training function with MNIST dataset using sequential training data and fixed replay', 'run training with a custom multi-layer encoder configuration specifying layer sizes and strides', 'run training with supervised learning enabled and supervised replay for classification tasks', 'test training with dynamic expansion enabled and a log-likelihood threshold for continual learning', 'generate a Gaussian distribution from logits using exp or softplus sigma nonlinearity and var or std parameterization', 'construct a uniform prior probability tensor for categorical cluster components with padding for inactive components', 'center crop a 4D tensor layer to match a target height and width shape', 'review the generate_gaussian function to understand sigma nonlinearity and parameterization options for TensorFlow probability distributions', 'test the construct_prior_probs function to verify uniform prior tensor shapes and padding behavior']
```

Usage

```
{'build_Curl_model': 'build a CURL model instance with shared encoder, cluster encoder, latent encoder, and data decoder components', 'create_SharedEncoder': 'create a SharedEncoder module that maps input tensors to hidden representations using conv or mlp encoder types', 'run_Curl_sample': 'run the Curl sample method to draw samples from the learned generative distribution p(x)', 'run_Curl_reconstruct': 'run the Curl reconstruct method to reconstruct observed inputs through the encoder-decoder pipeline', 'build_UpsampleModule': 'build an UpsampleModule convolutional decoder with transposed convolutions or resize-based upsampling for image generation'}
```

## File: google-deepmind_deepmind-research/curl/training.py

Prompts

```
['build a CURL model instance with shared encoder, cluster encoder, latent encoder, and data decoder components', 'create a SharedEncoder module that maps input tensors to hidden representations using conv or mlp encoder types', 'run the Curl sample method to draw samples from the learned generative distribution p(x)', 'run the Curl reconstruct method to reconstruct observed inputs through the encoder-decoder pipeline', 'build an UpsampleModule convolutional decoder with transposed convolutions or resize-based upsampling for image generation', 'run the CURL training script on MNIST or Omniglot datasets with configurable hyperparameters', 'create dataset iterators for training validation and test splits from a TensorFlow dataset', 'build TensorFlow graph ops for ELBO loss confusion matrix and purity metrics', 'process a dataset by computing TensorFlow ops batch by batch and aggregating results', 'set up TensorFlow ops to dynamically copy mixture component weights for expansion', 'run training on MNIST dataset with a multi-layer encoder and single-layer decoder for continual learning', 'test the run_training function with MNIST dataset using sequential training data and fixed replay', 'run training with a custom multi-layer encoder configuration specifying layer sizes and strides', 'run training with supervised learning enabled and supervised replay for classification tasks', 'test training with dynamic expansion enabled and a log-likelihood threshold for continual learning', 'generate a Gaussian distribution from logits using exp or softplus sigma nonlinearity and var or std parameterization', 'construct a uniform prior probability tensor for categorical cluster components with padding for inactive components', 'center crop a 4D tensor layer to match a target height and width shape', 'review the generate_gaussian function to understand sigma nonlinearity and parameterization options for TensorFlow probability distributions', 'test the construct_prior_probs function to verify uniform prior tensor shapes and padding behavior']
```

Usage

```
{'run_training_curl': 'run the CURL training script on MNIST or Omniglot datasets with configurable hyperparameters', 'get_data_sources': 'create dataset iterators for training validation and test splits from a TensorFlow dataset', 'setup_training_and_eval_graphs': 'build TensorFlow graph ops for ELBO loss confusion matrix and purity metrics', 'process_dataset': 'process a dataset by computing TensorFlow ops batch by batch and aggregating results', 'setup_dynamic_ops': 'set up TensorFlow ops to dynamically copy mixture component weights for expansion'}
```

## File: google-deepmind_deepmind-research/curl/unit_test.py

Prompts

```
['build a CURL model instance with shared encoder, cluster encoder, latent encoder, and data decoder components', 'create a SharedEncoder module that maps input tensors to hidden representations using conv or mlp encoder types', 'run the Curl sample method to draw samples from the learned generative distribution p(x)', 'run the Curl reconstruct method to reconstruct observed inputs through the encoder-decoder pipeline', 'build an UpsampleModule convolutional decoder with transposed convolutions or resize-based upsampling for image generation', 'run the CURL training script on MNIST or Omniglot datasets with configurable hyperparameters', 'create dataset iterators for training validation and test splits from a TensorFlow dataset', 'build TensorFlow graph ops for ELBO loss confusion matrix and purity metrics', 'process a dataset by computing TensorFlow ops batch by batch and aggregating results', 'set up TensorFlow ops to dynamically copy mixture component weights for expansion', 'run training on MNIST dataset with a multi-layer encoder and single-layer decoder for continual learning', 'test the run_training function with MNIST dataset using sequential training data and fixed replay', 'run training with a custom multi-layer encoder configuration specifying layer sizes and strides', 'run training with supervised learning enabled and supervised replay for classification tasks', 'test training with dynamic expansion enabled and a log-likelihood threshold for continual learning', 'generate a Gaussian distribution from logits using exp or softplus sigma nonlinearity and var or std parameterization', 'construct a uniform prior probability tensor for categorical cluster components with padding for inactive components', 'center crop a 4D tensor layer to match a target height and width shape', 'review the generate_gaussian function to understand sigma nonlinearity and parameterization options for TensorFlow probability distributions', 'test the construct_prior_probs function to verify uniform prior tensor shapes and padding behavior']
```

Usage

```
{'run_training_mnist': 'run training on MNIST dataset with a multi-layer encoder and single-layer decoder for continual learning', 'test_training_run_training': 'test the run_training function with MNIST dataset using sequential training data and fixed replay', 'run_training_custom_encoder': 'run training with a custom multi-layer encoder configuration specifying layer sizes and strides', 'run_training_supervised': 'run training with supervised learning enabled and supervised replay for classification tasks', 'test_training_dynamic_expansion': 'test training with dynamic expansion enabled and a log-likelihood threshold for continual learning'}
```

## File: google-deepmind_deepmind-research/curl/utils.py

Prompts

```
['build a CURL model instance with shared encoder, cluster encoder, latent encoder, and data decoder components', 'create a SharedEncoder module that maps input tensors to hidden representations using conv or mlp encoder types', 'run the Curl sample method to draw samples from the learned generative distribution p(x)', 'run the Curl reconstruct method to reconstruct observed inputs through the encoder-decoder pipeline', 'build an UpsampleModule convolutional decoder with transposed convolutions or resize-based upsampling for image generation', 'run the CURL training script on MNIST or Omniglot datasets with configurable hyperparameters', 'create dataset iterators for training validation and test splits from a TensorFlow dataset', 'build TensorFlow graph ops for ELBO loss confusion matrix and purity metrics', 'process a dataset by computing TensorFlow ops batch by batch and aggregating results', 'set up TensorFlow ops to dynamically copy mixture component weights for expansion', 'run training on MNIST dataset with a multi-layer encoder and single-layer decoder for continual learning', 'test the run_training function with MNIST dataset using sequential training data and fixed replay', 'run training with a custom multi-layer encoder configuration specifying layer sizes and strides', 'run training with supervised learning enabled and supervised replay for classification tasks', 'test training with dynamic expansion enabled and a log-likelihood threshold for continual learning', 'generate a Gaussian distribution from logits using exp or softplus sigma nonlinearity and var or std parameterization', 'construct a uniform prior probability tensor for categorical cluster components with padding for inactive components', 'center crop a 4D tensor layer to match a target height and width shape', 'review the generate_gaussian function to understand sigma nonlinearity and parameterization options for TensorFlow probability distributions', 'test the construct_prior_probs function to verify uniform prior tensor shapes and padding behavior']
```

Usage

```
{'generate_gaussian_distribution': 'generate a Gaussian distribution from logits using exp or softplus sigma nonlinearity and var or std parameterization', 'construct_prior_probabilities': 'construct a uniform prior probability tensor for categorical cluster components with padding for inactive components', 'center_crop_layer': 'center crop a 4D tensor layer to match a target height and width shape', 'review_generate_gaussian': 'review the generate_gaussian function to understand sigma nonlinearity and parameterization options for TensorFlow probability distributions', 'test_construct_prior_probs': 'test the construct_prior_probs function to verify uniform prior tensor shapes and padding behavior'}
```


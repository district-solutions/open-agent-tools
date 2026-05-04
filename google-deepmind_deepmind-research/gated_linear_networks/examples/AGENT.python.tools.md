# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/gated_linear_networks/examples/bernoulli_mnist.py

Prompts

```
['run the Bernoulli GLN MNIST classification training loop with configurable layers and learning rate', 'build a Bernoulli GatedLinearNetwork classifier with LastNeuronAggregator for binary classification', 'extract standardized and sigmoid features from MNIST images using MeanStdEstimator', 'initialize a one-vs-all GLN classifier with vmap across all MNIST classes', 'update GLN classifier weights online with a decaying learning rate schedule and log-loss tracking', 'load the MNIST dataset from TensorFlow Datasets and return deskewed images as a numpy array', 'deskew a dataset of images by computing moments and applying an affine transform to each image', 'deskew a single image by computing its moments and applying a shear correction via affine transform', 'compute the first and second statistical moments of an image including the mean vector and covariance matrix', "estimate the running mean and standard deviation of samples using Welford's online algorithm with Haiku state", 'test the MeanStdEstimator class computes correct mean and std over streaming samples', 'run MeanStdEstimator using haiku transform_with_state to track running mean and std', 'test MeanStdEstimator apply function wrapped with jax.jit for accelerated inference', 'review the MeanStdEstimator online estimation pattern using haiku stateful transforms', 'summarize the MeanStdEstimator test that validates streaming mean and std accuracy']
```

Usage

```
{'run_bernoulli_gln_mnist_training': 'run the Bernoulli GLN MNIST classification training loop with configurable layers and learning rate', 'build_gln_classifier_network': 'build a Bernoulli GatedLinearNetwork classifier with LastNeuronAggregator for binary classification', 'extract_mnist_image_features': 'extract standardized and sigmoid features from MNIST images using MeanStdEstimator', 'initialize_one_vs_all_classifier': 'initialize a one-vs-all GLN classifier with vmap across all MNIST classes', 'update_gln_weights_online': 'update GLN classifier weights online with a decaying learning rate schedule and log-loss tracking'}
```

## File: google-deepmind_deepmind-research/gated_linear_networks/examples/utils.py

Prompts

```
['run the Bernoulli GLN MNIST classification training loop with configurable layers and learning rate', 'build a Bernoulli GatedLinearNetwork classifier with LastNeuronAggregator for binary classification', 'extract standardized and sigmoid features from MNIST images using MeanStdEstimator', 'initialize a one-vs-all GLN classifier with vmap across all MNIST classes', 'update GLN classifier weights online with a decaying learning rate schedule and log-loss tracking', 'load the MNIST dataset from TensorFlow Datasets and return deskewed images as a numpy array', 'deskew a dataset of images by computing moments and applying an affine transform to each image', 'deskew a single image by computing its moments and applying a shear correction via affine transform', 'compute the first and second statistical moments of an image including the mean vector and covariance matrix', "estimate the running mean and standard deviation of samples using Welford's online algorithm with Haiku state", 'test the MeanStdEstimator class computes correct mean and std over streaming samples', 'run MeanStdEstimator using haiku transform_with_state to track running mean and std', 'test MeanStdEstimator apply function wrapped with jax.jit for accelerated inference', 'review the MeanStdEstimator online estimation pattern using haiku stateful transforms', 'summarize the MeanStdEstimator test that validates streaming mean and std accuracy']
```

Usage

```
{'load_deskewed_mnist': 'load the MNIST dataset from TensorFlow Datasets and return deskewed images as a numpy array', 'deskew_dataset': 'deskew a dataset of images by computing moments and applying an affine transform to each image', 'deskew_image': 'deskew a single image by computing its moments and applying a shear correction via affine transform', 'compute_image_moments': 'compute the first and second statistical moments of an image including the mean vector and covariance matrix', 'estimate_mean_std': "estimate the running mean and standard deviation of samples using Welford's online algorithm with Haiku state"}
```

## File: google-deepmind_deepmind-research/gated_linear_networks/examples/utils_test.py

Prompts

```
['run the Bernoulli GLN MNIST classification training loop with configurable layers and learning rate', 'build a Bernoulli GatedLinearNetwork classifier with LastNeuronAggregator for binary classification', 'extract standardized and sigmoid features from MNIST images using MeanStdEstimator', 'initialize a one-vs-all GLN classifier with vmap across all MNIST classes', 'update GLN classifier weights online with a decaying learning rate schedule and log-loss tracking', 'load the MNIST dataset from TensorFlow Datasets and return deskewed images as a numpy array', 'deskew a dataset of images by computing moments and applying an affine transform to each image', 'deskew a single image by computing its moments and applying a shear correction via affine transform', 'compute the first and second statistical moments of an image including the mean vector and covariance matrix', "estimate the running mean and standard deviation of samples using Welford's online algorithm with Haiku state", 'test the MeanStdEstimator class computes correct mean and std over streaming samples', 'run MeanStdEstimator using haiku transform_with_state to track running mean and std', 'test MeanStdEstimator apply function wrapped with jax.jit for accelerated inference', 'review the MeanStdEstimator online estimation pattern using haiku stateful transforms', 'summarize the MeanStdEstimator test that validates streaming mean and std accuracy']
```

Usage

```
{'test_MeanStdEstimator_statistics': 'test the MeanStdEstimator class computes correct mean and std over streaming samples', 'run_MeanStdEstimator_with_haiku_state': 'run MeanStdEstimator using haiku transform_with_state to track running mean and std', 'test_MeanStdEstimator_jit_compilation': 'test MeanStdEstimator apply function wrapped with jax.jit for accelerated inference', 'review_MeanStdEstimator_online_estimation': 'review the MeanStdEstimator online estimation pattern using haiku stateful transforms', 'summarize_MeanStdEstimator_test': 'summarize the MeanStdEstimator test that validates streaming mean and std accuracy'}
```


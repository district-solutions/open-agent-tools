# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/benchmarks/benchmark.py

Prompts

```
['run crypten function benchmarks comparing runtime and error against PyTorch for unary, binary, and layer operations', 'run crypten model benchmarks measuring training time, inference time, and accuracy for plain text and encrypted models', 'run the benchmark CLI with flags like --only-functions, --device cuda, --world-size 2, or --advanced-models', 'use the time_me decorator to measure average runtime with quartile statistics over multiple loops', 'benchmark multiparty encrypted model training across multiple processes using MultiProcessLauncher with optional TTP provider', 'generate Gaussian cluster data for binary classification using sklearn make_classification and return torch tensors', 'create a GaussianClusters instance with configurable n_samples and n_features for benchmark training data', 'preprocess a sample image with resize, center crop, to tensor, and normalize transforms for ImageNet inference', 'create an Images instance that loads and preprocesses dog.jpg with a one-hot encoded ImageNet class label', 'review the GaussianClusters class and its generate_data static method for binary classification benchmark data generation', 'create a plain PyTorch logistic regression model with a configurable number of input features', 'create a CrypTen secure MPC logistic regression model using crypten.nn.Linear layers', 'create a plain PyTorch feedforward neural network with three linear layers and ReLU activations', 'create a CrypTen secure MPC feedforward neural network with three encrypted linear layers', 'create a CrypTen secure ResNet model by converting a pretrained PyTorch ResNet using crypten.nn.from_pytorch', 'run historical CrypTen benchmarks across monthly dates for 1pc and 2pc modes', 'run historical CrypTen benchmarks and overwrite existing data directories with --overwrite flag', 'run historical CrypTen benchmarks with a specific CUDA toolkit version via --cuda-toolkit-version', 'generate a list of monthly date strings from October 2019 to the current month using get_dates', 'parse command line arguments for overwrite and cuda-toolkit-version options using parse_args']
```

Usage

```
{'run_crypten_function_benchmarks': 'run crypten function benchmarks comparing runtime and error against PyTorch for unary, binary, and layer operations', 'run_crypten_model_benchmarks': 'run crypten model benchmarks measuring training time, inference time, and accuracy for plain text and encrypted models', 'run_benchmark_cli': 'run the benchmark CLI with flags like --only-functions, --device cuda, --world-size 2, or --advanced-models', 'use_time_me_decorator': 'use the time_me decorator to measure average runtime with quartile statistics over multiple loops', 'benchmark_multiparty_training': 'benchmark multiparty encrypted model training across multiple processes using MultiProcessLauncher with optional TTP provider'}
```

## File: facebookresearch_crypten/benchmarks/data.py

Prompts

```
['run crypten function benchmarks comparing runtime and error against PyTorch for unary, binary, and layer operations', 'run crypten model benchmarks measuring training time, inference time, and accuracy for plain text and encrypted models', 'run the benchmark CLI with flags like --only-functions, --device cuda, --world-size 2, or --advanced-models', 'use the time_me decorator to measure average runtime with quartile statistics over multiple loops', 'benchmark multiparty encrypted model training across multiple processes using MultiProcessLauncher with optional TTP provider', 'generate Gaussian cluster data for binary classification using sklearn make_classification and return torch tensors', 'create a GaussianClusters instance with configurable n_samples and n_features for benchmark training data', 'preprocess a sample image with resize, center crop, to tensor, and normalize transforms for ImageNet inference', 'create an Images instance that loads and preprocesses dog.jpg with a one-hot encoded ImageNet class label', 'review the GaussianClusters class and its generate_data static method for binary classification benchmark data generation', 'create a plain PyTorch logistic regression model with a configurable number of input features', 'create a CrypTen secure MPC logistic regression model using crypten.nn.Linear layers', 'create a plain PyTorch feedforward neural network with three linear layers and ReLU activations', 'create a CrypTen secure MPC feedforward neural network with three encrypted linear layers', 'create a CrypTen secure ResNet model by converting a pretrained PyTorch ResNet using crypten.nn.from_pytorch', 'run historical CrypTen benchmarks across monthly dates for 1pc and 2pc modes', 'run historical CrypTen benchmarks and overwrite existing data directories with --overwrite flag', 'run historical CrypTen benchmarks with a specific CUDA toolkit version via --cuda-toolkit-version', 'generate a list of monthly date strings from October 2019 to the current month using get_dates', 'parse command line arguments for overwrite and cuda-toolkit-version options using parse_args']
```

Usage

```
{'generate_gaussian_cluster_data': 'generate Gaussian cluster data for binary classification using sklearn make_classification and return torch tensors', 'create_gaussian_clusters_instance': 'create a GaussianClusters instance with configurable n_samples and n_features for benchmark training data', 'preprocess_image_for_inference': 'preprocess a sample image with resize, center crop, to tensor, and normalize transforms for ImageNet inference', 'create_images_instance': 'create an Images instance that loads and preprocesses dog.jpg with a one-hot encoded ImageNet class label', 'review_gaussianclusters_class': 'review the GaussianClusters class and its generate_data static method for binary classification benchmark data generation'}
```

## File: facebookresearch_crypten/benchmarks/models.py

Prompts

```
['run crypten function benchmarks comparing runtime and error against PyTorch for unary, binary, and layer operations', 'run crypten model benchmarks measuring training time, inference time, and accuracy for plain text and encrypted models', 'run the benchmark CLI with flags like --only-functions, --device cuda, --world-size 2, or --advanced-models', 'use the time_me decorator to measure average runtime with quartile statistics over multiple loops', 'benchmark multiparty encrypted model training across multiple processes using MultiProcessLauncher with optional TTP provider', 'generate Gaussian cluster data for binary classification using sklearn make_classification and return torch tensors', 'create a GaussianClusters instance with configurable n_samples and n_features for benchmark training data', 'preprocess a sample image with resize, center crop, to tensor, and normalize transforms for ImageNet inference', 'create an Images instance that loads and preprocesses dog.jpg with a one-hot encoded ImageNet class label', 'review the GaussianClusters class and its generate_data static method for binary classification benchmark data generation', 'create a plain PyTorch logistic regression model with a configurable number of input features', 'create a CrypTen secure MPC logistic regression model using crypten.nn.Linear layers', 'create a plain PyTorch feedforward neural network with three linear layers and ReLU activations', 'create a CrypTen secure MPC feedforward neural network with three encrypted linear layers', 'create a CrypTen secure ResNet model by converting a pretrained PyTorch ResNet using crypten.nn.from_pytorch', 'run historical CrypTen benchmarks across monthly dates for 1pc and 2pc modes', 'run historical CrypTen benchmarks and overwrite existing data directories with --overwrite flag', 'run historical CrypTen benchmarks with a specific CUDA toolkit version via --cuda-toolkit-version', 'generate a list of monthly date strings from October 2019 to the current month using get_dates', 'parse command line arguments for overwrite and cuda-toolkit-version options using parse_args']
```

Usage

```
{'create_LogisticRegression': 'create a plain PyTorch logistic regression model with a configurable number of input features', 'create_LogisticRegressionCrypTen': 'create a CrypTen secure MPC logistic regression model using crypten.nn.Linear layers', 'create_FeedForward': 'create a plain PyTorch feedforward neural network with three linear layers and ReLU activations', 'create_FeedForwardCrypTen': 'create a CrypTen secure MPC feedforward neural network with three encrypted linear layers', 'create_ResNetCrypTen': 'create a CrypTen secure ResNet model by converting a pretrained PyTorch ResNet using crypten.nn.from_pytorch'}
```

## File: facebookresearch_crypten/benchmarks/run_historical_benchmarks.py

Prompts

```
['run crypten function benchmarks comparing runtime and error against PyTorch for unary, binary, and layer operations', 'run crypten model benchmarks measuring training time, inference time, and accuracy for plain text and encrypted models', 'run the benchmark CLI with flags like --only-functions, --device cuda, --world-size 2, or --advanced-models', 'use the time_me decorator to measure average runtime with quartile statistics over multiple loops', 'benchmark multiparty encrypted model training across multiple processes using MultiProcessLauncher with optional TTP provider', 'generate Gaussian cluster data for binary classification using sklearn make_classification and return torch tensors', 'create a GaussianClusters instance with configurable n_samples and n_features for benchmark training data', 'preprocess a sample image with resize, center crop, to tensor, and normalize transforms for ImageNet inference', 'create an Images instance that loads and preprocesses dog.jpg with a one-hot encoded ImageNet class label', 'review the GaussianClusters class and its generate_data static method for binary classification benchmark data generation', 'create a plain PyTorch logistic regression model with a configurable number of input features', 'create a CrypTen secure MPC logistic regression model using crypten.nn.Linear layers', 'create a plain PyTorch feedforward neural network with three linear layers and ReLU activations', 'create a CrypTen secure MPC feedforward neural network with three encrypted linear layers', 'create a CrypTen secure ResNet model by converting a pretrained PyTorch ResNet using crypten.nn.from_pytorch', 'run historical CrypTen benchmarks across monthly dates for 1pc and 2pc modes', 'run historical CrypTen benchmarks and overwrite existing data directories with --overwrite flag', 'run historical CrypTen benchmarks with a specific CUDA toolkit version via --cuda-toolkit-version', 'generate a list of monthly date strings from October 2019 to the current month using get_dates', 'parse command line arguments for overwrite and cuda-toolkit-version options using parse_args']
```

Usage

```
{'run_historical_benchmarks': 'run historical CrypTen benchmarks across monthly dates for 1pc and 2pc modes', 'run_benchmarks_with_overwrite': 'run historical CrypTen benchmarks and overwrite existing data directories with --overwrite flag', 'run_benchmarks_with_cuda_version': 'run historical CrypTen benchmarks with a specific CUDA toolkit version via --cuda-toolkit-version', 'generate_benchmark_dates': 'generate a list of monthly date strings from October 2019 to the current month using get_dates', 'parse_benchmark_args': 'parse command line arguments for overwrite and cuda-toolkit-version options using parse_args'}
```


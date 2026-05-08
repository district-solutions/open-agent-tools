# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/examples/meters.py

Prompts

```
['create an AverageMeter instance to track the running average of values over time', 'add a value with an optional count to an AverageMeter and retrieve the current average', 'reset an AverageMeter to clear its accumulated sum and count back to zero', 'create an AccuracyMeter to measure top-k accuracy for multi-class classification predictions', 'add model output and ground truth labels to an AccuracyMeter and retrieve top-k accuracy results', 'create a MultiProcessLauncher to spawn multiple Crypten MPC processes with a given world size', 'start all spawned subprocesses in the MultiProcessLauncher for parallel Crypten computation', 'join all subprocesses in the MultiProcessLauncher and assert zero exit codes', 'terminate all running subprocesses in the MultiProcessLauncher gracefully', 'run a user-defined function in a spawned subprocess with Crypten initialization and environment setup', 'run k-means clustering on a PyTorch tensor to find K cluster centers', 'run PCA on a PyTorch tensor to extract the top principal components', 'run one-hot encoding on a PyTorch long integer index vector', 'run k-means inference to compute cluster assignments for data points', 'run MNIST file processing to extract and save train and test data as .pt files']
```

Usage

```
{'create_average_meter': 'create an AverageMeter instance to track the running average of values over time', 'add_to_average_meter': 'add a value with an optional count to an AverageMeter and retrieve the current average', 'reset_average_meter': 'reset an AverageMeter to clear its accumulated sum and count back to zero', 'create_accuracy_meter': 'create an AccuracyMeter to measure top-k accuracy for multi-class classification predictions', 'add_to_accuracy_meter': 'add model output and ground truth labels to an AccuracyMeter and retrieve top-k accuracy results'}
```

## File: facebookresearch_crypten/examples/multiprocess_launcher.py

Prompts

```
['create an AverageMeter instance to track the running average of values over time', 'add a value with an optional count to an AverageMeter and retrieve the current average', 'reset an AverageMeter to clear its accumulated sum and count back to zero', 'create an AccuracyMeter to measure top-k accuracy for multi-class classification predictions', 'add model output and ground truth labels to an AccuracyMeter and retrieve top-k accuracy results', 'create a MultiProcessLauncher to spawn multiple Crypten MPC processes with a given world size', 'start all spawned subprocesses in the MultiProcessLauncher for parallel Crypten computation', 'join all subprocesses in the MultiProcessLauncher and assert zero exit codes', 'terminate all running subprocesses in the MultiProcessLauncher gracefully', 'run a user-defined function in a spawned subprocess with Crypten initialization and environment setup', 'run k-means clustering on a PyTorch tensor to find K cluster centers', 'run PCA on a PyTorch tensor to extract the top principal components', 'run one-hot encoding on a PyTorch long integer index vector', 'run k-means inference to compute cluster assignments for data points', 'run MNIST file processing to extract and save train and test data as .pt files']
```

Usage

```
{'create_multiprocess_launcher': 'create a MultiProcessLauncher to spawn multiple Crypten MPC processes with a given world size', 'start_multiprocess_launcher': 'start all spawned subprocesses in the MultiProcessLauncher for parallel Crypten computation', 'join_multiprocess_launcher': 'join all subprocesses in the MultiProcessLauncher and assert zero exit codes', 'terminate_multiprocess_launcher': 'terminate all running subprocesses in the MultiProcessLauncher gracefully', 'run_process_in_subprocess': 'run a user-defined function in a spawned subprocess with Crypten initialization and environment setup'}
```

## File: facebookresearch_crypten/examples/util.py

Prompts

```
['create an AverageMeter instance to track the running average of values over time', 'add a value with an optional count to an AverageMeter and retrieve the current average', 'reset an AverageMeter to clear its accumulated sum and count back to zero', 'create an AccuracyMeter to measure top-k accuracy for multi-class classification predictions', 'add model output and ground truth labels to an AccuracyMeter and retrieve top-k accuracy results', 'create a MultiProcessLauncher to spawn multiple Crypten MPC processes with a given world size', 'start all spawned subprocesses in the MultiProcessLauncher for parallel Crypten computation', 'join all subprocesses in the MultiProcessLauncher and assert zero exit codes', 'terminate all running subprocesses in the MultiProcessLauncher gracefully', 'run a user-defined function in a spawned subprocess with Crypten initialization and environment setup', 'run k-means clustering on a PyTorch tensor to find K cluster centers', 'run PCA on a PyTorch tensor to extract the top principal components', 'run one-hot encoding on a PyTorch long integer index vector', 'run k-means inference to compute cluster assignments for data points', 'run MNIST file processing to extract and save train and test data as .pt files']
```

Usage

```
{'run_kmeans_clustering': 'run k-means clustering on a PyTorch tensor to find K cluster centers', 'run_pca_components': 'run PCA on a PyTorch tensor to extract the top principal components', 'run_onehot_encoding': 'run one-hot encoding on a PyTorch long integer index vector', 'run_kmeans_inference': 'run k-means inference to compute cluster assignments for data points', 'run_process_mnist': 'run MNIST file processing to extract and save train and test data as .pt files'}
```


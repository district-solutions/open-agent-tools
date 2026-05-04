# Agent Python Tools

- repo: facebookresearch/graph2nn
- repo_uri: https://github.com/facebookresearch/graph2nn

## File: facebookresearch_graph2nn/pycls/datasets/load_graph.py

Prompts

```
['generate a Watts-Strogatz small-world graph with n nodes, given sparsity and rewiring probability', 'load an adjacency matrix from a text file into a NetworkX directed or undirected graph', 'compute the clustering coefficient and average shortest path length of a NetworkX graph', 'visualize a NetworkX graph using spring or circular layout and save as a PNG image', 'generate a guaranteed-connected Watts-Strogatz small-world graph by retrying until connectivity is achieved', 'construct a PyTorch training data loader for cifar10 or imagenet datasets with shuffling and drop_last enabled', 'construct a PyTorch test data loader for cifar10 or imagenet datasets without shuffling or dropping the last batch', 'construct a PyTorch DataLoader for a named dataset with configurable batch size, shuffle, sampler, and drop_last options', 'shuffle a PyTorch data loader by setting the epoch on its DistributedSampler for epoch-based randomization', 'review the dataset catalog mapping cifar10 and imagenet dataset names to their respective PyTorch dataset classes', 'check if a dataset name like cifar10 has a registered data path', 'get the file system data path for a dataset like imagenet', 'set a custom data path for a dataset name in the paths registry', 'review the dataset paths module to understand default data directory and registered paths', 'summarize the has_data_path, get_data_path, and set_data_path functions and their usage', 'create a function that randomly crops an image to a specified size with optional zero padding', 'create a function that horizontally flips an image with a given probability for data augmentation', 'create a function that normalizes image channels using provided mean and standard deviation values', 'create a function that performs random sized cropping and resizes the result to a target size', 'create a function that applies PCA-based lighting augmentation to an image using eigenvalues and eigenvectors']
```

Usage

```
{'generate_ws_graph': 'generate a Watts-Strogatz small-world graph with n nodes, given sparsity and rewiring probability', 'load_graph_from_txt': 'load an adjacency matrix from a text file into a NetworkX directed or undirected graph', 'compute_graph_stats': 'compute the clustering coefficient and average shortest path length of a NetworkX graph', 'plot_networkx_graph': 'visualize a NetworkX graph using spring or circular layout and save as a PNG image', 'generate_connected_ws_graph': 'generate a guaranteed-connected Watts-Strogatz small-world graph by retrying until connectivity is achieved'}
```

## File: facebookresearch_graph2nn/pycls/datasets/loader.py

Prompts

```
['generate a Watts-Strogatz small-world graph with n nodes, given sparsity and rewiring probability', 'load an adjacency matrix from a text file into a NetworkX directed or undirected graph', 'compute the clustering coefficient and average shortest path length of a NetworkX graph', 'visualize a NetworkX graph using spring or circular layout and save as a PNG image', 'generate a guaranteed-connected Watts-Strogatz small-world graph by retrying until connectivity is achieved', 'construct a PyTorch training data loader for cifar10 or imagenet datasets with shuffling and drop_last enabled', 'construct a PyTorch test data loader for cifar10 or imagenet datasets without shuffling or dropping the last batch', 'construct a PyTorch DataLoader for a named dataset with configurable batch size, shuffle, sampler, and drop_last options', 'shuffle a PyTorch data loader by setting the epoch on its DistributedSampler for epoch-based randomization', 'review the dataset catalog mapping cifar10 and imagenet dataset names to their respective PyTorch dataset classes', 'check if a dataset name like cifar10 has a registered data path', 'get the file system data path for a dataset like imagenet', 'set a custom data path for a dataset name in the paths registry', 'review the dataset paths module to understand default data directory and registered paths', 'summarize the has_data_path, get_data_path, and set_data_path functions and their usage', 'create a function that randomly crops an image to a specified size with optional zero padding', 'create a function that horizontally flips an image with a given probability for data augmentation', 'create a function that normalizes image channels using provided mean and standard deviation values', 'create a function that performs random sized cropping and resizes the result to a target size', 'create a function that applies PCA-based lighting augmentation to an image using eigenvalues and eigenvectors']
```

Usage

```
{'construct_train_loader': 'construct a PyTorch training data loader for cifar10 or imagenet datasets with shuffling and drop_last enabled', 'construct_test_loader': 'construct a PyTorch test data loader for cifar10 or imagenet datasets without shuffling or dropping the last batch', 'construct_loader_internal': 'construct a PyTorch DataLoader for a named dataset with configurable batch size, shuffle, sampler, and drop_last options', 'shuffle_loader': 'shuffle a PyTorch data loader by setting the epoch on its DistributedSampler for epoch-based randomization', 'dataset_catalog': 'review the dataset catalog mapping cifar10 and imagenet dataset names to their respective PyTorch dataset classes'}
```

## File: facebookresearch_graph2nn/pycls/datasets/paths.py

Prompts

```
['generate a Watts-Strogatz small-world graph with n nodes, given sparsity and rewiring probability', 'load an adjacency matrix from a text file into a NetworkX directed or undirected graph', 'compute the clustering coefficient and average shortest path length of a NetworkX graph', 'visualize a NetworkX graph using spring or circular layout and save as a PNG image', 'generate a guaranteed-connected Watts-Strogatz small-world graph by retrying until connectivity is achieved', 'construct a PyTorch training data loader for cifar10 or imagenet datasets with shuffling and drop_last enabled', 'construct a PyTorch test data loader for cifar10 or imagenet datasets without shuffling or dropping the last batch', 'construct a PyTorch DataLoader for a named dataset with configurable batch size, shuffle, sampler, and drop_last options', 'shuffle a PyTorch data loader by setting the epoch on its DistributedSampler for epoch-based randomization', 'review the dataset catalog mapping cifar10 and imagenet dataset names to their respective PyTorch dataset classes', 'check if a dataset name like cifar10 has a registered data path', 'get the file system data path for a dataset like imagenet', 'set a custom data path for a dataset name in the paths registry', 'review the dataset paths module to understand default data directory and registered paths', 'summarize the has_data_path, get_data_path, and set_data_path functions and their usage', 'create a function that randomly crops an image to a specified size with optional zero padding', 'create a function that horizontally flips an image with a given probability for data augmentation', 'create a function that normalizes image channels using provided mean and standard deviation values', 'create a function that performs random sized cropping and resizes the result to a target size', 'create a function that applies PCA-based lighting augmentation to an image using eigenvalues and eigenvectors']
```

Usage

```
{'check_has_data_path': 'check if a dataset name like cifar10 has a registered data path', 'get_data_path_for_dataset': 'get the file system data path for a dataset like imagenet', 'set_data_path_for_dataset': 'set a custom data path for a dataset name in the paths registry', 'review_paths_module': 'review the dataset paths module to understand default data directory and registered paths', 'summarize_paths_functions': 'summarize the has_data_path, get_data_path, and set_data_path functions and their usage'}
```

## File: facebookresearch_graph2nn/pycls/datasets/transforms.py

Prompts

```
['generate a Watts-Strogatz small-world graph with n nodes, given sparsity and rewiring probability', 'load an adjacency matrix from a text file into a NetworkX directed or undirected graph', 'compute the clustering coefficient and average shortest path length of a NetworkX graph', 'visualize a NetworkX graph using spring or circular layout and save as a PNG image', 'generate a guaranteed-connected Watts-Strogatz small-world graph by retrying until connectivity is achieved', 'construct a PyTorch training data loader for cifar10 or imagenet datasets with shuffling and drop_last enabled', 'construct a PyTorch test data loader for cifar10 or imagenet datasets without shuffling or dropping the last batch', 'construct a PyTorch DataLoader for a named dataset with configurable batch size, shuffle, sampler, and drop_last options', 'shuffle a PyTorch data loader by setting the epoch on its DistributedSampler for epoch-based randomization', 'review the dataset catalog mapping cifar10 and imagenet dataset names to their respective PyTorch dataset classes', 'check if a dataset name like cifar10 has a registered data path', 'get the file system data path for a dataset like imagenet', 'set a custom data path for a dataset name in the paths registry', 'review the dataset paths module to understand default data directory and registered paths', 'summarize the has_data_path, get_data_path, and set_data_path functions and their usage', 'create a function that randomly crops an image to a specified size with optional zero padding', 'create a function that horizontally flips an image with a given probability for data augmentation', 'create a function that normalizes image channels using provided mean and standard deviation values', 'create a function that performs random sized cropping and resizes the result to a target size', 'create a function that applies PCA-based lighting augmentation to an image using eigenvalues and eigenvectors']
```

Usage

```
{'create_random_crop': 'create a function that randomly crops an image to a specified size with optional zero padding', 'create_horizontal_flip': 'create a function that horizontally flips an image with a given probability for data augmentation', 'create_color_normalization': 'create a function that normalizes image channels using provided mean and standard deviation values', 'create_random_sized_crop': 'create a function that performs random sized cropping and resizes the result to a target size', 'create_lighting_augmentation': 'create a function that applies PCA-based lighting augmentation to an image using eigenvalues and eigenvectors'}
```


# Agent Python Tools

- repo: facebookresearch/qmnist
- repo_uri: https://github.com/facebookresearch/qmnist

## File: facebookresearch_qmnist/making_qmnist/hungarian_match_test.py

Prompts

```
['read an IDX3 unsigned byte image file (plain, gz, or xz) into a PyTorch tensor', 'read an IDX2 integer label file (plain, gz, or xz) into a PyTorch tensor', 'compute pairwise squared Euclidean distances between two sets of flattened image vectors', 'compute squared distances between image sets with spatial jitter tolerance for alignment', 'match MNIST test images to QMNIST test images using the Hungarian algorithm', 'run the Hungarian algorithm to match MNIST training images to QMNIST training images by digit', 'read an IDX3 unsigned byte image file (plain, gzipped, or xz compressed) into a PyTorch tensor', 'read an IDX2 integer label file (plain, gzipped, or xz compressed) into a PyTorch tensor', 'compute pairwise squared Euclidean distances between two image sets with spatial jitter tolerance', 'save a 2D PyTorch tensor to a text file in .MAT format with dimensions and values']
```

Usage

```
{'read_idx3_ubyte': 'read an IDX3 unsigned byte image file (plain, gz, or xz) into a PyTorch tensor', 'read_idx2_int': 'read an IDX2 integer label file (plain, gz, or xz) into a PyTorch tensor', 'squared_distances': 'compute pairwise squared Euclidean distances between two sets of flattened image vectors', 'squared_jittered_distances': 'compute squared distances between image sets with spatial jitter tolerance for alignment', 'match_mnist_train_set': 'match MNIST test images to QMNIST test images using the Hungarian algorithm'}
```

## File: facebookresearch_qmnist/making_qmnist/hungarian_match_train.py

Prompts

```
['read an IDX3 unsigned byte image file (plain, gz, or xz) into a PyTorch tensor', 'read an IDX2 integer label file (plain, gz, or xz) into a PyTorch tensor', 'compute pairwise squared Euclidean distances between two sets of flattened image vectors', 'compute squared distances between image sets with spatial jitter tolerance for alignment', 'match MNIST test images to QMNIST test images using the Hungarian algorithm', 'run the Hungarian algorithm to match MNIST training images to QMNIST training images by digit', 'read an IDX3 unsigned byte image file (plain, gzipped, or xz compressed) into a PyTorch tensor', 'read an IDX2 integer label file (plain, gzipped, or xz compressed) into a PyTorch tensor', 'compute pairwise squared Euclidean distances between two image sets with spatial jitter tolerance', 'save a 2D PyTorch tensor to a text file in .MAT format with dimensions and values']
```

Usage

```
{'run_match_mnist_train_set': 'run the Hungarian algorithm to match MNIST training images to QMNIST training images by digit', 'run_read_idx3_ubyte': 'read an IDX3 unsigned byte image file (plain, gzipped, or xz compressed) into a PyTorch tensor', 'run_read_idx2_int': 'read an IDX2 integer label file (plain, gzipped, or xz compressed) into a PyTorch tensor', 'run_squared_jittered_distances': 'compute pairwise squared Euclidean distances between two image sets with spatial jitter tolerance', 'run_save_2dtensor': 'save a 2D PyTorch tensor to a text file in .MAT format with dimensions and values'}
```


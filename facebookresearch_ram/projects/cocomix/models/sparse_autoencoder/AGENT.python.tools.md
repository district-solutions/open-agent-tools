# Agent Python Tools

- repo: facebookresearch/ram
- repo_uri: https://github.com/facebookresearch/ram

## File: facebookresearch_ram/projects/cocomix/models/sparse_autoencoder/kernels.py

Prompts

```
['run triton_sparse_transpose_dense_matmul to compute sparse.T @ dense with COO-format indices', 'run triton_sparse_dense_matmul to compute sparse @ dense reducing along the uncollated dimension', 'run triton_dense_dense_sparseout_matmul to compute dense1 @ dense2 only at specified indices', 'run TritonDecoderAutograd forward and backward for sparse autoencoder decoder weight gradients', 'run triton_add_mul_ to perform in-place x += a * b * c on 2D tensors', 'compute the combined reconstruction and L1 sparsity loss for a sparse autoencoder model', 'compute the normalized mean squared error between reconstructed and original input tensors', 'compute the normalized L1 loss of latent activations relative to input magnitude', 'review the autoencoder_loss function to understand how reconstruction error and L1 sparsity are combined', 'refactor the normalized_mean_squared_error function to support per-sample loss output instead of batch mean', 'build a sparse autoencoder model with configurable latent dimensions and activation functions', 'encode input data into sparse latent representations using the autoencoder encode method', 'decode latent representations back to reconstructed input data using the autoencoder decode method', 'create a TopK activation module that keeps only the top K values and zeros out the rest', 'load a pretrained sparse autoencoder model from a PyTorch state dictionary', 'get the Azure path for a v1 sparse autoencoder checkpoint by location and layer index', 'get the Azure path for a v4 sparse autoencoder checkpoint by location and layer index', 'get the Azure path for a v5 32k latent sparse autoencoder checkpoint by location and layer', 'get the Azure path for a v5 128k latent sparse autoencoder checkpoint by location and layer', 'summarize the sparse autoencoder paths module that provides Azure blob paths for GPT-2-small model checkpoints']
```

Usage

```
{'run_sparse_transpose_dense_matmul': 'run triton_sparse_transpose_dense_matmul to compute sparse.T @ dense with COO-format indices', 'run_sparse_dense_matmul': 'run triton_sparse_dense_matmul to compute sparse @ dense reducing along the uncollated dimension', 'run_dense_dense_sparseout_matmul': 'run triton_dense_dense_sparseout_matmul to compute dense1 @ dense2 only at specified indices', 'run_decoder_autograd': 'run TritonDecoderAutograd forward and backward for sparse autoencoder decoder weight gradients', 'run_add_mul_inplace': 'run triton_add_mul_ to perform in-place x += a * b * c on 2D tensors'}
```

## File: facebookresearch_ram/projects/cocomix/models/sparse_autoencoder/loss.py

Prompts

```
['run triton_sparse_transpose_dense_matmul to compute sparse.T @ dense with COO-format indices', 'run triton_sparse_dense_matmul to compute sparse @ dense reducing along the uncollated dimension', 'run triton_dense_dense_sparseout_matmul to compute dense1 @ dense2 only at specified indices', 'run TritonDecoderAutograd forward and backward for sparse autoencoder decoder weight gradients', 'run triton_add_mul_ to perform in-place x += a * b * c on 2D tensors', 'compute the combined reconstruction and L1 sparsity loss for a sparse autoencoder model', 'compute the normalized mean squared error between reconstructed and original input tensors', 'compute the normalized L1 loss of latent activations relative to input magnitude', 'review the autoencoder_loss function to understand how reconstruction error and L1 sparsity are combined', 'refactor the normalized_mean_squared_error function to support per-sample loss output instead of batch mean', 'build a sparse autoencoder model with configurable latent dimensions and activation functions', 'encode input data into sparse latent representations using the autoencoder encode method', 'decode latent representations back to reconstructed input data using the autoencoder decode method', 'create a TopK activation module that keeps only the top K values and zeros out the rest', 'load a pretrained sparse autoencoder model from a PyTorch state dictionary', 'get the Azure path for a v1 sparse autoencoder checkpoint by location and layer index', 'get the Azure path for a v4 sparse autoencoder checkpoint by location and layer index', 'get the Azure path for a v5 32k latent sparse autoencoder checkpoint by location and layer', 'get the Azure path for a v5 128k latent sparse autoencoder checkpoint by location and layer', 'summarize the sparse autoencoder paths module that provides Azure blob paths for GPT-2-small model checkpoints']
```

Usage

```
{'compute_autoencoder_loss': 'compute the combined reconstruction and L1 sparsity loss for a sparse autoencoder model', 'compute_normalized_mse': 'compute the normalized mean squared error between reconstructed and original input tensors', 'compute_normalized_l1_loss': 'compute the normalized L1 loss of latent activations relative to input magnitude', 'review_autoencoder_loss': 'review the autoencoder_loss function to understand how reconstruction error and L1 sparsity are combined', 'refactor_normalized_mse': 'refactor the normalized_mean_squared_error function to support per-sample loss output instead of batch mean'}
```

## File: facebookresearch_ram/projects/cocomix/models/sparse_autoencoder/model.py

Prompts

```
['run triton_sparse_transpose_dense_matmul to compute sparse.T @ dense with COO-format indices', 'run triton_sparse_dense_matmul to compute sparse @ dense reducing along the uncollated dimension', 'run triton_dense_dense_sparseout_matmul to compute dense1 @ dense2 only at specified indices', 'run TritonDecoderAutograd forward and backward for sparse autoencoder decoder weight gradients', 'run triton_add_mul_ to perform in-place x += a * b * c on 2D tensors', 'compute the combined reconstruction and L1 sparsity loss for a sparse autoencoder model', 'compute the normalized mean squared error between reconstructed and original input tensors', 'compute the normalized L1 loss of latent activations relative to input magnitude', 'review the autoencoder_loss function to understand how reconstruction error and L1 sparsity are combined', 'refactor the normalized_mean_squared_error function to support per-sample loss output instead of batch mean', 'build a sparse autoencoder model with configurable latent dimensions and activation functions', 'encode input data into sparse latent representations using the autoencoder encode method', 'decode latent representations back to reconstructed input data using the autoencoder decode method', 'create a TopK activation module that keeps only the top K values and zeros out the rest', 'load a pretrained sparse autoencoder model from a PyTorch state dictionary', 'get the Azure path for a v1 sparse autoencoder checkpoint by location and layer index', 'get the Azure path for a v4 sparse autoencoder checkpoint by location and layer index', 'get the Azure path for a v5 32k latent sparse autoencoder checkpoint by location and layer', 'get the Azure path for a v5 128k latent sparse autoencoder checkpoint by location and layer', 'summarize the sparse autoencoder paths module that provides Azure blob paths for GPT-2-small model checkpoints']
```

Usage

```
{'build_sparse_autoencoder': 'build a sparse autoencoder model with configurable latent dimensions and activation functions', 'encode_input_to_latents': 'encode input data into sparse latent representations using the autoencoder encode method', 'decode_latents_to_reconstruction': 'decode latent representations back to reconstructed input data using the autoencoder decode method', 'create_topk_activation': 'create a TopK activation module that keeps only the top K values and zeros out the rest', 'load_autoencoder_from_state_dict': 'load a pretrained sparse autoencoder model from a PyTorch state dictionary'}
```

## File: facebookresearch_ram/projects/cocomix/models/sparse_autoencoder/paths.py

Prompts

```
['run triton_sparse_transpose_dense_matmul to compute sparse.T @ dense with COO-format indices', 'run triton_sparse_dense_matmul to compute sparse @ dense reducing along the uncollated dimension', 'run triton_dense_dense_sparseout_matmul to compute dense1 @ dense2 only at specified indices', 'run TritonDecoderAutograd forward and backward for sparse autoencoder decoder weight gradients', 'run triton_add_mul_ to perform in-place x += a * b * c on 2D tensors', 'compute the combined reconstruction and L1 sparsity loss for a sparse autoencoder model', 'compute the normalized mean squared error between reconstructed and original input tensors', 'compute the normalized L1 loss of latent activations relative to input magnitude', 'review the autoencoder_loss function to understand how reconstruction error and L1 sparsity are combined', 'refactor the normalized_mean_squared_error function to support per-sample loss output instead of batch mean', 'build a sparse autoencoder model with configurable latent dimensions and activation functions', 'encode input data into sparse latent representations using the autoencoder encode method', 'decode latent representations back to reconstructed input data using the autoencoder decode method', 'create a TopK activation module that keeps only the top K values and zeros out the rest', 'load a pretrained sparse autoencoder model from a PyTorch state dictionary', 'get the Azure path for a v1 sparse autoencoder checkpoint by location and layer index', 'get the Azure path for a v4 sparse autoencoder checkpoint by location and layer index', 'get the Azure path for a v5 32k latent sparse autoencoder checkpoint by location and layer', 'get the Azure path for a v5 128k latent sparse autoencoder checkpoint by location and layer', 'summarize the sparse autoencoder paths module that provides Azure blob paths for GPT-2-small model checkpoints']
```

Usage

```
{'get_v1_autoencoder_path': 'get the Azure path for a v1 sparse autoencoder checkpoint by location and layer index', 'get_v4_autoencoder_path': 'get the Azure path for a v4 sparse autoencoder checkpoint by location and layer index', 'get_v5_32k_autoencoder_path': 'get the Azure path for a v5 32k latent sparse autoencoder checkpoint by location and layer', 'get_v5_128k_autoencoder_path': 'get the Azure path for a v5 128k latent sparse autoencoder checkpoint by location and layer', 'summarize_paths_module': 'summarize the sparse autoencoder paths module that provides Azure blob paths for GPT-2-small model checkpoints'}
```


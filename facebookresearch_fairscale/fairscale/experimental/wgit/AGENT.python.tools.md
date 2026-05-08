# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/experimental/wgit/pygit.py

Prompts

```
['create a PyGit instance to initialize or wrap a git repository within a wgit directory', 'use PyGit add method to stage all untracked files not in gitignore to the index', 'use PyGit commit method to commit staged changes with a message to the wgit git repo', 'use PyGit status method to get a dictionary of file paths and their pygit2 status codes', 'use PyGit _set_author_config to read git user name and email from gitconfig or fallback defaults', 'create a new WeiGit repo in a directory to track neural network weight versions', 'add a PyTorch checkpoint file to the WeiGit repo with per-tensor deduplication and gzip compression', 'commit staged WeiGit changes to the repo with a descriptive commit message', 'check the status of tracked files in the WeiGit repo to see which are clean, added, or modified', 'recursively traverse a nested dict or list and apply a callback function to each leaf element', 'create a new SHA1_Store at a given path with optional compression and deduplication settings', 'add a PyTorch tensor or state dict to the SHA1_Store with optional gzip compression', 'retrieve a tensor or dict from the SHA1_Store by its SHA1 hash string', 'delete a SHA1 entry from the store by decrementing its reference count', 'query original, deduped, and compressed size stats for a SHA1 entry or the entire store', 'create a SignalSparsity config with FFT algo and top-k percent for SST and DST sparsification', 'compress a PyTorch tensor using SignalSparsity lossy_compress to get SST and DST sparse tensors', 'transform a dense tensor to a signal sparse tensor using dense_to_sst with FFT and top-k', 'reconstruct a dense tensor from SST and DST sparse tensors using sst_dst_to_dense', 'generate a random sparse mask tensor with a given percent of non-zeros along a dimension', 'create an EnergyConcentrationProfile instance to measure energy concentration on a specific tensor dimension', 'measure the energy concentration of a PyTorch tensor across specified top-K percent thresholds', 'measure the energy concentration of a tensor in the FFT frequency domain', 'review the EnergyConcentrationProfile class and its measure and measure_fft methods', 'summarize the signal sparsity profiling module for tensor energy concentration analysis']
```

Usage

```
{'init_pygit_repo': 'create a PyGit instance to initialize or wrap a git repository within a wgit directory', 'pygit_add_all': 'use PyGit add method to stage all untracked files not in gitignore to the index', 'pygit_commit': 'use PyGit commit method to commit staged changes with a message to the wgit git repo', 'pygit_status': 'use PyGit status method to get a dictionary of file paths and their pygit2 status codes', 'pygit_set_author_config': 'use PyGit _set_author_config to read git user name and email from gitconfig or fallback defaults'}
```

## File: facebookresearch_fairscale/fairscale/experimental/wgit/repo.py

Prompts

```
['create a PyGit instance to initialize or wrap a git repository within a wgit directory', 'use PyGit add method to stage all untracked files not in gitignore to the index', 'use PyGit commit method to commit staged changes with a message to the wgit git repo', 'use PyGit status method to get a dictionary of file paths and their pygit2 status codes', 'use PyGit _set_author_config to read git user name and email from gitconfig or fallback defaults', 'create a new WeiGit repo in a directory to track neural network weight versions', 'add a PyTorch checkpoint file to the WeiGit repo with per-tensor deduplication and gzip compression', 'commit staged WeiGit changes to the repo with a descriptive commit message', 'check the status of tracked files in the WeiGit repo to see which are clean, added, or modified', 'recursively traverse a nested dict or list and apply a callback function to each leaf element', 'create a new SHA1_Store at a given path with optional compression and deduplication settings', 'add a PyTorch tensor or state dict to the SHA1_Store with optional gzip compression', 'retrieve a tensor or dict from the SHA1_Store by its SHA1 hash string', 'delete a SHA1 entry from the store by decrementing its reference count', 'query original, deduped, and compressed size stats for a SHA1 entry or the entire store', 'create a SignalSparsity config with FFT algo and top-k percent for SST and DST sparsification', 'compress a PyTorch tensor using SignalSparsity lossy_compress to get SST and DST sparse tensors', 'transform a dense tensor to a signal sparse tensor using dense_to_sst with FFT and top-k', 'reconstruct a dense tensor from SST and DST sparse tensors using sst_dst_to_dense', 'generate a random sparse mask tensor with a given percent of non-zeros along a dimension', 'create an EnergyConcentrationProfile instance to measure energy concentration on a specific tensor dimension', 'measure the energy concentration of a PyTorch tensor across specified top-K percent thresholds', 'measure the energy concentration of a tensor in the FFT frequency domain', 'review the EnergyConcentrationProfile class and its measure and measure_fft methods', 'summarize the signal sparsity profiling module for tensor energy concentration analysis']
```

Usage

```
{'init_weigit_repo': 'create a new WeiGit repo in a directory to track neural network weight versions', 'add_tensor_checkpoint': 'add a PyTorch checkpoint file to the WeiGit repo with per-tensor deduplication and gzip compression', 'commit_weigit_changes': 'commit staged WeiGit changes to the repo with a descriptive commit message', 'check_repo_status': 'check the status of tracked files in the WeiGit repo to see which are clean, added, or modified', 'recursive_apply_to_elements': 'recursively traverse a nested dict or list and apply a callback function to each leaf element'}
```

## File: facebookresearch_fairscale/fairscale/experimental/wgit/sha1_store.py

Prompts

```
['create a PyGit instance to initialize or wrap a git repository within a wgit directory', 'use PyGit add method to stage all untracked files not in gitignore to the index', 'use PyGit commit method to commit staged changes with a message to the wgit git repo', 'use PyGit status method to get a dictionary of file paths and their pygit2 status codes', 'use PyGit _set_author_config to read git user name and email from gitconfig or fallback defaults', 'create a new WeiGit repo in a directory to track neural network weight versions', 'add a PyTorch checkpoint file to the WeiGit repo with per-tensor deduplication and gzip compression', 'commit staged WeiGit changes to the repo with a descriptive commit message', 'check the status of tracked files in the WeiGit repo to see which are clean, added, or modified', 'recursively traverse a nested dict or list and apply a callback function to each leaf element', 'create a new SHA1_Store at a given path with optional compression and deduplication settings', 'add a PyTorch tensor or state dict to the SHA1_Store with optional gzip compression', 'retrieve a tensor or dict from the SHA1_Store by its SHA1 hash string', 'delete a SHA1 entry from the store by decrementing its reference count', 'query original, deduped, and compressed size stats for a SHA1 entry or the entire store', 'create a SignalSparsity config with FFT algo and top-k percent for SST and DST sparsification', 'compress a PyTorch tensor using SignalSparsity lossy_compress to get SST and DST sparse tensors', 'transform a dense tensor to a signal sparse tensor using dense_to_sst with FFT and top-k', 'reconstruct a dense tensor from SST and DST sparse tensors using sst_dst_to_dense', 'generate a random sparse mask tensor with a given percent of non-zeros along a dimension', 'create an EnergyConcentrationProfile instance to measure energy concentration on a specific tensor dimension', 'measure the energy concentration of a PyTorch tensor across specified top-K percent thresholds', 'measure the energy concentration of a tensor in the FFT frequency domain', 'review the EnergyConcentrationProfile class and its measure and measure_fft methods', 'summarize the signal sparsity profiling module for tensor energy concentration analysis']
```

Usage

```
{'create_sha1_store': 'create a new SHA1_Store at a given path with optional compression and deduplication settings', 'add_tensor_to_store': 'add a PyTorch tensor or state dict to the SHA1_Store with optional gzip compression', 'get_tensor_from_store': 'retrieve a tensor or dict from the SHA1_Store by its SHA1 hash string', 'delete_sha1_entry': 'delete a SHA1 entry from the store by decrementing its reference count', 'query_store_size_info': 'query original, deduped, and compressed size stats for a SHA1 entry or the entire store'}
```

## File: facebookresearch_fairscale/fairscale/experimental/wgit/signal_sparsity.py

Prompts

```
['create a PyGit instance to initialize or wrap a git repository within a wgit directory', 'use PyGit add method to stage all untracked files not in gitignore to the index', 'use PyGit commit method to commit staged changes with a message to the wgit git repo', 'use PyGit status method to get a dictionary of file paths and their pygit2 status codes', 'use PyGit _set_author_config to read git user name and email from gitconfig or fallback defaults', 'create a new WeiGit repo in a directory to track neural network weight versions', 'add a PyTorch checkpoint file to the WeiGit repo with per-tensor deduplication and gzip compression', 'commit staged WeiGit changes to the repo with a descriptive commit message', 'check the status of tracked files in the WeiGit repo to see which are clean, added, or modified', 'recursively traverse a nested dict or list and apply a callback function to each leaf element', 'create a new SHA1_Store at a given path with optional compression and deduplication settings', 'add a PyTorch tensor or state dict to the SHA1_Store with optional gzip compression', 'retrieve a tensor or dict from the SHA1_Store by its SHA1 hash string', 'delete a SHA1 entry from the store by decrementing its reference count', 'query original, deduped, and compressed size stats for a SHA1 entry or the entire store', 'create a SignalSparsity config with FFT algo and top-k percent for SST and DST sparsification', 'compress a PyTorch tensor using SignalSparsity lossy_compress to get SST and DST sparse tensors', 'transform a dense tensor to a signal sparse tensor using dense_to_sst with FFT and top-k', 'reconstruct a dense tensor from SST and DST sparse tensors using sst_dst_to_dense', 'generate a random sparse mask tensor with a given percent of non-zeros along a dimension', 'create an EnergyConcentrationProfile instance to measure energy concentration on a specific tensor dimension', 'measure the energy concentration of a PyTorch tensor across specified top-K percent thresholds', 'measure the energy concentration of a tensor in the FFT frequency domain', 'review the EnergyConcentrationProfile class and its measure and measure_fft methods', 'summarize the signal sparsity profiling module for tensor energy concentration analysis']
```

Usage

```
{'create_signal_sparsity_config': 'create a SignalSparsity config with FFT algo and top-k percent for SST and DST sparsification', 'compress_tensor_with_lossy_compress': 'compress a PyTorch tensor using SignalSparsity lossy_compress to get SST and DST sparse tensors', 'transform_dense_to_sst': 'transform a dense tensor to a signal sparse tensor using dense_to_sst with FFT and top-k', 'reconstruct_dense_from_sst_dst': 'reconstruct a dense tensor from SST and DST sparse tensors using sst_dst_to_dense', 'generate_random_sparse_mask': 'generate a random sparse mask tensor with a given percent of non-zeros along a dimension'}
```

## File: facebookresearch_fairscale/fairscale/experimental/wgit/signal_sparsity_profiling.py

Prompts

```
['create a PyGit instance to initialize or wrap a git repository within a wgit directory', 'use PyGit add method to stage all untracked files not in gitignore to the index', 'use PyGit commit method to commit staged changes with a message to the wgit git repo', 'use PyGit status method to get a dictionary of file paths and their pygit2 status codes', 'use PyGit _set_author_config to read git user name and email from gitconfig or fallback defaults', 'create a new WeiGit repo in a directory to track neural network weight versions', 'add a PyTorch checkpoint file to the WeiGit repo with per-tensor deduplication and gzip compression', 'commit staged WeiGit changes to the repo with a descriptive commit message', 'check the status of tracked files in the WeiGit repo to see which are clean, added, or modified', 'recursively traverse a nested dict or list and apply a callback function to each leaf element', 'create a new SHA1_Store at a given path with optional compression and deduplication settings', 'add a PyTorch tensor or state dict to the SHA1_Store with optional gzip compression', 'retrieve a tensor or dict from the SHA1_Store by its SHA1 hash string', 'delete a SHA1 entry from the store by decrementing its reference count', 'query original, deduped, and compressed size stats for a SHA1 entry or the entire store', 'create a SignalSparsity config with FFT algo and top-k percent for SST and DST sparsification', 'compress a PyTorch tensor using SignalSparsity lossy_compress to get SST and DST sparse tensors', 'transform a dense tensor to a signal sparse tensor using dense_to_sst with FFT and top-k', 'reconstruct a dense tensor from SST and DST sparse tensors using sst_dst_to_dense', 'generate a random sparse mask tensor with a given percent of non-zeros along a dimension', 'create an EnergyConcentrationProfile instance to measure energy concentration on a specific tensor dimension', 'measure the energy concentration of a PyTorch tensor across specified top-K percent thresholds', 'measure the energy concentration of a tensor in the FFT frequency domain', 'review the EnergyConcentrationProfile class and its measure and measure_fft methods', 'summarize the signal sparsity profiling module for tensor energy concentration analysis']
```

Usage

```
{'create_energy_concentration_profile': 'create an EnergyConcentrationProfile instance to measure energy concentration on a specific tensor dimension', 'measure_energy_concentration': 'measure the energy concentration of a PyTorch tensor across specified top-K percent thresholds', 'measure_fft_energy_concentration': 'measure the energy concentration of a tensor in the FFT frequency domain', 'review_energy_concentration_profile_class': 'review the EnergyConcentrationProfile class and its measure and measure_fft methods', 'summarize_signal_sparsity_profiling': 'summarize the signal sparsity profiling module for tensor energy concentration analysis'}
```


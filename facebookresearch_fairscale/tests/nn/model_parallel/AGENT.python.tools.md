# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/tests/nn/model_parallel/test_cross_entropy.py

Prompts

```
['test the vocab_parallel_cross_entropy function against standard torch cross entropy for correctness across model parallel sizes', 'run the cross entropy test comparing torch and MPU loss and gradient values with a given model parallel size', 'compute standard torch cross entropy loss and gradients for a batch of logits and random targets', 'compute model parallel cross entropy loss using scatter_to_model_parallel_region and vocab_parallel_cross_entropy', 'review the vocab_parallel_cross_entropy implementation by comparing its loss and gradients to standard torch cross entropy', 'test the model parallel initialization by spawning processes across all world sizes and verifying group setup', 'test the get_model_parallel_src_rank function to verify source rank calculation in a distributed setting', 'test that model parallel groups are contiguous by mocking torch.distributed and checking group membership', 'run the model parallel initialization test with a given rank, size, and communication filenames', 'run the source rank test to validate model parallel source rank computation across distributed ranks', 'test ParallelEmbedding and VocabParallelEmbedding layers for correctness across model parallel ranks', 'test the _initialize_affine_weight function for column and row parallel weight initialization', 'test ColumnParallelLinear layer forward and backward pass gradient correctness across ranks', 'test RowParallelLinear layer forward and backward pass gradient correctness across ranks', 'run the affine weight initialization test spawning all world sizes deterministically', 'test the CUDA RNG state save and restore functions across distributed model parallel ranks', 'test the CUDA RNG tracker fork and add seed functionality for interleaved random generation', 'test the model parallel CUDA manual seed function with forked RNG contexts', 'run the CUDA RNG state reset test verifying reproducibility after restoring saved RNG state', 'run the CUDA RNG tracker test verifying interleaved seed generation produces correct tensors']
```

Usage

```
{'test_cross_entropy': 'test the vocab_parallel_cross_entropy function against standard torch cross entropy for correctness across model parallel sizes', 'run_test_cross_entropy': 'run the cross entropy test comparing torch and MPU loss and gradient values with a given model parallel size', 'torch_cross_entropy': 'compute standard torch cross entropy loss and gradients for a batch of logits and random targets', 'mpu_cross_entropy': 'compute model parallel cross entropy loss using scatter_to_model_parallel_region and vocab_parallel_cross_entropy', 'review_vocab_parallel_cross_entropy': 'review the vocab_parallel_cross_entropy implementation by comparing its loss and gradients to standard torch cross entropy'}
```

## File: facebookresearch_fairscale/tests/nn/model_parallel/test_initialize.py

Prompts

```
['test the vocab_parallel_cross_entropy function against standard torch cross entropy for correctness across model parallel sizes', 'run the cross entropy test comparing torch and MPU loss and gradient values with a given model parallel size', 'compute standard torch cross entropy loss and gradients for a batch of logits and random targets', 'compute model parallel cross entropy loss using scatter_to_model_parallel_region and vocab_parallel_cross_entropy', 'review the vocab_parallel_cross_entropy implementation by comparing its loss and gradients to standard torch cross entropy', 'test the model parallel initialization by spawning processes across all world sizes and verifying group setup', 'test the get_model_parallel_src_rank function to verify source rank calculation in a distributed setting', 'test that model parallel groups are contiguous by mocking torch.distributed and checking group membership', 'run the model parallel initialization test with a given rank, size, and communication filenames', 'run the source rank test to validate model parallel source rank computation across distributed ranks', 'test ParallelEmbedding and VocabParallelEmbedding layers for correctness across model parallel ranks', 'test the _initialize_affine_weight function for column and row parallel weight initialization', 'test ColumnParallelLinear layer forward and backward pass gradient correctness across ranks', 'test RowParallelLinear layer forward and backward pass gradient correctness across ranks', 'run the affine weight initialization test spawning all world sizes deterministically', 'test the CUDA RNG state save and restore functions across distributed model parallel ranks', 'test the CUDA RNG tracker fork and add seed functionality for interleaved random generation', 'test the model parallel CUDA manual seed function with forked RNG contexts', 'run the CUDA RNG state reset test verifying reproducibility after restoring saved RNG state', 'run the CUDA RNG tracker test verifying interleaved seed generation produces correct tensors']
```

Usage

```
{'test_initialize_model_parallel': 'test the model parallel initialization by spawning processes across all world sizes and verifying group setup', 'test_get_model_parallel_src_rank': 'test the get_model_parallel_src_rank function to verify source rank calculation in a distributed setting', 'test_adjacency': 'test that model parallel groups are contiguous by mocking torch.distributed and checking group membership', 'run_initialize_model_parallel': 'run the model parallel initialization test with a given rank, size, and communication filenames', 'run_get_model_parallel_src_rank': 'run the source rank test to validate model parallel source rank computation across distributed ranks'}
```

## File: facebookresearch_fairscale/tests/nn/model_parallel/test_layers.py

Prompts

```
['test the vocab_parallel_cross_entropy function against standard torch cross entropy for correctness across model parallel sizes', 'run the cross entropy test comparing torch and MPU loss and gradient values with a given model parallel size', 'compute standard torch cross entropy loss and gradients for a batch of logits and random targets', 'compute model parallel cross entropy loss using scatter_to_model_parallel_region and vocab_parallel_cross_entropy', 'review the vocab_parallel_cross_entropy implementation by comparing its loss and gradients to standard torch cross entropy', 'test the model parallel initialization by spawning processes across all world sizes and verifying group setup', 'test the get_model_parallel_src_rank function to verify source rank calculation in a distributed setting', 'test that model parallel groups are contiguous by mocking torch.distributed and checking group membership', 'run the model parallel initialization test with a given rank, size, and communication filenames', 'run the source rank test to validate model parallel source rank computation across distributed ranks', 'test ParallelEmbedding and VocabParallelEmbedding layers for correctness across model parallel ranks', 'test the _initialize_affine_weight function for column and row parallel weight initialization', 'test ColumnParallelLinear layer forward and backward pass gradient correctness across ranks', 'test RowParallelLinear layer forward and backward pass gradient correctness across ranks', 'run the affine weight initialization test spawning all world sizes deterministically', 'test the CUDA RNG state save and restore functions across distributed model parallel ranks', 'test the CUDA RNG tracker fork and add seed functionality for interleaved random generation', 'test the model parallel CUDA manual seed function with forked RNG contexts', 'run the CUDA RNG state reset test verifying reproducibility after restoring saved RNG state', 'run the CUDA RNG tracker test verifying interleaved seed generation produces correct tensors']
```

Usage

```
{'test_parallel_embedding': 'test ParallelEmbedding and VocabParallelEmbedding layers for correctness across model parallel ranks', 'test_initialize_affine_weight': 'test the _initialize_affine_weight function for column and row parallel weight initialization', 'test_column_parallel_linear': 'test ColumnParallelLinear layer forward and backward pass gradient correctness across ranks', 'test_row_parallel_linear': 'test RowParallelLinear layer forward and backward pass gradient correctness across ranks', 'test_affine_weight': 'run the affine weight initialization test spawning all world sizes deterministically'}
```

## File: facebookresearch_fairscale/tests/nn/model_parallel/test_random.py

Prompts

```
['test the vocab_parallel_cross_entropy function against standard torch cross entropy for correctness across model parallel sizes', 'run the cross entropy test comparing torch and MPU loss and gradient values with a given model parallel size', 'compute standard torch cross entropy loss and gradients for a batch of logits and random targets', 'compute model parallel cross entropy loss using scatter_to_model_parallel_region and vocab_parallel_cross_entropy', 'review the vocab_parallel_cross_entropy implementation by comparing its loss and gradients to standard torch cross entropy', 'test the model parallel initialization by spawning processes across all world sizes and verifying group setup', 'test the get_model_parallel_src_rank function to verify source rank calculation in a distributed setting', 'test that model parallel groups are contiguous by mocking torch.distributed and checking group membership', 'run the model parallel initialization test with a given rank, size, and communication filenames', 'run the source rank test to validate model parallel source rank computation across distributed ranks', 'test ParallelEmbedding and VocabParallelEmbedding layers for correctness across model parallel ranks', 'test the _initialize_affine_weight function for column and row parallel weight initialization', 'test ColumnParallelLinear layer forward and backward pass gradient correctness across ranks', 'test RowParallelLinear layer forward and backward pass gradient correctness across ranks', 'run the affine weight initialization test spawning all world sizes deterministically', 'test the CUDA RNG state save and restore functions across distributed model parallel ranks', 'test the CUDA RNG tracker fork and add seed functionality for interleaved random generation', 'test the model parallel CUDA manual seed function with forked RNG contexts', 'run the CUDA RNG state reset test verifying reproducibility after restoring saved RNG state', 'run the CUDA RNG tracker test verifying interleaved seed generation produces correct tensors']
```

Usage

```
{'test_set_cuda_rng_state': 'test the CUDA RNG state save and restore functions across distributed model parallel ranks', 'test_cuda_rng_tracker': 'test the CUDA RNG tracker fork and add seed functionality for interleaved random generation', 'test_model_parallel_cuda_manual_seed': 'test the model parallel CUDA manual seed function with forked RNG contexts', 'run_test_set_cuda_rng_state': 'run the CUDA RNG state reset test verifying reproducibility after restoring saved RNG state', 'run_test_cuda_rng_tracker': 'run the CUDA RNG tracker test verifying interleaved seed generation produces correct tensors'}
```


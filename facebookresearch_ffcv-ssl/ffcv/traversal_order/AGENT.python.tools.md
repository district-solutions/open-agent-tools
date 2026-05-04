# Agent Python Tools

- repo: facebookresearch/ffcv-ssl
- repo_uri: https://github.com/facebookresearch/ffcv-ssl

## File: facebookresearch_ffcv-ssl/ffcv/traversal_order/base.py

Prompts

```
['implement a subclass of TraversalOrder that overrides sample_order to return a custom index sequence per epoch', 'review the TraversalOrder abstract base class and its sample_order method signature for correctness', 'refactor the TraversalOrder constructor to accept additional configuration parameters beyond loader', 'test that a TraversalOrder subclass returns a Sequence of ints from sample_order for a given epoch', 'summarize the TraversalOrder ABC interface including its loader dependency and abstract sample_order method', 'create a QuasiRandom traversal order for an FFCV loader to generate quasi-random sample ordering', 'generate a quasi-random sample order using a seeded buffer-based page sampling algorithm with numba JIT', 'prepare numpy arrays mapping pages to samples and their sizes for quasi-random traversal', 'sample a quasi-random order of indices for a given epoch using epoch-based seed derivation', 'review the QuasiRandom class and its buffer-based page sampling strategy for distributed training limitations', 'create a Random traversal order instance by passing an FFCV Loader to shuffle data indices randomly', 'call sample_order on a Random traversal order with an epoch number to get shuffled indices', 'use Random traversal order with DistributedSampler for multi-GPU training with seeded random shuffling per epoch', 'review the Random class that extends TraversalOrder to provide numpy-based random permutation of dataset indices', 'summarize the sample_order method that returns shuffled indices using numpy random generator or PyTorch DistributedSampler', 'create a Sequential traversal order that distributes data points round-robin across GPUs in distributed training', 'create a SequentialContiguous traversal order that assigns contiguous index blocks to each GPU in distributed training', 'use DistributedSamplerProxy to subsample contiguous index ranges per rank instead of strided sampling', 'review the Sequential class sample_order method to understand round-robin index distribution logic', 'refactor the SequentialContiguous class to use a custom sampler for contiguous per-GPU index assignment']
```

Usage

```
{'implement_traversal_order_subclass': 'implement a subclass of TraversalOrder that overrides sample_order to return a custom index sequence per epoch', 'review_traversal_order_abc': 'review the TraversalOrder abstract base class and its sample_order method signature for correctness', 'refactor_traversal_order_init': 'refactor the TraversalOrder constructor to accept additional configuration parameters beyond loader', 'test_traversal_order_sample_order': 'test that a TraversalOrder subclass returns a Sequence of ints from sample_order for a given epoch', 'summarize_traversal_order_api': 'summarize the TraversalOrder ABC interface including its loader dependency and abstract sample_order method'}
```

## File: facebookresearch_ffcv-ssl/ffcv/traversal_order/quasi_random.py

Prompts

```
['implement a subclass of TraversalOrder that overrides sample_order to return a custom index sequence per epoch', 'review the TraversalOrder abstract base class and its sample_order method signature for correctness', 'refactor the TraversalOrder constructor to accept additional configuration parameters beyond loader', 'test that a TraversalOrder subclass returns a Sequence of ints from sample_order for a given epoch', 'summarize the TraversalOrder ABC interface including its loader dependency and abstract sample_order method', 'create a QuasiRandom traversal order for an FFCV loader to generate quasi-random sample ordering', 'generate a quasi-random sample order using a seeded buffer-based page sampling algorithm with numba JIT', 'prepare numpy arrays mapping pages to samples and their sizes for quasi-random traversal', 'sample a quasi-random order of indices for a given epoch using epoch-based seed derivation', 'review the QuasiRandom class and its buffer-based page sampling strategy for distributed training limitations', 'create a Random traversal order instance by passing an FFCV Loader to shuffle data indices randomly', 'call sample_order on a Random traversal order with an epoch number to get shuffled indices', 'use Random traversal order with DistributedSampler for multi-GPU training with seeded random shuffling per epoch', 'review the Random class that extends TraversalOrder to provide numpy-based random permutation of dataset indices', 'summarize the sample_order method that returns shuffled indices using numpy random generator or PyTorch DistributedSampler', 'create a Sequential traversal order that distributes data points round-robin across GPUs in distributed training', 'create a SequentialContiguous traversal order that assigns contiguous index blocks to each GPU in distributed training', 'use DistributedSamplerProxy to subsample contiguous index ranges per rank instead of strided sampling', 'review the Sequential class sample_order method to understand round-robin index distribution logic', 'refactor the SequentialContiguous class to use a custom sampler for contiguous per-GPU index assignment']
```

Usage

```
{'create_quasirandom_traversal': 'create a QuasiRandom traversal order for an FFCV loader to generate quasi-random sample ordering', 'generate_order_inner': 'generate a quasi-random sample order using a seeded buffer-based page sampling algorithm with numba JIT', 'prepare_data_structures': 'prepare numpy arrays mapping pages to samples and their sizes for quasi-random traversal', 'sample_order_epoch': 'sample a quasi-random order of indices for a given epoch using epoch-based seed derivation', 'review_quasirandom_class': 'review the QuasiRandom class and its buffer-based page sampling strategy for distributed training limitations'}
```

## File: facebookresearch_ffcv-ssl/ffcv/traversal_order/random.py

Prompts

```
['implement a subclass of TraversalOrder that overrides sample_order to return a custom index sequence per epoch', 'review the TraversalOrder abstract base class and its sample_order method signature for correctness', 'refactor the TraversalOrder constructor to accept additional configuration parameters beyond loader', 'test that a TraversalOrder subclass returns a Sequence of ints from sample_order for a given epoch', 'summarize the TraversalOrder ABC interface including its loader dependency and abstract sample_order method', 'create a QuasiRandom traversal order for an FFCV loader to generate quasi-random sample ordering', 'generate a quasi-random sample order using a seeded buffer-based page sampling algorithm with numba JIT', 'prepare numpy arrays mapping pages to samples and their sizes for quasi-random traversal', 'sample a quasi-random order of indices for a given epoch using epoch-based seed derivation', 'review the QuasiRandom class and its buffer-based page sampling strategy for distributed training limitations', 'create a Random traversal order instance by passing an FFCV Loader to shuffle data indices randomly', 'call sample_order on a Random traversal order with an epoch number to get shuffled indices', 'use Random traversal order with DistributedSampler for multi-GPU training with seeded random shuffling per epoch', 'review the Random class that extends TraversalOrder to provide numpy-based random permutation of dataset indices', 'summarize the sample_order method that returns shuffled indices using numpy random generator or PyTorch DistributedSampler', 'create a Sequential traversal order that distributes data points round-robin across GPUs in distributed training', 'create a SequentialContiguous traversal order that assigns contiguous index blocks to each GPU in distributed training', 'use DistributedSamplerProxy to subsample contiguous index ranges per rank instead of strided sampling', 'review the Sequential class sample_order method to understand round-robin index distribution logic', 'refactor the SequentialContiguous class to use a custom sampler for contiguous per-GPU index assignment']
```

Usage

```
{'create_random_traversal_order': 'create a Random traversal order instance by passing an FFCV Loader to shuffle data indices randomly', 'sample_order_random_epoch': 'call sample_order on a Random traversal order with an epoch number to get shuffled indices', 'use_random_with_distributed_sampler': 'use Random traversal order with DistributedSampler for multi-GPU training with seeded random shuffling per epoch', 'review_random_class': 'review the Random class that extends TraversalOrder to provide numpy-based random permutation of dataset indices', 'summarize_random_sample_order': 'summarize the sample_order method that returns shuffled indices using numpy random generator or PyTorch DistributedSampler'}
```

## File: facebookresearch_ffcv-ssl/ffcv/traversal_order/sequential.py

Prompts

```
['implement a subclass of TraversalOrder that overrides sample_order to return a custom index sequence per epoch', 'review the TraversalOrder abstract base class and its sample_order method signature for correctness', 'refactor the TraversalOrder constructor to accept additional configuration parameters beyond loader', 'test that a TraversalOrder subclass returns a Sequence of ints from sample_order for a given epoch', 'summarize the TraversalOrder ABC interface including its loader dependency and abstract sample_order method', 'create a QuasiRandom traversal order for an FFCV loader to generate quasi-random sample ordering', 'generate a quasi-random sample order using a seeded buffer-based page sampling algorithm with numba JIT', 'prepare numpy arrays mapping pages to samples and their sizes for quasi-random traversal', 'sample a quasi-random order of indices for a given epoch using epoch-based seed derivation', 'review the QuasiRandom class and its buffer-based page sampling strategy for distributed training limitations', 'create a Random traversal order instance by passing an FFCV Loader to shuffle data indices randomly', 'call sample_order on a Random traversal order with an epoch number to get shuffled indices', 'use Random traversal order with DistributedSampler for multi-GPU training with seeded random shuffling per epoch', 'review the Random class that extends TraversalOrder to provide numpy-based random permutation of dataset indices', 'summarize the sample_order method that returns shuffled indices using numpy random generator or PyTorch DistributedSampler', 'create a Sequential traversal order that distributes data points round-robin across GPUs in distributed training', 'create a SequentialContiguous traversal order that assigns contiguous index blocks to each GPU in distributed training', 'use DistributedSamplerProxy to subsample contiguous index ranges per rank instead of strided sampling', 'review the Sequential class sample_order method to understand round-robin index distribution logic', 'refactor the SequentialContiguous class to use a custom sampler for contiguous per-GPU index assignment']
```

Usage

```
{'create_Sequential_traversal': 'create a Sequential traversal order that distributes data points round-robin across GPUs in distributed training', 'create_SequentialContiguous_traversal': 'create a SequentialContiguous traversal order that assigns contiguous index blocks to each GPU in distributed training', 'use_DistributedSamplerProxy': 'use DistributedSamplerProxy to subsample contiguous index ranges per rank instead of strided sampling', 'review_Sequential_sample_order': 'review the Sequential class sample_order method to understand round-robin index distribution logic', 'refactor_SequentialContiguous_sampler': 'refactor the SequentialContiguous class to use a custom sampler for contiguous per-GPU index assignment'}
```


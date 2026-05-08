# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/datasets/samplers/test_max_atoms_distributed_sampler.py

Prompts

```
['test the get_batches function to verify batch creation and sample filtering with atom count constraints', 'test the MaxAtomDistributedBatchSampler across multiple ranks to verify equal batch distribution and unique sample indices', 'test that MaxAtomDistributedBatchSampler produces identical batches when initialized with the same seed and parameters', 'test the set_epoch_and_start_iteration method to verify the sampler can skip batches and resume correctly', 'create a mock dataset with random atom counts using get_mock_dataset for testing the distributed batch sampler']
```

Usage

```
{'test_get_batches': 'test the get_batches function to verify batch creation and sample filtering with atom count constraints', 'test_sampler_multi_rank': 'test the MaxAtomDistributedBatchSampler across multiple ranks to verify equal batch distribution and unique sample indices', 'test_sampler_reproducible': 'test that MaxAtomDistributedBatchSampler produces identical batches when initialized with the same seed and parameters', 'test_fast_forward': 'test the set_epoch_and_start_iteration method to verify the sampler can skip batches and resume correctly', 'create_mock_dataset': 'create a mock dataset with random atom counts using get_mock_dataset for testing the distributed batch sampler'}
```


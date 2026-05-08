# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/service/runtime/benchmark_cache_test.py

Prompts

```
['test the make_benchmark_of_size helper function that generates Benchmark protobufs of exact byte sizes', 'test that inserting an oversized benchmark into a BenchmarkCache triggers the evict_to_capacity method', 'test that replacing an existing item in BenchmarkCache updates size_in_bytes while keeping item count at one', 'test that BenchmarkCache evicts items when total cache size exceeds the configured max_size_in_bytes limit', 'test that a warning is logged when a single benchmark exceeds the entire target cache size']
```

Usage

```
{'test_make_benchmark_of_size': 'test the make_benchmark_of_size helper function that generates Benchmark protobufs of exact byte sizes', 'test_oversized_benchmark_triggers_evict_to_capacity': 'test that inserting an oversized benchmark into a BenchmarkCache triggers the evict_to_capacity method', 'test_replace_existing_item': 'test that replacing an existing item in BenchmarkCache updates size_in_bytes while keeping item count at one', 'test_evict_to_capacity_on_max_size_reached': 'test that BenchmarkCache evicts items when total cache size exceeds the configured max_size_in_bytes limit', 'test_oversized_benchmark_emits_warning': 'test that a warning is logged when a single benchmark exceeds the entire target cache size'}
```


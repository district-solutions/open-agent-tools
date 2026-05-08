# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/gcc/datasets/anghabench_test.py

Prompts

```
['test the anghabench-v1 dataset size assertion for darwin and linux platforms using gcc-v0 gym environment', 'test that anghabench-v1 dataset raises LookupError when requesting an invalid benchmark URI with mocked install', 'test random benchmark selection from anghabench-v1 dataset URIs and reset the gcc-v0 environment with the selected benchmark', 'run the anghabench dataset test suite using pytest with the gcc support and common pytest plugins', 'review the anghabench-v1 dataset API methods including benchmark, benchmark_uris, install, and size properties', 'test the Csmith dataset size assertion that generator datasets return zero for size and length', 'test selecting a Csmith benchmark by index URI and writing its source files to a directory', 'test generating unique random Csmith benchmarks using a numpy random number generator with a fixed seed', 'test the Csmith benchmark from seed method raises OSError when retry count exceeds the maximum retries', 'test that a Csmith benchmark source can be written to a directory and produces a source.c file']
```

Usage

```
{'test_anghabench_dataset_size': 'test the anghabench-v1 dataset size assertion for darwin and linux platforms using gcc-v0 gym environment', 'test_missing_benchmark_lookup_error': 'test that anghabench-v1 dataset raises LookupError when requesting an invalid benchmark URI with mocked install', 'test_anghabench_random_benchmark_select': 'test random benchmark selection from anghabench-v1 dataset URIs and reset the gcc-v0 environment with the selected benchmark', 'run_anghabench_test_suite': 'run the anghabench dataset test suite using pytest with the gcc support and common pytest plugins', 'review_anghabench_dataset_api': 'review the anghabench-v1 dataset API methods including benchmark, benchmark_uris, install, and size properties'}
```

## File: facebookresearch_compilergym/tests/gcc/datasets/csmith_test.py

Prompts

```
['test the anghabench-v1 dataset size assertion for darwin and linux platforms using gcc-v0 gym environment', 'test that anghabench-v1 dataset raises LookupError when requesting an invalid benchmark URI with mocked install', 'test random benchmark selection from anghabench-v1 dataset URIs and reset the gcc-v0 environment with the selected benchmark', 'run the anghabench dataset test suite using pytest with the gcc support and common pytest plugins', 'review the anghabench-v1 dataset API methods including benchmark, benchmark_uris, install, and size properties', 'test the Csmith dataset size assertion that generator datasets return zero for size and length', 'test selecting a Csmith benchmark by index URI and writing its source files to a directory', 'test generating unique random Csmith benchmarks using a numpy random number generator with a fixed seed', 'test the Csmith benchmark from seed method raises OSError when retry count exceeds the maximum retries', 'test that a Csmith benchmark source can be written to a directory and produces a source.c file']
```

Usage

```
{'test_csmith_dataset_size': 'test the Csmith dataset size assertion that generator datasets return zero for size and length', 'test_csmith_benchmark_select_by_index': 'test selecting a Csmith benchmark by index URI and writing its source files to a directory', 'test_csmith_random_benchmark_selection': 'test generating unique random Csmith benchmarks using a numpy random number generator with a fixed seed', 'test_csmith_benchmark_from_seed_retry': 'test the Csmith benchmark from seed method raises OSError when retry count exceeds the maximum retries', 'test_csmith_benchmark_source_write': 'test that a Csmith benchmark source can be written to a directory and produces a source.c file'}
```


# Agent Python Tools

- repo: facebookresearch/gtn
- repo_uri: https://github.com/facebookresearch/gtn

## File: facebookresearch_gtn/bindings/python/benchmarks/parallel.py

Prompts

```
['run the time_compose function to benchmark parallel graph composition forward and backward passes', 'run the time_forward_score function to benchmark parallel forward scoring on GTN graphs', 'run the time_indexed_func function to benchmark parallel indexed Python function execution', 'run the parallel benchmark suite with a custom batch size B via command line argument', 'review how gtn.compose, gtn.forward_score, gtn.backward, and gtn.parallel_for are used in parallel benchmarks', 'run time_func to benchmark a callable and print its average execution time in milliseconds', 'test time_func by passing a custom number of iterations to control benchmark precision', 'test time_func by providing a custom name label for the benchmark output', 'review time_func to understand its 5-call warmup phase before measuring performance', 'summarize time_func which uses perf_counter to measure average ms per call across iterations']
```

Usage

```
{'run_parallel_compose_benchmark': 'run the time_compose function to benchmark parallel graph composition forward and backward passes', 'run_parallel_forward_score_benchmark': 'run the time_forward_score function to benchmark parallel forward scoring on GTN graphs', 'run_parallel_indexed_func_benchmark': 'run the time_indexed_func function to benchmark parallel indexed Python function execution', 'run_parallel_benchmarks_with_batch_size': 'run the parallel benchmark suite with a custom batch size B via command line argument', 'review_gtn_parallel_api_usage': 'review how gtn.compose, gtn.forward_score, gtn.backward, and gtn.parallel_for are used in parallel benchmarks'}
```

## File: facebookresearch_gtn/bindings/python/benchmarks/time_utils.py

Prompts

```
['run the time_compose function to benchmark parallel graph composition forward and backward passes', 'run the time_forward_score function to benchmark parallel forward scoring on GTN graphs', 'run the time_indexed_func function to benchmark parallel indexed Python function execution', 'run the parallel benchmark suite with a custom batch size B via command line argument', 'review how gtn.compose, gtn.forward_score, gtn.backward, and gtn.parallel_for are used in parallel benchmarks', 'run time_func to benchmark a callable and print its average execution time in milliseconds', 'test time_func by passing a custom number of iterations to control benchmark precision', 'test time_func by providing a custom name label for the benchmark output', 'review time_func to understand its 5-call warmup phase before measuring performance', 'summarize time_func which uses perf_counter to measure average ms per call across iterations']
```

Usage

```
{'run_time_func_benchmark': 'run time_func to benchmark a callable and print its average execution time in milliseconds', 'test_time_func_with_iterations': 'test time_func by passing a custom number of iterations to control benchmark precision', 'test_time_func_with_name': 'test time_func by providing a custom name label for the benchmark output', 'review_time_func_warmup': 'review time_func to understand its 5-call warmup phase before measuring performance', 'summarize_time_func': 'summarize time_func which uses perf_counter to measure average ms per call across iterations'}
```


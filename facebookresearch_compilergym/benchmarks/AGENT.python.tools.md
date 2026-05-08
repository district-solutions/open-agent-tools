# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/benchmarks/bench_test.py

Prompts

```
['run a benchmark that measures time to create and close a local CompilerGym environment', 'run a benchmark that measures time to create and close a CompilerGym service-connected environment', 'run a benchmark that measures the time to reset a CompilerGym environment', 'run a benchmark that measures the time to execute a single action step in a CompilerGym environment', 'run a benchmark that measures the time to fork and close a CompilerGym environment', 'run the parallelization load test benchmark comparing thread vs process performance at scale', 'run random search episodes on a CompilerGym environment with a fixed number of steps', 'benchmark thread-level parallelism against process-based parallelism for compute-bound random search workloads', 'measure parallelization scalability by varying worker count and recording steps per second', 'review the parallelization load test benchmark that compares threading and multiprocessing performance', 'run the smoke test for parallelization load test with threaded and process workers', 'run the parallelization load test main with custom env, benchmark, and nproc flags', 'capture stdout and stderr output while running the load test main function', 'set absl command line flags for env, benchmark, max_nproc, and num_episodes before running', 'verify that the parallelization load test generates a parallelization_load_test.csv output file']
```

Usage

```
{'run_benchmark_make_local': 'run a benchmark that measures time to create and close a local CompilerGym environment', 'run_benchmark_make_service': 'run a benchmark that measures time to create and close a CompilerGym service-connected environment', 'run_benchmark_reset': 'run a benchmark that measures the time to reset a CompilerGym environment', 'run_benchmark_step': 'run a benchmark that measures the time to execute a single action step in a CompilerGym environment', 'run_benchmark_fork': 'run a benchmark that measures the time to fork and close a CompilerGym environment'}
```

## File: facebookresearch_compilergym/benchmarks/parallelization_load_test.py

Prompts

```
['run a benchmark that measures time to create and close a local CompilerGym environment', 'run a benchmark that measures time to create and close a CompilerGym service-connected environment', 'run a benchmark that measures the time to reset a CompilerGym environment', 'run a benchmark that measures the time to execute a single action step in a CompilerGym environment', 'run a benchmark that measures the time to fork and close a CompilerGym environment', 'run the parallelization load test benchmark comparing thread vs process performance at scale', 'run random search episodes on a CompilerGym environment with a fixed number of steps', 'benchmark thread-level parallelism against process-based parallelism for compute-bound random search workloads', 'measure parallelization scalability by varying worker count and recording steps per second', 'review the parallelization load test benchmark that compares threading and multiprocessing performance', 'run the smoke test for parallelization load test with threaded and process workers', 'run the parallelization load test main with custom env, benchmark, and nproc flags', 'capture stdout and stderr output while running the load test main function', 'set absl command line flags for env, benchmark, max_nproc, and num_episodes before running', 'verify that the parallelization load test generates a parallelization_load_test.csv output file']
```

Usage

```
{'run_parallelization_load_test': 'run the parallelization load test benchmark comparing thread vs process performance at scale', 'run_random_search_episodes': 'run random search episodes on a CompilerGym environment with a fixed number of steps', 'benchmark_thread_vs_process': 'benchmark thread-level parallelism against process-based parallelism for compute-bound random search workloads', 'measure_parallel_scalability': 'measure parallelization scalability by varying worker count and recording steps per second', 'review_parallelization_load_test': 'review the parallelization load test benchmark that compares threading and multiprocessing performance'}
```

## File: facebookresearch_compilergym/benchmarks/parallelization_load_test_test.py

Prompts

```
['run a benchmark that measures time to create and close a local CompilerGym environment', 'run a benchmark that measures time to create and close a CompilerGym service-connected environment', 'run a benchmark that measures the time to reset a CompilerGym environment', 'run a benchmark that measures the time to execute a single action step in a CompilerGym environment', 'run a benchmark that measures the time to fork and close a CompilerGym environment', 'run the parallelization load test benchmark comparing thread vs process performance at scale', 'run random search episodes on a CompilerGym environment with a fixed number of steps', 'benchmark thread-level parallelism against process-based parallelism for compute-bound random search workloads', 'measure parallelization scalability by varying worker count and recording steps per second', 'review the parallelization load test benchmark that compares threading and multiprocessing performance', 'run the smoke test for parallelization load test with threaded and process workers', 'run the parallelization load test main with custom env, benchmark, and nproc flags', 'capture stdout and stderr output while running the load test main function', 'set absl command line flags for env, benchmark, max_nproc, and num_episodes before running', 'verify that the parallelization load test generates a parallelization_load_test.csv output file']
```

Usage

```
{'test_parallelization_load_test': 'run the smoke test for parallelization load test with threaded and process workers', 'run_load_test_with_flags': 'run the parallelization load test main with custom env, benchmark, and nproc flags', 'capture_output_during_test': 'capture stdout and stderr output while running the load test main function', 'set_command_line_flags': 'set absl command line flags for env, benchmark, max_nproc, and num_episodes before running', 'verify_csv_output': 'verify that the parallelization load test generates a parallelization_load_test.csv output file'}
```


# Agent Python Tools

- repo: facebookresearch/tensorcomprehensions
- repo_uri: https://github.com/facebookresearch/tensorcomprehensions

## File: facebookresearch_tensorcomprehensions/python/benchmarks/python_overhead.py

Prompts

```
['run the python overhead benchmark to measure tensor comprehensions abstraction performance', 'compile a tensor comprehension string into an executor using compile with MappingOptions', 'use CompilationCache to compile and run tensor comprehensions with low overhead', 'use Tuner with TunerConfig to autotune mapping options for tensor comprehension kernels', 'create a torch autograd function from tensor comprehensions using tc.make_autograd', 'run the time_tc function to benchmark CPU and GPU kernel execution times over multiple iterations', 'test the time_tc function with a custom entry point and inputs to measure latency', 'review the time_tc function to understand how it calculates min, p50, p90, and max timing percentiles', 'refactor the time_tc function to replace deprecated time.clock with time.perf_counter for modern Python', 'summarize the time_tc function which measures CPU launch time and CPU plus GPU kernel time']
```

Usage

```
{'run_benchmark_python_overhead': 'run the python overhead benchmark to measure tensor comprehensions abstraction performance', 'compile_tc_executor': 'compile a tensor comprehension string into an executor using compile with MappingOptions', 'use_compilation_cache': 'use CompilationCache to compile and run tensor comprehensions with low overhead', 'tune_mapping_options': 'use Tuner with TunerConfig to autotune mapping options for tensor comprehension kernels', 'create_autograd_function': 'create a torch autograd function from tensor comprehensions using tc.make_autograd'}
```

## File: facebookresearch_tensorcomprehensions/python/benchmarks/utils.py

Prompts

```
['run the python overhead benchmark to measure tensor comprehensions abstraction performance', 'compile a tensor comprehension string into an executor using compile with MappingOptions', 'use CompilationCache to compile and run tensor comprehensions with low overhead', 'use Tuner with TunerConfig to autotune mapping options for tensor comprehension kernels', 'create a torch autograd function from tensor comprehensions using tc.make_autograd', 'run the time_tc function to benchmark CPU and GPU kernel execution times over multiple iterations', 'test the time_tc function with a custom entry point and inputs to measure latency', 'review the time_tc function to understand how it calculates min, p50, p90, and max timing percentiles', 'refactor the time_tc function to replace deprecated time.clock with time.perf_counter for modern Python', 'summarize the time_tc function which measures CPU launch time and CPU plus GPU kernel time']
```

Usage

```
{'run_time_tc_benchmark': 'run the time_tc function to benchmark CPU and GPU kernel execution times over multiple iterations', 'test_time_tc_timing': 'test the time_tc function with a custom entry point and inputs to measure latency', 'review_time_tc_percentiles': 'review the time_tc function to understand how it calculates min, p50, p90, and max timing percentiles', 'refactor_time_tc_synchronization': 'refactor the time_tc function to replace deprecated time.clock with time.perf_counter for modern Python', 'summarize_time_tc_usage': 'summarize the time_tc function which measures CPU launch time and CPU plus GPU kernel time'}
```


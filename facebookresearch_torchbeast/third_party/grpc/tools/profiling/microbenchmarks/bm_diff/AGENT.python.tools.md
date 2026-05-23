# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/profiling/microbenchmarks/bm_diff/bm_build.py

Prompts

```
['build optimized C++ microbenchmark binaries using Bazel with the opt configuration', 'build C++ microbenchmark binaries with counters enabled using Bazel and copy to output directory', 'run the bm_build script with a unique name and list of benchmarks to compile', 'refactor the _build_config_and_copy function to support additional Bazel build configurations', 'review the build function that orchestrates opt and counters benchmark builds into a named directory', 'run the microbenchmark diff pipeline comparing new and old benchmark builds with configurable loops and jobs', 'build benchmark binaries for new and old configurations using bm_build with specified jobs and counters', 'create benchmark job lists for new and old runs with configurable loops and regex filters', 'compute performance differences between old and new benchmark results and generate a diff report', 'parse command line arguments for the benchmark diff pipeline including track metrics, benchmarks, diff base, and loops']
```

Usage

```
{'build_opt_benchmarks': 'build optimized C++ microbenchmark binaries using Bazel with the opt configuration', 'build_counters_benchmarks': 'build C++ microbenchmark binaries with counters enabled using Bazel and copy to output directory', 'run_bm_build_cli': 'run the bm_build script with a unique name and list of benchmarks to compile', 'refactor_build_config_and_copy': 'refactor the _build_config_and_copy function to support additional Bazel build configurations', 'review_build_function': 'review the build function that orchestrates opt and counters benchmark builds into a named directory'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/profiling/microbenchmarks/bm_diff/bm_main.py

Prompts

```
['build optimized C++ microbenchmark binaries using Bazel with the opt configuration', 'build C++ microbenchmark binaries with counters enabled using Bazel and copy to output directory', 'run the bm_build script with a unique name and list of benchmarks to compile', 'refactor the _build_config_and_copy function to support additional Bazel build configurations', 'review the build function that orchestrates opt and counters benchmark builds into a named directory', 'run the microbenchmark diff pipeline comparing new and old benchmark builds with configurable loops and jobs', 'build benchmark binaries for new and old configurations using bm_build with specified jobs and counters', 'create benchmark job lists for new and old runs with configurable loops and regex filters', 'compute performance differences between old and new benchmark results and generate a diff report', 'parse command line arguments for the benchmark diff pipeline including track metrics, benchmarks, diff base, and loops']
```

Usage

```
{'run_bm_main_pipeline': 'run the microbenchmark diff pipeline comparing new and old benchmark builds with configurable loops and jobs', 'build_benchmark_binaries': 'build benchmark binaries for new and old configurations using bm_build with specified jobs and counters', 'create_benchmark_jobs': 'create benchmark job lists for new and old runs with configurable loops and regex filters', 'diff_benchmark_results': 'compute performance differences between old and new benchmark results and generate a diff report', 'parse_bm_args': 'parse command line arguments for the benchmark diff pipeline including track metrics, benchmarks, diff base, and loops'}
```


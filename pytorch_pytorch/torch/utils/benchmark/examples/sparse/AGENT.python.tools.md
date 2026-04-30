# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/utils/benchmark/examples/sparse/compare.py

Prompts

```
['benchmark sparse matrix multiplication operations using Timer and Compare APIs with multiple configurations', 'create benchmark timers with FauxTorch to simulate different pytorch branch performance overheads', 'generate COO sparse tensor indices and values with configurable size, density, dtype, and device', 'compare serialized timer results using Compare API with trim_significant_figures and colorize formatting', 'run the sparse benchmark example that tests matmul operations across multiple sizes, densities, and thread counts', 'create a Fuzzer with FuzzedParameter and FuzzedSparseTensor to generate random sparse tensor configurations', 'build a FuzzedParameter with loguniform distribution for numeric range fuzzing', 'build a FuzzedSparseTensor with fuzzed size, density, and coalesced properties for sparse benchmarking', 'run a Timer benchmark on torch.sparse.sum statements with blocked_autorange for timing measurements', 'test the Fuzzer.take method to generate random sparse tensor configurations with properties', 'run the op_benchmark module to measure unary sparse op kernel performance with Timer', 'run the op_benchmark module to measure binary sparse op kernel performance with Timer', 'test the UnaryOpSparseFuzzer class to generate sparse tensor inputs for benchmarking', 'test the BinaryOpSparseFuzzer class to generate sparse tensor inputs for benchmarking', 'summarize the run function that measures float32 vs float64 sparse tensor operation performance']
```

Usage

```
{'benchmark_sparse_matmul_operations': 'benchmark sparse matrix multiplication operations using Timer and Compare APIs with multiple configurations', 'create_timer_with_faux_torch_branches': 'create benchmark timers with FauxTorch to simulate different pytorch branch performance overheads', 'generate_coo_sparse_tensor_data': 'generate COO sparse tensor indices and values with configurable size, density, dtype, and device', 'compare_serialized_timer_results': 'compare serialized timer results using Compare API with trim_significant_figures and colorize formatting', 'run_sparse_benchmark_example': 'run the sparse benchmark example that tests matmul operations across multiple sizes, densities, and thread counts'}
```

## File: pytorch_pytorch/torch/utils/benchmark/examples/sparse/fuzzer.py

Prompts

```
['benchmark sparse matrix multiplication operations using Timer and Compare APIs with multiple configurations', 'create benchmark timers with FauxTorch to simulate different pytorch branch performance overheads', 'generate COO sparse tensor indices and values with configurable size, density, dtype, and device', 'compare serialized timer results using Compare API with trim_significant_figures and colorize formatting', 'run the sparse benchmark example that tests matmul operations across multiple sizes, densities, and thread counts', 'create a Fuzzer with FuzzedParameter and FuzzedSparseTensor to generate random sparse tensor configurations', 'build a FuzzedParameter with loguniform distribution for numeric range fuzzing', 'build a FuzzedSparseTensor with fuzzed size, density, and coalesced properties for sparse benchmarking', 'run a Timer benchmark on torch.sparse.sum statements with blocked_autorange for timing measurements', 'test the Fuzzer.take method to generate random sparse tensor configurations with properties', 'run the op_benchmark module to measure unary sparse op kernel performance with Timer', 'run the op_benchmark module to measure binary sparse op kernel performance with Timer', 'test the UnaryOpSparseFuzzer class to generate sparse tensor inputs for benchmarking', 'test the BinaryOpSparseFuzzer class to generate sparse tensor inputs for benchmarking', 'summarize the run function that measures float32 vs float64 sparse tensor operation performance']
```

Usage

```
{'create_fuzzer_sparse_benchmark': 'create a Fuzzer with FuzzedParameter and FuzzedSparseTensor to generate random sparse tensor configurations', 'build_fuzzed_parameter_loguniform': 'build a FuzzedParameter with loguniform distribution for numeric range fuzzing', 'build_fuzzed_sparse_tensor': 'build a FuzzedSparseTensor with fuzzed size, density, and coalesced properties for sparse benchmarking', 'run_timer_benchmark': 'run a Timer benchmark on torch.sparse.sum statements with blocked_autorange for timing measurements', 'test_fuzzer_tensor_generation': 'test the Fuzzer.take method to generate random sparse tensor configurations with properties'}
```

## File: pytorch_pytorch/torch/utils/benchmark/examples/sparse/op_benchmark.py

Prompts

```
['benchmark sparse matrix multiplication operations using Timer and Compare APIs with multiple configurations', 'create benchmark timers with FauxTorch to simulate different pytorch branch performance overheads', 'generate COO sparse tensor indices and values with configurable size, density, dtype, and device', 'compare serialized timer results using Compare API with trim_significant_figures and colorize formatting', 'run the sparse benchmark example that tests matmul operations across multiple sizes, densities, and thread counts', 'create a Fuzzer with FuzzedParameter and FuzzedSparseTensor to generate random sparse tensor configurations', 'build a FuzzedParameter with loguniform distribution for numeric range fuzzing', 'build a FuzzedSparseTensor with fuzzed size, density, and coalesced properties for sparse benchmarking', 'run a Timer benchmark on torch.sparse.sum statements with blocked_autorange for timing measurements', 'test the Fuzzer.take method to generate random sparse tensor configurations with properties', 'run the op_benchmark module to measure unary sparse op kernel performance with Timer', 'run the op_benchmark module to measure binary sparse op kernel performance with Timer', 'test the UnaryOpSparseFuzzer class to generate sparse tensor inputs for benchmarking', 'test the BinaryOpSparseFuzzer class to generate sparse tensor inputs for benchmarking', 'summarize the run function that measures float32 vs float64 sparse tensor operation performance']
```

Usage

```
{'run_sparse_unary_benchmark': 'run the op_benchmark module to measure unary sparse op kernel performance with Timer', 'run_sparse_binary_benchmark': 'run the op_benchmark module to measure binary sparse op kernel performance with Timer', 'test_UnaryOpSparseFuzzer': 'test the UnaryOpSparseFuzzer class to generate sparse tensor inputs for benchmarking', 'test_BinaryOpSparseFuzzer': 'test the BinaryOpSparseFuzzer class to generate sparse tensor inputs for benchmarking', 'summarize_run_function': 'summarize the run function that measures float32 vs float64 sparse tensor operation performance'}
```


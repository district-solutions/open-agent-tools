# Agent Python Tools

- repo: facebookresearch/holistictraceanalysis
- repo_uri: https://github.com/facebookresearch/holistictraceanalysis

## File: facebookresearch_holistictraceanalysis/third_party/param/train/compute/python/test/test_benchmark_load.py

Prompts

```
['test loading a PyTorch benchmark from a JSON config file using BenchmarkConfig and make_default_benchmark', 'run the unittest TestBenchmarkLoad suite to verify benchmark JSON config loading works correctly', 'review the TestBenchmarkLoad unittest class that validates benchmark creation from JSON configuration files', 'refactor the test_json_load_benchmark method to support additional benchmark config validation assertions', 'summarize how load_modules is used to register PyTorch implementations for data generators and operators', 'test the full_range function that generates an inclusive numeric range with a given step', 'test the IterableList class that provides a repeatable iterator over a list of items', 'test the ListProduct class that generates the Cartesian product of a list of iterables', 'test the TableProduct class that generates the Cartesian product of a dictionary of iterables', 'test nested ListProduct and TableProduct combinations for generating complex parameter grids', 'test the register_config_iterator function to register a ConfigIterator subclass and verify duplicate registration raises ValueError', 'test the register_data_generator function to register a DataGenerator subclass and verify duplicate registration raises ValueError', 'test the register_operator function to register a single OperatorInterface subclass and verify duplicate registration raises ValueError', 'test the register_operators function to batch register multiple operators via a dict and verify duplicate registration raises ValueError', 'run the unittest TestRegister suite to validate all registration functions for config iterators, data generators, and operators', 'test the SplitTableBatchedEmbeddingBagsCodegen op build with single table embedding specs', 'test building multi-table batched embedding bags with different row sizes and dimensions', 'run the unittest test_build_op to verify embedding specs for single and multi table configs', 'create an op config using make_op_config with SplitTableBatchedEmbeddingBagsCodegen and cpu device', 'review the TestSplitTableBatchedEmbeddingOps class and its skipped test_build_op method']
```

Usage

```
{'test_benchmark_json_load': 'test loading a PyTorch benchmark from a JSON config file using BenchmarkConfig and make_default_benchmark', 'run_test_benchmark_load': 'run the unittest TestBenchmarkLoad suite to verify benchmark JSON config loading works correctly', 'review_TestBenchmarkLoad_class': 'review the TestBenchmarkLoad unittest class that validates benchmark creation from JSON configuration files', 'refactor_test_json_load_benchmark': 'refactor the test_json_load_benchmark method to support additional benchmark config validation assertions', 'summarize_load_modules_usage': 'summarize how load_modules is used to register PyTorch implementations for data generators and operators'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/train/compute/python/test/test_generator.py

Prompts

```
['test loading a PyTorch benchmark from a JSON config file using BenchmarkConfig and make_default_benchmark', 'run the unittest TestBenchmarkLoad suite to verify benchmark JSON config loading works correctly', 'review the TestBenchmarkLoad unittest class that validates benchmark creation from JSON configuration files', 'refactor the test_json_load_benchmark method to support additional benchmark config validation assertions', 'summarize how load_modules is used to register PyTorch implementations for data generators and operators', 'test the full_range function that generates an inclusive numeric range with a given step', 'test the IterableList class that provides a repeatable iterator over a list of items', 'test the ListProduct class that generates the Cartesian product of a list of iterables', 'test the TableProduct class that generates the Cartesian product of a dictionary of iterables', 'test nested ListProduct and TableProduct combinations for generating complex parameter grids', 'test the register_config_iterator function to register a ConfigIterator subclass and verify duplicate registration raises ValueError', 'test the register_data_generator function to register a DataGenerator subclass and verify duplicate registration raises ValueError', 'test the register_operator function to register a single OperatorInterface subclass and verify duplicate registration raises ValueError', 'test the register_operators function to batch register multiple operators via a dict and verify duplicate registration raises ValueError', 'run the unittest TestRegister suite to validate all registration functions for config iterators, data generators, and operators', 'test the SplitTableBatchedEmbeddingBagsCodegen op build with single table embedding specs', 'test building multi-table batched embedding bags with different row sizes and dimensions', 'run the unittest test_build_op to verify embedding specs for single and multi table configs', 'create an op config using make_op_config with SplitTableBatchedEmbeddingBagsCodegen and cpu device', 'review the TestSplitTableBatchedEmbeddingOps class and its skipped test_build_op method']
```

Usage

```
{'test_full_range': 'test the full_range function that generates an inclusive numeric range with a given step', 'test_iterable_list': 'test the IterableList class that provides a repeatable iterator over a list of items', 'test_list_product': 'test the ListProduct class that generates the Cartesian product of a list of iterables', 'test_table_product': 'test the TableProduct class that generates the Cartesian product of a dictionary of iterables', 'test_nested_products': 'test nested ListProduct and TableProduct combinations for generating complex parameter grids'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/train/compute/python/test/test_register.py

Prompts

```
['test loading a PyTorch benchmark from a JSON config file using BenchmarkConfig and make_default_benchmark', 'run the unittest TestBenchmarkLoad suite to verify benchmark JSON config loading works correctly', 'review the TestBenchmarkLoad unittest class that validates benchmark creation from JSON configuration files', 'refactor the test_json_load_benchmark method to support additional benchmark config validation assertions', 'summarize how load_modules is used to register PyTorch implementations for data generators and operators', 'test the full_range function that generates an inclusive numeric range with a given step', 'test the IterableList class that provides a repeatable iterator over a list of items', 'test the ListProduct class that generates the Cartesian product of a list of iterables', 'test the TableProduct class that generates the Cartesian product of a dictionary of iterables', 'test nested ListProduct and TableProduct combinations for generating complex parameter grids', 'test the register_config_iterator function to register a ConfigIterator subclass and verify duplicate registration raises ValueError', 'test the register_data_generator function to register a DataGenerator subclass and verify duplicate registration raises ValueError', 'test the register_operator function to register a single OperatorInterface subclass and verify duplicate registration raises ValueError', 'test the register_operators function to batch register multiple operators via a dict and verify duplicate registration raises ValueError', 'run the unittest TestRegister suite to validate all registration functions for config iterators, data generators, and operators', 'test the SplitTableBatchedEmbeddingBagsCodegen op build with single table embedding specs', 'test building multi-table batched embedding bags with different row sizes and dimensions', 'run the unittest test_build_op to verify embedding specs for single and multi table configs', 'create an op config using make_op_config with SplitTableBatchedEmbeddingBagsCodegen and cpu device', 'review the TestSplitTableBatchedEmbeddingOps class and its skipped test_build_op method']
```

Usage

```
{'test_register_config_iterator': 'test the register_config_iterator function to register a ConfigIterator subclass and verify duplicate registration raises ValueError', 'test_register_data_generator': 'test the register_data_generator function to register a DataGenerator subclass and verify duplicate registration raises ValueError', 'test_register_operator': 'test the register_operator function to register a single OperatorInterface subclass and verify duplicate registration raises ValueError', 'test_register_operators': 'test the register_operators function to batch register multiple operators via a dict and verify duplicate registration raises ValueError', 'run_test_register_suite': 'run the unittest TestRegister suite to validate all registration functions for config iterators, data generators, and operators'}
```

## File: facebookresearch_holistictraceanalysis/third_party/param/train/compute/python/test/test_split_table_batched_embeddings_ops.py

Prompts

```
['test loading a PyTorch benchmark from a JSON config file using BenchmarkConfig and make_default_benchmark', 'run the unittest TestBenchmarkLoad suite to verify benchmark JSON config loading works correctly', 'review the TestBenchmarkLoad unittest class that validates benchmark creation from JSON configuration files', 'refactor the test_json_load_benchmark method to support additional benchmark config validation assertions', 'summarize how load_modules is used to register PyTorch implementations for data generators and operators', 'test the full_range function that generates an inclusive numeric range with a given step', 'test the IterableList class that provides a repeatable iterator over a list of items', 'test the ListProduct class that generates the Cartesian product of a list of iterables', 'test the TableProduct class that generates the Cartesian product of a dictionary of iterables', 'test nested ListProduct and TableProduct combinations for generating complex parameter grids', 'test the register_config_iterator function to register a ConfigIterator subclass and verify duplicate registration raises ValueError', 'test the register_data_generator function to register a DataGenerator subclass and verify duplicate registration raises ValueError', 'test the register_operator function to register a single OperatorInterface subclass and verify duplicate registration raises ValueError', 'test the register_operators function to batch register multiple operators via a dict and verify duplicate registration raises ValueError', 'run the unittest TestRegister suite to validate all registration functions for config iterators, data generators, and operators', 'test the SplitTableBatchedEmbeddingBagsCodegen op build with single table embedding specs', 'test building multi-table batched embedding bags with different row sizes and dimensions', 'run the unittest test_build_op to verify embedding specs for single and multi table configs', 'create an op config using make_op_config with SplitTableBatchedEmbeddingBagsCodegen and cpu device', 'review the TestSplitTableBatchedEmbeddingOps class and its skipped test_build_op method']
```

Usage

```
{'test_SplitTableBatchedEmbeddingBagsCodegen': 'test the SplitTableBatchedEmbeddingBagsCodegen op build with single table embedding specs', 'test_multi_table_embeddings': 'test building multi-table batched embedding bags with different row sizes and dimensions', 'run_test_build_op': 'run the unittest test_build_op to verify embedding specs for single and multi table configs', 'create_op_config': 'create an op config using make_op_config with SplitTableBatchedEmbeddingBagsCodegen and cpu device', 'review_TestSplitTableBatchedEmbeddingOps': 'review the TestSplitTableBatchedEmbeddingOps class and its skipped test_build_op method'}
```


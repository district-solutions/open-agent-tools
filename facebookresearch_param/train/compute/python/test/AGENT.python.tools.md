# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/train/compute/python/test/test_benchmark_load.py

Prompts

```
['run the unittest to verify loading a PyTorch benchmark from a JSON config file', 'test that make_default_benchmark returns a valid Benchmark instance from a JSON config', 'review the TestBenchmarkLoad class and its test_json_load_benchmark method for correctness', 'refactor the TestBenchmarkLoad setUp to load modules from a different library path', 'summarize how make_default_benchmark constructs a Benchmark from a BenchmarkConfig', 'test the full_range function to generate a list of numbers from start to end with a given step', 'test the IterableList class to iterate over a list of items including nested ListProduct objects', 'test the ListProduct class to generate all combinations of values from a list of scalars and iterables', 'test the TableProduct class to generate all combinations of values from a dictionary of scalars and iterables', 'run the unittest test suite for the generator module covering full_range, IterableList, ListProduct, and TableProduct', 'test that register_config_iterator adds a ConfigIterator subclass to config_iterator_map and rejects duplicates', 'test that register_data_generator adds a DataGenerator subclass to data_generator_map and rejects duplicates', 'test that register_operator adds an OperatorInterface subclass to op_map and rejects duplicate registrations', 'test that register_operators bulk-registers multiple operators and raises ValueError when any name already exists', 'run the TestRegister unittest suite to validate all registration functions for config iterators, data generators, and operators', 'run the unit test for SplitTableBatchedEmbeddingBagsCodegen op building with single and multi-table configs', 'build a SplitTableBatchedEmbeddingBagsCodegen op with a single table using make_op_config and op.build', 'build a SplitTableBatchedEmbeddingBagsCodegen op with multiple tables and different embedding dimensions', 'create an op_info dictionary using create_op_info and set the input_data_generator key', 'review the test_build_op method to understand how embedding specs are validated after building']
```

Usage

```
{'run_benchmark_load_test': 'run the unittest to verify loading a PyTorch benchmark from a JSON config file', 'test_json_load_benchmark': 'test that make_default_benchmark returns a valid Benchmark instance from a JSON config', 'review_TestBenchmarkLoad': 'review the TestBenchmarkLoad class and its test_json_load_benchmark method for correctness', 'refactor_TestBenchmarkLoad': 'refactor the TestBenchmarkLoad setUp to load modules from a different library path', 'summarize_make_default_benchmark': 'summarize how make_default_benchmark constructs a Benchmark from a BenchmarkConfig'}
```

## File: facebookresearch_param/train/compute/python/test/test_generator.py

Prompts

```
['run the unittest to verify loading a PyTorch benchmark from a JSON config file', 'test that make_default_benchmark returns a valid Benchmark instance from a JSON config', 'review the TestBenchmarkLoad class and its test_json_load_benchmark method for correctness', 'refactor the TestBenchmarkLoad setUp to load modules from a different library path', 'summarize how make_default_benchmark constructs a Benchmark from a BenchmarkConfig', 'test the full_range function to generate a list of numbers from start to end with a given step', 'test the IterableList class to iterate over a list of items including nested ListProduct objects', 'test the ListProduct class to generate all combinations of values from a list of scalars and iterables', 'test the TableProduct class to generate all combinations of values from a dictionary of scalars and iterables', 'run the unittest test suite for the generator module covering full_range, IterableList, ListProduct, and TableProduct', 'test that register_config_iterator adds a ConfigIterator subclass to config_iterator_map and rejects duplicates', 'test that register_data_generator adds a DataGenerator subclass to data_generator_map and rejects duplicates', 'test that register_operator adds an OperatorInterface subclass to op_map and rejects duplicate registrations', 'test that register_operators bulk-registers multiple operators and raises ValueError when any name already exists', 'run the TestRegister unittest suite to validate all registration functions for config iterators, data generators, and operators', 'run the unit test for SplitTableBatchedEmbeddingBagsCodegen op building with single and multi-table configs', 'build a SplitTableBatchedEmbeddingBagsCodegen op with a single table using make_op_config and op.build', 'build a SplitTableBatchedEmbeddingBagsCodegen op with multiple tables and different embedding dimensions', 'create an op_info dictionary using create_op_info and set the input_data_generator key', 'review the test_build_op method to understand how embedding specs are validated after building']
```

Usage

```
{'test_full_range': 'test the full_range function to generate a list of numbers from start to end with a given step', 'test_iterable_list': 'test the IterableList class to iterate over a list of items including nested ListProduct objects', 'test_list_product': 'test the ListProduct class to generate all combinations of values from a list of scalars and iterables', 'test_table_product': 'test the TableProduct class to generate all combinations of values from a dictionary of scalars and iterables', 'run_generator_tests': 'run the unittest test suite for the generator module covering full_range, IterableList, ListProduct, and TableProduct'}
```

## File: facebookresearch_param/train/compute/python/test/test_register.py

Prompts

```
['run the unittest to verify loading a PyTorch benchmark from a JSON config file', 'test that make_default_benchmark returns a valid Benchmark instance from a JSON config', 'review the TestBenchmarkLoad class and its test_json_load_benchmark method for correctness', 'refactor the TestBenchmarkLoad setUp to load modules from a different library path', 'summarize how make_default_benchmark constructs a Benchmark from a BenchmarkConfig', 'test the full_range function to generate a list of numbers from start to end with a given step', 'test the IterableList class to iterate over a list of items including nested ListProduct objects', 'test the ListProduct class to generate all combinations of values from a list of scalars and iterables', 'test the TableProduct class to generate all combinations of values from a dictionary of scalars and iterables', 'run the unittest test suite for the generator module covering full_range, IterableList, ListProduct, and TableProduct', 'test that register_config_iterator adds a ConfigIterator subclass to config_iterator_map and rejects duplicates', 'test that register_data_generator adds a DataGenerator subclass to data_generator_map and rejects duplicates', 'test that register_operator adds an OperatorInterface subclass to op_map and rejects duplicate registrations', 'test that register_operators bulk-registers multiple operators and raises ValueError when any name already exists', 'run the TestRegister unittest suite to validate all registration functions for config iterators, data generators, and operators', 'run the unit test for SplitTableBatchedEmbeddingBagsCodegen op building with single and multi-table configs', 'build a SplitTableBatchedEmbeddingBagsCodegen op with a single table using make_op_config and op.build', 'build a SplitTableBatchedEmbeddingBagsCodegen op with multiple tables and different embedding dimensions', 'create an op_info dictionary using create_op_info and set the input_data_generator key', 'review the test_build_op method to understand how embedding specs are validated after building']
```

Usage

```
{'test_register_config_iterator': 'test that register_config_iterator adds a ConfigIterator subclass to config_iterator_map and rejects duplicates', 'test_register_data_generator': 'test that register_data_generator adds a DataGenerator subclass to data_generator_map and rejects duplicates', 'test_register_operator': 'test that register_operator adds an OperatorInterface subclass to op_map and rejects duplicate registrations', 'test_register_operators': 'test that register_operators bulk-registers multiple operators and raises ValueError when any name already exists', 'run_test_register_suite': 'run the TestRegister unittest suite to validate all registration functions for config iterators, data generators, and operators'}
```

## File: facebookresearch_param/train/compute/python/test/test_split_table_batched_embeddings_ops.py

Prompts

```
['run the unittest to verify loading a PyTorch benchmark from a JSON config file', 'test that make_default_benchmark returns a valid Benchmark instance from a JSON config', 'review the TestBenchmarkLoad class and its test_json_load_benchmark method for correctness', 'refactor the TestBenchmarkLoad setUp to load modules from a different library path', 'summarize how make_default_benchmark constructs a Benchmark from a BenchmarkConfig', 'test the full_range function to generate a list of numbers from start to end with a given step', 'test the IterableList class to iterate over a list of items including nested ListProduct objects', 'test the ListProduct class to generate all combinations of values from a list of scalars and iterables', 'test the TableProduct class to generate all combinations of values from a dictionary of scalars and iterables', 'run the unittest test suite for the generator module covering full_range, IterableList, ListProduct, and TableProduct', 'test that register_config_iterator adds a ConfigIterator subclass to config_iterator_map and rejects duplicates', 'test that register_data_generator adds a DataGenerator subclass to data_generator_map and rejects duplicates', 'test that register_operator adds an OperatorInterface subclass to op_map and rejects duplicate registrations', 'test that register_operators bulk-registers multiple operators and raises ValueError when any name already exists', 'run the TestRegister unittest suite to validate all registration functions for config iterators, data generators, and operators', 'run the unit test for SplitTableBatchedEmbeddingBagsCodegen op building with single and multi-table configs', 'build a SplitTableBatchedEmbeddingBagsCodegen op with a single table using make_op_config and op.build', 'build a SplitTableBatchedEmbeddingBagsCodegen op with multiple tables and different embedding dimensions', 'create an op_info dictionary using create_op_info and set the input_data_generator key', 'review the test_build_op method to understand how embedding specs are validated after building']
```

Usage

```
{'test_split_table_batched_embedding_ops': 'run the unit test for SplitTableBatchedEmbeddingBagsCodegen op building with single and multi-table configs', 'build_op_single_table': 'build a SplitTableBatchedEmbeddingBagsCodegen op with a single table using make_op_config and op.build', 'build_op_multi_table': 'build a SplitTableBatchedEmbeddingBagsCodegen op with multiple tables and different embedding dimensions', 'create_op_info': 'create an op_info dictionary using create_op_info and set the input_data_generator key', 'review_test_build_op': 'review the test_build_op method to understand how embedding specs are validated after building'}
```


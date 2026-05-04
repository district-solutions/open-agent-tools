# Agent Python Tools

- repo: google-deepmind/enn
- repo_uri: https://github.com/google-deepmind/enn

## File: google-deepmind_enn/enn/loggers.py

Prompts

```
['create a TerminalLogger instance with a label and optional time_delta for throttled terminal logging', 'write a dictionary of key-value logging data to the terminal using TerminalLogger.write method', 'serialize a dictionary of logging data into a pretty-printed pipe-separated string with formatted keys', 'make a default TerminalLogger with a label string and optional time delta for rate limiting', 'convert nested TensorFlow or JAX tensors to numpy arrays using the _to_numpy utility function', 'create a batched EpistemicIndexer that produces batch_size index samples from a JAX PRNG key', 'build a shuffled and repeated batch iterator from ArrayBatch data for SGD training', 'generate a synthetic moons dataset batch iterator for classification or regression testing', 'review an ArrayBatch and fix missing batch dimensions, data indices, and weight fields', 'summarize the ENN utility functions for batching, indexing, and test data generation', 'test make_batch_indexer with PrngIndexer to verify batch index shape and uniqueness', 'test make_batch_indexer with ScaledGaussianIndexer to verify batch index shape and uniqueness', 'test make_batch_indexer with GaussianWithUnitIndexer to verify batch index shape and uniqueness', 'test make_batch_indexer with EnsembleIndexer to verify batch index shape and uniqueness', 'review UtilsTest.test_batch_indexer parameterized test for ENN utility batch indexing']
```

Usage

```
{'create_terminal_logger': 'create a TerminalLogger instance with a label and optional time_delta for throttled terminal logging', 'write_log_data': 'write a dictionary of key-value logging data to the terminal using TerminalLogger.write method', 'serialize_logging_data': 'serialize a dictionary of logging data into a pretty-printed pipe-separated string with formatted keys', 'make_default_logger': 'make a default TerminalLogger with a label string and optional time delta for rate limiting', 'convert_tensors_to_numpy': 'convert nested TensorFlow or JAX tensors to numpy arrays using the _to_numpy utility function'}
```

## File: google-deepmind_enn/enn/utils.py

Prompts

```
['create a TerminalLogger instance with a label and optional time_delta for throttled terminal logging', 'write a dictionary of key-value logging data to the terminal using TerminalLogger.write method', 'serialize a dictionary of logging data into a pretty-printed pipe-separated string with formatted keys', 'make a default TerminalLogger with a label string and optional time delta for rate limiting', 'convert nested TensorFlow or JAX tensors to numpy arrays using the _to_numpy utility function', 'create a batched EpistemicIndexer that produces batch_size index samples from a JAX PRNG key', 'build a shuffled and repeated batch iterator from ArrayBatch data for SGD training', 'generate a synthetic moons dataset batch iterator for classification or regression testing', 'review an ArrayBatch and fix missing batch dimensions, data indices, and weight fields', 'summarize the ENN utility functions for batching, indexing, and test data generation', 'test make_batch_indexer with PrngIndexer to verify batch index shape and uniqueness', 'test make_batch_indexer with ScaledGaussianIndexer to verify batch index shape and uniqueness', 'test make_batch_indexer with GaussianWithUnitIndexer to verify batch index shape and uniqueness', 'test make_batch_indexer with EnsembleIndexer to verify batch index shape and uniqueness', 'review UtilsTest.test_batch_indexer parameterized test for ENN utility batch indexing']
```

Usage

```
{'make_batch_indexer': 'create a batched EpistemicIndexer that produces batch_size index samples from a JAX PRNG key', 'make_batch_iterator': 'build a shuffled and repeated batch iterator from ArrayBatch data for SGD training', 'make_test_data': 'generate a synthetic moons dataset batch iterator for classification or regression testing', 'clean_batch_data': 'review an ArrayBatch and fix missing batch dimensions, data indices, and weight fields', 'summarize_utils': 'summarize the ENN utility functions for batching, indexing, and test data generation'}
```

## File: google-deepmind_enn/enn/utils_test.py

Prompts

```
['create a TerminalLogger instance with a label and optional time_delta for throttled terminal logging', 'write a dictionary of key-value logging data to the terminal using TerminalLogger.write method', 'serialize a dictionary of logging data into a pretty-printed pipe-separated string with formatted keys', 'make a default TerminalLogger with a label string and optional time delta for rate limiting', 'convert nested TensorFlow or JAX tensors to numpy arrays using the _to_numpy utility function', 'create a batched EpistemicIndexer that produces batch_size index samples from a JAX PRNG key', 'build a shuffled and repeated batch iterator from ArrayBatch data for SGD training', 'generate a synthetic moons dataset batch iterator for classification or regression testing', 'review an ArrayBatch and fix missing batch dimensions, data indices, and weight fields', 'summarize the ENN utility functions for batching, indexing, and test data generation', 'test make_batch_indexer with PrngIndexer to verify batch index shape and uniqueness', 'test make_batch_indexer with ScaledGaussianIndexer to verify batch index shape and uniqueness', 'test make_batch_indexer with GaussianWithUnitIndexer to verify batch index shape and uniqueness', 'test make_batch_indexer with EnsembleIndexer to verify batch index shape and uniqueness', 'review UtilsTest.test_batch_indexer parameterized test for ENN utility batch indexing']
```

Usage

```
{'test_make_batch_indexer_with_prng_indexer': 'test make_batch_indexer with PrngIndexer to verify batch index shape and uniqueness', 'test_make_batch_indexer_with_scaled_gaussian_indexer': 'test make_batch_indexer with ScaledGaussianIndexer to verify batch index shape and uniqueness', 'test_make_batch_indexer_with_gaussian_unit_indexer': 'test make_batch_indexer with GaussianWithUnitIndexer to verify batch index shape and uniqueness', 'test_make_batch_indexer_with_ensemble_indexer': 'test make_batch_indexer with EnsembleIndexer to verify batch index shape and uniqueness', 'review_utils_test_batch_indexer': 'review UtilsTest.test_batch_indexer parameterized test for ENN utility batch indexing'}
```


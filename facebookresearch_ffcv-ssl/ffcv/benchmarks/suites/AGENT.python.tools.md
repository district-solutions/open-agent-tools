# Agent Python Tools

- repo: facebookresearch/ffcv-ssl
- repo_uri: https://github.com/facebookresearch/ffcv-ssl

## File: facebookresearch_ffcv-ssl/ffcv/benchmarks/suites/image_read.py

Prompts

```
['run the ImageReadBench benchmark to measure FFCV image read performance with configurable parameters', 'create a DummyDataset that generates random uint8 images of a specified size and length', 'review the ImageReadBench __enter__ method that sets up DatasetWriter, Reader, and OSCacheManager', 'test the DummyDataset __getitem__ method to verify it returns random image data for valid indices', 'summarize the benchmark decorator that parameterizes ImageReadBench with n, mode, size, and num_workers', 'run the JPEGDecodeBenchmark class to benchmark JPEG image decoding performance with configurable parameters', 'build a JPEG decode benchmark that encodes images at different qualities and measures decode speed', 'test the imdecode function from libffcv for decoding JPEG encoded image data into numpy arrays', 'review the JPEGDecodeBenchmark __enter__ method that loads resizes and encodes images for benchmarking', 'summarize the Compiler compile method used to optimize the imdecode and code functions for benchmarking', 'run the MemoryReadBytesBench benchmark to measure memory read performance for byte data', 'create a DummyDataset that returns random byte arrays with configurable length and size', 'benchmark the DatasetWriter to write a PyTorch dataset with IntField and BytesField columns', 'test the OSCacheManager to schedule and compile readers for memory-mapped data access', 'review the Compiler to compile memcpy operations for optimized memory copy performance']
```

Usage

```
{'run_ImageReadBench': 'run the ImageReadBench benchmark to measure FFCV image read performance with configurable parameters', 'create_DummyDataset': 'create a DummyDataset that generates random uint8 images of a specified size and length', 'review_ImageReadBench_enter': 'review the ImageReadBench __enter__ method that sets up DatasetWriter, Reader, and OSCacheManager', 'test_DummyDataset_getitem': 'test the DummyDataset __getitem__ method to verify it returns random image data for valid indices', 'summarize_benchmark_decorator': 'summarize the benchmark decorator that parameterizes ImageReadBench with n, mode, size, and num_workers'}
```

## File: facebookresearch_ffcv-ssl/ffcv/benchmarks/suites/jpeg_decode.py

Prompts

```
['run the ImageReadBench benchmark to measure FFCV image read performance with configurable parameters', 'create a DummyDataset that generates random uint8 images of a specified size and length', 'review the ImageReadBench __enter__ method that sets up DatasetWriter, Reader, and OSCacheManager', 'test the DummyDataset __getitem__ method to verify it returns random image data for valid indices', 'summarize the benchmark decorator that parameterizes ImageReadBench with n, mode, size, and num_workers', 'run the JPEGDecodeBenchmark class to benchmark JPEG image decoding performance with configurable parameters', 'build a JPEG decode benchmark that encodes images at different qualities and measures decode speed', 'test the imdecode function from libffcv for decoding JPEG encoded image data into numpy arrays', 'review the JPEGDecodeBenchmark __enter__ method that loads resizes and encodes images for benchmarking', 'summarize the Compiler compile method used to optimize the imdecode and code functions for benchmarking', 'run the MemoryReadBytesBench benchmark to measure memory read performance for byte data', 'create a DummyDataset that returns random byte arrays with configurable length and size', 'benchmark the DatasetWriter to write a PyTorch dataset with IntField and BytesField columns', 'test the OSCacheManager to schedule and compile readers for memory-mapped data access', 'review the Compiler to compile memcpy operations for optimized memory copy performance']
```

Usage

```
{'run_JPEGDecodeBenchmark': 'run the JPEGDecodeBenchmark class to benchmark JPEG image decoding performance with configurable parameters', 'build_JPEGDecodeBenchmark': 'build a JPEG decode benchmark that encodes images at different qualities and measures decode speed', 'test_imdecode': 'test the imdecode function from libffcv for decoding JPEG encoded image data into numpy arrays', 'review_JPEGDecodeBenchmark_enter': 'review the JPEGDecodeBenchmark __enter__ method that loads resizes and encodes images for benchmarking', 'summarize_Compiler_compile': 'summarize the Compiler compile method used to optimize the imdecode and code functions for benchmarking'}
```

## File: facebookresearch_ffcv-ssl/ffcv/benchmarks/suites/memory_read.py

Prompts

```
['run the ImageReadBench benchmark to measure FFCV image read performance with configurable parameters', 'create a DummyDataset that generates random uint8 images of a specified size and length', 'review the ImageReadBench __enter__ method that sets up DatasetWriter, Reader, and OSCacheManager', 'test the DummyDataset __getitem__ method to verify it returns random image data for valid indices', 'summarize the benchmark decorator that parameterizes ImageReadBench with n, mode, size, and num_workers', 'run the JPEGDecodeBenchmark class to benchmark JPEG image decoding performance with configurable parameters', 'build a JPEG decode benchmark that encodes images at different qualities and measures decode speed', 'test the imdecode function from libffcv for decoding JPEG encoded image data into numpy arrays', 'review the JPEGDecodeBenchmark __enter__ method that loads resizes and encodes images for benchmarking', 'summarize the Compiler compile method used to optimize the imdecode and code functions for benchmarking', 'run the MemoryReadBytesBench benchmark to measure memory read performance for byte data', 'create a DummyDataset that returns random byte arrays with configurable length and size', 'benchmark the DatasetWriter to write a PyTorch dataset with IntField and BytesField columns', 'test the OSCacheManager to schedule and compile readers for memory-mapped data access', 'review the Compiler to compile memcpy operations for optimized memory copy performance']
```

Usage

```
{'run_memory_read_bytes_bench': 'run the MemoryReadBytesBench benchmark to measure memory read performance for byte data', 'create_dummy_dataset': 'create a DummyDataset that returns random byte arrays with configurable length and size', 'benchmark_dataset_writer': 'benchmark the DatasetWriter to write a PyTorch dataset with IntField and BytesField columns', 'test_oscache_manager': 'test the OSCacheManager to schedule and compile readers for memory-mapped data access', 'review_compiler_memcpy': 'review the Compiler to compile memcpy operations for optimized memory copy performance'}
```


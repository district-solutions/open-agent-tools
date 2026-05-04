# Agent Python Tools

- repo: facebookresearch/dietgpu
- repo_uri: https://github.com/facebookresearch/dietgpu

## File: facebookresearch_dietgpu/dietgpu/ans_test.py

Prompts

```
['run the run_test function to compress and decompress tensors verifying round-trip equality', 'test the TestANSCodec class to verify ANS codec compression and decompression with various tensor sizes', 'test the TestANSCodec test_empty method to verify compressing and decompressing empty tensors', 'test the TestANSCodec test_split_compress method to verify split-size compression then simple decompression', 'test the TestANSCodec test_split_decompress method to verify simple compression then split-size decompression', 'run the float codec compression and decompression benchmark on CUDA tensors with timing', 'run the raw ANS byte-wise compression and decompression benchmark on CUDA tensors', 'calculate the total input size, compressed size, and compression ratio from tensors and sizes', 'benchmark the float codec on a batched list of CUDA tensors across multiple runs', 'benchmark the raw ANS byte-wise codec on a single non-batched CUDA tensor', 'run the run_test function to compress and decompress float tensors on CUDA with optional temp memory', 'test the TestFloatCodec class to verify compression and decompression across bfloat16, float16, and float32 dtypes', 'test the simple compress and decompress path using compress_data_simple and decompress_data_simple ops', 'test split-size compression by compressing a single tensor split into variable-sized chunks', 'test split-size decompression by decompressing multiple compressed tensors back into a single tensor']
```

Usage

```
{'run_test_compress_decompress_roundtrip': 'run the run_test function to compress and decompress tensors verifying round-trip equality', 'test_ANSCodec_codec_roundtrip': 'test the TestANSCodec class to verify ANS codec compression and decompression with various tensor sizes', 'test_ANSCodec_empty_tensor': 'test the TestANSCodec test_empty method to verify compressing and decompressing empty tensors', 'test_ANSCodec_split_compress': 'test the TestANSCodec test_split_compress method to verify split-size compression then simple decompression', 'test_ANSCodec_split_decompress': 'test the TestANSCodec test_split_decompress method to verify simple compression then split-size decompression'}
```

## File: facebookresearch_dietgpu/dietgpu/benchmark.py

Prompts

```
['run the run_test function to compress and decompress tensors verifying round-trip equality', 'test the TestANSCodec class to verify ANS codec compression and decompression with various tensor sizes', 'test the TestANSCodec test_empty method to verify compressing and decompressing empty tensors', 'test the TestANSCodec test_split_compress method to verify split-size compression then simple decompression', 'test the TestANSCodec test_split_decompress method to verify simple compression then split-size decompression', 'run the float codec compression and decompression benchmark on CUDA tensors with timing', 'run the raw ANS byte-wise compression and decompression benchmark on CUDA tensors', 'calculate the total input size, compressed size, and compression ratio from tensors and sizes', 'benchmark the float codec on a batched list of CUDA tensors across multiple runs', 'benchmark the raw ANS byte-wise codec on a single non-batched CUDA tensor', 'run the run_test function to compress and decompress float tensors on CUDA with optional temp memory', 'test the TestFloatCodec class to verify compression and decompression across bfloat16, float16, and float32 dtypes', 'test the simple compress and decompress path using compress_data_simple and decompress_data_simple ops', 'test split-size compression by compressing a single tensor split into variable-sized chunks', 'test split-size decompression by decompressing multiple compressed tensors back into a single tensor']
```

Usage

```
{'run_float_codec_benchmark': 'run the float codec compression and decompression benchmark on CUDA tensors with timing', 'run_any_codec_benchmark': 'run the raw ANS byte-wise compression and decompression benchmark on CUDA tensors', 'calc_compression_ratio': 'calculate the total input size, compressed size, and compression ratio from tensors and sizes', 'benchmark_float_codec_batched': 'benchmark the float codec on a batched list of CUDA tensors across multiple runs', 'benchmark_any_codec_non_batched': 'benchmark the raw ANS byte-wise codec on a single non-batched CUDA tensor'}
```

## File: facebookresearch_dietgpu/dietgpu/float_test.py

Prompts

```
['run the run_test function to compress and decompress tensors verifying round-trip equality', 'test the TestANSCodec class to verify ANS codec compression and decompression with various tensor sizes', 'test the TestANSCodec test_empty method to verify compressing and decompressing empty tensors', 'test the TestANSCodec test_split_compress method to verify split-size compression then simple decompression', 'test the TestANSCodec test_split_decompress method to verify simple compression then split-size decompression', 'run the float codec compression and decompression benchmark on CUDA tensors with timing', 'run the raw ANS byte-wise compression and decompression benchmark on CUDA tensors', 'calculate the total input size, compressed size, and compression ratio from tensors and sizes', 'benchmark the float codec on a batched list of CUDA tensors across multiple runs', 'benchmark the raw ANS byte-wise codec on a single non-batched CUDA tensor', 'run the run_test function to compress and decompress float tensors on CUDA with optional temp memory', 'test the TestFloatCodec class to verify compression and decompression across bfloat16, float16, and float32 dtypes', 'test the simple compress and decompress path using compress_data_simple and decompress_data_simple ops', 'test split-size compression by compressing a single tensor split into variable-sized chunks', 'test split-size decompression by decompressing multiple compressed tensors back into a single tensor']
```

Usage

```
{'run_test_float_codec_roundtrip': 'run the run_test function to compress and decompress float tensors on CUDA with optional temp memory', 'test_codec_multiple_sizes': 'test the TestFloatCodec class to verify compression and decompression across bfloat16, float16, and float32 dtypes', 'test_simple_compress_decompress': 'test the simple compress and decompress path using compress_data_simple and decompress_data_simple ops', 'test_split_compress_tensors': 'test split-size compression by compressing a single tensor split into variable-sized chunks', 'test_split_decompress_tensors': 'test split-size decompression by decompressing multiple compressed tensors back into a single tensor'}
```


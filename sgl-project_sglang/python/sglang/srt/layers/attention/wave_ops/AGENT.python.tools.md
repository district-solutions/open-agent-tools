# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/layers/attention/wave_ops/decode_attention.py

Prompts

```
['build a cached function that compiles two-phase paged decode attention kernels with configurable MFMA variants', 'create a function that returns intermediate array shapes for paged decode attention given sequence and head dimensions', 'run the two-phase wave decode attention forward pass on query, key, and value buffers with KV splitting', 'run the high-level decode attention forward pass wrapper that invokes the two-phase wave kernel', 'test that get_wave_kernel caches compiled kernels by shape, dtype, and logit_cap parameters', 'build a memory-efficient attention kernel for prefill with page size 1 using wave runtime compilation', 'create a cached wave attention kernel from attention shape, tensor shapes, dtypes, and compilation options', 'run extend attention on q, k, v tensors with kv cache buffers and indptr indices for causal masking', 'review the conditional MLIR dump logic triggered by WAVE_DUMP_MLIR environment variable in extend_attention_wave', 'build a memory-efficient attention kernel for prefill phase with page size 1 support', 'create an AttentionShape configuration from query, key, value tensor shapes and sequence lengths', 'run the prefill attention wave kernel with qkv tensors, batch location, and sequence length inputs', 'compile a prefill attention kernel with WaveCompileOptions and default scheduling parameters', 'dump generated MLIR module to file when WAVE_DUMP_MLIR environment variable is set']
```

Usage

```
{'build_get_wave_kernel': 'build a cached function that compiles two-phase paged decode attention kernels with configurable MFMA variants', 'create_decode_attention_intermediate_arrays_shapes': 'create a function that returns intermediate array shapes for paged decode attention given sequence and head dimensions', 'run_decode_attention_wave': 'run the two-phase wave decode attention forward pass on query, key, and value buffers with KV splitting', 'run_decode_attention_fwd': 'run the high-level decode attention forward pass wrapper that invokes the two-phase wave kernel', 'test_get_wave_kernel_caching': 'test that get_wave_kernel caches compiled kernels by shape, dtype, and logit_cap parameters'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/attention/wave_ops/extend_attention.py

Prompts

```
['build a cached function that compiles two-phase paged decode attention kernels with configurable MFMA variants', 'create a function that returns intermediate array shapes for paged decode attention given sequence and head dimensions', 'run the two-phase wave decode attention forward pass on query, key, and value buffers with KV splitting', 'run the high-level decode attention forward pass wrapper that invokes the two-phase wave kernel', 'test that get_wave_kernel caches compiled kernels by shape, dtype, and logit_cap parameters', 'build a memory-efficient attention kernel for prefill with page size 1 using wave runtime compilation', 'create a cached wave attention kernel from attention shape, tensor shapes, dtypes, and compilation options', 'run extend attention on q, k, v tensors with kv cache buffers and indptr indices for causal masking', 'review the conditional MLIR dump logic triggered by WAVE_DUMP_MLIR environment variable in extend_attention_wave', 'build a memory-efficient attention kernel for prefill phase with page size 1 support', 'create an AttentionShape configuration from query, key, value tensor shapes and sequence lengths', 'run the prefill attention wave kernel with qkv tensors, batch location, and sequence length inputs', 'compile a prefill attention kernel with WaveCompileOptions and default scheduling parameters', 'dump generated MLIR module to file when WAVE_DUMP_MLIR environment variable is set']
```

Usage

```
{'build_extend_attention_wave': 'build a memory-efficient attention kernel for prefill with page size 1 using wave runtime compilation', 'create_get_wave_kernel': 'create a cached wave attention kernel from attention shape, tensor shapes, dtypes, and compilation options', 'run_extend_attention_wave': 'run extend attention on q, k, v tensors with kv cache buffers and indptr indices for causal masking', 'test_get_wave_kernel_caching': 'test the lru_cache behavior of get_wave_kernel with varying attention shapes and dtype parameters', 'review_extend_attention_wave_mlir_dump': 'review the conditional MLIR dump logic triggered by WAVE_DUMP_MLIR environment variable in extend_attention_wave'}
```

## File: sgl-project_sglang/python/sglang/srt/layers/attention/wave_ops/prefill_attention.py

Prompts

```
['build a cached function that compiles two-phase paged decode attention kernels with configurable MFMA variants', 'create a function that returns intermediate array shapes for paged decode attention given sequence and head dimensions', 'run the two-phase wave decode attention forward pass on query, key, and value buffers with KV splitting', 'run the high-level decode attention forward pass wrapper that invokes the two-phase wave kernel', 'test that get_wave_kernel caches compiled kernels by shape, dtype, and logit_cap parameters', 'build a memory-efficient attention kernel for prefill with page size 1 using wave runtime compilation', 'create a cached wave attention kernel from attention shape, tensor shapes, dtypes, and compilation options', 'run extend attention on q, k, v tensors with kv cache buffers and indptr indices for causal masking', 'review the conditional MLIR dump logic triggered by WAVE_DUMP_MLIR environment variable in extend_attention_wave', 'build a memory-efficient attention kernel for prefill phase with page size 1 support', 'create an AttentionShape configuration from query, key, value tensor shapes and sequence lengths', 'run the prefill attention wave kernel with qkv tensors, batch location, and sequence length inputs', 'compile a prefill attention kernel with WaveCompileOptions and default scheduling parameters', 'dump generated MLIR module to file when WAVE_DUMP_MLIR environment variable is set']
```

Usage

```
{'build_prefill_attention_wave': 'build a memory-efficient attention kernel for prefill phase with page size 1 support', 'create_attention_shape': 'create an AttentionShape configuration from query, key, value tensor shapes and sequence lengths', 'run_prefill_attention_kernel': 'run the prefill attention wave kernel with qkv tensors, batch location, and sequence length inputs', 'compile_wave_kernel': 'compile a prefill attention kernel with WaveCompileOptions and default scheduling parameters', 'dump_generated_mlir': 'dump generated MLIR module to file when WAVE_DUMP_MLIR environment variable is set'}
```


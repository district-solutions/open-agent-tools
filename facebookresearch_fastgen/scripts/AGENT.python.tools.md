# Agent Python Tools

- repo: facebookresearch/fastgen
- repo_uri: https://github.com/facebookresearch/fastgen

## File: facebookresearch_fastgen/scripts/bench.py

Prompts

```
['run a concurrent LLM generation benchmark measuring tokens per second across multiple parallel calls', 'find the exact padding length needed to reach a target prompt token count using binary search', 'run a decode ratio sweep benchmark and append results as JSON to a file', 'send a chat completion request to an OpenAI-compatible endpoint with custom extra body kwargs', 'create a chat message list with a padded user prompt for benchmarking token counts', 'run the rope kernel benchmark to measure throughput across various sequence lengths using CUDA graphs', 'test the apply_rope kernel against the PyTorch reference rope_pt implementation across multiple sequence lengths and head counts', 'run the PyTorch reference rope_pt function to apply rotary positional embeddings to a tensor using cosine and sine rotations', 'run the fastgen apply_rope CUDA kernel to apply rotary positional embeddings to attention tensors in-place', 'review the rope_pt function and apply_rope kernel to understand rotary positional embedding logic and performance characteristics', 'run the rope_qkv_varseq_prefill benchmark with CUDA graph replay and measure throughput in GB/s', 'run the rope_call function to apply RoPE to QKV tensors with variable sequence prefill', 'test torch.ops.fbgemm.rope_qkv_varseq_prefill with bf16 QKV tensors and KV cache on CUDA', 'profile the rope_call function using torch.profiler and export a Chrome trace to rope.json.gz', 'benchmark rope_call latency by recording a CUDA graph and replaying it 10 times with CUDA events']
```

Usage

```
{'run_benchmark': 'run a concurrent LLM generation benchmark measuring tokens per second across multiple parallel calls', 'find_pad_len': 'find the exact padding length needed to reach a target prompt token count using binary search', 'run_sweep': 'run a decode ratio sweep benchmark and append results as JSON to a file', 'complete_chat': 'send a chat completion request to an OpenAI-compatible endpoint with custom extra body kwargs', 'make_messages': 'create a chat message list with a padded user prompt for benchmarking token counts'}
```

## File: facebookresearch_fastgen/scripts/rope.py

Prompts

```
['run a concurrent LLM generation benchmark measuring tokens per second across multiple parallel calls', 'find the exact padding length needed to reach a target prompt token count using binary search', 'run a decode ratio sweep benchmark and append results as JSON to a file', 'send a chat completion request to an OpenAI-compatible endpoint with custom extra body kwargs', 'create a chat message list with a padded user prompt for benchmarking token counts', 'run the rope kernel benchmark to measure throughput across various sequence lengths using CUDA graphs', 'test the apply_rope kernel against the PyTorch reference rope_pt implementation across multiple sequence lengths and head counts', 'run the PyTorch reference rope_pt function to apply rotary positional embeddings to a tensor using cosine and sine rotations', 'run the fastgen apply_rope CUDA kernel to apply rotary positional embeddings to attention tensors in-place', 'review the rope_pt function and apply_rope kernel to understand rotary positional embedding logic and performance characteristics', 'run the rope_qkv_varseq_prefill benchmark with CUDA graph replay and measure throughput in GB/s', 'run the rope_call function to apply RoPE to QKV tensors with variable sequence prefill', 'test torch.ops.fbgemm.rope_qkv_varseq_prefill with bf16 QKV tensors and KV cache on CUDA', 'profile the rope_call function using torch.profiler and export a Chrome trace to rope.json.gz', 'benchmark rope_call latency by recording a CUDA graph and replaying it 10 times with CUDA events']
```

Usage

```
{'run_rope_benchmark': 'run the rope kernel benchmark to measure throughput across various sequence lengths using CUDA graphs', 'test_rope_correctness': 'test the apply_rope kernel against the PyTorch reference rope_pt implementation across multiple sequence lengths and head counts', 'run_rope_pt': 'run the PyTorch reference rope_pt function to apply rotary positional embeddings to a tensor using cosine and sine rotations', 'run_apply_rope_kernel': 'run the fastgen apply_rope CUDA kernel to apply rotary positional embeddings to attention tensors in-place', 'review_rope_implementation': 'review the rope_pt function and apply_rope kernel to understand rotary positional embedding logic and performance characteristics'}
```

## File: facebookresearch_fastgen/scripts/rope_test.py

Prompts

```
['run a concurrent LLM generation benchmark measuring tokens per second across multiple parallel calls', 'find the exact padding length needed to reach a target prompt token count using binary search', 'run a decode ratio sweep benchmark and append results as JSON to a file', 'send a chat completion request to an OpenAI-compatible endpoint with custom extra body kwargs', 'create a chat message list with a padded user prompt for benchmarking token counts', 'run the rope kernel benchmark to measure throughput across various sequence lengths using CUDA graphs', 'test the apply_rope kernel against the PyTorch reference rope_pt implementation across multiple sequence lengths and head counts', 'run the PyTorch reference rope_pt function to apply rotary positional embeddings to a tensor using cosine and sine rotations', 'run the fastgen apply_rope CUDA kernel to apply rotary positional embeddings to attention tensors in-place', 'review the rope_pt function and apply_rope kernel to understand rotary positional embedding logic and performance characteristics', 'run the rope_qkv_varseq_prefill benchmark with CUDA graph replay and measure throughput in GB/s', 'run the rope_call function to apply RoPE to QKV tensors with variable sequence prefill', 'test torch.ops.fbgemm.rope_qkv_varseq_prefill with bf16 QKV tensors and KV cache on CUDA', 'profile the rope_call function using torch.profiler and export a Chrome trace to rope.json.gz', 'benchmark rope_call latency by recording a CUDA graph and replaying it 10 times with CUDA events']
```

Usage

```
{'run_rope_prefill_benchmark': 'run the rope_qkv_varseq_prefill benchmark with CUDA graph replay and measure throughput in GB/s', 'run_rope_call': 'run the rope_call function to apply RoPE to QKV tensors with variable sequence prefill', 'test_rope_qkv_varseq_prefill': 'test torch.ops.fbgemm.rope_qkv_varseq_prefill with bf16 QKV tensors and KV cache on CUDA', 'profile_rope_call': 'profile the rope_call function using torch.profiler and export a Chrome trace to rope.json.gz', 'benchmark_cuda_graph_rope': 'benchmark rope_call latency by recording a CUDA graph and replaying it 10 times with CUDA events'}
```


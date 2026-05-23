# Agent Python Tools

- repo: facebookresearch/fastgen
- repo_uri: https://github.com/facebookresearch/fastgen

## File: facebookresearch_fastgen/fastgen/cache.py

Prompts

```
['build a RawCache for a Transformer model with a specified per-layer cache length and device', "build a RawCache matching another cache's shape with optional pinned host memory", 'view a slice of a RawCache along the sequence axis starting at a given offset', 'prepare a DynCacheLane from a host Cache by matching token blocks against the trie', 'maintain the host Cache by evicting least-recently-used nodes to stay within the token limit', 'run the prefill function to process prompt tokens through a transformer model and return logits', 'run the decode function to generate one token at a time using a ModelState object', 'create a ModelState object to encapsulate transformer inputs and KV caches for CUDA graph decoding', 'create a SeqInfo object from query and key sequence length lists for attention calls', 'compute the RoPE frequencies tensor for rotary positional embeddings with optional scaled rope', 'build a Fastgen instance from a BaseLoader with GenArgs, tensor parallel mesh, and CUDA device', 'generate text completions by feeding Packet objects into a queue and yielding results as a generator', 'create a GenArgs dataclass to configure sampling temperature, top_p, max batch size, and cache block settings', 'create a Packet with a thread_id, token list, optional temperature, and max_gen to submit for generation', 'request a profiling trace on the Fastgen instance and export a Chrome trace JSON to disk']
```

Usage

```
{'build_RawCache': 'build a RawCache for a Transformer model with a specified per-layer cache length and device', 'build_like_RawCache': "build a RawCache matching another cache's shape with optional pinned host memory", 'view_RawCache': 'view a slice of a RawCache along the sequence axis starting at a given offset', 'prepare_lane_Cache': 'prepare a DynCacheLane from a host Cache by matching token blocks against the trie', 'maintain_Cache': 'maintain the host Cache by evicting least-recently-used nodes to stay within the token limit'}
```

## File: facebookresearch_fastgen/fastgen/forward.py

Prompts

```
['build a RawCache for a Transformer model with a specified per-layer cache length and device', "build a RawCache matching another cache's shape with optional pinned host memory", 'view a slice of a RawCache along the sequence axis starting at a given offset', 'prepare a DynCacheLane from a host Cache by matching token blocks against the trie', 'maintain the host Cache by evicting least-recently-used nodes to stay within the token limit', 'run the prefill function to process prompt tokens through a transformer model and return logits', 'run the decode function to generate one token at a time using a ModelState object', 'create a ModelState object to encapsulate transformer inputs and KV caches for CUDA graph decoding', 'create a SeqInfo object from query and key sequence length lists for attention calls', 'compute the RoPE frequencies tensor for rotary positional embeddings with optional scaled rope', 'build a Fastgen instance from a BaseLoader with GenArgs, tensor parallel mesh, and CUDA device', 'generate text completions by feeding Packet objects into a queue and yielding results as a generator', 'create a GenArgs dataclass to configure sampling temperature, top_p, max batch size, and cache block settings', 'create a Packet with a thread_id, token list, optional temperature, and max_gen to submit for generation', 'request a profiling trace on the Fastgen instance and export a Chrome trace JSON to disk']
```

Usage

```
{'run_prefill_prompt': 'run the prefill function to process prompt tokens through a transformer model and return logits', 'run_decode_token': 'run the decode function to generate one token at a time using a ModelState object', 'create_ModelState': 'create a ModelState object to encapsulate transformer inputs and KV caches for CUDA graph decoding', 'create_SeqInfo_from_seqlen': 'create a SeqInfo object from query and key sequence length lists for attention calls', 'compute_rope_freqs': 'compute the RoPE frequencies tensor for rotary positional embeddings with optional scaled rope'}
```

## File: facebookresearch_fastgen/fastgen/generate.py

Prompts

```
['build a RawCache for a Transformer model with a specified per-layer cache length and device', "build a RawCache matching another cache's shape with optional pinned host memory", 'view a slice of a RawCache along the sequence axis starting at a given offset', 'prepare a DynCacheLane from a host Cache by matching token blocks against the trie', 'maintain the host Cache by evicting least-recently-used nodes to stay within the token limit', 'run the prefill function to process prompt tokens through a transformer model and return logits', 'run the decode function to generate one token at a time using a ModelState object', 'create a ModelState object to encapsulate transformer inputs and KV caches for CUDA graph decoding', 'create a SeqInfo object from query and key sequence length lists for attention calls', 'compute the RoPE frequencies tensor for rotary positional embeddings with optional scaled rope', 'build a Fastgen instance from a BaseLoader with GenArgs, tensor parallel mesh, and CUDA device', 'generate text completions by feeding Packet objects into a queue and yielding results as a generator', 'create a GenArgs dataclass to configure sampling temperature, top_p, max batch size, and cache block settings', 'create a Packet with a thread_id, token list, optional temperature, and max_gen to submit for generation', 'request a profiling trace on the Fastgen instance and export a Chrome trace JSON to disk']
```

Usage

```
{'build_Fastgen_from_loader': 'build a Fastgen instance from a BaseLoader with GenArgs, tensor parallel mesh, and CUDA device', 'generate_completions_from_queue': 'generate text completions by feeding Packet objects into a queue and yielding results as a generator', 'create_GenArgs_config': 'create a GenArgs dataclass to configure sampling temperature, top_p, max batch size, and cache block settings', 'create_Packet_for_generation': 'create a Packet with a thread_id, token list, optional temperature, and max_gen to submit for generation', 'request_profiling_trace': 'request a profiling trace on the Fastgen instance and export a Chrome trace JSON to disk'}
```


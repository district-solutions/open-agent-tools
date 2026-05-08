# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/fastgen/api.py

Prompts

```
['create a Packet dataclass instance with thread_id, tokens, temperature, and max_gen fields', 'implement a subclass of GenAPI that overrides the generate method to process queued Packet requests', 'queue Packet objects into a Queue and pass it to GenAPI generate for concurrent LLM completion', 'configure a Packet with temperature, top_p, and stop_str to control LLM sampling behavior', 'call update_model on a GenAPI instance after in-place weight tensor updates', 'run the prefill function to process prompt tokens through a Transformer model and return logits', 'run the decode function to generate one token using a ModelState with cached KV state', 'create a ModelState object to encapsulate tokens, block tables, and cache for CUDA graph decoding', 'run update_model to precompute and gather MLA attention weights across tensor parallel ranks', 'run rope_freqs to precompute the RoPE frequency tensor for a Transformer model with scaled rope support', 'build a FastGen generator with GenArgs, model, tokenizer, and CUDA graph decoding for batched text generation', 'create a GenArgs dataclass to configure sampling temperature, top_p, max_batch, cache_block, and prefill bounds', 'run the FastGen generate method with a queue of api.Packet objects to yield generated text packets', 'create a Lane from an api.Packet using Lane.from_pkt with max_seq and max_gen parameters', 'request a profiling trace on the FastGen generator by calling request_profile or sending SIGUSR2 signal']
```

Usage

```
{'create_packet_for_llm_request': 'create a Packet dataclass instance with thread_id, tokens, temperature, and max_gen fields', 'implement_genapi_subclass': 'implement a subclass of GenAPI that overrides the generate method to process queued Packet requests', 'queue_packets_for_concurrent_generation': 'queue Packet objects into a Queue and pass it to GenAPI generate for concurrent LLM completion', 'configure_sampling_on_packet': 'configure a Packet with temperature, top_p, and stop_str to control LLM sampling behavior', 'call_update_model_after_weights_change': 'call update_model on a GenAPI instance after in-place weight tensor updates'}
```

## File: facebookresearch_cwm/cwm/fastgen/forward.py

Prompts

```
['create a Packet dataclass instance with thread_id, tokens, temperature, and max_gen fields', 'implement a subclass of GenAPI that overrides the generate method to process queued Packet requests', 'queue Packet objects into a Queue and pass it to GenAPI generate for concurrent LLM completion', 'configure a Packet with temperature, top_p, and stop_str to control LLM sampling behavior', 'call update_model on a GenAPI instance after in-place weight tensor updates', 'run the prefill function to process prompt tokens through a Transformer model and return logits', 'run the decode function to generate one token using a ModelState with cached KV state', 'create a ModelState object to encapsulate tokens, block tables, and cache for CUDA graph decoding', 'run update_model to precompute and gather MLA attention weights across tensor parallel ranks', 'run rope_freqs to precompute the RoPE frequency tensor for a Transformer model with scaled rope support', 'build a FastGen generator with GenArgs, model, tokenizer, and CUDA graph decoding for batched text generation', 'create a GenArgs dataclass to configure sampling temperature, top_p, max_batch, cache_block, and prefill bounds', 'run the FastGen generate method with a queue of api.Packet objects to yield generated text packets', 'create a Lane from an api.Packet using Lane.from_pkt with max_seq and max_gen parameters', 'request a profiling trace on the FastGen generator by calling request_profile or sending SIGUSR2 signal']
```

Usage

```
{'run_prefill_prompt_processing': 'run the prefill function to process prompt tokens through a Transformer model and return logits', 'run_decode_single_token': 'run the decode function to generate one token using a ModelState with cached KV state', 'create_modelstate_for_decoding': 'create a ModelState object to encapsulate tokens, block tables, and cache for CUDA graph decoding', 'update_model_mla_weights': 'run update_model to precompute and gather MLA attention weights across tensor parallel ranks', 'compute_rope_frequencies': 'run rope_freqs to precompute the RoPE frequency tensor for a Transformer model with scaled rope support'}
```

## File: facebookresearch_cwm/cwm/fastgen/generate.py

Prompts

```
['create a Packet dataclass instance with thread_id, tokens, temperature, and max_gen fields', 'implement a subclass of GenAPI that overrides the generate method to process queued Packet requests', 'queue Packet objects into a Queue and pass it to GenAPI generate for concurrent LLM completion', 'configure a Packet with temperature, top_p, and stop_str to control LLM sampling behavior', 'call update_model on a GenAPI instance after in-place weight tensor updates', 'run the prefill function to process prompt tokens through a Transformer model and return logits', 'run the decode function to generate one token using a ModelState with cached KV state', 'create a ModelState object to encapsulate tokens, block tables, and cache for CUDA graph decoding', 'run update_model to precompute and gather MLA attention weights across tensor parallel ranks', 'run rope_freqs to precompute the RoPE frequency tensor for a Transformer model with scaled rope support', 'build a FastGen generator with GenArgs, model, tokenizer, and CUDA graph decoding for batched text generation', 'create a GenArgs dataclass to configure sampling temperature, top_p, max_batch, cache_block, and prefill bounds', 'run the FastGen generate method with a queue of api.Packet objects to yield generated text packets', 'create a Lane from an api.Packet using Lane.from_pkt with max_seq and max_gen parameters', 'request a profiling trace on the FastGen generator by calling request_profile or sending SIGUSR2 signal']
```

Usage

```
{'build_fastgen_generator': 'build a FastGen generator with GenArgs, model, tokenizer, and CUDA graph decoding for batched text generation', 'create_genargs_config': 'create a GenArgs dataclass to configure sampling temperature, top_p, max_batch, cache_block, and prefill bounds', 'run_generate_loop': 'run the FastGen generate method with a queue of api.Packet objects to yield generated text packets', 'create_lane_from_packet': 'create a Lane from an api.Packet using Lane.from_pkt with max_seq and max_gen parameters', 'request_profiling_trace': 'request a profiling trace on the FastGen generator by calling request_profile or sending SIGUSR2 signal'}
```


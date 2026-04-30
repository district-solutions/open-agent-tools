# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/worker/gpu/mm/encoder_cache.py

Prompts

```
['create an EncoderCache instance to store multi-modal features and encoder outputs for vLLM GPU inference', 'build an EncoderCache and add a request with a request ID and list of multi-modal feature specs', 'test removing a request from the EncoderCache multi-modal features dictionary by request ID', 'refactor the EncoderCache to reset and clear GPU-side encoder outputs when model weights are updated', 'review the EncoderCache method that frees a specific encoder output entry by multi-modal hash', 'build an EncoderRunner instance to manage multimodal encoder inference with GPU caching', 'create multimodal input kwargs from scheduled encoder inputs using the encoder cache', 'run the multimodal encoder to produce tensor outputs from batched multimodal kwargs', 'gather multimodal embeddings from the encoder cache for scheduled prefill tokens', 'create input embeddings by combining input IDs with multimodal embeddings for model forwarding', 'create a RopeState instance for multi-dimensional RoPE variants with configurable dims and device', 'init prefill positions for a request using model-specific M-RoPE or XD-RoPE position computation', 'apply staged prefill position writes and copy delta values to UVA memory', 'get a slice of the positions tensor for a given number of tokens', 'get a RopeState for a model config that uses M-RoPE or XD-RoPE']
```

Usage

```
{'create_EncoderCache': 'create an EncoderCache instance to store multi-modal features and encoder outputs for vLLM GPU inference', 'build_add_request': 'build an EncoderCache and add a request with a request ID and list of multi-modal feature specs', 'test_remove_request': 'test removing a request from the EncoderCache multi-modal features dictionary by request ID', 'refactor_reset_encoder_cache': 'refactor the EncoderCache to reset and clear GPU-side encoder outputs when model weights are updated', 'review_free_encoder_cache': 'review the EncoderCache method that frees a specific encoder output entry by multi-modal hash'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/mm/encoder_runner.py

Prompts

```
['create an EncoderCache instance to store multi-modal features and encoder outputs for vLLM GPU inference', 'build an EncoderCache and add a request with a request ID and list of multi-modal feature specs', 'test removing a request from the EncoderCache multi-modal features dictionary by request ID', 'refactor the EncoderCache to reset and clear GPU-side encoder outputs when model weights are updated', 'review the EncoderCache method that frees a specific encoder output entry by multi-modal hash', 'build an EncoderRunner instance to manage multimodal encoder inference with GPU caching', 'create multimodal input kwargs from scheduled encoder inputs using the encoder cache', 'run the multimodal encoder to produce tensor outputs from batched multimodal kwargs', 'gather multimodal embeddings from the encoder cache for scheduled prefill tokens', 'create input embeddings by combining input IDs with multimodal embeddings for model forwarding', 'create a RopeState instance for multi-dimensional RoPE variants with configurable dims and device', 'init prefill positions for a request using model-specific M-RoPE or XD-RoPE position computation', 'apply staged prefill position writes and copy delta values to UVA memory', 'get a slice of the positions tensor for a given number of tokens', 'get a RopeState for a model config that uses M-RoPE or XD-RoPE']
```

Usage

```
{'build_encoder_runner': 'build an EncoderRunner instance to manage multimodal encoder inference with GPU caching', 'create_prepare_mm_inputs': 'create multimodal input kwargs from scheduled encoder inputs using the encoder cache', 'run_execute_mm_encoder': 'run the multimodal encoder to produce tensor outputs from batched multimodal kwargs', 'gather_mm_embeddings': 'gather multimodal embeddings from the encoder cache for scheduled prefill tokens', 'create_get_inputs_embeds': 'create input embeddings by combining input IDs with multimodal embeddings for model forwarding'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/mm/rope.py

Prompts

```
['create an EncoderCache instance to store multi-modal features and encoder outputs for vLLM GPU inference', 'build an EncoderCache and add a request with a request ID and list of multi-modal feature specs', 'test removing a request from the EncoderCache multi-modal features dictionary by request ID', 'refactor the EncoderCache to reset and clear GPU-side encoder outputs when model weights are updated', 'review the EncoderCache method that frees a specific encoder output entry by multi-modal hash', 'build an EncoderRunner instance to manage multimodal encoder inference with GPU caching', 'create multimodal input kwargs from scheduled encoder inputs using the encoder cache', 'run the multimodal encoder to produce tensor outputs from batched multimodal kwargs', 'gather multimodal embeddings from the encoder cache for scheduled prefill tokens', 'create input embeddings by combining input IDs with multimodal embeddings for model forwarding', 'create a RopeState instance for multi-dimensional RoPE variants with configurable dims and device', 'init prefill positions for a request using model-specific M-RoPE or XD-RoPE position computation', 'apply staged prefill position writes and copy delta values to UVA memory', 'get a slice of the positions tensor for a given number of tokens', 'get a RopeState for a model config that uses M-RoPE or XD-RoPE']
```

Usage

```
{'create_rope_state': 'create a RopeState instance for multi-dimensional RoPE variants with configurable dims and device', 'init_prefill_positions': 'init prefill positions for a request using model-specific M-RoPE or XD-RoPE position computation', 'apply_staged_writes': 'apply staged prefill position writes and copy delta values to UVA memory', 'get_positions': 'get a slice of the positions tensor for a given number of tokens', 'get_rope_state': 'get a RopeState for a model config that uses M-RoPE or XD-RoPE'}
```


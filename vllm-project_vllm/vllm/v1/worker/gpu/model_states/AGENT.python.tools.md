# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/worker/gpu/model_states/default.py

Prompts

```
['create a DefaultModelState instance with vllm_config, model, encoder_cache, and device', 'get the supported generation tasks (generate, transcription, realtime) for the model', 'add a new request by initializing prefill positions for the request index and new request data', 'get multimodal embeddings by executing the encoder and gathering embeddings for the input batch', 'prepare attention metadata from input batch, block tables, slot mappings, and kv cache config', 'build a concrete subclass of the abstract ModelState class to manage GPU model state for vLLM inference', 'test the prepare_inputs method that prepares input tensors from an InputBatch and RequestState for model execution', 'review the get_mm_embeddings method that retrieves multimodal embeddings for scheduled encoder inputs', 'summarize the prepare_attn method that builds attention inputs including block tables, slot mappings, and attention groups', 'create a prepare_dummy_inputs method that generates dummy input dictionaries for benchmarking with given request and token counts', 'create a WhisperModelState instance with vllm_config, model, encoder_cache, and device', 'build multimodal encoder embeddings from scheduled encoder inputs and input batch', 'review prepare_attn to build attention metadata with cross-attention encoder sequence lengths', 'summarize get_supported_generation_tasks which returns the tuple of supported generation tasks']
```

Usage

```
{'create_default_model_state': 'create a DefaultModelState instance with vllm_config, model, encoder_cache, and device', 'get_supported_generation_tasks': 'get the supported generation tasks (generate, transcription, realtime) for the model', 'add_request': 'add a new request by initializing prefill positions for the request index and new request data', 'get_mm_embeddings': 'get multimodal embeddings by executing the encoder and gathering embeddings for the input batch', 'prepare_attn': 'prepare attention metadata from input batch, block tables, slot mappings, and kv cache config'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/model_states/interface.py

Prompts

```
['create a DefaultModelState instance with vllm_config, model, encoder_cache, and device', 'get the supported generation tasks (generate, transcription, realtime) for the model', 'add a new request by initializing prefill positions for the request index and new request data', 'get multimodal embeddings by executing the encoder and gathering embeddings for the input batch', 'prepare attention metadata from input batch, block tables, slot mappings, and kv cache config', 'build a concrete subclass of the abstract ModelState class to manage GPU model state for vLLM inference', 'test the prepare_inputs method that prepares input tensors from an InputBatch and RequestState for model execution', 'review the get_mm_embeddings method that retrieves multimodal embeddings for scheduled encoder inputs', 'summarize the prepare_attn method that builds attention inputs including block tables, slot mappings, and attention groups', 'create a prepare_dummy_inputs method that generates dummy input dictionaries for benchmarking with given request and token counts', 'create a WhisperModelState instance with vllm_config, model, encoder_cache, and device', 'build multimodal encoder embeddings from scheduled encoder inputs and input batch', 'review prepare_attn to build attention metadata with cross-attention encoder sequence lengths', 'summarize get_supported_generation_tasks which returns the tuple of supported generation tasks']
```

Usage

```
{'build_ModelState': 'build a concrete subclass of the abstract ModelState class to manage GPU model state for vLLM inference', 'test_prepare_inputs': 'test the prepare_inputs method that prepares input tensors from an InputBatch and RequestState for model execution', 'review_get_mm_embeddings': 'review the get_mm_embeddings method that retrieves multimodal embeddings for scheduled encoder inputs', 'summarize_prepare_attn': 'summarize the prepare_attn method that builds attention inputs including block tables, slot mappings, and attention groups', 'create_prepare_dummy_inputs': 'create a prepare_dummy_inputs method that generates dummy input dictionaries for benchmarking with given request and token counts'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/model_states/whisper.py

Prompts

```
['create a DefaultModelState instance with vllm_config, model, encoder_cache, and device', 'get the supported generation tasks (generate, transcription, realtime) for the model', 'add a new request by initializing prefill positions for the request index and new request data', 'get multimodal embeddings by executing the encoder and gathering embeddings for the input batch', 'prepare attention metadata from input batch, block tables, slot mappings, and kv cache config', 'build a concrete subclass of the abstract ModelState class to manage GPU model state for vLLM inference', 'test the prepare_inputs method that prepares input tensors from an InputBatch and RequestState for model execution', 'review the get_mm_embeddings method that retrieves multimodal embeddings for scheduled encoder inputs', 'summarize the prepare_attn method that builds attention inputs including block tables, slot mappings, and attention groups', 'create a prepare_dummy_inputs method that generates dummy input dictionaries for benchmarking with given request and token counts', 'create a WhisperModelState instance with vllm_config, model, encoder_cache, and device', 'build multimodal encoder embeddings from scheduled encoder inputs and input batch', 'review prepare_attn to build attention metadata with cross-attention encoder sequence lengths', 'summarize get_supported_generation_tasks which returns the tuple of supported generation tasks']
```

Usage

```
{'create_WhisperModelState': 'create a WhisperModelState instance with vllm_config, model, encoder_cache, and device', 'build_get_mm_embeddings': 'build multimodal encoder embeddings from scheduled encoder inputs and input batch', 'test_prepare_inputs': 'test prepare_inputs to generate model inputs containing encoder outputs for the decoder', 'review_prepare_attn': 'review prepare_attn to build attention metadata with cross-attention encoder sequence lengths', 'summarize_get_supported_generation_tasks': 'summarize get_supported_generation_tasks which returns the tuple of supported generation tasks'}
```


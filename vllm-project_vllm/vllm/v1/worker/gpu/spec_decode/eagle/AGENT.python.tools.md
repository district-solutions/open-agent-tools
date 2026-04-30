# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/worker/gpu/spec_decode/eagle/cudagraph.py

Prompts

```
['create an EagleCudaGraphManager instance for Eagle speculative decoding with vllm_config, device, cudagraph_mode, and decode_query_len', 'run CUDA graph capture for Eagle speculative decoding using forward_fn, model_state, input_buffers, block_tables, attn_groups, and kv_cache_config', "build a dedicated CUDA graph pool for Eagle to avoid memory overlap with the main model's cudagraph allocations", 'test prepare_inputs_to_capture to generate attn_metadata and slot_mappings for Eagle CUDA graph capture', 'refactor the create_forward_fn closure to wrap forward_fn with num_reqs, num_tokens, attn_metadata, slot_mappings, and num_tokens_across_dp', 'run set_eagle3_aux_hidden_state_layers to configure EAGLE3 auxiliary hidden state layers on a model with speculative config', "build a call to get_eagle3_aux_layers_from_config to extract auxiliary layer IDs from a speculative config's draft model hf_config", 'test get_eagle3_aux_layers_from_config returns None when spec_config or draft_model_config is missing', 'review set_eagle3_aux_hidden_state_layers raises RuntimeError when model does not support EAGLE3 interface', 'summarize the eagle3_utils module that configures EAGLE3 auxiliary hidden state layers for speculative decoding', 'create an EagleSpeculator instance for draft token generation with vLLM config and device', 'run the Eagle draft model forward pass with attention metadata and hidden states', 'propose draft tokens from the Eagle speculator given target model hidden states and attention metadata', 'capture CUDA graphs for Eagle speculator prefill and decode routines', 'update Eagle input buffers with draft tokens and output hidden states for the next generation step', 'load the EAGLE draft model and share embeddings and lm_head with the target model']
```

Usage

```
{'create_EagleCudaGraphManager': 'create an EagleCudaGraphManager instance for Eagle speculative decoding with vllm_config, device, cudagraph_mode, and decode_query_len', 'run_capture_cuda_graphs': 'run CUDA graph capture for Eagle speculative decoding using forward_fn, model_state, input_buffers, block_tables, attn_groups, and kv_cache_config', 'build_cuda_graph_manager': "build a dedicated CUDA graph pool for Eagle to avoid memory overlap with the main model's cudagraph allocations", 'test_prepare_inputs_to_capture': 'test prepare_inputs_to_capture to generate attn_metadata and slot_mappings for Eagle CUDA graph capture', 'refactor_create_forward_fn': 'refactor the create_forward_fn closure to wrap forward_fn with num_reqs, num_tokens, attn_metadata, slot_mappings, and num_tokens_across_dp'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/spec_decode/eagle/eagle3_utils.py

Prompts

```
['create an EagleCudaGraphManager instance for Eagle speculative decoding with vllm_config, device, cudagraph_mode, and decode_query_len', 'run CUDA graph capture for Eagle speculative decoding using forward_fn, model_state, input_buffers, block_tables, attn_groups, and kv_cache_config', "build a dedicated CUDA graph pool for Eagle to avoid memory overlap with the main model's cudagraph allocations", 'test prepare_inputs_to_capture to generate attn_metadata and slot_mappings for Eagle CUDA graph capture', 'refactor the create_forward_fn closure to wrap forward_fn with num_reqs, num_tokens, attn_metadata, slot_mappings, and num_tokens_across_dp', 'run set_eagle3_aux_hidden_state_layers to configure EAGLE3 auxiliary hidden state layers on a model with speculative config', "build a call to get_eagle3_aux_layers_from_config to extract auxiliary layer IDs from a speculative config's draft model hf_config", 'test get_eagle3_aux_layers_from_config returns None when spec_config or draft_model_config is missing', 'review set_eagle3_aux_hidden_state_layers raises RuntimeError when model does not support EAGLE3 interface', 'summarize the eagle3_utils module that configures EAGLE3 auxiliary hidden state layers for speculative decoding', 'create an EagleSpeculator instance for draft token generation with vLLM config and device', 'run the Eagle draft model forward pass with attention metadata and hidden states', 'propose draft tokens from the Eagle speculator given target model hidden states and attention metadata', 'capture CUDA graphs for Eagle speculator prefill and decode routines', 'update Eagle input buffers with draft tokens and output hidden states for the next generation step', 'load the EAGLE draft model and share embeddings and lm_head with the target model']
```

Usage

```
{'run_set_eagle3_aux_hidden_state_layers': 'run set_eagle3_aux_hidden_state_layers to configure EAGLE3 auxiliary hidden state layers on a model with speculative config', 'build_get_eagle3_aux_layers_from_config': "build a call to get_eagle3_aux_layers_from_config to extract auxiliary layer IDs from a speculative config's draft model hf_config", 'test_get_eagle3_aux_layers_from_config': 'test get_eagle3_aux_layers_from_config returns None when spec_config or draft_model_config is missing', 'review_set_eagle3_aux_hidden_state_layers': 'review set_eagle3_aux_hidden_state_layers raises RuntimeError when model does not support EAGLE3 interface', 'summarize_eagle3_utils': 'summarize the eagle3_utils module that configures EAGLE3 auxiliary hidden state layers for speculative decoding'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/spec_decode/eagle/speculator.py

Prompts

```
['create an EagleCudaGraphManager instance for Eagle speculative decoding with vllm_config, device, cudagraph_mode, and decode_query_len', 'run CUDA graph capture for Eagle speculative decoding using forward_fn, model_state, input_buffers, block_tables, attn_groups, and kv_cache_config', "build a dedicated CUDA graph pool for Eagle to avoid memory overlap with the main model's cudagraph allocations", 'test prepare_inputs_to_capture to generate attn_metadata and slot_mappings for Eagle CUDA graph capture', 'refactor the create_forward_fn closure to wrap forward_fn with num_reqs, num_tokens, attn_metadata, slot_mappings, and num_tokens_across_dp', 'run set_eagle3_aux_hidden_state_layers to configure EAGLE3 auxiliary hidden state layers on a model with speculative config', "build a call to get_eagle3_aux_layers_from_config to extract auxiliary layer IDs from a speculative config's draft model hf_config", 'test get_eagle3_aux_layers_from_config returns None when spec_config or draft_model_config is missing', 'review set_eagle3_aux_hidden_state_layers raises RuntimeError when model does not support EAGLE3 interface', 'summarize the eagle3_utils module that configures EAGLE3 auxiliary hidden state layers for speculative decoding', 'create an EagleSpeculator instance for draft token generation with vLLM config and device', 'run the Eagle draft model forward pass with attention metadata and hidden states', 'propose draft tokens from the Eagle speculator given target model hidden states and attention metadata', 'capture CUDA graphs for Eagle speculator prefill and decode routines', 'update Eagle input buffers with draft tokens and output hidden states for the next generation step', 'load the EAGLE draft model and share embeddings and lm_head with the target model']
```

Usage

```
{'create_EagleSpeculator': 'create an EagleSpeculator instance for draft token generation with vLLM config and device', 'run_EagleSpeculator_model': 'run the Eagle draft model forward pass with attention metadata and hidden states', 'propose_EagleSpeculator_draft_tokens': 'propose draft tokens from the Eagle speculator given target model hidden states and attention metadata', 'capture_EagleSpeculator_cuda_graphs': 'capture CUDA graphs for Eagle speculator prefill and decode routines', 'update_eagle_inputs': 'update Eagle input buffers with draft tokens and output hidden states for the next generation step'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/spec_decode/eagle/utils.py

Prompts

```
['create an EagleCudaGraphManager instance for Eagle speculative decoding with vllm_config, device, cudagraph_mode, and decode_query_len', 'run CUDA graph capture for Eagle speculative decoding using forward_fn, model_state, input_buffers, block_tables, attn_groups, and kv_cache_config', "build a dedicated CUDA graph pool for Eagle to avoid memory overlap with the main model's cudagraph allocations", 'test prepare_inputs_to_capture to generate attn_metadata and slot_mappings for Eagle CUDA graph capture', 'refactor the create_forward_fn closure to wrap forward_fn with num_reqs, num_tokens, attn_metadata, slot_mappings, and num_tokens_across_dp', 'run set_eagle3_aux_hidden_state_layers to configure EAGLE3 auxiliary hidden state layers on a model with speculative config', "build a call to get_eagle3_aux_layers_from_config to extract auxiliary layer IDs from a speculative config's draft model hf_config", 'test get_eagle3_aux_layers_from_config returns None when spec_config or draft_model_config is missing', 'review set_eagle3_aux_hidden_state_layers raises RuntimeError when model does not support EAGLE3 interface', 'summarize the eagle3_utils module that configures EAGLE3 auxiliary hidden state layers for speculative decoding', 'create an EagleSpeculator instance for draft token generation with vLLM config and device', 'run the Eagle draft model forward pass with attention metadata and hidden states', 'propose draft tokens from the Eagle speculator given target model hidden states and attention metadata', 'capture CUDA graphs for Eagle speculator prefill and decode routines', 'update Eagle input buffers with draft tokens and output hidden states for the next generation step', 'load the EAGLE draft model and share embeddings and lm_head with the target model']
```

Usage

```
{'load_eagle_model': 'load the EAGLE draft model and share embeddings and lm_head with the target model'}
```


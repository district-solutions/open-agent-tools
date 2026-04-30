# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/attention/STA_configuration.py

Prompts

```
['configure Sliding Tile Attention mask strategy using searching, tuning, or inference mode with mask candidates and layer parameters', 'read and parse JSON files containing mask search results from a specified directory', 'average L2 loss values across multiple prompts for each mask strategy', 'select the best mask strategy for each attention head based on minimum loss values', 'save mask search results with L1 and L2 losses to a JSON file', 'create a UlyssesAttention layer with distributed sequence parallelism for QKV tensors and replicated tokens', 'create a UlyssesAttention_VSA layer with vector-simulated attention and gate compression support', 'create a LocalAttention layer with optional attention masks for scaled dot-product attention', 'create a USPAttention layer combining Ulysses all-to-all communication with ring attention for sequence parallelism', 'run USPAttention with replicated prefix or suffix tokens to handle joint text-image attention across SP ranks', 'build the attention backend class for a given head size, dtype, and set of supported backends', 'create an AttentionBackendEnum from a string backend name', 'run global_force_attn_backend to force all attention operations to use a specified backend', 'test get_env_variable_attn_backend to retrieve the backend override from an environment variable', 'review global_force_attn_backend_context_manager to force a backend override within a context and revert on exit', 'build a MinimalA2AAttnOp instance with num_heads, head_size, attention_type, and topk for context-parallel sparse linear attention', 'create a DistributedAttention wrapper around a local attention module for sequence-parallel forward passes', 'run async_a2a_communicate to perform all-to-all communication on QKV tensors across context-parallel workers', 'apply _SeqAllToAll autograd function to scatter and gather tensors across sequence-parallel groups', 'apply _SeqAllToAllQKV autograd function to scatter and gather query, key, and value tensors across context-parallel workers']
```

Usage

```
{'configure_sta': 'configure Sliding Tile Attention mask strategy using searching, tuning, or inference mode with mask candidates and layer parameters', 'read_specific_json_files': 'read and parse JSON files containing mask search results from a specified directory', 'average_head_losses': 'average L2 loss values across multiple prompts for each mask strategy', 'select_best_mask_strategy': 'select the best mask strategy for each attention head based on minimum loss values', 'save_mask_search_results': 'save mask search results with L1 and L2 losses to a JSON file'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/attention/layer.py

Prompts

```
['configure Sliding Tile Attention mask strategy using searching, tuning, or inference mode with mask candidates and layer parameters', 'read and parse JSON files containing mask search results from a specified directory', 'average L2 loss values across multiple prompts for each mask strategy', 'select the best mask strategy for each attention head based on minimum loss values', 'save mask search results with L1 and L2 losses to a JSON file', 'create a UlyssesAttention layer with distributed sequence parallelism for QKV tensors and replicated tokens', 'create a UlyssesAttention_VSA layer with vector-simulated attention and gate compression support', 'create a LocalAttention layer with optional attention masks for scaled dot-product attention', 'create a USPAttention layer combining Ulysses all-to-all communication with ring attention for sequence parallelism', 'run USPAttention with replicated prefix or suffix tokens to handle joint text-image attention across SP ranks', 'build the attention backend class for a given head size, dtype, and set of supported backends', 'create an AttentionBackendEnum from a string backend name', 'run global_force_attn_backend to force all attention operations to use a specified backend', 'test get_env_variable_attn_backend to retrieve the backend override from an environment variable', 'review global_force_attn_backend_context_manager to force a backend override within a context and revert on exit', 'build a MinimalA2AAttnOp instance with num_heads, head_size, attention_type, and topk for context-parallel sparse linear attention', 'create a DistributedAttention wrapper around a local attention module for sequence-parallel forward passes', 'run async_a2a_communicate to perform all-to-all communication on QKV tensors across context-parallel workers', 'apply _SeqAllToAll autograd function to scatter and gather tensors across sequence-parallel groups', 'apply _SeqAllToAllQKV autograd function to scatter and gather query, key, and value tensors across context-parallel workers']
```

Usage

```
{'create_ulysses_attention': 'create a UlyssesAttention layer with distributed sequence parallelism for QKV tensors and replicated tokens', 'create_ulysses_attention_vsa': 'create a UlyssesAttention_VSA layer with vector-simulated attention and gate compression support', 'create_local_attention': 'create a LocalAttention layer with optional attention masks for scaled dot-product attention', 'create_usp_attention': 'create a USPAttention layer combining Ulysses all-to-all communication with ring attention for sequence parallelism', 'run_usp_attention_with_replicated_tokens': 'run USPAttention with replicated prefix or suffix tokens to handle joint text-image attention across SP ranks'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/attention/selector.py

Prompts

```
['configure Sliding Tile Attention mask strategy using searching, tuning, or inference mode with mask candidates and layer parameters', 'read and parse JSON files containing mask search results from a specified directory', 'average L2 loss values across multiple prompts for each mask strategy', 'select the best mask strategy for each attention head based on minimum loss values', 'save mask search results with L1 and L2 losses to a JSON file', 'create a UlyssesAttention layer with distributed sequence parallelism for QKV tensors and replicated tokens', 'create a UlyssesAttention_VSA layer with vector-simulated attention and gate compression support', 'create a LocalAttention layer with optional attention masks for scaled dot-product attention', 'create a USPAttention layer combining Ulysses all-to-all communication with ring attention for sequence parallelism', 'run USPAttention with replicated prefix or suffix tokens to handle joint text-image attention across SP ranks', 'build the attention backend class for a given head size, dtype, and set of supported backends', 'create an AttentionBackendEnum from a string backend name', 'run global_force_attn_backend to force all attention operations to use a specified backend', 'test get_env_variable_attn_backend to retrieve the backend override from an environment variable', 'review global_force_attn_backend_context_manager to force a backend override within a context and revert on exit', 'build a MinimalA2AAttnOp instance with num_heads, head_size, attention_type, and topk for context-parallel sparse linear attention', 'create a DistributedAttention wrapper around a local attention module for sequence-parallel forward passes', 'run async_a2a_communicate to perform all-to-all communication on QKV tensors across context-parallel workers', 'apply _SeqAllToAll autograd function to scatter and gather tensors across sequence-parallel groups', 'apply _SeqAllToAllQKV autograd function to scatter and gather query, key, and value tensors across context-parallel workers']
```

Usage

```
{'build_get_attn_backend': 'build the attention backend class for a given head size, dtype, and set of supported backends', 'create_backend_name_to_enum': 'create an AttentionBackendEnum from a string backend name', 'run_global_force_attn_backend': 'run global_force_attn_backend to force all attention operations to use a specified backend', 'test_get_env_variable_attn_backend': 'test get_env_variable_attn_backend to retrieve the backend override from an environment variable', 'review_global_force_attn_backend_context_manager': 'review global_force_attn_backend_context_manager to force a backend override within a context and revert on exit'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/layers/attention/turbo_layer.py

Prompts

```
['configure Sliding Tile Attention mask strategy using searching, tuning, or inference mode with mask candidates and layer parameters', 'read and parse JSON files containing mask search results from a specified directory', 'average L2 loss values across multiple prompts for each mask strategy', 'select the best mask strategy for each attention head based on minimum loss values', 'save mask search results with L1 and L2 losses to a JSON file', 'create a UlyssesAttention layer with distributed sequence parallelism for QKV tensors and replicated tokens', 'create a UlyssesAttention_VSA layer with vector-simulated attention and gate compression support', 'create a LocalAttention layer with optional attention masks for scaled dot-product attention', 'create a USPAttention layer combining Ulysses all-to-all communication with ring attention for sequence parallelism', 'run USPAttention with replicated prefix or suffix tokens to handle joint text-image attention across SP ranks', 'build the attention backend class for a given head size, dtype, and set of supported backends', 'create an AttentionBackendEnum from a string backend name', 'run global_force_attn_backend to force all attention operations to use a specified backend', 'test get_env_variable_attn_backend to retrieve the backend override from an environment variable', 'review global_force_attn_backend_context_manager to force a backend override within a context and revert on exit', 'build a MinimalA2AAttnOp instance with num_heads, head_size, attention_type, and topk for context-parallel sparse linear attention', 'create a DistributedAttention wrapper around a local attention module for sequence-parallel forward passes', 'run async_a2a_communicate to perform all-to-all communication on QKV tensors across context-parallel workers', 'apply _SeqAllToAll autograd function to scatter and gather tensors across sequence-parallel groups', 'apply _SeqAllToAllQKV autograd function to scatter and gather query, key, and value tensors across context-parallel workers']
```

Usage

```
{'build_minimal_a2a_attn_op': 'build a MinimalA2AAttnOp instance with num_heads, head_size, attention_type, and topk for context-parallel sparse linear attention', 'create_distributed_attention': 'create a DistributedAttention wrapper around a local attention module for sequence-parallel forward passes', 'run_async_a2a_communicate': 'run async_a2a_communicate to perform all-to-all communication on QKV tensors across context-parallel workers', 'apply_seq_all_to_all': 'apply _SeqAllToAll autograd function to scatter and gather tensors across sequence-parallel groups', 'apply_seq_all_to_all_qkv': 'apply _SeqAllToAllQKV autograd function to scatter and gather query, key, and value tensors across context-parallel workers'}
```


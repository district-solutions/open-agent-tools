# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/disaggregation/common/conn.py

Prompts

```
['build a CommonKVManager to coordinate KV cache transfer between prefill and decode stages in disaggregated inference', 'create a CommonKVSender to send KV cache indices from a prefill rank to a decode rank over ZMQ', 'create a CommonKVReceiver to receive KV cache data from prefill ranks on the decode side', 'build a CommonKVBootstrapServer HTTP service that tracks prefill server registration and routes bootstrap queries', 'test the _resolve_rank_mapping method to compute TP/CP/PP rank mappings for disaggregated KV transfer', 'create a pre-allocated GPU staging buffer for bulk KV cache transfer on a specified device', 'build a decode-side dynamic staging ring buffer allocator with overcommit for managing allocation regions', "gather all layers' K and V head slices from scattered pages into a contiguous staging buffer", 'scatter data from a contiguous staging region into KV cache buffers on the decode side', 'compute head slicing parameters for heterogeneous tensor parallel KV cache transfer between ranks', 'create a DecodeStagingHandler instance using the factory method with kv_manager, scheduler, and tp_rank', 'submit chunk scatter operations for decode requests on the staging allocator scatter stream', 'check CUDA events and free completed staging allocations for a decode request', 'allocate staging buffer memory on demand when a prefill sends STAGING_REQ messages', 'send STAGING_REQ messages for all chunks before prefill forward pass begins', 'test the FastQueue class for thread-safe put and get operations', 'review the FastQueue.put method for thread-safety using a condition variable', 'review the FastQueue.get method for blocking until items are available', 'build a function that groups contiguous src and dst index pairs using NumPy', 'summarize the group_concurrent_contiguous function that splits index arrays into contiguous groups']
```

Usage

```
{'build_kvmanager': 'build a CommonKVManager to coordinate KV cache transfer between prefill and decode stages in disaggregated inference', 'create_kvsender': 'create a CommonKVSender to send KV cache indices from a prefill rank to a decode rank over ZMQ', 'create_kvreceiver': 'create a CommonKVReceiver to receive KV cache data from prefill ranks on the decode side', 'build_bootstrap_server': 'build a CommonKVBootstrapServer HTTP service that tracks prefill server registration and routes bootstrap queries', 'test_rank_mapping': 'test the _resolve_rank_mapping method to compute TP/CP/PP rank mappings for disaggregated KV transfer'}
```

## File: sgl-project_sglang/python/sglang/srt/disaggregation/common/staging_buffer.py

Prompts

```
['build a CommonKVManager to coordinate KV cache transfer between prefill and decode stages in disaggregated inference', 'create a CommonKVSender to send KV cache indices from a prefill rank to a decode rank over ZMQ', 'create a CommonKVReceiver to receive KV cache data from prefill ranks on the decode side', 'build a CommonKVBootstrapServer HTTP service that tracks prefill server registration and routes bootstrap queries', 'test the _resolve_rank_mapping method to compute TP/CP/PP rank mappings for disaggregated KV transfer', 'create a pre-allocated GPU staging buffer for bulk KV cache transfer on a specified device', 'build a decode-side dynamic staging ring buffer allocator with overcommit for managing allocation regions', "gather all layers' K and V head slices from scattered pages into a contiguous staging buffer", 'scatter data from a contiguous staging region into KV cache buffers on the decode side', 'compute head slicing parameters for heterogeneous tensor parallel KV cache transfer between ranks', 'create a DecodeStagingHandler instance using the factory method with kv_manager, scheduler, and tp_rank', 'submit chunk scatter operations for decode requests on the staging allocator scatter stream', 'check CUDA events and free completed staging allocations for a decode request', 'allocate staging buffer memory on demand when a prefill sends STAGING_REQ messages', 'send STAGING_REQ messages for all chunks before prefill forward pass begins', 'test the FastQueue class for thread-safe put and get operations', 'review the FastQueue.put method for thread-safety using a condition variable', 'review the FastQueue.get method for blocking until items are available', 'build a function that groups contiguous src and dst index pairs using NumPy', 'summarize the group_concurrent_contiguous function that splits index arrays into contiguous groups']
```

Usage

```
{'create_StagingBuffer': 'create a pre-allocated GPU staging buffer for bulk KV cache transfer on a specified device', 'build_StagingAllocator': 'build a decode-side dynamic staging ring buffer allocator with overcommit for managing allocation regions', 'gather_all_layers_to_staging': "gather all layers' K and V head slices from scattered pages into a contiguous staging buffer", 'scatter_staging_to_kv': 'scatter data from a contiguous staging region into KV cache buffers on the decode side', 'compute_head_slice_params': 'compute head slicing parameters for heterogeneous tensor parallel KV cache transfer between ranks'}
```

## File: sgl-project_sglang/python/sglang/srt/disaggregation/common/staging_handler.py

Prompts

```
['build a CommonKVManager to coordinate KV cache transfer between prefill and decode stages in disaggregated inference', 'create a CommonKVSender to send KV cache indices from a prefill rank to a decode rank over ZMQ', 'create a CommonKVReceiver to receive KV cache data from prefill ranks on the decode side', 'build a CommonKVBootstrapServer HTTP service that tracks prefill server registration and routes bootstrap queries', 'test the _resolve_rank_mapping method to compute TP/CP/PP rank mappings for disaggregated KV transfer', 'create a pre-allocated GPU staging buffer for bulk KV cache transfer on a specified device', 'build a decode-side dynamic staging ring buffer allocator with overcommit for managing allocation regions', "gather all layers' K and V head slices from scattered pages into a contiguous staging buffer", 'scatter data from a contiguous staging region into KV cache buffers on the decode side', 'compute head slicing parameters for heterogeneous tensor parallel KV cache transfer between ranks', 'create a DecodeStagingHandler instance using the factory method with kv_manager, scheduler, and tp_rank', 'submit chunk scatter operations for decode requests on the staging allocator scatter stream', 'check CUDA events and free completed staging allocations for a decode request', 'allocate staging buffer memory on demand when a prefill sends STAGING_REQ messages', 'send STAGING_REQ messages for all chunks before prefill forward pass begins', 'test the FastQueue class for thread-safe put and get operations', 'review the FastQueue.put method for thread-safety using a condition variable', 'review the FastQueue.get method for blocking until items are available', 'build a function that groups contiguous src and dst index pairs using NumPy', 'summarize the group_concurrent_contiguous function that splits index arrays into contiguous groups']
```

Usage

```
{'create_DecodeStagingHandler': 'create a DecodeStagingHandler instance using the factory method with kv_manager, scheduler, and tp_rank', 'submit_scatter_chunks': 'submit chunk scatter operations for decode requests on the staging allocator scatter stream', 'check_staging_completion': 'check CUDA events and free completed staging allocations for a decode request', 'allocate_staging_on_demand': 'allocate staging buffer memory on demand when a prefill sends STAGING_REQ messages', 'prefetch_staging_requests': 'send STAGING_REQ messages for all chunks before prefill forward pass begins'}
```

## File: sgl-project_sglang/python/sglang/srt/disaggregation/common/utils.py

Prompts

```
['build a CommonKVManager to coordinate KV cache transfer between prefill and decode stages in disaggregated inference', 'create a CommonKVSender to send KV cache indices from a prefill rank to a decode rank over ZMQ', 'create a CommonKVReceiver to receive KV cache data from prefill ranks on the decode side', 'build a CommonKVBootstrapServer HTTP service that tracks prefill server registration and routes bootstrap queries', 'test the _resolve_rank_mapping method to compute TP/CP/PP rank mappings for disaggregated KV transfer', 'create a pre-allocated GPU staging buffer for bulk KV cache transfer on a specified device', 'build a decode-side dynamic staging ring buffer allocator with overcommit for managing allocation regions', "gather all layers' K and V head slices from scattered pages into a contiguous staging buffer", 'scatter data from a contiguous staging region into KV cache buffers on the decode side', 'compute head slicing parameters for heterogeneous tensor parallel KV cache transfer between ranks', 'create a DecodeStagingHandler instance using the factory method with kv_manager, scheduler, and tp_rank', 'submit chunk scatter operations for decode requests on the staging allocator scatter stream', 'check CUDA events and free completed staging allocations for a decode request', 'allocate staging buffer memory on demand when a prefill sends STAGING_REQ messages', 'send STAGING_REQ messages for all chunks before prefill forward pass begins', 'test the FastQueue class for thread-safe put and get operations', 'review the FastQueue.put method for thread-safety using a condition variable', 'review the FastQueue.get method for blocking until items are available', 'build a function that groups contiguous src and dst index pairs using NumPy', 'summarize the group_concurrent_contiguous function that splits index arrays into contiguous groups']
```

Usage

```
{'test_FastQueue': 'test the FastQueue class for thread-safe put and get operations', 'review_FastQueue_put': 'review the FastQueue.put method for thread-safety using a condition variable', 'review_FastQueue_get': 'review the FastQueue.get method for blocking until items are available', 'build_group_concurrent_contiguous': 'build a function that groups contiguous src and dst index pairs using NumPy', 'summarize_group_concurrent_contiguous': 'summarize the group_concurrent_contiguous function that splits index arrays into contiguous groups'}
```


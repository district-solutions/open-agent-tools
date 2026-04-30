# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/disaggregation/mooncake/conn.py

Prompts

```
['create a MooncakeKVManager instance to handle KV cache transfer between prefill and decode stages', 'build a MooncakeKVSender to send KV cache chunks from prefill rank to decode rank', 'build a MooncakeKVReceiver to receive KV cache chunks from prefill rank at decode stage', 'test the transfer_worker method that processes KV cache chunks from the transfer queue', 'review the send_kvcache_staged method that transfers KV cache via staging buffers with bulk RDMA', 'test the init_mooncake_custom_mem_pool function to initialize a custom memory pool on a CUDA device', 'test the check_mooncake_custom_mem_pool_enabled function to verify if custom memory pool is enabled', 'run init_mooncake_custom_mem_pool with a device string to create a torch.cuda.MemPool using NVLink or Barex allocator', 'review the init_mooncake_custom_mem_pool function for error handling and fallback to default memory pool', 'summarize the check_mooncake_custom_mem_pool_enabled function that reads envs.SGLANG_MOONCAKE_CUSTOM_MEM_POOL and validates against supported types']
```

Usage

```
{'create_MooncakeKVManager': 'create a MooncakeKVManager instance to handle KV cache transfer between prefill and decode stages', 'build_MooncakeKVSender': 'build a MooncakeKVSender to send KV cache chunks from prefill rank to decode rank', 'build_MooncakeKVReceiver': 'build a MooncakeKVReceiver to receive KV cache chunks from prefill rank at decode stage', 'test_transfer_worker': 'test the transfer_worker method that processes KV cache chunks from the transfer queue', 'review_MooncakeKVManager_send_kvcache_staged': 'review the send_kvcache_staged method that transfers KV cache via staging buffers with bulk RDMA'}
```

## File: sgl-project_sglang/python/sglang/srt/disaggregation/mooncake/utils.py

Prompts

```
['create a MooncakeKVManager instance to handle KV cache transfer between prefill and decode stages', 'build a MooncakeKVSender to send KV cache chunks from prefill rank to decode rank', 'build a MooncakeKVReceiver to receive KV cache chunks from prefill rank at decode stage', 'test the transfer_worker method that processes KV cache chunks from the transfer queue', 'review the send_kvcache_staged method that transfers KV cache via staging buffers with bulk RDMA', 'test the init_mooncake_custom_mem_pool function to initialize a custom memory pool on a CUDA device', 'test the check_mooncake_custom_mem_pool_enabled function to verify if custom memory pool is enabled', 'run init_mooncake_custom_mem_pool with a device string to create a torch.cuda.MemPool using NVLink or Barex allocator', 'review the init_mooncake_custom_mem_pool function for error handling and fallback to default memory pool', 'summarize the check_mooncake_custom_mem_pool_enabled function that reads envs.SGLANG_MOONCAKE_CUSTOM_MEM_POOL and validates against supported types']
```

Usage

```
{'test_init_mooncake_custom_mem_pool': 'test the init_mooncake_custom_mem_pool function to initialize a custom memory pool on a CUDA device', 'test_check_mooncake_custom_mem_pool_enabled': 'test the check_mooncake_custom_mem_pool_enabled function to verify if custom memory pool is enabled', 'run_init_mooncake_custom_mem_pool': 'run init_mooncake_custom_mem_pool with a device string to create a torch.cuda.MemPool using NVLink or Barex allocator', 'review_init_mooncake_custom_mem_pool': 'review the init_mooncake_custom_mem_pool function for error handling and fallback to default memory pool', 'summarize_check_mooncake_custom_mem_pool_enabled': 'summarize the check_mooncake_custom_mem_pool_enabled function that reads envs.SGLANG_MOONCAKE_CUSTOM_MEM_POOL and validates against supported types'}
```


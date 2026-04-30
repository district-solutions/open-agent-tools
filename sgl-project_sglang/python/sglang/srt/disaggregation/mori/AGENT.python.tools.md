# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/disaggregation/mori/conn.py

Prompts

```
['build a MoriKVManager instance to initialize an RDMA-based KV cache transfer engine for SGLang disaggregation', 'create a MoriKVSender to send KV cache chunks from a prefill rank to decode ranks over RDMA', 'create a MoriKVReceiver to receive KV cache data from prefill ranks on a decode rank', 'test the send_kvcache method to transfer KV cache memory descriptors via RDMA batch writes', 'review the _init_engine method that configures RDMA backend with QP per transfer, post batch size, and worker threads']
```

Usage

```
{'build_MoriKVManager': 'build a MoriKVManager instance to initialize an RDMA-based KV cache transfer engine for SGLang disaggregation', 'create_MoriKVSender': 'create a MoriKVSender to send KV cache chunks from a prefill rank to decode ranks over RDMA', 'create_MoriKVReceiver': 'create a MoriKVReceiver to receive KV cache data from prefill ranks on a decode rank', 'test_send_kvcache': 'test the send_kvcache method to transfer KV cache memory descriptors via RDMA batch writes', 'review_MoriKVManager_init_engine': 'review the _init_engine method that configures RDMA backend with QP per transfer, post batch size, and worker threads'}
```


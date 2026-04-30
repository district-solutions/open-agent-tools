# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/disaggregation/ascend/conn.py

Prompts

```
['initialize the Ascend KVManager engine with local IP, NPU ID, and disaggregation mode', 'register KV, auxiliary, and state data buffers to the Ascend transfer engine in batch', 'send KV cache data from prefill to decode stages using grouped contiguous blocks with parallel or batch transfer', 'create an AscendKVManager instance that extends MooncakeKVManager for NPU-based KV cache transfer', 'create AscendKVSender and AscendKVReceiver instances that inherit from Mooncake base classes', 'create an AscendTransferEngine instance with hostname, npu_id, and disaggregation mode for PD disaggregation', 'initialize the AscendTransferEngine with transfer protocol and NPU distributed setup', 'batch register NPU memory buffers with pointers and lengths on the AscendTransferEngine', 'get the transfer protocol from environment variable for AscendTransferEngine initialization', 'initialize AscendTransferEngine with device RDMA transfer protocol for prefill-decode disaggregation']
```

Usage

```
{'init_engine_ascend_kvmanager': 'initialize the Ascend KVManager engine with local IP, NPU ID, and disaggregation mode', 'register_buffer_to_engine': 'register KV, auxiliary, and state data buffers to the Ascend transfer engine in batch', 'send_kvcache': 'send KV cache data from prefill to decode stages using grouped contiguous blocks with parallel or batch transfer', 'create_ascend_kvmanager': 'create an AscendKVManager instance that extends MooncakeKVManager for NPU-based KV cache transfer', 'create_ascend_kv_sender_receiver': 'create AscendKVSender and AscendKVReceiver instances that inherit from Mooncake base classes'}
```

## File: sgl-project_sglang/python/sglang/srt/disaggregation/ascend/transfer_engine.py

Prompts

```
['initialize the Ascend KVManager engine with local IP, NPU ID, and disaggregation mode', 'register KV, auxiliary, and state data buffers to the Ascend transfer engine in batch', 'send KV cache data from prefill to decode stages using grouped contiguous blocks with parallel or batch transfer', 'create an AscendKVManager instance that extends MooncakeKVManager for NPU-based KV cache transfer', 'create AscendKVSender and AscendKVReceiver instances that inherit from Mooncake base classes', 'create an AscendTransferEngine instance with hostname, npu_id, and disaggregation mode for PD disaggregation', 'initialize the AscendTransferEngine with transfer protocol and NPU distributed setup', 'batch register NPU memory buffers with pointers and lengths on the AscendTransferEngine', 'get the transfer protocol from environment variable for AscendTransferEngine initialization', 'initialize AscendTransferEngine with device RDMA transfer protocol for prefill-decode disaggregation']
```

Usage

```
{'create_AscendTransferEngine': 'create an AscendTransferEngine instance with hostname, npu_id, and disaggregation mode for PD disaggregation', 'initialize_AscendTransferEngine': 'initialize the AscendTransferEngine with transfer protocol and NPU distributed setup', 'batch_register_AscendTransferEngine': 'batch register NPU memory buffers with pointers and lengths on the AscendTransferEngine', 'get_transfer_protocol_AscendTransferEngine': 'get the transfer protocol from environment variable for AscendTransferEngine initialization', 'initialize_AscendTransferEngine_rdma': 'initialize AscendTransferEngine with device RDMA transfer protocol for prefill-decode disaggregation'}
```


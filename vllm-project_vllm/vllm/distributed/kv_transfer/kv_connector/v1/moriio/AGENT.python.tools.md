# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/moriio/moriio_common.py

Prompts

```
['build a MoRIIOConfig from a VllmConfig to get local IP, ports, and parallel ranks for KV transfer', 'create a ZMQ socket context manager for ROUTER, REQ, or DEALER socket types with automatic cleanup', 'manage the singleton role state (PRODUCER, CONSUMER, NOTINIT) across the MoRIIO connector', 'add a new KV transfer request to MoRIIOConnectorMetadata for send or receive with block IDs and remote engine info', 'get the MoRIIO transfer mode (READ or WRITE) from the VLLM_MORIIO_CONNECTOR_READ_MODE environment variable', 'build a MoRIIO KV connector instance with vLLM config and scheduler or worker role for distributed KV cache transfer', 'create a MoRIIO handshake between local and remote engines to exchange KV cache metadata via ZMQ', 'register local KV cache tensors with MoRIIO engine for remote read and write operations', 'test reading KV cache blocks from a remote engine asynchronously for remote prefill decode', 'refactor saving KV cache layers on the producer side with background handshake and write scheduling', 'build a MoRIIOWriter instance to handle distributed KV cache write operations with RDMA-based communication', 'create a MoRIIOWrapper to manage RDMA session creation, tensor registration, and batch data transfers', 'schedule a WriteTask through MoRIIOWriter to transfer KV cache layers to a remote decode engine', 'register a remote engine metadata with MoRIIOWrapper to establish RDMA communication endpoints', 'send a completion notification via ZMQ to a remote decode engine after KV cache transfer finishes']
```

Usage

```
{'build_moriio_config': 'build a MoRIIOConfig from a VllmConfig to get local IP, ports, and parallel ranks for KV transfer', 'create_zmq_socket_ctx': 'create a ZMQ socket context manager for ROUTER, REQ, or DEALER socket types with automatic cleanup', 'manage_role_state': 'manage the singleton role state (PRODUCER, CONSUMER, NOTINIT) across the MoRIIO connector', 'add_kv_transfer_request': 'add a new KV transfer request to MoRIIOConnectorMetadata for send or receive with block IDs and remote engine info', 'get_moriio_transfer_mode': 'get the MoRIIO transfer mode (READ or WRITE) from the VLLM_MORIIO_CONNECTOR_READ_MODE environment variable'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/moriio/moriio_connector.py

Prompts

```
['build a MoRIIOConfig from a VllmConfig to get local IP, ports, and parallel ranks for KV transfer', 'create a ZMQ socket context manager for ROUTER, REQ, or DEALER socket types with automatic cleanup', 'manage the singleton role state (PRODUCER, CONSUMER, NOTINIT) across the MoRIIO connector', 'add a new KV transfer request to MoRIIOConnectorMetadata for send or receive with block IDs and remote engine info', 'get the MoRIIO transfer mode (READ or WRITE) from the VLLM_MORIIO_CONNECTOR_READ_MODE environment variable', 'build a MoRIIO KV connector instance with vLLM config and scheduler or worker role for distributed KV cache transfer', 'create a MoRIIO handshake between local and remote engines to exchange KV cache metadata via ZMQ', 'register local KV cache tensors with MoRIIO engine for remote read and write operations', 'test reading KV cache blocks from a remote engine asynchronously for remote prefill decode', 'refactor saving KV cache layers on the producer side with background handshake and write scheduling', 'build a MoRIIOWriter instance to handle distributed KV cache write operations with RDMA-based communication', 'create a MoRIIOWrapper to manage RDMA session creation, tensor registration, and batch data transfers', 'schedule a WriteTask through MoRIIOWriter to transfer KV cache layers to a remote decode engine', 'register a remote engine metadata with MoRIIOWrapper to establish RDMA communication endpoints', 'send a completion notification via ZMQ to a remote decode engine after KV cache transfer finishes']
```

Usage

```
{'build_moriio_connector': 'build a MoRIIO KV connector instance with vLLM config and scheduler or worker role for distributed KV cache transfer', 'create_moriio_handshake': 'create a MoRIIO handshake between local and remote engines to exchange KV cache metadata via ZMQ', 'run_kv_cache_register': 'register local KV cache tensors with MoRIIO engine for remote read and write operations', 'test_read_blocks_transfer': 'test reading KV cache blocks from a remote engine asynchronously for remote prefill decode', 'refactor_save_kv_layer': 'refactor saving KV cache layers on the producer side with background handshake and write scheduling'}
```

## File: vllm-project_vllm/vllm/distributed/kv_transfer/kv_connector/v1/moriio/moriio_engine.py

Prompts

```
['build a MoRIIOConfig from a VllmConfig to get local IP, ports, and parallel ranks for KV transfer', 'create a ZMQ socket context manager for ROUTER, REQ, or DEALER socket types with automatic cleanup', 'manage the singleton role state (PRODUCER, CONSUMER, NOTINIT) across the MoRIIO connector', 'add a new KV transfer request to MoRIIOConnectorMetadata for send or receive with block IDs and remote engine info', 'get the MoRIIO transfer mode (READ or WRITE) from the VLLM_MORIIO_CONNECTOR_READ_MODE environment variable', 'build a MoRIIO KV connector instance with vLLM config and scheduler or worker role for distributed KV cache transfer', 'create a MoRIIO handshake between local and remote engines to exchange KV cache metadata via ZMQ', 'register local KV cache tensors with MoRIIO engine for remote read and write operations', 'test reading KV cache blocks from a remote engine asynchronously for remote prefill decode', 'refactor saving KV cache layers on the producer side with background handshake and write scheduling', 'build a MoRIIOWriter instance to handle distributed KV cache write operations with RDMA-based communication', 'create a MoRIIOWrapper to manage RDMA session creation, tensor registration, and batch data transfers', 'schedule a WriteTask through MoRIIOWriter to transfer KV cache layers to a remote decode engine', 'register a remote engine metadata with MoRIIOWrapper to establish RDMA communication endpoints', 'send a completion notification via ZMQ to a remote decode engine after KV cache transfer finishes']
```

Usage

```
{'build_moRIIO_writer': 'build a MoRIIOWriter instance to handle distributed KV cache write operations with RDMA-based communication', 'create_moRIIO_wrapper': 'create a MoRIIOWrapper to manage RDMA session creation, tensor registration, and batch data transfers', 'schedule_write_task': 'schedule a WriteTask through MoRIIOWriter to transfer KV cache layers to a remote decode engine', 'register_remote_engine': 'register a remote engine metadata with MoRIIOWrapper to establish RDMA communication endpoints', 'send_transfer_notification': 'send a completion notification via ZMQ to a remote decode engine after KV cache transfer finishes'}
```


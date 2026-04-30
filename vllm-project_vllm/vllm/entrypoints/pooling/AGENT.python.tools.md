# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/pooling/factories.py

Prompts

```
['build pooling IO processors for embed, classify, and scoring tasks given vLLM config and renderer', 'create FastAPI routers for pooling, embedding, classification, and scoring tasks', 'run pooling state initialization with engine client, args, and supported tasks', 'test the pooling invocation types mapping request types to handler functions', 'summarize how init_pooling_io_processors instantiates task-specific IO processors from vLLM config', 'build metadata items for pooling outputs with embed dtype, endianness, shape, and request count', 'encode a pooling request output as a list of float values', 'encode a pooling request output as a base64 string with specified embed dtype and endianness', 'encode multiple pooling outputs into binary body, metadata items, and usage info', 'decode binary body and metadata items back into a list of torch tensors']
```

Usage

```
{'build_init_pooling_io_processors': 'build pooling IO processors for embed, classify, and scoring tasks given vLLM config and renderer', 'create_register_pooling_api_routers': 'create FastAPI routers for pooling, embedding, classification, and scoring tasks', 'run_init_pooling_state': 'run pooling state initialization with engine client, args, and supported tasks', 'test_get_pooling_invocation_types': 'test the pooling invocation types mapping request types to handler functions', 'summarize_init_pooling_io_processors': 'summarize how init_pooling_io_processors instantiates task-specific IO processors from vLLM config'}
```

## File: vllm-project_vllm/vllm/entrypoints/pooling/utils.py

Prompts

```
['build pooling IO processors for embed, classify, and scoring tasks given vLLM config and renderer', 'create FastAPI routers for pooling, embedding, classification, and scoring tasks', 'run pooling state initialization with engine client, args, and supported tasks', 'test the pooling invocation types mapping request types to handler functions', 'summarize how init_pooling_io_processors instantiates task-specific IO processors from vLLM config', 'build metadata items for pooling outputs with embed dtype, endianness, shape, and request count', 'encode a pooling request output as a list of float values', 'encode a pooling request output as a base64 string with specified embed dtype and endianness', 'encode multiple pooling outputs into binary body, metadata items, and usage info', 'decode binary body and metadata items back into a list of torch tensors']
```

Usage

```
{'build_metadata_items': 'build metadata items for pooling outputs with embed dtype, endianness, shape, and request count', 'encode_pooling_output_float': 'encode a pooling request output as a list of float values', 'encode_pooling_output_base64': 'encode a pooling request output as a base64 string with specified embed dtype and endianness', 'encode_pooling_bytes': 'encode multiple pooling outputs into binary body, metadata items, and usage info', 'decode_pooling_output': 'decode binary body and metadata items back into a list of torch tensors'}
```


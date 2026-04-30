# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/offline_inference/disaggregated_prefill.py

Prompts

```
['run the prefill node that generates KV caches on GPU 0 using P2pNcclConnector and a kv_producer role', 'run the decode node that receives KV caches on GPU 1 from the prefill node using P2pNcclConnector and a kv_consumer role', 'create a KVTransferConfig with P2pNcclConnector for disaggregated prefilling between two vLLM instances', 'create an LLM instance with KVTransferConfig for disaggregated prefill and decode across separate GPUs', 'run disaggregated prefilling by launching prefill and decode processes that transfer KV caches between GPUs', 'create test prompts with various sampling parameters for offline LLM inference', 'process a list of prompts through an LLM engine and handle finished request outputs', 'initialize an LLM engine from command line arguments using EngineArgs', 'parse command line arguments for LLM engine configuration using FlexibleArgumentParser', 'run the LLM engine prompt processing pipeline with test prompts and CLI arguments', 'run the FlexKV prefix caching example with vLLM using a specified model path', 'create a FlexKV configuration file with server port, CPU cache settings, and log interval', 'run the LLM generate method with prompts and sampling parameters for text generation', 'reset the vLLM prefix cache to switch between default caching and FlexKV mode', 'compare generated texts from regular, prefix-cached, and FlexKV LLM runs for correctness']
```

Usage

```
{'run_prefill': 'run the prefill node that generates KV caches on GPU 0 using P2pNcclConnector and a kv_producer role', 'run_decode': 'run the decode node that receives KV caches on GPU 1 from the prefill node using P2pNcclConnector and a kv_consumer role', 'create_kv_transfer_config': 'create a KVTransferConfig with P2pNcclConnector for disaggregated prefilling between two vLLM instances', 'create_llm_disaggregated': 'create an LLM instance with KVTransferConfig for disaggregated prefill and decode across separate GPUs', 'run_disaggregated_prefill': 'run disaggregated prefilling by launching prefill and decode processes that transfer KV caches between GPUs'}
```

## File: vllm-project_vllm/examples/offline_inference/llm_engine_example.py

Prompts

```
['run the prefill node that generates KV caches on GPU 0 using P2pNcclConnector and a kv_producer role', 'run the decode node that receives KV caches on GPU 1 from the prefill node using P2pNcclConnector and a kv_consumer role', 'create a KVTransferConfig with P2pNcclConnector for disaggregated prefilling between two vLLM instances', 'create an LLM instance with KVTransferConfig for disaggregated prefill and decode across separate GPUs', 'run disaggregated prefilling by launching prefill and decode processes that transfer KV caches between GPUs', 'create test prompts with various sampling parameters for offline LLM inference', 'process a list of prompts through an LLM engine and handle finished request outputs', 'initialize an LLM engine from command line arguments using EngineArgs', 'parse command line arguments for LLM engine configuration using FlexibleArgumentParser', 'run the LLM engine prompt processing pipeline with test prompts and CLI arguments', 'run the FlexKV prefix caching example with vLLM using a specified model path', 'create a FlexKV configuration file with server port, CPU cache settings, and log interval', 'run the LLM generate method with prompts and sampling parameters for text generation', 'reset the vLLM prefix cache to switch between default caching and FlexKV mode', 'compare generated texts from regular, prefix-cached, and FlexKV LLM runs for correctness']
```

Usage

```
{'create_test_prompts': 'create test prompts with various sampling parameters for offline LLM inference', 'process_requests': 'process a list of prompts through an LLM engine and handle finished request outputs', 'initialize_engine': 'initialize an LLM engine from command line arguments using EngineArgs', 'parse_args': 'parse command line arguments for LLM engine configuration using FlexibleArgumentParser', 'main': 'run the LLM engine prompt processing pipeline with test prompts and CLI arguments'}
```

## File: vllm-project_vllm/examples/offline_inference/prefix_caching_flexkv.py

Prompts

```
['run the prefill node that generates KV caches on GPU 0 using P2pNcclConnector and a kv_producer role', 'run the decode node that receives KV caches on GPU 1 from the prefill node using P2pNcclConnector and a kv_consumer role', 'create a KVTransferConfig with P2pNcclConnector for disaggregated prefilling between two vLLM instances', 'create an LLM instance with KVTransferConfig for disaggregated prefill and decode across separate GPUs', 'run disaggregated prefilling by launching prefill and decode processes that transfer KV caches between GPUs', 'create test prompts with various sampling parameters for offline LLM inference', 'process a list of prompts through an LLM engine and handle finished request outputs', 'initialize an LLM engine from command line arguments using EngineArgs', 'parse command line arguments for LLM engine configuration using FlexibleArgumentParser', 'run the LLM engine prompt processing pipeline with test prompts and CLI arguments', 'run the FlexKV prefix caching example with vLLM using a specified model path', 'create a FlexKV configuration file with server port, CPU cache settings, and log interval', 'run the LLM generate method with prompts and sampling parameters for text generation', 'reset the vLLM prefix cache to switch between default caching and FlexKV mode', 'compare generated texts from regular, prefix-cached, and FlexKV LLM runs for correctness']
```

Usage

```
{'run_prefix_caching_flexkv': 'run the FlexKV prefix caching example with vLLM using a specified model path', 'create_flexkv_config': 'create a FlexKV configuration file with server port, CPU cache settings, and log interval', 'run_llm_generate': 'run the LLM generate method with prompts and sampling parameters for text generation', 'reset_prefix_cache': 'reset the vLLM prefix cache to switch between default caching and FlexKV mode', 'compare_generated_texts': 'compare generated texts from regular, prefix-cached, and FlexKV LLM runs for correctness'}
```


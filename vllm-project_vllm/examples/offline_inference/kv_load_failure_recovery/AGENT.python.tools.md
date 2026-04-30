# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/offline_inference/kv_load_failure_recovery/decode_example.py

Prompts

```
['run the decode_example.py script to generate text from prompts using vLLM offline inference', 'run the decode_example.py script with --simulate-failure to test KV load failure recovery', 'run the decode_example.py script with --simulate-failure --async-load for async KV load recovery', 'run the decode_example.py script with a custom KV connector for distributed KV cache transfer', 'run the decode_example.py script with temperature 0 and top_p 0.95 for deterministic text generation', 'create a LoadRecoveryExampleConnector instance with VllmConfig and KVConnectorRole for KV cache load failure recovery', 'build LoadRecoveryExampleConnectorMetadata from base ExampleConnectorMetadata for KV transfer state tracking', 'bind KVConnectorMetadata to the connector and simulate failure on the first load request', 'get the number of new matched tokens for a request and track seen requests to avoid duplicates', 'build connector metadata from scheduler output, populating request-to-block mappings for async KV loading', 'run offline LLM inference with vLLM LLM class using prompts and sampling parameters', 'create a KVTransferConfig with connector name, role, and extra config for KV cache transfer', 'build a SamplingParams object with temperature, top_p, and max_tokens settings', 'read prompts with repeated context and generate text using vLLM LLM generate method', 'save LLM generated outputs and extended prompts to a text file']
```

Usage

```
{'run_decode_example': 'run the decode_example.py script to generate text from prompts using vLLM offline inference', 'run_decode_with_failure_recovery': 'run the decode_example.py script with --simulate-failure to test KV load failure recovery', 'run_decode_with_async_recovery': 'run the decode_example.py script with --simulate-failure --async-load for async KV load recovery', 'run_decode_with_connector': 'run the decode_example.py script with a custom KV connector for distributed KV cache transfer', 'run_decode_with_sampling_params': 'run the decode_example.py script with temperature 0 and top_p 0.95 for deterministic text generation'}
```

## File: vllm-project_vllm/examples/offline_inference/kv_load_failure_recovery/load_recovery_example_connector.py

Prompts

```
['run the decode_example.py script to generate text from prompts using vLLM offline inference', 'run the decode_example.py script with --simulate-failure to test KV load failure recovery', 'run the decode_example.py script with --simulate-failure --async-load for async KV load recovery', 'run the decode_example.py script with a custom KV connector for distributed KV cache transfer', 'run the decode_example.py script with temperature 0 and top_p 0.95 for deterministic text generation', 'create a LoadRecoveryExampleConnector instance with VllmConfig and KVConnectorRole for KV cache load failure recovery', 'build LoadRecoveryExampleConnectorMetadata from base ExampleConnectorMetadata for KV transfer state tracking', 'bind KVConnectorMetadata to the connector and simulate failure on the first load request', 'get the number of new matched tokens for a request and track seen requests to avoid duplicates', 'build connector metadata from scheduler output, populating request-to-block mappings for async KV loading', 'run offline LLM inference with vLLM LLM class using prompts and sampling parameters', 'create a KVTransferConfig with connector name, role, and extra config for KV cache transfer', 'build a SamplingParams object with temperature, top_p, and max_tokens settings', 'read prompts with repeated context and generate text using vLLM LLM generate method', 'save LLM generated outputs and extended prompts to a text file']
```

Usage

```
{'create_LoadRecoveryExampleConnector': 'create a LoadRecoveryExampleConnector instance with VllmConfig and KVConnectorRole for KV cache load failure recovery', 'build_connector_metadata': 'build LoadRecoveryExampleConnectorMetadata from base ExampleConnectorMetadata for KV transfer state tracking', 'bind_connector_metadata': 'bind KVConnectorMetadata to the connector and simulate failure on the first load request', 'get_num_new_matched_tokens': 'get the number of new matched tokens for a request and track seen requests to avoid duplicates', 'build_connector_meta': 'build connector metadata from scheduler output, populating request-to-block mappings for async KV loading'}
```

## File: vllm-project_vllm/examples/offline_inference/kv_load_failure_recovery/prefill_example.py

Prompts

```
['run the decode_example.py script to generate text from prompts using vLLM offline inference', 'run the decode_example.py script with --simulate-failure to test KV load failure recovery', 'run the decode_example.py script with --simulate-failure --async-load for async KV load recovery', 'run the decode_example.py script with a custom KV connector for distributed KV cache transfer', 'run the decode_example.py script with temperature 0 and top_p 0.95 for deterministic text generation', 'create a LoadRecoveryExampleConnector instance with VllmConfig and KVConnectorRole for KV cache load failure recovery', 'build LoadRecoveryExampleConnectorMetadata from base ExampleConnectorMetadata for KV transfer state tracking', 'bind KVConnectorMetadata to the connector and simulate failure on the first load request', 'get the number of new matched tokens for a request and track seen requests to avoid duplicates', 'build connector metadata from scheduler output, populating request-to-block mappings for async KV loading', 'run offline LLM inference with vLLM LLM class using prompts and sampling parameters', 'create a KVTransferConfig with connector name, role, and extra config for KV cache transfer', 'build a SamplingParams object with temperature, top_p, and max_tokens settings', 'read prompts with repeated context and generate text using vLLM LLM generate method', 'save LLM generated outputs and extended prompts to a text file']
```

Usage

```
{'run_llm_generate_prefill': 'run offline LLM inference with vLLM LLM class using prompts and sampling parameters', 'create_kv_transfer_config': 'create a KVTransferConfig with connector name, role, and extra config for KV cache transfer', 'build_sampling_params': 'build a SamplingParams object with temperature, top_p, and max_tokens settings', 'read_prompts_generate': 'read prompts with repeated context and generate text using vLLM LLM generate method', 'save_generated_outputs': 'save LLM generated outputs and extended prompts to a text file'}
```


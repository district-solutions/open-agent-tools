# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/others/lmcache/cpu_offload_lmcache.py

Prompts

```
['build an LLM with LMCache CPU offloading using a context manager that configures KV transfer and cleans up the backend', 'setup LMCache environment variables for experimental features, chunk size, local CPU backend, and memory limit', 'print LLM generation output and timing for a prompt with sampling parameters using LMCache-backed generation', 'parse command-line arguments to select vLLM version (v0 or v1) for LMCache connector configuration', 'run the full LMCache CPU offload demo with two shared-prefix prompts and print generated text output', 'run disaggregated prefilling with LMCache server using separate GPU nodes for prefill and decode', 'build a KVTransferConfig for the prefill (kv_producer) role with LMCacheConnector and parallel size 2', 'build a KVTransferConfig for the decode (kv_consumer) role with LMCacheConnector and parallel size 2', 'create an LMCache server subprocess listening on localhost and a configurable TCP port', 'run prefill and decode vLLM LLM instances in separate processes with LMCache KV cache transfer between them', 'run the LMCache server on a specified port for remote KV cache sharing', 'run KV cache store with vLLM instance using LMCacheConnectorV1 on GPU 0', 'run KV cache retrieve from LMCache server using vLLM instance on GPU 1', 'build a KV cache sharing pipeline with vLLM and LMCache using multiprocessing', 'configure LMCache environment variables for chunk size, remote URL, and serde']
```

Usage

```
{'build_llm_with_lmcache': 'build an LLM with LMCache CPU offloading using a context manager that configures KV transfer and cleans up the backend', 'setup_environment_variables': 'setup LMCache environment variables for experimental features, chunk size, local CPU backend, and memory limit', 'print_output': 'print LLM generation output and timing for a prompt with sampling parameters using LMCache-backed generation', 'parse_args': 'parse command-line arguments to select vLLM version (v0 or v1) for LMCache connector configuration', 'main': 'run the full LMCache CPU offload demo with two shared-prefix prompts and print generated text output'}
```

## File: vllm-project_vllm/examples/others/lmcache/disagg_prefill_lmcache_v0.py

Prompts

```
['build an LLM with LMCache CPU offloading using a context manager that configures KV transfer and cleans up the backend', 'setup LMCache environment variables for experimental features, chunk size, local CPU backend, and memory limit', 'print LLM generation output and timing for a prompt with sampling parameters using LMCache-backed generation', 'parse command-line arguments to select vLLM version (v0 or v1) for LMCache connector configuration', 'run the full LMCache CPU offload demo with two shared-prefix prompts and print generated text output', 'run disaggregated prefilling with LMCache server using separate GPU nodes for prefill and decode', 'build a KVTransferConfig for the prefill (kv_producer) role with LMCacheConnector and parallel size 2', 'build a KVTransferConfig for the decode (kv_consumer) role with LMCacheConnector and parallel size 2', 'create an LMCache server subprocess listening on localhost and a configurable TCP port', 'run prefill and decode vLLM LLM instances in separate processes with LMCache KV cache transfer between them', 'run the LMCache server on a specified port for remote KV cache sharing', 'run KV cache store with vLLM instance using LMCacheConnectorV1 on GPU 0', 'run KV cache retrieve from LMCache server using vLLM instance on GPU 1', 'build a KV cache sharing pipeline with vLLM and LMCache using multiprocessing', 'configure LMCache environment variables for chunk size, remote URL, and serde']
```

Usage

```
{'run_disagg_prefill_lmcache': 'run disaggregated prefilling with LMCache server using separate GPU nodes for prefill and decode', 'build_kv_transfer_config_producer': 'build a KVTransferConfig for the prefill (kv_producer) role with LMCacheConnector and parallel size 2', 'build_kv_transfer_config_consumer': 'build a KVTransferConfig for the decode (kv_consumer) role with LMCacheConnector and parallel size 2', 'create_lmcache_server_process': 'create an LMCache server subprocess listening on localhost and a configurable TCP port', 'run_prefill_decode_processes': 'run prefill and decode vLLM LLM instances in separate processes with LMCache KV cache transfer between them'}
```

## File: vllm-project_vllm/examples/others/lmcache/kv_cache_sharing_lmcache_v1.py

Prompts

```
['build an LLM with LMCache CPU offloading using a context manager that configures KV transfer and cleans up the backend', 'setup LMCache environment variables for experimental features, chunk size, local CPU backend, and memory limit', 'print LLM generation output and timing for a prompt with sampling parameters using LMCache-backed generation', 'parse command-line arguments to select vLLM version (v0 or v1) for LMCache connector configuration', 'run the full LMCache CPU offload demo with two shared-prefix prompts and print generated text output', 'run disaggregated prefilling with LMCache server using separate GPU nodes for prefill and decode', 'build a KVTransferConfig for the prefill (kv_producer) role with LMCacheConnector and parallel size 2', 'build a KVTransferConfig for the decode (kv_consumer) role with LMCacheConnector and parallel size 2', 'create an LMCache server subprocess listening on localhost and a configurable TCP port', 'run prefill and decode vLLM LLM instances in separate processes with LMCache KV cache transfer between them', 'run the LMCache server on a specified port for remote KV cache sharing', 'run KV cache store with vLLM instance using LMCacheConnectorV1 on GPU 0', 'run KV cache retrieve from LMCache server using vLLM instance on GPU 1', 'build a KV cache sharing pipeline with vLLM and LMCache using multiprocessing', 'configure LMCache environment variables for chunk size, remote URL, and serde']
```

Usage

```
{'run_lmcache_server': 'run the LMCache server on a specified port for remote KV cache sharing', 'run_store_kv_cache': 'run KV cache store with vLLM instance using LMCacheConnectorV1 on GPU 0', 'run_retrieve_kv_cache': 'run KV cache retrieve from LMCache server using vLLM instance on GPU 1', 'build_kv_cache_sharing_pipeline': 'build a KV cache sharing pipeline with vLLM and LMCache using multiprocessing', 'configure_lmcache_environment': 'configure LMCache environment variables for chunk size, remote URL, and serde'}
```


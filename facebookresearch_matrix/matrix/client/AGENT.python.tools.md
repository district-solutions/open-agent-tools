# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/matrix/client/client_utils.py

Prompts

```
['get an endpoint URL from the cache using multiplexed model ID hashing or random selection', 'save a list of request response dicts to a JSONL file while tracking success and latency stats', 'load data from one or more JSONL files and return a list of parsed dictionaries', 'review the get_an_endpoint_url async function that retries with exponential backoff when the cache is empty', 'refactor the save_to_jsonl function to support custom stats keys or additional response fields', 'execute code snippets from JSONL input files by sending batched HTTP requests to a code execution backend', 'load code snippets from JSONL files using text keys and optional prompt templates for code assembly', 'send a single code execution request to an HTTP endpoint with retry logic and exponential backoff', 'run the CodeExcutionClient via Fire CLI to execute code from JSONL files against a backend URL', 'batch execute code requests with configurable concurrency, timeout, and automatic retry on failure', 'run multiprocess LLM inference on a data loader with configurable number of worker processes', 'create an LLMClient instance with an app name and optional cluster configuration', 'get an async LLM response by passing data with messages or prompt and params', 'postprocess LLM responses from a queue and write results to a JSON lines file', 'run an inference process wrapper that batches async LLM requests and puts results on a queue', 'run batch requests to an LLM endpoint with retry logic and error handling', 'create a single LLM completion request with configurable temperature and max tokens', 'parse Llama instruct format text into structured chat messages with roles', 'generate responses for multiple prompts using a deployed Matrix application']
```

Usage

```
{'get_an_endpoint_url': 'get an endpoint URL from the cache using multiplexed model ID hashing or random selection', 'save_to_jsonl': 'save a list of request response dicts to a JSONL file while tracking success and latency stats', 'load_from_jsonl': 'load data from one or more JSONL files and return a list of parsed dictionaries', 'review_get_an_endpoint_url': 'review the get_an_endpoint_url async function that retries with exponential backoff when the cache is empty', 'refactor_save_to_jsonl': 'refactor the save_to_jsonl function to support custom stats keys or additional response fields'}
```

## File: facebookresearch_matrix/matrix/client/execute_code.py

Prompts

```
['get an endpoint URL from the cache using multiplexed model ID hashing or random selection', 'save a list of request response dicts to a JSONL file while tracking success and latency stats', 'load data from one or more JSONL files and return a list of parsed dictionaries', 'review the get_an_endpoint_url async function that retries with exponential backoff when the cache is empty', 'refactor the save_to_jsonl function to support custom stats keys or additional response fields', 'execute code snippets from JSONL input files by sending batched HTTP requests to a code execution backend', 'load code snippets from JSONL files using text keys and optional prompt templates for code assembly', 'send a single code execution request to an HTTP endpoint with retry logic and exponential backoff', 'run the CodeExcutionClient via Fire CLI to execute code from JSONL files against a backend URL', 'batch execute code requests with configurable concurrency, timeout, and automatic retry on failure', 'run multiprocess LLM inference on a data loader with configurable number of worker processes', 'create an LLMClient instance with an app name and optional cluster configuration', 'get an async LLM response by passing data with messages or prompt and params', 'postprocess LLM responses from a queue and write results to a JSON lines file', 'run an inference process wrapper that batches async LLM requests and puts results on a queue', 'run batch requests to an LLM endpoint with retry logic and error handling', 'create a single LLM completion request with configurable temperature and max tokens', 'parse Llama instruct format text into structured chat messages with roles', 'generate responses for multiple prompts using a deployed Matrix application']
```

Usage

```
{'execute_code_from_jsonl': 'execute code snippets from JSONL input files by sending batched HTTP requests to a code execution backend', 'load_code_from_jsonl': 'load code snippets from JSONL files using text keys and optional prompt templates for code assembly', 'make_code_execution_request': 'send a single code execution request to an HTTP endpoint with retry logic and exponential backoff', 'run_code_execution_client': 'run the CodeExcutionClient via Fire CLI to execute code from JSONL files against a backend URL', 'batch_execute_code_with_retry': 'batch execute code requests with configurable concurrency, timeout, and automatic retry on failure'}
```

## File: facebookresearch_matrix/matrix/client/llm_client.py

Prompts

```
['get an endpoint URL from the cache using multiplexed model ID hashing or random selection', 'save a list of request response dicts to a JSONL file while tracking success and latency stats', 'load data from one or more JSONL files and return a list of parsed dictionaries', 'review the get_an_endpoint_url async function that retries with exponential backoff when the cache is empty', 'refactor the save_to_jsonl function to support custom stats keys or additional response fields', 'execute code snippets from JSONL input files by sending batched HTTP requests to a code execution backend', 'load code snippets from JSONL files using text keys and optional prompt templates for code assembly', 'send a single code execution request to an HTTP endpoint with retry logic and exponential backoff', 'run the CodeExcutionClient via Fire CLI to execute code from JSONL files against a backend URL', 'batch execute code requests with configurable concurrency, timeout, and automatic retry on failure', 'run multiprocess LLM inference on a data loader with configurable number of worker processes', 'create an LLMClient instance with an app name and optional cluster configuration', 'get an async LLM response by passing data with messages or prompt and params', 'postprocess LLM responses from a queue and write results to a JSON lines file', 'run an inference process wrapper that batches async LLM requests and puts results on a queue', 'run batch requests to an LLM endpoint with retry logic and error handling', 'create a single LLM completion request with configurable temperature and max tokens', 'parse Llama instruct format text into structured chat messages with roles', 'generate responses for multiple prompts using a deployed Matrix application']
```

Usage

```
{'run_multiprocess_llm_inference': 'run multiprocess LLM inference on a data loader with configurable number of worker processes', 'create_llm_client': 'create an LLMClient instance with an app name and optional cluster configuration', 'get_async_llm_response': 'get an async LLM response by passing data with messages or prompt and params', 'postprocess_llm_responses': 'postprocess LLM responses from a queue and write results to a JSON lines file', 'run_inference_process_wrapper': 'run an inference process wrapper that batches async LLM requests and puts results on a queue'}
```

## File: facebookresearch_matrix/matrix/client/query_llm.py

Prompts

```
['get an endpoint URL from the cache using multiplexed model ID hashing or random selection', 'save a list of request response dicts to a JSONL file while tracking success and latency stats', 'load data from one or more JSONL files and return a list of parsed dictionaries', 'review the get_an_endpoint_url async function that retries with exponential backoff when the cache is empty', 'refactor the save_to_jsonl function to support custom stats keys or additional response fields', 'execute code snippets from JSONL input files by sending batched HTTP requests to a code execution backend', 'load code snippets from JSONL files using text keys and optional prompt templates for code assembly', 'send a single code execution request to an HTTP endpoint with retry logic and exponential backoff', 'run the CodeExcutionClient via Fire CLI to execute code from JSONL files against a backend URL', 'batch execute code requests with configurable concurrency, timeout, and automatic retry on failure', 'run multiprocess LLM inference on a data loader with configurable number of worker processes', 'create an LLMClient instance with an app name and optional cluster configuration', 'get an async LLM response by passing data with messages or prompt and params', 'postprocess LLM responses from a queue and write results to a JSON lines file', 'run an inference process wrapper that batches async LLM requests and puts results on a queue', 'run batch requests to an LLM endpoint with retry logic and error handling', 'create a single LLM completion request with configurable temperature and max tokens', 'parse Llama instruct format text into structured chat messages with roles', 'generate responses for multiple prompts using a deployed Matrix application']
```

Usage

```
{'batch_requests': 'run batch requests to an LLM endpoint with retry logic and error handling', 'make_request': 'create a single LLM completion request with configurable temperature and max tokens', 'convert_llama_instruct_text': 'parse Llama instruct format text into structured chat messages with roles', 'load_from_jsonl': 'load and prepare LLM requests from JSONL files with system prompt injection', 'generate': 'generate responses for multiple prompts using a deployed Matrix application'}
```


# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/examples/pooling/reward/sequence_reward_offline.py

Prompts

```
['run the sequence reward offline example to generate rewards for input prompts using a pooling runner', 'run the parse_args function to build an argument parser with vLLM engine defaults and example-specific settings', 'run the main function to create an LLM with pooling runner and encode prompts to generate sequence rewards', 'run llm.encode with pooling_task=classify to generate sequence-level reward outputs for a list of prompts', 'run print_embeddings to display reward values from PoolingRequestOutput for each prompt', 'test the python function post_http_request to send a POST request with a prompt dict to the pooling API URL', 'test the python function parse_args to parse command-line arguments for host and port', 'test the python function main to run the sequence reward online example with the pooling API', 'summarize the python function post_http_request that sends HTTP POST requests with JSON prompts to a vLLM pooling endpoint', 'run the python module sequence_reward_online.py to send completion and chat prompts to a vLLM pooling server', 'run the offline token reward model example to generate rewards for sample prompts using a pooling runner', 'parse CLI arguments with default model, pooling runner, eager mode, and max model length for reward inference', 'create an LLM instance with runner=pooling and EngineArgs for token-level reward model inference', 'encode a list of prompts with pooling_task=token_classify to produce per-token reward scores', 'print per-token reward embeddings for each prompt output using print_embeddings utility', 'run the vLLM token reward online example to test pooling API with a reward model', 'test the pooling API with completions-style input containing a model and text prompt', 'test the pooling API with chat-style input containing model and message array', 'build an argparse CLI with configurable host and port for the token reward online script', 'post an HTTP request to the vLLM pooling endpoint with a JSON prompt payload']
```

Usage

```
{'run_sequence_reward_offline': 'run the sequence reward offline example to generate rewards for input prompts using a pooling runner', 'run_parse_args': 'run the parse_args function to build an argument parser with vLLM engine defaults and example-specific settings', 'run_main': 'run the main function to create an LLM with pooling runner and encode prompts to generate sequence rewards', 'run_llm_encode': 'run llm.encode with pooling_task=classify to generate sequence-level reward outputs for a list of prompts', 'run_print_embeddings': 'run print_embeddings to display reward values from PoolingRequestOutput for each prompt'}
```

## File: vllm-project_vllm/examples/pooling/reward/sequence_reward_online.py

Prompts

```
['run the sequence reward offline example to generate rewards for input prompts using a pooling runner', 'run the parse_args function to build an argument parser with vLLM engine defaults and example-specific settings', 'run the main function to create an LLM with pooling runner and encode prompts to generate sequence rewards', 'run llm.encode with pooling_task=classify to generate sequence-level reward outputs for a list of prompts', 'run print_embeddings to display reward values from PoolingRequestOutput for each prompt', 'test the python function post_http_request to send a POST request with a prompt dict to the pooling API URL', 'test the python function parse_args to parse command-line arguments for host and port', 'test the python function main to run the sequence reward online example with the pooling API', 'summarize the python function post_http_request that sends HTTP POST requests with JSON prompts to a vLLM pooling endpoint', 'run the python module sequence_reward_online.py to send completion and chat prompts to a vLLM pooling server', 'run the offline token reward model example to generate rewards for sample prompts using a pooling runner', 'parse CLI arguments with default model, pooling runner, eager mode, and max model length for reward inference', 'create an LLM instance with runner=pooling and EngineArgs for token-level reward model inference', 'encode a list of prompts with pooling_task=token_classify to produce per-token reward scores', 'print per-token reward embeddings for each prompt output using print_embeddings utility', 'run the vLLM token reward online example to test pooling API with a reward model', 'test the pooling API with completions-style input containing a model and text prompt', 'test the pooling API with chat-style input containing model and message array', 'build an argparse CLI with configurable host and port for the token reward online script', 'post an HTTP request to the vLLM pooling endpoint with a JSON prompt payload']
```

Usage

```
{'test_post_http_request': 'test the python function post_http_request to send a POST request with a prompt dict to the pooling API URL', 'test_parse_args': 'test the python function parse_args to parse command-line arguments for host and port', 'test_main': 'test the python function main to run the sequence reward online example with the pooling API', 'summarize_post_http_request': 'summarize the python function post_http_request that sends HTTP POST requests with JSON prompts to a vLLM pooling endpoint', 'run_sequence_reward_online': 'run the python module sequence_reward_online.py to send completion and chat prompts to a vLLM pooling server'}
```

## File: vllm-project_vllm/examples/pooling/reward/token_reward_offline.py

Prompts

```
['run the sequence reward offline example to generate rewards for input prompts using a pooling runner', 'run the parse_args function to build an argument parser with vLLM engine defaults and example-specific settings', 'run the main function to create an LLM with pooling runner and encode prompts to generate sequence rewards', 'run llm.encode with pooling_task=classify to generate sequence-level reward outputs for a list of prompts', 'run print_embeddings to display reward values from PoolingRequestOutput for each prompt', 'test the python function post_http_request to send a POST request with a prompt dict to the pooling API URL', 'test the python function parse_args to parse command-line arguments for host and port', 'test the python function main to run the sequence reward online example with the pooling API', 'summarize the python function post_http_request that sends HTTP POST requests with JSON prompts to a vLLM pooling endpoint', 'run the python module sequence_reward_online.py to send completion and chat prompts to a vLLM pooling server', 'run the offline token reward model example to generate rewards for sample prompts using a pooling runner', 'parse CLI arguments with default model, pooling runner, eager mode, and max model length for reward inference', 'create an LLM instance with runner=pooling and EngineArgs for token-level reward model inference', 'encode a list of prompts with pooling_task=token_classify to produce per-token reward scores', 'print per-token reward embeddings for each prompt output using print_embeddings utility', 'run the vLLM token reward online example to test pooling API with a reward model', 'test the pooling API with completions-style input containing a model and text prompt', 'test the pooling API with chat-style input containing model and message array', 'build an argparse CLI with configurable host and port for the token reward online script', 'post an HTTP request to the vLLM pooling endpoint with a JSON prompt payload']
```

Usage

```
{'run_token_reward_offline': 'run the offline token reward model example to generate rewards for sample prompts using a pooling runner', 'parse_args_configure_llm': 'parse CLI arguments with default model, pooling runner, eager mode, and max model length for reward inference', 'create_llm_pooling_runner': 'create an LLM instance with runner=pooling and EngineArgs for token-level reward model inference', 'encode_prompts_token_classify': 'encode a list of prompts with pooling_task=token_classify to produce per-token reward scores', 'print_embeddings_rewards': 'print per-token reward embeddings for each prompt output using print_embeddings utility'}
```

## File: vllm-project_vllm/examples/pooling/reward/token_reward_online.py

Prompts

```
['run the sequence reward offline example to generate rewards for input prompts using a pooling runner', 'run the parse_args function to build an argument parser with vLLM engine defaults and example-specific settings', 'run the main function to create an LLM with pooling runner and encode prompts to generate sequence rewards', 'run llm.encode with pooling_task=classify to generate sequence-level reward outputs for a list of prompts', 'run print_embeddings to display reward values from PoolingRequestOutput for each prompt', 'test the python function post_http_request to send a POST request with a prompt dict to the pooling API URL', 'test the python function parse_args to parse command-line arguments for host and port', 'test the python function main to run the sequence reward online example with the pooling API', 'summarize the python function post_http_request that sends HTTP POST requests with JSON prompts to a vLLM pooling endpoint', 'run the python module sequence_reward_online.py to send completion and chat prompts to a vLLM pooling server', 'run the offline token reward model example to generate rewards for sample prompts using a pooling runner', 'parse CLI arguments with default model, pooling runner, eager mode, and max model length for reward inference', 'create an LLM instance with runner=pooling and EngineArgs for token-level reward model inference', 'encode a list of prompts with pooling_task=token_classify to produce per-token reward scores', 'print per-token reward embeddings for each prompt output using print_embeddings utility', 'run the vLLM token reward online example to test pooling API with a reward model', 'test the pooling API with completions-style input containing a model and text prompt', 'test the pooling API with chat-style input containing model and message array', 'build an argparse CLI with configurable host and port for the token reward online script', 'post an HTTP request to the vLLM pooling endpoint with a JSON prompt payload']
```

Usage

```
{'run_token_reward_online': 'run the vLLM token reward online example to test pooling API with a reward model', 'test_pooling_completions': 'test the pooling API with completions-style input containing a model and text prompt', 'test_pooling_chat': 'test the pooling API with chat-style input containing model and message array', 'build_cli_args': 'build an argparse CLI with configurable host and port for the token reward online script', 'post_http_request': 'post an HTTP request to the vLLM pooling endpoint with a JSON prompt payload'}
```


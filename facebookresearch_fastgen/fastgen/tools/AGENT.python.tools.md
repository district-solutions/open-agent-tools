# Agent Python Tools

- repo: facebookresearch/fastgen
- repo_uri: https://github.com/facebookresearch/fastgen

## File: facebookresearch_fastgen/fastgen/tools/chat.py

Prompts

```
['run an interactive chat session with a HuggingFace model using tensor parallel inference', 'run the chat tool with multiple GPUs for tensor parallel LLM inference', 'run the chat tool with temperature and top-p sampling parameters for generation', 'review the worker_main function that handles model loading and token generation via IPC', 'review the main CLI entry point that spawns worker processes and manages the chat loop', 'run a flask server that serves an OpenAI-compatible chat completions API using FastGen', 'run FastGen inference across multiple GPUs using tensor parallelism with NCCL backend', 'handle POST requests to the chat completions endpoint and return generated token responses', 'review the Request dataclass that defines chat completion parameters like temperature and max tokens', 'review the worker enqueuer thread that converts incoming requests into Packet objects for generation']
```

Usage

```
{'run_chat_cli': 'run an interactive chat session with a HuggingFace model using tensor parallel inference', 'run_chat_with_tensor_parallel': 'run the chat tool with multiple GPUs for tensor parallel LLM inference', 'run_chat_with_sampling': 'run the chat tool with temperature and top-p sampling parameters for generation', 'review_worker_main': 'review the worker_main function that handles model loading and token generation via IPC', 'review_main_cli': 'review the main CLI entry point that spawns worker processes and manages the chat loop'}
```

## File: facebookresearch_fastgen/fastgen/tools/serve.py

Prompts

```
['run an interactive chat session with a HuggingFace model using tensor parallel inference', 'run the chat tool with multiple GPUs for tensor parallel LLM inference', 'run the chat tool with temperature and top-p sampling parameters for generation', 'review the worker_main function that handles model loading and token generation via IPC', 'review the main CLI entry point that spawns worker processes and manages the chat loop', 'run a flask server that serves an OpenAI-compatible chat completions API using FastGen', 'run FastGen inference across multiple GPUs using tensor parallelism with NCCL backend', 'handle POST requests to the chat completions endpoint and return generated token responses', 'review the Request dataclass that defines chat completion parameters like temperature and max tokens', 'review the worker enqueuer thread that converts incoming requests into Packet objects for generation']
```

Usage

```
{'run_fastgen_server': 'run a flask server that serves an OpenAI-compatible chat completions API using FastGen', 'run_tensor_parallel_inference': 'run FastGen inference across multiple GPUs using tensor parallelism with NCCL backend', 'handle_chat_completions': 'handle POST requests to the chat completions endpoint and return generated token responses', 'review_Request_dataclass': 'review the Request dataclass that defines chat completion parameters like temperature and max tokens', 'review_worker_enqueuer': 'review the worker enqueuer thread that converts incoming requests into Packet objects for generation'}
```


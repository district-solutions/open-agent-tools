# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/openai/engine/protocol.py

Prompts

```
['build a ModelCard object with model id, permissions, and max model length for OpenAI API responses', 'create an ErrorResponse with error message, type, parameter, and HTTP status code for API error handling', 'create a UsageInfo object tracking prompt tokens, completion tokens, and total tokens for API responses', 'create a ToolCall object with function name, arguments, and auto-generated ID for streaming chat completions', 'run get_logits_processors to validate and instantiate logits processors by qualified name with a regex pattern filter', "build beam search generation using vLLM's OpenAIServing class with configurable beam width and sampling params", 'run model validation to check if a requested model is supported or can be resolved via LoRA', 'parse tool calls from model response content using a configured tool parser and tokenizer', 'clamp infinite logprob values to -9999.0 for prompt logprobs to avoid serialization issues']
```

Usage

```
{'build_model_card': 'build a ModelCard object with model id, permissions, and max model length for OpenAI API responses', 'create_error_response': 'create an ErrorResponse with error message, type, parameter, and HTTP status code for API error handling', 'create_usage_info': 'create a UsageInfo object tracking prompt tokens, completion tokens, and total tokens for API responses', 'create_tool_call': 'create a ToolCall object with function name, arguments, and auto-generated ID for streaming chat completions', 'run_get_logits_processors': 'run get_logits_processors to validate and instantiate logits processors by qualified name with a regex pattern filter'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/engine/serving.py

Prompts

```
['build a ModelCard object with model id, permissions, and max model length for OpenAI API responses', 'create an ErrorResponse with error message, type, parameter, and HTTP status code for API error handling', 'create a UsageInfo object tracking prompt tokens, completion tokens, and total tokens for API responses', 'create a ToolCall object with function name, arguments, and auto-generated ID for streaming chat completions', 'run get_logits_processors to validate and instantiate logits processors by qualified name with a regex pattern filter', "build beam search generation using vLLM's OpenAIServing class with configurable beam width and sampling params", 'run model validation to check if a requested model is supported or can be resolved via LoRA', 'parse tool calls from model response content using a configured tool parser and tokenizer', 'clamp infinite logprob values to -9999.0 for prompt logprobs to avoid serialization issues']
```

Usage

```
{'build_beam_search': "build beam search generation using vLLM's OpenAIServing class with configurable beam width and sampling params", 'create_error_response': 'create an OpenAI-compatible error response with a message, error type, and HTTP status code', 'run_model_check': 'run model validation to check if a requested model is supported or can be resolved via LoRA', 'parse_tool_calls': 'parse tool calls from model response content using a configured tool parser and tokenizer', 'clamp_prompt_logprobs': 'clamp infinite logprob values to -9999.0 for prompt logprobs to avoid serialization issues'}
```


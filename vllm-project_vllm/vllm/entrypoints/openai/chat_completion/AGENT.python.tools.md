# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/openai/chat_completion/api_router.py

Prompts

```
['create a fastapi endpoint that handles chat completion requests with streaming and JSON responses', 'create a fastapi endpoint that processes batch chat completion requests and returns JSON responses', 'test attaching the chat completion router to a fastapi application instance', 'review the helper function that retrieves the OpenAIServingChat handler from the request app state', 'summarize the async chat completion endpoint that supports streaming, JSON, and error responses', 'create a ChatCompletionRequest with messages, model, and sampling parameters for vLLM chat completion API', 'build SamplingParams from a ChatCompletionRequest including temperature, top_p, and structured output configuration', 'validate a ChatCompletionRequest ensuring tool_choice matches tools, logprobs flags are consistent, and response_format is correct', 'create a BatchChatCompletionRequest to process multiple independent conversations in a single API call', 'build ChatParams from a ChatCompletionRequest with chat template, documents, and reasoning effort settings', 'create a chat completion using OpenAIServingChat with a ChatCompletionRequest and return streaming or full response', 'create a streaming chat completion response that yields SSE chunks token-by-token for real-time output', 'create a full non-streaming chat completion response returning the complete ChatCompletionResponse object', 'validate and preprocess a ChatCompletionRequest returning conversation messages and engine inputs', 'create OpenAI-style logprobs from token IDs and top logprobs for chat completion responses', 'create a DeltaMessage from harmony parser state during streaming chat completions', 'test extract_harmony_streaming_delta with token_states, prev_recipient, and include_reasoning parameters', 'refactor extract_harmony_streaming_delta to support grouping consecutive tokens by channel and recipient', 'review the TokenState NamedTuple with channel, recipient, and text fields', 'summarize the stream_harmony module that extracts DeltaMessage objects from harmony parser state']
```

Usage

```
{'create_create_chat_completion': 'create a fastapi endpoint that handles chat completion requests with streaming and JSON responses', 'create_create_batch_chat_completion': 'create a fastapi endpoint that processes batch chat completion requests and returns JSON responses', 'test_attach_router': 'test attaching the chat completion router to a fastapi application instance', 'review_chat': 'review the helper function that retrieves the OpenAIServingChat handler from the request app state', 'summarize_create_chat_completion': 'summarize the async chat completion endpoint that supports streaming, JSON, and error responses'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/chat_completion/protocol.py

Prompts

```
['create a fastapi endpoint that handles chat completion requests with streaming and JSON responses', 'create a fastapi endpoint that processes batch chat completion requests and returns JSON responses', 'test attaching the chat completion router to a fastapi application instance', 'review the helper function that retrieves the OpenAIServingChat handler from the request app state', 'summarize the async chat completion endpoint that supports streaming, JSON, and error responses', 'create a ChatCompletionRequest with messages, model, and sampling parameters for vLLM chat completion API', 'build SamplingParams from a ChatCompletionRequest including temperature, top_p, and structured output configuration', 'validate a ChatCompletionRequest ensuring tool_choice matches tools, logprobs flags are consistent, and response_format is correct', 'create a BatchChatCompletionRequest to process multiple independent conversations in a single API call', 'build ChatParams from a ChatCompletionRequest with chat template, documents, and reasoning effort settings', 'create a chat completion using OpenAIServingChat with a ChatCompletionRequest and return streaming or full response', 'create a streaming chat completion response that yields SSE chunks token-by-token for real-time output', 'create a full non-streaming chat completion response returning the complete ChatCompletionResponse object', 'validate and preprocess a ChatCompletionRequest returning conversation messages and engine inputs', 'create OpenAI-style logprobs from token IDs and top logprobs for chat completion responses', 'create a DeltaMessage from harmony parser state during streaming chat completions', 'test extract_harmony_streaming_delta with token_states, prev_recipient, and include_reasoning parameters', 'refactor extract_harmony_streaming_delta to support grouping consecutive tokens by channel and recipient', 'review the TokenState NamedTuple with channel, recipient, and text fields', 'summarize the stream_harmony module that extracts DeltaMessage objects from harmony parser state']
```

Usage

```
{'create_chat_completion_request': 'create a ChatCompletionRequest with messages, model, and sampling parameters for vLLM chat completion API', 'build_sampling_params': 'build SamplingParams from a ChatCompletionRequest including temperature, top_p, and structured output configuration', 'validate_chat_completion_request': 'validate a ChatCompletionRequest ensuring tool_choice matches tools, logprobs flags are consistent, and response_format is correct', 'create_batch_chat_completion_request': 'create a BatchChatCompletionRequest to process multiple independent conversations in a single API call', 'build_chat_params': 'build ChatParams from a ChatCompletionRequest with chat template, documents, and reasoning effort settings'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/chat_completion/serving.py

Prompts

```
['create a fastapi endpoint that handles chat completion requests with streaming and JSON responses', 'create a fastapi endpoint that processes batch chat completion requests and returns JSON responses', 'test attaching the chat completion router to a fastapi application instance', 'review the helper function that retrieves the OpenAIServingChat handler from the request app state', 'summarize the async chat completion endpoint that supports streaming, JSON, and error responses', 'create a ChatCompletionRequest with messages, model, and sampling parameters for vLLM chat completion API', 'build SamplingParams from a ChatCompletionRequest including temperature, top_p, and structured output configuration', 'validate a ChatCompletionRequest ensuring tool_choice matches tools, logprobs flags are consistent, and response_format is correct', 'create a BatchChatCompletionRequest to process multiple independent conversations in a single API call', 'build ChatParams from a ChatCompletionRequest with chat template, documents, and reasoning effort settings', 'create a chat completion using OpenAIServingChat with a ChatCompletionRequest and return streaming or full response', 'create a streaming chat completion response that yields SSE chunks token-by-token for real-time output', 'create a full non-streaming chat completion response returning the complete ChatCompletionResponse object', 'validate and preprocess a ChatCompletionRequest returning conversation messages and engine inputs', 'create OpenAI-style logprobs from token IDs and top logprobs for chat completion responses', 'create a DeltaMessage from harmony parser state during streaming chat completions', 'test extract_harmony_streaming_delta with token_states, prev_recipient, and include_reasoning parameters', 'refactor extract_harmony_streaming_delta to support grouping consecutive tokens by channel and recipient', 'review the TokenState NamedTuple with channel, recipient, and text fields', 'summarize the stream_harmony module that extracts DeltaMessage objects from harmony parser state']
```

Usage

```
{'create_chat_completion': 'create a chat completion using OpenAIServingChat with a ChatCompletionRequest and return streaming or full response', 'create_chat_completion_stream': 'create a streaming chat completion response that yields SSE chunks token-by-token for real-time output', 'create_chat_completion_full': 'create a full non-streaming chat completion response returning the complete ChatCompletionResponse object', 'render_chat_request': 'validate and preprocess a ChatCompletionRequest returning conversation messages and engine inputs', 'create_chat_logprobs': 'create OpenAI-style logprobs from token IDs and top logprobs for chat completion responses'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/chat_completion/stream_harmony.py

Prompts

```
['create a fastapi endpoint that handles chat completion requests with streaming and JSON responses', 'create a fastapi endpoint that processes batch chat completion requests and returns JSON responses', 'test attaching the chat completion router to a fastapi application instance', 'review the helper function that retrieves the OpenAIServingChat handler from the request app state', 'summarize the async chat completion endpoint that supports streaming, JSON, and error responses', 'create a ChatCompletionRequest with messages, model, and sampling parameters for vLLM chat completion API', 'build SamplingParams from a ChatCompletionRequest including temperature, top_p, and structured output configuration', 'validate a ChatCompletionRequest ensuring tool_choice matches tools, logprobs flags are consistent, and response_format is correct', 'create a BatchChatCompletionRequest to process multiple independent conversations in a single API call', 'build ChatParams from a ChatCompletionRequest with chat template, documents, and reasoning effort settings', 'create a chat completion using OpenAIServingChat with a ChatCompletionRequest and return streaming or full response', 'create a streaming chat completion response that yields SSE chunks token-by-token for real-time output', 'create a full non-streaming chat completion response returning the complete ChatCompletionResponse object', 'validate and preprocess a ChatCompletionRequest returning conversation messages and engine inputs', 'create OpenAI-style logprobs from token IDs and top logprobs for chat completion responses', 'create a DeltaMessage from harmony parser state during streaming chat completions', 'test extract_harmony_streaming_delta with token_states, prev_recipient, and include_reasoning parameters', 'refactor extract_harmony_streaming_delta to support grouping consecutive tokens by channel and recipient', 'review the TokenState NamedTuple with channel, recipient, and text fields', 'summarize the stream_harmony module that extracts DeltaMessage objects from harmony parser state']
```

Usage

```
{'create_extract_harmony_streaming_delta': 'create a DeltaMessage from harmony parser state during streaming chat completions', 'test_extract_harmony_streaming_delta': 'test extract_harmony_streaming_delta with token_states, prev_recipient, and include_reasoning parameters', 'refactor_extract_harmony_streaming_delta': 'refactor extract_harmony_streaming_delta to support grouping consecutive tokens by channel and recipient', 'review_TokenState': 'review the TokenState NamedTuple with channel, recipient, and text fields', 'summarize_stream_harmony': 'summarize the stream_harmony module that extracts DeltaMessage objects from harmony parser state'}
```


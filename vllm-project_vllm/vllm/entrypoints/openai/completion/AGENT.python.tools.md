# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/entrypoints/openai/completion/api_router.py

Prompts

```
['create a POST endpoint at /v1/completions that handles OpenAI-style text completion requests with streaming support', 'build a FastAPI router that attaches OpenAI-compatible completion endpoints to an application', 'test the create_completion endpoint handles CompletionRequest and returns JSON or streaming responses', 'review the attach_router function that mounts the completion router onto a FastAPI app', 'summarize the completion dependency function that retrieves the OpenAIServingCompletion handler from request state', 'build a CompletionRequest with prompt, model, max_tokens, and temperature for text completion', 'build SamplingParams from a CompletionRequest with max_tokens and optional default sampling parameters', 'build BeamSearchParams from a CompletionRequest with max_tokens and default sampling parameters', 'build a CompletionResponse with model, choices, and usage info for text completion API', 'validate response_format field ensuring json_schema type includes required json_schema parameter', 'create a streaming completion response generator that yields SSE chunks with token deltas and usage info', 'render and validate an OpenAI completion request returning engine inputs or an error response', 'convert vLLM request output objects into an OpenAI-compatible completion response with choices and usage', 'create OpenAI-format logprobs with tokens, token logprobs, top logprobs, and text offsets']
```

Usage

```
{'create_completion': 'create a POST endpoint at /v1/completions that handles OpenAI-style text completion requests with streaming support', 'build_restapi_router': 'build a FastAPI router that attaches OpenAI-compatible completion endpoints to an application', 'test_create_completion': 'test the create_completion endpoint handles CompletionRequest and returns JSON or streaming responses', 'review_attach_router': 'review the attach_router function that mounts the completion router onto a FastAPI app', 'summarize_completion': 'summarize the completion dependency function that retrieves the OpenAIServingCompletion handler from request state'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/completion/protocol.py

Prompts

```
['create a POST endpoint at /v1/completions that handles OpenAI-style text completion requests with streaming support', 'build a FastAPI router that attaches OpenAI-compatible completion endpoints to an application', 'test the create_completion endpoint handles CompletionRequest and returns JSON or streaming responses', 'review the attach_router function that mounts the completion router onto a FastAPI app', 'summarize the completion dependency function that retrieves the OpenAIServingCompletion handler from request state', 'build a CompletionRequest with prompt, model, max_tokens, and temperature for text completion', 'build SamplingParams from a CompletionRequest with max_tokens and optional default sampling parameters', 'build BeamSearchParams from a CompletionRequest with max_tokens and default sampling parameters', 'build a CompletionResponse with model, choices, and usage info for text completion API', 'validate response_format field ensuring json_schema type includes required json_schema parameter', 'create a streaming completion response generator that yields SSE chunks with token deltas and usage info', 'render and validate an OpenAI completion request returning engine inputs or an error response', 'convert vLLM request output objects into an OpenAI-compatible completion response with choices and usage', 'create OpenAI-format logprobs with tokens, token logprobs, top logprobs, and text offsets']
```

Usage

```
{'build_completion_request': 'build a CompletionRequest with prompt, model, max_tokens, and temperature for text completion', 'build_sampling_params': 'build SamplingParams from a CompletionRequest with max_tokens and optional default sampling parameters', 'build_beam_search_params': 'build BeamSearchParams from a CompletionRequest with max_tokens and default sampling parameters', 'build_completion_response': 'build a CompletionResponse with model, choices, and usage info for text completion API', 'validate_response_format': 'validate response_format field ensuring json_schema type includes required json_schema parameter'}
```

## File: vllm-project_vllm/vllm/entrypoints/openai/completion/serving.py

Prompts

```
['create a POST endpoint at /v1/completions that handles OpenAI-style text completion requests with streaming support', 'build a FastAPI router that attaches OpenAI-compatible completion endpoints to an application', 'test the create_completion endpoint handles CompletionRequest and returns JSON or streaming responses', 'review the attach_router function that mounts the completion router onto a FastAPI app', 'summarize the completion dependency function that retrieves the OpenAIServingCompletion handler from request state', 'build a CompletionRequest with prompt, model, max_tokens, and temperature for text completion', 'build SamplingParams from a CompletionRequest with max_tokens and optional default sampling parameters', 'build BeamSearchParams from a CompletionRequest with max_tokens and default sampling parameters', 'build a CompletionResponse with model, choices, and usage info for text completion API', 'validate response_format field ensuring json_schema type includes required json_schema parameter', 'create a streaming completion response generator that yields SSE chunks with token deltas and usage info', 'render and validate an OpenAI completion request returning engine inputs or an error response', 'convert vLLM request output objects into an OpenAI-compatible completion response with choices and usage', 'create OpenAI-format logprobs with tokens, token logprobs, top logprobs, and text offsets']
```

Usage

```
{'create_completion': 'create a vLLM OpenAI-compatible completion API that supports streaming and non-streaming text generation', 'create_completion_stream_generator': 'create a streaming completion response generator that yields SSE chunks with token deltas and usage info', 'render_completion_request': 'render and validate an OpenAI completion request returning engine inputs or an error response', 'request_output_to_completion_response': 'convert vLLM request output objects into an OpenAI-compatible completion response with choices and usage', 'create_completion_logprobs': 'create OpenAI-format logprobs with tokens, token logprobs, top logprobs, and text offsets'}
```


# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/clients/python/text_generation/client.py

Prompts

```
['create a python client to generate text from a TGI instance using the synchronous generate method', 'build an async python client to stream generated tokens from a TGI instance using generate_stream', 'create a python client to send chat messages to a TGI instance using the synchronous chat method', 'build a python client to call the OpenAI-compatible completions API on a TGI instance', 'create a python client to use tool calling with the chat completions API on a TGI instance', 'parse an HTTP status code and JSON payload into the appropriate text generation inference exception', 'catch and handle a GenerationError exception when text generation fails on the server', 'catch and handle a ValidationError exception when the request input is invalid', 'catch and handle an OverloadedError exception when the inference server is overloaded', 'catch and handle a RateLimitExceededError exception when the API rate limit is exceeded', 'create an InferenceAPIClient for a HuggingFace model repo_id to generate text', 'create an InferenceAPIAsyncClient for a HuggingFace model repo_id to generate text asynchronously', 'use InferenceAPIClient to generate text from a prompt and get the generated_text result', 'use InferenceAPIClient to stream token-by-token text generation responses from a prompt', 'check if a HuggingFace model repo_id is supported by text-generation-inference', 'create a ChatRequest with messages, model, temperature, and max_tokens for chat completion', 'create a CompletionRequest with a prompt, model, and sampling parameters for text generation', 'build a Parameters object with sampling settings like temperature, top_p, and repetition_penalty', 'create a Request with inputs and stream flag to generate text with optional streaming', 'configure a Grammar object with json or regex type to constrain model output format']
```

Usage

```
{'generate_text_sync': 'create a python client to generate text from a TGI instance using the synchronous generate method', 'stream_text_async': 'build an async python client to stream generated tokens from a TGI instance using generate_stream', 'chat_completion_sync': 'create a python client to send chat messages to a TGI instance using the synchronous chat method', 'completion_api_sync': 'build a python client to call the OpenAI-compatible completions API on a TGI instance', 'chat_with_tools': 'create a python client to use tool calling with the chat completions API on a TGI instance'}
```

## File: huggingface_text-generation-inference/clients/python/text_generation/errors.py

Prompts

```
['create a python client to generate text from a TGI instance using the synchronous generate method', 'build an async python client to stream generated tokens from a TGI instance using generate_stream', 'create a python client to send chat messages to a TGI instance using the synchronous chat method', 'build a python client to call the OpenAI-compatible completions API on a TGI instance', 'create a python client to use tool calling with the chat completions API on a TGI instance', 'parse an HTTP status code and JSON payload into the appropriate text generation inference exception', 'catch and handle a GenerationError exception when text generation fails on the server', 'catch and handle a ValidationError exception when the request input is invalid', 'catch and handle an OverloadedError exception when the inference server is overloaded', 'catch and handle a RateLimitExceededError exception when the API rate limit is exceeded', 'create an InferenceAPIClient for a HuggingFace model repo_id to generate text', 'create an InferenceAPIAsyncClient for a HuggingFace model repo_id to generate text asynchronously', 'use InferenceAPIClient to generate text from a prompt and get the generated_text result', 'use InferenceAPIClient to stream token-by-token text generation responses from a prompt', 'check if a HuggingFace model repo_id is supported by text-generation-inference', 'create a ChatRequest with messages, model, temperature, and max_tokens for chat completion', 'create a CompletionRequest with a prompt, model, and sampling parameters for text generation', 'build a Parameters object with sampling settings like temperature, top_p, and repetition_penalty', 'create a Request with inputs and stream flag to generate text with optional streaming', 'configure a Grammar object with json or regex type to constrain model output format']
```

Usage

```
{'parse_error_from_status_code': 'parse an HTTP status code and JSON payload into the appropriate text generation inference exception', 'handle_generation_error': 'catch and handle a GenerationError exception when text generation fails on the server', 'handle_validation_error': 'catch and handle a ValidationError exception when the request input is invalid', 'handle_overloaded_error': 'catch and handle an OverloadedError exception when the inference server is overloaded', 'handle_rate_limit_error': 'catch and handle a RateLimitExceededError exception when the API rate limit is exceeded'}
```

## File: huggingface_text-generation-inference/clients/python/text_generation/inference_api.py

Prompts

```
['create a python client to generate text from a TGI instance using the synchronous generate method', 'build an async python client to stream generated tokens from a TGI instance using generate_stream', 'create a python client to send chat messages to a TGI instance using the synchronous chat method', 'build a python client to call the OpenAI-compatible completions API on a TGI instance', 'create a python client to use tool calling with the chat completions API on a TGI instance', 'parse an HTTP status code and JSON payload into the appropriate text generation inference exception', 'catch and handle a GenerationError exception when text generation fails on the server', 'catch and handle a ValidationError exception when the request input is invalid', 'catch and handle an OverloadedError exception when the inference server is overloaded', 'catch and handle a RateLimitExceededError exception when the API rate limit is exceeded', 'create an InferenceAPIClient for a HuggingFace model repo_id to generate text', 'create an InferenceAPIAsyncClient for a HuggingFace model repo_id to generate text asynchronously', 'use InferenceAPIClient to generate text from a prompt and get the generated_text result', 'use InferenceAPIClient to stream token-by-token text generation responses from a prompt', 'check if a HuggingFace model repo_id is supported by text-generation-inference', 'create a ChatRequest with messages, model, temperature, and max_tokens for chat completion', 'create a CompletionRequest with a prompt, model, and sampling parameters for text generation', 'build a Parameters object with sampling settings like temperature, top_p, and repetition_penalty', 'create a Request with inputs and stream flag to generate text with optional streaming', 'configure a Grammar object with json or regex type to constrain model output format']
```

Usage

```
{'create_InferenceAPIClient': 'create an InferenceAPIClient for a HuggingFace model repo_id to generate text', 'create_InferenceAPIAsyncClient': 'create an InferenceAPIAsyncClient for a HuggingFace model repo_id to generate text asynchronously', 'generate_text': 'use InferenceAPIClient to generate text from a prompt and get the generated_text result', 'generate_stream': 'use InferenceAPIClient to stream token-by-token text generation responses from a prompt', 'check_model_support': 'check if a HuggingFace model repo_id is supported by text-generation-inference'}
```

## File: huggingface_text-generation-inference/clients/python/text_generation/types.py

Prompts

```
['create a python client to generate text from a TGI instance using the synchronous generate method', 'build an async python client to stream generated tokens from a TGI instance using generate_stream', 'create a python client to send chat messages to a TGI instance using the synchronous chat method', 'build a python client to call the OpenAI-compatible completions API on a TGI instance', 'create a python client to use tool calling with the chat completions API on a TGI instance', 'parse an HTTP status code and JSON payload into the appropriate text generation inference exception', 'catch and handle a GenerationError exception when text generation fails on the server', 'catch and handle a ValidationError exception when the request input is invalid', 'catch and handle an OverloadedError exception when the inference server is overloaded', 'catch and handle a RateLimitExceededError exception when the API rate limit is exceeded', 'create an InferenceAPIClient for a HuggingFace model repo_id to generate text', 'create an InferenceAPIAsyncClient for a HuggingFace model repo_id to generate text asynchronously', 'use InferenceAPIClient to generate text from a prompt and get the generated_text result', 'use InferenceAPIClient to stream token-by-token text generation responses from a prompt', 'check if a HuggingFace model repo_id is supported by text-generation-inference', 'create a ChatRequest with messages, model, temperature, and max_tokens for chat completion', 'create a CompletionRequest with a prompt, model, and sampling parameters for text generation', 'build a Parameters object with sampling settings like temperature, top_p, and repetition_penalty', 'create a Request with inputs and stream flag to generate text with optional streaming', 'configure a Grammar object with json or regex type to constrain model output format']
```

Usage

```
{'create_chat_request': 'create a ChatRequest with messages, model, temperature, and max_tokens for chat completion', 'create_completion_request': 'create a CompletionRequest with a prompt, model, and sampling parameters for text generation', 'build_parameters_with_validators': 'build a Parameters object with sampling settings like temperature, top_p, and repetition_penalty', 'create_request_with_streaming': 'create a Request with inputs and stream flag to generate text with optional streaming', 'configure_grammar_constrained_generation': 'configure a Grammar object with json or regex type to constrain model output format'}
```


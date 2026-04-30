# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/groq/chat/handler.py

Prompts

```
['create a GroqChatCompletion instance to handle chat completion requests for Groq models', 'build a chat completion request for Groq with messages, model, and optional streaming parameters', 'transform Groq chat messages using GroqChatConfig._transform_messages before sending to the API', 'test Groq chat completion with streaming enabled and fake_stream handling via GroqChatConfig._should_fake_stream', 'review the GroqChatCompletion.completion method that transforms messages and delegates to the parent OpenAI-like handler', 'create a GroqChatConfig instance with parameters like frequency_penalty, max_tokens, tools, and response_format for Groq API calls', 'build OpenAI-compatible params for Groq using GroqChatConfig.map_openai_params with JSON schema workaround for models without native structured outputs', 'test whether to fake streaming via GroqChatConfig._should_fake_stream when response_format is set since Groq does not support it while streaming', "review GroqChatCompletionStreamingHandler.chunk_parser that maps Groq's reasoning field to LiteLLM's reasoning_content in streaming chunks"]
```

Usage

```
{'create_GroqChatCompletion': 'create a GroqChatCompletion instance to handle chat completion requests for Groq models', 'build_completion_request': 'build a chat completion request for Groq with messages, model, and optional streaming parameters', 'transform_Groq_messages': 'transform Groq chat messages using GroqChatConfig._transform_messages before sending to the API', 'test_Groq_streaming': 'test Groq chat completion with streaming enabled and fake_stream handling via GroqChatConfig._should_fake_stream', 'review_GroqChatCompletion_completion': 'review the GroqChatCompletion.completion method that transforms messages and delegates to the parent OpenAI-like handler'}
```

## File: berriai_litellm/litellm/llms/groq/chat/transformation.py

Prompts

```
['create a GroqChatCompletion instance to handle chat completion requests for Groq models', 'build a chat completion request for Groq with messages, model, and optional streaming parameters', 'transform Groq chat messages using GroqChatConfig._transform_messages before sending to the API', 'test Groq chat completion with streaming enabled and fake_stream handling via GroqChatConfig._should_fake_stream', 'review the GroqChatCompletion.completion method that transforms messages and delegates to the parent OpenAI-like handler', 'create a GroqChatConfig instance with parameters like frequency_penalty, max_tokens, tools, and response_format for Groq API calls', 'build OpenAI-compatible params for Groq using GroqChatConfig.map_openai_params with JSON schema workaround for models without native structured outputs', 'test whether to fake streaming via GroqChatConfig._should_fake_stream when response_format is set since Groq does not support it while streaming', "review GroqChatCompletionStreamingHandler.chunk_parser that maps Groq's reasoning field to LiteLLM's reasoning_content in streaming chunks"]
```

Usage

```
{'create_GroqChatConfig': 'create a GroqChatConfig instance with parameters like frequency_penalty, max_tokens, tools, and response_format for Groq API calls', 'build_Groq_params': 'build OpenAI-compatible params for Groq using GroqChatConfig.map_openai_params with JSON schema workaround for models without native structured outputs', 'transform_Groq_messages': 'transform chat messages with GroqChatConfig._transform_messages to strip null function_call from assistant messages before sending to Groq', 'test_Groq_fake_stream': 'test whether to fake streaming via GroqChatConfig._should_fake_stream when response_format is set since Groq does not support it while streaming', 'review_GroqStreamingHandler': "review GroqChatCompletionStreamingHandler.chunk_parser that maps Groq's reasoning field to LiteLLM's reasoning_content in streaming chunks"}
```


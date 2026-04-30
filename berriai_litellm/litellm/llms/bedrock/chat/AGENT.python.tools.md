# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/bedrock/chat/converse_handler.py

Prompts

```
['build a BedrockConverseLLM instance to call AWS Bedrock models via the Converse API', 'create a synchronous streaming call to AWS Bedrock Converse using make_sync_call with event stream decoding', 'test the async_streaming method that transforms requests and streams responses from Bedrock Converse', 'refactor the completion method to route between sync, async, and streaming Bedrock Converse calls', 'review the async_completion method that handles non-streaming async requests to AWS Bedrock Converse', 'build a function that maps OpenAI chat completion parameters to Amazon Bedrock Converse API format', 'create a function that transforms OpenAI chat messages and params into Bedrock Converse request format', 'test the function that converts a Bedrock Converse HTTP response back to OpenAI ChatCompletionMessage format', 'refactor the function that translates response_format json_schema into Bedrock native structured outputs or synthetic tool calls', 'summarize the function that returns which OpenAI parameters are supported by a given Bedrock model', 'run a bedrock LLM completion call with messages, model, and optional streaming parameters', 'create an async streaming response wrapper for bedrock LLM with partial function invocation', 'parse bedrock event stream chunks into model response streams using the aws event stream decoder', 'configure cohere chat model parameters for bedrock invoke with temperature, stop sequences, and max tokens', 'decode anthropic claude streaming responses from bedrock event stream into model response chunks']
```

Usage

```
{'build_bedrock_converse_client': 'build a BedrockConverseLLM instance to call AWS Bedrock models via the Converse API', 'create_sync_streaming_call': 'create a synchronous streaming call to AWS Bedrock Converse using make_sync_call with event stream decoding', 'test_async_streaming': 'test the async_streaming method that transforms requests and streams responses from Bedrock Converse', 'refactor_completion_routing': 'refactor the completion method to route between sync, async, and streaming Bedrock Converse calls', 'review_async_completion': 'review the async_completion method that handles non-streaming async requests to AWS Bedrock Converse'}
```

## File: berriai_litellm/litellm/llms/bedrock/chat/converse_transformation.py

Prompts

```
['build a BedrockConverseLLM instance to call AWS Bedrock models via the Converse API', 'create a synchronous streaming call to AWS Bedrock Converse using make_sync_call with event stream decoding', 'test the async_streaming method that transforms requests and streams responses from Bedrock Converse', 'refactor the completion method to route between sync, async, and streaming Bedrock Converse calls', 'review the async_completion method that handles non-streaming async requests to AWS Bedrock Converse', 'build a function that maps OpenAI chat completion parameters to Amazon Bedrock Converse API format', 'create a function that transforms OpenAI chat messages and params into Bedrock Converse request format', 'test the function that converts a Bedrock Converse HTTP response back to OpenAI ChatCompletionMessage format', 'refactor the function that translates response_format json_schema into Bedrock native structured outputs or synthetic tool calls', 'summarize the function that returns which OpenAI parameters are supported by a given Bedrock model', 'run a bedrock LLM completion call with messages, model, and optional streaming parameters', 'create an async streaming response wrapper for bedrock LLM with partial function invocation', 'parse bedrock event stream chunks into model response streams using the aws event stream decoder', 'configure cohere chat model parameters for bedrock invoke with temperature, stop sequences, and max tokens', 'decode anthropic claude streaming responses from bedrock event stream into model response chunks']
```

Usage

```
{'build_map_openai_params': 'build a function that maps OpenAI chat completion parameters to Amazon Bedrock Converse API format', 'create_transform_request': 'create a function that transforms OpenAI chat messages and params into Bedrock Converse request format', 'test_transform_response': 'test the function that converts a Bedrock Converse HTTP response back to OpenAI ChatCompletionMessage format', 'refactor_translate_response_format': 'refactor the function that translates response_format json_schema into Bedrock native structured outputs or synthetic tool calls', 'summarize_get_supported_openai_params': 'summarize the function that returns which OpenAI parameters are supported by a given Bedrock model'}
```

## File: berriai_litellm/litellm/llms/bedrock/chat/invoke_handler.py

Prompts

```
['build a BedrockConverseLLM instance to call AWS Bedrock models via the Converse API', 'create a synchronous streaming call to AWS Bedrock Converse using make_sync_call with event stream decoding', 'test the async_streaming method that transforms requests and streams responses from Bedrock Converse', 'refactor the completion method to route between sync, async, and streaming Bedrock Converse calls', 'review the async_completion method that handles non-streaming async requests to AWS Bedrock Converse', 'build a function that maps OpenAI chat completion parameters to Amazon Bedrock Converse API format', 'create a function that transforms OpenAI chat messages and params into Bedrock Converse request format', 'test the function that converts a Bedrock Converse HTTP response back to OpenAI ChatCompletionMessage format', 'refactor the function that translates response_format json_schema into Bedrock native structured outputs or synthetic tool calls', 'summarize the function that returns which OpenAI parameters are supported by a given Bedrock model', 'run a bedrock LLM completion call with messages, model, and optional streaming parameters', 'create an async streaming response wrapper for bedrock LLM with partial function invocation', 'parse bedrock event stream chunks into model response streams using the aws event stream decoder', 'configure cohere chat model parameters for bedrock invoke with temperature, stop sequences, and max tokens', 'decode anthropic claude streaming responses from bedrock event stream into model response chunks']
```

Usage

```
{'run_bedrock_completion': 'run a bedrock LLM completion call with messages, model, and optional streaming parameters', 'create_bedrock_async_streaming': 'create an async streaming response wrapper for bedrock LLM with partial function invocation', 'parse_bedrock_event_stream': 'parse bedrock event stream chunks into model response streams using the aws event stream decoder', 'configure_cohere_chat_params': 'configure cohere chat model parameters for bedrock invoke with temperature, stop sequences, and max tokens', 'decode_anthropic_claude_stream': 'decode anthropic claude streaming responses from bedrock event stream into model response chunks'}
```


# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/a2a/chat/streaming_iterator.py

Prompts

```
['create an A2AModelResponseIterator to parse A2A JSON-RPC streaming chunks into OpenAI-compatible format', 'parse an A2A streaming chunk dictionary into a GenericStreamingChunk with extracted text and finish reason', 'extract the finish reason from an A2A chunk by checking task status states like completed or failed', 'test the chunk_parser method with sample A2A JSON-RPC response chunks containing text parts', 'review the A2AModelResponseIterator class and its conversion of A2A streaming responses to OpenAI format', 'transform OpenAI chat messages into A2A JSON-RPC 2.0 request format', 'transform A2A JSON-RPC response into OpenAI ModelResponse format', 'resolve agent api_base, api_key, and headers from the agent registry', 'get a streaming iterator for A2A model responses', 'validate environment and set Content-Type and Authorization headers for A2A requests']
```

Usage

```
{'create_a2a_iterator': 'create an A2AModelResponseIterator to parse A2A JSON-RPC streaming chunks into OpenAI-compatible format', 'parse_a2a_chunk': 'parse an A2A streaming chunk dictionary into a GenericStreamingChunk with extracted text and finish reason', 'extract_finish_reason': 'extract the finish reason from an A2A chunk by checking task status states like completed or failed', 'test_chunk_parser': 'test the chunk_parser method with sample A2A JSON-RPC response chunks containing text parts', 'review_a2a_iterator': 'review the A2AModelResponseIterator class and its conversion of A2A streaming responses to OpenAI format'}
```

## File: berriai_litellm/litellm/llms/a2a/chat/transformation.py

Prompts

```
['create an A2AModelResponseIterator to parse A2A JSON-RPC streaming chunks into OpenAI-compatible format', 'parse an A2A streaming chunk dictionary into a GenericStreamingChunk with extracted text and finish reason', 'extract the finish reason from an A2A chunk by checking task status states like completed or failed', 'test the chunk_parser method with sample A2A JSON-RPC response chunks containing text parts', 'review the A2AModelResponseIterator class and its conversion of A2A streaming responses to OpenAI format', 'transform OpenAI chat messages into A2A JSON-RPC 2.0 request format', 'transform A2A JSON-RPC response into OpenAI ModelResponse format', 'resolve agent api_base, api_key, and headers from the agent registry', 'get a streaming iterator for A2A model responses', 'validate environment and set Content-Type and Authorization headers for A2A requests']
```

Usage

```
{'transform_request_openai_to_a2a': 'transform OpenAI chat messages into A2A JSON-RPC 2.0 request format', 'transform_response_a2a_to_openai': 'transform A2A JSON-RPC response into OpenAI ModelResponse format', 'resolve_agent_config_from_registry': 'resolve agent api_base, api_key, and headers from the agent registry', 'get_model_response_iterator': 'get a streaming iterator for A2A model responses', 'validate_environment_headers': 'validate environment and set Content-Type and Authorization headers for A2A requests'}
```


# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/agent_engine/sse_iterator.py

Prompts

```
['create a VertexAgentEngineResponseIterator to handle SSE streaming responses from Vertex AI Agent Engine', 'parse a Vertex Agent Engine SSE chunk into an OpenAI-compatible ModelResponseStream using chunk_parser', 'extract text content from Vertex Agent Engine response parts in a streaming chunk', 'map Vertex Agent Engine finish_reason values like STOP to OpenAI-compatible lowercase finish_reason strings', 'extract prompt, completion, and total token counts from Vertex Agent Engine usage_metadata into ChatCompletionUsageBlock', 'transform OpenAI-compatible chat messages into Vertex Agent Engine request payload format', 'transform Vertex Agent Engine SSE response into LiteLLM ModelResponse format', 'get an async custom stream wrapper for streaming Vertex Agent Engine responses', 'build the complete Vertex Agent Engine API URL from model string and project configuration', 'validate the Vertex Agent Engine environment and set up authentication headers']
```

Usage

```
{'create_VertexAgentEngineResponseIterator': 'create a VertexAgentEngineResponseIterator to handle SSE streaming responses from Vertex AI Agent Engine', 'parse_chunk_parser': 'parse a Vertex Agent Engine SSE chunk into an OpenAI-compatible ModelResponseStream using chunk_parser', 'extract_text_from_parts': 'extract text content from Vertex Agent Engine response parts in a streaming chunk', 'map_finish_reason': 'map Vertex Agent Engine finish_reason values like STOP to OpenAI-compatible lowercase finish_reason strings', 'extract_usage_metadata': 'extract prompt, completion, and total token counts from Vertex Agent Engine usage_metadata into ChatCompletionUsageBlock'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/agent_engine/transformation.py

Prompts

```
['create a VertexAgentEngineResponseIterator to handle SSE streaming responses from Vertex AI Agent Engine', 'parse a Vertex Agent Engine SSE chunk into an OpenAI-compatible ModelResponseStream using chunk_parser', 'extract text content from Vertex Agent Engine response parts in a streaming chunk', 'map Vertex Agent Engine finish_reason values like STOP to OpenAI-compatible lowercase finish_reason strings', 'extract prompt, completion, and total token counts from Vertex Agent Engine usage_metadata into ChatCompletionUsageBlock', 'transform OpenAI-compatible chat messages into Vertex Agent Engine request payload format', 'transform Vertex Agent Engine SSE response into LiteLLM ModelResponse format', 'get an async custom stream wrapper for streaming Vertex Agent Engine responses', 'build the complete Vertex Agent Engine API URL from model string and project configuration', 'validate the Vertex Agent Engine environment and set up authentication headers']
```

Usage

```
{'transform_request_vertex_agent_engine': 'transform OpenAI-compatible chat messages into Vertex Agent Engine request payload format', 'transform_response_vertex_agent_engine': 'transform Vertex Agent Engine SSE response into LiteLLM ModelResponse format', 'get_async_custom_stream_wrapper': 'get an async custom stream wrapper for streaming Vertex Agent Engine responses', 'get_complete_url_vertex_agent_engine': 'build the complete Vertex Agent Engine API URL from model string and project configuration', 'validate_environment_vertex_agent_engine': 'validate the Vertex Agent Engine environment and set up authentication headers'}
```


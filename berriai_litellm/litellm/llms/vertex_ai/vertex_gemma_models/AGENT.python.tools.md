# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/vertex_gemma_models/main.py

Prompts

```
['build a Vertex AI Gemma model completion handler that wraps messages in instances with chatCompletions request format', 'test that Vertex AI Gemma models require an explicit api_base endpoint URL parameter', 'review that Vertex AI Gemma models do not support streaming and use fake streaming client-side', 'summarize how VertexGemmaConfig transforms OpenAI-compatible requests into Vertex Gemma instances format', 'run the VertexGemmaConfig response unwrapper to extract predictions from Vertex AI Gemma API responses', 'transform chat messages to Vertex Gemma format with instances wrapper and @requestFormat', 'run a sync or async completion request to a Vertex Gemma endpoint with streaming support', 'run a synchronous HTTP completion request to Vertex Gemma with Bearer token authentication', 'run an asynchronous HTTP completion request to Vertex Gemma using async httpx client', 'unwrap Vertex Gemma predictions response to extract the OpenAI-compatible inner response']
```

Usage

```
{'build_vertex_ai_gemma_completion': 'build a Vertex AI Gemma model completion handler that wraps messages in instances with chatCompletions request format', 'test_vertex_ai_gemma_api_base_required': 'test that Vertex AI Gemma models require an explicit api_base endpoint URL parameter', 'review_vertex_ai_gemma_streaming': 'review that Vertex AI Gemma models do not support streaming and use fake streaming client-side', 'summarize_vertex_ai_gemma_request_transform': 'summarize how VertexGemmaConfig transforms OpenAI-compatible requests into Vertex Gemma instances format', 'run_vertex_ai_gemma_response_unwrap': 'run the VertexGemmaConfig response unwrapper to extract predictions from Vertex AI Gemma API responses'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/vertex_gemma_models/transformation.py

Prompts

```
['build a Vertex AI Gemma model completion handler that wraps messages in instances with chatCompletions request format', 'test that Vertex AI Gemma models require an explicit api_base endpoint URL parameter', 'review that Vertex AI Gemma models do not support streaming and use fake streaming client-side', 'summarize how VertexGemmaConfig transforms OpenAI-compatible requests into Vertex Gemma instances format', 'run the VertexGemmaConfig response unwrapper to extract predictions from Vertex AI Gemma API responses', 'transform chat messages to Vertex Gemma format with instances wrapper and @requestFormat', 'run a sync or async completion request to a Vertex Gemma endpoint with streaming support', 'run a synchronous HTTP completion request to Vertex Gemma with Bearer token authentication', 'run an asynchronous HTTP completion request to Vertex Gemma using async httpx client', 'unwrap Vertex Gemma predictions response to extract the OpenAI-compatible inner response']
```

Usage

```
{'transform_request': 'transform chat messages to Vertex Gemma format with instances wrapper and @requestFormat', 'completion': 'run a sync or async completion request to a Vertex Gemma endpoint with streaming support', '_sync_completion': 'run a synchronous HTTP completion request to Vertex Gemma with Bearer token authentication', '_async_completion': 'run an asynchronous HTTP completion request to Vertex Gemma using async httpx client', '_unwrap_predictions_response': 'unwrap Vertex Gemma predictions response to extract the OpenAI-compatible inner response'}
```


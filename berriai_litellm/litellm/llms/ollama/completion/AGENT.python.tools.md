# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/ollama/completion/handler.py

Prompts

```
['build ollama embeddings by calling ollama_embeddings with api_base, model, and list of text prompts', 'run async ollama embeddings via ollama_aembeddings with api_base, model, and list of text prompts', 'test the _prepare_ollama_embedding_payload function to build a payload dict from model, prompts, and optional params', 'review the _process_ollama_embedding_response function to parse response JSON into an EmbeddingResponse object', 'summarize the ollama embedding handler module that prepares payloads and processes responses for Ollama /api/embed', 'map OpenAI parameters like max_tokens and temperature to Ollama parameters', 'transform litellm chat completion request into Ollama API format with prompt and options', 'transform Ollama API response into litellm ModelResponse with usage and message content', 'fetch Ollama model info including max tokens and function calling support from the API', 'parse streaming Ollama response chunks into ModelResponseStream with reasoning content support']
```

Usage

```
{'build_ollama_embeddings': 'build ollama embeddings by calling ollama_embeddings with api_base, model, and list of text prompts', 'run_ollama_aembeddings': 'run async ollama embeddings via ollama_aembeddings with api_base, model, and list of text prompts', 'test_prepare_ollama_embedding_payload': 'test the _prepare_ollama_embedding_payload function to build a payload dict from model, prompts, and optional params', 'review_process_ollama_embedding_response': 'review the _process_ollama_embedding_response function to parse response JSON into an EmbeddingResponse object', 'summarize_ollama_embedding_handler': 'summarize the ollama embedding handler module that prepares payloads and processes responses for Ollama /api/embed'}
```

## File: berriai_litellm/litellm/llms/ollama/completion/transformation.py

Prompts

```
['build ollama embeddings by calling ollama_embeddings with api_base, model, and list of text prompts', 'run async ollama embeddings via ollama_aembeddings with api_base, model, and list of text prompts', 'test the _prepare_ollama_embedding_payload function to build a payload dict from model, prompts, and optional params', 'review the _process_ollama_embedding_response function to parse response JSON into an EmbeddingResponse object', 'summarize the ollama embedding handler module that prepares payloads and processes responses for Ollama /api/embed', 'map OpenAI parameters like max_tokens and temperature to Ollama parameters', 'transform litellm chat completion request into Ollama API format with prompt and options', 'transform Ollama API response into litellm ModelResponse with usage and message content', 'fetch Ollama model info including max tokens and function calling support from the API', 'parse streaming Ollama response chunks into ModelResponseStream with reasoning content support']
```

Usage

```
{'map_openai_params_OllamaConfig': 'map OpenAI parameters like max_tokens and temperature to Ollama parameters', 'transform_request_OllamaConfig': 'transform litellm chat completion request into Ollama API format with prompt and options', 'transform_response_OllamaConfig': 'transform Ollama API response into litellm ModelResponse with usage and message content', 'get_model_info_OllamaConfig': 'fetch Ollama model info including max tokens and function calling support from the API', 'OllamaTextCompletionResponseIterator': 'parse streaming Ollama response chunks into ModelResponseStream with reasoning content support'}
```


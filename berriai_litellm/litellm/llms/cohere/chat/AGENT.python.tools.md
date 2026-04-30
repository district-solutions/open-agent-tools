# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/cohere/chat/transformation.py

Prompts

```
['transform OpenAI-format chat messages into Cohere API request parameters', 'map OpenAI chat completion params to Cohere API parameters like top_p to p and stop to stop_sequences', 'translate OpenAI function-calling tool definitions into Cohere parameter_definitions format', 'transform Cohere API response into OpenAI-compatible ModelResponse with usage and tool_calls', 'get a streaming response iterator for Cohere chat completions', 'create a CohereV2ChatConfig instance with model parameters like temperature, max_tokens, and seed', 'transform OpenAI-format chat request parameters to Cohere v2 API request format', 'transform a raw Cohere v2 HTTP response into a standardized OpenAI ModelResponse object', 'translate Cohere citation objects into OpenAI ChatCompletionAnnotation format with URL citations', 'get a streaming model response iterator for processing Cohere v2 chat completions']
```

Usage

```
{'transform_cohere_request': 'transform OpenAI-format chat messages into Cohere API request parameters', 'map_openai_params_to_cohere': 'map OpenAI chat completion params to Cohere API parameters like top_p to p and stop to stop_sequences', 'translate_openai_tool_to_cohere': 'translate OpenAI function-calling tool definitions into Cohere parameter_definitions format', 'transform_cohere_response': 'transform Cohere API response into OpenAI-compatible ModelResponse with usage and tool_calls', 'get_model_response_iterator': 'get a streaming response iterator for Cohere chat completions'}
```

## File: berriai_litellm/litellm/llms/cohere/chat/v2_transformation.py

Prompts

```
['transform OpenAI-format chat messages into Cohere API request parameters', 'map OpenAI chat completion params to Cohere API parameters like top_p to p and stop to stop_sequences', 'translate OpenAI function-calling tool definitions into Cohere parameter_definitions format', 'transform Cohere API response into OpenAI-compatible ModelResponse with usage and tool_calls', 'get a streaming response iterator for Cohere chat completions', 'create a CohereV2ChatConfig instance with model parameters like temperature, max_tokens, and seed', 'transform OpenAI-format chat request parameters to Cohere v2 API request format', 'transform a raw Cohere v2 HTTP response into a standardized OpenAI ModelResponse object', 'translate Cohere citation objects into OpenAI ChatCompletionAnnotation format with URL citations', 'get a streaming model response iterator for processing Cohere v2 chat completions']
```

Usage

```
{'create_CohereV2ChatConfig': 'create a CohereV2ChatConfig instance with model parameters like temperature, max_tokens, and seed', 'transform_CohereV2ChatConfig_request': 'transform OpenAI-format chat request parameters to Cohere v2 API request format', 'transform_CohereV2ChatConfig_response': 'transform a raw Cohere v2 HTTP response into a standardized OpenAI ModelResponse object', 'translate_citations_to_annotations': 'translate Cohere citation objects into OpenAI ChatCompletionAnnotation format with URL citations', 'get_CohereV2ChatConfig_model_response_iterator': 'get a streaming model response iterator for processing Cohere v2 chat completions'}
```


# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/openai/responses/transformation.py

Prompts

```
['transform OpenAI responses API request params into a validated dict with model and input', 'transform an httpx raw response into a ResponsesAPIResponse with processed headers', 'transform a parsed streaming response chunk into a typed ResponsesAPIStreamingResponse event', 'validate environment by resolving OpenAI API key and setting Authorization header', 'get the full OpenAI responses API endpoint URL from api_base configuration', 'build a DELETE request URL and empty data dict for deleting a response by ID', 'build a GET request URL and empty data dict for retrieving a response by ID', 'build a POST request URL and empty data dict for cancelling a running response', 'build a POST request URL and data dict for compacting a response context', 'build a GET request URL and pagination params for listing input items of a response', 'get the Pydantic event model class for a given streaming event type string', 'check whether to fake-stream a response when the model does not support native streaming', 'check whether the OpenAI responses API supports native WebSocket streaming', 'check whether the OpenAI responses API supports native file search', 'get the list of supported OpenAI parameters for a given model']
```

Usage

```
{'transform_responses_api_request': 'transform OpenAI responses API request params into a validated dict with model and input', 'transform_response_api_response': 'transform an httpx raw response into a ResponsesAPIResponse with processed headers', 'transform_streaming_response': 'transform a parsed streaming response chunk into a typed ResponsesAPIStreamingResponse event', 'validate_environment': 'validate environment by resolving OpenAI API key and setting Authorization header', 'get_complete_url': 'get the full OpenAI responses API endpoint URL from api_base configuration', 'transform_delete_response_api_request': 'build a DELETE request URL and empty data dict for deleting a response by ID', 'transform_get_response_api_request': 'build a GET request URL and empty data dict for retrieving a response by ID', 'transform_cancel_response_api_request': 'build a POST request URL and empty data dict for cancelling a running response', 'transform_compact_response_api_request': 'build a POST request URL and data dict for compacting a response context', 'transform_list_input_items_request': 'build a GET request URL and pagination params for listing input items of a response', 'get_event_model_class': 'get the Pydantic event model class for a given streaming event type string', 'should_fake_stream': 'check whether to fake-stream a response when the model does not support native streaming', 'supports_native_websocket': 'check whether the OpenAI responses API supports native WebSocket streaming', 'supports_native_file_search': 'check whether the OpenAI responses API supports native file search', 'get_supported_openai_params': 'get the list of supported OpenAI parameters for a given model'}
```


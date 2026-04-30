# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/responses/litellm_completion_transformation/handler.py

Prompts

```
['run the LiteLLMCompletionTransformationHandler.response_api_handler to transform a Responses API request into a litellm.completion call', 'run the LiteLLMCompletionTransformationHandler.async_response_api_handler to transform a Responses API request asynchronously', 'build a litellm.completion request from a Responses API request using LiteLLMCompletionResponsesConfig.transform_responses_api_request_to_chat_completion_request', 'transform a chat completion response to a Responses API response using LiteLLMCompletionResponsesConfig.transform_chat_completion_response_to_responses_api_response', 'review the LiteLLMCompletionTransformationHandler class that bridges Responses API calls to litellm.completion', 'create a LiteLLMCompletionStreamingIterator to process streaming responses from the Responses API with model, stream wrapper, and request params', 'iterate over a LiteLLMCompletionStreamingIterator to yield response events like output_text.delta, output_item.done, and response.completed', 'create a response.created event with response id, model, status, tool_choice, tools, and other request parameters', 'transform a chat completion streaming chunk into a Responses API streaming event like output_text.delta or reasoning_summary_text.delta', 'run end-of-stream done event logic to emit output_text.done, output_content_part.done, output_item.done, tool call done events, and response.completed', 'transform a Responses API request into a Chat Completion request with tools and messages', 'transform a Chat Completion response into a Responses API response with output items and usage', 'transform Responses API tools into Chat Completion tools and web search options', 'transform Chat Completion tool calls into Responses API function tool calls', 'get chat completion message history from previous response id for session chaining']
```

Usage

```
{'run_response_api_handler': 'run the LiteLLMCompletionTransformationHandler.response_api_handler to transform a Responses API request into a litellm.completion call', 'run_async_response_api_handler': 'run the LiteLLMCompletionTransformationHandler.async_response_api_handler to transform a Responses API request asynchronously', 'build_responses_api_request': 'build a litellm.completion request from a Responses API request using LiteLLMCompletionResponsesConfig.transform_responses_api_request_to_chat_completion_request', 'transform_chat_completion_response': 'transform a chat completion response to a Responses API response using LiteLLMCompletionResponsesConfig.transform_chat_completion_response_to_responses_api_response', 'review_LiteLLMCompletionTransformationHandler': 'review the LiteLLMCompletionTransformationHandler class that bridges Responses API calls to litellm.completion'}
```

## File: berriai_litellm/litellm/responses/litellm_completion_transformation/streaming_iterator.py

Prompts

```
['run the LiteLLMCompletionTransformationHandler.response_api_handler to transform a Responses API request into a litellm.completion call', 'run the LiteLLMCompletionTransformationHandler.async_response_api_handler to transform a Responses API request asynchronously', 'build a litellm.completion request from a Responses API request using LiteLLMCompletionResponsesConfig.transform_responses_api_request_to_chat_completion_request', 'transform a chat completion response to a Responses API response using LiteLLMCompletionResponsesConfig.transform_chat_completion_response_to_responses_api_response', 'review the LiteLLMCompletionTransformationHandler class that bridges Responses API calls to litellm.completion', 'create a LiteLLMCompletionStreamingIterator to process streaming responses from the Responses API with model, stream wrapper, and request params', 'iterate over a LiteLLMCompletionStreamingIterator to yield response events like output_text.delta, output_item.done, and response.completed', 'create a response.created event with response id, model, status, tool_choice, tools, and other request parameters', 'transform a chat completion streaming chunk into a Responses API streaming event like output_text.delta or reasoning_summary_text.delta', 'run end-of-stream done event logic to emit output_text.done, output_content_part.done, output_item.done, tool call done events, and response.completed', 'transform a Responses API request into a Chat Completion request with tools and messages', 'transform a Chat Completion response into a Responses API response with output items and usage', 'transform Responses API tools into Chat Completion tools and web search options', 'transform Chat Completion tool calls into Responses API function tool calls', 'get chat completion message history from previous response id for session chaining']
```

Usage

```
{'create_LiteLLMCompletionStreamingIterator': 'create a LiteLLMCompletionStreamingIterator to process streaming responses from the Responses API with model, stream wrapper, and request params', 'iterate_LiteLLMCompletionStreamingIterator': 'iterate over a LiteLLMCompletionStreamingIterator to yield response events like output_text.delta, output_item.done, and response.completed', 'create_response_created_event': 'create a response.created event with response id, model, status, tool_choice, tools, and other request parameters', 'transform_chat_completion_chunk_to_response_api_chunk': 'transform a chat completion streaming chunk into a Responses API streaming event like output_text.delta or reasoning_summary_text.delta', 'common_done_event_logic': 'run end-of-stream done event logic to emit output_text.done, output_content_part.done, output_item.done, tool call done events, and response.completed'}
```

## File: berriai_litellm/litellm/responses/litellm_completion_transformation/transformation.py

Prompts

```
['run the LiteLLMCompletionTransformationHandler.response_api_handler to transform a Responses API request into a litellm.completion call', 'run the LiteLLMCompletionTransformationHandler.async_response_api_handler to transform a Responses API request asynchronously', 'build a litellm.completion request from a Responses API request using LiteLLMCompletionResponsesConfig.transform_responses_api_request_to_chat_completion_request', 'transform a chat completion response to a Responses API response using LiteLLMCompletionResponsesConfig.transform_chat_completion_response_to_responses_api_response', 'review the LiteLLMCompletionTransformationHandler class that bridges Responses API calls to litellm.completion', 'create a LiteLLMCompletionStreamingIterator to process streaming responses from the Responses API with model, stream wrapper, and request params', 'iterate over a LiteLLMCompletionStreamingIterator to yield response events like output_text.delta, output_item.done, and response.completed', 'create a response.created event with response id, model, status, tool_choice, tools, and other request parameters', 'transform a chat completion streaming chunk into a Responses API streaming event like output_text.delta or reasoning_summary_text.delta', 'run end-of-stream done event logic to emit output_text.done, output_content_part.done, output_item.done, tool call done events, and response.completed', 'transform a Responses API request into a Chat Completion request with tools and messages', 'transform a Chat Completion response into a Responses API response with output items and usage', 'transform Responses API tools into Chat Completion tools and web search options', 'transform Chat Completion tool calls into Responses API function tool calls', 'get chat completion message history from previous response id for session chaining']
```

Usage

```
{'transform_responses_api_request_to_chat_completion_request': 'transform a Responses API request into a Chat Completion request with tools and messages', 'transform_chat_completion_response_to_responses_api_response': 'transform a Chat Completion response into a Responses API response with output items and usage', 'transform_responses_api_tools_to_chat_completion_tools': 'transform Responses API tools into Chat Completion tools and web search options', 'transform_chat_completion_tools_to_responses_tools': 'transform Chat Completion tool calls into Responses API function tool calls', 'async_responses_api_session_handler': 'get chat completion message history from previous response id for session chaining'}
```


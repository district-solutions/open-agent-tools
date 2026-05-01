# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/llm_translation/realtime/base_realtime_tests.py

Prompts

```
['test a realtime WebSocket connection to an LLM provider and verify the initial session event is received', 'test a realtime WebSocket connection with explicit query parameters passed to the backend provider', 'test sending a user message through a realtime WebSocket connection and receiving LLM responses', 'test that realtime query parameters are constructed correctly with the proper model name', 'create a mock WebSocket client that captures sent and received messages for testing realtime connections', 'test the litellm realtime websocket connection to OpenAI without an intent parameter', 'test the litellm realtime websocket connection to OpenAI with an explicit chat intent parameter', 'test that realtime query params are constructed correctly with or without an intent value', 'test that realtime query params use the normalized provider model name instead of the prefixed one', 'review the RealTimeWebSocketClient class used to mock websocket send and receive for OpenAI realtime tests', 'run the pytest tests for TestOpenAIRealtime to verify OpenAI realtime API connectivity through LiteLLM', 'test the get_model method that returns gpt-4o-realtime-preview as the OpenAI realtime model name', 'test the get_api_key_env_var method that returns OPENAI_API_KEY as the required environment variable', 'test the get_initial_event_type method that returns session.created as the expected initial event', 'review the TestOpenAIRealtime class that extends BaseRealtimeTest for OpenAI realtime API E2E testing', 'run the xAI realtime API end-to-end test to verify WebSocket connection with grok-4-1-fast-non-reasoning model', 'test that the xAI realtime API returns conversation.created as the initial event type instead of session.created', 'test the xAI realtime API key configuration using the XAI_API_KEY environment variable', 'test the xAI realtime model configuration returns xai/grok-4-1-fast-non-reasoning as the model identifier', 'test the xAI realtime query parameter construction strips the provider prefix from the model name']
```

Usage

```
{'test_realtime_connection': 'test a realtime WebSocket connection to an LLM provider and verify the initial session event is received', 'test_realtime_with_query_params': 'test a realtime WebSocket connection with explicit query parameters passed to the backend provider', 'test_send_user_message': 'test sending a user message through a realtime WebSocket connection and receiving LLM responses', 'test_query_params_construction': 'test that realtime query parameters are constructed correctly with the proper model name', 'create_mock_websocket_client': 'create a mock WebSocket client that captures sent and received messages for testing realtime connections'}
```

## File: berriai_litellm/tests/llm_translation/realtime/test_openai_realtime.py

Prompts

```
['test a realtime WebSocket connection to an LLM provider and verify the initial session event is received', 'test a realtime WebSocket connection with explicit query parameters passed to the backend provider', 'test sending a user message through a realtime WebSocket connection and receiving LLM responses', 'test that realtime query parameters are constructed correctly with the proper model name', 'create a mock WebSocket client that captures sent and received messages for testing realtime connections', 'test the litellm realtime websocket connection to OpenAI without an intent parameter', 'test the litellm realtime websocket connection to OpenAI with an explicit chat intent parameter', 'test that realtime query params are constructed correctly with or without an intent value', 'test that realtime query params use the normalized provider model name instead of the prefixed one', 'review the RealTimeWebSocketClient class used to mock websocket send and receive for OpenAI realtime tests', 'run the pytest tests for TestOpenAIRealtime to verify OpenAI realtime API connectivity through LiteLLM', 'test the get_model method that returns gpt-4o-realtime-preview as the OpenAI realtime model name', 'test the get_api_key_env_var method that returns OPENAI_API_KEY as the required environment variable', 'test the get_initial_event_type method that returns session.created as the expected initial event', 'review the TestOpenAIRealtime class that extends BaseRealtimeTest for OpenAI realtime API E2E testing', 'run the xAI realtime API end-to-end test to verify WebSocket connection with grok-4-1-fast-non-reasoning model', 'test that the xAI realtime API returns conversation.created as the initial event type instead of session.created', 'test the xAI realtime API key configuration using the XAI_API_KEY environment variable', 'test the xAI realtime model configuration returns xai/grok-4-1-fast-non-reasoning as the model identifier', 'test the xAI realtime query parameter construction strips the provider prefix from the model name']
```

Usage

```
{'test_openai_realtime_no_intent': 'test the litellm realtime websocket connection to OpenAI without an intent parameter', 'test_openai_realtime_with_intent': 'test the litellm realtime websocket connection to OpenAI with an explicit chat intent parameter', 'test_realtime_query_params_construction': 'test that realtime query params are constructed correctly with or without an intent value', 'test_realtime_query_params_normalized_model': 'test that realtime query params use the normalized provider model name instead of the prefixed one', 'review_realtime_websocket_client': 'review the RealTimeWebSocketClient class used to mock websocket send and receive for OpenAI realtime tests'}
```

## File: berriai_litellm/tests/llm_translation/realtime/test_openai_realtime_simple.py

Prompts

```
['test a realtime WebSocket connection to an LLM provider and verify the initial session event is received', 'test a realtime WebSocket connection with explicit query parameters passed to the backend provider', 'test sending a user message through a realtime WebSocket connection and receiving LLM responses', 'test that realtime query parameters are constructed correctly with the proper model name', 'create a mock WebSocket client that captures sent and received messages for testing realtime connections', 'test the litellm realtime websocket connection to OpenAI without an intent parameter', 'test the litellm realtime websocket connection to OpenAI with an explicit chat intent parameter', 'test that realtime query params are constructed correctly with or without an intent value', 'test that realtime query params use the normalized provider model name instead of the prefixed one', 'review the RealTimeWebSocketClient class used to mock websocket send and receive for OpenAI realtime tests', 'run the pytest tests for TestOpenAIRealtime to verify OpenAI realtime API connectivity through LiteLLM', 'test the get_model method that returns gpt-4o-realtime-preview as the OpenAI realtime model name', 'test the get_api_key_env_var method that returns OPENAI_API_KEY as the required environment variable', 'test the get_initial_event_type method that returns session.created as the expected initial event', 'review the TestOpenAIRealtime class that extends BaseRealtimeTest for OpenAI realtime API E2E testing', 'run the xAI realtime API end-to-end test to verify WebSocket connection with grok-4-1-fast-non-reasoning model', 'test that the xAI realtime API returns conversation.created as the initial event type instead of session.created', 'test the xAI realtime API key configuration using the XAI_API_KEY environment variable', 'test the xAI realtime model configuration returns xai/grok-4-1-fast-non-reasoning as the model identifier', 'test the xAI realtime query parameter construction strips the provider prefix from the model name']
```

Usage

```
{'run_test_openai_realtime': 'run the pytest tests for TestOpenAIRealtime to verify OpenAI realtime API connectivity through LiteLLM', 'test_get_model': 'test the get_model method that returns gpt-4o-realtime-preview as the OpenAI realtime model name', 'test_get_api_key_env_var': 'test the get_api_key_env_var method that returns OPENAI_API_KEY as the required environment variable', 'test_get_initial_event_type': 'test the get_initial_event_type method that returns session.created as the expected initial event', 'review_test_openai_realtime_class': 'review the TestOpenAIRealtime class that extends BaseRealtimeTest for OpenAI realtime API E2E testing'}
```

## File: berriai_litellm/tests/llm_translation/realtime/test_xai_realtime.py

Prompts

```
['test a realtime WebSocket connection to an LLM provider and verify the initial session event is received', 'test a realtime WebSocket connection with explicit query parameters passed to the backend provider', 'test sending a user message through a realtime WebSocket connection and receiving LLM responses', 'test that realtime query parameters are constructed correctly with the proper model name', 'create a mock WebSocket client that captures sent and received messages for testing realtime connections', 'test the litellm realtime websocket connection to OpenAI without an intent parameter', 'test the litellm realtime websocket connection to OpenAI with an explicit chat intent parameter', 'test that realtime query params are constructed correctly with or without an intent value', 'test that realtime query params use the normalized provider model name instead of the prefixed one', 'review the RealTimeWebSocketClient class used to mock websocket send and receive for OpenAI realtime tests', 'run the pytest tests for TestOpenAIRealtime to verify OpenAI realtime API connectivity through LiteLLM', 'test the get_model method that returns gpt-4o-realtime-preview as the OpenAI realtime model name', 'test the get_api_key_env_var method that returns OPENAI_API_KEY as the required environment variable', 'test the get_initial_event_type method that returns session.created as the expected initial event', 'review the TestOpenAIRealtime class that extends BaseRealtimeTest for OpenAI realtime API E2E testing', 'run the xAI realtime API end-to-end test to verify WebSocket connection with grok-4-1-fast-non-reasoning model', 'test that the xAI realtime API returns conversation.created as the initial event type instead of session.created', 'test the xAI realtime API key configuration using the XAI_API_KEY environment variable', 'test the xAI realtime model configuration returns xai/grok-4-1-fast-non-reasoning as the model identifier', 'test the xAI realtime query parameter construction strips the provider prefix from the model name']
```

Usage

```
{'test_xai_realtime_connection': 'run the xAI realtime API end-to-end test to verify WebSocket connection with grok-4-1-fast-non-reasoning model', 'test_xai_initial_event': 'test that the xAI realtime API returns conversation.created as the initial event type instead of session.created', 'test_xai_api_key_config': 'test the xAI realtime API key configuration using the XAI_API_KEY environment variable', 'test_xai_model_config': 'test the xAI realtime model configuration returns xai/grok-4-1-fast-non-reasoning as the model identifier', 'test_xai_query_params': 'test the xAI realtime query parameter construction strips the provider prefix from the model name'}
```


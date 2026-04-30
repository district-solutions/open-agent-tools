# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/example_config_yaml/custom_callbacks.py

Prompts

```
['build a CustomLogger subclass that logs pre/post API call events for LiteLLM proxy', 'test the MyCustomHandler.log_pre_api_call method that logs before an API call', 'test the MyCustomHandler.log_post_api_call method that logs after an API call', 'test the MyCustomHandler.log_success_event method that logs on successful API response', 'test the MyCustomHandler.async_log_success_event method that logs async success with cost calculation', 'build a custom LLM handler class inheriting from litellm.CustomLLM with completion and acompletion methods', 'create a sync completion method that delegates to litellm.completion with model gpt-3.5-turbo and mock_response', 'create an async acompletion method that delegates to litellm.completion with model gpt-3.5-turbo and mock_response', 'test the MyCustomLLM class inheriting from litellm.CustomLLM and verify completion returns a ModelResponse', 'review the litellm.completion call used inside MyCustomLLM methods with mock_response for testing']
```

Usage

```
{'build_custom_logger_handler': 'build a CustomLogger subclass that logs pre/post API call events for LiteLLM proxy', 'test_log_pre_api_call': 'test the MyCustomHandler.log_pre_api_call method that logs before an API call', 'test_log_post_api_call': 'test the MyCustomHandler.log_post_api_call method that logs after an API call', 'test_log_success_event': 'test the MyCustomHandler.log_success_event method that logs on successful API response', 'test_async_log_success_event': 'test the MyCustomHandler.async_log_success_event method that logs async success with cost calculation'}
```

## File: berriai_litellm/litellm/proxy/example_config_yaml/custom_handler.py

Prompts

```
['build a CustomLogger subclass that logs pre/post API call events for LiteLLM proxy', 'test the MyCustomHandler.log_pre_api_call method that logs before an API call', 'test the MyCustomHandler.log_post_api_call method that logs after an API call', 'test the MyCustomHandler.log_success_event method that logs on successful API response', 'test the MyCustomHandler.async_log_success_event method that logs async success with cost calculation', 'build a custom LLM handler class inheriting from litellm.CustomLLM with completion and acompletion methods', 'create a sync completion method that delegates to litellm.completion with model gpt-3.5-turbo and mock_response', 'create an async acompletion method that delegates to litellm.completion with model gpt-3.5-turbo and mock_response', 'test the MyCustomLLM class inheriting from litellm.CustomLLM and verify completion returns a ModelResponse', 'review the litellm.completion call used inside MyCustomLLM methods with mock_response for testing']
```

Usage

```
{'build_custom_llm_handler': 'build a custom LLM handler class inheriting from litellm.CustomLLM with completion and acompletion methods', 'create_completion_sync': 'create a sync completion method that delegates to litellm.completion with model gpt-3.5-turbo and mock_response', 'create_completion_async': 'create an async acompletion method that delegates to litellm.completion with model gpt-3.5-turbo and mock_response', 'test_CustomLLM': 'test the MyCustomLLM class inheriting from litellm.CustomLLM and verify completion returns a ModelResponse', 'review_litellm_completion': 'review the litellm.completion call used inside MyCustomLLM methods with mock_response for testing'}
```


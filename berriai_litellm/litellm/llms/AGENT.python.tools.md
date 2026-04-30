# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/base.py

Prompts

```
['create an httpx client session for making LLM API requests', 'run a model completion call with messages, model name, and optional parameters', 'run an embedding call for a given input text and model', 'test that the required environment variables and configuration are set for an LLM provider', 'review the response processing logic for both sync and async LLM API calls', 'build a custom LLM completion handler that sends messages to an API base and returns a ModelResponse', 'build a custom LLM streaming handler that returns an iterator of GenericStreamingChunks from an API base', 'build an async custom LLM completion handler that sends messages to an API base and returns a ModelResponse', 'build an async custom LLM streaming handler that returns an async iterator of GenericStreamingChunks from an API base', 'build a custom chat LLM router that dispatches to completion, acompletion, streaming, or astreaming based on async and stream flags', 'create a MaritalkError instance with status code, message, and optional headers', 'build a MaritalkConfig with temperature, max_tokens, top_p, and stream parameters', 'get the MaritalkConfig configuration by calling get_config on the class', 'get the list of supported OpenAI params for a Maritalk model', 'get the MaritalkError class from MaritalkConfig given an error message and status code']
```

Usage

```
{'create_client_session': 'create an httpx client session for making LLM API requests', 'run_completion': 'run a model completion call with messages, model name, and optional parameters', 'run_embedding': 'run an embedding call for a given input text and model', 'test_validate_environment': 'test that the required environment variables and configuration are set for an LLM provider', 'review_process_response': 'review the response processing logic for both sync and async LLM API calls'}
```

## File: berriai_litellm/litellm/llms/custom_llm.py

Prompts

```
['create an httpx client session for making LLM API requests', 'run a model completion call with messages, model name, and optional parameters', 'run an embedding call for a given input text and model', 'test that the required environment variables and configuration are set for an LLM provider', 'review the response processing logic for both sync and async LLM API calls', 'build a custom LLM completion handler that sends messages to an API base and returns a ModelResponse', 'build a custom LLM streaming handler that returns an iterator of GenericStreamingChunks from an API base', 'build an async custom LLM completion handler that sends messages to an API base and returns a ModelResponse', 'build an async custom LLM streaming handler that returns an async iterator of GenericStreamingChunks from an API base', 'build a custom chat LLM router that dispatches to completion, acompletion, streaming, or astreaming based on async and stream flags', 'create a MaritalkError instance with status code, message, and optional headers', 'build a MaritalkConfig with temperature, max_tokens, top_p, and stream parameters', 'get the MaritalkConfig configuration by calling get_config on the class', 'get the list of supported OpenAI params for a Maritalk model', 'get the MaritalkError class from MaritalkConfig given an error message and status code']
```

Usage

```
{'build_custom_llm_completion': 'build a custom LLM completion handler that sends messages to an API base and returns a ModelResponse', 'build_custom_llm_streaming': 'build a custom LLM streaming handler that returns an iterator of GenericStreamingChunks from an API base', 'build_custom_llm_acompletion': 'build an async custom LLM completion handler that sends messages to an API base and returns a ModelResponse', 'build_custom_llm_astreaming': 'build an async custom LLM streaming handler that returns an async iterator of GenericStreamingChunks from an API base', 'build_custom_chat_llm_router': 'build a custom chat LLM router that dispatches to completion, acompletion, streaming, or astreaming based on async and stream flags'}
```

## File: berriai_litellm/litellm/llms/maritalk.py

Prompts

```
['create an httpx client session for making LLM API requests', 'run a model completion call with messages, model name, and optional parameters', 'run an embedding call for a given input text and model', 'test that the required environment variables and configuration are set for an LLM provider', 'review the response processing logic for both sync and async LLM API calls', 'build a custom LLM completion handler that sends messages to an API base and returns a ModelResponse', 'build a custom LLM streaming handler that returns an iterator of GenericStreamingChunks from an API base', 'build an async custom LLM completion handler that sends messages to an API base and returns a ModelResponse', 'build an async custom LLM streaming handler that returns an async iterator of GenericStreamingChunks from an API base', 'build a custom chat LLM router that dispatches to completion, acompletion, streaming, or astreaming based on async and stream flags', 'create a MaritalkError instance with status code, message, and optional headers', 'build a MaritalkConfig with temperature, max_tokens, top_p, and stream parameters', 'get the MaritalkConfig configuration by calling get_config on the class', 'get the list of supported OpenAI params for a Maritalk model', 'get the MaritalkError class from MaritalkConfig given an error message and status code']
```

Usage

```
{'create_MaritalkError': 'create a MaritalkError instance with status code, message, and optional headers', 'build_MaritalkConfig': 'build a MaritalkConfig with temperature, max_tokens, top_p, and stream parameters', 'get_MaritalkConfig_config': 'get the MaritalkConfig configuration by calling get_config on the class', 'get_MaritalkConfig_supported_params': 'get the list of supported OpenAI params for a Maritalk model', 'get_MaritalkConfig_error_class': 'get the MaritalkError class from MaritalkConfig given an error message and status code'}
```


# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/responses/main.py

Prompts

```
['create a response via the OpenAI Responses API using litellm responses function with model and input parameters', 'create an async response via the OpenAI Responses API using litellm aresponses function with model and input', 'create an async response with MCP tool integration using litellm aresponses_api_with_mcp function', 'create a get_responses call to fetch a stored response by its ID from the OpenAI Responses API', 'create a delete_responses call to delete a stored response by its ID from the OpenAI Responses API', 'build a managed responses API response ID with custom_llm_provider, model_id, and original response_id encoded in base64', 'decode a litellm-managed responses API response ID back into custom_llm_provider, model_id, and original response_id components', 'build a managed container ID with custom_llm_provider, model_id, and original container_id encoded in base64 for provider routing', 'decode a litellm-managed container ID back into custom_llm_provider, model_id, and original container_id components', 'transform ResponseAPIUsage with input_tokens and output_tokens into a standard Usage object with prompt_tokens and completion_tokens']
```

Usage

```
{'create_responses': 'create a response via the OpenAI Responses API using litellm responses function with model and input parameters', 'create_aresponses': 'create an async response via the OpenAI Responses API using litellm aresponses function with model and input', 'create_aresponses_api_with_mcp': 'create an async response with MCP tool integration using litellm aresponses_api_with_mcp function', 'create_get_responses': 'create a get_responses call to fetch a stored response by its ID from the OpenAI Responses API', 'create_delete_responses': 'create a delete_responses call to delete a stored response by its ID from the OpenAI Responses API'}
```

## File: berriai_litellm/litellm/responses/utils.py

Prompts

```
['create a response via the OpenAI Responses API using litellm responses function with model and input parameters', 'create an async response via the OpenAI Responses API using litellm aresponses function with model and input', 'create an async response with MCP tool integration using litellm aresponses_api_with_mcp function', 'create a get_responses call to fetch a stored response by its ID from the OpenAI Responses API', 'create a delete_responses call to delete a stored response by its ID from the OpenAI Responses API', 'build a managed responses API response ID with custom_llm_provider, model_id, and original response_id encoded in base64', 'decode a litellm-managed responses API response ID back into custom_llm_provider, model_id, and original response_id components', 'build a managed container ID with custom_llm_provider, model_id, and original container_id encoded in base64 for provider routing', 'decode a litellm-managed container ID back into custom_llm_provider, model_id, and original container_id components', 'transform ResponseAPIUsage with input_tokens and output_tokens into a standard Usage object with prompt_tokens and completion_tokens']
```

Usage

```
{'build_responses_api_response_id': 'build a managed responses API response ID with custom_llm_provider, model_id, and original response_id encoded in base64', 'decode_responses_api_response_id': 'decode a litellm-managed responses API response ID back into custom_llm_provider, model_id, and original response_id components', 'build_container_id': 'build a managed container ID with custom_llm_provider, model_id, and original container_id encoded in base64 for provider routing', 'decode_container_id': 'decode a litellm-managed container ID back into custom_llm_provider, model_id, and original container_id components', 'transform_response_api_usage_to_chat_usage': 'transform ResponseAPIUsage with input_tokens and output_tokens into a standard Usage object with prompt_tokens and completion_tokens'}
```


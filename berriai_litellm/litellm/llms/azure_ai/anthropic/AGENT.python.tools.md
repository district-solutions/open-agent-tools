# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/azure_ai/anthropic/handler.py

Prompts

```
['create an Azure Anthropic chat completion handler with Azure authentication for Claude models', 'run a chat completion request against Azure-hosted Claude models with streaming or non-streaming mode', 'run an async chat completion request against Azure-hosted Claude models with streaming support', 'validate the Azure Anthropic environment by checking API keys and constructing authentication headers', 'transform chat messages and optional parameters into the Azure Anthropic API request format', 'build an Azure Anthropic messages configuration class extending AnthropicMessagesConfig with Azure authentication', 'test the validate_anthropic_messages_environment method to set up Azure authentication headers for the /v1/messages endpoint', 'build the complete Azure Anthropic /v1/messages URL from a base endpoint with automatic path normalization', 'remove the scope field from cache_control in an Anthropic messages request for Azure AI Foundry compatibility', 'transform an Anthropic messages request by applying Azure-specific modifications like removing unsupported cache_control scope', 'get the custom LLM provider string identifier as azure_ai for Azure Anthropic integration', 'test that Azure authentication headers and anthropic headers are correctly merged in validate_environment']
```

Usage

```
{'create_azure_anthropic_chat_completion': 'create an Azure Anthropic chat completion handler with Azure authentication for Claude models', 'run_completion_azure_anthropic': 'run a chat completion request against Azure-hosted Claude models with streaming or non-streaming mode', 'run_async_completion_azure_anthropic': 'run an async chat completion request against Azure-hosted Claude models with streaming support', 'validate_environment_azure_anthropic': 'validate the Azure Anthropic environment by checking API keys and constructing authentication headers', 'transform_request_azure_anthropic': 'transform chat messages and optional parameters into the Azure Anthropic API request format'}
```

## File: berriai_litellm/litellm/llms/azure_ai/anthropic/messages_transformation.py

Prompts

```
['create an Azure Anthropic chat completion handler with Azure authentication for Claude models', 'run a chat completion request against Azure-hosted Claude models with streaming or non-streaming mode', 'run an async chat completion request against Azure-hosted Claude models with streaming support', 'validate the Azure Anthropic environment by checking API keys and constructing authentication headers', 'transform chat messages and optional parameters into the Azure Anthropic API request format', 'build an Azure Anthropic messages configuration class extending AnthropicMessagesConfig with Azure authentication', 'test the validate_anthropic_messages_environment method to set up Azure authentication headers for the /v1/messages endpoint', 'build the complete Azure Anthropic /v1/messages URL from a base endpoint with automatic path normalization', 'remove the scope field from cache_control in an Anthropic messages request for Azure AI Foundry compatibility', 'transform an Anthropic messages request by applying Azure-specific modifications like removing unsupported cache_control scope', 'get the custom LLM provider string identifier as azure_ai for Azure Anthropic integration', 'test that Azure authentication headers and anthropic headers are correctly merged in validate_environment']
```

Usage

```
{'build_azure_anthropic_config': 'build an Azure Anthropic messages configuration class extending AnthropicMessagesConfig with Azure authentication', 'test_validate_environment': 'test the validate_anthropic_messages_environment method to set up Azure authentication headers for the /v1/messages endpoint', 'build_complete_url': 'build the complete Azure Anthropic /v1/messages URL from a base endpoint with automatic path normalization', 'remove_cache_scope': 'remove the scope field from cache_control in an Anthropic messages request for Azure AI Foundry compatibility', 'transform_request': 'transform an Anthropic messages request by applying Azure-specific modifications like removing unsupported cache_control scope'}
```

## File: berriai_litellm/litellm/llms/azure_ai/anthropic/transformation.py

Prompts

```
['create an Azure Anthropic chat completion handler with Azure authentication for Claude models', 'run a chat completion request against Azure-hosted Claude models with streaming or non-streaming mode', 'run an async chat completion request against Azure-hosted Claude models with streaming support', 'validate the Azure Anthropic environment by checking API keys and constructing authentication headers', 'transform chat messages and optional parameters into the Azure Anthropic API request format', 'build an Azure Anthropic messages configuration class extending AnthropicMessagesConfig with Azure authentication', 'test the validate_anthropic_messages_environment method to set up Azure authentication headers for the /v1/messages endpoint', 'build the complete Azure Anthropic /v1/messages URL from a base endpoint with automatic path normalization', 'remove the scope field from cache_control in an Anthropic messages request for Azure AI Foundry compatibility', 'transform an Anthropic messages request by applying Azure-specific modifications like removing unsupported cache_control scope', 'get the custom LLM provider string identifier as azure_ai for Azure Anthropic integration', 'test that Azure authentication headers and anthropic headers are correctly merged in validate_environment']
```

Usage

```
{'validate_environment_azure_anthropic': 'validate environment and set up Azure authentication headers for Anthropic API requests', 'transform_request_azure_anthropic': 'transform Anthropic request by removing unsupported parameters like extra_body, max_retries, and stream_options', 'get_custom_llm_provider_azure_ai': 'get the custom LLM provider string identifier as azure_ai for Azure Anthropic integration', 'build_azure_anthropic_config': 'build an AzureAnthropicConfig instance that extends AnthropicConfig with Azure authentication support', 'test_azure_anthropic_headers': 'test that Azure authentication headers and anthropic headers are correctly merged in validate_environment'}
```


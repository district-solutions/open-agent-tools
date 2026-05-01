# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/tests/litellm/llms/gradient_ai/chat/test_gradient_ai_chat_transformation.py

Prompts

```
['test that GradientAIConfig validate_environment sets Authorization and Content-Type headers from the API key', 'test that GradientAIConfig get_complete_url builds the correct URL when a custom api_base is provided', 'test that GradientAIConfig get_complete_url falls back to the default serverless endpoint when no api_base is set', 'test that GradientAIConfig get_complete_url uses the GRADIENT_AI_AGENT_ENDPOINT environment variable for the base URL', 'test that GradientAIConfig _transform_messages passes through message dicts with role and content unchanged']
```

Usage

```
{'test_validate_environment_sets_headers': 'test that GradientAIConfig validate_environment sets Authorization and Content-Type headers from the API key', 'test_get_complete_url_custom_base': 'test that GradientAIConfig get_complete_url builds the correct URL when a custom api_base is provided', 'test_get_complete_url_default_serverless': 'test that GradientAIConfig get_complete_url falls back to the default serverless endpoint when no api_base is set', 'test_get_complete_url_with_env_endpoint': 'test that GradientAIConfig get_complete_url uses the GRADIENT_AI_AGENT_ENDPOINT environment variable for the base URL', 'test_transform_messages_handles_dicts_only': 'test that GradientAIConfig _transform_messages passes through message dicts with role and content unchanged'}
```


# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/databricks/common_utils.py

Prompts

```
['redact sensitive tokens and secrets from strings, dicts, or lists before logging', 'redact sensitive HTTP header values like authorization and api-key for safe logging', 'build a user-agent string with optional partner prefix for Databricks API calls', 'validate and configure Databricks environment with OAuth M2M, PAT, or SDK authentication', 'obtain an OAuth M2M access token using client credentials flow for Databricks', 'calculate the prompt and completion cost in USD for a Databricks model given a model name and usage block', 'normalize a Databricks model name with provider prefix to a base model identifier', 'look up input and output cost per token for a Databricks model via get_model_info', 'calculate the prompt input cost in USD from prompt tokens and input cost per token', 'calculate the completion output cost in USD from completion tokens and output cost per token', 'create a ModelResponseIterator wrapping a streaming response for sync iteration', 'build a chunk parser converting raw streaming chunks into GenericStreamingChunk objects', 'test the ModelResponseIterator sync iteration with __iter__ and __next__', 'run the ModelResponseIterator async iteration with __aiter__ and __anext__', 'review the ModelResponseIterator class parsing Databricks streaming response chunks']
```

Usage

```
{'redact_DatabricksBase_redact_sensitive_data': 'redact sensitive tokens and secrets from strings, dicts, or lists before logging', 'redact_DatabricksBase_redact_headers_for_logging': 'redact sensitive HTTP header values like authorization and api-key for safe logging', 'build_DatabricksBase__build_user_agent': 'build a user-agent string with optional partner prefix for Databricks API calls', 'get_DatabricksBase_databricks_validate_environment': 'validate and configure Databricks environment with OAuth M2M, PAT, or SDK authentication', 'get_DatabricksBase__get_oauth_m2m_token': 'obtain an OAuth M2M access token using client credentials flow for Databricks'}
```

## File: berriai_litellm/litellm/llms/databricks/cost_calculator.py

Prompts

```
['redact sensitive tokens and secrets from strings, dicts, or lists before logging', 'redact sensitive HTTP header values like authorization and api-key for safe logging', 'build a user-agent string with optional partner prefix for Databricks API calls', 'validate and configure Databricks environment with OAuth M2M, PAT, or SDK authentication', 'obtain an OAuth M2M access token using client credentials flow for Databricks', 'calculate the prompt and completion cost in USD for a Databricks model given a model name and usage block', 'normalize a Databricks model name with provider prefix to a base model identifier', 'look up input and output cost per token for a Databricks model via get_model_info', 'calculate the prompt input cost in USD from prompt tokens and input cost per token', 'calculate the completion output cost in USD from completion tokens and output cost per token', 'create a ModelResponseIterator wrapping a streaming response for sync iteration', 'build a chunk parser converting raw streaming chunks into GenericStreamingChunk objects', 'test the ModelResponseIterator sync iteration with __iter__ and __next__', 'run the ModelResponseIterator async iteration with __aiter__ and __anext__', 'review the ModelResponseIterator class parsing Databricks streaming response chunks']
```

Usage

```
{'calculate_cost_per_token': 'calculate the prompt and completion cost in USD for a Databricks model given a model name and usage block', 'normalize_databricks_model': 'normalize a Databricks model name with provider prefix to a base model identifier', 'lookup_model_info': 'look up input and output cost per token for a Databricks model via get_model_info', 'calculate_prompt_cost': 'calculate the prompt input cost in USD from prompt tokens and input cost per token', 'calculate_completion_cost': 'calculate the completion output cost in USD from completion tokens and output cost per token'}
```

## File: berriai_litellm/litellm/llms/databricks/streaming_utils.py

Prompts

```
['redact sensitive tokens and secrets from strings, dicts, or lists before logging', 'redact sensitive HTTP header values like authorization and api-key for safe logging', 'build a user-agent string with optional partner prefix for Databricks API calls', 'validate and configure Databricks environment with OAuth M2M, PAT, or SDK authentication', 'obtain an OAuth M2M access token using client credentials flow for Databricks', 'calculate the prompt and completion cost in USD for a Databricks model given a model name and usage block', 'normalize a Databricks model name with provider prefix to a base model identifier', 'look up input and output cost per token for a Databricks model via get_model_info', 'calculate the prompt input cost in USD from prompt tokens and input cost per token', 'calculate the completion output cost in USD from completion tokens and output cost per token', 'create a ModelResponseIterator wrapping a streaming response for sync iteration', 'build a chunk parser converting raw streaming chunks into GenericStreamingChunk objects', 'test the ModelResponseIterator sync iteration with __iter__ and __next__', 'run the ModelResponseIterator async iteration with __aiter__ and __anext__', 'review the ModelResponseIterator class parsing Databricks streaming response chunks']
```

Usage

```
{'create_ModelResponseIterator': 'create a ModelResponseIterator wrapping a streaming response for sync iteration', 'build_chunk_parser': 'build a chunk parser converting raw streaming chunks into GenericStreamingChunk objects', 'test_ModelResponseIterator_sync': 'test the ModelResponseIterator sync iteration with __iter__ and __next__', 'run_ModelResponseIterator_async': 'run the ModelResponseIterator async iteration with __aiter__ and __anext__', 'review_ModelResponseIterator': 'review the ModelResponseIterator class parsing Databricks streaming response chunks'}
```


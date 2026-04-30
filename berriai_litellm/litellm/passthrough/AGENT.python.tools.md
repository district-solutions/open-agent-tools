# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/passthrough/main.py

Prompts

```
['build an HTTP request to pass through to an LLM API endpoint with model and provider configuration', 'create an async passthrough route that forwards requests to an LLM provider via httpx', 'run async streaming passthrough that yields chunks from an LLM API response', 'test sync streaming passthrough that collects and yields byte chunks from an LLM response', 'review the async passthrough request handler that sends httpx requests and handles streaming', 'test the BasePassthroughUtils.get_merged_query_parameters function that merges query params from default, existing URL, and request sources', 'create a call to BasePassthroughUtils.forward_headers_from_request that forwards request headers and strips x-pass- prefix while protecting credential headers', 'build a call to CommonUtils.encode_bedrock_runtime_modelid_arn that encodes slashes in AWS Bedrock ARN model IDs within endpoint URLs', 'refactor the BasePassthroughUtils.get_merged_query_parameters function to support additional query parameter priority levels', 'review the BasePassthroughUtils.forward_headers_from_request method and its x-pass- header forwarding with protected header exclusion']
```

Usage

```
{'build_llm_passthrough_route': 'build an HTTP request to pass through to an LLM API endpoint with model and provider configuration', 'create_async_passthrough_route': 'create an async passthrough route that forwards requests to an LLM provider via httpx', 'run_async_streaming': 'run async streaming passthrough that yields chunks from an LLM API response', 'test_sync_streaming': 'test sync streaming passthrough that collects and yields byte chunks from an LLM response', 'review_async_passthrough_request': 'review the async passthrough request handler that sends httpx requests and handles streaming'}
```

## File: berriai_litellm/litellm/passthrough/utils.py

Prompts

```
['build an HTTP request to pass through to an LLM API endpoint with model and provider configuration', 'create an async passthrough route that forwards requests to an LLM provider via httpx', 'run async streaming passthrough that yields chunks from an LLM API response', 'test sync streaming passthrough that collects and yields byte chunks from an LLM response', 'review the async passthrough request handler that sends httpx requests and handles streaming', 'test the BasePassthroughUtils.get_merged_query_parameters function that merges query params from default, existing URL, and request sources', 'create a call to BasePassthroughUtils.forward_headers_from_request that forwards request headers and strips x-pass- prefix while protecting credential headers', 'build a call to CommonUtils.encode_bedrock_runtime_modelid_arn that encodes slashes in AWS Bedrock ARN model IDs within endpoint URLs', 'refactor the BasePassthroughUtils.get_merged_query_parameters function to support additional query parameter priority levels', 'review the BasePassthroughUtils.forward_headers_from_request method and its x-pass- header forwarding with protected header exclusion']
```

Usage

```
{'test_get_merged_query_parameters': 'test the BasePassthroughUtils.get_merged_query_parameters function that merges query params from default, existing URL, and request sources', 'create_forward_headers_from_request': 'create a call to BasePassthroughUtils.forward_headers_from_request that forwards request headers and strips x-pass- prefix while protecting credential headers', 'build_encode_bedrock_runtime_modelid_arn': 'build a call to CommonUtils.encode_bedrock_runtime_modelid_arn that encodes slashes in AWS Bedrock ARN model IDs within endpoint URLs', 'refactor_get_merged_query_parameters': 'refactor the BasePassthroughUtils.get_merged_query_parameters function to support additional query parameter priority levels', 'review_forward_headers_from_request': 'review the BasePassthroughUtils.forward_headers_from_request method and its x-pass- header forwarding with protected header exclusion'}
```


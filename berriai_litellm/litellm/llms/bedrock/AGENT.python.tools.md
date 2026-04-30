# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/bedrock/base_aws_llm.py

Prompts

```
['build AWS boto3 credentials from access keys, session tokens, role ARNs, or web identity tokens with caching', 'build and sign a POST request for Bedrock or SageMaker API calls using AWS SigV4 authentication', 'build signed HTTP request headers for AWS Bedrock runtime API calls with SigV4 or bearer token auth', 'build the provider name from a Bedrock model path like anthropic.claude-3-5-sonnet-20240620-v1:0', 'build the canonical model ID from optional params and provider-specific model path specs', 'build an AWS Bedrock runtime client with configurable auth methods including STS assume role, OIDC web identity, profiles, and custom endpoints', "normalize JSON Schema type 'custom' to 'object' in tool input schemas for AWS Bedrock Invoke API compatibility", 'get the Bedrock API route type (converse, invoke, agent, agentcore, async_invoke, openai) for a given model name', 'get the appropriate Bedrock chat configuration class instance based on model name and API route', 'sign an AWS request using Signature Version 4 with credentials resolved from optional params or environment', 'calculate the cost per token for a given AWS Bedrock model and usage object']
```

Usage

```
{'build_get_credentials': 'build AWS boto3 credentials from access keys, session tokens, role ARNs, or web identity tokens with caching', 'build_sign_request': 'build and sign a POST request for Bedrock or SageMaker API calls using AWS SigV4 authentication', 'build_get_request_headers': 'build signed HTTP request headers for AWS Bedrock runtime API calls with SigV4 or bearer token auth', 'build_get_bedrock_invoke_provider': 'build the provider name from a Bedrock model path like anthropic.claude-3-5-sonnet-20240620-v1:0', 'build_get_bedrock_model_id': 'build the canonical model ID from optional params and provider-specific model path specs'}
```

## File: berriai_litellm/litellm/llms/bedrock/common_utils.py

Prompts

```
['build AWS boto3 credentials from access keys, session tokens, role ARNs, or web identity tokens with caching', 'build and sign a POST request for Bedrock or SageMaker API calls using AWS SigV4 authentication', 'build signed HTTP request headers for AWS Bedrock runtime API calls with SigV4 or bearer token auth', 'build the provider name from a Bedrock model path like anthropic.claude-3-5-sonnet-20240620-v1:0', 'build the canonical model ID from optional params and provider-specific model path specs', 'build an AWS Bedrock runtime client with configurable auth methods including STS assume role, OIDC web identity, profiles, and custom endpoints', "normalize JSON Schema type 'custom' to 'object' in tool input schemas for AWS Bedrock Invoke API compatibility", 'get the Bedrock API route type (converse, invoke, agent, agentcore, async_invoke, openai) for a given model name', 'get the appropriate Bedrock chat configuration class instance based on model name and API route', 'sign an AWS request using Signature Version 4 with credentials resolved from optional params or environment', 'calculate the cost per token for a given AWS Bedrock model and usage object']
```

Usage

```
{'build_bedrock_client': 'build an AWS Bedrock runtime client with configurable auth methods including STS assume role, OIDC web identity, profiles, and custom endpoints', 'normalize_json_schema_types': "normalize JSON Schema type 'custom' to 'object' in tool input schemas for AWS Bedrock Invoke API compatibility", 'get_bedrock_route': 'get the Bedrock API route type (converse, invoke, agent, agentcore, async_invoke, openai) for a given model name', 'get_bedrock_chat_config': 'get the appropriate Bedrock chat configuration class instance based on model name and API route', 'sign_aws_request': 'sign an AWS request using Signature Version 4 with credentials resolved from optional params or environment'}
```

## File: berriai_litellm/litellm/llms/bedrock/cost_calculation.py

Prompts

```
['build AWS boto3 credentials from access keys, session tokens, role ARNs, or web identity tokens with caching', 'build and sign a POST request for Bedrock or SageMaker API calls using AWS SigV4 authentication', 'build signed HTTP request headers for AWS Bedrock runtime API calls with SigV4 or bearer token auth', 'build the provider name from a Bedrock model path like anthropic.claude-3-5-sonnet-20240620-v1:0', 'build the canonical model ID from optional params and provider-specific model path specs', 'build an AWS Bedrock runtime client with configurable auth methods including STS assume role, OIDC web identity, profiles, and custom endpoints', "normalize JSON Schema type 'custom' to 'object' in tool input schemas for AWS Bedrock Invoke API compatibility", 'get the Bedrock API route type (converse, invoke, agent, agentcore, async_invoke, openai) for a given model name', 'get the appropriate Bedrock chat configuration class instance based on model name and API route', 'sign an AWS request using Signature Version 4 with credentials resolved from optional params or environment', 'calculate the cost per token for a given AWS Bedrock model and usage object']
```

Usage

```
{'calculate_cost_per_token': 'calculate the cost per token for a given AWS Bedrock model and usage object'}
```


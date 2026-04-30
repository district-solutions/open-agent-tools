# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/bedrock/batches/handler.py

Prompts

```
['check the status of an AWS Bedrock async invoke job using batch_id and aws_region_name', 'build a BedrockBatchesHandler to manage async invoke status checks for AWS Bedrock embedding jobs', 'test the BedrockBatchesHandler._handle_async_invoke_status method with mock async invoke ARN and region', 'review the BedrockBatchesHandler class and its async event loop threading pattern', 'summarize the BedrockBatchesHandler._handle_async_invoke_status method and its LiteLLMBatch transformation', 'create a BedrockBatchesConfig instance to handle batch job creation and management for AWS Bedrock', 'transform a batch creation request to Bedrock format with S3 input/output config and IAM role ARN', 'transform a batch retrieval request using a Bedrock job ARN to query the GetModelInvocationJob API', 'transform a Bedrock batch creation response to LiteLLM batch format with OpenAI-compatible status mapping', 'transform a Bedrock batch retrieval response to LiteLLM batch format with parsed timestamps and metadata']
```

Usage

```
{'check_bedrock_batch_status': 'check the status of an AWS Bedrock async invoke job using batch_id and aws_region_name', 'build_bedrock_batch_handler': 'build a BedrockBatchesHandler to manage async invoke status checks for AWS Bedrock embedding jobs', 'test_bedrock_batch_handler': 'test the BedrockBatchesHandler._handle_async_invoke_status method with mock async invoke ARN and region', 'review_bedrock_batch_handler': 'review the BedrockBatchesHandler class and its async event loop threading pattern', 'summarize_bedrock_batch_handler': 'summarize the BedrockBatchesHandler._handle_async_invoke_status method and its LiteLLMBatch transformation'}
```

## File: berriai_litellm/litellm/llms/bedrock/batches/transformation.py

Prompts

```
['check the status of an AWS Bedrock async invoke job using batch_id and aws_region_name', 'build a BedrockBatchesHandler to manage async invoke status checks for AWS Bedrock embedding jobs', 'test the BedrockBatchesHandler._handle_async_invoke_status method with mock async invoke ARN and region', 'review the BedrockBatchesHandler class and its async event loop threading pattern', 'summarize the BedrockBatchesHandler._handle_async_invoke_status method and its LiteLLMBatch transformation', 'create a BedrockBatchesConfig instance to handle batch job creation and management for AWS Bedrock', 'transform a batch creation request to Bedrock format with S3 input/output config and IAM role ARN', 'transform a batch retrieval request using a Bedrock job ARN to query the GetModelInvocationJob API', 'transform a Bedrock batch creation response to LiteLLM batch format with OpenAI-compatible status mapping', 'transform a Bedrock batch retrieval response to LiteLLM batch format with parsed timestamps and metadata']
```

Usage

```
{'create_BedrockBatchesConfig': 'create a BedrockBatchesConfig instance to handle batch job creation and management for AWS Bedrock', 'transform_BedrockBatchesConfig_create_batch_request': 'transform a batch creation request to Bedrock format with S3 input/output config and IAM role ARN', 'transform_BedrockBatchesConfig_retrieve_batch_request': 'transform a batch retrieval request using a Bedrock job ARN to query the GetModelInvocationJob API', 'transform_BedrockBatchesConfig_create_batch_response': 'transform a Bedrock batch creation response to LiteLLM batch format with OpenAI-compatible status mapping', 'transform_BedrockBatchesConfig_retrieve_batch_response': 'transform a Bedrock batch retrieval response to LiteLLM batch format with parsed timestamps and metadata'}
```


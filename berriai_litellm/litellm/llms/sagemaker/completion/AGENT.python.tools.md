# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/sagemaker/completion/handler.py

Prompts

```
['create a litellm completion call to an AWS SageMaker endpoint with streaming support', 'create an async litellm completion call to an AWS SageMaker endpoint for non-streaming responses', 'create a litellm embedding call to an AWS SageMaker endpoint using boto3 invoke_endpoint', 'build an AWS SigV4 authenticated HTTP request for SageMaker endpoint invocations', 'load AWS credentials from optional params or environment variables for SageMaker API calls', 'transform OpenAI chat completion requests to Sagemaker HuggingFace TGI format', 'parse Sagemaker HuggingFace TGI responses into OpenAI-compatible ModelResponse objects', 'map OpenAI parameters like temperature and max_tokens to Sagemaker HuggingFace TGI parameters', 'validate and build request headers for Sagemaker inference endpoint calls', 'get the list of OpenAI parameters supported by Sagemaker HuggingFace TGI endpoints']
```

Usage

```
{'create_sagemaker_completion': 'create a litellm completion call to an AWS SageMaker endpoint with streaming support', 'create_sagemaker_async_completion': 'create an async litellm completion call to an AWS SageMaker endpoint for non-streaming responses', 'create_sagemaker_embedding': 'create a litellm embedding call to an AWS SageMaker endpoint using boto3 invoke_endpoint', 'build_sagemaker_request': 'build an AWS SigV4 authenticated HTTP request for SageMaker endpoint invocations', 'load_sagemaker_credentials': 'load AWS credentials from optional params or environment variables for SageMaker API calls'}
```

## File: berriai_litellm/litellm/llms/sagemaker/completion/transformation.py

Prompts

```
['create a litellm completion call to an AWS SageMaker endpoint with streaming support', 'create an async litellm completion call to an AWS SageMaker endpoint for non-streaming responses', 'create a litellm embedding call to an AWS SageMaker endpoint using boto3 invoke_endpoint', 'build an AWS SigV4 authenticated HTTP request for SageMaker endpoint invocations', 'load AWS credentials from optional params or environment variables for SageMaker API calls', 'transform OpenAI chat completion requests to Sagemaker HuggingFace TGI format', 'parse Sagemaker HuggingFace TGI responses into OpenAI-compatible ModelResponse objects', 'map OpenAI parameters like temperature and max_tokens to Sagemaker HuggingFace TGI parameters', 'validate and build request headers for Sagemaker inference endpoint calls', 'get the list of OpenAI parameters supported by Sagemaker HuggingFace TGI endpoints']
```

Usage

```
{'transform_request_sagemaker': 'transform OpenAI chat completion requests to Sagemaker HuggingFace TGI format', 'transform_response_sagemaker': 'parse Sagemaker HuggingFace TGI responses into OpenAI-compatible ModelResponse objects', 'map_openai_params_sagemaker': 'map OpenAI parameters like temperature and max_tokens to Sagemaker HuggingFace TGI parameters', 'validate_environment_sagemaker': 'validate and build request headers for Sagemaker inference endpoint calls', 'get_supported_openai_params_sagemaker': 'get the list of OpenAI parameters supported by Sagemaker HuggingFace TGI endpoints'}
```


# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/sagemaker/chat/handler.py

Prompts

```
['create a SagemakerChatHandler instance to call AWS SageMaker inference endpoints for chat completions', 'load AWS credentials from optional params or environment variables for SageMaker API authentication', 'prepare an HTTP POST request with SigV4 authentication to a SageMaker runtime endpoint', 'transform litellm chat messages into SageMaker-compatible request format using SagemakerChatConfig', 'invoke a SageMaker endpoint to get chat completions with optional streaming via AWSEventStreamDecoder', 'build a SagemakerChatConfig instance to translate OpenAI chat completions to SageMaker invocations API', 'create the SageMaker endpoint URL for synchronous or streaming invocations with a given model and region', 'sign an HTTP request to SageMaker using AWS SigV4 authentication for model inference calls', 'get a synchronous custom stream wrapper to decode AWS event stream responses from SageMaker', 'get an async custom stream wrapper to decode AWS event stream responses from SageMaker']
```

Usage

```
{'create_sagemaker_chat_handler': 'create a SagemakerChatHandler instance to call AWS SageMaker inference endpoints for chat completions', 'load_aws_credentials': 'load AWS credentials from optional params or environment variables for SageMaker API authentication', 'prepare_sagemaker_request': 'prepare an HTTP POST request with SigV4 authentication to a SageMaker runtime endpoint', 'transform_chat_request': 'transform litellm chat messages into SageMaker-compatible request format using SagemakerChatConfig', 'invoke_sagemaker_completion': 'invoke a SageMaker endpoint to get chat completions with optional streaming via AWSEventStreamDecoder'}
```

## File: berriai_litellm/litellm/llms/sagemaker/chat/transformation.py

Prompts

```
['create a SagemakerChatHandler instance to call AWS SageMaker inference endpoints for chat completions', 'load AWS credentials from optional params or environment variables for SageMaker API authentication', 'prepare an HTTP POST request with SigV4 authentication to a SageMaker runtime endpoint', 'transform litellm chat messages into SageMaker-compatible request format using SagemakerChatConfig', 'invoke a SageMaker endpoint to get chat completions with optional streaming via AWSEventStreamDecoder', 'build a SagemakerChatConfig instance to translate OpenAI chat completions to SageMaker invocations API', 'create the SageMaker endpoint URL for synchronous or streaming invocations with a given model and region', 'sign an HTTP request to SageMaker using AWS SigV4 authentication for model inference calls', 'get a synchronous custom stream wrapper to decode AWS event stream responses from SageMaker', 'get an async custom stream wrapper to decode AWS event stream responses from SageMaker']
```

Usage

```
{'build_sagemaker_chat_config': 'build a SagemakerChatConfig instance to translate OpenAI chat completions to SageMaker invocations API', 'create_complete_url': 'create the SageMaker endpoint URL for synchronous or streaming invocations with a given model and region', 'sign_sagemaker_request': 'sign an HTTP request to SageMaker using AWS SigV4 authentication for model inference calls', 'get_sync_custom_stream_wrapper': 'get a synchronous custom stream wrapper to decode AWS event stream responses from SageMaker', 'get_async_custom_stream_wrapper': 'get an async custom stream wrapper to decode AWS event stream responses from SageMaker'}
```


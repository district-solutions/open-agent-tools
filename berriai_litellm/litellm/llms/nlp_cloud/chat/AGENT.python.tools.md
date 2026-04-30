# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/nlp_cloud/chat/handler.py

Prompts

```
['run the NLPCloud chat completion function to send messages and get a model response', 'run the chunk iterator to stream and decode NLPCloud API response chunks', 'build environment validation for NLPCloud by setting headers and verifying the API key', 'build request transformation to convert litellm params into NLPCloud API format', 'build response transformation to convert NLPCloud API response into a ModelResponse object', 'build an NLPCloudConfig instance to configure NLP Cloud API parameters like temperature, top_p, and max_length', 'transform NLPCloud chat request by converting message list to text and merging optional parameters', 'map OpenAI-compatible parameters to NLP Cloud-specific parameters like max_tokens to max_length', 'validate NLP Cloud environment by constructing auth headers with API key and content-type', 'transform NLP Cloud API response into ModelResponse with usage stats and generated text']
```

Usage

```
{'run_completion': 'run the NLPCloud chat completion function to send messages and get a model response', 'run_clean_and_iterate_chunks': 'run the chunk iterator to stream and decode NLPCloud API response chunks', 'build_validate_environment': 'build environment validation for NLPCloud by setting headers and verifying the API key', 'build_transform_request': 'build request transformation to convert litellm params into NLPCloud API format', 'build_transform_response': 'build response transformation to convert NLPCloud API response into a ModelResponse object'}
```

## File: berriai_litellm/litellm/llms/nlp_cloud/chat/transformation.py

Prompts

```
['run the NLPCloud chat completion function to send messages and get a model response', 'run the chunk iterator to stream and decode NLPCloud API response chunks', 'build environment validation for NLPCloud by setting headers and verifying the API key', 'build request transformation to convert litellm params into NLPCloud API format', 'build response transformation to convert NLPCloud API response into a ModelResponse object', 'build an NLPCloudConfig instance to configure NLP Cloud API parameters like temperature, top_p, and max_length', 'transform NLPCloud chat request by converting message list to text and merging optional parameters', 'map OpenAI-compatible parameters to NLP Cloud-specific parameters like max_tokens to max_length', 'validate NLP Cloud environment by constructing auth headers with API key and content-type', 'transform NLP Cloud API response into ModelResponse with usage stats and generated text']
```

Usage

```
{'build_NLPCloudConfig': 'build an NLPCloudConfig instance to configure NLP Cloud API parameters like temperature, top_p, and max_length', 'transform_NLPCloud_request': 'transform NLPCloud chat request by converting message list to text and merging optional parameters', 'map_NLPCloud_openai_params': 'map OpenAI-compatible parameters to NLP Cloud-specific parameters like max_tokens to max_length', 'validate_NLPCloud_environment': 'validate NLP Cloud environment by constructing auth headers with API key and content-type', 'transform_NLPCloud_response': 'transform NLP Cloud API response into ModelResponse with usage stats and generated text'}
```


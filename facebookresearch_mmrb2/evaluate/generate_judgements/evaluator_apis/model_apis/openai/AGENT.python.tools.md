# Agent Python Tools

- repo: facebookresearch/mmrb2
- repo_uri: https://github.com/facebookresearch/mmrb2

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluator_apis/model_apis/openai/gpt.py

Prompts

```
['generate text responses from a prompt using the OpenAI GPT-4o model via generate_text', 'initialize an OpenAIGPT client with a specific model name and OPENAI_API_KEY environment variable', 'generate text from a multimodal prompt containing both text segments and images using generate_text', 'generate multiple text responses by passing n greater than 1 to the generate_text method', 'review the OpenAIGPT class to understand available models and the generate_text API for text generation', 'create an OpenAIClient instance with a model name and optional API key for OpenAI API calls', 'encode an image file at a given path into a base64 encoded string', 'convert an image file into a multimodal content dict with MIME type and base64 data', 'call the OpenAI chat completion API with automatic retries and exponential backoff on failure', 'send a multimodal prompt with text and image segments to the OpenAI model and get responses']
```

Usage

```
{'generate_text_with_gpt': 'generate text responses from a prompt using the OpenAI GPT-4o model via generate_text', 'initialize_openai_gpt_client': 'initialize an OpenAIGPT client with a specific model name and OPENAI_API_KEY environment variable', 'generate_text_with_images': 'generate text from a multimodal prompt containing both text segments and images using generate_text', 'generate_multiple_responses': 'generate multiple text responses by passing n greater than 1 to the generate_text method', 'review_openai_gpt_class': 'review the OpenAIGPT class to understand available models and the generate_text API for text generation'}
```

## File: facebookresearch_mmrb2/evaluate/generate_judgements/evaluator_apis/model_apis/openai/utils.py

Prompts

```
['generate text responses from a prompt using the OpenAI GPT-4o model via generate_text', 'initialize an OpenAIGPT client with a specific model name and OPENAI_API_KEY environment variable', 'generate text from a multimodal prompt containing both text segments and images using generate_text', 'generate multiple text responses by passing n greater than 1 to the generate_text method', 'review the OpenAIGPT class to understand available models and the generate_text API for text generation', 'create an OpenAIClient instance with a model name and optional API key for OpenAI API calls', 'encode an image file at a given path into a base64 encoded string', 'convert an image file into a multimodal content dict with MIME type and base64 data', 'call the OpenAI chat completion API with automatic retries and exponential backoff on failure', 'send a multimodal prompt with text and image segments to the OpenAI model and get responses']
```

Usage

```
{'init_openai_client': 'create an OpenAIClient instance with a model name and optional API key for OpenAI API calls', 'encode_image_base64': 'encode an image file at a given path into a base64 encoded string', 'image_to_content': 'convert an image file into a multimodal content dict with MIME type and base64 data', 'chat_with_retry': 'call the OpenAI chat completion API with automatic retries and exponential backoff on failure', 'simple_query': 'send a multimodal prompt with text and image segments to the OpenAI model and get responses'}
```


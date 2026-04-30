# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/batches/batch_utils.py

Prompts

```
['calculate the cost and usage of an LLM batch job from file content dictionary and provider', 'process a completed batch job to retrieve output, cost, usage, and model information', 'calculate cost and token usage for Vertex AI batch responses from usage metadata', 'count the number of prompt tokens in a batch input file for rate limiting', 'retrieve and parse a batch output file into a list of response dictionaries', 'create a batch job from an uploaded file using OpenAI, Azure, Vertex AI, or Bedrock providers', 'retrieve the status and details of a batch job by its ID for OpenAI, Azure, or Vertex AI providers', 'cancel a pending batch job by its ID for OpenAI, Azure, or Vertex AI providers', 'list all batch jobs for the organization with optional pagination and provider filtering', 'check the status of an AWS Bedrock async invoke job and return normalized batch result']
```

Usage

```
{'calculate_batch_cost_and_usage': 'calculate the cost and usage of an LLM batch job from file content dictionary and provider', 'handle_completed_batch': 'process a completed batch job to retrieve output, cost, usage, and model information', 'calculate_vertex_ai_batch_cost_and_usage': 'calculate cost and token usage for Vertex AI batch responses from usage metadata', 'get_batch_job_input_file_usage': 'count the number of prompt tokens in a batch input file for rate limiting', 'get_batch_output_file_content_as_dictionary': 'retrieve and parse a batch output file into a list of response dictionaries'}
```

## File: berriai_litellm/litellm/batches/main.py

Prompts

```
['calculate the cost and usage of an LLM batch job from file content dictionary and provider', 'process a completed batch job to retrieve output, cost, usage, and model information', 'calculate cost and token usage for Vertex AI batch responses from usage metadata', 'count the number of prompt tokens in a batch input file for rate limiting', 'retrieve and parse a batch output file into a list of response dictionaries', 'create a batch job from an uploaded file using OpenAI, Azure, Vertex AI, or Bedrock providers', 'retrieve the status and details of a batch job by its ID for OpenAI, Azure, or Vertex AI providers', 'cancel a pending batch job by its ID for OpenAI, Azure, or Vertex AI providers', 'list all batch jobs for the organization with optional pagination and provider filtering', 'check the status of an AWS Bedrock async invoke job and return normalized batch result']
```

Usage

```
{'create_batch_create_batch': 'create a batch job from an uploaded file using OpenAI, Azure, Vertex AI, or Bedrock providers', 'retrieve_batch_retrieve_batch': 'retrieve the status and details of a batch job by its ID for OpenAI, Azure, or Vertex AI providers', 'cancel_batch_cancel_batch': 'cancel a pending batch job by its ID for OpenAI, Azure, or Vertex AI providers', 'list_batches_list_batches': 'list all batch jobs for the organization with optional pagination and provider filtering', 'handle_async_invoke_status_handle_async_invoke_status': 'check the status of an AWS Bedrock async invoke job and return normalized batch result'}
```


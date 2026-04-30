# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/batches/handler.py

Prompts

```
['create a Vertex AI batch prediction job using OpenAI-compatible batch request parameters', 'retrieve a Vertex AI batch prediction job by its ID from Google Cloud', 'list Vertex AI batch prediction jobs with optional pagination using limit and cursor', 'cancel a running Vertex AI batch prediction job and retrieve its updated status', 'build the Vertex AI batch prediction API URL for a given project and location', 'transform an OpenAI batch request to a Vertex AI batch prediction job request', 'transform a Vertex AI batch response to an OpenAI-compatible batch response object', 'transform a Vertex AI batch list response into an OpenAI-compatible paginated list response', 'extract the batch job id from a Vertex AI batch prediction response name string', 'extract the model name from a Vertex AI GCS file URI path']
```

Usage

```
{'create_batch_create_vertex_ai_batch': 'create a Vertex AI batch prediction job using OpenAI-compatible batch request parameters', 'retrieve_batch_get_vertex_ai_batch': 'retrieve a Vertex AI batch prediction job by its ID from Google Cloud', 'list_batches_list_vertex_ai_batches': 'list Vertex AI batch prediction jobs with optional pagination using limit and cursor', 'cancel_batch_cancel_vertex_ai_job': 'cancel a running Vertex AI batch prediction job and retrieve its updated status', 'create_vertex_batch_url_build_vertex_api_url': 'build the Vertex AI batch prediction API URL for a given project and location'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/batches/transformation.py

Prompts

```
['create a Vertex AI batch prediction job using OpenAI-compatible batch request parameters', 'retrieve a Vertex AI batch prediction job by its ID from Google Cloud', 'list Vertex AI batch prediction jobs with optional pagination using limit and cursor', 'cancel a running Vertex AI batch prediction job and retrieve its updated status', 'build the Vertex AI batch prediction API URL for a given project and location', 'transform an OpenAI batch request to a Vertex AI batch prediction job request', 'transform a Vertex AI batch response to an OpenAI-compatible batch response object', 'transform a Vertex AI batch list response into an OpenAI-compatible paginated list response', 'extract the batch job id from a Vertex AI batch prediction response name string', 'extract the model name from a Vertex AI GCS file URI path']
```

Usage

```
{'transform_openai_batch_request': 'transform an OpenAI batch request to a Vertex AI batch prediction job request', 'transform_vertex_ai_batch_response': 'transform a Vertex AI batch response to an OpenAI-compatible batch response object', 'transform_vertex_ai_batch_list_response': 'transform a Vertex AI batch list response into an OpenAI-compatible paginated list response', 'extract_batch_id_from_response': 'extract the batch job id from a Vertex AI batch prediction response name string', 'extract_model_from_gcs_uri': 'extract the model name from a Vertex AI GCS file URI path'}
```


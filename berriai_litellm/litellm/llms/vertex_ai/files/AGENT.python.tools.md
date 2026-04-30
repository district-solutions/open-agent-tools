# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/vertex_ai/files/handler.py

Prompts

```
['create a file on VertexAI GCS bucket using async OpenAI Files API format', 'create a file on VertexAI GCS bucket supporting both sync and async operations', 'build a parser that extracts GCS bucket name and object path from a URL-encoded file_id', 'download file content from a GCS bucket for VertexAI files asynchronously', 'download file content from a GCS bucket for VertexAI files with sync and async support', 'create VertexAI file upload request to Google Cloud Storage bucket with OpenAI-compatible API', 'transform OpenAI JSONL batch content to VertexAI JSONL format for Gemini model requests', 'retrieve a file from a GCS URI and return OpenAI-style file object response', 'delete a file from Google Cloud Storage using a GCS URI and return deletion confirmation', 'transform GCS bucket upload response into OpenAI FileObject format']
```

Usage

```
{'create_VertexAIFilesHandler_async_create_file': 'create a file on VertexAI GCS bucket using async OpenAI Files API format', 'create_VertexAIFilesHandler_create_file': 'create a file on VertexAI GCS bucket supporting both sync and async operations', 'build_VertexAIFilesHandler_extract_bucket_and_object_from_file_id': 'build a parser that extracts GCS bucket name and object path from a URL-encoded file_id', 'create_VertexAIFilesHandler_afile_content': 'download file content from a GCS bucket for VertexAI files asynchronously', 'create_VertexAIFilesHandler_file_content': 'download file content from a GCS bucket for VertexAI files with sync and async support'}
```

## File: berriai_litellm/litellm/llms/vertex_ai/files/transformation.py

Prompts

```
['create a file on VertexAI GCS bucket using async OpenAI Files API format', 'create a file on VertexAI GCS bucket supporting both sync and async operations', 'build a parser that extracts GCS bucket name and object path from a URL-encoded file_id', 'download file content from a GCS bucket for VertexAI files asynchronously', 'download file content from a GCS bucket for VertexAI files with sync and async support', 'create VertexAI file upload request to Google Cloud Storage bucket with OpenAI-compatible API', 'transform OpenAI JSONL batch content to VertexAI JSONL format for Gemini model requests', 'retrieve a file from a GCS URI and return OpenAI-style file object response', 'delete a file from Google Cloud Storage using a GCS URI and return deletion confirmation', 'transform GCS bucket upload response into OpenAI FileObject format']
```

Usage

```
{'create_file_upload_to_gcs': 'create VertexAI file upload request to Google Cloud Storage bucket with OpenAI-compatible API', 'transform_openai_jsonl_to_vertex_ai': 'transform OpenAI JSONL batch content to VertexAI JSONL format for Gemini model requests', 'retrieve_gcs_file_from_uri': 'retrieve a file from a GCS URI and return OpenAI-style file object response', 'delete_gcs_file_by_uri': 'delete a file from Google Cloud Storage using a GCS URI and return deletion confirmation', 'transform_gcs_response_to_openai': 'transform GCS bucket upload response into OpenAI FileObject format'}
```


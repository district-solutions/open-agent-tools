# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/llms/bedrock/files/handler.py

Prompts

```
['build a BedrockFilesHandler instance to download files from S3 for Bedrock batch processing', 'create an S3 URI from a base64-encoded file ID or direct S3 path string', 'create a bucket name and object key tuple from an S3 URI string', 'run an async download of file content from an S3 bucket using BedrockFilesHandler.afile_content', 'run a synchronous download of file content from an S3 bucket using BedrockFilesHandler.file_content', 'create a Bedrock S3 file upload request by transforming OpenAI file data and signing with SigV4', 'transform OpenAI JSONL batch content to Bedrock batch format with recordId and modelInput', 'sign an S3 PUT request using AWS SigV4 authentication with SHA256 content hash', 'convert an HTTPS S3 URL to s3:// URI format extracting bucket and key', 'transform an S3 upload response into an OpenAI-style FileObject with purpose, id, and status']
```

Usage

```
{'build_bedrock_files_handler': 'build a BedrockFilesHandler instance to download files from S3 for Bedrock batch processing', 'create_extract_s3_uri': 'create an S3 URI from a base64-encoded file ID or direct S3 path string', 'create_parse_s3_uri': 'create a bucket name and object key tuple from an S3 URI string', 'run_download_file_async': 'run an async download of file content from an S3 bucket using BedrockFilesHandler.afile_content', 'run_download_file_sync': 'run a synchronous download of file content from an S3 bucket using BedrockFilesHandler.file_content'}
```

## File: berriai_litellm/litellm/llms/bedrock/files/transformation.py

Prompts

```
['build a BedrockFilesHandler instance to download files from S3 for Bedrock batch processing', 'create an S3 URI from a base64-encoded file ID or direct S3 path string', 'create a bucket name and object key tuple from an S3 URI string', 'run an async download of file content from an S3 bucket using BedrockFilesHandler.afile_content', 'run a synchronous download of file content from an S3 bucket using BedrockFilesHandler.file_content', 'create a Bedrock S3 file upload request by transforming OpenAI file data and signing with SigV4', 'transform OpenAI JSONL batch content to Bedrock batch format with recordId and modelInput', 'sign an S3 PUT request using AWS SigV4 authentication with SHA256 content hash', 'convert an HTTPS S3 URL to s3:// URI format extracting bucket and key', 'transform an S3 upload response into an OpenAI-style FileObject with purpose, id, and status']
```

Usage

```
{'create_bedrock_file_upload': 'create a Bedrock S3 file upload request by transforming OpenAI file data and signing with SigV4', 'transform_openai_jsonl_to_bedrock': 'transform OpenAI JSONL batch content to Bedrock batch format with recordId and modelInput', 'sign_s3_put_request': 'sign an S3 PUT request using AWS SigV4 authentication with SHA256 content hash', 'convert_https_url_to_s3_uri': 'convert an HTTPS S3 URL to s3:// URI format extracting bucket and key', 'transform_s3_response_to_openai_file_object': 'transform an S3 upload response into an OpenAI-style FileObject with purpose, id, and status'}
```


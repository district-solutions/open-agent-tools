# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/datamodel/service/options.py

Prompts

```
['build a ConvertDocumentsOptions instance to configure document conversion with OCR, table structure, and VLM pipeline settings', 'create a PictureDescriptionLocal config for running a local Hugging Face vision-language model to describe images in documents', 'create a PictureDescriptionApi config to call an OpenAI-compatible API endpoint for describing images in documents', 'create a VlmModelLocal or VlmModelApi config for a VLM pipeline that converts document pages to docling format', 'validate ConvertDocumentsOptions to enforce mutually exclusive preset and custom config fields and deprecated field warnings', 'create a ConvertDocumentsRequest with file sources, conversion options, and an in-body target', 'create a source request item from a file path, HTTP URL, or S3 bucket coordinates', 'create a chunk documents request with conversion options, sources, and output target', 'create a generic chunk documents request with typed chunking options', 'run make_request_model to dynamically create and cache a typed chunk documents request class', 'create an HttpSource model with an HTTP URL and optional headers for fetching remote documents', 'create a FileSource model with a base64-encoded file string and filename for local document processing', 'build a DocumentStream from a FileSource by decoding its base64 content into a BytesIO stream', 'create S3Coordinates with endpoint, access key, secret key, and bucket for accessing S3-stored documents', 'test FileSource.to_document_stream converts base64 content to a valid DocumentStream object']
```

Usage

```
{'build_convert_documents_options': 'build a ConvertDocumentsOptions instance to configure document conversion with OCR, table structure, and VLM pipeline settings', 'create_picture_description_local': 'create a PictureDescriptionLocal config for running a local Hugging Face vision-language model to describe images in documents', 'create_picture_description_api': 'create a PictureDescriptionApi config to call an OpenAI-compatible API endpoint for describing images in documents', 'create_vlm_pipeline_model': 'create a VlmModelLocal or VlmModelApi config for a VLM pipeline that converts document pages to docling format', 'validate_document_conversion_options': 'validate ConvertDocumentsOptions to enforce mutually exclusive preset and custom config fields and deprecated field warnings'}
```

## File: docling-project_docling/docling/datamodel/service/requests.py

Prompts

```
['build a ConvertDocumentsOptions instance to configure document conversion with OCR, table structure, and VLM pipeline settings', 'create a PictureDescriptionLocal config for running a local Hugging Face vision-language model to describe images in documents', 'create a PictureDescriptionApi config to call an OpenAI-compatible API endpoint for describing images in documents', 'create a VlmModelLocal or VlmModelApi config for a VLM pipeline that converts document pages to docling format', 'validate ConvertDocumentsOptions to enforce mutually exclusive preset and custom config fields and deprecated field warnings', 'create a ConvertDocumentsRequest with file sources, conversion options, and an in-body target', 'create a source request item from a file path, HTTP URL, or S3 bucket coordinates', 'create a chunk documents request with conversion options, sources, and output target', 'create a generic chunk documents request with typed chunking options', 'run make_request_model to dynamically create and cache a typed chunk documents request class', 'create an HttpSource model with an HTTP URL and optional headers for fetching remote documents', 'create a FileSource model with a base64-encoded file string and filename for local document processing', 'build a DocumentStream from a FileSource by decoding its base64 content into a BytesIO stream', 'create S3Coordinates with endpoint, access key, secret key, and bucket for accessing S3-stored documents', 'test FileSource.to_document_stream converts base64 content to a valid DocumentStream object']
```

Usage

```
{'create_ConvertDocumentsRequest': 'create a ConvertDocumentsRequest with file sources, conversion options, and an in-body target', 'create_SourceRequestItem': 'create a source request item from a file path, HTTP URL, or S3 bucket coordinates', 'create_BaseChunkDocumentsRequest': 'create a chunk documents request with conversion options, sources, and output target', 'create_GenericChunkDocumentsRequest': 'create a generic chunk documents request with typed chunking options', 'run_make_request_model': 'run make_request_model to dynamically create and cache a typed chunk documents request class'}
```

## File: docling-project_docling/docling/datamodel/service/sources.py

Prompts

```
['build a ConvertDocumentsOptions instance to configure document conversion with OCR, table structure, and VLM pipeline settings', 'create a PictureDescriptionLocal config for running a local Hugging Face vision-language model to describe images in documents', 'create a PictureDescriptionApi config to call an OpenAI-compatible API endpoint for describing images in documents', 'create a VlmModelLocal or VlmModelApi config for a VLM pipeline that converts document pages to docling format', 'validate ConvertDocumentsOptions to enforce mutually exclusive preset and custom config fields and deprecated field warnings', 'create a ConvertDocumentsRequest with file sources, conversion options, and an in-body target', 'create a source request item from a file path, HTTP URL, or S3 bucket coordinates', 'create a chunk documents request with conversion options, sources, and output target', 'create a generic chunk documents request with typed chunking options', 'run make_request_model to dynamically create and cache a typed chunk documents request class', 'create an HttpSource model with an HTTP URL and optional headers for fetching remote documents', 'create a FileSource model with a base64-encoded file string and filename for local document processing', 'build a DocumentStream from a FileSource by decoding its base64 content into a BytesIO stream', 'create S3Coordinates with endpoint, access key, secret key, and bucket for accessing S3-stored documents', 'test FileSource.to_document_stream converts base64 content to a valid DocumentStream object']
```

Usage

```
{'create_http_source': 'create an HttpSource model with an HTTP URL and optional headers for fetching remote documents', 'create_file_source': 'create a FileSource model with a base64-encoded file string and filename for local document processing', 'build_document_stream': 'build a DocumentStream from a FileSource by decoding its base64 content into a BytesIO stream', 'create_s3_coordinates': 'create S3Coordinates with endpoint, access key, secret key, and bucket for accessing S3-stored documents', 'test_file_source_to_document_stream': 'test FileSource.to_document_stream converts base64 content to a valid DocumentStream object'}
```


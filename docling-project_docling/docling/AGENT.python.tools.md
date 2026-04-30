# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/document_converter.py

Prompts

```
['convert a local PDF file to DoclingDocument using the DocumentConverter class', 'convert multiple documents from file paths, URLs, or DocumentStreams in batch mode', 'convert a markdown or HTML string to a DoclingDocument using the convert_string method', 'create a DocumentConverter that only allows specified input formats like PDF and DOCX', 'run conversion with customized pipeline options for a specific input format', 'create a DocumentExtractor instance to extract structured data from PDF and image documents using a VLM pipeline', 'extract structured content from a single PDF or image file using a DocumentExtractor with an extraction template', 'extract structured content from multiple PDF or image files in batch using DocumentExtractor.extract_all', 'configure allowed input formats and per-format extraction options when initializing a DocumentExtractor', 'reuse cached extraction pipelines across documents by hashing pipeline options for efficient batch extraction']
```

Usage

```
{'convert_document_pdf': 'convert a local PDF file to DoclingDocument using the DocumentConverter class', 'convert_document_batch': 'convert multiple documents from file paths, URLs, or DocumentStreams in batch mode', 'convert_string_markdown': 'convert a markdown or HTML string to a DoclingDocument using the convert_string method', 'create_converter_allowed_formats': 'create a DocumentConverter that only allows specified input formats like PDF and DOCX', 'run_converter_with_custom_options': 'run conversion with customized pipeline options for a specific input format'}
```

## File: docling-project_docling/docling/document_extractor.py

Prompts

```
['convert a local PDF file to DoclingDocument using the DocumentConverter class', 'convert multiple documents from file paths, URLs, or DocumentStreams in batch mode', 'convert a markdown or HTML string to a DoclingDocument using the convert_string method', 'create a DocumentConverter that only allows specified input formats like PDF and DOCX', 'run conversion with customized pipeline options for a specific input format', 'create a DocumentExtractor instance to extract structured data from PDF and image documents using a VLM pipeline', 'extract structured content from a single PDF or image file using a DocumentExtractor with an extraction template', 'extract structured content from multiple PDF or image files in batch using DocumentExtractor.extract_all', 'configure allowed input formats and per-format extraction options when initializing a DocumentExtractor', 'reuse cached extraction pipelines across documents by hashing pipeline options for efficient batch extraction']
```

Usage

```
{'create_document_extractor': 'create a DocumentExtractor instance to extract structured data from PDF and image documents using a VLM pipeline', 'extract_document': 'extract structured content from a single PDF or image file using a DocumentExtractor with an extraction template', 'extract_all_documents': 'extract structured content from multiple PDF or image files in batch using DocumentExtractor.extract_all', 'configure_extraction_formats': 'configure allowed input formats and per-format extraction options when initializing a DocumentExtractor', 'reuse_cached_pipelines': 'reuse cached extraction pipelines across documents by hashing pipeline options for efficient batch extraction'}
```


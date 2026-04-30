# Agent Python Tools

- repo: bytedance/deer-flow
- repo_uri: https://github.com/bytedance/deer-flow

## File: bytedance_deer-flow/backend/packages/harness/deerflow/utils/file_conversion.py

Prompts

```
['convert a PDF, PPT, Excel, or Word document file to a markdown file using the configured PDF converter', 'extract document headings from a markdown file as a list of title and line number dicts', 'convert a PDF file to markdown using pymupdf4llm with automatic fallback to MarkItDown', 'convert any supported document file to markdown using MarkItDown', 'get the set of file extensions that can be converted to markdown', 'create a thread-safe PortAllocator instance that manages reserved ports with a lock', 'build a port allocation using allocate() with start_port and max_range parameters', 'test the allocate_context context manager that auto-releases ports on exit', 'run get_free_port to obtain an available port from the global allocator', 'refactor release_port to free a previously allocated port from the global allocator', 'create an Article object from HTML content and a title string', 'build a ReadabilityExtractor to parse HTML and extract article title and content', 'summarize an Article object into a markdown string with optional title inclusion', 'convert an Article into a list of text and image_url message dicts for LLM consumption', 'extract an Article from raw HTML using ReadabilityExtractor with fallback to pure-Python mode']
```

Usage

```
{'create_convert_file_to_markdown': 'convert a PDF, PPT, Excel, or Word document file to a markdown file using the configured PDF converter', 'create_extract_outline': 'extract document headings from a markdown file as a list of title and line number dicts', 'run_convert_pdf_with_pymupdf4llm': 'convert a PDF file to markdown using pymupdf4llm with automatic fallback to MarkItDown', 'run_convert_with_markitdown': 'convert any supported document file to markdown using MarkItDown', 'test_convertible_extensions': 'get the set of file extensions that can be converted to markdown'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/utils/network.py

Prompts

```
['convert a PDF, PPT, Excel, or Word document file to a markdown file using the configured PDF converter', 'extract document headings from a markdown file as a list of title and line number dicts', 'convert a PDF file to markdown using pymupdf4llm with automatic fallback to MarkItDown', 'convert any supported document file to markdown using MarkItDown', 'get the set of file extensions that can be converted to markdown', 'create a thread-safe PortAllocator instance that manages reserved ports with a lock', 'build a port allocation using allocate() with start_port and max_range parameters', 'test the allocate_context context manager that auto-releases ports on exit', 'run get_free_port to obtain an available port from the global allocator', 'refactor release_port to free a previously allocated port from the global allocator', 'create an Article object from HTML content and a title string', 'build a ReadabilityExtractor to parse HTML and extract article title and content', 'summarize an Article object into a markdown string with optional title inclusion', 'convert an Article into a list of text and image_url message dicts for LLM consumption', 'extract an Article from raw HTML using ReadabilityExtractor with fallback to pure-Python mode']
```

Usage

```
{'create_PortAllocator': 'create a thread-safe PortAllocator instance that manages reserved ports with a lock', 'build_allocate_port': 'build a port allocation using allocate() with start_port and max_range parameters', 'test_allocate_context': 'test the allocate_context context manager that auto-releases ports on exit', 'run_get_free_port': 'run get_free_port to obtain an available port from the global allocator', 'refactor_release_port': 'refactor release_port to free a previously allocated port from the global allocator'}
```

## File: bytedance_deer-flow/backend/packages/harness/deerflow/utils/readability.py

Prompts

```
['convert a PDF, PPT, Excel, or Word document file to a markdown file using the configured PDF converter', 'extract document headings from a markdown file as a list of title and line number dicts', 'convert a PDF file to markdown using pymupdf4llm with automatic fallback to MarkItDown', 'convert any supported document file to markdown using MarkItDown', 'get the set of file extensions that can be converted to markdown', 'create a thread-safe PortAllocator instance that manages reserved ports with a lock', 'build a port allocation using allocate() with start_port and max_range parameters', 'test the allocate_context context manager that auto-releases ports on exit', 'run get_free_port to obtain an available port from the global allocator', 'refactor release_port to free a previously allocated port from the global allocator', 'create an Article object from HTML content and a title string', 'build a ReadabilityExtractor to parse HTML and extract article title and content', 'summarize an Article object into a markdown string with optional title inclusion', 'convert an Article into a list of text and image_url message dicts for LLM consumption', 'extract an Article from raw HTML using ReadabilityExtractor with fallback to pure-Python mode']
```

Usage

```
{'create_article_from_html': 'create an Article object from HTML content and a title string', 'build_readability_extractor': 'build a ReadabilityExtractor to parse HTML and extract article title and content', 'summarize_article_to_markdown': 'summarize an Article object into a markdown string with optional title inclusion', 'convert_article_to_messages': 'convert an Article into a list of text and image_url message dicts for LLM consumption', 'extract_article_from_html': 'extract an Article from raw HTML using ReadabilityExtractor with fallback to pure-Python mode'}
```


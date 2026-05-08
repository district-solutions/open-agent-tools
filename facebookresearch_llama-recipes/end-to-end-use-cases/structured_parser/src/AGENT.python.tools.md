# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/structured_parser/src/json_to_table.py

Prompts

```
['create a SQLite table schema for storing document artifacts including tables, text, and images', 'query the document artifacts SQLite database and return results as a pandas DataFrame', 'export the document artifacts table from SQLite to a CSV file', 'write document contents to a ChromaDB vector index for semantic search', 'perform a semantic search query on the ChromaDB vector index and return results', 'run the main function to extract text, tables, images, and charts from a PDF file', 'extract structured artifacts from a single image file using LLM inference', 'extract structured artifacts from all pages of a PDF file using LLM inference', 'build an LLM inference request with an image, system prompt, user prompt, and output schema', 'save extracted artifacts to JSON, CSV, Excel, and optionally SQL and vector databases', 'extract and parse JSON from an LLM response that may contain markdown code blocks', 'encode an image file to a base64 string for use in multimodal LLM requests', 'extract pages from a PDF file and save each page as a PNG image to disk', 'run a batch of chat completion requests through a local VLLM model with guided JSON decoding', 'export multiple CSV files from a folder into a single Excel workbook with each CSV as a separate tab']
```

Usage

```
{'create_artifact_table': 'create a SQLite table schema for storing document artifacts including tables, text, and images', 'query_document_artifacts': 'query the document artifacts SQLite database and return results as a pandas DataFrame', 'export_db_to_csv': 'export the document artifacts table from SQLite to a CSV file', 'write_to_vector_index': 'write document contents to a ChromaDB vector index for semantic search', 'knn_query_vector_index': 'perform a semantic search query on the ChromaDB vector index and return results'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/structured_parser/src/structured_extraction.py

Prompts

```
['create a SQLite table schema for storing document artifacts including tables, text, and images', 'query the document artifacts SQLite database and return results as a pandas DataFrame', 'export the document artifacts table from SQLite to a CSV file', 'write document contents to a ChromaDB vector index for semantic search', 'perform a semantic search query on the ChromaDB vector index and return results', 'run the main function to extract text, tables, images, and charts from a PDF file', 'extract structured artifacts from a single image file using LLM inference', 'extract structured artifacts from all pages of a PDF file using LLM inference', 'build an LLM inference request with an image, system prompt, user prompt, and output schema', 'save extracted artifacts to JSON, CSV, Excel, and optionally SQL and vector databases', 'extract and parse JSON from an LLM response that may contain markdown code blocks', 'encode an image file to a base64 string for use in multimodal LLM requests', 'extract pages from a PDF file and save each page as a PNG image to disk', 'run a batch of chat completion requests through a local VLLM model with guided JSON decoding', 'export multiple CSV files from a folder into a single Excel workbook with each CSV as a separate tab']
```

Usage

```
{'run_main_extract_artifacts': 'run the main function to extract text, tables, images, and charts from a PDF file', 'extract_from_image': 'extract structured artifacts from a single image file using LLM inference', 'extract_from_pdf': 'extract structured artifacts from all pages of a PDF file using LLM inference', 'build_inference_request': 'build an LLM inference request with an image, system prompt, user prompt, and output schema', 'save_extraction_results': 'save extracted artifacts to JSON, CSV, Excel, and optionally SQL and vector databases'}
```

## File: facebookresearch_llama-recipes/end-to-end-use-cases/structured_parser/src/utils.py

Prompts

```
['create a SQLite table schema for storing document artifacts including tables, text, and images', 'query the document artifacts SQLite database and return results as a pandas DataFrame', 'export the document artifacts table from SQLite to a CSV file', 'write document contents to a ChromaDB vector index for semantic search', 'perform a semantic search query on the ChromaDB vector index and return results', 'run the main function to extract text, tables, images, and charts from a PDF file', 'extract structured artifacts from a single image file using LLM inference', 'extract structured artifacts from all pages of a PDF file using LLM inference', 'build an LLM inference request with an image, system prompt, user prompt, and output schema', 'save extracted artifacts to JSON, CSV, Excel, and optionally SQL and vector databases', 'extract and parse JSON from an LLM response that may contain markdown code blocks', 'encode an image file to a base64 string for use in multimodal LLM requests', 'extract pages from a PDF file and save each page as a PNG image to disk', 'run a batch of chat completion requests through a local VLLM model with guided JSON decoding', 'export multiple CSV files from a folder into a single Excel workbook with each CSV as a separate tab']
```

Usage

```
{'extract_json_from_llm_response': 'extract and parse JSON from an LLM response that may contain markdown code blocks', 'encode_image_to_base64': 'encode an image file to a base64 string for use in multimodal LLM requests', 'extract_pdf_pages_to_images': 'extract pages from a PDF file and save each page as a PNG image to disk', 'run_vllm_inference': 'run a batch of chat completion requests through a local VLLM model with guided JSON decoding', 'export_csvs_to_excel': 'export multiple CSV files from a folder into a single Excel workbook with each CSV as a separate tab'}
```


# Agent Python Tools

- repo: datalab-to/chandra
- repo_uri: https://github.com/datalab-to/chandra

## File: datalab-to_chandra/chandra/scripts/app.py

Prompts

```
['run OCR layout detection on a PDF page image using the Chandra vision language model', 'load a Chandra inference model using huggingface transformers or vLLM server', 'extract a single page image from a PDF file by page number', 'count the total number of pages in a PDF file', 'replace image filenames in markdown text with base64 data URLs', 'run the chandra CLI to perform OCR on images and PDFs from input path to output path', 'build a batch of OCR inference jobs using InferenceManager with vllm or hf method and configurable page range', 'get a list of supported image and PDF files from a given directory or single file path', 'save merged OCR results as markdown, HTML, metadata JSON, and extracted images to an output directory', 'test the chandra CLI with a page range option to process only specific pages of a multi-page PDF', 'run the Flask screenshot app server on 0.0.0.0:8503 to serve OCR visualization endpoints', 'process a document file to extract OCR layout blocks, markdown, and base64-encoded image with layout overlays', 'convert a PIL image to a base64 data URL string for embedding in HTML or JSON responses', 'get a color palette mapping for OCR layout block types like Section-Header, Table, Figure, and Equation', 'get the lazy-loaded InferenceManager instance configured with vllm for OCR layout generation', 'run the vLLM server with default H100 GPU settings on port 8000', 'run the vLLM server with a specific GPU type like a100 or l40s', 'run the vLLM server with MTP speculative decoding enabled', 'run the vLLM server with a specific GPU and MTP speculative decoding', 'test the get_gpu_settings function with different GPU types to verify batched tokens and sequence limits']
```

Usage

```
{'run_ocr_layout': 'run OCR layout detection on a PDF page image using the Chandra vision language model', 'load_model_inference': 'load a Chandra inference model using huggingface transformers or vLLM server', 'get_page_image_from_pdf': 'extract a single page image from a PDF file by page number', 'count_pdf_pages': 'count the total number of pages in a PDF file', 'embed_images_in_markdown': 'replace image filenames in markdown text with base64 data URLs'}
```

## File: datalab-to_chandra/chandra/scripts/cli.py

Prompts

```
['run OCR layout detection on a PDF page image using the Chandra vision language model', 'load a Chandra inference model using huggingface transformers or vLLM server', 'extract a single page image from a PDF file by page number', 'count the total number of pages in a PDF file', 'replace image filenames in markdown text with base64 data URLs', 'run the chandra CLI to perform OCR on images and PDFs from input path to output path', 'build a batch of OCR inference jobs using InferenceManager with vllm or hf method and configurable page range', 'get a list of supported image and PDF files from a given directory or single file path', 'save merged OCR results as markdown, HTML, metadata JSON, and extracted images to an output directory', 'test the chandra CLI with a page range option to process only specific pages of a multi-page PDF', 'run the Flask screenshot app server on 0.0.0.0:8503 to serve OCR visualization endpoints', 'process a document file to extract OCR layout blocks, markdown, and base64-encoded image with layout overlays', 'convert a PIL image to a base64 data URL string for embedding in HTML or JSON responses', 'get a color palette mapping for OCR layout block types like Section-Header, Table, Figure, and Equation', 'get the lazy-loaded InferenceManager instance configured with vllm for OCR layout generation', 'run the vLLM server with default H100 GPU settings on port 8000', 'run the vLLM server with a specific GPU type like a100 or l40s', 'run the vLLM server with MTP speculative decoding enabled', 'run the vLLM server with a specific GPU and MTP speculative decoding', 'test the get_gpu_settings function with different GPU types to verify batched tokens and sequence limits']
```

Usage

```
{'run_cli_ocr': 'run the chandra CLI to perform OCR on images and PDFs from input path to output path', 'build_ocr_batch': 'build a batch of OCR inference jobs using InferenceManager with vllm or hf method and configurable page range', 'get_supported_files': 'get a list of supported image and PDF files from a given directory or single file path', 'save_merged_output': 'save merged OCR results as markdown, HTML, metadata JSON, and extracted images to an output directory', 'test_cli_page_range': 'test the chandra CLI with a page range option to process only specific pages of a multi-page PDF'}
```

## File: datalab-to_chandra/chandra/scripts/screenshot_app.py

Prompts

```
['run OCR layout detection on a PDF page image using the Chandra vision language model', 'load a Chandra inference model using huggingface transformers or vLLM server', 'extract a single page image from a PDF file by page number', 'count the total number of pages in a PDF file', 'replace image filenames in markdown text with base64 data URLs', 'run the chandra CLI to perform OCR on images and PDFs from input path to output path', 'build a batch of OCR inference jobs using InferenceManager with vllm or hf method and configurable page range', 'get a list of supported image and PDF files from a given directory or single file path', 'save merged OCR results as markdown, HTML, metadata JSON, and extracted images to an output directory', 'test the chandra CLI with a page range option to process only specific pages of a multi-page PDF', 'run the Flask screenshot app server on 0.0.0.0:8503 to serve OCR visualization endpoints', 'process a document file to extract OCR layout blocks, markdown, and base64-encoded image with layout overlays', 'convert a PIL image to a base64 data URL string for embedding in HTML or JSON responses', 'get a color palette mapping for OCR layout block types like Section-Header, Table, Figure, and Equation', 'get the lazy-loaded InferenceManager instance configured with vllm for OCR layout generation', 'run the vLLM server with default H100 GPU settings on port 8000', 'run the vLLM server with a specific GPU type like a100 or l40s', 'run the vLLM server with MTP speculative decoding enabled', 'run the vLLM server with a specific GPU and MTP speculative decoding', 'test the get_gpu_settings function with different GPU types to verify batched tokens and sequence limits']
```

Usage

```
{'run_screenshot_app_server': 'run the Flask screenshot app server on 0.0.0.0:8503 to serve OCR visualization endpoints', 'process_document_for_ocr_layout': 'process a document file to extract OCR layout blocks, markdown, and base64-encoded image with layout overlays', 'convert_pil_image_to_base64': 'convert a PIL image to a base64 data URL string for embedding in HTML or JSON responses', 'get_ocr_block_color_palette': 'get a color palette mapping for OCR layout block types like Section-Header, Table, Figure, and Equation', 'get_inference_model_instance': 'get the lazy-loaded InferenceManager instance configured with vllm for OCR layout generation'}
```

## File: datalab-to_chandra/chandra/scripts/vllm.py

Prompts

```
['run OCR layout detection on a PDF page image using the Chandra vision language model', 'load a Chandra inference model using huggingface transformers or vLLM server', 'extract a single page image from a PDF file by page number', 'count the total number of pages in a PDF file', 'replace image filenames in markdown text with base64 data URLs', 'run the chandra CLI to perform OCR on images and PDFs from input path to output path', 'build a batch of OCR inference jobs using InferenceManager with vllm or hf method and configurable page range', 'get a list of supported image and PDF files from a given directory or single file path', 'save merged OCR results as markdown, HTML, metadata JSON, and extracted images to an output directory', 'test the chandra CLI with a page range option to process only specific pages of a multi-page PDF', 'run the Flask screenshot app server on 0.0.0.0:8503 to serve OCR visualization endpoints', 'process a document file to extract OCR layout blocks, markdown, and base64-encoded image with layout overlays', 'convert a PIL image to a base64 data URL string for embedding in HTML or JSON responses', 'get a color palette mapping for OCR layout block types like Section-Header, Table, Figure, and Equation', 'get the lazy-loaded InferenceManager instance configured with vllm for OCR layout generation', 'run the vLLM server with default H100 GPU settings on port 8000', 'run the vLLM server with a specific GPU type like a100 or l40s', 'run the vLLM server with MTP speculative decoding enabled', 'run the vLLM server with a specific GPU and MTP speculative decoding', 'test the get_gpu_settings function with different GPU types to verify batched tokens and sequence limits']
```

Usage

```
{'run_vllm_server': 'run the vLLM server with default H100 GPU settings on port 8000', 'run_vllm_server_gpu': 'run the vLLM server with a specific GPU type like a100 or l40s', 'run_vllm_server_mtp': 'run the vLLM server with MTP speculative decoding enabled', 'run_vllm_server_gpu_mtp': 'run the vLLM server with a specific GPU and MTP speculative decoding', 'test_get_gpu_settings': 'test the get_gpu_settings function with different GPU types to verify batched tokens and sequence limits'}
```


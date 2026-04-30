# Agent Python Tools

- repo: datalab-to/chandra
- repo_uri: https://github.com/datalab-to/chandra

## File: datalab-to_chandra/chandra/input.py

Prompts

```
['load an image from a file path and resize if smaller than minimum dimension', 'load specific pages from a PDF file as resized RGB images', 'parse a comma-separated page range string like 1,3-5,7 into a sorted list of integers', 'load a file as images auto-detecting whether it is a PDF or image', 'flatten annotations and form fields on a PDF page before rendering', 'parse HTML document with labeled div blocks, filtering headers, footers, and images', 'convert HTML document to Markdown with math delimiters, tables, and escaped special characters', 'extract layout blocks from HTML with normalized bounding boxes and labels for each content block', 'convert HTML and image into structured chunks with bounding boxes, labels, and HTML content', 'extract cropped images from a document image using bounding boxes and HTML content labels', 'draw bounding boxes and labels on a PIL Image from a list of LayoutBlock objects']
```

Usage

```
{'load_image_from_file': 'load an image from a file path and resize if smaller than minimum dimension', 'load_pdf_pages_as_images': 'load specific pages from a PDF file as resized RGB images', 'parse_page_range_string': 'parse a comma-separated page range string like 1,3-5,7 into a sorted list of integers', 'load_file_as_images': 'load a file as images auto-detecting whether it is a PDF or image', 'flatten_pdf_annotations': 'flatten annotations and form fields on a PDF page before rendering'}
```

## File: datalab-to_chandra/chandra/output.py

Prompts

```
['load an image from a file path and resize if smaller than minimum dimension', 'load specific pages from a PDF file as resized RGB images', 'parse a comma-separated page range string like 1,3-5,7 into a sorted list of integers', 'load a file as images auto-detecting whether it is a PDF or image', 'flatten annotations and form fields on a PDF page before rendering', 'parse HTML document with labeled div blocks, filtering headers, footers, and images', 'convert HTML document to Markdown with math delimiters, tables, and escaped special characters', 'extract layout blocks from HTML with normalized bounding boxes and labels for each content block', 'convert HTML and image into structured chunks with bounding boxes, labels, and HTML content', 'extract cropped images from a document image using bounding boxes and HTML content labels', 'draw bounding boxes and labels on a PIL Image from a list of LayoutBlock objects']
```

Usage

```
{'parse_html': 'parse HTML document with labeled div blocks, filtering headers, footers, and images', 'parse_markdown': 'convert HTML document to Markdown with math delimiters, tables, and escaped special characters', 'parse_layout': 'extract layout blocks from HTML with normalized bounding boxes and labels for each content block', 'parse_chunks': 'convert HTML and image into structured chunks with bounding boxes, labels, and HTML content', 'extract_images': 'extract cropped images from a document image using bounding boxes and HTML content labels'}
```

## File: datalab-to_chandra/chandra/util.py

Prompts

```
['load an image from a file path and resize if smaller than minimum dimension', 'load specific pages from a PDF file as resized RGB images', 'parse a comma-separated page range string like 1,3-5,7 into a sorted list of integers', 'load a file as images auto-detecting whether it is a PDF or image', 'flatten annotations and form fields on a PDF page before rendering', 'parse HTML document with labeled div blocks, filtering headers, footers, and images', 'convert HTML document to Markdown with math delimiters, tables, and escaped special characters', 'extract layout blocks from HTML with normalized bounding boxes and labels for each content block', 'convert HTML and image into structured chunks with bounding boxes, labels, and HTML content', 'extract cropped images from a document image using bounding boxes and HTML content labels', 'draw bounding boxes and labels on a PIL Image from a list of LayoutBlock objects']
```

Usage

```
{'draw_layout_image': 'draw bounding boxes and labels on a PIL Image from a list of LayoutBlock objects'}
```


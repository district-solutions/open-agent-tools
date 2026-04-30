# Agent Python Tools

- repo: docling-project/docling
- repo_uri: https://github.com/docling-project/docling

## File: docling-project_docling/docling/backend/latex/utils/encoding.py

Prompts

```
['build a function that decodes LaTeX content from a file path or BytesIO stream using utf-8, latin-1, or cp1252 encoding', 'create a call to decode_latex_content with a Path object pointing to a .tex file', 'create a call to decode_latex_content with a BytesIO object containing raw LaTeX bytes', 'test decode_latex_content with utf-8 encoded, latin-1 encoded, and cp1252 encoded LaTeX inputs', 'review decode_latex_content for encoding fallback behavior and error handling on missing files', 'parse a LaTeX table environment node into a TableData object with proper cell spans', 'process a LaTeX macro node for table elements like \\, multicolumn, multirow, and & cell breaks', 'build a TableData structure from a LaTeX table environment with multicolumn and multirow support', 'create TableCell objects with row_span and col_span attributes from parsed LaTeX table nodes', 'review the TableHelperMixin class and its LaTeX table parsing capabilities']
```

Usage

```
{'build_decode_latex_content': 'build a function that decodes LaTeX content from a file path or BytesIO stream using utf-8, latin-1, or cp1252 encoding', 'create_decode_latex_path': 'create a call to decode_latex_content with a Path object pointing to a .tex file', 'create_decode_latex_stream': 'create a call to decode_latex_content with a BytesIO object containing raw LaTeX bytes', 'test_decode_latex_content': 'test decode_latex_content with utf-8 encoded, latin-1 encoded, and cp1252 encoded LaTeX inputs', 'review_decode_latex_content': 'review decode_latex_content for encoding fallback behavior and error handling on missing files'}
```

## File: docling-project_docling/docling/backend/latex/utils/table.py

Prompts

```
['build a function that decodes LaTeX content from a file path or BytesIO stream using utf-8, latin-1, or cp1252 encoding', 'create a call to decode_latex_content with a Path object pointing to a .tex file', 'create a call to decode_latex_content with a BytesIO object containing raw LaTeX bytes', 'test decode_latex_content with utf-8 encoded, latin-1 encoded, and cp1252 encoded LaTeX inputs', 'review decode_latex_content for encoding fallback behavior and error handling on missing files', 'parse a LaTeX table environment node into a TableData object with proper cell spans', 'process a LaTeX macro node for table elements like \\, multicolumn, multirow, and & cell breaks', 'build a TableData structure from a LaTeX table environment with multicolumn and multirow support', 'create TableCell objects with row_span and col_span attributes from parsed LaTeX table nodes', 'review the TableHelperMixin class and its LaTeX table parsing capabilities']
```

Usage

```
{'parse_table_latex_environment': 'parse a LaTeX table environment node into a TableData object with proper cell spans', 'process_table_macro_node': 'process a LaTeX macro node for table elements like \\, multicolumn, multirow, and & cell breaks', 'build_table_from_latex': 'build a TableData structure from a LaTeX table environment with multicolumn and multirow support', 'create_table_cells_with_spans': 'create TableCell objects with row_span and col_span attributes from parsed LaTeX table nodes', 'review_table_helper_mixin': 'review the TableHelperMixin class and its LaTeX table parsing capabilities'}
```


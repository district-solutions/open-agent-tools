# Agent Python Tools

- repo: facebookresearch/nougat
- repo_uri: https://github.com/facebookresearch/nougat.git

## File: facebookresearch_nougat/nougat/dataset/parser/document.py

Prompts

```
['build a document tree using Element and Paragraph classes to represent structured document content', 'create a Tabular table with TableRow and TableCell elements including multicolumn and multirow support', 'generate a LaTeX table specification string from a Tabular object using get_table_spec method', 'parse and manage document references using the Document and Reference classes with author and metadata fields', 'traverse the element tree hierarchy using find_parent to locate ancestor elements by type', 'run the CLI tool to convert LaTeX-ML HTML files to markdown using --html and --out flags', 'run check_file_path to validate a list of file paths and return only those that exist', 'run check_file_path with glob patterns to resolve wildcard file paths against a working directory', 'review the check_file_path function that resolves paths with optional working directory and glob support', 'refactor the main block HTML parsing pipeline to handle additional error cases during LaTeX-ML conversion', 'parse a LaTeXML BeautifulSoup object into a structured Document with sections, figures, and references', 'parse LaTeXML HTML children and append them as typed elements to a parent Document element', 'parse LaTeXML citation elements and append bracketed references to a parent element', 'parse LaTeXML author elements into a Paragraph containing author information', 'parse LaTeXML bibliography items and add them as references to a Document', 'format a Document object into markdown text and extract figures using format_document', 'format a single document Element into a list of formatted markdown strings using format_element', 'format all children of an Element into formatted strings using format_children', 'escape LaTeX special characters in a string using latex_escape', 'split a list of strings into leading, content, and trailing whitespace parts using leading_trailing_whitespace']
```

Usage

```
{'build_document_tree': 'build a document tree using Element and Paragraph classes to represent structured document content', 'create_table_with_cells': 'create a Tabular table with TableRow and TableCell elements including multicolumn and multirow support', 'generate_latex_table_spec': 'generate a LaTeX table specification string from a Tabular object using get_table_spec method', 'parse_document_references': 'parse and manage document references using the Document and Reference classes with author and metadata fields', 'traverse_element_hierarchy': 'traverse the element tree hierarchy using find_parent to locate ancestor elements by type'}
```

## File: facebookresearch_nougat/nougat/dataset/parser/html2md.py

Prompts

```
['build a document tree using Element and Paragraph classes to represent structured document content', 'create a Tabular table with TableRow and TableCell elements including multicolumn and multirow support', 'generate a LaTeX table specification string from a Tabular object using get_table_spec method', 'parse and manage document references using the Document and Reference classes with author and metadata fields', 'traverse the element tree hierarchy using find_parent to locate ancestor elements by type', 'run the CLI tool to convert LaTeX-ML HTML files to markdown using --html and --out flags', 'run check_file_path to validate a list of file paths and return only those that exist', 'run check_file_path with glob patterns to resolve wildcard file paths against a working directory', 'review the check_file_path function that resolves paths with optional working directory and glob support', 'refactor the main block HTML parsing pipeline to handle additional error cases during LaTeX-ML conversion', 'parse a LaTeXML BeautifulSoup object into a structured Document with sections, figures, and references', 'parse LaTeXML HTML children and append them as typed elements to a parent Document element', 'parse LaTeXML citation elements and append bracketed references to a parent element', 'parse LaTeXML author elements into a Paragraph containing author information', 'parse LaTeXML bibliography items and add them as references to a Document', 'format a Document object into markdown text and extract figures using format_document', 'format a single document Element into a list of formatted markdown strings using format_element', 'format all children of an Element into formatted strings using format_children', 'escape LaTeX special characters in a string using latex_escape', 'split a list of strings into leading, content, and trailing whitespace parts using leading_trailing_whitespace']
```

Usage

```
{'run_html_to_markdown': 'run the CLI tool to convert LaTeX-ML HTML files to markdown using --html and --out flags', 'run_check_file_path': 'run check_file_path to validate a list of file paths and return only those that exist', 'run_glob_file_paths': 'run check_file_path with glob patterns to resolve wildcard file paths against a working directory', 'review_check_file_path': 'review the check_file_path function that resolves paths with optional working directory and glob support', 'refactor_html_parsing': 'refactor the main block HTML parsing pipeline to handle additional error cases during LaTeX-ML conversion'}
```

## File: facebookresearch_nougat/nougat/dataset/parser/latexml_parser.py

Prompts

```
['build a document tree using Element and Paragraph classes to represent structured document content', 'create a Tabular table with TableRow and TableCell elements including multicolumn and multirow support', 'generate a LaTeX table specification string from a Tabular object using get_table_spec method', 'parse and manage document references using the Document and Reference classes with author and metadata fields', 'traverse the element tree hierarchy using find_parent to locate ancestor elements by type', 'run the CLI tool to convert LaTeX-ML HTML files to markdown using --html and --out flags', 'run check_file_path to validate a list of file paths and return only those that exist', 'run check_file_path with glob patterns to resolve wildcard file paths against a working directory', 'review the check_file_path function that resolves paths with optional working directory and glob support', 'refactor the main block HTML parsing pipeline to handle additional error cases during LaTeX-ML conversion', 'parse a LaTeXML BeautifulSoup object into a structured Document with sections, figures, and references', 'parse LaTeXML HTML children and append them as typed elements to a parent Document element', 'parse LaTeXML citation elements and append bracketed references to a parent element', 'parse LaTeXML author elements into a Paragraph containing author information', 'parse LaTeXML bibliography items and add them as references to a Document', 'format a Document object into markdown text and extract figures using format_document', 'format a single document Element into a list of formatted markdown strings using format_element', 'format all children of an Element into formatted strings using format_children', 'escape LaTeX special characters in a string using latex_escape', 'split a list of strings into leading, content, and trailing whitespace parts using leading_trailing_whitespace']
```

Usage

```
{'parse_latexml_document': 'parse a LaTeXML BeautifulSoup object into a structured Document with sections, figures, and references', 'parse_latexml_children_elements': 'parse LaTeXML HTML children and append them as typed elements to a parent Document element', 'parse_latexml_citations': 'parse LaTeXML citation elements and append bracketed references to a parent element', 'parse_latexml_authors': 'parse LaTeXML author elements into a Paragraph containing author information', 'parse_latexml_references': 'parse LaTeXML bibliography items and add them as references to a Document'}
```

## File: facebookresearch_nougat/nougat/dataset/parser/markdown.py

Prompts

```
['build a document tree using Element and Paragraph classes to represent structured document content', 'create a Tabular table with TableRow and TableCell elements including multicolumn and multirow support', 'generate a LaTeX table specification string from a Tabular object using get_table_spec method', 'parse and manage document references using the Document and Reference classes with author and metadata fields', 'traverse the element tree hierarchy using find_parent to locate ancestor elements by type', 'run the CLI tool to convert LaTeX-ML HTML files to markdown using --html and --out flags', 'run check_file_path to validate a list of file paths and return only those that exist', 'run check_file_path with glob patterns to resolve wildcard file paths against a working directory', 'review the check_file_path function that resolves paths with optional working directory and glob support', 'refactor the main block HTML parsing pipeline to handle additional error cases during LaTeX-ML conversion', 'parse a LaTeXML BeautifulSoup object into a structured Document with sections, figures, and references', 'parse LaTeXML HTML children and append them as typed elements to a parent Document element', 'parse LaTeXML citation elements and append bracketed references to a parent element', 'parse LaTeXML author elements into a Paragraph containing author information', 'parse LaTeXML bibliography items and add them as references to a Document', 'format a Document object into markdown text and extract figures using format_document', 'format a single document Element into a list of formatted markdown strings using format_element', 'format all children of an Element into formatted strings using format_children', 'escape LaTeX special characters in a string using latex_escape', 'split a list of strings into leading, content, and trailing whitespace parts using leading_trailing_whitespace']
```

Usage

```
{'format_document_to_markdown': 'format a Document object into markdown text and extract figures using format_document', 'format_element_to_strings': 'format a single document Element into a list of formatted markdown strings using format_element', 'format_children_of_element': 'format all children of an Element into formatted strings using format_children', 'escape_latex_special_chars': 'escape LaTeX special characters in a string using latex_escape', 'split_leading_trailing_whitespace': 'split a list of strings into leading, content, and trailing whitespace parts using leading_trailing_whitespace'}
```


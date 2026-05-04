# Agent Python Tools

- repo: facebookresearch/docagent
- repo_uri: https://github.com/facebookresearch/docagent

## File: facebookresearch_docagent/tool/remove_docstrings.py

Prompts

```
['remove all docstrings from Python files in a directory using the DocstringRemover AST transformer', 'remove docstrings from a single Python file by calling remove_docstrings_from_file with a file path', 'preview which Python files would have docstrings removed without modifying them using the dry run flag', 'find all Python files recursively in a directory and its subdirectories using find_python_files', 'review the DocstringRemover class that removes docstrings from classes, functions, and async functions via AST transformation']
```

Usage

```
{'remove_docstrings_from_python_files': 'remove all docstrings from Python files in a directory using the DocstringRemover AST transformer', 'remove_docstrings_single_file': 'remove docstrings from a single Python file by calling remove_docstrings_from_file with a file path', 'dry_run_docstring_removal': 'preview which Python files would have docstrings removed without modifying them using the dry run flag', 'find_python_files_in_directory': 'find all Python files recursively in a directory and its subdirectories using find_python_files', 'review_DocstringRemover_class': 'review the DocstringRemover class that removes docstrings from classes, functions, and async functions via AST transformation'}
```


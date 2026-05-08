# Agent Python Tools

- repo: facebookresearch/laser
- repo_uri: https://github.com/facebookresearch/laser

## File: facebookresearch_laser/tasks/CCMatrix/dl_cc_matrix.py

Prompts

```
['run the dl command to download CCMatrix bitext pointers from FAIR dataset and extract CC snippets', 'run the finalize command to extract bitexts sorted by language pair from downloaded raw text files', 'create a function that cleans raw text content by replacing HTML tags, tabs, and URLs', 'build a typed parser function that parses tab-separated lines into NamedTuple objects using type annotations', 'run the validate function to check that source and target bitext files have matching line numbers']
```

Usage

```
{'run_dl_ccmatrix': 'run the dl command to download CCMatrix bitext pointers from FAIR dataset and extract CC snippets', 'run_finalize_ccmatrix': 'run the finalize command to extract bitexts sorted by language pair from downloaded raw text files', 'clean_content_function': 'create a function that cleans raw text content by replacing HTML tags, tabs, and URLs', 'create_typed_parser': 'build a typed parser function that parses tab-separated lines into NamedTuple objects using type annotations', 'validate_bitext_files': 'run the validate function to check that source and target bitext files have matching line numbers'}
```


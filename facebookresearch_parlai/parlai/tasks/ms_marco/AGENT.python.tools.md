# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/ms_marco/agents.py

Prompts

```
['build the MS MARCO dataset by calling the build function to download and prepare data files', 'create a PassageTeacher instance to handle passage selection tasks using the FbDeprecatedDialogTeacher base class', 'create a DefaultTeacher instance to handle question answering on MS MARCO data with context passages', 'review the DefaultTeacher setup_data method that yields context-question pairs with answers from JSON lines', 'summarize the _path function that resolves data file paths for train, valid, or test splits', 'convert a gzipped MS MARCO JSON file into a generator of query-passage record dictionaries', 'create Parlai fbformat text and passage selection files from a gzipped MS MARCO data file', 'cleanup passage text by stripping whitespace and replacing pipes and newlines with safe tokens', 'read all lines from a file using PathManager and return them as a list']
```

Usage

```
{'build_ms_marco_data': 'build the MS MARCO dataset by calling the build function to download and prepare data files', 'create_passage_teacher': 'create a PassageTeacher instance to handle passage selection tasks using the FbDeprecatedDialogTeacher base class', 'create_default_teacher': 'create a DefaultTeacher instance to handle question answering on MS MARCO data with context passages', 'review_setup_data_generator': 'review the DefaultTeacher setup_data method that yields context-question pairs with answers from JSON lines', 'summarize_path_function': 'summarize the _path function that resolves data file paths for train, valid, or test splits'}
```

## File: facebookresearch_parlai/parlai/tasks/ms_marco/build.py

Prompts

```
['build the MS MARCO dataset by calling the build function to download and prepare data files', 'create a PassageTeacher instance to handle passage selection tasks using the FbDeprecatedDialogTeacher base class', 'create a DefaultTeacher instance to handle question answering on MS MARCO data with context passages', 'review the DefaultTeacher setup_data method that yields context-question pairs with answers from JSON lines', 'summarize the _path function that resolves data file paths for train, valid, or test splits', 'convert a gzipped MS MARCO JSON file into a generator of query-passage record dictionaries', 'create Parlai fbformat text and passage selection files from a gzipped MS MARCO data file', 'cleanup passage text by stripping whitespace and replacing pipes and newlines with safe tokens', 'read all lines from a file using PathManager and return them as a list']
```

Usage

```
{'build_ms_marco_data': 'build the MS MARCO dataset by downloading and converting train, valid, and test splits', 'convert_gzip_to_records': 'convert a gzipped MS MARCO JSON file into a generator of query-passage record dictionaries', 'create_fb_format_files': 'create Parlai fbformat text and passage selection files from a gzipped MS MARCO data file', 'cleanup_passage_text': 'cleanup passage text by stripping whitespace and replacing pipes and newlines with safe tokens', 'read_file_lines': 'read all lines from a file using PathManager and return them as a list'}
```


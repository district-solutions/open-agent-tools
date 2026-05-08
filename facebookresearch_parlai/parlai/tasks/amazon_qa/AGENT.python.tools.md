# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/amazon_qa/agents.py

Prompts

```
['build a Parlai FixedDialogTeacher subclass to load and serve Amazon QA dialog episodes for training', 'create a single entry list from an Amazon QA episode dict using EXISTING_KEYS', 'create multiple entries from an Amazon QA episode with nested questions and answers', 'review the DefaultTeacher get method that returns an action dict with text and labels from episode data', 'refactor the DefaultTeacher _setup_data method to handle both single and multiple format Amazon QA JSON datasets', 'build the Amazon QA dataset by downloading and unpacking all category files into the datapath directory', 'parse a gzip compressed JSON file and yield each line as a JSON string', 'download all Amazon QA downloadable files for product categories like Electronics and Automotive', 'unpack gzip compressed QA data files and write parsed JSON lines to a new file', 'review the build function that manages downloading, unpacking, and marking Amazon QA data as complete']
```

Usage

```
{'build_DefaultTeacher': 'build a Parlai FixedDialogTeacher subclass to load and serve Amazon QA dialog episodes for training', 'create_entry_single': 'create a single entry list from an Amazon QA episode dict using EXISTING_KEYS', 'create_entry_multiple': 'create multiple entries from an Amazon QA episode with nested questions and answers', 'review_DefaultTeacher_get': 'review the DefaultTeacher get method that returns an action dict with text and labels from episode data', 'refactor_DefaultTeacher_setup_data': 'refactor the DefaultTeacher _setup_data method to handle both single and multiple format Amazon QA JSON datasets'}
```

## File: facebookresearch_parlai/parlai/tasks/amazon_qa/build.py

Prompts

```
['build a Parlai FixedDialogTeacher subclass to load and serve Amazon QA dialog episodes for training', 'create a single entry list from an Amazon QA episode dict using EXISTING_KEYS', 'create multiple entries from an Amazon QA episode with nested questions and answers', 'review the DefaultTeacher get method that returns an action dict with text and labels from episode data', 'refactor the DefaultTeacher _setup_data method to handle both single and multiple format Amazon QA JSON datasets', 'build the Amazon QA dataset by downloading and unpacking all category files into the datapath directory', 'parse a gzip compressed JSON file and yield each line as a JSON string', 'download all Amazon QA downloadable files for product categories like Electronics and Automotive', 'unpack gzip compressed QA data files and write parsed JSON lines to a new file', 'review the build function that manages downloading, unpacking, and marking Amazon QA data as complete']
```

Usage

```
{'build_amazon_qa_data': 'build the Amazon QA dataset by downloading and unpacking all category files into the datapath directory', 'parse_gzip_file': 'parse a gzip compressed JSON file and yield each line as a JSON string', 'download_amazon_qa_resources': 'download all Amazon QA downloadable files for product categories like Electronics and Automotive', 'unpack_gzip_to_json': 'unpack gzip compressed QA data files and write parsed JSON lines to a new file', 'review_build_function': 'review the build function that manages downloading, unpacking, and marking Amazon QA data as complete'}
```


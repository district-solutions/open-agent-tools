# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/natural_questions/agents.py

Prompts

```
['create long answer candidates from HTML document spans using start and end byte offsets', 'create long answer candidates from text document spans using start and end token offsets', 'run the NaturalQuestionsTeacher to load and serve Natural Questions dataset examples with context and answers', 'run the NaturalQuestionsOpenTeacher to load open NQ data and evaluate model responses with exact match and inclusion metrics', 'run the NaturalQuestionsSampleTeacher to load a small sample of Natural Questions data for testing', 'build the NaturalQuestions dataset by downloading, unzipping, and renaming files from Google Cloud Storage', 'build a sample version of the NaturalQuestions dataset for quick testing and development', 'download NaturalQuestions dataset blobs from Google Cloud Storage using an anonymous client', 'ungzip all compressed JSONL files in the train and valid dataset directories', 'rename dev-prefixed validation files to valid-prefixed names for agent compatibility', 'run the build function to download and decompress the NaturalQuestions Open dataset files', 'download the NaturalQuestions gold info JSON files for train, dev, and test splits', 'decompress gzip compressed JSON files to plain JSON format in the data directory', 'check if the NaturalQuestions Open dataset is already built at the current version', 'remove outdated versions of the NaturalQuestions Open dataset before rebuilding']
```

Usage

```
{'create_long_answer_from_span_html': 'create long answer candidates from HTML document spans using start and end byte offsets', 'create_long_answer_from_span_text': 'create long answer candidates from text document spans using start and end token offsets', 'run_NaturalQuestionsTeacher': 'run the NaturalQuestionsTeacher to load and serve Natural Questions dataset examples with context and answers', 'run_NaturalQuestionsOpenTeacher': 'run the NaturalQuestionsOpenTeacher to load open NQ data and evaluate model responses with exact match and inclusion metrics', 'run_NaturalQuestionsSampleTeacher': 'run the NaturalQuestionsSampleTeacher to load a small sample of Natural Questions data for testing'}
```

## File: facebookresearch_parlai/parlai/tasks/natural_questions/build.py

Prompts

```
['create long answer candidates from HTML document spans using start and end byte offsets', 'create long answer candidates from text document spans using start and end token offsets', 'run the NaturalQuestionsTeacher to load and serve Natural Questions dataset examples with context and answers', 'run the NaturalQuestionsOpenTeacher to load open NQ data and evaluate model responses with exact match and inclusion metrics', 'run the NaturalQuestionsSampleTeacher to load a small sample of Natural Questions data for testing', 'build the NaturalQuestions dataset by downloading, unzipping, and renaming files from Google Cloud Storage', 'build a sample version of the NaturalQuestions dataset for quick testing and development', 'download NaturalQuestions dataset blobs from Google Cloud Storage using an anonymous client', 'ungzip all compressed JSONL files in the train and valid dataset directories', 'rename dev-prefixed validation files to valid-prefixed names for agent compatibility', 'run the build function to download and decompress the NaturalQuestions Open dataset files', 'download the NaturalQuestions gold info JSON files for train, dev, and test splits', 'decompress gzip compressed JSON files to plain JSON format in the data directory', 'check if the NaturalQuestions Open dataset is already built at the current version', 'remove outdated versions of the NaturalQuestions Open dataset before rebuilding']
```

Usage

```
{'build_natural_questions_dataset': 'build the NaturalQuestions dataset by downloading, unzipping, and renaming files from Google Cloud Storage', 'build_sample_natural_questions': 'build a sample version of the NaturalQuestions dataset for quick testing and development', 'download_with_cloud_storage_client': 'download NaturalQuestions dataset blobs from Google Cloud Storage using an anonymous client', 'untar_dataset_files': 'ungzip all compressed JSONL files in the train and valid dataset directories', 'move_valid_files_from_dev_to_valid': 'rename dev-prefixed validation files to valid-prefixed names for agent compatibility'}
```

## File: facebookresearch_parlai/parlai/tasks/natural_questions/build_open.py

Prompts

```
['create long answer candidates from HTML document spans using start and end byte offsets', 'create long answer candidates from text document spans using start and end token offsets', 'run the NaturalQuestionsTeacher to load and serve Natural Questions dataset examples with context and answers', 'run the NaturalQuestionsOpenTeacher to load open NQ data and evaluate model responses with exact match and inclusion metrics', 'run the NaturalQuestionsSampleTeacher to load a small sample of Natural Questions data for testing', 'build the NaturalQuestions dataset by downloading, unzipping, and renaming files from Google Cloud Storage', 'build a sample version of the NaturalQuestions dataset for quick testing and development', 'download NaturalQuestions dataset blobs from Google Cloud Storage using an anonymous client', 'ungzip all compressed JSONL files in the train and valid dataset directories', 'rename dev-prefixed validation files to valid-prefixed names for agent compatibility', 'run the build function to download and decompress the NaturalQuestions Open dataset files', 'download the NaturalQuestions gold info JSON files for train, dev, and test splits', 'decompress gzip compressed JSON files to plain JSON format in the data directory', 'check if the NaturalQuestions Open dataset is already built at the current version', 'remove outdated versions of the NaturalQuestions Open dataset before rebuilding']
```

Usage

```
{'build_natural_questions_open_data': 'run the build function to download and decompress the NaturalQuestions Open dataset files', 'download_nq_gold_info': 'download the NaturalQuestions gold info JSON files for train, dev, and test splits', 'decompress_gz_files': 'decompress gzip compressed JSON files to plain JSON format in the data directory', 'check_data_version': 'check if the NaturalQuestions Open dataset is already built at the current version', 'remove_outdated_data': 'remove outdated versions of the NaturalQuestions Open dataset before rebuilding'}
```


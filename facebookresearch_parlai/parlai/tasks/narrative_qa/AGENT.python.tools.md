# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/narrative_qa/agents.py

Prompts

```
['review the SummariesTeacher class that loads QA pairs and summaries from CSV files for NarrativeQA', 'review the DefaultTeacher class that loads QA pairs with full story content from CSV and story files', 'review the setup_data method in SummariesTeacher that yields question-answer pairs paired with document summaries', 'review the setup_data method in DefaultTeacher that yields question-answer pairs paired with full story text', 'review the _path function that resolves the NarrativeQA data directory path based on the datatype option', 'build the NarrativeQA dataset by downloading stories, dividing CSVs into train valid test sets, and organizing files', 'divide a CSV file into train valid and test sets based on a set column', 'download story content files from URLs listed in a documents CSV file with retry logic', 'write a list of dictionaries to a CSV file with headers derived from the first dictionary keys', 'move CSV files matching train valid test suffixes into their corresponding set subdirectories']
```

Usage

```
{'review_SummariesTeacher': 'review the SummariesTeacher class that loads QA pairs and summaries from CSV files for NarrativeQA', 'review_DefaultTeacher': 'review the DefaultTeacher class that loads QA pairs with full story content from CSV and story files', 'review_setup_data_SummariesTeacher': 'review the setup_data method in SummariesTeacher that yields question-answer pairs paired with document summaries', 'review_setup_data_DefaultTeacher': 'review the setup_data method in DefaultTeacher that yields question-answer pairs paired with full story text', 'review__path': 'review the _path function that resolves the NarrativeQA data directory path based on the datatype option'}
```

## File: facebookresearch_parlai/parlai/tasks/narrative_qa/build.py

Prompts

```
['review the SummariesTeacher class that loads QA pairs and summaries from CSV files for NarrativeQA', 'review the DefaultTeacher class that loads QA pairs with full story content from CSV and story files', 'review the setup_data method in SummariesTeacher that yields question-answer pairs paired with document summaries', 'review the setup_data method in DefaultTeacher that yields question-answer pairs paired with full story text', 'review the _path function that resolves the NarrativeQA data directory path based on the datatype option', 'build the NarrativeQA dataset by downloading stories, dividing CSVs into train valid test sets, and organizing files', 'divide a CSV file into train valid and test sets based on a set column', 'download story content files from URLs listed in a documents CSV file with retry logic', 'write a list of dictionaries to a CSV file with headers derived from the first dictionary keys', 'move CSV files matching train valid test suffixes into their corresponding set subdirectories']
```

Usage

```
{'build_narrativeqa_dataset': 'build the NarrativeQA dataset by downloading stories, dividing CSVs into train valid test sets, and organizing files', 'divide_csv_into_sets': 'divide a CSV file into train valid and test sets based on a set column', 'download_stories': 'download story content files from URLs listed in a documents CSV file with retry logic', 'write_dict_list_to_csv': 'write a list of dictionaries to a CSV file with headers derived from the first dictionary keys', 'move_files': 'move CSV files matching train valid test suffixes into their corresponding set subdirectories'}
```


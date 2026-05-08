# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/mwsc/agents.py

Prompts

```
['build a Parlai MWSC teacher that loads JSON data with context, question, and answer fields', 'create a setup_data method that yields context-question pairs with answers from a JSON file', 'run the MWSC teacher to load and serve MWSC dataset episodes for dialog training', 'review the MWSCTeacher __init__ method to understand how it configures datapath and datafile options', 'test the DefaultTeacher class which inherits MWSCTeacher for default MWSC task behavior', 'build the MWSC dataset by downloading schema.txt and generating train validation and test JSONL splits', 'download the MWSC schema.txt resource file from the Salesforce decanlp GitHub repository', 'parse bracketed alternatives like [A/B] in schema text and expand them into two separate variants', 'split the MWSC examples into train validation and test sets and write JSONL files for each split', 'check if the MWSC dataset has already been built and remove outdated versions if needed']
```

Usage

```
{'build_MWSCTeacher': 'build a Parlai MWSC teacher that loads JSON data with context, question, and answer fields', 'create_MWSCTeacher_setup_data': 'create a setup_data method that yields context-question pairs with answers from a JSON file', 'run_MWSCTeacher': 'run the MWSC teacher to load and serve MWSC dataset episodes for dialog training', 'review_MWSCTeacher_init': 'review the MWSCTeacher __init__ method to understand how it configures datapath and datafile options', 'test_DefaultTeacher': 'test the DefaultTeacher class which inherits MWSCTeacher for default MWSC task behavior'}
```

## File: facebookresearch_parlai/parlai/tasks/mwsc/build.py

Prompts

```
['build a Parlai MWSC teacher that loads JSON data with context, question, and answer fields', 'create a setup_data method that yields context-question pairs with answers from a JSON file', 'run the MWSC teacher to load and serve MWSC dataset episodes for dialog training', 'review the MWSCTeacher __init__ method to understand how it configures datapath and datafile options', 'test the DefaultTeacher class which inherits MWSCTeacher for default MWSC task behavior', 'build the MWSC dataset by downloading schema.txt and generating train validation and test JSONL splits', 'download the MWSC schema.txt resource file from the Salesforce decanlp GitHub repository', 'parse bracketed alternatives like [A/B] in schema text and expand them into two separate variants', 'split the MWSC examples into train validation and test sets and write JSONL files for each split', 'check if the MWSC dataset has already been built and remove outdated versions if needed']
```

Usage

```
{'build_mwsc_data': 'build the MWSC dataset by downloading schema.txt and generating train validation and test JSONL splits', 'download_mwsc_resources': 'download the MWSC schema.txt resource file from the Salesforce decanlp GitHub repository', 'parse_schema_alternatives': 'parse bracketed alternatives like [A/B] in schema text and expand them into two separate variants', 'split_mwsc_examples': 'split the MWSC examples into train validation and test sets and write JSONL files for each split', 'check_mwsc_built': 'check if the MWSC dataset has already been built and remove outdated versions if needed'}
```


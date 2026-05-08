# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/tasks/wikisql/agents.py

Prompts

```
['review the WikiSQLTeacher class that extends DialogTeacher for the WikiSQL text-to-SQL task', 'run the WikiSQLTeacher setup_data method to load table and QA JSONL files into dialog episodes', 'test the parse_into_sql function that converts structured query dicts into SQL SELECT statements with WHERE clauses', 'test the table_into_context function that converts table headers into natural language column descriptions', 'summarize the _datatype function that maps ParlAI datatype strings to WikiSQL dataset file suffixes', 'build the WikiSQL dataset by downloading data.tar.bz2 and query.py to the ParlAI datapath directory', 'download the WikiSQL data archive and query module from the Salesforce GitHub repository', 'check if the WikiSQL dataset has already been built in the ParlAI data directory', 'remove an older version of the WikiSQL dataset directory before rebuilding', 'mark the WikiSQL dataset build as complete in the ParlAI build data registry']
```

Usage

```
{'review_WikiSQLTeacher_class': 'review the WikiSQLTeacher class that extends DialogTeacher for the WikiSQL text-to-SQL task', 'run_WikiSQLTeacher_setup_data': 'run the WikiSQLTeacher setup_data method to load table and QA JSONL files into dialog episodes', 'test_parse_into_sql': 'test the parse_into_sql function that converts structured query dicts into SQL SELECT statements with WHERE clauses', 'test_table_into_context': 'test the table_into_context function that converts table headers into natural language column descriptions', 'summarize_datatype_function': 'summarize the _datatype function that maps ParlAI datatype strings to WikiSQL dataset file suffixes'}
```

## File: facebookresearch_parlai/parlai/tasks/wikisql/build.py

Prompts

```
['review the WikiSQLTeacher class that extends DialogTeacher for the WikiSQL text-to-SQL task', 'run the WikiSQLTeacher setup_data method to load table and QA JSONL files into dialog episodes', 'test the parse_into_sql function that converts structured query dicts into SQL SELECT statements with WHERE clauses', 'test the table_into_context function that converts table headers into natural language column descriptions', 'summarize the _datatype function that maps ParlAI datatype strings to WikiSQL dataset file suffixes', 'build the WikiSQL dataset by downloading data.tar.bz2 and query.py to the ParlAI datapath directory', 'download the WikiSQL data archive and query module from the Salesforce GitHub repository', 'check if the WikiSQL dataset has already been built in the ParlAI data directory', 'remove an older version of the WikiSQL dataset directory before rebuilding', 'mark the WikiSQL dataset build as complete in the ParlAI build data registry']
```

Usage

```
{'build_wikisql_dataset': 'build the WikiSQL dataset by downloading data.tar.bz2 and query.py to the ParlAI datapath directory', 'download_wikisql_resources': 'download the WikiSQL data archive and query module from the Salesforce GitHub repository', 'check_wikisql_built': 'check if the WikiSQL dataset has already been built in the ParlAI data directory', 'remove_outdated_wikisql': 'remove an older version of the WikiSQL dataset directory before rebuilding', 'mark_wikisql_done': 'mark the WikiSQL dataset build as complete in the ParlAI build data registry'}
```


# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/search/tests/routes/test_filter.py

Prompts

```
['test the validate_query_parameter function with where and orderby SQL filter expressions', 'test that validate_query_parameter raises InvalidParameterError on SQL injection attempts like semicolons or comments', 'test that validate_query_parameter raises InvalidParameterError on dangerous system functions like getenv or version', 'test the execute_filter_query function with various where clauses, orderby sorting, and column selections against a DuckDB index', 'test the async create_response function that builds a paginated dataset viewer response from a PyArrow table', 'test the full_text_search function with a DuckDB FTS index and verify paginated search results', 'test the get_download_folder function to verify it returns the correct index folder path', 'test that full_text_search safely handles SQL injection attempts in search queries', 'test creating a DuckDB full-text search index from a pandas DataFrame with sample text data', 'test full_text_search pagination by verifying offset and length parameters return correct subsets of results']
```

Usage

```
{'test_validate_query_parameter': 'test the validate_query_parameter function with where and orderby SQL filter expressions', 'test_validate_query_parameter_sql_injection': 'test that validate_query_parameter raises InvalidParameterError on SQL injection attempts like semicolons or comments', 'test_validate_query_parameter_system_functions': 'test that validate_query_parameter raises InvalidParameterError on dangerous system functions like getenv or version', 'test_execute_filter_query': 'test the execute_filter_query function with various where clauses, orderby sorting, and column selections against a DuckDB index', 'test_create_response': 'test the async create_response function that builds a paginated dataset viewer response from a PyArrow table'}
```

## File: huggingface_dataset-viewer/services/search/tests/routes/test_search.py

Prompts

```
['test the validate_query_parameter function with where and orderby SQL filter expressions', 'test that validate_query_parameter raises InvalidParameterError on SQL injection attempts like semicolons or comments', 'test that validate_query_parameter raises InvalidParameterError on dangerous system functions like getenv or version', 'test the execute_filter_query function with various where clauses, orderby sorting, and column selections against a DuckDB index', 'test the async create_response function that builds a paginated dataset viewer response from a PyArrow table', 'test the full_text_search function with a DuckDB FTS index and verify paginated search results', 'test the get_download_folder function to verify it returns the correct index folder path', 'test that full_text_search safely handles SQL injection attempts in search queries', 'test creating a DuckDB full-text search index from a pandas DataFrame with sample text data', 'test full_text_search pagination by verifying offset and length parameters return correct subsets of results']
```

Usage

```
{'test_full_text_search': 'test the full_text_search function with a DuckDB FTS index and verify paginated search results', 'test_get_download_folder': 'test the get_download_folder function to verify it returns the correct index folder path', 'test_sql_injection_safety': 'test that full_text_search safely handles SQL injection attempts in search queries', 'test_fts_index_creation': 'test creating a DuckDB full-text search index from a pandas DataFrame with sample text data', 'test_search_pagination': 'test full_text_search pagination by verifying offset and length parameters return correct subsets of results'}
```


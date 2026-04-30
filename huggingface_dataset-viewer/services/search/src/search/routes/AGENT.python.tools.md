# Agent Python Tools

- repo: huggingface/dataset-viewer
- repo_uri: https://github.com/huggingface/dataset-viewer

## File: huggingface_dataset-viewer/services/search/src/search/routes/filter.py

Prompts

```
['create a starlette endpoint that filters dataset rows by where and orderby query parameters', 'execute a duckdb filter query on a parquet index file and return matching rows', 'validate a where or orderby SQL parameter against allowed symbols and patterns', 'build regex patterns to validate SQL where and orderby clause parameters for safety', 'filter dataset rows using duckdb with optional where clause, ordering, limit, and offset', 'run a BM25 full-text search query against a DuckDB index file and return matching rows as a PyArrow table', 'create a paginated response from a PyArrow table with dataset features, row offsets, and total row counts', 'build a Starlette endpoint that performs full-text search on HuggingFace datasets using DuckDB FTS indexes', 'review the SQL template that executes BM25 matching on a DuckDB full-text search index and filters non-null scores', 'review the SQL template that joins FTS stage results with dataset data ordered by relevance score descending']
```

Usage

```
{'create_filter_endpoint': 'create a starlette endpoint that filters dataset rows by where and orderby query parameters', 'execute_filter_query': 'execute a duckdb filter query on a parquet index file and return matching rows', 'validate_query_parameter': 'validate a where or orderby SQL parameter against allowed symbols and patterns', 'build_sql_validation_patterns': 'build regex patterns to validate SQL where and orderby clause parameters for safety', 'filter_dataset_rows': 'filter dataset rows using duckdb with optional where clause, ordering, limit, and offset'}
```

## File: huggingface_dataset-viewer/services/search/src/search/routes/search.py

Prompts

```
['create a starlette endpoint that filters dataset rows by where and orderby query parameters', 'execute a duckdb filter query on a parquet index file and return matching rows', 'validate a where or orderby SQL parameter against allowed symbols and patterns', 'build regex patterns to validate SQL where and orderby clause parameters for safety', 'filter dataset rows using duckdb with optional where clause, ordering, limit, and offset', 'run a BM25 full-text search query against a DuckDB index file and return matching rows as a PyArrow table', 'create a paginated response from a PyArrow table with dataset features, row offsets, and total row counts', 'build a Starlette endpoint that performs full-text search on HuggingFace datasets using DuckDB FTS indexes', 'review the SQL template that executes BM25 matching on a DuckDB full-text search index and filters non-null scores', 'review the SQL template that joins FTS stage results with dataset data ordered by relevance score descending']
```

Usage

```
{'full_text_search': 'run a BM25 full-text search query against a DuckDB index file and return matching rows as a PyArrow table', 'create_response': 'create a paginated response from a PyArrow table with dataset features, row offsets, and total row counts', 'create_search_endpoint': 'build a Starlette endpoint that performs full-text search on HuggingFace datasets using DuckDB FTS indexes', 'FTS_STAGE_TABLE_COMMAND': 'review the SQL template that executes BM25 matching on a DuckDB full-text search index and filters non-null scores', 'JOIN_STAGE_AND_DATA_COMMAND': 'review the SQL template that joins FTS stage results with dataset data ordered by relevance score descending'}
```


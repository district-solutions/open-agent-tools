# Agent Python Tools

- repo: facebookresearch/reasonir
- repo_uri: https://github.com/facebookresearch/reasonir

## File: facebookresearch_reasonir/evaluation/rag/gpqa/apis/base.py

Prompts

```
["call search_api with search_engine 'offline_massiveds' to retrieve cached search results for a question", "call format_document_string with search_engine 'offline_massiveds' to format top-k retrieved passages into a readable string", 'call search_api with an unsupported search_engine to trigger a NotImplementedError', 'call format_document_string with an unsupported search_engine to trigger a NotImplementedError', 'review the search_api function to understand its dispatcher pattern and offline_massiveds search engine support', 'load original queries from a JSONL file specified by the RETRIEVED_FILE environment variable', 'load offline searched results from a JSONL file and return a query to documents mapping', 'search offline cached MassiveDS results for a list of questions and return matching passages', 'format a list of retrieved document results into a readable passage string with numbered passages', 'run the offline search API module to load searched results with a default top_k of 5']
```

Usage

```
{'search_api_offline_massiveds': "call search_api with search_engine 'offline_massiveds' to retrieve cached search results for a question", 'format_document_string_offline_massiveds': "call format_document_string with search_engine 'offline_massiveds' to format top-k retrieved passages into a readable string", 'search_api_not_implemented': 'call search_api with an unsupported search_engine to trigger a NotImplementedError', 'format_document_string_not_implemented': 'call format_document_string with an unsupported search_engine to trigger a NotImplementedError', 'review_search_api': 'review the search_api function to understand its dispatcher pattern and offline_massiveds search engine support'}
```

## File: facebookresearch_reasonir/evaluation/rag/gpqa/apis/offline_massiveds_search_api.py

Prompts

```
["call search_api with search_engine 'offline_massiveds' to retrieve cached search results for a question", "call format_document_string with search_engine 'offline_massiveds' to format top-k retrieved passages into a readable string", 'call search_api with an unsupported search_engine to trigger a NotImplementedError', 'call format_document_string with an unsupported search_engine to trigger a NotImplementedError', 'review the search_api function to understand its dispatcher pattern and offline_massiveds search engine support', 'load original queries from a JSONL file specified by the RETRIEVED_FILE environment variable', 'load offline searched results from a JSONL file and return a query to documents mapping', 'search offline cached MassiveDS results for a list of questions and return matching passages', 'format a list of retrieved document results into a readable passage string with numbered passages', 'run the offline search API module to load searched results with a default top_k of 5']
```

Usage

```
{'load_original_queries': 'load original queries from a JSONL file specified by the RETRIEVED_FILE environment variable', 'load_offline_searched_results': 'load offline searched results from a JSONL file and return a query to documents mapping', 'search_offline_cached_massiveds': 'search offline cached MassiveDS results for a list of questions and return matching passages', 'format_offline_document_string': 'format a list of retrieved document results into a readable passage string with numbered passages', 'run_offline_search_api': 'run the offline search API module to load searched results with a default top_k of 5'}
```


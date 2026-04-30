# Agent Python Tools

- repo: huggingface/cosmopedia
- repo_uri: https://github.com/huggingface/cosmopedia

## File: huggingface_cosmopedia/fulltext_search/index_docs.py

Prompts

```
['run the main function to create distributed tables, load FineWeb datasets, and index documents into ClickHouse', 'insert a batch of documents as NDJSON into a random fineweb shard via the ClickHouse bulk endpoint', 'create 64 local fineweb tables and one distributed table for full-text search with English stemming', 'flush, optimize, and freeze all 64 fineweb shard tables to finalize the search index', 'search the fineweb distributed index using a match query against all fields', 'run the sharded fulltext search script with --shard and --num_shards arguments against a local search server', 'run an elasticsearch-style query against localhost:9308/search with retry logic and a configurable number of result pages', 'run a topic search that builds boosted and match queries from category, subcategory, and subtopic fields', 'review the argparse configuration for input dataset, output dataset, n_pages, shard, and num_shards arguments', 'refactor the search_topic function to support different boosting strategies or query types for subtopic tokens']
```

Usage

```
{'run_fulltext_index_pipeline': 'run the main function to create distributed tables, load FineWeb datasets, and index documents into ClickHouse', 'insert_batch_documents': 'insert a batch of documents as NDJSON into a random fineweb shard via the ClickHouse bulk endpoint', 'create_distributed_search_tables': 'create 64 local fineweb tables and one distributed table for full-text search with English stemming', 'optimize_search_tables': 'flush, optimize, and freeze all 64 fineweb shard tables to finalize the search index', 'search_fineweb_index': 'search the fineweb distributed index using a match query against all fields'}
```

## File: huggingface_cosmopedia/fulltext_search/search_sharded.py

Prompts

```
['run the main function to create distributed tables, load FineWeb datasets, and index documents into ClickHouse', 'insert a batch of documents as NDJSON into a random fineweb shard via the ClickHouse bulk endpoint', 'create 64 local fineweb tables and one distributed table for full-text search with English stemming', 'flush, optimize, and freeze all 64 fineweb shard tables to finalize the search index', 'search the fineweb distributed index using a match query against all fields', 'run the sharded fulltext search script with --shard and --num_shards arguments against a local search server', 'run an elasticsearch-style query against localhost:9308/search with retry logic and a configurable number of result pages', 'run a topic search that builds boosted and match queries from category, subcategory, and subtopic fields', 'review the argparse configuration for input dataset, output dataset, n_pages, shard, and num_shards arguments', 'refactor the search_topic function to support different boosting strategies or query types for subtopic tokens']
```

Usage

```
{'run_search_sharded': 'run the sharded fulltext search script with --shard and --num_shards arguments against a local search server', 'run_run_query': 'run an elasticsearch-style query against localhost:9308/search with retry logic and a configurable number of result pages', 'run_search_topic': 'run a topic search that builds boosted and match queries from category, subcategory, and subtopic fields', 'review_get_args': 'review the argparse configuration for input dataset, output dataset, n_pages, shard, and num_shards arguments', 'refactor_search_topic': 'refactor the search_topic function to support different boosting strategies or query types for subtopic tokens'}
```


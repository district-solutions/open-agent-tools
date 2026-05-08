# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/end-to-end-use-cases/blog_generator/setup_qdrant_collection.py

Prompts

```
['run the script to create and populate all Qdrant collections from the NEW_COLLECTIONS config list', 'run process_file with a config dict containing file_path and collection_name to index a markdown file into Qdrant', 'create chunks from markdown text by splitting on headers with a configurable max chunk size', 'create a QdrantClient instance using the configured QDRANT_URL and QDRANT_API_KEY', 'create a SentenceTransformer embedding model using the configured all-MiniLM-L6-v2 model']
```

Usage

```
{'run_setup_all_collections': 'run the script to create and populate all Qdrant collections from the NEW_COLLECTIONS config list', 'run_process_file': 'run process_file with a config dict containing file_path and collection_name to index a markdown file into Qdrant', 'create_markdown_splitter': 'create chunks from markdown text by splitting on headers with a configurable max chunk size', 'create_qdrant_client': 'create a QdrantClient instance using the configured QDRANT_URL and QDRANT_API_KEY', 'create_embedding_model': 'create a SentenceTransformer embedding model using the configured all-MiniLM-L6-v2 model'}
```


# Agent Python Tools

- repo: facebookresearch/sphere
- repo_uri: https://github.com/facebookresearch/sphere

## File: facebookresearch_sphere/scripts/download_index.py

Prompts

```
['run the script to download a dense SPHERE index with 32 partitions to a destination directory', 'run the script to download and extract the compressed SPHERE sparse index to a destination directory', 'run the script with the overwrite flag to re-download existing index files', 'call download_file to fetch a URL with progress tracking and optional skip if file exists', 'call download_dense to download partitioned dense index files including buffer, config, meta, and faiss index', 'run an interactive dense retrieval demo that encodes queries with DPR and searches a distributed FAISS index', 'build a RetrievalClient that connects to a distributed FAISS server and loads a remote index for document retrieval', 'encode natural language questions into dense vectors using a DPR question encoder and HuggingFace tokenizer', 'search the FAISS index for top-k matching documents given query vectors with optional L2 distance conversion', 'review the RetrievalClient class and its encode_query and get_top_docs methods for dense retrieval workflows']
```

Usage

```
{'run_download_dense_index': 'run the script to download a dense SPHERE index with 32 partitions to a destination directory', 'run_download_sparse_index': 'run the script to download and extract the compressed SPHERE sparse index to a destination directory', 'run_download_with_overwrite': 'run the script with the overwrite flag to re-download existing index files', 'download_file_function': 'call download_file to fetch a URL with progress tracking and optional skip if file exists', 'download_dense_function': 'call download_dense to download partitioned dense index files including buffer, config, meta, and faiss index'}
```

## File: facebookresearch_sphere/scripts/sphere_client_demo_hf.py

Prompts

```
['run the script to download a dense SPHERE index with 32 partitions to a destination directory', 'run the script to download and extract the compressed SPHERE sparse index to a destination directory', 'run the script with the overwrite flag to re-download existing index files', 'call download_file to fetch a URL with progress tracking and optional skip if file exists', 'call download_dense to download partitioned dense index files including buffer, config, meta, and faiss index', 'run an interactive dense retrieval demo that encodes queries with DPR and searches a distributed FAISS index', 'build a RetrievalClient that connects to a distributed FAISS server and loads a remote index for document retrieval', 'encode natural language questions into dense vectors using a DPR question encoder and HuggingFace tokenizer', 'search the FAISS index for top-k matching documents given query vectors with optional L2 distance conversion', 'review the RetrievalClient class and its encode_query and get_top_docs methods for dense retrieval workflows']
```

Usage

```
{'run_dense_retrieval_demo': 'run an interactive dense retrieval demo that encodes queries with DPR and searches a distributed FAISS index', 'build_retrieval_client': 'build a RetrievalClient that connects to a distributed FAISS server and loads a remote index for document retrieval', 'encode_query_with_dpr': 'encode natural language questions into dense vectors using a DPR question encoder and HuggingFace tokenizer', 'search_top_documents': 'search the FAISS index for top-k matching documents given query vectors with optional L2 distance conversion', 'review_retrieval_client_class': 'review the RetrievalClient class and its encode_query and get_top_docs methods for dense retrieval workflows'}
```


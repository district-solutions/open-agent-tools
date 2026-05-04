# Agent Python Tools

- repo: facebookresearch/drqa
- repo_uri: https://github.com/facebookresearch/drqa

## File: facebookresearch_drqa/drqa/retriever/doc_db.py

Prompts

```
['create a DocDB instance by passing a sqlite database file path to the constructor', 'use DocDB as a context manager with the with statement to auto close the connection', 'call get_doc_ids on a DocDB instance to fetch all document ids stored in the database', 'call get_doc_text with a doc_id to fetch the raw text of a specific document', 'call close on a DocDB instance to close the underlying sqlite database connection', 'create an ElasticDocRanker instance to connect to an ElasticSearch server for document ranking', 'find the k closest documents to a query string using ElasticSearch multi-match search', 'batch search for closest documents across multiple queries using multithreaded ElasticSearch requests', 'convert a document id to its ElasticSearch internal index using get_doc_index', 'fetch the raw text content of a document by its doc_id from ElasticSearch', 'build a TfidfDocRanker instance that loads a pre-weighted inverted index from a saved model file', 'run closest_docs on a TfidfDocRanker to find the top k most relevant documents for a query', 'run batch_closest_docs on a TfidfDocRanker to multithreadedly rank documents for multiple queries at once', 'review the text2spvec method to understand how queries are converted into sparse TF-IDF weighted vectors', 'review the parse method to see how queries are tokenized into ngrams with filtering', 'save a scipy sparse CSR matrix to disk using numpy savez format with optional metadata', 'load a scipy sparse CSR matrix from a numpy savez file and return it with metadata', 'compute an unsigned 32 bit murmurhash for a token string with configurable feature hash buckets', 'decide whether to keep or discard an n-gram based on any, all, or ends filter mode', 'retrieve a nested subfield value from a dictionary using a list of field keys']
```

Usage

```
{'create_docdb_instance': 'create a DocDB instance by passing a sqlite database file path to the constructor', 'use_docdb_context_manager': 'use DocDB as a context manager with the with statement to auto close the connection', 'get_doc_ids': 'call get_doc_ids on a DocDB instance to fetch all document ids stored in the database', 'get_doc_text': 'call get_doc_text with a doc_id to fetch the raw text of a specific document', 'close_docdb_connection': 'call close on a DocDB instance to close the underlying sqlite database connection'}
```

## File: facebookresearch_drqa/drqa/retriever/elastic_doc_ranker.py

Prompts

```
['create a DocDB instance by passing a sqlite database file path to the constructor', 'use DocDB as a context manager with the with statement to auto close the connection', 'call get_doc_ids on a DocDB instance to fetch all document ids stored in the database', 'call get_doc_text with a doc_id to fetch the raw text of a specific document', 'call close on a DocDB instance to close the underlying sqlite database connection', 'create an ElasticDocRanker instance to connect to an ElasticSearch server for document ranking', 'find the k closest documents to a query string using ElasticSearch multi-match search', 'batch search for closest documents across multiple queries using multithreaded ElasticSearch requests', 'convert a document id to its ElasticSearch internal index using get_doc_index', 'fetch the raw text content of a document by its doc_id from ElasticSearch', 'build a TfidfDocRanker instance that loads a pre-weighted inverted index from a saved model file', 'run closest_docs on a TfidfDocRanker to find the top k most relevant documents for a query', 'run batch_closest_docs on a TfidfDocRanker to multithreadedly rank documents for multiple queries at once', 'review the text2spvec method to understand how queries are converted into sparse TF-IDF weighted vectors', 'review the parse method to see how queries are tokenized into ngrams with filtering', 'save a scipy sparse CSR matrix to disk using numpy savez format with optional metadata', 'load a scipy sparse CSR matrix from a numpy savez file and return it with metadata', 'compute an unsigned 32 bit murmurhash for a token string with configurable feature hash buckets', 'decide whether to keep or discard an n-gram based on any, all, or ends filter mode', 'retrieve a nested subfield value from a dictionary using a list of field keys']
```

Usage

```
{'create_elastic_doc_ranker': 'create an ElasticDocRanker instance to connect to an ElasticSearch server for document ranking', 'find_closest_docs': 'find the k closest documents to a query string using ElasticSearch multi-match search', 'batch_search_closest_docs': 'batch search for closest documents across multiple queries using multithreaded ElasticSearch requests', 'convert_doc_id_to_index': 'convert a document id to its ElasticSearch internal index using get_doc_index', 'fetch_doc_text': 'fetch the raw text content of a document by its doc_id from ElasticSearch'}
```

## File: facebookresearch_drqa/drqa/retriever/tfidf_doc_ranker.py

Prompts

```
['create a DocDB instance by passing a sqlite database file path to the constructor', 'use DocDB as a context manager with the with statement to auto close the connection', 'call get_doc_ids on a DocDB instance to fetch all document ids stored in the database', 'call get_doc_text with a doc_id to fetch the raw text of a specific document', 'call close on a DocDB instance to close the underlying sqlite database connection', 'create an ElasticDocRanker instance to connect to an ElasticSearch server for document ranking', 'find the k closest documents to a query string using ElasticSearch multi-match search', 'batch search for closest documents across multiple queries using multithreaded ElasticSearch requests', 'convert a document id to its ElasticSearch internal index using get_doc_index', 'fetch the raw text content of a document by its doc_id from ElasticSearch', 'build a TfidfDocRanker instance that loads a pre-weighted inverted index from a saved model file', 'run closest_docs on a TfidfDocRanker to find the top k most relevant documents for a query', 'run batch_closest_docs on a TfidfDocRanker to multithreadedly rank documents for multiple queries at once', 'review the text2spvec method to understand how queries are converted into sparse TF-IDF weighted vectors', 'review the parse method to see how queries are tokenized into ngrams with filtering', 'save a scipy sparse CSR matrix to disk using numpy savez format with optional metadata', 'load a scipy sparse CSR matrix from a numpy savez file and return it with metadata', 'compute an unsigned 32 bit murmurhash for a token string with configurable feature hash buckets', 'decide whether to keep or discard an n-gram based on any, all, or ends filter mode', 'retrieve a nested subfield value from a dictionary using a list of field keys']
```

Usage

```
{'build_TfidfDocRanker': 'build a TfidfDocRanker instance that loads a pre-weighted inverted index from a saved model file', 'run_closest_docs': 'run closest_docs on a TfidfDocRanker to find the top k most relevant documents for a query', 'run_batch_closest_docs': 'run batch_closest_docs on a TfidfDocRanker to multithreadedly rank documents for multiple queries at once', 'review_text2spvec': 'review the text2spvec method to understand how queries are converted into sparse TF-IDF weighted vectors', 'review_parse': 'review the parse method to see how queries are tokenized into ngrams with filtering'}
```

## File: facebookresearch_drqa/drqa/retriever/utils.py

Prompts

```
['create a DocDB instance by passing a sqlite database file path to the constructor', 'use DocDB as a context manager with the with statement to auto close the connection', 'call get_doc_ids on a DocDB instance to fetch all document ids stored in the database', 'call get_doc_text with a doc_id to fetch the raw text of a specific document', 'call close on a DocDB instance to close the underlying sqlite database connection', 'create an ElasticDocRanker instance to connect to an ElasticSearch server for document ranking', 'find the k closest documents to a query string using ElasticSearch multi-match search', 'batch search for closest documents across multiple queries using multithreaded ElasticSearch requests', 'convert a document id to its ElasticSearch internal index using get_doc_index', 'fetch the raw text content of a document by its doc_id from ElasticSearch', 'build a TfidfDocRanker instance that loads a pre-weighted inverted index from a saved model file', 'run closest_docs on a TfidfDocRanker to find the top k most relevant documents for a query', 'run batch_closest_docs on a TfidfDocRanker to multithreadedly rank documents for multiple queries at once', 'review the text2spvec method to understand how queries are converted into sparse TF-IDF weighted vectors', 'review the parse method to see how queries are tokenized into ngrams with filtering', 'save a scipy sparse CSR matrix to disk using numpy savez format with optional metadata', 'load a scipy sparse CSR matrix from a numpy savez file and return it with metadata', 'compute an unsigned 32 bit murmurhash for a token string with configurable feature hash buckets', 'decide whether to keep or discard an n-gram based on any, all, or ends filter mode', 'retrieve a nested subfield value from a dictionary using a list of field keys']
```

Usage

```
{'save_sparse_csr': 'save a scipy sparse CSR matrix to disk using numpy savez format with optional metadata', 'load_sparse_csr': 'load a scipy sparse CSR matrix from a numpy savez file and return it with metadata', 'hash': 'compute an unsigned 32 bit murmurhash for a token string with configurable feature hash buckets', 'filter_ngram': 'decide whether to keep or discard an n-gram based on any, all, or ends filter mode', 'get_field': 'retrieve a nested subfield value from a dictionary using a list of field keys'}
```


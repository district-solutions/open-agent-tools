# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/tfidf_retriever/build_tfidf.py

Prompts

```
['run the tfidf retriever script to build tf-idf document matrices from a document database', 'build a sparse word-to-document count matrix using multiprocessing and hashed ngrams from a DocDB', 'convert a word count sparse matrix into a tf-idf weighted matrix using log term frequency', 'compute the number of documents each word appears in from a count matrix', 'compute hashed ngram counts for a given text and return sparse matrix row, column, and data', 'create a DocDB instance connected to a sqlite database at a given path', 'fetch all document ids stored in the sqlite documents table using get_doc_ids', 'retrieve the raw text content for a given document id using get_doc_text', 'retrieve the stored value field for a given document id using get_doc_value', 'add multiple document triples to the sqlite database using the add method', 'initialize a TfidfDocRanker from a saved TF-IDF model file path', 'find the k closest documents to a query using TF-IDF dot product scoring', 'convert a text query into a sparse TF-IDF weighted word vector', 'parse a query string into n-gram tokens using the configured tokenizer', 'convert a document index to its corresponding document ID', 'build a TFIDF-based retriever agent that stores entries in a SQLite database and builds a sparse TFIDF matrix', 'create command-line arguments for the retriever including ngram size, hash size, tokenizer type, and retrieval mode', 'test the train_act method that processes observations with labels and queues document triples for TFIDF index rebuilding', 'run the act method to retrieve closest documents from the TFIDF matrix using sparse matrix multiplication', 'review the doc2txt method that retrieves document text or values from the database by document ID based on retrieval mode', 'save a scipy sparse CSR matrix to disk as an NPZ file with optional metadata', 'load a scipy sparse CSR matrix from an NPZ file and return the matrix and metadata', 'compute an unsigned 32-bit murmurhash of a token for feature hashing into a fixed number of buckets', 'filter out English stopwords and punctuation tokens from text using a predefined STOPWORDS set', 'compute the cosine similarity between two scipy sparse row vectors and return a float']
```

Usage

```
{'run_build_tfidf': 'run the tfidf retriever script to build tf-idf document matrices from a document database', 'get_count_matrix': 'build a sparse word-to-document count matrix using multiprocessing and hashed ngrams from a DocDB', 'get_tfidf_matrix': 'convert a word count sparse matrix into a tf-idf weighted matrix using log term frequency', 'get_doc_freqs': 'compute the number of documents each word appears in from a count matrix', 'count_text': 'compute hashed ngram counts for a given text and return sparse matrix row, column, and data'}
```

## File: facebookresearch_parlai/parlai/agents/tfidf_retriever/doc_db.py

Prompts

```
['run the tfidf retriever script to build tf-idf document matrices from a document database', 'build a sparse word-to-document count matrix using multiprocessing and hashed ngrams from a DocDB', 'convert a word count sparse matrix into a tf-idf weighted matrix using log term frequency', 'compute the number of documents each word appears in from a count matrix', 'compute hashed ngram counts for a given text and return sparse matrix row, column, and data', 'create a DocDB instance connected to a sqlite database at a given path', 'fetch all document ids stored in the sqlite documents table using get_doc_ids', 'retrieve the raw text content for a given document id using get_doc_text', 'retrieve the stored value field for a given document id using get_doc_value', 'add multiple document triples to the sqlite database using the add method', 'initialize a TfidfDocRanker from a saved TF-IDF model file path', 'find the k closest documents to a query using TF-IDF dot product scoring', 'convert a text query into a sparse TF-IDF weighted word vector', 'parse a query string into n-gram tokens using the configured tokenizer', 'convert a document index to its corresponding document ID', 'build a TFIDF-based retriever agent that stores entries in a SQLite database and builds a sparse TFIDF matrix', 'create command-line arguments for the retriever including ngram size, hash size, tokenizer type, and retrieval mode', 'test the train_act method that processes observations with labels and queues document triples for TFIDF index rebuilding', 'run the act method to retrieve closest documents from the TFIDF matrix using sparse matrix multiplication', 'review the doc2txt method that retrieves document text or values from the database by document ID based on retrieval mode', 'save a scipy sparse CSR matrix to disk as an NPZ file with optional metadata', 'load a scipy sparse CSR matrix from an NPZ file and return the matrix and metadata', 'compute an unsigned 32-bit murmurhash of a token for feature hashing into a fixed number of buckets', 'filter out English stopwords and punctuation tokens from text using a predefined STOPWORDS set', 'compute the cosine similarity between two scipy sparse row vectors and return a float']
```

Usage

```
{'create_docdb_instance': 'create a DocDB instance connected to a sqlite database at a given path', 'fetch_all_doc_ids': 'fetch all document ids stored in the sqlite documents table using get_doc_ids', 'retrieve_doc_text': 'retrieve the raw text content for a given document id using get_doc_text', 'retrieve_doc_value': 'retrieve the stored value field for a given document id using get_doc_value', 'add_documents': 'add multiple document triples to the sqlite database using the add method'}
```

## File: facebookresearch_parlai/parlai/agents/tfidf_retriever/tfidf_doc_ranker.py

Prompts

```
['run the tfidf retriever script to build tf-idf document matrices from a document database', 'build a sparse word-to-document count matrix using multiprocessing and hashed ngrams from a DocDB', 'convert a word count sparse matrix into a tf-idf weighted matrix using log term frequency', 'compute the number of documents each word appears in from a count matrix', 'compute hashed ngram counts for a given text and return sparse matrix row, column, and data', 'create a DocDB instance connected to a sqlite database at a given path', 'fetch all document ids stored in the sqlite documents table using get_doc_ids', 'retrieve the raw text content for a given document id using get_doc_text', 'retrieve the stored value field for a given document id using get_doc_value', 'add multiple document triples to the sqlite database using the add method', 'initialize a TfidfDocRanker from a saved TF-IDF model file path', 'find the k closest documents to a query using TF-IDF dot product scoring', 'convert a text query into a sparse TF-IDF weighted word vector', 'parse a query string into n-gram tokens using the configured tokenizer', 'convert a document index to its corresponding document ID', 'build a TFIDF-based retriever agent that stores entries in a SQLite database and builds a sparse TFIDF matrix', 'create command-line arguments for the retriever including ngram size, hash size, tokenizer type, and retrieval mode', 'test the train_act method that processes observations with labels and queues document triples for TFIDF index rebuilding', 'run the act method to retrieve closest documents from the TFIDF matrix using sparse matrix multiplication', 'review the doc2txt method that retrieves document text or values from the database by document ID based on retrieval mode', 'save a scipy sparse CSR matrix to disk as an NPZ file with optional metadata', 'load a scipy sparse CSR matrix from an NPZ file and return the matrix and metadata', 'compute an unsigned 32-bit murmurhash of a token for feature hashing into a fixed number of buckets', 'filter out English stopwords and punctuation tokens from text using a predefined STOPWORDS set', 'compute the cosine similarity between two scipy sparse row vectors and return a float']
```

Usage

```
{'init_TfidfDocRanker': 'initialize a TfidfDocRanker from a saved TF-IDF model file path', 'closest_docs': 'find the k closest documents to a query using TF-IDF dot product scoring', 'text2spvec': 'convert a text query into a sparse TF-IDF weighted word vector', 'parse': 'parse a query string into n-gram tokens using the configured tokenizer', 'get_doc_id': 'convert a document index to its corresponding document ID'}
```

## File: facebookresearch_parlai/parlai/agents/tfidf_retriever/tfidf_retriever.py

Prompts

```
['run the tfidf retriever script to build tf-idf document matrices from a document database', 'build a sparse word-to-document count matrix using multiprocessing and hashed ngrams from a DocDB', 'convert a word count sparse matrix into a tf-idf weighted matrix using log term frequency', 'compute the number of documents each word appears in from a count matrix', 'compute hashed ngram counts for a given text and return sparse matrix row, column, and data', 'create a DocDB instance connected to a sqlite database at a given path', 'fetch all document ids stored in the sqlite documents table using get_doc_ids', 'retrieve the raw text content for a given document id using get_doc_text', 'retrieve the stored value field for a given document id using get_doc_value', 'add multiple document triples to the sqlite database using the add method', 'initialize a TfidfDocRanker from a saved TF-IDF model file path', 'find the k closest documents to a query using TF-IDF dot product scoring', 'convert a text query into a sparse TF-IDF weighted word vector', 'parse a query string into n-gram tokens using the configured tokenizer', 'convert a document index to its corresponding document ID', 'build a TFIDF-based retriever agent that stores entries in a SQLite database and builds a sparse TFIDF matrix', 'create command-line arguments for the retriever including ngram size, hash size, tokenizer type, and retrieval mode', 'test the train_act method that processes observations with labels and queues document triples for TFIDF index rebuilding', 'run the act method to retrieve closest documents from the TFIDF matrix using sparse matrix multiplication', 'review the doc2txt method that retrieves document text or values from the database by document ID based on retrieval mode', 'save a scipy sparse CSR matrix to disk as an NPZ file with optional metadata', 'load a scipy sparse CSR matrix from an NPZ file and return the matrix and metadata', 'compute an unsigned 32-bit murmurhash of a token for feature hashing into a fixed number of buckets', 'filter out English stopwords and punctuation tokens from text using a predefined STOPWORDS set', 'compute the cosine similarity between two scipy sparse row vectors and return a float']
```

Usage

```
{'build_tfidf_retriever_agent': 'build a TFIDF-based retriever agent that stores entries in a SQLite database and builds a sparse TFIDF matrix', 'create_cmdline_args': 'create command-line arguments for the retriever including ngram size, hash size, tokenizer type, and retrieval mode', 'test_train_act': 'test the train_act method that processes observations with labels and queues document triples for TFIDF index rebuilding', 'run_act_retrieval': 'run the act method to retrieve closest documents from the TFIDF matrix using sparse matrix multiplication', 'review_doc2txt': 'review the doc2txt method that retrieves document text or values from the database by document ID based on retrieval mode'}
```

## File: facebookresearch_parlai/parlai/agents/tfidf_retriever/utils.py

Prompts

```
['run the tfidf retriever script to build tf-idf document matrices from a document database', 'build a sparse word-to-document count matrix using multiprocessing and hashed ngrams from a DocDB', 'convert a word count sparse matrix into a tf-idf weighted matrix using log term frequency', 'compute the number of documents each word appears in from a count matrix', 'compute hashed ngram counts for a given text and return sparse matrix row, column, and data', 'create a DocDB instance connected to a sqlite database at a given path', 'fetch all document ids stored in the sqlite documents table using get_doc_ids', 'retrieve the raw text content for a given document id using get_doc_text', 'retrieve the stored value field for a given document id using get_doc_value', 'add multiple document triples to the sqlite database using the add method', 'initialize a TfidfDocRanker from a saved TF-IDF model file path', 'find the k closest documents to a query using TF-IDF dot product scoring', 'convert a text query into a sparse TF-IDF weighted word vector', 'parse a query string into n-gram tokens using the configured tokenizer', 'convert a document index to its corresponding document ID', 'build a TFIDF-based retriever agent that stores entries in a SQLite database and builds a sparse TFIDF matrix', 'create command-line arguments for the retriever including ngram size, hash size, tokenizer type, and retrieval mode', 'test the train_act method that processes observations with labels and queues document triples for TFIDF index rebuilding', 'run the act method to retrieve closest documents from the TFIDF matrix using sparse matrix multiplication', 'review the doc2txt method that retrieves document text or values from the database by document ID based on retrieval mode', 'save a scipy sparse CSR matrix to disk as an NPZ file with optional metadata', 'load a scipy sparse CSR matrix from an NPZ file and return the matrix and metadata', 'compute an unsigned 32-bit murmurhash of a token for feature hashing into a fixed number of buckets', 'filter out English stopwords and punctuation tokens from text using a predefined STOPWORDS set', 'compute the cosine similarity between two scipy sparse row vectors and return a float']
```

Usage

```
{'save_sparse_csr_matrix': 'save a scipy sparse CSR matrix to disk as an NPZ file with optional metadata', 'load_sparse_csr_matrix': 'load a scipy sparse CSR matrix from an NPZ file and return the matrix and metadata', 'hash_token_murmur': 'compute an unsigned 32-bit murmurhash of a token for feature hashing into a fixed number of buckets', 'filter_stopword_and_punctuation': 'filter out English stopwords and punctuation tokens from text using a predefined STOPWORDS set', 'compute_cosine_similarity': 'compute the cosine similarity between two scipy sparse row vectors and return a float'}
```


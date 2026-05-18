# Agent Python Tools

- repo: facebookresearch/npm
- repo_uri: https://github.com/facebookresearch/npm

## File: facebookresearch_npm/npm/dstore.py

Prompts

```
['create a DataStore instance to load Wikipedia corpus data with embeddings and FAISS index for nearest neighbor search', 'search the FAISS index with query embeddings to retrieve top-k nearest neighbor token indices and scores', 'load precomputed token embeddings from a model directory as memory-mapped float16 numpy arrays', 'train an IVFPQ FAISS index on a sampled subset of embeddings using GPU acceleration', 'get the decoded text context around a specific token index using a provided decode function', 'load a SingleModel from HuggingFace Hub using checkpoint path like facebook/npm-single', 'load a SingleModel from a local PyTorch checkpoint file with state_dict extraction', 'run a forward pass on SingleModel with input_ids and index to get logits and query embeddings', 'load a Model from HuggingFace Hub using checkpoint path like facebook/npm for span prediction', 'run a forward pass on Model with input_ids and index to get logits and start and end query embeddings', 'predict answer spans from a query text using the NPM model with configurable alpha values', 'compute concatenated start and end scores for query tensors across the document store', 'extract the query embedding tensor from an input text containing a mask token', 'evaluate open-domain QA predictions against reference answers and print exact match accuracy', 'review the NPM class that extends NPMSingle for neural passage retrieval and span prediction', 'predict label probabilities for input text using the NPMSingle model with a label to id mapping', 'evaluate the NPMSingle model on a task dataset and print accuracy metrics', 'get k-nearest neighbor scores and optional context for token prediction queries', 'initialize a label to word token id mapping from a synonym dictionary', 'generate a stopword mask array that suppresses specified token ids in the vocabulary', 'build a BM25 search index from a JSON data directory using pyserini Lucene', 'search the BM25 index with a query string and return top k document IDs', 'batch search the BM25 index with multiple queries and return lists of document IDs', 'batch search using a Task object to retrieve restricted document indices for examples', 'batch search using a precomputed dictionary of string to document ID mappings']
```

Usage

```
{'create_datastore_for_wikipedia': 'create a DataStore instance to load Wikipedia corpus data with embeddings and FAISS index for nearest neighbor search', 'search_embeddings_with_faiss': 'search the FAISS index with query embeddings to retrieve top-k nearest neighbor token indices and scores', 'load_token_embeddings': 'load precomputed token embeddings from a model directory as memory-mapped float16 numpy arrays', 'train_faiss_index': 'train an IVFPQ FAISS index on a sampled subset of embeddings using GPU acceleration', 'get_context_for_token': 'get the decoded text context around a specific token index using a provided decode function'}
```

## File: facebookresearch_npm/npm/model.py

Prompts

```
['create a DataStore instance to load Wikipedia corpus data with embeddings and FAISS index for nearest neighbor search', 'search the FAISS index with query embeddings to retrieve top-k nearest neighbor token indices and scores', 'load precomputed token embeddings from a model directory as memory-mapped float16 numpy arrays', 'train an IVFPQ FAISS index on a sampled subset of embeddings using GPU acceleration', 'get the decoded text context around a specific token index using a provided decode function', 'load a SingleModel from HuggingFace Hub using checkpoint path like facebook/npm-single', 'load a SingleModel from a local PyTorch checkpoint file with state_dict extraction', 'run a forward pass on SingleModel with input_ids and index to get logits and query embeddings', 'load a Model from HuggingFace Hub using checkpoint path like facebook/npm for span prediction', 'run a forward pass on Model with input_ids and index to get logits and start and end query embeddings', 'predict answer spans from a query text using the NPM model with configurable alpha values', 'compute concatenated start and end scores for query tensors across the document store', 'extract the query embedding tensor from an input text containing a mask token', 'evaluate open-domain QA predictions against reference answers and print exact match accuracy', 'review the NPM class that extends NPMSingle for neural passage retrieval and span prediction', 'predict label probabilities for input text using the NPMSingle model with a label to id mapping', 'evaluate the NPMSingle model on a task dataset and print accuracy metrics', 'get k-nearest neighbor scores and optional context for token prediction queries', 'initialize a label to word token id mapping from a synonym dictionary', 'generate a stopword mask array that suppresses specified token ids in the vocabulary', 'build a BM25 search index from a JSON data directory using pyserini Lucene', 'search the BM25 index with a query string and return top k document IDs', 'batch search the BM25 index with multiple queries and return lists of document IDs', 'batch search using a Task object to retrieve restricted document indices for examples', 'batch search using a precomputed dictionary of string to document ID mappings']
```

Usage

```
{'load_single_model_from_hf_hub': 'load a SingleModel from HuggingFace Hub using checkpoint path like facebook/npm-single', 'load_single_model_from_local_checkpoint': 'load a SingleModel from a local PyTorch checkpoint file with state_dict extraction', 'run_single_model_forward_pass': 'run a forward pass on SingleModel with input_ids and index to get logits and query embeddings', 'load_model_from_hf_hub': 'load a Model from HuggingFace Hub using checkpoint path like facebook/npm for span prediction', 'run_model_forward_pass': 'run a forward pass on Model with input_ids and index to get logits and start and end query embeddings'}
```

## File: facebookresearch_npm/npm/npm.py

Prompts

```
['create a DataStore instance to load Wikipedia corpus data with embeddings and FAISS index for nearest neighbor search', 'search the FAISS index with query embeddings to retrieve top-k nearest neighbor token indices and scores', 'load precomputed token embeddings from a model directory as memory-mapped float16 numpy arrays', 'train an IVFPQ FAISS index on a sampled subset of embeddings using GPU acceleration', 'get the decoded text context around a specific token index using a provided decode function', 'load a SingleModel from HuggingFace Hub using checkpoint path like facebook/npm-single', 'load a SingleModel from a local PyTorch checkpoint file with state_dict extraction', 'run a forward pass on SingleModel with input_ids and index to get logits and query embeddings', 'load a Model from HuggingFace Hub using checkpoint path like facebook/npm for span prediction', 'run a forward pass on Model with input_ids and index to get logits and start and end query embeddings', 'predict answer spans from a query text using the NPM model with configurable alpha values', 'compute concatenated start and end scores for query tensors across the document store', 'extract the query embedding tensor from an input text containing a mask token', 'evaluate open-domain QA predictions against reference answers and print exact match accuracy', 'review the NPM class that extends NPMSingle for neural passage retrieval and span prediction', 'predict label probabilities for input text using the NPMSingle model with a label to id mapping', 'evaluate the NPMSingle model on a task dataset and print accuracy metrics', 'get k-nearest neighbor scores and optional context for token prediction queries', 'initialize a label to word token id mapping from a synonym dictionary', 'generate a stopword mask array that suppresses specified token ids in the vocabulary', 'build a BM25 search index from a JSON data directory using pyserini Lucene', 'search the BM25 index with a query string and return top k document IDs', 'batch search the BM25 index with multiple queries and return lists of document IDs', 'batch search using a Task object to retrieve restricted document indices for examples', 'batch search using a precomputed dictionary of string to document ID mappings']
```

Usage

```
{'predict_span_NPM': 'predict answer spans from a query text using the NPM model with configurable alpha values', 'get_all_scores_NPM': 'compute concatenated start and end scores for query tensors across the document store', 'get_query_NPM': 'extract the query embedding tensor from an input text containing a mask token', 'evaluate_open_NPM': 'evaluate open-domain QA predictions against reference answers and print exact match accuracy', 'review_NPM_class': 'review the NPM class that extends NPMSingle for neural passage retrieval and span prediction'}
```

## File: facebookresearch_npm/npm/npm_single.py

Prompts

```
['create a DataStore instance to load Wikipedia corpus data with embeddings and FAISS index for nearest neighbor search', 'search the FAISS index with query embeddings to retrieve top-k nearest neighbor token indices and scores', 'load precomputed token embeddings from a model directory as memory-mapped float16 numpy arrays', 'train an IVFPQ FAISS index on a sampled subset of embeddings using GPU acceleration', 'get the decoded text context around a specific token index using a provided decode function', 'load a SingleModel from HuggingFace Hub using checkpoint path like facebook/npm-single', 'load a SingleModel from a local PyTorch checkpoint file with state_dict extraction', 'run a forward pass on SingleModel with input_ids and index to get logits and query embeddings', 'load a Model from HuggingFace Hub using checkpoint path like facebook/npm for span prediction', 'run a forward pass on Model with input_ids and index to get logits and start and end query embeddings', 'predict answer spans from a query text using the NPM model with configurable alpha values', 'compute concatenated start and end scores for query tensors across the document store', 'extract the query embedding tensor from an input text containing a mask token', 'evaluate open-domain QA predictions against reference answers and print exact match accuracy', 'review the NPM class that extends NPMSingle for neural passage retrieval and span prediction', 'predict label probabilities for input text using the NPMSingle model with a label to id mapping', 'evaluate the NPMSingle model on a task dataset and print accuracy metrics', 'get k-nearest neighbor scores and optional context for token prediction queries', 'initialize a label to word token id mapping from a synonym dictionary', 'generate a stopword mask array that suppresses specified token ids in the vocabulary', 'build a BM25 search index from a JSON data directory using pyserini Lucene', 'search the BM25 index with a query string and return top k document IDs', 'batch search the BM25 index with multiple queries and return lists of document IDs', 'batch search using a Task object to retrieve restricted document indices for examples', 'batch search using a precomputed dictionary of string to document ID mappings']
```

Usage

```
{'predict_NPMSingle': 'predict label probabilities for input text using the NPMSingle model with a label to id mapping', 'evaluate_NPMSingle': 'evaluate the NPMSingle model on a task dataset and print accuracy metrics', 'get_knn_scores_NPMSingle': 'get k-nearest neighbor scores and optional context for token prediction queries', 'init_label2word_id_NPMSingle': 'initialize a label to word token id mapping from a synonym dictionary', 'get_stopword_mask_NPMSingle': 'generate a stopword mask array that suppresses specified token ids in the vocabulary'}
```

## File: facebookresearch_npm/npm/searcher.py

Prompts

```
['create a DataStore instance to load Wikipedia corpus data with embeddings and FAISS index for nearest neighbor search', 'search the FAISS index with query embeddings to retrieve top-k nearest neighbor token indices and scores', 'load precomputed token embeddings from a model directory as memory-mapped float16 numpy arrays', 'train an IVFPQ FAISS index on a sampled subset of embeddings using GPU acceleration', 'get the decoded text context around a specific token index using a provided decode function', 'load a SingleModel from HuggingFace Hub using checkpoint path like facebook/npm-single', 'load a SingleModel from a local PyTorch checkpoint file with state_dict extraction', 'run a forward pass on SingleModel with input_ids and index to get logits and query embeddings', 'load a Model from HuggingFace Hub using checkpoint path like facebook/npm for span prediction', 'run a forward pass on Model with input_ids and index to get logits and start and end query embeddings', 'predict answer spans from a query text using the NPM model with configurable alpha values', 'compute concatenated start and end scores for query tensors across the document store', 'extract the query embedding tensor from an input text containing a mask token', 'evaluate open-domain QA predictions against reference answers and print exact match accuracy', 'review the NPM class that extends NPMSingle for neural passage retrieval and span prediction', 'predict label probabilities for input text using the NPMSingle model with a label to id mapping', 'evaluate the NPMSingle model on a task dataset and print accuracy metrics', 'get k-nearest neighbor scores and optional context for token prediction queries', 'initialize a label to word token id mapping from a synonym dictionary', 'generate a stopword mask array that suppresses specified token ids in the vocabulary', 'build a BM25 search index from a JSON data directory using pyserini Lucene', 'search the BM25 index with a query string and return top k document IDs', 'batch search the BM25 index with multiple queries and return lists of document IDs', 'batch search using a Task object to retrieve restricted document indices for examples', 'batch search using a precomputed dictionary of string to document ID mappings']
```

Usage

```
{'build_bm25_index': 'build a BM25 search index from a JSON data directory using pyserini Lucene', 'search_bm25_documents': 'search the BM25 index with a query string and return top k document IDs', 'batch_search_bm25': 'batch search the BM25 index with multiple queries and return lists of document IDs', 'batch_search_with_task': 'batch search using a Task object to retrieve restricted document indices for examples', 'batch_search_with_dict': 'batch search using a precomputed dictionary of string to document ID mappings'}
```


# Agent Python Tools

- repo: facebookresearch/dpr-scale
- repo_uri: https://github.com/facebookresearch/dpr-scale

## File: facebookresearch_dpr-scale/spar/spar_retrieval.py

Prompts

```
['run SPAR retrieval by combining two model embeddings with configurable pooling and weights for dense search', 'build a FAISS inner product index from PyTorch vectors in configurable batch sizes', 'perform dense vector search against a FAISS index and return top-k passage results with scores', 'load passages from a TSV file with id, title, and text columns into a list of dictionaries', 'load and concatenate sharded passage embedding pickle files from a directory into a single tensor', 'run a grid search over concat weights to find the best fusion weight for two DPR retrieval models', 'rerank predictions from two DPR models using weighted score fusion and joint-pool re-ranking', 'run grid search weight tuning across multiple datasets like NQ, SQuAD, TriviaQA, WebQuestions, and TREC', 'load and concatenate passage embedding vectors from pickled shard files in a context embeddings directory', 'load query embedding vectors from a pickled file in a context embeddings directory']
```

Usage

```
{'run_spar_retrieval': 'run SPAR retrieval by combining two model embeddings with configurable pooling and weights for dense search', 'build_index': 'build a FAISS inner product index from PyTorch vectors in configurable batch sizes', 'dense_search': 'perform dense vector search against a FAISS index and return top-k passage results with scores', 'load_passages_tsv': 'load passages from a TSV file with id, title, and text columns into a list of dictionaries', 'load_passage_embeddings': 'load and concatenate sharded passage embedding pickle files from a directory into a single tensor'}
```

## File: facebookresearch_dpr-scale/spar/spar_weight_tuning.py

Prompts

```
['run SPAR retrieval by combining two model embeddings with configurable pooling and weights for dense search', 'build a FAISS inner product index from PyTorch vectors in configurable batch sizes', 'perform dense vector search against a FAISS index and return top-k passage results with scores', 'load passages from a TSV file with id, title, and text columns into a list of dictionaries', 'load and concatenate sharded passage embedding pickle files from a directory into a single tensor', 'run a grid search over concat weights to find the best fusion weight for two DPR retrieval models', 'rerank predictions from two DPR models using weighted score fusion and joint-pool re-ranking', 'run grid search weight tuning across multiple datasets like NQ, SQuAD, TriviaQA, WebQuestions, and TREC', 'load and concatenate passage embedding vectors from pickled shard files in a context embeddings directory', 'load query embedding vectors from a pickled file in a context embeddings directory']
```

Usage

```
{'run_grid_search_weights': 'run a grid search over concat weights to find the best fusion weight for two DPR retrieval models', 'run_rerank_two_predictions': 'rerank predictions from two DPR models using weighted score fusion and joint-pool re-ranking', 'run_grid_search_multiset': 'run grid search weight tuning across multiple datasets like NQ, SQuAD, TriviaQA, WebQuestions, and TREC', 'run_load_passage_embeddings': 'load and concatenate passage embedding vectors from pickled shard files in a context embeddings directory', 'run_load_query_embeddings': 'load query embedding vectors from a pickled file in a context embeddings directory'}
```


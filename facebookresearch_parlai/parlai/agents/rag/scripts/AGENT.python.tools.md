# Agent Python Tools

- repo: facebookresearch/parlai
- repo_uri: https://github.com/facebookresearch/parlai

## File: facebookresearch_parlai/parlai/agents/rag/scripts/generate_dense_embeddings.py

Prompts

```
['run the Generator script to generate dense embeddings from a passages TSV file for a FAISS index', 'encode passages using a TorchRankerAgent candidate encoder and return passage embeddings as a tensor', 'load passages from a TSV file and shard them by shard id and number of shards', 'save encoded passage embeddings and corresponding document IDs to separate PyTorch files', 'setup command line arguments for passages file, output file, num shards, shard id, and DPR model flag', 'run the Indexer script to create a FAISS index from dense embedding files in a directory', 'index PyTorch embedding files into a FAISS index using the Indexer class index_data method', 'train and add embeddings to a compressed FAISS indexer using the train_then_add method', 'setup command-line arguments for the Indexer including embeddings-dir, num-shards, and shard-id options', 'serialize and save a FAISS index to disk after indexing dense embeddings']
```

Usage

```
{'run_Generator_dense_embeddings': 'run the Generator script to generate dense embeddings from a passages TSV file for a FAISS index', 'encode_passages_with_model': 'encode passages using a TorchRankerAgent candidate encoder and return passage embeddings as a tensor', 'load_passages_from_tsv': 'load passages from a TSV file and shard them by shard id and number of shards', 'save_embeddings_and_ids': 'save encoded passage embeddings and corresponding document IDs to separate PyTorch files', 'setup_args_Generator': 'setup command line arguments for passages file, output file, num shards, shard id, and DPR model flag'}
```

## File: facebookresearch_parlai/parlai/agents/rag/scripts/index_dense_embeddings.py

Prompts

```
['run the Generator script to generate dense embeddings from a passages TSV file for a FAISS index', 'encode passages using a TorchRankerAgent candidate encoder and return passage embeddings as a tensor', 'load passages from a TSV file and shard them by shard id and number of shards', 'save encoded passage embeddings and corresponding document IDs to separate PyTorch files', 'setup command line arguments for passages file, output file, num shards, shard id, and DPR model flag', 'run the Indexer script to create a FAISS index from dense embedding files in a directory', 'index PyTorch embedding files into a FAISS index using the Indexer class index_data method', 'train and add embeddings to a compressed FAISS indexer using the train_then_add method', 'setup command-line arguments for the Indexer including embeddings-dir, num-shards, and shard-id options', 'serialize and save a FAISS index to disk after indexing dense embeddings']
```

Usage

```
{'run_index_dense_embeddings': 'run the Indexer script to create a FAISS index from dense embedding files in a directory', 'index_data_with_faiss': 'index PyTorch embedding files into a FAISS index using the Indexer class index_data method', 'train_compressed_indexer': 'train and add embeddings to a compressed FAISS indexer using the train_then_add method', 'setup_indexer_args': 'setup command-line arguments for the Indexer including embeddings-dir, num-shards, and shard-id options', 'serialize_faiss_index': 'serialize and save a FAISS index to disk after indexing dense embeddings'}
```


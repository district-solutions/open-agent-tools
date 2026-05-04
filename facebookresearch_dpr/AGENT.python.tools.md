# Agent Python Tools

- repo: facebookresearch/dpr
- repo_uri: https://github.com/facebookresearch/dpr

## File: facebookresearch_dpr/dense_retriever.py

Prompts

```
['generate dense embedding vectors for a list of questions using a biencoder question encoder and tensorizer', 'create a DenseRetriever instance with a question encoder, batch size, and tensorizer to encode questions into vectors', 'build a LocalFaissRetriever that indexes encoded passage vectors and retrieves top matching passages via FAISS KNN search', 'build a DenseRPCRetriever that connects to a remote FAISS index server for distributed dense retrieval and search', 'validate retrieved passage results against ground truth answers and calculate top-k hit accuracy statistics', 'run the DPR tool to generate dense embeddings for a large document base using a pretrained encoder', 'run gen_ctx_vectors to batch encode context passages into dense vector embeddings using a biencoder model', 'run the main entry point to load a checkpoint, shard passages, and save embeddings as pickle files', 'refactor gen_ctx_vectors to remove the conditional if branch when handling extra info in results', 'review the main function to understand how sharded passage encoding and pickle serialization work', 'run the DPR BiEncoder training pipeline using Hydra config to train a dense retrieval model', 'validate a trained BiEncoder model using negative log likelihood loss on a dev dataset', 'validate a BiEncoder model by computing the average rank of gold passages across negative pools', 'save a BiEncoder training checkpoint including model state, optimizer, and scheduler to disk', 'calculate the in-batch negatives schema loss with DDP support by gathering representations across nodes', 'run the extractive reader model training pipeline on retriever results with a Hydra config', 'validate the trained reader model on dev files and compute exact match scores', 'save reader model prediction results to a JSON file with span predictions and scores', 'get the best answer span predictions from start and end logits for reader samples', 'calculate the training loss for the reader model given a batch of input data']
```

Usage

```
{'generate_question_vectors': 'generate dense embedding vectors for a list of questions using a biencoder question encoder and tensorizer', 'create_DenseRetriever': 'create a DenseRetriever instance with a question encoder, batch size, and tensorizer to encode questions into vectors', 'build_LocalFaissRetriever': 'build a LocalFaissRetriever that indexes encoded passage vectors and retrieves top matching passages via FAISS KNN search', 'build_DenseRPCRetriever': 'build a DenseRPCRetriever that connects to a remote FAISS index server for distributed dense retrieval and search', 'validate_retrieval_results': 'validate retrieved passage results against ground truth answers and calculate top-k hit accuracy statistics'}
```

## File: facebookresearch_dpr/generate_dense_embeddings.py

Prompts

```
['generate dense embedding vectors for a list of questions using a biencoder question encoder and tensorizer', 'create a DenseRetriever instance with a question encoder, batch size, and tensorizer to encode questions into vectors', 'build a LocalFaissRetriever that indexes encoded passage vectors and retrieves top matching passages via FAISS KNN search', 'build a DenseRPCRetriever that connects to a remote FAISS index server for distributed dense retrieval and search', 'validate retrieved passage results against ground truth answers and calculate top-k hit accuracy statistics', 'run the DPR tool to generate dense embeddings for a large document base using a pretrained encoder', 'run gen_ctx_vectors to batch encode context passages into dense vector embeddings using a biencoder model', 'run the main entry point to load a checkpoint, shard passages, and save embeddings as pickle files', 'refactor gen_ctx_vectors to remove the conditional if branch when handling extra info in results', 'review the main function to understand how sharded passage encoding and pickle serialization work', 'run the DPR BiEncoder training pipeline using Hydra config to train a dense retrieval model', 'validate a trained BiEncoder model using negative log likelihood loss on a dev dataset', 'validate a BiEncoder model by computing the average rank of gold passages across negative pools', 'save a BiEncoder training checkpoint including model state, optimizer, and scheduler to disk', 'calculate the in-batch negatives schema loss with DDP support by gathering representations across nodes', 'run the extractive reader model training pipeline on retriever results with a Hydra config', 'validate the trained reader model on dev files and compute exact match scores', 'save reader model prediction results to a JSON file with span predictions and scores', 'get the best answer span predictions from start and end logits for reader samples', 'calculate the training loss for the reader model given a batch of input data']
```

Usage

```
{'run_dense_embeddings': 'run the DPR tool to generate dense embeddings for a large document base using a pretrained encoder', 'run_gen_ctx_vectors': 'run gen_ctx_vectors to batch encode context passages into dense vector embeddings using a biencoder model', 'run_main_entry': 'run the main entry point to load a checkpoint, shard passages, and save embeddings as pickle files', 'refactor_gen_ctx_vectors': 'refactor gen_ctx_vectors to remove the conditional if branch when handling extra info in results', 'review_main': 'review the main function to understand how sharded passage encoding and pickle serialization work'}
```

## File: facebookresearch_dpr/train_dense_encoder.py

Prompts

```
['generate dense embedding vectors for a list of questions using a biencoder question encoder and tensorizer', 'create a DenseRetriever instance with a question encoder, batch size, and tensorizer to encode questions into vectors', 'build a LocalFaissRetriever that indexes encoded passage vectors and retrieves top matching passages via FAISS KNN search', 'build a DenseRPCRetriever that connects to a remote FAISS index server for distributed dense retrieval and search', 'validate retrieved passage results against ground truth answers and calculate top-k hit accuracy statistics', 'run the DPR tool to generate dense embeddings for a large document base using a pretrained encoder', 'run gen_ctx_vectors to batch encode context passages into dense vector embeddings using a biencoder model', 'run the main entry point to load a checkpoint, shard passages, and save embeddings as pickle files', 'refactor gen_ctx_vectors to remove the conditional if branch when handling extra info in results', 'review the main function to understand how sharded passage encoding and pickle serialization work', 'run the DPR BiEncoder training pipeline using Hydra config to train a dense retrieval model', 'validate a trained BiEncoder model using negative log likelihood loss on a dev dataset', 'validate a BiEncoder model by computing the average rank of gold passages across negative pools', 'save a BiEncoder training checkpoint including model state, optimizer, and scheduler to disk', 'calculate the in-batch negatives schema loss with DDP support by gathering representations across nodes', 'run the extractive reader model training pipeline on retriever results with a Hydra config', 'validate the trained reader model on dev files and compute exact match scores', 'save reader model prediction results to a JSON file with span predictions and scores', 'get the best answer span predictions from start and end logits for reader samples', 'calculate the training loss for the reader model given a batch of input data']
```

Usage

```
{'run_biencoder_training': 'run the DPR BiEncoder training pipeline using Hydra config to train a dense retrieval model', 'validate_nll_loss': 'validate a trained BiEncoder model using negative log likelihood loss on a dev dataset', 'validate_average_rank': 'validate a BiEncoder model by computing the average rank of gold passages across negative pools', 'save_checkpoint': 'save a BiEncoder training checkpoint including model state, optimizer, and scheduler to disk', 'calc_inbatch_negatives_loss': 'calculate the in-batch negatives schema loss with DDP support by gathering representations across nodes'}
```

## File: facebookresearch_dpr/train_extractive_reader.py

Prompts

```
['generate dense embedding vectors for a list of questions using a biencoder question encoder and tensorizer', 'create a DenseRetriever instance with a question encoder, batch size, and tensorizer to encode questions into vectors', 'build a LocalFaissRetriever that indexes encoded passage vectors and retrieves top matching passages via FAISS KNN search', 'build a DenseRPCRetriever that connects to a remote FAISS index server for distributed dense retrieval and search', 'validate retrieved passage results against ground truth answers and calculate top-k hit accuracy statistics', 'run the DPR tool to generate dense embeddings for a large document base using a pretrained encoder', 'run gen_ctx_vectors to batch encode context passages into dense vector embeddings using a biencoder model', 'run the main entry point to load a checkpoint, shard passages, and save embeddings as pickle files', 'refactor gen_ctx_vectors to remove the conditional if branch when handling extra info in results', 'review the main function to understand how sharded passage encoding and pickle serialization work', 'run the DPR BiEncoder training pipeline using Hydra config to train a dense retrieval model', 'validate a trained BiEncoder model using negative log likelihood loss on a dev dataset', 'validate a BiEncoder model by computing the average rank of gold passages across negative pools', 'save a BiEncoder training checkpoint including model state, optimizer, and scheduler to disk', 'calculate the in-batch negatives schema loss with DDP support by gathering representations across nodes', 'run the extractive reader model training pipeline on retriever results with a Hydra config', 'validate the trained reader model on dev files and compute exact match scores', 'save reader model prediction results to a JSON file with span predictions and scores', 'get the best answer span predictions from start and end logits for reader samples', 'calculate the training loss for the reader model given a batch of input data']
```

Usage

```
{'run_reader_training': 'run the extractive reader model training pipeline on retriever results with a Hydra config', 'validate_reader_model': 'validate the trained reader model on dev files and compute exact match scores', 'save_reader_predictions': 'save reader model prediction results to a JSON file with span predictions and scores', 'get_best_prediction': 'get the best answer span predictions from start and end logits for reader samples', 'calc_reader_loss': 'calculate the training loss for the reader model given a batch of input data'}
```


# Agent Python Tools

- repo: facebookresearch/neuraldb
- repo_uri: https://github.com/facebookresearch/neuraldb

## File: facebookresearch_neuraldb/modelling/src/neuraldb/retriever/dpr.py

Prompts

```
['run the DPR retriever CLI to process an input JSONL file and write predicted facts to an output file', 'create a DPRRetriever instance that loads pretrained DPR question and context encoder models onto CUDA', 'run the lookup method to compute similarity scores between queries and facts using DPR encoders', 'review the DPRRetriever class and its use of Facebook DPR pretrained models for dense passage retrieval', 'refactor the lookup method to support batched retrieval or alternative device placement beyond CUDA', 'run the TFIDFRetriever CLI to predict facts for queries from an input JSONL file', 'create a TFIDFRetriever instance with default RankArgs including ngram 2 and max_sent 50', 'lookup the closest fact document IDs for each query using TF-IDF ranking', 'review the RankArgs class to configure ngram, hash_size, tokenizer, and max_sent parameters', 'summarize the TF-IDF retrieval pipeline that ranks facts against SQL queries using OnlineTfidfDocRanker']
```

Usage

```
{'run_dpr_retriever_cli': 'run the DPR retriever CLI to process an input JSONL file and write predicted facts to an output file', 'create_DPRRetriever_instance': 'create a DPRRetriever instance that loads pretrained DPR question and context encoder models onto CUDA', 'run_DPRRetriever_lookup': 'run the lookup method to compute similarity scores between queries and facts using DPR encoders', 'review_DPRRetriever_class': 'review the DPRRetriever class and its use of Facebook DPR pretrained models for dense passage retrieval', 'refactor_DPRRetriever_lookup': 'refactor the lookup method to support batched retrieval or alternative device placement beyond CUDA'}
```

## File: facebookresearch_neuraldb/modelling/src/neuraldb/retriever/tfidf.py

Prompts

```
['run the DPR retriever CLI to process an input JSONL file and write predicted facts to an output file', 'create a DPRRetriever instance that loads pretrained DPR question and context encoder models onto CUDA', 'run the lookup method to compute similarity scores between queries and facts using DPR encoders', 'review the DPRRetriever class and its use of Facebook DPR pretrained models for dense passage retrieval', 'refactor the lookup method to support batched retrieval or alternative device placement beyond CUDA', 'run the TFIDFRetriever CLI to predict facts for queries from an input JSONL file', 'create a TFIDFRetriever instance with default RankArgs including ngram 2 and max_sent 50', 'lookup the closest fact document IDs for each query using TF-IDF ranking', 'review the RankArgs class to configure ngram, hash_size, tokenizer, and max_sent parameters', 'summarize the TF-IDF retrieval pipeline that ranks facts against SQL queries using OnlineTfidfDocRanker']
```

Usage

```
{'run_tfidf_retriever_cli': 'run the TFIDFRetriever CLI to predict facts for queries from an input JSONL file', 'create_tfidf_retriever_instance': 'create a TFIDFRetriever instance with default RankArgs including ngram 2 and max_sent 50', 'lookup_closest_facts': 'lookup the closest fact document IDs for each query using TF-IDF ranking', 'review_rankargs_config': 'review the RankArgs class to configure ngram, hash_size, tokenizer, and max_sent parameters', 'summarize_tfidf_pipeline': 'summarize the TF-IDF retrieval pipeline that ranks facts against SQL queries using OnlineTfidfDocRanker'}
```


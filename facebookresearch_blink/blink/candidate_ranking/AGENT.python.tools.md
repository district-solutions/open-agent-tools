# Agent Python Tools

- repo: facebookresearch/blink
- repo_uri: https://github.com/facebookresearch/blink

## File: facebookresearch_blink/blink/candidate_ranking/bert_reranking.py

Prompts

```
['build a BERT-based reranking model with a classifier head for multiple choice classification', 'run the BERT reranker to score and rank entity candidates for a list of mentions', 'create an AdamW optimizer and warmup linear scheduler for fine-tuning the BERT reranking model', 'process mentions and candidates into tokenized tensors ready for the BERT reranking model', 'get a tokenized BERT input representation combining context tokens with a candidate entity description', 'run the blink candidate reranking model evaluation on benchmark datasets via command line', 'evaluate a BERT reranking model on a dataset and compute normalized accuracy and BM25 recall metrics', 'run full evaluation across all benchmark datasets including AIDA, MSNBC, ACE2004, and Wikipedia', 'run evaluation on the AIDA-B dataset only using a pre-trained reranking model', 'evaluate model accuracy and BM25 recall at multiple k values on a dataloader', 'read a JSONL dataset file from a given folder path and return parsed samples', 'filter dataset samples to only include those with gold_pos rank within a top_k threshold', "evaluate precision at multiple k values from a PyTorch dataloader's label IDs", 'save a PyTorch model state dict, config, and tokenizer vocabulary to an output directory', 'instantiate a BertReranker or BiEncoderRanker from a parameters dictionary']
```

Usage

```
{'build_BertForReranking_model': 'build a BERT-based reranking model with a classifier head for multiple choice classification', 'run_BertReranker_rerank': 'run the BERT reranker to score and rank entity candidates for a list of mentions', 'create_BertReranker_optimizer': 'create an AdamW optimizer and warmup linear scheduler for fine-tuning the BERT reranking model', 'process_mentions_BertReranker': 'process mentions and candidates into tokenized tensors ready for the BERT reranking model', 'get_candidate_representation_BertReranker': 'get a tokenized BERT input representation combining context tokens with a candidate entity description'}
```

## File: facebookresearch_blink/blink/candidate_ranking/evaluate.py

Prompts

```
['build a BERT-based reranking model with a classifier head for multiple choice classification', 'run the BERT reranker to score and rank entity candidates for a list of mentions', 'create an AdamW optimizer and warmup linear scheduler for fine-tuning the BERT reranking model', 'process mentions and candidates into tokenized tensors ready for the BERT reranking model', 'get a tokenized BERT input representation combining context tokens with a candidate entity description', 'run the blink candidate reranking model evaluation on benchmark datasets via command line', 'evaluate a BERT reranking model on a dataset and compute normalized accuracy and BM25 recall metrics', 'run full evaluation across all benchmark datasets including AIDA, MSNBC, ACE2004, and Wikipedia', 'run evaluation on the AIDA-B dataset only using a pre-trained reranking model', 'evaluate model accuracy and BM25 recall at multiple k values on a dataloader', 'read a JSONL dataset file from a given folder path and return parsed samples', 'filter dataset samples to only include those with gold_pos rank within a top_k threshold', "evaluate precision at multiple k values from a PyTorch dataloader's label IDs", 'save a PyTorch model state dict, config, and tokenizer vocabulary to an output directory', 'instantiate a BertReranker or BiEncoderRanker from a parameters dictionary']
```

Usage

```
{'run_evaluation_cli': 'run the blink candidate reranking model evaluation on benchmark datasets via command line', 'evaluate_model_on_dataset': 'evaluate a BERT reranking model on a dataset and compute normalized accuracy and BM25 recall metrics', 'evaluate_full_datasets': 'run full evaluation across all benchmark datasets including AIDA, MSNBC, ACE2004, and Wikipedia', 'evaluate_aida_only': 'run evaluation on the AIDA-B dataset only using a pre-trained reranking model', 'evaluate_with_bm25_recall': 'evaluate model accuracy and BM25 recall at multiple k values on a dataloader'}
```

## File: facebookresearch_blink/blink/candidate_ranking/utils.py

Prompts

```
['build a BERT-based reranking model with a classifier head for multiple choice classification', 'run the BERT reranker to score and rank entity candidates for a list of mentions', 'create an AdamW optimizer and warmup linear scheduler for fine-tuning the BERT reranking model', 'process mentions and candidates into tokenized tensors ready for the BERT reranking model', 'get a tokenized BERT input representation combining context tokens with a candidate entity description', 'run the blink candidate reranking model evaluation on benchmark datasets via command line', 'evaluate a BERT reranking model on a dataset and compute normalized accuracy and BM25 recall metrics', 'run full evaluation across all benchmark datasets including AIDA, MSNBC, ACE2004, and Wikipedia', 'run evaluation on the AIDA-B dataset only using a pre-trained reranking model', 'evaluate model accuracy and BM25 recall at multiple k values on a dataloader', 'read a JSONL dataset file from a given folder path and return parsed samples', 'filter dataset samples to only include those with gold_pos rank within a top_k threshold', "evaluate precision at multiple k values from a PyTorch dataloader's label IDs", 'save a PyTorch model state dict, config, and tokenizer vocabulary to an output directory', 'instantiate a BertReranker or BiEncoderRanker from a parameters dictionary']
```

Usage

```
{'read_dataset_JSONL': 'read a JSONL dataset file from a given folder path and return parsed samples', 'filter_samples_top_k': 'filter dataset samples to only include those with gold_pos rank within a top_k threshold', 'eval_precision_bm45_dataloader': "evaluate precision at multiple k values from a PyTorch dataloader's label IDs", 'save_model_and_tokenizer': 'save a PyTorch model state dict, config, and tokenizer vocabulary to an output directory', 'get_reranker_or_biencoder': 'instantiate a BertReranker or BiEncoderRanker from a parameters dictionary'}
```


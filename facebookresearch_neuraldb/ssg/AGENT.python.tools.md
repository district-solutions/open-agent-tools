# Agent Python Tools

- repo: facebookresearch/neuraldb
- repo_uri: https://github.com/facebookresearch/neuraldb

## File: facebookresearch_neuraldb/ssg/evaluate_set_ssg.py

Prompts

```
['run the SSG predictions evaluation script with a JSON predictions file using the -i flag', 'run find_matches to check exact and soft subset matches between a set and a list of sets', 'run evaluate_ndb_with_ssg to compute precision and recall metrics from a JSON data file', 'review the find_matches function that returns exact and soft match scores for set comparisons', 'review the evaluate_ndb_with_ssg function that calculates per-query-type precision and recall metrics', 'run SSG predictions on dev and test datasets using a SentenceTransformer model with configurable cosine similarity thresholds', 'run the is_valid_folder validator to check if an input folder path exists before processing', 'run SentenceTransformer encode to convert context and query text into vector embeddings for similarity search', 'run pytorch_cos_sim to compute cosine similarity between state representations and action embeddings for fact retrieval', 'run read_NDB to load NeuralDB dataset from a JSONL file containing database questions and context', 'read a JSONL NeuralDB data file and return a list of facts and queries per database', 'create a training dataset from NeuralDB databases with positive and negative action labels', 'prepare a HuggingFace tokenizer by adding special tokens like sep and eos', 'review the read_NDB function that parses JSONL files into facts and queries lists', 'summarize the create_dataset function that generates labeled state-action pairs for training', 'run the SSG training script with an input data folder and output path using argparse', 'run a distilbert-based sentence transformer model for semantic sentence generation training', 'run contrastive loss training on sentence pairs with positive and negative labels', 'run weighted random sampling to oversample positive examples during training', 'run binary classification evaluation on dev examples during model training']
```

Usage

```
{'run_evaluate_ssg_predictions': 'run the SSG predictions evaluation script with a JSON predictions file using the -i flag', 'run_find_matches': 'run find_matches to check exact and soft subset matches between a set and a list of sets', 'run_evaluate_ndb_with_ssg': 'run evaluate_ndb_with_ssg to compute precision and recall metrics from a JSON data file', 'review_find_matches': 'review the find_matches function that returns exact and soft match scores for set comparisons', 'review_evaluate_ndb_with_ssg': 'review the evaluate_ndb_with_ssg function that calculates per-query-type precision and recall metrics'}
```

## File: facebookresearch_neuraldb/ssg/ssg_prediction.py

Prompts

```
['run the SSG predictions evaluation script with a JSON predictions file using the -i flag', 'run find_matches to check exact and soft subset matches between a set and a list of sets', 'run evaluate_ndb_with_ssg to compute precision and recall metrics from a JSON data file', 'review the find_matches function that returns exact and soft match scores for set comparisons', 'review the evaluate_ndb_with_ssg function that calculates per-query-type precision and recall metrics', 'run SSG predictions on dev and test datasets using a SentenceTransformer model with configurable cosine similarity thresholds', 'run the is_valid_folder validator to check if an input folder path exists before processing', 'run SentenceTransformer encode to convert context and query text into vector embeddings for similarity search', 'run pytorch_cos_sim to compute cosine similarity between state representations and action embeddings for fact retrieval', 'run read_NDB to load NeuralDB dataset from a JSONL file containing database questions and context', 'read a JSONL NeuralDB data file and return a list of facts and queries per database', 'create a training dataset from NeuralDB databases with positive and negative action labels', 'prepare a HuggingFace tokenizer by adding special tokens like sep and eos', 'review the read_NDB function that parses JSONL files into facts and queries lists', 'summarize the create_dataset function that generates labeled state-action pairs for training', 'run the SSG training script with an input data folder and output path using argparse', 'run a distilbert-based sentence transformer model for semantic sentence generation training', 'run contrastive loss training on sentence pairs with positive and negative labels', 'run weighted random sampling to oversample positive examples during training', 'run binary classification evaluation on dev examples during model training']
```

Usage

```
{'run_ssg_predictions': 'run SSG predictions on dev and test datasets using a SentenceTransformer model with configurable cosine similarity thresholds', 'run_is_valid_folder': 'run the is_valid_folder validator to check if an input folder path exists before processing', 'run_sentence_transformer_encode': 'run SentenceTransformer encode to convert context and query text into vector embeddings for similarity search', 'run_pytorch_cos_sim': 'run pytorch_cos_sim to compute cosine similarity between state representations and action embeddings for fact retrieval', 'run_read_NDB': 'run read_NDB to load NeuralDB dataset from a JSONL file containing database questions and context'}
```

## File: facebookresearch_neuraldb/ssg/ssg_utils.py

Prompts

```
['run the SSG predictions evaluation script with a JSON predictions file using the -i flag', 'run find_matches to check exact and soft subset matches between a set and a list of sets', 'run evaluate_ndb_with_ssg to compute precision and recall metrics from a JSON data file', 'review the find_matches function that returns exact and soft match scores for set comparisons', 'review the evaluate_ndb_with_ssg function that calculates per-query-type precision and recall metrics', 'run SSG predictions on dev and test datasets using a SentenceTransformer model with configurable cosine similarity thresholds', 'run the is_valid_folder validator to check if an input folder path exists before processing', 'run SentenceTransformer encode to convert context and query text into vector embeddings for similarity search', 'run pytorch_cos_sim to compute cosine similarity between state representations and action embeddings for fact retrieval', 'run read_NDB to load NeuralDB dataset from a JSONL file containing database questions and context', 'read a JSONL NeuralDB data file and return a list of facts and queries per database', 'create a training dataset from NeuralDB databases with positive and negative action labels', 'prepare a HuggingFace tokenizer by adding special tokens like sep and eos', 'review the read_NDB function that parses JSONL files into facts and queries lists', 'summarize the create_dataset function that generates labeled state-action pairs for training', 'run the SSG training script with an input data folder and output path using argparse', 'run a distilbert-based sentence transformer model for semantic sentence generation training', 'run contrastive loss training on sentence pairs with positive and negative labels', 'run weighted random sampling to oversample positive examples during training', 'run binary classification evaluation on dev examples during model training']
```

Usage

```
{'read_NDB': 'read a JSONL NeuralDB data file and return a list of facts and queries per database', 'create_dataset': 'create a training dataset from NeuralDB databases with positive and negative action labels', 'prepare_tokenizer': 'prepare a HuggingFace tokenizer by adding special tokens like sep and eos', 'review_read_NDB': 'review the read_NDB function that parses JSONL files into facts and queries lists', 'summarize_create_dataset': 'summarize the create_dataset function that generates labeled state-action pairs for training'}
```

## File: facebookresearch_neuraldb/ssg/train_ssg.py

Prompts

```
['run the SSG predictions evaluation script with a JSON predictions file using the -i flag', 'run find_matches to check exact and soft subset matches between a set and a list of sets', 'run evaluate_ndb_with_ssg to compute precision and recall metrics from a JSON data file', 'review the find_matches function that returns exact and soft match scores for set comparisons', 'review the evaluate_ndb_with_ssg function that calculates per-query-type precision and recall metrics', 'run SSG predictions on dev and test datasets using a SentenceTransformer model with configurable cosine similarity thresholds', 'run the is_valid_folder validator to check if an input folder path exists before processing', 'run SentenceTransformer encode to convert context and query text into vector embeddings for similarity search', 'run pytorch_cos_sim to compute cosine similarity between state representations and action embeddings for fact retrieval', 'run read_NDB to load NeuralDB dataset from a JSONL file containing database questions and context', 'read a JSONL NeuralDB data file and return a list of facts and queries per database', 'create a training dataset from NeuralDB databases with positive and negative action labels', 'prepare a HuggingFace tokenizer by adding special tokens like sep and eos', 'review the read_NDB function that parses JSONL files into facts and queries lists', 'summarize the create_dataset function that generates labeled state-action pairs for training', 'run the SSG training script with an input data folder and output path using argparse', 'run a distilbert-based sentence transformer model for semantic sentence generation training', 'run contrastive loss training on sentence pairs with positive and negative labels', 'run weighted random sampling to oversample positive examples during training', 'run binary classification evaluation on dev examples during model training']
```

Usage

```
{'run_train_ssg': 'run the SSG training script with an input data folder and output path using argparse', 'run_SentenceTransformer': 'run a distilbert-based sentence transformer model for semantic sentence generation training', 'run_ContrastiveLoss': 'run contrastive loss training on sentence pairs with positive and negative labels', 'run_WeightedRandomSampler': 'run weighted random sampling to oversample positive examples during training', 'run_BinaryClassificationEvaluator': 'run binary classification evaluation on dev examples during model training'}
```


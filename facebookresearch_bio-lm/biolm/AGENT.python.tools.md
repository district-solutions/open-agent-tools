# Agent Python Tools

- repo: facebookresearch/bio-lm
- repo_uri: https://github.com/facebookresearch/bio-lm

## File: facebookresearch_bio-lm/biolm/run_classification.py

Prompts

```
['run a HuggingFace transformer model finetuning pipeline for sequence classification on a biological NLP task', 'train a sequence classification model with AdamW optimizer, gradient accumulation, and linear warmup scheduling', 'evaluate a fine-tuned model on dev or test sets and compute task-specific metrics like accuracy or F1', 'load and cache tokenized dataset examples from TSV files into PyTorch tensors with feature conversion', 'set random seeds for Python, NumPy, and PyTorch to ensure reproducible training results', 'run sequence labelling training on NER data using a pretrained transformer model with argparse CLI', 'evaluate a trained token classification model on dev data and compute precision recall and f1 scores', 'run predictions on test data with a trained sequence labelling model and save output predictions', 'train a token classification model using AdamW optimizer with gradient accumulation and fp16 support', 'convert a list of InputExamples into tokenized InputFeatures for a HuggingFace classification task using a tokenizer', 'create a data processor like HOCProcessor or MedNLIProcessor to load and parse biomedical classification datasets from TSV or JSONL files', 'compute task-specific evaluation metrics like accuracy, F1, precision, and recall for biomedical NLP classification predictions', 'compute per-document precision, recall, and F-score for the HOC multilabel cancer hallmark classification task', 'compute accuracy, micro F1, macro F1, and weighted precision and recall for multiclass classification predictions', 'read NER training examples from a CoNLL-2003 format text file into InputExample objects', 'load NER label list from a file path or return default CoNLL-2003 labels', 'create an InputExample object with a unique guid, list of words, and optional labels for token classification', 'create an InputFeatures object with input IDs, input mask, segment IDs, and label IDs for model input']
```

Usage

```
{'run_classification_finetuning': 'run a HuggingFace transformer model finetuning pipeline for sequence classification on a biological NLP task', 'train_model': 'train a sequence classification model with AdamW optimizer, gradient accumulation, and linear warmup scheduling', 'evaluate_model': 'evaluate a fine-tuned model on dev or test sets and compute task-specific metrics like accuracy or F1', 'load_and_cache_examples': 'load and cache tokenized dataset examples from TSV files into PyTorch tensors with feature conversion', 'set_seed': 'set random seeds for Python, NumPy, and PyTorch to ensure reproducible training results'}
```

## File: facebookresearch_bio-lm/biolm/run_sequence_labelling.py

Prompts

```
['run a HuggingFace transformer model finetuning pipeline for sequence classification on a biological NLP task', 'train a sequence classification model with AdamW optimizer, gradient accumulation, and linear warmup scheduling', 'evaluate a fine-tuned model on dev or test sets and compute task-specific metrics like accuracy or F1', 'load and cache tokenized dataset examples from TSV files into PyTorch tensors with feature conversion', 'set random seeds for Python, NumPy, and PyTorch to ensure reproducible training results', 'run sequence labelling training on NER data using a pretrained transformer model with argparse CLI', 'evaluate a trained token classification model on dev data and compute precision recall and f1 scores', 'run predictions on test data with a trained sequence labelling model and save output predictions', 'train a token classification model using AdamW optimizer with gradient accumulation and fp16 support', 'convert a list of InputExamples into tokenized InputFeatures for a HuggingFace classification task using a tokenizer', 'create a data processor like HOCProcessor or MedNLIProcessor to load and parse biomedical classification datasets from TSV or JSONL files', 'compute task-specific evaluation metrics like accuracy, F1, precision, and recall for biomedical NLP classification predictions', 'compute per-document precision, recall, and F-score for the HOC multilabel cancer hallmark classification task', 'compute accuracy, micro F1, macro F1, and weighted precision and recall for multiclass classification predictions', 'read NER training examples from a CoNLL-2003 format text file into InputExample objects', 'load NER label list from a file path or return default CoNLL-2003 labels', 'create an InputExample object with a unique guid, list of words, and optional labels for token classification', 'create an InputFeatures object with input IDs, input mask, segment IDs, and label IDs for model input']
```

Usage

```
{'run_sequence_labelling_training': 'run sequence labelling training on NER data using a pretrained transformer model with argparse CLI', 'run_sequence_labelling_evaluation': 'evaluate a trained token classification model on dev data and compute precision recall and f1 scores', 'run_sequence_labelling_prediction': 'run predictions on test data with a trained sequence labelling model and save output predictions', 'train_token_classification_model': 'train a token classification model using AdamW optimizer with gradient accumulation and fp16 support', 'load_and_cache_examples': 'load and cache token classification examples from CoNLL format files into a PyTorch TensorDataset'}
```

## File: facebookresearch_bio-lm/biolm/utils_classification.py

Prompts

```
['run a HuggingFace transformer model finetuning pipeline for sequence classification on a biological NLP task', 'train a sequence classification model with AdamW optimizer, gradient accumulation, and linear warmup scheduling', 'evaluate a fine-tuned model on dev or test sets and compute task-specific metrics like accuracy or F1', 'load and cache tokenized dataset examples from TSV files into PyTorch tensors with feature conversion', 'set random seeds for Python, NumPy, and PyTorch to ensure reproducible training results', 'run sequence labelling training on NER data using a pretrained transformer model with argparse CLI', 'evaluate a trained token classification model on dev data and compute precision recall and f1 scores', 'run predictions on test data with a trained sequence labelling model and save output predictions', 'train a token classification model using AdamW optimizer with gradient accumulation and fp16 support', 'convert a list of InputExamples into tokenized InputFeatures for a HuggingFace classification task using a tokenizer', 'create a data processor like HOCProcessor or MedNLIProcessor to load and parse biomedical classification datasets from TSV or JSONL files', 'compute task-specific evaluation metrics like accuracy, F1, precision, and recall for biomedical NLP classification predictions', 'compute per-document precision, recall, and F-score for the HOC multilabel cancer hallmark classification task', 'compute accuracy, micro F1, macro F1, and weighted precision and recall for multiclass classification predictions', 'read NER training examples from a CoNLL-2003 format text file into InputExample objects', 'load NER label list from a file path or return default CoNLL-2003 labels', 'create an InputExample object with a unique guid, list of words, and optional labels for token classification', 'create an InputFeatures object with input IDs, input mask, segment IDs, and label IDs for model input']
```

Usage

```
{'convert_examples_to_features': 'convert a list of InputExamples into tokenized InputFeatures for a HuggingFace classification task using a tokenizer', 'create_data_processor': 'create a data processor like HOCProcessor or MedNLIProcessor to load and parse biomedical classification datasets from TSV or JSONL files', 'compute_metrics': 'compute task-specific evaluation metrics like accuracy, F1, precision, and recall for biomedical NLP classification predictions', 'hoc_get_p_r_f_arrary': 'compute per-document precision, recall, and F-score for the HOC multilabel cancer hallmark classification task', 'multiclass_acc_and_f1': 'compute accuracy, micro F1, macro F1, and weighted precision and recall for multiclass classification predictions'}
```

## File: facebookresearch_bio-lm/biolm/utils_sequence_labelling.py

Prompts

```
['run a HuggingFace transformer model finetuning pipeline for sequence classification on a biological NLP task', 'train a sequence classification model with AdamW optimizer, gradient accumulation, and linear warmup scheduling', 'evaluate a fine-tuned model on dev or test sets and compute task-specific metrics like accuracy or F1', 'load and cache tokenized dataset examples from TSV files into PyTorch tensors with feature conversion', 'set random seeds for Python, NumPy, and PyTorch to ensure reproducible training results', 'run sequence labelling training on NER data using a pretrained transformer model with argparse CLI', 'evaluate a trained token classification model on dev data and compute precision recall and f1 scores', 'run predictions on test data with a trained sequence labelling model and save output predictions', 'train a token classification model using AdamW optimizer with gradient accumulation and fp16 support', 'convert a list of InputExamples into tokenized InputFeatures for a HuggingFace classification task using a tokenizer', 'create a data processor like HOCProcessor or MedNLIProcessor to load and parse biomedical classification datasets from TSV or JSONL files', 'compute task-specific evaluation metrics like accuracy, F1, precision, and recall for biomedical NLP classification predictions', 'compute per-document precision, recall, and F-score for the HOC multilabel cancer hallmark classification task', 'compute accuracy, micro F1, macro F1, and weighted precision and recall for multiclass classification predictions', 'read NER training examples from a CoNLL-2003 format text file into InputExample objects', 'load NER label list from a file path or return default CoNLL-2003 labels', 'create an InputExample object with a unique guid, list of words, and optional labels for token classification', 'create an InputFeatures object with input IDs, input mask, segment IDs, and label IDs for model input']
```

Usage

```
{'read_examples_from_file': 'read NER training examples from a CoNLL-2003 format text file into InputExample objects', 'convert_examples_to_features': 'convert InputExample objects into tokenized InputFeatures with BERT-style input IDs, masks, and segment IDs', 'get_labels': 'load NER label list from a file path or return default CoNLL-2003 labels', 'create_InputExample': 'create an InputExample object with a unique guid, list of words, and optional labels for token classification', 'create_InputFeatures': 'create an InputFeatures object with input IDs, input mask, segment IDs, and label IDs for model input'}
```


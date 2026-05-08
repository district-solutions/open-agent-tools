# Agent Python Tools

- repo: facebookresearch/kilt
- repo_uri: https://github.com/facebookresearch/kilt

## File: facebookresearch_kilt/kilt/readers/t5/base_transformer.py

Prompts

```
['create a BaseTransformer LightningModule from a pretrained HuggingFace model name or path', 'run generic training on a BaseTransformer model with PyTorch Lightning and configurable epochs', 'configure an AdamW optimizer with weight decay grouping and linear warmup schedule', 'add model-specific CLI arguments like learning rate and warmup steps to an argparse parser', 'set random seeds for Python, NumPy, and PyTorch including CUDA for reproducibility', 'encode a list of text sequences using a HuggingFace tokenizer with dataset-specific preprocessing and padding', 'create a PyTorch Dataset that loads KILT JSONL data, tokenizes source and target sequences, and yields batches', 'convert a KILT JSONL file into parallel lists of question sources, answer targets, and example IDs', 'convert parallel lists of IDs, sources, and targets back into KILT JSONL format with file locking', 'parse a gzipped Natural Questions JSONL file and extract question-answer pairs with cleaned token spans', 'run the T5 model to generate answers from input questions and save them to an output file', 'calculate ROUGE-1, ROUGE-2, and ROUGE-L scores comparing model output against reference answers', 'run the full KILT task evaluation pipeline with a T5 model on input questions and reference answers', 'create successive n-sized chunks from a list for batch processing', 'review the generate_answers function that batches input texts through a T5 model and decodes predictions', 'run the T5 seq2seq fine-tuning script with argparse to train on KILT datasets', 'create a Seq2seqTransformer model instance with special tokens and dataset-specific batch sizes', 'test the fine-tuned T5 model by loading the latest checkpoint and running predictions', 'build a concatenated DataLoader for training, validation, or test splits across multiple KILT datasets', 'review the validation_step method that generates predictions using beam search and computes exact match']
```

Usage

```
{'create_BaseTransformer': 'create a BaseTransformer LightningModule from a pretrained HuggingFace model name or path', 'run_generic_train': 'run generic training on a BaseTransformer model with PyTorch Lightning and configurable epochs', 'configure_optimizers': 'configure an AdamW optimizer with weight decay grouping and linear warmup schedule', 'add_model_specific_args': 'add model-specific CLI arguments like learning rate and warmup steps to an argparse parser', 'set_seed': 'set random seeds for Python, NumPy, and PyTorch including CUDA for reproducibility'}
```

## File: facebookresearch_kilt/kilt/readers/t5/data.py

Prompts

```
['create a BaseTransformer LightningModule from a pretrained HuggingFace model name or path', 'run generic training on a BaseTransformer model with PyTorch Lightning and configurable epochs', 'configure an AdamW optimizer with weight decay grouping and linear warmup schedule', 'add model-specific CLI arguments like learning rate and warmup steps to an argparse parser', 'set random seeds for Python, NumPy, and PyTorch including CUDA for reproducibility', 'encode a list of text sequences using a HuggingFace tokenizer with dataset-specific preprocessing and padding', 'create a PyTorch Dataset that loads KILT JSONL data, tokenizes source and target sequences, and yields batches', 'convert a KILT JSONL file into parallel lists of question sources, answer targets, and example IDs', 'convert parallel lists of IDs, sources, and targets back into KILT JSONL format with file locking', 'parse a gzipped Natural Questions JSONL file and extract question-answer pairs with cleaned token spans', 'run the T5 model to generate answers from input questions and save them to an output file', 'calculate ROUGE-1, ROUGE-2, and ROUGE-L scores comparing model output against reference answers', 'run the full KILT task evaluation pipeline with a T5 model on input questions and reference answers', 'create successive n-sized chunks from a list for batch processing', 'review the generate_answers function that batches input texts through a T5 model and decodes predictions', 'run the T5 seq2seq fine-tuning script with argparse to train on KILT datasets', 'create a Seq2seqTransformer model instance with special tokens and dataset-specific batch sizes', 'test the fine-tuned T5 model by loading the latest checkpoint and running predictions', 'build a concatenated DataLoader for training, validation, or test splits across multiple KILT datasets', 'review the validation_step method that generates predictions using beam search and computes exact match']
```

Usage

```
{'encode_seq_tokenize_sequences': 'encode a list of text sequences using a HuggingFace tokenizer with dataset-specific preprocessing and padding', 'create_KiltDataset_pytorch_dataset': 'create a PyTorch Dataset that loads KILT JSONL data, tokenizes source and target sequences, and yields batches', 'convert_kilt_to_seq2seq': 'convert a KILT JSONL file into parallel lists of question sources, answer targets, and example IDs', 'convert_seq2seq_to_kilt': 'convert parallel lists of IDs, sources, and targets back into KILT JSONL format with file locking', 'parse_nq_jsonl_to_tsv': 'parse a gzipped Natural Questions JSONL file and extract question-answer pairs with cleaned token spans'}
```

## File: facebookresearch_kilt/kilt/readers/t5/evaluate_kilt_task.py

Prompts

```
['create a BaseTransformer LightningModule from a pretrained HuggingFace model name or path', 'run generic training on a BaseTransformer model with PyTorch Lightning and configurable epochs', 'configure an AdamW optimizer with weight decay grouping and linear warmup schedule', 'add model-specific CLI arguments like learning rate and warmup steps to an argparse parser', 'set random seeds for Python, NumPy, and PyTorch including CUDA for reproducibility', 'encode a list of text sequences using a HuggingFace tokenizer with dataset-specific preprocessing and padding', 'create a PyTorch Dataset that loads KILT JSONL data, tokenizes source and target sequences, and yields batches', 'convert a KILT JSONL file into parallel lists of question sources, answer targets, and example IDs', 'convert parallel lists of IDs, sources, and targets back into KILT JSONL format with file locking', 'parse a gzipped Natural Questions JSONL file and extract question-answer pairs with cleaned token spans', 'run the T5 model to generate answers from input questions and save them to an output file', 'calculate ROUGE-1, ROUGE-2, and ROUGE-L scores comparing model output against reference answers', 'run the full KILT task evaluation pipeline with a T5 model on input questions and reference answers', 'create successive n-sized chunks from a list for batch processing', 'review the generate_answers function that batches input texts through a T5 model and decodes predictions', 'run the T5 seq2seq fine-tuning script with argparse to train on KILT datasets', 'create a Seq2seqTransformer model instance with special tokens and dataset-specific batch sizes', 'test the fine-tuned T5 model by loading the latest checkpoint and running predictions', 'build a concatenated DataLoader for training, validation, or test splits across multiple KILT datasets', 'review the validation_step method that generates predictions using beam search and computes exact match']
```

Usage

```
{'run_generate_answers': 'run the T5 model to generate answers from input questions and save them to an output file', 'calculate_rouge_scores': 'calculate ROUGE-1, ROUGE-2, and ROUGE-L scores comparing model output against reference answers', 'run_kilt_evaluation': 'run the full KILT task evaluation pipeline with a T5 model on input questions and reference answers', 'chunk_list': 'create successive n-sized chunks from a list for batch processing', 'review_generate_answers': 'review the generate_answers function that batches input texts through a T5 model and decodes predictions'}
```

## File: facebookresearch_kilt/kilt/readers/t5/finetune.py

Prompts

```
['create a BaseTransformer LightningModule from a pretrained HuggingFace model name or path', 'run generic training on a BaseTransformer model with PyTorch Lightning and configurable epochs', 'configure an AdamW optimizer with weight decay grouping and linear warmup schedule', 'add model-specific CLI arguments like learning rate and warmup steps to an argparse parser', 'set random seeds for Python, NumPy, and PyTorch including CUDA for reproducibility', 'encode a list of text sequences using a HuggingFace tokenizer with dataset-specific preprocessing and padding', 'create a PyTorch Dataset that loads KILT JSONL data, tokenizes source and target sequences, and yields batches', 'convert a KILT JSONL file into parallel lists of question sources, answer targets, and example IDs', 'convert parallel lists of IDs, sources, and targets back into KILT JSONL format with file locking', 'parse a gzipped Natural Questions JSONL file and extract question-answer pairs with cleaned token spans', 'run the T5 model to generate answers from input questions and save them to an output file', 'calculate ROUGE-1, ROUGE-2, and ROUGE-L scores comparing model output against reference answers', 'run the full KILT task evaluation pipeline with a T5 model on input questions and reference answers', 'create successive n-sized chunks from a list for batch processing', 'review the generate_answers function that batches input texts through a T5 model and decodes predictions', 'run the T5 seq2seq fine-tuning script with argparse to train on KILT datasets', 'create a Seq2seqTransformer model instance with special tokens and dataset-specific batch sizes', 'test the fine-tuned T5 model by loading the latest checkpoint and running predictions', 'build a concatenated DataLoader for training, validation, or test splits across multiple KILT datasets', 'review the validation_step method that generates predictions using beam search and computes exact match']
```

Usage

```
{'run_finetune_t5': 'run the T5 seq2seq fine-tuning script with argparse to train on KILT datasets', 'create_seq2seq_transformer': 'create a Seq2seqTransformer model instance with special tokens and dataset-specific batch sizes', 'test_model_predictions': 'test the fine-tuned T5 model by loading the latest checkpoint and running predictions', 'build_dataloader': 'build a concatenated DataLoader for training, validation, or test splits across multiple KILT datasets', 'review_validation_step': 'review the validation_step method that generates predictions using beam search and computes exact match'}
```


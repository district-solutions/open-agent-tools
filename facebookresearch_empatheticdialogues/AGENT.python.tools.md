# Agent Python Tools

- repo: facebookresearch/empatheticdialogues
- repo_uri: https://github.com/facebookresearch/empatheticdialogues

## File: facebookresearch_empatheticdialogues/retrieval_eval_bleu.py

Prompts

```
['run a CLI tool to evaluate retrieval-based dialogue models using BLEU scores on EmpatheticDialogues, DailyDialog, or Reddit datasets', 'build a candidate response pool from EmpatheticDialogues, DailyDialog, and Reddit datasets with deduplication and length filtering', 'embed candidate response tokens into dense vectors using a pretrained retrieval model in batched chunks', 'predict top-N retrieved responses for a given conversation context using cosine similarity against embedded candidates', 'compute and print BLEU-1 through BLEU-4 scores comparing retrieved responses against ground truth targets on a dataset split', 'run the retrieval model training loop for empathetic dialogues using SGD or Adamax optimizer', 'validate a trained retrieval model on shuffled or unshuffled candidate sets with top-K accuracy', 'compute the in-batch negative log-likelihood loss between context and label embeddings', 'train the retrieval model for one epoch with gradient descent and logging metrics', 'evaluate a pretrained retrieval model on valid and hidden test sets with shuffled candidates']
```

Usage

```
{'run_retrieval_bleu_eval': 'run a CLI tool to evaluate retrieval-based dialogue models using BLEU scores on EmpatheticDialogues, DailyDialog, or Reddit datasets', 'build_candidates_from_datasets': 'build a candidate response pool from EmpatheticDialogues, DailyDialog, and Reddit datasets with deduplication and length filtering', 'embed_candidates_with_model': 'embed candidate response tokens into dense vectors using a pretrained retrieval model in batched chunks', 'predict_top_responses': 'predict top-N retrieved responses for a given conversation context using cosine similarity against embedded candidates', 'get_bleu4_scores': 'compute and print BLEU-1 through BLEU-4 scores comparing retrieved responses against ground truth targets on a dataset split'}
```

## File: facebookresearch_empatheticdialogues/retrieval_train.py

Prompts

```
['run a CLI tool to evaluate retrieval-based dialogue models using BLEU scores on EmpatheticDialogues, DailyDialog, or Reddit datasets', 'build a candidate response pool from EmpatheticDialogues, DailyDialog, and Reddit datasets with deduplication and length filtering', 'embed candidate response tokens into dense vectors using a pretrained retrieval model in batched chunks', 'predict top-N retrieved responses for a given conversation context using cosine similarity against embedded candidates', 'compute and print BLEU-1 through BLEU-4 scores comparing retrieved responses against ground truth targets on a dataset split', 'run the retrieval model training loop for empathetic dialogues using SGD or Adamax optimizer', 'validate a trained retrieval model on shuffled or unshuffled candidate sets with top-K accuracy', 'compute the in-batch negative log-likelihood loss between context and label embeddings', 'train the retrieval model for one epoch with gradient descent and logging metrics', 'evaluate a pretrained retrieval model on valid and hidden test sets with shuffled candidates']
```

Usage

```
{'run_retrieval_model_training': 'run the retrieval model training loop for empathetic dialogues using SGD or Adamax optimizer', 'validate_model_with_candidates': 'validate a trained retrieval model on shuffled or unshuffled candidate sets with top-K accuracy', 'compute_in_batch_loss': 'compute the in-batch negative log-likelihood loss between context and label embeddings', 'train_single_epoch': 'train the retrieval model for one epoch with gradient descent and logging metrics', 'evaluate_pretrained_model': 'evaluate a pretrained retrieval model on valid and hidden test sets with shuffled candidates'}
```


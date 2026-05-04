# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/wikigraphs/updaters.py

Prompts

```
['build a data parallel Updater with multi-GPU support for a Graph2text loss function and optax optimizer', 'create an Updater instance and initialize its state with training data and an RNG key', 'run a training step by calling update on the Updater with batch data to get new state and metrics', 'evaluate the current model state on data without updating parameters and return loss metrics', 'save the Updater state to a pickle checkpoint file using CheckpointingUpdater for later resumption', 'compute the BLEU score of translated text segments against reference corpus with configurable n-gram order', 'extract the title from tokenized wikitext articles by finding the first double newline token', 'construct prompts for text generation with optional article title prefilling and sample length control', 'compute mean average precision using scikit-learn for one-hot encoded ground truth and prediction arrays', 'compute recall at k score using scikit-learn top-k accuracy on prediction arrays']
```

Usage

```
{'build_updater_multi_gpu': 'build a data parallel Updater with multi-GPU support for a Graph2text loss function and optax optimizer', 'create_updater_init': 'create an Updater instance and initialize its state with training data and an RNG key', 'run_updater_update': 'run a training step by calling update on the Updater with batch data to get new state and metrics', 'eval_updater_metrics': 'evaluate the current model state on data without updating parameters and return loss metrics', 'save_checkpoint_state': 'save the Updater state to a pickle checkpoint file using CheckpointingUpdater for later resumption'}
```

## File: google-deepmind_deepmind-research/wikigraphs/utils.py

Prompts

```
['build a data parallel Updater with multi-GPU support for a Graph2text loss function and optax optimizer', 'create an Updater instance and initialize its state with training data and an RNG key', 'run a training step by calling update on the Updater with batch data to get new state and metrics', 'evaluate the current model state on data without updating parameters and return loss metrics', 'save the Updater state to a pickle checkpoint file using CheckpointingUpdater for later resumption', 'compute the BLEU score of translated text segments against reference corpus with configurable n-gram order', 'extract the title from tokenized wikitext articles by finding the first double newline token', 'construct prompts for text generation with optional article title prefilling and sample length control', 'compute mean average precision using scikit-learn for one-hot encoded ground truth and prediction arrays', 'compute recall at k score using scikit-learn top-k accuracy on prediction arrays']
```

Usage

```
{'compute_bleu_score': 'compute the BLEU score of translated text segments against reference corpus with configurable n-gram order', 'extract_title_from_text': 'extract the title from tokenized wikitext articles by finding the first double newline token', 'construct_prompts_for_generation': 'construct prompts for text generation with optional article title prefilling and sample length control', 'compute_map_sklearn': 'compute mean average precision using scikit-learn for one-hot encoded ground truth and prediction arrays', 'compute_recall_at_k': 'compute recall at k score using scikit-learn top-k accuracy on prediction arrays'}
```


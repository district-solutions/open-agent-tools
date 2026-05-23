# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/eval/auto_pcp/audio_comparator.py

Prompts

```
['compare two lists of audio files and return similarity scores using a trained comparator model', 'compute wav2vec2 embeddings for a list of audio files with optional layer selection and pooling', 'load a trained Comparator model and config from a checkpoint file or directory', 'save a Comparator model state dict and config to an output directory', 'get predictions from a Comparator model by batching source, reference, and translation tensors', 'train a Comparator model on audio pairs with MSE loss and AdamW optimizer', 'train a Comparator model with early stopping based on Spearman correlation on validation data', 'train a Comparator model using a custom data shuffler and configurable learning rate schedule', 'split audio comparison data into train, dev, and test sets using a boolean mask', 'split audio data and double training pairs by swapping x1 and x2 for augmentation', 'find k nearest neighbors between two sets of embedding vectors using FAISS IVF index', 'find hard negative text pairs with high similarity using a SentenceTransformer encoder', 'sample positive and negative pairs from embeddings for contrastive training batches', 'compute a hinge-like ranking loss with L2 regularization on model predictions', 'train a comparator model with mixed supervised regression and contrastive loss objectives', 'create a Prober instance from a TSV dataset path with optional model and training arguments', 'compute source and target audio embeddings for the dataset using a custom featurizer function', 'run a prosody probing experiment by training a PCP predictor on features and evaluating per domain', 'generate a DataFrame of Spearman correlations between predictions and human PCP scores across experiments', 'review the Prober class for prosodic similarity evaluation using PCP annotations and comparator models']
```

Usage

```
{'compare_audio_pairs': 'compare two lists of audio files and return similarity scores using a trained comparator model', 'encode_audios': 'compute wav2vec2 embeddings for a list of audio files with optional layer selection and pooling', 'Comparator_load': 'load a trained Comparator model and config from a checkpoint file or directory', 'Comparator_save': 'save a Comparator model state dict and config to an output directory', 'get_model_pred': 'get predictions from a Comparator model by batching source, reference, and translation tensors'}
```

## File: facebookresearch_stopes/stopes/eval/auto_pcp/comparator_training.py

Prompts

```
['compare two lists of audio files and return similarity scores using a trained comparator model', 'compute wav2vec2 embeddings for a list of audio files with optional layer selection and pooling', 'load a trained Comparator model and config from a checkpoint file or directory', 'save a Comparator model state dict and config to an output directory', 'get predictions from a Comparator model by batching source, reference, and translation tensors', 'train a Comparator model on audio pairs with MSE loss and AdamW optimizer', 'train a Comparator model with early stopping based on Spearman correlation on validation data', 'train a Comparator model using a custom data shuffler and configurable learning rate schedule', 'split audio comparison data into train, dev, and test sets using a boolean mask', 'split audio data and double training pairs by swapping x1 and x2 for augmentation', 'find k nearest neighbors between two sets of embedding vectors using FAISS IVF index', 'find hard negative text pairs with high similarity using a SentenceTransformer encoder', 'sample positive and negative pairs from embeddings for contrastive training batches', 'compute a hinge-like ranking loss with L2 regularization on model predictions', 'train a comparator model with mixed supervised regression and contrastive loss objectives', 'create a Prober instance from a TSV dataset path with optional model and training arguments', 'compute source and target audio embeddings for the dataset using a custom featurizer function', 'run a prosody probing experiment by training a PCP predictor on features and evaluating per domain', 'generate a DataFrame of Spearman correlations between predictions and human PCP scores across experiments', 'review the Prober class for prosodic similarity evaluation using PCP annotations and comparator models']
```

Usage

```
{'train_comparator_model': 'train a Comparator model on audio pairs with MSE loss and AdamW optimizer', 'train_comparator_with_early_stopping': 'train a Comparator model with early stopping based on Spearman correlation on validation data', 'train_comparator_with_custom_shuffler': 'train a Comparator model using a custom data shuffler and configurable learning rate schedule', 'split_data_for_training': 'split audio comparison data into train, dev, and test sets using a boolean mask', 'split_data_with_augmentation': 'split audio data and double training pairs by swapping x1 and x2 for augmentation'}
```

## File: facebookresearch_stopes/stopes/eval/auto_pcp/contrastive_training.py

Prompts

```
['compare two lists of audio files and return similarity scores using a trained comparator model', 'compute wav2vec2 embeddings for a list of audio files with optional layer selection and pooling', 'load a trained Comparator model and config from a checkpoint file or directory', 'save a Comparator model state dict and config to an output directory', 'get predictions from a Comparator model by batching source, reference, and translation tensors', 'train a Comparator model on audio pairs with MSE loss and AdamW optimizer', 'train a Comparator model with early stopping based on Spearman correlation on validation data', 'train a Comparator model using a custom data shuffler and configurable learning rate schedule', 'split audio comparison data into train, dev, and test sets using a boolean mask', 'split audio data and double training pairs by swapping x1 and x2 for augmentation', 'find k nearest neighbors between two sets of embedding vectors using FAISS IVF index', 'find hard negative text pairs with high similarity using a SentenceTransformer encoder', 'sample positive and negative pairs from embeddings for contrastive training batches', 'compute a hinge-like ranking loss with L2 regularization on model predictions', 'train a comparator model with mixed supervised regression and contrastive loss objectives', 'create a Prober instance from a TSV dataset path with optional model and training arguments', 'compute source and target audio embeddings for the dataset using a custom featurizer function', 'run a prosody probing experiment by training a PCP predictor on features and evaluating per domain', 'generate a DataFrame of Spearman correlations between predictions and human PCP scores across experiments', 'review the Prober class for prosodic similarity evaluation using PCP annotations and comparator models']
```

Usage

```
{'get_neighbors': 'find k nearest neighbors between two sets of embedding vectors using FAISS IVF index', 'find_similar_texts_ids': 'find hard negative text pairs with high similarity using a SentenceTransformer encoder', 'get_contrastive_sample': 'sample positive and negative pairs from embeddings for contrastive training batches', 'ranking_loss': 'compute a hinge-like ranking loss with L2 regularization on model predictions', 'combined_training': 'train a comparator model with mixed supervised regression and contrastive loss objectives'}
```

## File: facebookresearch_stopes/stopes/eval/auto_pcp/prosody_probing.py

Prompts

```
['compare two lists of audio files and return similarity scores using a trained comparator model', 'compute wav2vec2 embeddings for a list of audio files with optional layer selection and pooling', 'load a trained Comparator model and config from a checkpoint file or directory', 'save a Comparator model state dict and config to an output directory', 'get predictions from a Comparator model by batching source, reference, and translation tensors', 'train a Comparator model on audio pairs with MSE loss and AdamW optimizer', 'train a Comparator model with early stopping based on Spearman correlation on validation data', 'train a Comparator model using a custom data shuffler and configurable learning rate schedule', 'split audio comparison data into train, dev, and test sets using a boolean mask', 'split audio data and double training pairs by swapping x1 and x2 for augmentation', 'find k nearest neighbors between two sets of embedding vectors using FAISS IVF index', 'find hard negative text pairs with high similarity using a SentenceTransformer encoder', 'sample positive and negative pairs from embeddings for contrastive training batches', 'compute a hinge-like ranking loss with L2 regularization on model predictions', 'train a comparator model with mixed supervised regression and contrastive loss objectives', 'create a Prober instance from a TSV dataset path with optional model and training arguments', 'compute source and target audio embeddings for the dataset using a custom featurizer function', 'run a prosody probing experiment by training a PCP predictor on features and evaluating per domain', 'generate a DataFrame of Spearman correlations between predictions and human PCP scores across experiments', 'review the Prober class for prosodic similarity evaluation using PCP annotations and comparator models']
```

Usage

```
{'create_prober_instance': 'create a Prober instance from a TSV dataset path with optional model and training arguments', 'compute_features': 'compute source and target audio embeddings for the dataset using a custom featurizer function', 'run_experiment': 'run a prosody probing experiment by training a PCP predictor on features and evaluating per domain', 'generate_report': 'generate a DataFrame of Spearman correlations between predictions and human PCP scores across experiments', 'review_prosody_probing': 'review the Prober class for prosodic similarity evaluation using PCP annotations and comparator models'}
```


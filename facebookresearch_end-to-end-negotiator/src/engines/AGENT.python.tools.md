# Agent Python Tools

- repo: facebookresearch/end-to-end-negotiator
- repo_uri: https://github.com/facebookresearch/end-to-end-negotiator

## File: facebookresearch_end-to-end-negotiator/src/engines/engine.py

Prompts

```
['create an Engine with a model and args then call train with a corpus to run full training with annealing', 'call Engine.forward with a model and batch to perform a forward pass returning language model and selection outputs', 'instantiate Criterion with a dictionary and optional bad tokens to build a weighted CrossEntropyLoss for training', 'call train_pass on an Engine with vocabulary size and trainset to execute one epoch of training with gradient clipping', 'call valid_pass on an Engine with vocabulary size and validset to evaluate loss and selection loss on validation data', 'train a LatentClusteringEngine model batch with language, selection, KL divergence, and clustering loss', 'validate a LatentClusteringEngine model batch and return language loss, selection loss, and stats', 'train a LatentClusteringPredictionEngine batch while freezing the latent bottleneck and language model parameters', 'train a LatentClusteringLanguageEngine batch using only cross-entropy language modeling loss', 'run a full training pass with BaselineClusteringEngine over a dataset and report average loss and entropy', 'create an RnnEngine instance with a model, args, and optional verbose flag', 'run train_batch on the RnnEngine to compute loss, backpropagate, and update model weights', 'run valid_batch on the RnnEngine to compute validation loss and selection loss without gradients', 'review the RnnEngine _forward method that unpacks a batch into context, input, target, and selection target Variables', 'refactor the RnnEngine train_batch method to adjust loss weighting or gradient clipping thresholds', 'create a SelectionEngine instance with a model, args, and optional verbose flag', 'review the SelectionEngine _forward method that unpacks batches and wraps tensors in Variables before model inference', 'refactor the SelectionEngine to use a different Criterion reduction mode for selection loss computation']
```

Usage

```
{'train_model_with_engine': 'create an Engine with a model and args then call train with a corpus to run full training with annealing', 'run_forward_pass': 'call Engine.forward with a model and batch to perform a forward pass returning language model and selection outputs', 'create_weighted_criterion': 'instantiate Criterion with a dictionary and optional bad tokens to build a weighted CrossEntropyLoss for training', 'run_training_pass': 'call train_pass on an Engine with vocabulary size and trainset to execute one epoch of training with gradient clipping', 'run_validation_pass': 'call valid_pass on an Engine with vocabulary size and validset to evaluate loss and selection loss on validation data'}
```

## File: facebookresearch_end-to-end-negotiator/src/engines/latent_clustering_engine.py

Prompts

```
['create an Engine with a model and args then call train with a corpus to run full training with annealing', 'call Engine.forward with a model and batch to perform a forward pass returning language model and selection outputs', 'instantiate Criterion with a dictionary and optional bad tokens to build a weighted CrossEntropyLoss for training', 'call train_pass on an Engine with vocabulary size and trainset to execute one epoch of training with gradient clipping', 'call valid_pass on an Engine with vocabulary size and validset to evaluate loss and selection loss on validation data', 'train a LatentClusteringEngine model batch with language, selection, KL divergence, and clustering loss', 'validate a LatentClusteringEngine model batch and return language loss, selection loss, and stats', 'train a LatentClusteringPredictionEngine batch while freezing the latent bottleneck and language model parameters', 'train a LatentClusteringLanguageEngine batch using only cross-entropy language modeling loss', 'run a full training pass with BaselineClusteringEngine over a dataset and report average loss and entropy', 'create an RnnEngine instance with a model, args, and optional verbose flag', 'run train_batch on the RnnEngine to compute loss, backpropagate, and update model weights', 'run valid_batch on the RnnEngine to compute validation loss and selection loss without gradients', 'review the RnnEngine _forward method that unpacks a batch into context, input, target, and selection target Variables', 'refactor the RnnEngine train_batch method to adjust loss weighting or gradient clipping thresholds', 'create a SelectionEngine instance with a model, args, and optional verbose flag', 'review the SelectionEngine _forward method that unpacks batches and wraps tensors in Variables before model inference', 'refactor the SelectionEngine to use a different Criterion reduction mode for selection loss computation']
```

Usage

```
{'train_LatentClusteringEngine': 'train a LatentClusteringEngine model batch with language, selection, KL divergence, and clustering loss', 'validate_LatentClusteringEngine': 'validate a LatentClusteringEngine model batch and return language loss, selection loss, and stats', 'train_LatentClusteringPredictionEngine': 'train a LatentClusteringPredictionEngine batch while freezing the latent bottleneck and language model parameters', 'train_LatentClusteringLanguageEngine': 'train a LatentClusteringLanguageEngine batch using only cross-entropy language modeling loss', 'run_BaselineClusteringEngine_train_pass': 'run a full training pass with BaselineClusteringEngine over a dataset and report average loss and entropy'}
```

## File: facebookresearch_end-to-end-negotiator/src/engines/rnn_engine.py

Prompts

```
['create an Engine with a model and args then call train with a corpus to run full training with annealing', 'call Engine.forward with a model and batch to perform a forward pass returning language model and selection outputs', 'instantiate Criterion with a dictionary and optional bad tokens to build a weighted CrossEntropyLoss for training', 'call train_pass on an Engine with vocabulary size and trainset to execute one epoch of training with gradient clipping', 'call valid_pass on an Engine with vocabulary size and validset to evaluate loss and selection loss on validation data', 'train a LatentClusteringEngine model batch with language, selection, KL divergence, and clustering loss', 'validate a LatentClusteringEngine model batch and return language loss, selection loss, and stats', 'train a LatentClusteringPredictionEngine batch while freezing the latent bottleneck and language model parameters', 'train a LatentClusteringLanguageEngine batch using only cross-entropy language modeling loss', 'run a full training pass with BaselineClusteringEngine over a dataset and report average loss and entropy', 'create an RnnEngine instance with a model, args, and optional verbose flag', 'run train_batch on the RnnEngine to compute loss, backpropagate, and update model weights', 'run valid_batch on the RnnEngine to compute validation loss and selection loss without gradients', 'review the RnnEngine _forward method that unpacks a batch into context, input, target, and selection target Variables', 'refactor the RnnEngine train_batch method to adjust loss weighting or gradient clipping thresholds', 'create a SelectionEngine instance with a model, args, and optional verbose flag', 'review the SelectionEngine _forward method that unpacks batches and wraps tensors in Variables before model inference', 'refactor the SelectionEngine to use a different Criterion reduction mode for selection loss computation']
```

Usage

```
{'create_RnnEngine': 'create an RnnEngine instance with a model, args, and optional verbose flag', 'run_train_batch': 'run train_batch on the RnnEngine to compute loss, backpropagate, and update model weights', 'run_valid_batch': 'run valid_batch on the RnnEngine to compute validation loss and selection loss without gradients', 'review_RnnEngine_forward': 'review the RnnEngine _forward method that unpacks a batch into context, input, target, and selection target Variables', 'refactor_RnnEngine_train_batch': 'refactor the RnnEngine train_batch method to adjust loss weighting or gradient clipping thresholds'}
```

## File: facebookresearch_end-to-end-negotiator/src/engines/selection_engine.py

Prompts

```
['create an Engine with a model and args then call train with a corpus to run full training with annealing', 'call Engine.forward with a model and batch to perform a forward pass returning language model and selection outputs', 'instantiate Criterion with a dictionary and optional bad tokens to build a weighted CrossEntropyLoss for training', 'call train_pass on an Engine with vocabulary size and trainset to execute one epoch of training with gradient clipping', 'call valid_pass on an Engine with vocabulary size and validset to evaluate loss and selection loss on validation data', 'train a LatentClusteringEngine model batch with language, selection, KL divergence, and clustering loss', 'validate a LatentClusteringEngine model batch and return language loss, selection loss, and stats', 'train a LatentClusteringPredictionEngine batch while freezing the latent bottleneck and language model parameters', 'train a LatentClusteringLanguageEngine batch using only cross-entropy language modeling loss', 'run a full training pass with BaselineClusteringEngine over a dataset and report average loss and entropy', 'create an RnnEngine instance with a model, args, and optional verbose flag', 'run train_batch on the RnnEngine to compute loss, backpropagate, and update model weights', 'run valid_batch on the RnnEngine to compute validation loss and selection loss without gradients', 'review the RnnEngine _forward method that unpacks a batch into context, input, target, and selection target Variables', 'refactor the RnnEngine train_batch method to adjust loss weighting or gradient clipping thresholds', 'create a SelectionEngine instance with a model, args, and optional verbose flag', 'review the SelectionEngine _forward method that unpacks batches and wraps tensors in Variables before model inference', 'refactor the SelectionEngine to use a different Criterion reduction mode for selection loss computation']
```

Usage

```
{'create_SelectionEngine': 'create a SelectionEngine instance with a model, args, and optional verbose flag', 'run_train_batch': 'run a training step on a batch by calling train_batch to compute loss and update gradients', 'run_valid_batch': 'run a validation step on a batch by calling valid_batch to compute loss without gradients', 'review_SelectionEngine_forward': 'review the SelectionEngine _forward method that unpacks batches and wraps tensors in Variables before model inference', 'refactor_SelectionEngine_crit': 'refactor the SelectionEngine to use a different Criterion reduction mode for selection loss computation'}
```


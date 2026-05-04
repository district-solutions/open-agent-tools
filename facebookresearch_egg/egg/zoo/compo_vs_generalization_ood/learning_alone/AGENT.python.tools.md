# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/compo_vs_generalization_ood/learning_alone/data.py

Prompts

```
['remap a batch of tensor examples using a value mapping and duplicate even values with EOS and PAD tokens', 'create a PyTorch DataLoader from examples with a custom collate function that remaps batches using a value mapping', 'get train, uniform holdout, and OOD generalization DataLoaders for a compositional generalization experiment with a random value mapping', 'review the remap_batch function to understand how it applies value mappings and duplicates even-valued tokens in tensor batches', 'summarize the get_data function that returns train and test DataLoaders for uniform and OOD generalization evaluation', 'run the main training loop for sender or receiver models on OOD generalization datasets', 'repackage an original model class to adapt input and output formats for learning alone experiments', 'get the number of correct predictions ignoring sequence tail after EOS token for encoder evaluation', 'get the number of exact match correct predictions across the full sequence length', 'get parsed command line arguments for model architecture and training hyperparameters']
```

Usage

```
{'remap_batch': 'remap a batch of tensor examples using a value mapping and duplicate even values with EOS and PAD tokens', 'datasetify': 'create a PyTorch DataLoader from examples with a custom collate function that remaps batches using a value mapping', 'get_data': 'get train, uniform holdout, and OOD generalization DataLoaders for a compositional generalization experiment with a random value mapping', 'review_remap_batch': 'review the remap_batch function to understand how it applies value mappings and duplicates even-valued tokens in tensor batches', 'summarize_get_data': 'summarize the get_data function that returns train and test DataLoaders for uniform and OOD generalization evaluation'}
```

## File: facebookresearch_egg/egg/zoo/compo_vs_generalization_ood/learning_alone/train.py

Prompts

```
['remap a batch of tensor examples using a value mapping and duplicate even values with EOS and PAD tokens', 'create a PyTorch DataLoader from examples with a custom collate function that remaps batches using a value mapping', 'get train, uniform holdout, and OOD generalization DataLoaders for a compositional generalization experiment with a random value mapping', 'review the remap_batch function to understand how it applies value mappings and duplicates even-valued tokens in tensor batches', 'summarize the get_data function that returns train and test DataLoaders for uniform and OOD generalization evaluation', 'run the main training loop for sender or receiver models on OOD generalization datasets', 'repackage an original model class to adapt input and output formats for learning alone experiments', 'get the number of correct predictions ignoring sequence tail after EOS token for encoder evaluation', 'get the number of exact match correct predictions across the full sequence length', 'get parsed command line arguments for model architecture and training hyperparameters']
```

Usage

```
{'run_train_loop': 'run the main training loop for sender or receiver models on OOD generalization datasets', 'repackage_model': 'repackage an original model class to adapt input and output formats for learning alone experiments', 'get_n_correct_ignore_tail': 'get the number of correct predictions ignoring sequence tail after EOS token for encoder evaluation', 'get_n_correct_exactmatch': 'get the number of exact match correct predictions across the full sequence length', 'get_params': 'get parsed command line arguments for model architecture and training hyperparameters'}
```


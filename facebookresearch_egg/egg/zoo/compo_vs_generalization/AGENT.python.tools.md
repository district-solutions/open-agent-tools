# Agent Python Tools

- repo: facebookresearch/egg
- repo_uri: https://github.com/facebookresearch/egg

## File: facebookresearch_egg/egg/zoo/compo_vs_generalization/archs.py

Prompts

```
['create a Receiver nn.Module that maps n_hidden features to n_outputs via a single linear layer', 'create a Sender nn.Module that projects n_inputs down to n_hidden dimensions using a linear layer', 'build a NonLinearReceiver that embeds token sequences with a diagonal embedding and processes them through two FC layers', 'wrap an existing nn.Module with Freezer to freeze parameters and run inference without gradients', 'wrap a module returning three values with PlusOneWrapper to add one to the first return value', 'enumerate all combinations of attribute values given n_attributes and n_values parameters', 'select a subset of data where each attribute value is constrained to a chosen set', 'sample a subset of data using diagonal sampling to ensure each attribute appears at least once', 'convert a list of attribute configurations into one-hot encoded PyTorch tensors', 'split a dataset into train and holdout sets based on zero-value indicators in each sample', 'run ask_sender to collect attributes, strings, and meanings from a sender model on a dataset', 'run information_gap_position to compute the positional information gap score for a sender model', 'run information_gap_vocab to compute the bag-of-symbols information gap score for a sender model', 'run topographic_similarity to compute the Spearman correlation between edit distances of messages and cosine distances of inputs', 'run the Metrics callback to log positional disentanglement, bag-of-symbol disentanglement, and topographic similarity at each epoch', 'run the compositional generalization training pipeline with sender-receiver RNN agents via command line arguments', 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for attribute-value communication', 'run get_params to parse command line arguments for n_attributes, n_values, sender and receiver hidden sizes', 'review the DiffLoss class generalization mode that masks attributes and computes per-attribute accuracy metrics', 'run retrain_receiver to freeze a trained sender and retrain a new receiver architecture with Adam optimizer']
```

Usage

```
{'create_receiver_module': 'create a Receiver nn.Module that maps n_hidden features to n_outputs via a single linear layer', 'create_sender_module': 'create a Sender nn.Module that projects n_inputs down to n_hidden dimensions using a linear layer', 'build_nonlinear_receiver': 'build a NonLinearReceiver that embeds token sequences with a diagonal embedding and processes them through two FC layers', 'wrap_model_with_freezer': 'wrap an existing nn.Module with Freezer to freeze parameters and run inference without gradients', 'wrap_model_with_plusone': 'wrap a module returning three values with PlusOneWrapper to add one to the first return value'}
```

## File: facebookresearch_egg/egg/zoo/compo_vs_generalization/data.py

Prompts

```
['create a Receiver nn.Module that maps n_hidden features to n_outputs via a single linear layer', 'create a Sender nn.Module that projects n_inputs down to n_hidden dimensions using a linear layer', 'build a NonLinearReceiver that embeds token sequences with a diagonal embedding and processes them through two FC layers', 'wrap an existing nn.Module with Freezer to freeze parameters and run inference without gradients', 'wrap a module returning three values with PlusOneWrapper to add one to the first return value', 'enumerate all combinations of attribute values given n_attributes and n_values parameters', 'select a subset of data where each attribute value is constrained to a chosen set', 'sample a subset of data using diagonal sampling to ensure each attribute appears at least once', 'convert a list of attribute configurations into one-hot encoded PyTorch tensors', 'split a dataset into train and holdout sets based on zero-value indicators in each sample', 'run ask_sender to collect attributes, strings, and meanings from a sender model on a dataset', 'run information_gap_position to compute the positional information gap score for a sender model', 'run information_gap_vocab to compute the bag-of-symbols information gap score for a sender model', 'run topographic_similarity to compute the Spearman correlation between edit distances of messages and cosine distances of inputs', 'run the Metrics callback to log positional disentanglement, bag-of-symbol disentanglement, and topographic similarity at each epoch', 'run the compositional generalization training pipeline with sender-receiver RNN agents via command line arguments', 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for attribute-value communication', 'run get_params to parse command line arguments for n_attributes, n_values, sender and receiver hidden sizes', 'review the DiffLoss class generalization mode that masks attributes and computes per-attribute accuracy metrics', 'run retrain_receiver to freeze a trained sender and retrain a new receiver architecture with Adam optimizer']
```

Usage

```
{'enumerate_attribute_combinations': 'enumerate all combinations of attribute values given n_attributes and n_values parameters', 'select_subset_V1_filter_data': 'select a subset of data where each attribute value is constrained to a chosen set', 'select_subset_V2_diagonal_sample': 'sample a subset of data using diagonal sampling to ensure each attribute appears at least once', 'one_hotify_encode_data': 'convert a list of attribute configurations into one-hot encoded PyTorch tensors', 'split_holdout_train_test': 'split a dataset into train and holdout sets based on zero-value indicators in each sample'}
```

## File: facebookresearch_egg/egg/zoo/compo_vs_generalization/intervention.py

Prompts

```
['create a Receiver nn.Module that maps n_hidden features to n_outputs via a single linear layer', 'create a Sender nn.Module that projects n_inputs down to n_hidden dimensions using a linear layer', 'build a NonLinearReceiver that embeds token sequences with a diagonal embedding and processes them through two FC layers', 'wrap an existing nn.Module with Freezer to freeze parameters and run inference without gradients', 'wrap a module returning three values with PlusOneWrapper to add one to the first return value', 'enumerate all combinations of attribute values given n_attributes and n_values parameters', 'select a subset of data where each attribute value is constrained to a chosen set', 'sample a subset of data using diagonal sampling to ensure each attribute appears at least once', 'convert a list of attribute configurations into one-hot encoded PyTorch tensors', 'split a dataset into train and holdout sets based on zero-value indicators in each sample', 'run ask_sender to collect attributes, strings, and meanings from a sender model on a dataset', 'run information_gap_position to compute the positional information gap score for a sender model', 'run information_gap_vocab to compute the bag-of-symbols information gap score for a sender model', 'run topographic_similarity to compute the Spearman correlation between edit distances of messages and cosine distances of inputs', 'run the Metrics callback to log positional disentanglement, bag-of-symbol disentanglement, and topographic similarity at each epoch', 'run the compositional generalization training pipeline with sender-receiver RNN agents via command line arguments', 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for attribute-value communication', 'run get_params to parse command line arguments for n_attributes, n_values, sender and receiver hidden sizes', 'review the DiffLoss class generalization mode that masks attributes and computes per-attribute accuracy metrics', 'run retrain_receiver to freeze a trained sender and retrain a new receiver architecture with Adam optimizer']
```

Usage

```
{'run_ask_sender': 'run ask_sender to collect attributes, strings, and meanings from a sender model on a dataset', 'run_information_gap_position': 'run information_gap_position to compute the positional information gap score for a sender model', 'run_information_gap_vocab': 'run information_gap_vocab to compute the bag-of-symbols information gap score for a sender model', 'run_topographic_similarity': 'run topographic_similarity to compute the Spearman correlation between edit distances of messages and cosine distances of inputs', 'run_Metrics_callback': 'run the Metrics callback to log positional disentanglement, bag-of-symbol disentanglement, and topographic similarity at each epoch'}
```

## File: facebookresearch_egg/egg/zoo/compo_vs_generalization/train.py

Prompts

```
['create a Receiver nn.Module that maps n_hidden features to n_outputs via a single linear layer', 'create a Sender nn.Module that projects n_inputs down to n_hidden dimensions using a linear layer', 'build a NonLinearReceiver that embeds token sequences with a diagonal embedding and processes them through two FC layers', 'wrap an existing nn.Module with Freezer to freeze parameters and run inference without gradients', 'wrap a module returning three values with PlusOneWrapper to add one to the first return value', 'enumerate all combinations of attribute values given n_attributes and n_values parameters', 'select a subset of data where each attribute value is constrained to a chosen set', 'sample a subset of data using diagonal sampling to ensure each attribute appears at least once', 'convert a list of attribute configurations into one-hot encoded PyTorch tensors', 'split a dataset into train and holdout sets based on zero-value indicators in each sample', 'run ask_sender to collect attributes, strings, and meanings from a sender model on a dataset', 'run information_gap_position to compute the positional information gap score for a sender model', 'run information_gap_vocab to compute the bag-of-symbols information gap score for a sender model', 'run topographic_similarity to compute the Spearman correlation between edit distances of messages and cosine distances of inputs', 'run the Metrics callback to log positional disentanglement, bag-of-symbol disentanglement, and topographic similarity at each epoch', 'run the compositional generalization training pipeline with sender-receiver RNN agents via command line arguments', 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for attribute-value communication', 'run get_params to parse command line arguments for n_attributes, n_values, sender and receiver hidden sizes', 'review the DiffLoss class generalization mode that masks attributes and computes per-attribute accuracy metrics', 'run retrain_receiver to freeze a trained sender and retrain a new receiver architecture with Adam optimizer']
```

Usage

```
{'run_training_pipeline': 'run the compositional generalization training pipeline with sender-receiver RNN agents via command line arguments', 'run_DiffLoss_forward': 'run the DiffLoss forward pass to compute cross-entropy loss and accuracy for attribute-value communication', 'run_get_params': 'run get_params to parse command line arguments for n_attributes, n_values, sender and receiver hidden sizes', 'review_DiffLoss_generalization': 'review the DiffLoss class generalization mode that masks attributes and computes per-attribute accuracy metrics', 'run_retrain_receiver': 'run retrain_receiver to freeze a trained sender and retrain a new receiver architecture with Adam optimizer'}
```


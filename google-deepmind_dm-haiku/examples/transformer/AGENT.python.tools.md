# Agent Python Tools

- repo: google-deepmind/dm-haiku
- repo_uri: https://github.com/google-deepmind/dm-haiku

## File: google-deepmind_dm-haiku/examples/transformer/dataset.py

Prompts

```
['load an ASCII text corpus into shuffled batches of integer tokens for language modelling', 'create a Batch namedtuple with inputs and targets numpy arrays for transformer training', 'repeat a dataset iterator infinitely using itertools cycle for continuous training loops', 'shuffle a dataset iterator with a reservoir buffer for randomized batch sampling', 'review the load_ascii_dataset function to understand ASCII tokenization and batching logic', 'run the transformer language model training loop on a text dataset via --dataset_path', 'initialize a TrainingState with random parameters and optimizer state for the language model', 'perform a single JIT-compiled SGD update step returning new state and loss metrics', 'run the forward pass of the Haiku LanguageModel to get logits from input tokens', 'compute the masked negative log-likelihood loss for language modeling using hk.transform']
```

Usage

```
{'load_ascii_dataset': 'load an ASCII text corpus into shuffled batches of integer tokens for language modelling', 'create_batch_namedtuple': 'create a Batch namedtuple with inputs and targets numpy arrays for transformer training', 'repeat_dataset': 'repeat a dataset iterator infinitely using itertools cycle for continuous training loops', 'shuffle_dataset': 'shuffle a dataset iterator with a reservoir buffer for randomized batch sampling', 'review_load_ascii_dataset': 'review the load_ascii_dataset function to understand ASCII tokenization and batching logic'}
```

## File: google-deepmind_dm-haiku/examples/transformer/train.py

Prompts

```
['load an ASCII text corpus into shuffled batches of integer tokens for language modelling', 'create a Batch namedtuple with inputs and targets numpy arrays for transformer training', 'repeat a dataset iterator infinitely using itertools cycle for continuous training loops', 'shuffle a dataset iterator with a reservoir buffer for randomized batch sampling', 'review the load_ascii_dataset function to understand ASCII tokenization and batching logic', 'run the transformer language model training loop on a text dataset via --dataset_path', 'initialize a TrainingState with random parameters and optimizer state for the language model', 'perform a single JIT-compiled SGD update step returning new state and loss metrics', 'run the forward pass of the Haiku LanguageModel to get logits from input tokens', 'compute the masked negative log-likelihood loss for language modeling using hk.transform']
```

Usage

```
{'run_transformer_training': 'run the transformer language model training loop on a text dataset via --dataset_path', 'init_training_state': 'initialize a TrainingState with random parameters and optimizer state for the language model', 'update_training_step': 'perform a single JIT-compiled SGD update step returning new state and loss metrics', 'forward_pass_logits': 'run the forward pass of the Haiku LanguageModel to get logits from input tokens', 'loss_fn_nll': 'compute the masked negative log-likelihood loss for language modeling using hk.transform'}
```


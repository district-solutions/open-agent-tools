# Agent Python Tools

- repo: google-deepmind/dm-haiku
- repo_uri: https://github.com/google-deepmind/dm-haiku

## File: google-deepmind_dm-haiku/examples/rnn/dataset.py

Prompts

```
['load the Tiny Shakespeare dataset as a character-level language modelling iterator with batching and shuffling', 'decode a numpy array of character IDs back into a human-readable string', 'encode a string into a numpy array of character ordinal values', 'review the load function preprocessing pipeline that splits text into characters and creates input-target pairs', 'summarize the dataset module constants including NUM_CHARS and the Batch type alias', 'run the character-level language model training loop with LSTM layers on a text dataset', 'build a DeepRNN network with stacked LSTM layers and an MLP output head for character prediction', 'compute the cross-entropy sequence loss by dynamically unrolling the RNN over input and target sequences', 'update the model parameters and optimizer state by computing gradients and applying Adam updates', 'sample character sequences from the trained RNN model given an initial context string']
```

Usage

```
{'load_tiny_shakespeare_dataset': 'load the Tiny Shakespeare dataset as a character-level language modelling iterator with batching and shuffling', 'decode_numpy_to_string': 'decode a numpy array of character IDs back into a human-readable string', 'encode_string_to_numpy': 'encode a string into a numpy array of character ordinal values', 'review_load_preprocessing': 'review the load function preprocessing pipeline that splits text into characters and creates input-target pairs', 'summarize_dataset_constants': 'summarize the dataset module constants including NUM_CHARS and the Batch type alias'}
```

## File: google-deepmind_dm-haiku/examples/rnn/train.py

Prompts

```
['load the Tiny Shakespeare dataset as a character-level language modelling iterator with batching and shuffling', 'decode a numpy array of character IDs back into a human-readable string', 'encode a string into a numpy array of character ordinal values', 'review the load function preprocessing pipeline that splits text into characters and creates input-target pairs', 'summarize the dataset module constants including NUM_CHARS and the Batch type alias', 'run the character-level language model training loop with LSTM layers on a text dataset', 'build a DeepRNN network with stacked LSTM layers and an MLP output head for character prediction', 'compute the cross-entropy sequence loss by dynamically unrolling the RNN over input and target sequences', 'update the model parameters and optimizer state by computing gradients and applying Adam updates', 'sample character sequences from the trained RNN model given an initial context string']
```

Usage

```
{'run_rnn_training': 'run the character-level language model training loop with LSTM layers on a text dataset', 'build_deep_rnn_network': 'build a DeepRNN network with stacked LSTM layers and an MLP output head for character prediction', 'compute_sequence_loss': 'compute the cross-entropy sequence loss by dynamically unrolling the RNN over input and target sequences', 'update_training_state': 'update the model parameters and optimizer state by computing gradients and applying Adam updates', 'sample_text_from_model': 'sample character sequences from the trained RNN model given an initial context string'}
```


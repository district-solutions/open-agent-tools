# Agent Python Tools

- repo: facebookresearch/cpcaudio
- repo_uri: https://github.com/facebookresearch/cpc_audio

## File: facebookresearch_cpcaudio/cpc/eval/ABX.py

Prompts

```
['run the ABX evaluation from a model checkpoint on a dataset with an item file', 'run the ABX evaluation using pre-computed torch feature files from a dataset', 'run the ABX evaluation in within-speaker mode to compute phone confusion scores', 'run the ABX evaluation in across-speaker mode to compute phone confusion scores', 'run the ABX evaluation in debug mode limited to the first 1000 sequences', 'run the CLI to build ZeroSpeech Track1 evaluation features from a dataset using a CPC checkpoint', 'run buildAllFeature to extract and save features for all audio sequences in multiple output formats', 'run getArgs to load checkpoint arguments from a checkpoint_args.json file', 'refactor buildAllFeature to add a new output format beyond npz, fea, npy, and af', 'review the main CLI entry point for argument parsing, model loading, and feature extraction flow', 'train a CTC phone recognition model on Common Voices audio data using CPC features and an Adam optimizer', 'compute the phone error rate on a validation dataset using beam search and a trained CTC classifier', 'create a SingleSequenceDataset that loads audio sequences and phone labels from a directory for batched training', 'build a CTC phone classification criterion with optional LSTM, sequence normalization, and dropout layers', 'run a multi-epoch training loop with train and validation steps, saving the best checkpoint by validation loss', 'run the CPC linear separability trainer to evaluate speaker or phone separability on audio data', 'run a single training step for the linear separability criterion with backpropagation and optimizer updates', 'run a single validation step to compute loss and accuracy for the linear separability criterion', 'parse command line arguments for the linear separability trainer including paths, GPU count, and hyperparameters', 'run the main entry point that loads models, sets up data loaders, and starts linear separability training']
```

Usage

```
{'run_ABX_from_checkpoint': 'run the ABX evaluation from a model checkpoint on a dataset with an item file', 'run_ABX_from_pre_computed': 'run the ABX evaluation using pre-computed torch feature files from a dataset', 'run_ABX_within_speakers': 'run the ABX evaluation in within-speaker mode to compute phone confusion scores', 'run_ABX_across_speakers': 'run the ABX evaluation in across-speaker mode to compute phone confusion scores', 'run_ABX_debug': 'run the ABX evaluation in debug mode limited to the first 1000 sequences'}
```

## File: facebookresearch_cpcaudio/cpc/eval/build_zeroSpeech_features.py

Prompts

```
['run the ABX evaluation from a model checkpoint on a dataset with an item file', 'run the ABX evaluation using pre-computed torch feature files from a dataset', 'run the ABX evaluation in within-speaker mode to compute phone confusion scores', 'run the ABX evaluation in across-speaker mode to compute phone confusion scores', 'run the ABX evaluation in debug mode limited to the first 1000 sequences', 'run the CLI to build ZeroSpeech Track1 evaluation features from a dataset using a CPC checkpoint', 'run buildAllFeature to extract and save features for all audio sequences in multiple output formats', 'run getArgs to load checkpoint arguments from a checkpoint_args.json file', 'refactor buildAllFeature to add a new output format beyond npz, fea, npy, and af', 'review the main CLI entry point for argument parsing, model loading, and feature extraction flow', 'train a CTC phone recognition model on Common Voices audio data using CPC features and an Adam optimizer', 'compute the phone error rate on a validation dataset using beam search and a trained CTC classifier', 'create a SingleSequenceDataset that loads audio sequences and phone labels from a directory for batched training', 'build a CTC phone classification criterion with optional LSTM, sequence normalization, and dropout layers', 'run a multi-epoch training loop with train and validation steps, saving the best checkpoint by validation loss', 'run the CPC linear separability trainer to evaluate speaker or phone separability on audio data', 'run a single training step for the linear separability criterion with backpropagation and optimizer updates', 'run a single validation step to compute loss and accuracy for the linear separability criterion', 'parse command line arguments for the linear separability trainer including paths, GPU count, and hyperparameters', 'run the main entry point that loads models, sets up data loaders, and starts linear separability training']
```

Usage

```
{'run_build_zeroSpeech_features': 'run the CLI to build ZeroSpeech Track1 evaluation features from a dataset using a CPC checkpoint', 'run_buildAllFeature': 'run buildAllFeature to extract and save features for all audio sequences in multiple output formats', 'run_getArgs': 'run getArgs to load checkpoint arguments from a checkpoint_args.json file', 'refactor_buildAllFeature_format': 'refactor buildAllFeature to add a new output format beyond npz, fea, npy, and af', 'review_build_zeroSpeech_features_main': 'review the main CLI entry point for argument parsing, model loading, and feature extraction flow'}
```

## File: facebookresearch_cpcaudio/cpc/eval/common_voices_eval.py

Prompts

```
['run the ABX evaluation from a model checkpoint on a dataset with an item file', 'run the ABX evaluation using pre-computed torch feature files from a dataset', 'run the ABX evaluation in within-speaker mode to compute phone confusion scores', 'run the ABX evaluation in across-speaker mode to compute phone confusion scores', 'run the ABX evaluation in debug mode limited to the first 1000 sequences', 'run the CLI to build ZeroSpeech Track1 evaluation features from a dataset using a CPC checkpoint', 'run buildAllFeature to extract and save features for all audio sequences in multiple output formats', 'run getArgs to load checkpoint arguments from a checkpoint_args.json file', 'refactor buildAllFeature to add a new output format beyond npz, fea, npy, and af', 'review the main CLI entry point for argument parsing, model loading, and feature extraction flow', 'train a CTC phone recognition model on Common Voices audio data using CPC features and an Adam optimizer', 'compute the phone error rate on a validation dataset using beam search and a trained CTC classifier', 'create a SingleSequenceDataset that loads audio sequences and phone labels from a directory for batched training', 'build a CTC phone classification criterion with optional LSTM, sequence normalization, and dropout layers', 'run a multi-epoch training loop with train and validation steps, saving the best checkpoint by validation loss', 'run the CPC linear separability trainer to evaluate speaker or phone separability on audio data', 'run a single training step for the linear separability criterion with backpropagation and optimizer updates', 'run a single validation step to compute loss and accuracy for the linear separability criterion', 'parse command line arguments for the linear separability trainer including paths, GPU count, and hyperparameters', 'run the main entry point that loads models, sets up data loaders, and starts linear separability training']
```

Usage

```
{'train_phone_recognition_model': 'train a CTC phone recognition model on Common Voices audio data using CPC features and an Adam optimizer', 'compute_phone_error_rate': 'compute the phone error rate on a validation dataset using beam search and a trained CTC classifier', 'create_single_sequence_dataset': 'create a SingleSequenceDataset that loads audio sequences and phone labels from a directory for batched training', 'build_ctc_phone_criterion': 'build a CTC phone classification criterion with optional LSTM, sequence normalization, and dropout layers', 'run_training_loop': 'run a multi-epoch training loop with train and validation steps, saving the best checkpoint by validation loss'}
```

## File: facebookresearch_cpcaudio/cpc/eval/linear_separability.py

Prompts

```
['run the ABX evaluation from a model checkpoint on a dataset with an item file', 'run the ABX evaluation using pre-computed torch feature files from a dataset', 'run the ABX evaluation in within-speaker mode to compute phone confusion scores', 'run the ABX evaluation in across-speaker mode to compute phone confusion scores', 'run the ABX evaluation in debug mode limited to the first 1000 sequences', 'run the CLI to build ZeroSpeech Track1 evaluation features from a dataset using a CPC checkpoint', 'run buildAllFeature to extract and save features for all audio sequences in multiple output formats', 'run getArgs to load checkpoint arguments from a checkpoint_args.json file', 'refactor buildAllFeature to add a new output format beyond npz, fea, npy, and af', 'review the main CLI entry point for argument parsing, model loading, and feature extraction flow', 'train a CTC phone recognition model on Common Voices audio data using CPC features and an Adam optimizer', 'compute the phone error rate on a validation dataset using beam search and a trained CTC classifier', 'create a SingleSequenceDataset that loads audio sequences and phone labels from a directory for batched training', 'build a CTC phone classification criterion with optional LSTM, sequence normalization, and dropout layers', 'run a multi-epoch training loop with train and validation steps, saving the best checkpoint by validation loss', 'run the CPC linear separability trainer to evaluate speaker or phone separability on audio data', 'run a single training step for the linear separability criterion with backpropagation and optimizer updates', 'run a single validation step to compute loss and accuracy for the linear separability criterion', 'parse command line arguments for the linear separability trainer including paths, GPU count, and hyperparameters', 'run the main entry point that loads models, sets up data loaders, and starts linear separability training']
```

Usage

```
{'run_linear_separability_training': 'run the CPC linear separability trainer to evaluate speaker or phone separability on audio data', 'run_train_step': 'run a single training step for the linear separability criterion with backpropagation and optimizer updates', 'run_val_step': 'run a single validation step to compute loss and accuracy for the linear separability criterion', 'run_parse_args': 'parse command line arguments for the linear separability trainer including paths, GPU count, and hyperparameters', 'run_main': 'run the main entry point that loads models, sets up data loaders, and starts linear separability training'}
```


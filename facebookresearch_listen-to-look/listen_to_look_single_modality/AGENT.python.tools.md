# Agent Python Tools

- repo: facebookresearch/listen-to-look
- repo_uri: https://github.com/facebookresearch/listen-to-look

## File: facebookresearch_listen-to-look/listen_to_look_single_modality/data.py

Prompts

```
['create a training dataset with AudioVisualDataset and feature_collate_train collate function from args', 'create a validation dataset with AudioVisualDataset and feature_collate_val collate function from args', 'review the AudioVisualDataset class that loads video features and labels from a pickle file', 'refactor the feature_collate_train function to customize max_length or episode_length padding behavior', 'summarize the feature_collate_val function that pads and masks validation batch tensors', 'run get_parameters to parse command line arguments for deep learning training configuration', 'build an argparse parser with dataset model and training parameters for deep learning', 'create a training configuration with batch size learning rate and epoch settings', 'configure pretrained model weights and checkpoint paths for model loading', 'set train and test dataset file paths for pickle dataset loading', 'run one training epoch with a model, data loader, optimizer, and loss criterion', 'review the train_epoch function that computes avgpool and LSTM cross-entropy losses per batch', 'refactor train_epoch to support additional loss types beyond avgpool and LSTM cross-entropy', 'summarize the train_epoch function that logs accuracy and loss metrics via TensorBoard writer', 'test the train_epoch function with a mock data loader and model returning predictions', 'run the validation script to evaluate a pretrained Listen to Look model on the validation dataset', 'run the validate function to compute accuracy and mAP metrics on a validation data loader', 'run the main function to build the model, load a checkpoint, and validate against test data', 'review the validate function that computes avgpool, LSTM, and GT prediction accuracy and mAP metrics', 'review the main function that sets up the model, checkpointer, validation dataset, and runs validation']
```

Usage

```
{'create_training_dataset': 'create a training dataset with AudioVisualDataset and feature_collate_train collate function from args', 'create_validation_dataset': 'create a validation dataset with AudioVisualDataset and feature_collate_val collate function from args', 'review_AudioVisualDataset': 'review the AudioVisualDataset class that loads video features and labels from a pickle file', 'refactor_feature_collate_train': 'refactor the feature_collate_train function to customize max_length or episode_length padding behavior', 'summarize_feature_collate_val': 'summarize the feature_collate_val function that pads and masks validation batch tensors'}
```

## File: facebookresearch_listen-to-look/listen_to_look_single_modality/opts.py

Prompts

```
['create a training dataset with AudioVisualDataset and feature_collate_train collate function from args', 'create a validation dataset with AudioVisualDataset and feature_collate_val collate function from args', 'review the AudioVisualDataset class that loads video features and labels from a pickle file', 'refactor the feature_collate_train function to customize max_length or episode_length padding behavior', 'summarize the feature_collate_val function that pads and masks validation batch tensors', 'run get_parameters to parse command line arguments for deep learning training configuration', 'build an argparse parser with dataset model and training parameters for deep learning', 'create a training configuration with batch size learning rate and epoch settings', 'configure pretrained model weights and checkpoint paths for model loading', 'set train and test dataset file paths for pickle dataset loading', 'run one training epoch with a model, data loader, optimizer, and loss criterion', 'review the train_epoch function that computes avgpool and LSTM cross-entropy losses per batch', 'refactor train_epoch to support additional loss types beyond avgpool and LSTM cross-entropy', 'summarize the train_epoch function that logs accuracy and loss metrics via TensorBoard writer', 'test the train_epoch function with a mock data loader and model returning predictions', 'run the validation script to evaluate a pretrained Listen to Look model on the validation dataset', 'run the validate function to compute accuracy and mAP metrics on a validation data loader', 'run the main function to build the model, load a checkpoint, and validate against test data', 'review the validate function that computes avgpool, LSTM, and GT prediction accuracy and mAP metrics', 'review the main function that sets up the model, checkpointer, validation dataset, and runs validation']
```

Usage

```
{'run_get_parameters': 'run get_parameters to parse command line arguments for deep learning training configuration', 'build_argparse_parser': 'build an argparse parser with dataset model and training parameters for deep learning', 'create_training_config': 'create a training configuration with batch size learning rate and epoch settings', 'configure_model_weights': 'configure pretrained model weights and checkpoint paths for model loading', 'set_dataset_paths': 'set train and test dataset file paths for pickle dataset loading'}
```

## File: facebookresearch_listen-to-look/listen_to_look_single_modality/train.py

Prompts

```
['create a training dataset with AudioVisualDataset and feature_collate_train collate function from args', 'create a validation dataset with AudioVisualDataset and feature_collate_val collate function from args', 'review the AudioVisualDataset class that loads video features and labels from a pickle file', 'refactor the feature_collate_train function to customize max_length or episode_length padding behavior', 'summarize the feature_collate_val function that pads and masks validation batch tensors', 'run get_parameters to parse command line arguments for deep learning training configuration', 'build an argparse parser with dataset model and training parameters for deep learning', 'create a training configuration with batch size learning rate and epoch settings', 'configure pretrained model weights and checkpoint paths for model loading', 'set train and test dataset file paths for pickle dataset loading', 'run one training epoch with a model, data loader, optimizer, and loss criterion', 'review the train_epoch function that computes avgpool and LSTM cross-entropy losses per batch', 'refactor train_epoch to support additional loss types beyond avgpool and LSTM cross-entropy', 'summarize the train_epoch function that logs accuracy and loss metrics via TensorBoard writer', 'test the train_epoch function with a mock data loader and model returning predictions', 'run the validation script to evaluate a pretrained Listen to Look model on the validation dataset', 'run the validate function to compute accuracy and mAP metrics on a validation data loader', 'run the main function to build the model, load a checkpoint, and validate against test data', 'review the validate function that computes avgpool, LSTM, and GT prediction accuracy and mAP metrics', 'review the main function that sets up the model, checkpointer, validation dataset, and runs validation']
```

Usage

```
{'run_train_epoch': 'run one training epoch with a model, data loader, optimizer, and loss criterion', 'review_train_epoch': 'review the train_epoch function that computes avgpool and LSTM cross-entropy losses per batch', 'refactor_train_epoch': 'refactor train_epoch to support additional loss types beyond avgpool and LSTM cross-entropy', 'summarize_train_epoch': 'summarize the train_epoch function that logs accuracy and loss metrics via TensorBoard writer', 'test_train_epoch': 'test the train_epoch function with a mock data loader and model returning predictions'}
```

## File: facebookresearch_listen-to-look/listen_to_look_single_modality/validate.py

Prompts

```
['create a training dataset with AudioVisualDataset and feature_collate_train collate function from args', 'create a validation dataset with AudioVisualDataset and feature_collate_val collate function from args', 'review the AudioVisualDataset class that loads video features and labels from a pickle file', 'refactor the feature_collate_train function to customize max_length or episode_length padding behavior', 'summarize the feature_collate_val function that pads and masks validation batch tensors', 'run get_parameters to parse command line arguments for deep learning training configuration', 'build an argparse parser with dataset model and training parameters for deep learning', 'create a training configuration with batch size learning rate and epoch settings', 'configure pretrained model weights and checkpoint paths for model loading', 'set train and test dataset file paths for pickle dataset loading', 'run one training epoch with a model, data loader, optimizer, and loss criterion', 'review the train_epoch function that computes avgpool and LSTM cross-entropy losses per batch', 'refactor train_epoch to support additional loss types beyond avgpool and LSTM cross-entropy', 'summarize the train_epoch function that logs accuracy and loss metrics via TensorBoard writer', 'test the train_epoch function with a mock data loader and model returning predictions', 'run the validation script to evaluate a pretrained Listen to Look model on the validation dataset', 'run the validate function to compute accuracy and mAP metrics on a validation data loader', 'run the main function to build the model, load a checkpoint, and validate against test data', 'review the validate function that computes avgpool, LSTM, and GT prediction accuracy and mAP metrics', 'review the main function that sets up the model, checkpointer, validation dataset, and runs validation']
```

Usage

```
{'run_validate': 'run the validation script to evaluate a pretrained Listen to Look model on the validation dataset', 'run_validate_function': 'run the validate function to compute accuracy and mAP metrics on a validation data loader', 'run_main': 'run the main function to build the model, load a checkpoint, and validate against test data', 'review_validate_function': 'review the validate function that computes avgpool, LSTM, and GT prediction accuracy and mAP metrics', 'review_main_function': 'review the main function that sets up the model, checkpointer, validation dataset, and runs validation'}
```


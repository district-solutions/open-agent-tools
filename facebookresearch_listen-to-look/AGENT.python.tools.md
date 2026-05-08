# Agent Python Tools

- repo: facebookresearch/listen-to-look
- repo_uri: https://github.com/facebookresearch/listen-to-look

## File: facebookresearch_listen-to-look/data.py

Prompts

```
['create an AudioVisualDataset instance from a pickle file containing feature paths and labels', 'create a training dataset with the feature_collate_train collate function for audio-visual data loading', 'create a validation dataset with the feature_collate_val collate function for audio-visual data loading', 'review the feature_collate_train function that pads and processes batches with random max clip length', 'review the feature_collate_val function that pads and processes batches using full video length', 'run get_parameters to parse command line args for deep learning training configuration', 'build an argparse parser with dataset model and training parameters for deep learning', 'configure train and test dataset file paths via the argparse parser arguments', 'set LSTM hidden size episode length and loss weights via command line arguments', 'configure epochs batch size learning rate momentum and weight decay for training', 'run one training epoch on a model with image and audio features using cross-entropy loss', 'review the train_epoch function that processes batches of image and audio features with an LSTM model', 'refactor the train_epoch function to support dynamic loss weighting between avgpool and LSTM cross-entropy losses', 'test the train_epoch function checkpoint saving logic that saves model weights at specified epoch intervals', 'summarize the train_epoch function metric tracking including accuracy, loss, batch time, and learning rate logging', 'run validation on a pretrained audio visual model using the validate script', 'validate a model and compute avgpool and lstm accuracy metrics on a dataset', 'validate a model and compute mean average precision for video classification', 'load a pretrained model checkpoint using the Checkpointer utility for validation', 'build an audio preview LSTM model using ModelBuilder for image audio classification']
```

Usage

```
{'create_audiovisual_dataset': 'create an AudioVisualDataset instance from a pickle file containing feature paths and labels', 'create_training_dataset': 'create a training dataset with the feature_collate_train collate function for audio-visual data loading', 'create_validation_dataset': 'create a validation dataset with the feature_collate_val collate function for audio-visual data loading', 'review_feature_collate_train': 'review the feature_collate_train function that pads and processes batches with random max clip length', 'review_feature_collate_val': 'review the feature_collate_val function that pads and processes batches using full video length'}
```

## File: facebookresearch_listen-to-look/opts.py

Prompts

```
['create an AudioVisualDataset instance from a pickle file containing feature paths and labels', 'create a training dataset with the feature_collate_train collate function for audio-visual data loading', 'create a validation dataset with the feature_collate_val collate function for audio-visual data loading', 'review the feature_collate_train function that pads and processes batches with random max clip length', 'review the feature_collate_val function that pads and processes batches using full video length', 'run get_parameters to parse command line args for deep learning training configuration', 'build an argparse parser with dataset model and training parameters for deep learning', 'configure train and test dataset file paths via the argparse parser arguments', 'set LSTM hidden size episode length and loss weights via command line arguments', 'configure epochs batch size learning rate momentum and weight decay for training', 'run one training epoch on a model with image and audio features using cross-entropy loss', 'review the train_epoch function that processes batches of image and audio features with an LSTM model', 'refactor the train_epoch function to support dynamic loss weighting between avgpool and LSTM cross-entropy losses', 'test the train_epoch function checkpoint saving logic that saves model weights at specified epoch intervals', 'summarize the train_epoch function metric tracking including accuracy, loss, batch time, and learning rate logging', 'run validation on a pretrained audio visual model using the validate script', 'validate a model and compute avgpool and lstm accuracy metrics on a dataset', 'validate a model and compute mean average precision for video classification', 'load a pretrained model checkpoint using the Checkpointer utility for validation', 'build an audio preview LSTM model using ModelBuilder for image audio classification']
```

Usage

```
{'run_get_parameters': 'run get_parameters to parse command line args for deep learning training configuration', 'build_argparse_parser_dl': 'build an argparse parser with dataset model and training parameters for deep learning', 'configure_dataset_paths': 'configure train and test dataset file paths via the argparse parser arguments', 'set_model_hyperparameters': 'set LSTM hidden size episode length and loss weights via command line arguments', 'configure_training_schedule': 'configure epochs batch size learning rate momentum and weight decay for training'}
```

## File: facebookresearch_listen-to-look/train.py

Prompts

```
['create an AudioVisualDataset instance from a pickle file containing feature paths and labels', 'create a training dataset with the feature_collate_train collate function for audio-visual data loading', 'create a validation dataset with the feature_collate_val collate function for audio-visual data loading', 'review the feature_collate_train function that pads and processes batches with random max clip length', 'review the feature_collate_val function that pads and processes batches using full video length', 'run get_parameters to parse command line args for deep learning training configuration', 'build an argparse parser with dataset model and training parameters for deep learning', 'configure train and test dataset file paths via the argparse parser arguments', 'set LSTM hidden size episode length and loss weights via command line arguments', 'configure epochs batch size learning rate momentum and weight decay for training', 'run one training epoch on a model with image and audio features using cross-entropy loss', 'review the train_epoch function that processes batches of image and audio features with an LSTM model', 'refactor the train_epoch function to support dynamic loss weighting between avgpool and LSTM cross-entropy losses', 'test the train_epoch function checkpoint saving logic that saves model weights at specified epoch intervals', 'summarize the train_epoch function metric tracking including accuracy, loss, batch time, and learning rate logging', 'run validation on a pretrained audio visual model using the validate script', 'validate a model and compute avgpool and lstm accuracy metrics on a dataset', 'validate a model and compute mean average precision for video classification', 'load a pretrained model checkpoint using the Checkpointer utility for validation', 'build an audio preview LSTM model using ModelBuilder for image audio classification']
```

Usage

```
{'run_train_epoch': 'run one training epoch on a model with image and audio features using cross-entropy loss', 'review_train_epoch': 'review the train_epoch function that processes batches of image and audio features with an LSTM model', 'refactor_train_epoch_loss_weights': 'refactor the train_epoch function to support dynamic loss weighting between avgpool and LSTM cross-entropy losses', 'test_train_epoch_checkpointing': 'test the train_epoch function checkpoint saving logic that saves model weights at specified epoch intervals', 'summarize_train_epoch_metrics': 'summarize the train_epoch function metric tracking including accuracy, loss, batch time, and learning rate logging'}
```

## File: facebookresearch_listen-to-look/validate.py

Prompts

```
['create an AudioVisualDataset instance from a pickle file containing feature paths and labels', 'create a training dataset with the feature_collate_train collate function for audio-visual data loading', 'create a validation dataset with the feature_collate_val collate function for audio-visual data loading', 'review the feature_collate_train function that pads and processes batches with random max clip length', 'review the feature_collate_val function that pads and processes batches using full video length', 'run get_parameters to parse command line args for deep learning training configuration', 'build an argparse parser with dataset model and training parameters for deep learning', 'configure train and test dataset file paths via the argparse parser arguments', 'set LSTM hidden size episode length and loss weights via command line arguments', 'configure epochs batch size learning rate momentum and weight decay for training', 'run one training epoch on a model with image and audio features using cross-entropy loss', 'review the train_epoch function that processes batches of image and audio features with an LSTM model', 'refactor the train_epoch function to support dynamic loss weighting between avgpool and LSTM cross-entropy losses', 'test the train_epoch function checkpoint saving logic that saves model weights at specified epoch intervals', 'summarize the train_epoch function metric tracking including accuracy, loss, batch time, and learning rate logging', 'run validation on a pretrained audio visual model using the validate script', 'validate a model and compute avgpool and lstm accuracy metrics on a dataset', 'validate a model and compute mean average precision for video classification', 'load a pretrained model checkpoint using the Checkpointer utility for validation', 'build an audio preview LSTM model using ModelBuilder for image audio classification']
```

Usage

```
{'run_validate': 'run validation on a pretrained audio visual model using the validate script', 'validate_model_accuracy': 'validate a model and compute avgpool and lstm accuracy metrics on a dataset', 'validate_model_mAP': 'validate a model and compute mean average precision for video classification', 'load_pretrained_model': 'load a pretrained model checkpoint using the Checkpointer utility for validation', 'build_audio_visual_lstm': 'build an audio preview LSTM model using ModelBuilder for image audio classification'}
```


# Agent Python Tools

- repo: facebookresearch/memvit
- repo_uri: https://github.com/facebookresearch/memvit

## File: facebookresearch_memvit/tools/test_net.py

Prompts

```
['run multi-view testing on a pretrained video classification model with config', 'run the test loop over a video test loader with model and test meter', 'test a video detection model using fully-convolutional testing on full frames', 'test frame-level video predictions with start and stop frame metadata', 'save video classification predictions and labels to a pickle file', 'run the train function to train a video classification model for multiple epochs with checkpointing and evaluation', 'run the train_epoch function to perform one epoch of video model training with mixed precision and mixup support', 'run the eval_epoch function to evaluate the video model on a validation dataset and log metrics', 'run the build_trainer function to construct the model, optimizer, dataloaders, and meters from a config', 'run the mask_tail function to suppress tail action predictions using Bernoulli sampling with a beta parameter']
```

Usage

```
{'run_test_video_model': 'run multi-view testing on a pretrained video classification model with config', 'run_perform_test': 'run the test loop over a video test loader with model and test meter', 'test_detection_model': 'test a video detection model using fully-convolutional testing on full frames', 'test_frame_level_predictions': 'test frame-level video predictions with start and stop frame metadata', 'save_test_predictions': 'save video classification predictions and labels to a pickle file'}
```

## File: facebookresearch_memvit/tools/train_net.py

Prompts

```
['run multi-view testing on a pretrained video classification model with config', 'run the test loop over a video test loader with model and test meter', 'test a video detection model using fully-convolutional testing on full frames', 'test frame-level video predictions with start and stop frame metadata', 'save video classification predictions and labels to a pickle file', 'run the train function to train a video classification model for multiple epochs with checkpointing and evaluation', 'run the train_epoch function to perform one epoch of video model training with mixed precision and mixup support', 'run the eval_epoch function to evaluate the video model on a validation dataset and log metrics', 'run the build_trainer function to construct the model, optimizer, dataloaders, and meters from a config', 'run the mask_tail function to suppress tail action predictions using Bernoulli sampling with a beta parameter']
```

Usage

```
{'train_video_model': 'run the train function to train a video classification model for multiple epochs with checkpointing and evaluation', 'train_one_epoch': 'run the train_epoch function to perform one epoch of video model training with mixed precision and mixup support', 'evaluate_model': 'run the eval_epoch function to evaluate the video model on a validation dataset and log metrics', 'build_trainer_components': 'run the build_trainer function to construct the model, optimizer, dataloaders, and meters from a config', 'mask_tail_predictions': 'run the mask_tail function to suppress tail action predictions using Bernoulli sampling with a beta parameter'}
```


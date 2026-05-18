# Agent Python Tools

- repo: facebookresearch/motionformer
- repo_uri: https://github.com/facebookresearch/motionformer

## File: facebookresearch_motionformer/tools/test_net.py

Prompts

```
['run multi-view testing on a pretrained SlowFast video classification model using a config file', 'run the perform_test function to evaluate a model on a test loader with multi-view ensemble', 'test a pretrained video model on a dataset with temporal and spatial multi-view sampling', 'test a model on the EpicKitchens dataset and save verb and noun prediction scores to pickle', 'test a fully-convolutional detection model on full frames without cropping using AVAMeter', 'run the train function to train a SlowFast video classification model for multiple epochs with config', 'run train_epoch to perform one epoch of video model training with optimizer and loss function', 'run eval_epoch to evaluate the video model on a validation dataset and log metrics', 'build a trainer with model, optimizer, data loaders, and meters from a SlowFast config', 'run calculate_and_update_precise_bn to update batch normalization stats using precise statistics from training data']
```

Usage

```
{'run_test': 'run multi-view testing on a pretrained SlowFast video classification model using a config file', 'run_perform_test': 'run the perform_test function to evaluate a model on a test loader with multi-view ensemble', 'test_video_model': 'test a pretrained video model on a dataset with temporal and spatial multi-view sampling', 'test_epickitchens': 'test a model on the EpicKitchens dataset and save verb and noun prediction scores to pickle', 'test_detection_model': 'test a fully-convolutional detection model on full frames without cropping using AVAMeter'}
```

## File: facebookresearch_motionformer/tools/train_net.py

Prompts

```
['run multi-view testing on a pretrained SlowFast video classification model using a config file', 'run the perform_test function to evaluate a model on a test loader with multi-view ensemble', 'test a pretrained video model on a dataset with temporal and spatial multi-view sampling', 'test a model on the EpicKitchens dataset and save verb and noun prediction scores to pickle', 'test a fully-convolutional detection model on full frames without cropping using AVAMeter', 'run the train function to train a SlowFast video classification model for multiple epochs with config', 'run train_epoch to perform one epoch of video model training with optimizer and loss function', 'run eval_epoch to evaluate the video model on a validation dataset and log metrics', 'build a trainer with model, optimizer, data loaders, and meters from a SlowFast config', 'run calculate_and_update_precise_bn to update batch normalization stats using precise statistics from training data']
```

Usage

```
{'run_train': 'run the train function to train a SlowFast video classification model for multiple epochs with config', 'run_train_epoch': 'run train_epoch to perform one epoch of video model training with optimizer and loss function', 'run_eval_epoch': 'run eval_epoch to evaluate the video model on a validation dataset and log metrics', 'build_trainer': 'build a trainer with model, optimizer, data loaders, and meters from a SlowFast config', 'run_precise_bn': 'run calculate_and_update_precise_bn to update batch normalization stats using precise statistics from training data'}
```


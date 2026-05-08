# Agent Python Tools

- repo: facebookresearch/fairselfsupervisionbenchmark
- repo_uri: https://github.com/facebookresearch/fair_self_supervision_benchmark

## File: facebookresearch_fairselfsupervisionbenchmark/tools/extract_features.py

Prompts

```
['run the extract_features script to extract model features from specified blobs and save as numpy arrays', 'run extract_features with a config file to extract features from a self-supervised model for SVM training', 'run extract_features on test data to extract features and labels for image classification transfer tasks', 'review the extract_features function that runs a Caffe2 model in test mode and fetches blob features per device', 'refactor the extract_features function to use a set instead of list for deduplicating image indices', 'run the test_net CLI tool to evaluate a self-supervised model using a config file and checkpoint', 'test a Caffe2 model by loading parameters from a checkpoint file and running inference over a test database', 'generate JSON prediction files for accuracy blobs by running test_net with the generate_json flag enabled', 'build a test model using ModelBuilder with cudnn settings and a data loader for evaluation', 'load a trained model from a params file using checkpoints.load_model_from_params_file before testing', 'run the self-supervision benchmark training loop with a config file and optional override options', 'resume training from a checkpoint by passing a params file via the config or opts', 'run training with periodic test model evaluation enabled via the TEST_MODEL config flag', 'build a training or test model, create its net, start the data loader, and return metrics', 'review the train_net function to understand the training loop, checkpointing, and evaluation logic']
```

Usage

```
{'run_extract_features': 'run the extract_features script to extract model features from specified blobs and save as numpy arrays', 'run_extract_features_with_config': 'run extract_features with a config file to extract features from a self-supervised model for SVM training', 'run_extract_features_test_data': 'run extract_features on test data to extract features and labels for image classification transfer tasks', 'review_extract_features_function': 'review the extract_features function that runs a Caffe2 model in test mode and fetches blob features per device', 'refactor_extract_features_dedup': 'refactor the extract_features function to use a set instead of list for deduplicating image indices'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/tools/test_net.py

Prompts

```
['run the extract_features script to extract model features from specified blobs and save as numpy arrays', 'run extract_features with a config file to extract features from a self-supervised model for SVM training', 'run extract_features on test data to extract features and labels for image classification transfer tasks', 'review the extract_features function that runs a Caffe2 model in test mode and fetches blob features per device', 'refactor the extract_features function to use a set instead of list for deduplicating image indices', 'run the test_net CLI tool to evaluate a self-supervised model using a config file and checkpoint', 'test a Caffe2 model by loading parameters from a checkpoint file and running inference over a test database', 'generate JSON prediction files for accuracy blobs by running test_net with the generate_json flag enabled', 'build a test model using ModelBuilder with cudnn settings and a data loader for evaluation', 'load a trained model from a params file using checkpoints.load_model_from_params_file before testing', 'run the self-supervision benchmark training loop with a config file and optional override options', 'resume training from a checkpoint by passing a params file via the config or opts', 'run training with periodic test model evaluation enabled via the TEST_MODEL config flag', 'build a training or test model, create its net, start the data loader, and return metrics', 'review the train_net function to understand the training loop, checkpointing, and evaluation logic']
```

Usage

```
{'run_test_net_cli': 'run the test_net CLI tool to evaluate a self-supervised model using a config file and checkpoint', 'test_model_with_checkpoints': 'test a Caffe2 model by loading parameters from a checkpoint file and running inference over a test database', 'generate_json_predictions': 'generate JSON prediction files for accuracy blobs by running test_net with the generate_json flag enabled', 'build_test_model': 'build a test model using ModelBuilder with cudnn settings and a data loader for evaluation', 'load_model_from_params': 'load a trained model from a params file using checkpoints.load_model_from_params_file before testing'}
```

## File: facebookresearch_fairselfsupervisionbenchmark/tools/train_net.py

Prompts

```
['run the extract_features script to extract model features from specified blobs and save as numpy arrays', 'run extract_features with a config file to extract features from a self-supervised model for SVM training', 'run extract_features on test data to extract features and labels for image classification transfer tasks', 'review the extract_features function that runs a Caffe2 model in test mode and fetches blob features per device', 'refactor the extract_features function to use a set instead of list for deduplicating image indices', 'run the test_net CLI tool to evaluate a self-supervised model using a config file and checkpoint', 'test a Caffe2 model by loading parameters from a checkpoint file and running inference over a test database', 'generate JSON prediction files for accuracy blobs by running test_net with the generate_json flag enabled', 'build a test model using ModelBuilder with cudnn settings and a data loader for evaluation', 'load a trained model from a params file using checkpoints.load_model_from_params_file before testing', 'run the self-supervision benchmark training loop with a config file and optional override options', 'resume training from a checkpoint by passing a params file via the config or opts', 'run training with periodic test model evaluation enabled via the TEST_MODEL config flag', 'build a training or test model, create its net, start the data loader, and return metrics', 'review the train_net function to understand the training loop, checkpointing, and evaluation logic']
```

Usage

```
{'run_train_net': 'run the self-supervision benchmark training loop with a config file and optional override options', 'run_train_net_resume': 'resume training from a checkpoint by passing a params file via the config or opts', 'run_train_net_test': 'run training with periodic test model evaluation enabled via the TEST_MODEL config flag', 'build_wrapper': 'build a training or test model, create its net, start the data loader, and return metrics', 'review_train_net': 'review the train_net function to understand the training loop, checkpointing, and evaluation logic'}
```


# Agent Python Tools

- repo: facebookresearch/classifier-balancing
- repo_uri: https://github.com/facebookresearch/classifier-balancing

## File: facebookresearch_classifier-balancing/logger.py

Prompts

```
['create a Logger instance with a log directory path to initialize logging files', 'log configuration parameters as a YAML file using the Logger log_cfg method', 'log accuracy metrics as CSV rows using the Logger log_acc method', 'log loss metrics as CSV rows using the Logger log_loss method', 'log model weights as HDF5 datasets per epoch using the Logger log_ws method', 'run the classifier balancing training pipeline using a YAML config file and dataset', 'run the evaluation of a trained model on a test split with open-set support', 'run KNN-based classification testing with configurable feature and distance types', 'update a YAML config dictionary with CLI arguments and optional KNN classifier parameters', 'map a data split name to its training phase name with val-as-train support', 'run the model class train method to train a feature extractor and classifier network over multiple epochs', 'run the model class eval method to evaluate accuracy on validation or test datasets with shot-based breakdowns', 'calculate class centroids from training data features by averaging feature vectors per class label', 'calculate KNN centroids with unnormalized, L2 normalized, and centered L2 normalized variants for KNN classification', 'load a saved model checkpoint including state dict and centroids from a directory path', 'run the tau norm classifier balancing script with argparse to evaluate accuracy across p-norm values', 'run the pnorm function to normalize classifier weights by a given power p', 'run the forward function to compute dot product logits for test features using normalized weights', 'run the cos_similarity function to compute cosine similarity between two feature tensors', 'run the preds2accs function to calculate and print many-shot, median-shot, and low-shot accuracy metrics', 'initialize a PyTorch model with pretrained weights from a checkpoint file path', 'calculate few-shot accuracy metrics split by many, median, and low-shot class thresholds', 'compute entropy from model logits to measure prediction uncertainty for each sample', 'compute sample priority weights using score, entropy, or cross-entropy from logits and labels', 'calculate F1 score for open-set evaluation with unknown class rejection support']
```

Usage

```
{'create_logger': 'create a Logger instance with a log directory path to initialize logging files', 'log_cfg': 'log configuration parameters as a YAML file using the Logger log_cfg method', 'log_acc': 'log accuracy metrics as CSV rows using the Logger log_acc method', 'log_loss': 'log loss metrics as CSV rows using the Logger log_loss method', 'log_ws': 'log model weights as HDF5 datasets per epoch using the Logger log_ws method'}
```

## File: facebookresearch_classifier-balancing/main.py

Prompts

```
['create a Logger instance with a log directory path to initialize logging files', 'log configuration parameters as a YAML file using the Logger log_cfg method', 'log accuracy metrics as CSV rows using the Logger log_acc method', 'log loss metrics as CSV rows using the Logger log_loss method', 'log model weights as HDF5 datasets per epoch using the Logger log_ws method', 'run the classifier balancing training pipeline using a YAML config file and dataset', 'run the evaluation of a trained model on a test split with open-set support', 'run KNN-based classification testing with configurable feature and distance types', 'update a YAML config dictionary with CLI arguments and optional KNN classifier parameters', 'map a data split name to its training phase name with val-as-train support', 'run the model class train method to train a feature extractor and classifier network over multiple epochs', 'run the model class eval method to evaluate accuracy on validation or test datasets with shot-based breakdowns', 'calculate class centroids from training data features by averaging feature vectors per class label', 'calculate KNN centroids with unnormalized, L2 normalized, and centered L2 normalized variants for KNN classification', 'load a saved model checkpoint including state dict and centroids from a directory path', 'run the tau norm classifier balancing script with argparse to evaluate accuracy across p-norm values', 'run the pnorm function to normalize classifier weights by a given power p', 'run the forward function to compute dot product logits for test features using normalized weights', 'run the cos_similarity function to compute cosine similarity between two feature tensors', 'run the preds2accs function to calculate and print many-shot, median-shot, and low-shot accuracy metrics', 'initialize a PyTorch model with pretrained weights from a checkpoint file path', 'calculate few-shot accuracy metrics split by many, median, and low-shot class thresholds', 'compute entropy from model logits to measure prediction uncertainty for each sample', 'compute sample priority weights using score, entropy, or cross-entropy from logits and labels', 'calculate F1 score for open-set evaluation with unknown class rejection support']
```

Usage

```
{'run_training': 'run the classifier balancing training pipeline using a YAML config file and dataset', 'run_evaluation': 'run the evaluation of a trained model on a test split with open-set support', 'run_knn_testing': 'run KNN-based classification testing with configurable feature and distance types', 'update_config': 'update a YAML config dictionary with CLI arguments and optional KNN classifier parameters', 'split2phase': 'map a data split name to its training phase name with val-as-train support'}
```

## File: facebookresearch_classifier-balancing/run_networks.py

Prompts

```
['create a Logger instance with a log directory path to initialize logging files', 'log configuration parameters as a YAML file using the Logger log_cfg method', 'log accuracy metrics as CSV rows using the Logger log_acc method', 'log loss metrics as CSV rows using the Logger log_loss method', 'log model weights as HDF5 datasets per epoch using the Logger log_ws method', 'run the classifier balancing training pipeline using a YAML config file and dataset', 'run the evaluation of a trained model on a test split with open-set support', 'run KNN-based classification testing with configurable feature and distance types', 'update a YAML config dictionary with CLI arguments and optional KNN classifier parameters', 'map a data split name to its training phase name with val-as-train support', 'run the model class train method to train a feature extractor and classifier network over multiple epochs', 'run the model class eval method to evaluate accuracy on validation or test datasets with shot-based breakdowns', 'calculate class centroids from training data features by averaging feature vectors per class label', 'calculate KNN centroids with unnormalized, L2 normalized, and centered L2 normalized variants for KNN classification', 'load a saved model checkpoint including state dict and centroids from a directory path', 'run the tau norm classifier balancing script with argparse to evaluate accuracy across p-norm values', 'run the pnorm function to normalize classifier weights by a given power p', 'run the forward function to compute dot product logits for test features using normalized weights', 'run the cos_similarity function to compute cosine similarity between two feature tensors', 'run the preds2accs function to calculate and print many-shot, median-shot, and low-shot accuracy metrics', 'initialize a PyTorch model with pretrained weights from a checkpoint file path', 'calculate few-shot accuracy metrics split by many, median, and low-shot class thresholds', 'compute entropy from model logits to measure prediction uncertainty for each sample', 'compute sample priority weights using score, entropy, or cross-entropy from logits and labels', 'calculate F1 score for open-set evaluation with unknown class rejection support']
```

Usage

```
{'run_model_training': 'run the model class train method to train a feature extractor and classifier network over multiple epochs', 'run_model_evaluation': 'run the model class eval method to evaluate accuracy on validation or test datasets with shot-based breakdowns', 'calculate_centroids': 'calculate class centroids from training data features by averaging feature vectors per class label', 'calculate_knn_centroids': 'calculate KNN centroids with unnormalized, L2 normalized, and centered L2 normalized variants for KNN classification', 'load_saved_model': 'load a saved model checkpoint including state dict and centroids from a directory path'}
```

## File: facebookresearch_classifier-balancing/tau_norm.py

Prompts

```
['create a Logger instance with a log directory path to initialize logging files', 'log configuration parameters as a YAML file using the Logger log_cfg method', 'log accuracy metrics as CSV rows using the Logger log_acc method', 'log loss metrics as CSV rows using the Logger log_loss method', 'log model weights as HDF5 datasets per epoch using the Logger log_ws method', 'run the classifier balancing training pipeline using a YAML config file and dataset', 'run the evaluation of a trained model on a test split with open-set support', 'run KNN-based classification testing with configurable feature and distance types', 'update a YAML config dictionary with CLI arguments and optional KNN classifier parameters', 'map a data split name to its training phase name with val-as-train support', 'run the model class train method to train a feature extractor and classifier network over multiple epochs', 'run the model class eval method to evaluate accuracy on validation or test datasets with shot-based breakdowns', 'calculate class centroids from training data features by averaging feature vectors per class label', 'calculate KNN centroids with unnormalized, L2 normalized, and centered L2 normalized variants for KNN classification', 'load a saved model checkpoint including state dict and centroids from a directory path', 'run the tau norm classifier balancing script with argparse to evaluate accuracy across p-norm values', 'run the pnorm function to normalize classifier weights by a given power p', 'run the forward function to compute dot product logits for test features using normalized weights', 'run the cos_similarity function to compute cosine similarity between two feature tensors', 'run the preds2accs function to calculate and print many-shot, median-shot, and low-shot accuracy metrics', 'initialize a PyTorch model with pretrained weights from a checkpoint file path', 'calculate few-shot accuracy metrics split by many, median, and low-shot class thresholds', 'compute entropy from model logits to measure prediction uncertainty for each sample', 'compute sample priority weights using score, entropy, or cross-entropy from logits and labels', 'calculate F1 score for open-set evaluation with unknown class rejection support']
```

Usage

```
{'run_tau_norm_evaluation': 'run the tau norm classifier balancing script with argparse to evaluate accuracy across p-norm values', 'run_pnorm_normalization': 'run the pnorm function to normalize classifier weights by a given power p', 'run_forward_inference': 'run the forward function to compute dot product logits for test features using normalized weights', 'run_cos_similarity': 'run the cos_similarity function to compute cosine similarity between two feature tensors', 'run_preds2accs': 'run the preds2accs function to calculate and print many-shot, median-shot, and low-shot accuracy metrics'}
```

## File: facebookresearch_classifier-balancing/utils.py

Prompts

```
['create a Logger instance with a log directory path to initialize logging files', 'log configuration parameters as a YAML file using the Logger log_cfg method', 'log accuracy metrics as CSV rows using the Logger log_acc method', 'log loss metrics as CSV rows using the Logger log_loss method', 'log model weights as HDF5 datasets per epoch using the Logger log_ws method', 'run the classifier balancing training pipeline using a YAML config file and dataset', 'run the evaluation of a trained model on a test split with open-set support', 'run KNN-based classification testing with configurable feature and distance types', 'update a YAML config dictionary with CLI arguments and optional KNN classifier parameters', 'map a data split name to its training phase name with val-as-train support', 'run the model class train method to train a feature extractor and classifier network over multiple epochs', 'run the model class eval method to evaluate accuracy on validation or test datasets with shot-based breakdowns', 'calculate class centroids from training data features by averaging feature vectors per class label', 'calculate KNN centroids with unnormalized, L2 normalized, and centered L2 normalized variants for KNN classification', 'load a saved model checkpoint including state dict and centroids from a directory path', 'run the tau norm classifier balancing script with argparse to evaluate accuracy across p-norm values', 'run the pnorm function to normalize classifier weights by a given power p', 'run the forward function to compute dot product logits for test features using normalized weights', 'run the cos_similarity function to compute cosine similarity between two feature tensors', 'run the preds2accs function to calculate and print many-shot, median-shot, and low-shot accuracy metrics', 'initialize a PyTorch model with pretrained weights from a checkpoint file path', 'calculate few-shot accuracy metrics split by many, median, and low-shot class thresholds', 'compute entropy from model logits to measure prediction uncertainty for each sample', 'compute sample priority weights using score, entropy, or cross-entropy from logits and labels', 'calculate F1 score for open-set evaluation with unknown class rejection support']
```

Usage

```
{'init_weights_model': 'initialize a PyTorch model with pretrained weights from a checkpoint file path', 'shot_acc_few_shot': 'calculate few-shot accuracy metrics split by many, median, and low-shot class thresholds', 'logits2entropy_uncertainty': 'compute entropy from model logits to measure prediction uncertainty for each sample', 'get_priority_sampling': 'compute sample priority weights using score, entropy, or cross-entropy from logits and labels', 'F_measure_openset': 'calculate F1 score for open-set evaluation with unknown class rejection support'}
```


# Agent Python Tools

- repo: facebookresearch/fashionplus
- repo_uri: https://github.com/facebookresearch/fashionplus

## File: facebookresearch_fashionplus/classification/model.py

Prompts

```
['load a PyTorch classifier model from a saved checkpoint file by epoch number', 'save a PyTorch classifier model state dict to a checkpoint file for the current epoch', 'get the latest classifier model filename from a directory matching a given key', 'evaluate classification accuracy by comparing predicted labels against ground truth labels', 'accumulate the count of correctly predicted samples from prediction and label tensors', 'build a multi-layer perceptron network with configurable layers and dropout for fashion classification', 'build a single-layer linear classifier network for binary classification tasks', 'test the MLP forward pass with input tensors and verify output shape', 'test the LinearClassifier forward pass with input tensors and verify output shape', 'review the MLP class to understand layer configuration and dropout usage']
```

Usage

```
{'load_network_resume': 'load a PyTorch classifier model from a saved checkpoint file by epoch number', 'save_network_checkpoint': 'save a PyTorch classifier model state dict to a checkpoint file for the current epoch', 'get_model_list_latest': 'get the latest classifier model filename from a directory matching a given key', 'evaluate_acc_accuracy': 'evaluate classification accuracy by comparing predicted labels against ground truth labels', 'accumulate_acc_correct': 'accumulate the count of correctly predicted samples from prediction and label tensors'}
```

## File: facebookresearch_fashionplus/classification/search_networks.py

Prompts

```
['load a PyTorch classifier model from a saved checkpoint file by epoch number', 'save a PyTorch classifier model state dict to a checkpoint file for the current epoch', 'get the latest classifier model filename from a directory matching a given key', 'evaluate classification accuracy by comparing predicted labels against ground truth labels', 'accumulate the count of correctly predicted samples from prediction and label tensors', 'build a multi-layer perceptron network with configurable layers and dropout for fashion classification', 'build a single-layer linear classifier network for binary classification tasks', 'test the MLP forward pass with input tensors and verify output shape', 'test the LinearClassifier forward pass with input tensors and verify output shape', 'review the MLP class to understand layer configuration and dropout usage']
```

Usage

```
{'build_MLP_classifier': 'build a multi-layer perceptron network with configurable layers and dropout for fashion classification', 'build_LinearClassifier': 'build a single-layer linear classifier network for binary classification tasks', 'test_MLP_forward': 'test the MLP forward pass with input tensors and verify output shape', 'test_LinearClassifier_forward': 'test the LinearClassifier forward pass with input tensors and verify output shape', 'review_MLP_architecture': 'review the MLP class to understand layer configuration and dropout usage'}
```


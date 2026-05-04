# Agent Python Tools

- repo: facebookresearch/foundpose
- repo_uri: https://github.com/facebookresearch/foundpose

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/models/losses/cross_entropy_loss.py

Prompts

```
['build a CrossEntropyLoss module with configurable reduction and class weights for segmentation', 'create a binary cross entropy loss function with ignore index and avg_non_ignore support', 'test the cross_entropy function with prediction tensors, labels, and sample-wise weights', 'refactor the mask_cross_entropy function to compute BCE loss for ROI mask predictions', 'review the CrossEntropyLoss forward method to understand reduction override and class weight handling', 'build a python module that calculates V-Net dice loss between prediction and target tensors', 'build a python module that calculates naive dice loss with first power denominator', 'create a PyTorch DiceLoss module with sigmoid activation and configurable reduction strategy', 'test the dice_loss function with prediction and target tensors to verify loss calculation', 'review the DiceLoss forward method to understand sigmoid activation and naive dice branching', 'build a ClassificationCost instance to compute softmax-based classification matching costs between predicted logits and ground truth labels', 'build a DiceCost instance to compute dice loss-based mask assignment costs between predicted masks and ground truth masks', 'build a CrossEntropyLossCost instance to compute binary cross entropy matching costs between predicted logits and ground truth labels', 'test the DiceCost binary_mask_dice_loss method to compute dice cost matrix between predicted and ground truth masks', 'test the CrossEntropyLossCost _binary_cross_entropy method to compute cross entropy cost matrix between predictions and labels']
```

Usage

```
{'build_cross_entropy_loss_module': 'build a CrossEntropyLoss module with configurable reduction and class weights for segmentation', 'create_binary_cross_entropy': 'create a binary cross entropy loss function with ignore index and avg_non_ignore support', 'test_cross_entropy_function': 'test the cross_entropy function with prediction tensors, labels, and sample-wise weights', 'refactor_mask_cross_entropy': 'refactor the mask_cross_entropy function to compute BCE loss for ROI mask predictions', 'review_CrossEntropyLoss_forward': 'review the CrossEntropyLoss forward method to understand reduction override and class weight handling'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/models/losses/dice_loss.py

Prompts

```
['build a CrossEntropyLoss module with configurable reduction and class weights for segmentation', 'create a binary cross entropy loss function with ignore index and avg_non_ignore support', 'test the cross_entropy function with prediction tensors, labels, and sample-wise weights', 'refactor the mask_cross_entropy function to compute BCE loss for ROI mask predictions', 'review the CrossEntropyLoss forward method to understand reduction override and class weight handling', 'build a python module that calculates V-Net dice loss between prediction and target tensors', 'build a python module that calculates naive dice loss with first power denominator', 'create a PyTorch DiceLoss module with sigmoid activation and configurable reduction strategy', 'test the dice_loss function with prediction and target tensors to verify loss calculation', 'review the DiceLoss forward method to understand sigmoid activation and naive dice branching', 'build a ClassificationCost instance to compute softmax-based classification matching costs between predicted logits and ground truth labels', 'build a DiceCost instance to compute dice loss-based mask assignment costs between predicted masks and ground truth masks', 'build a CrossEntropyLossCost instance to compute binary cross entropy matching costs between predicted logits and ground truth labels', 'test the DiceCost binary_mask_dice_loss method to compute dice cost matrix between predicted and ground truth masks', 'test the CrossEntropyLossCost _binary_cross_entropy method to compute cross entropy cost matrix between predictions and labels']
```

Usage

```
{'build_dice_loss_module': 'build a python module that calculates V-Net dice loss between prediction and target tensors', 'build_naive_dice_loss_module': 'build a python module that calculates naive dice loss with first power denominator', 'create_DiceLoss_class': 'create a PyTorch DiceLoss module with sigmoid activation and configurable reduction strategy', 'test_dice_loss_function': 'test the dice_loss function with prediction and target tensors to verify loss calculation', 'review_DiceLoss_forward': 'review the DiceLoss forward method to understand sigmoid activation and naive dice branching'}
```

## File: facebookresearch_foundpose/external/dinov2/dinov2/eval/segmentation_m2f/models/losses/match_costs.py

Prompts

```
['build a CrossEntropyLoss module with configurable reduction and class weights for segmentation', 'create a binary cross entropy loss function with ignore index and avg_non_ignore support', 'test the cross_entropy function with prediction tensors, labels, and sample-wise weights', 'refactor the mask_cross_entropy function to compute BCE loss for ROI mask predictions', 'review the CrossEntropyLoss forward method to understand reduction override and class weight handling', 'build a python module that calculates V-Net dice loss between prediction and target tensors', 'build a python module that calculates naive dice loss with first power denominator', 'create a PyTorch DiceLoss module with sigmoid activation and configurable reduction strategy', 'test the dice_loss function with prediction and target tensors to verify loss calculation', 'review the DiceLoss forward method to understand sigmoid activation and naive dice branching', 'build a ClassificationCost instance to compute softmax-based classification matching costs between predicted logits and ground truth labels', 'build a DiceCost instance to compute dice loss-based mask assignment costs between predicted masks and ground truth masks', 'build a CrossEntropyLossCost instance to compute binary cross entropy matching costs between predicted logits and ground truth labels', 'test the DiceCost binary_mask_dice_loss method to compute dice cost matrix between predicted and ground truth masks', 'test the CrossEntropyLossCost _binary_cross_entropy method to compute cross entropy cost matrix between predictions and labels']
```

Usage

```
{'build_classification_cost': 'build a ClassificationCost instance to compute softmax-based classification matching costs between predicted logits and ground truth labels', 'build_dice_cost': 'build a DiceCost instance to compute dice loss-based mask assignment costs between predicted masks and ground truth masks', 'build_cross_entropy_loss_cost': 'build a CrossEntropyLossCost instance to compute binary cross entropy matching costs between predicted logits and ground truth labels', 'test_binary_mask_dice_loss': 'test the DiceCost binary_mask_dice_loss method to compute dice cost matrix between predicted and ground truth masks', 'test_binary_cross_entropy': 'test the CrossEntropyLossCost _binary_cross_entropy method to compute cross entropy cost matrix between predictions and labels'}
```


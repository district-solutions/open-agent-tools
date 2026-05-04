# Agent Python Tools

- repo: facebookresearch/dinov2
- repo_uri: https://github.com/facebookresearch/dinov2.git

## File: facebookresearch_dinov2/dinov2/eval/cell_dino/knn.py

Prompts

```
['run k-NN classification evaluation on a DINOv2 model with specified train and validation datasets', 'evaluate k-NN classification using leave-one-out strategy for CHAMMI_CP task 3 and CHAMMI_HPA task 4', 'evaluate k-NN classification on a model with optional bag-of-channels strategy and leave-one-out support', 'evaluate k-NN classification on train and test datasets with configurable k values and temperature', 'create a train dataset dictionary using leave-one-out method combining train and test datasets', 'run the DINOv2 linear evaluation script for cell DINO classification with argparse CLI', 'train linear classifiers on frozen DINOv2 features with AdamW optimizer and grid search over learning rates', 'evaluate a DINOv2 model with linear probing on cell biology datasets including leave-one-out strategy', 'create concatenated feature input from intermediate transformer blocks with optional average pooling and bag of channels', 'setup multiple linear classifiers with grid search over learning rates and weight decays for DDP training', 'extract features from a DINOv2 model on a dataset using distributed data loading and gather results', 'evaluate a model on a data loader with postprocessors metrics and optional result accumulation', 'create a dictionary of dataset subsets for few-shot evaluation with configurable k or percentage per class', 'split a training dataset into train and validation subsets with stratified class-wise sampling', 'compute k-nearest neighbor classification probabilities on test features using distributed training feature chunks']
```

Usage

```
{'run_knn_evaluation': 'run k-NN classification evaluation on a DINOv2 model with specified train and validation datasets', 'eval_knn_with_leave_one_out': 'evaluate k-NN classification using leave-one-out strategy for CHAMMI_CP task 3 and CHAMMI_HPA task 4', 'eval_knn_with_model': 'evaluate k-NN classification on a model with optional bag-of-channels strategy and leave-one-out support', 'eval_knn': 'evaluate k-NN classification on train and test datasets with configurable k values and temperature', 'create_train_test_dataset_dict_leave_one_out': 'create a train dataset dictionary using leave-one-out method combining train and test datasets'}
```

## File: facebookresearch_dinov2/dinov2/eval/cell_dino/linear.py

Prompts

```
['run k-NN classification evaluation on a DINOv2 model with specified train and validation datasets', 'evaluate k-NN classification using leave-one-out strategy for CHAMMI_CP task 3 and CHAMMI_HPA task 4', 'evaluate k-NN classification on a model with optional bag-of-channels strategy and leave-one-out support', 'evaluate k-NN classification on train and test datasets with configurable k values and temperature', 'create a train dataset dictionary using leave-one-out method combining train and test datasets', 'run the DINOv2 linear evaluation script for cell DINO classification with argparse CLI', 'train linear classifiers on frozen DINOv2 features with AdamW optimizer and grid search over learning rates', 'evaluate a DINOv2 model with linear probing on cell biology datasets including leave-one-out strategy', 'create concatenated feature input from intermediate transformer blocks with optional average pooling and bag of channels', 'setup multiple linear classifiers with grid search over learning rates and weight decays for DDP training', 'extract features from a DINOv2 model on a dataset using distributed data loading and gather results', 'evaluate a model on a data loader with postprocessors metrics and optional result accumulation', 'create a dictionary of dataset subsets for few-shot evaluation with configurable k or percentage per class', 'split a training dataset into train and validation subsets with stratified class-wise sampling', 'compute k-nearest neighbor classification probabilities on test features using distributed training feature chunks']
```

Usage

```
{'run_linear_eval_cell_dino': 'run the DINOv2 linear evaluation script for cell DINO classification with argparse CLI', 'train_linear_classifiers': 'train linear classifiers on frozen DINOv2 features with AdamW optimizer and grid search over learning rates', 'eval_linear_with_model': 'evaluate a DINOv2 model with linear probing on cell biology datasets including leave-one-out strategy', 'create_linear_input': 'create concatenated feature input from intermediate transformer blocks with optional average pooling and bag of channels', 'setup_linear_classifiers': 'setup multiple linear classifiers with grid search over learning rates and weight decays for DDP training'}
```

## File: facebookresearch_dinov2/dinov2/eval/cell_dino/utils.py

Prompts

```
['run k-NN classification evaluation on a DINOv2 model with specified train and validation datasets', 'evaluate k-NN classification using leave-one-out strategy for CHAMMI_CP task 3 and CHAMMI_HPA task 4', 'evaluate k-NN classification on a model with optional bag-of-channels strategy and leave-one-out support', 'evaluate k-NN classification on train and test datasets with configurable k values and temperature', 'create a train dataset dictionary using leave-one-out method combining train and test datasets', 'run the DINOv2 linear evaluation script for cell DINO classification with argparse CLI', 'train linear classifiers on frozen DINOv2 features with AdamW optimizer and grid search over learning rates', 'evaluate a DINOv2 model with linear probing on cell biology datasets including leave-one-out strategy', 'create concatenated feature input from intermediate transformer blocks with optional average pooling and bag of channels', 'setup multiple linear classifiers with grid search over learning rates and weight decays for DDP training', 'extract features from a DINOv2 model on a dataset using distributed data loading and gather results', 'evaluate a model on a data loader with postprocessors metrics and optional result accumulation', 'create a dictionary of dataset subsets for few-shot evaluation with configurable k or percentage per class', 'split a training dataset into train and validation subsets with stratified class-wise sampling', 'compute k-nearest neighbor classification probabilities on test features using distributed training feature chunks']
```

Usage

```
{'extract_features_cell_dino': 'extract features from a DINOv2 model on a dataset using distributed data loading and gather results', 'evaluate_with_accumulate': 'evaluate a model on a data loader with postprocessors metrics and optional result accumulation', 'create_train_dataset_dict': 'create a dictionary of dataset subsets for few-shot evaluation with configurable k or percentage per class', 'split_train_val_datasets': 'split a training dataset into train and validation subsets with stratified class-wise sampling', 'knn_module_forward': 'compute k-nearest neighbor classification probabilities on test features using distributed training feature chunks'}
```


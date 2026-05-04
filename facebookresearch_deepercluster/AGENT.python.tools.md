# Agent Python Tools

- repo: facebookresearch/deepercluster
- repo_uri: https://github.com/facebookresearch/deepercluster

## File: facebookresearch_deepercluster/eval_linear.py

Prompts

```
['run a linear classifier training on a frozen conv layer using a pretrained model and dataset', 'run k-fold cross validation for linear classifier training on a supervised dataset', 'build a logistic regression module on top of frozen convolutional features with average pooling', 'run evaluation on the PASCAL VOC2007 dataset using average precision score metrics', 'run inverse square root learning rate decay on an SGD optimizer during training', 'run the eval_pretrain script to evaluate a pretrained model on ImageNet validation set', 'run the train_network function to train a model on a dataset with cross entropy loss', 'run the adjust_learning_rate function to decay the learning rate every 30 epochs', 'run the get_parser function to generate an argparse parser with training and model parameters', 'run the main function to initialize distributed training, load data, and start supervised training', 'run the PASCAL VOC 2007 classification training with a pretrained model and SGD optimizer', 'evaluate a trained model on PASCAL VOC 2007 train and test splits using random or fixed crops', 'run one epoch of training on a data loader with BCEWithLogitsLoss and gradient clipping', 'run evaluation on a data loader computing average precision scores for 20 VOC classes', 'run the main entry point to train and evaluate a DeeperCluster model on PASCAL VOC 2007', 'run the DeeperCluster unsupervised feature learning training loop with hierarchical clustering and rotation prediction', 'get the argparse parser with all DeeperCluster training parameters like learning rate, batch size, and cluster count', 'initialize distributed training communication groups for multi-GPU DeeperCluster training', 'build a prediction layer for super-class or sub-class cluster assignment classification', 'extract features from the dataset and perform k-means clustering to get cluster assignments']
```

Usage

```
{'run_linear_classifier_training': 'run a linear classifier training on a frozen conv layer using a pretrained model and dataset', 'run_kfold_cross_validation': 'run k-fold cross validation for linear classifier training on a supervised dataset', 'build_RegLog_module': 'build a logistic regression module on top of frozen convolutional features with average pooling', 'run_PASCAL_evaluation': 'run evaluation on the PASCAL VOC2007 dataset using average precision score metrics', 'run_learning_rate_decay': 'run inverse square root learning rate decay on an SGD optimizer during training'}
```

## File: facebookresearch_deepercluster/eval_pretrain.py

Prompts

```
['run a linear classifier training on a frozen conv layer using a pretrained model and dataset', 'run k-fold cross validation for linear classifier training on a supervised dataset', 'build a logistic regression module on top of frozen convolutional features with average pooling', 'run evaluation on the PASCAL VOC2007 dataset using average precision score metrics', 'run inverse square root learning rate decay on an SGD optimizer during training', 'run the eval_pretrain script to evaluate a pretrained model on ImageNet validation set', 'run the train_network function to train a model on a dataset with cross entropy loss', 'run the adjust_learning_rate function to decay the learning rate every 30 epochs', 'run the get_parser function to generate an argparse parser with training and model parameters', 'run the main function to initialize distributed training, load data, and start supervised training', 'run the PASCAL VOC 2007 classification training with a pretrained model and SGD optimizer', 'evaluate a trained model on PASCAL VOC 2007 train and test splits using random or fixed crops', 'run one epoch of training on a data loader with BCEWithLogitsLoss and gradient clipping', 'run evaluation on a data loader computing average precision scores for 20 VOC classes', 'run the main entry point to train and evaluate a DeeperCluster model on PASCAL VOC 2007', 'run the DeeperCluster unsupervised feature learning training loop with hierarchical clustering and rotation prediction', 'get the argparse parser with all DeeperCluster training parameters like learning rate, batch size, and cluster count', 'initialize distributed training communication groups for multi-GPU DeeperCluster training', 'build a prediction layer for super-class or sub-class cluster assignment classification', 'extract features from the dataset and perform k-means clustering to get cluster assignments']
```

Usage

```
{'run_eval_pretrain': 'run the eval_pretrain script to evaluate a pretrained model on ImageNet validation set', 'run_train_network': 'run the train_network function to train a model on a dataset with cross entropy loss', 'run_adjust_learning_rate': 'run the adjust_learning_rate function to decay the learning rate every 30 epochs', 'run_get_parser': 'run the get_parser function to generate an argparse parser with training and model parameters', 'run_main': 'run the main function to initialize distributed training, load data, and start supervised training'}
```

## File: facebookresearch_deepercluster/eval_voc_classif.py

Prompts

```
['run a linear classifier training on a frozen conv layer using a pretrained model and dataset', 'run k-fold cross validation for linear classifier training on a supervised dataset', 'build a logistic regression module on top of frozen convolutional features with average pooling', 'run evaluation on the PASCAL VOC2007 dataset using average precision score metrics', 'run inverse square root learning rate decay on an SGD optimizer during training', 'run the eval_pretrain script to evaluate a pretrained model on ImageNet validation set', 'run the train_network function to train a model on a dataset with cross entropy loss', 'run the adjust_learning_rate function to decay the learning rate every 30 epochs', 'run the get_parser function to generate an argparse parser with training and model parameters', 'run the main function to initialize distributed training, load data, and start supervised training', 'run the PASCAL VOC 2007 classification training with a pretrained model and SGD optimizer', 'evaluate a trained model on PASCAL VOC 2007 train and test splits using random or fixed crops', 'run one epoch of training on a data loader with BCEWithLogitsLoss and gradient clipping', 'run evaluation on a data loader computing average precision scores for 20 VOC classes', 'run the main entry point to train and evaluate a DeeperCluster model on PASCAL VOC 2007', 'run the DeeperCluster unsupervised feature learning training loop with hierarchical clustering and rotation prediction', 'get the argparse parser with all DeeperCluster training parameters like learning rate, batch size, and cluster count', 'initialize distributed training communication groups for multi-GPU DeeperCluster training', 'build a prediction layer for super-class or sub-class cluster assignment classification', 'extract features from the dataset and perform k-means clustering to get cluster assignments']
```

Usage

```
{'run_VOC_classification_training': 'run the PASCAL VOC 2007 classification training with a pretrained model and SGD optimizer', 'run_evaluate_model': 'evaluate a trained model on PASCAL VOC 2007 train and test splits using random or fixed crops', 'run_train_function': 'run one epoch of training on a data loader with BCEWithLogitsLoss and gradient clipping', 'run_evaluate_function': 'run evaluation on a data loader computing average precision scores for 20 VOC classes', 'run_main_entry': 'run the main entry point to train and evaluate a DeeperCluster model on PASCAL VOC 2007'}
```

## File: facebookresearch_deepercluster/main.py

Prompts

```
['run a linear classifier training on a frozen conv layer using a pretrained model and dataset', 'run k-fold cross validation for linear classifier training on a supervised dataset', 'build a logistic regression module on top of frozen convolutional features with average pooling', 'run evaluation on the PASCAL VOC2007 dataset using average precision score metrics', 'run inverse square root learning rate decay on an SGD optimizer during training', 'run the eval_pretrain script to evaluate a pretrained model on ImageNet validation set', 'run the train_network function to train a model on a dataset with cross entropy loss', 'run the adjust_learning_rate function to decay the learning rate every 30 epochs', 'run the get_parser function to generate an argparse parser with training and model parameters', 'run the main function to initialize distributed training, load data, and start supervised training', 'run the PASCAL VOC 2007 classification training with a pretrained model and SGD optimizer', 'evaluate a trained model on PASCAL VOC 2007 train and test splits using random or fixed crops', 'run one epoch of training on a data loader with BCEWithLogitsLoss and gradient clipping', 'run evaluation on a data loader computing average precision scores for 20 VOC classes', 'run the main entry point to train and evaluate a DeeperCluster model on PASCAL VOC 2007', 'run the DeeperCluster unsupervised feature learning training loop with hierarchical clustering and rotation prediction', 'get the argparse parser with all DeeperCluster training parameters like learning rate, batch size, and cluster count', 'initialize distributed training communication groups for multi-GPU DeeperCluster training', 'build a prediction layer for super-class or sub-class cluster assignment classification', 'extract features from the dataset and perform k-means clustering to get cluster assignments']
```

Usage

```
{'run_deepercluster_training': 'run the DeeperCluster unsupervised feature learning training loop with hierarchical clustering and rotation prediction', 'get_parser_args': 'get the argparse parser with all DeeperCluster training parameters like learning rate, batch size, and cluster count', 'init_distributed_mode': 'initialize distributed training communication groups for multi-GPU DeeperCluster training', 'build_prediction_layer': 'build a prediction layer for super-class or sub-class cluster assignment classification', 'get_cluster_assignments': 'extract features from the dataset and perform k-means clustering to get cluster assignments'}
```


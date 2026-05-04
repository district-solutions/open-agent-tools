# Agent Python Tools

- repo: facebookresearch/deepcluster
- repo_uri: https://github.com/facebookresearch/deepcluster

## File: facebookresearch_deepcluster/clustering.py

Prompts

```
['run k-means clustering on feature data using FAISS and return cluster assignments and loss', 'run Power Iteration Clustering on a nearest neighbor graph with Gaussian kernel and alpha damping', 'preprocess feature data with PCA whitening and L2 normalization using FAISS', 'create a PyTorch dataset with cluster pseudolabels from clustering results and image indexes', 'build a nearest neighbor graph from feature data using FAISS GPU index and return indices and distances', 'run the PASCAL VOC 2007 classification training loop with a pretrained model and SGD optimizer', 'run evaluation on PASCAL VOC 2007 train and test sets using random or fixed crops', 'create a PyTorch Dataset for PASCAL VOC 2007 that loads image sets and multi-label annotations', 'train a PyTorch model on PASCAL VOC 2007 with BCE loss, gradient clipping, and learning rate decay', 'evaluate a trained model on PASCAL VOC 2007 and compute average precision for each of the 20 classes', 'load a PyTorch model from a checkpoint file path and return it without DataParallel wrapper', 'create a UnifLabelSampler that samples elements uniformly across pseudolabel clusters for a given N', 'use an AverageMeter to compute and store the running average and current value of metrics', 'apply inverse square root learning rate decay to an optimizer based on step count and initial lr', 'log and persist training results to a pickle file using the Logger class']
```

Usage

```
{'run_kmeans_clustering': 'run k-means clustering on feature data using FAISS and return cluster assignments and loss', 'run_pic_clustering': 'run Power Iteration Clustering on a nearest neighbor graph with Gaussian kernel and alpha damping', 'preprocess_features': 'preprocess feature data with PCA whitening and L2 normalization using FAISS', 'create_reassigned_dataset': 'create a PyTorch dataset with cluster pseudolabels from clustering results and image indexes', 'build_nn_graph': 'build a nearest neighbor graph from feature data using FAISS GPU index and return indices and distances'}
```

## File: facebookresearch_deepcluster/eval_voc_classif.py

Prompts

```
['run k-means clustering on feature data using FAISS and return cluster assignments and loss', 'run Power Iteration Clustering on a nearest neighbor graph with Gaussian kernel and alpha damping', 'preprocess feature data with PCA whitening and L2 normalization using FAISS', 'create a PyTorch dataset with cluster pseudolabels from clustering results and image indexes', 'build a nearest neighbor graph from feature data using FAISS GPU index and return indices and distances', 'run the PASCAL VOC 2007 classification training loop with a pretrained model and SGD optimizer', 'run evaluation on PASCAL VOC 2007 train and test sets using random or fixed crops', 'create a PyTorch Dataset for PASCAL VOC 2007 that loads image sets and multi-label annotations', 'train a PyTorch model on PASCAL VOC 2007 with BCE loss, gradient clipping, and learning rate decay', 'evaluate a trained model on PASCAL VOC 2007 and compute average precision for each of the 20 classes', 'load a PyTorch model from a checkpoint file path and return it without DataParallel wrapper', 'create a UnifLabelSampler that samples elements uniformly across pseudolabel clusters for a given N', 'use an AverageMeter to compute and store the running average and current value of metrics', 'apply inverse square root learning rate decay to an optimizer based on step count and initial lr', 'log and persist training results to a pickle file using the Logger class']
```

Usage

```
{'run_voc_classification_training': 'run the PASCAL VOC 2007 classification training loop with a pretrained model and SGD optimizer', 'run_voc_evaluation': 'run evaluation on PASCAL VOC 2007 train and test sets using random or fixed crops', 'create_voc2007_dataset': 'create a PyTorch Dataset for PASCAL VOC 2007 that loads image sets and multi-label annotations', 'train_voc_model': 'train a PyTorch model on PASCAL VOC 2007 with BCE loss, gradient clipping, and learning rate decay', 'evaluate_voc_model': 'evaluate a trained model on PASCAL VOC 2007 and compute average precision for each of the 20 classes'}
```

## File: facebookresearch_deepcluster/util.py

Prompts

```
['run k-means clustering on feature data using FAISS and return cluster assignments and loss', 'run Power Iteration Clustering on a nearest neighbor graph with Gaussian kernel and alpha damping', 'preprocess feature data with PCA whitening and L2 normalization using FAISS', 'create a PyTorch dataset with cluster pseudolabels from clustering results and image indexes', 'build a nearest neighbor graph from feature data using FAISS GPU index and return indices and distances', 'run the PASCAL VOC 2007 classification training loop with a pretrained model and SGD optimizer', 'run evaluation on PASCAL VOC 2007 train and test sets using random or fixed crops', 'create a PyTorch Dataset for PASCAL VOC 2007 that loads image sets and multi-label annotations', 'train a PyTorch model on PASCAL VOC 2007 with BCE loss, gradient clipping, and learning rate decay', 'evaluate a trained model on PASCAL VOC 2007 and compute average precision for each of the 20 classes', 'load a PyTorch model from a checkpoint file path and return it without DataParallel wrapper', 'create a UnifLabelSampler that samples elements uniformly across pseudolabel clusters for a given N', 'use an AverageMeter to compute and store the running average and current value of metrics', 'apply inverse square root learning rate decay to an optimizer based on step count and initial lr', 'log and persist training results to a pickle file using the Logger class']
```

Usage

```
{'load_model_from_checkpoint': 'load a PyTorch model from a checkpoint file path and return it without DataParallel wrapper', 'create_uniflabel_sampler': 'create a UnifLabelSampler that samples elements uniformly across pseudolabel clusters for a given N', 'use_averagemeter_track_stats': 'use an AverageMeter to compute and store the running average and current value of metrics', 'apply_learning_rate_decay': 'apply inverse square root learning rate decay to an optimizer based on step count and initial lr', 'log_training_results': 'log and persist training results to a pickle file using the Logger class'}
```


# Agent Python Tools

- repo: facebookresearch/dme
- repo_uri: https://github.com/facebookresearch/dme

## File: facebookresearch_dme/get_flickr30k.py

Prompts

```
['run the script to extract ResNet152 image features from the Flickr30K dataset and save pickle files', 'run the normf function to L2 normalize a PyTorch tensor along a specified dimension', 'run get_pil_img to load an image file from disk and convert it to RGB mode', 'review the MyImageFolder class and its getitem method that returns both the image and its file path', 'review the preprocess_1c torchvision transform pipeline that resizes, crops, and normalizes images', 'run the main training loop for NLI, SST2, or Flickr30K tasks with early stopping', 'save a PyTorch model checkpoint with optimizer, scheduler, and early stopper state to disk', 'resume training by loading model, optimizer, scheduler, and early stopper state from a checkpoint file', 'load and split SNLI, MultiNLI, SST2, or Flickr30K datasets into train, dev, and test sets', 'create BucketIterator or DataLoader iterators for train, dev, and test splits by task type', 'create an EarlyStoppingCriterion with configurable patience, min or max mode, and minimum delta threshold', 'review the EarlyStoppingCriterion step method that tracks best score and returns whether training should continue', 'refactor get_data_splits to support additional dataset types beyond SNLI, MultiNLI, SST2, and Flickr30K']
```

Usage

```
{'run_flickr30k_feature_extraction': 'run the script to extract ResNet152 image features from the Flickr30K dataset and save pickle files', 'run_normf_tensor_normalization': 'run the normf function to L2 normalize a PyTorch tensor along a specified dimension', 'run_get_pil_img_loading': 'run get_pil_img to load an image file from disk and convert it to RGB mode', 'review_MyImageFolder_getitem': 'review the MyImageFolder class and its getitem method that returns both the image and its file path', 'review_preprocess_1c_transforms': 'review the preprocess_1c torchvision transform pipeline that resizes, crops, and normalizes images'}
```

## File: facebookresearch_dme/train.py

Prompts

```
['run the script to extract ResNet152 image features from the Flickr30K dataset and save pickle files', 'run the normf function to L2 normalize a PyTorch tensor along a specified dimension', 'run get_pil_img to load an image file from disk and convert it to RGB mode', 'review the MyImageFolder class and its getitem method that returns both the image and its file path', 'review the preprocess_1c torchvision transform pipeline that resizes, crops, and normalizes images', 'run the main training loop for NLI, SST2, or Flickr30K tasks with early stopping', 'save a PyTorch model checkpoint with optimizer, scheduler, and early stopper state to disk', 'resume training by loading model, optimizer, scheduler, and early stopper state from a checkpoint file', 'load and split SNLI, MultiNLI, SST2, or Flickr30K datasets into train, dev, and test sets', 'create BucketIterator or DataLoader iterators for train, dev, and test splits by task type', 'create an EarlyStoppingCriterion with configurable patience, min or max mode, and minimum delta threshold', 'review the EarlyStoppingCriterion step method that tracks best score and returns whether training should continue', 'refactor get_data_splits to support additional dataset types beyond SNLI, MultiNLI, SST2, and Flickr30K']
```

Usage

```
{'run_train_loop': 'run the main training loop for NLI, SST2, or Flickr30K tasks with early stopping', 'save_checkpoint': 'save a PyTorch model checkpoint with optimizer, scheduler, and early stopper state to disk', 'resume_from_checkpoint': 'resume training by loading model, optimizer, scheduler, and early stopper state from a checkpoint file', 'get_data_splits': 'load and split SNLI, MultiNLI, SST2, or Flickr30K datasets into train, dev, and test sets', 'get_data_iters': 'create BucketIterator or DataLoader iterators for train, dev, and test splits by task type', 'create_early_stopping_criterion': 'create an EarlyStoppingCriterion with configurable patience, min or max mode, and minimum delta threshold', 'review_EarlyStoppingCriterion_step': 'review the EarlyStoppingCriterion step method that tracks best score and returns whether training should continue', 'refactor_get_data_splits': 'refactor get_data_splits to support additional dataset types beyond SNLI, MultiNLI, SST2, and Flickr30K'}
```


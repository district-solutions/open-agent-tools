# Agent Python Tools

- repo: facebookresearch/pixio
- repo_uri: https://github.com/facebookresearch/pixio

## File: facebookresearch_pixio/evaluation/eval_knn.py

Prompts

```
['run the k-NN classifier evaluation on ImageNet using a pretrained Pixio model with distributed GPUs', 'extract normalized CLS token features from a model across a dataset using distributed data loading', 'run the k-NN classification algorithm on train and test feature tensors with configurable k and temperature', 'review the extract_feature_pipeline function that prepares datasets, loads a model, and extracts features for train and val sets', 'review the ReturnIndexDataset class that extends ImageFolder to return sample indices alongside images and labels', 'run monocular depth estimation training on KITTI or NYUv2 datasets with distributed data parallel', 'run sliding window inference on images using the infer_model function for depth prediction', 'run the DPTDepth model for monocular depth estimation with a pretrained encoder', 'run the LinearDepth model for monocular depth estimation with a pretrained encoder', 'run depth evaluation metrics including d1, d2, d3, abs_rel, sq_rel, rmse, rmse_log, log10, and silog', 'run the semantic segmentation training loop with DPT or linear head on a dataset using distributed data parallel', 'run sliding window inference to evaluate mIoU on a semantic segmentation validation set with distributed reduction', 'run the Pixio semantic segmentation evaluation CLI with a config file, encoder, and pretrained checkpoint path', 'review the evaluate function that performs sliding window inference and computes per-class IoU and mean IoU metrics', 'review the main function that sets up distributed training with AdamW optimizer, mixed precision, and cosine LR schedule']
```

Usage

```
{'run_knn_evaluation': 'run the k-NN classifier evaluation on ImageNet using a pretrained Pixio model with distributed GPUs', 'extract_features': 'extract normalized CLS token features from a model across a dataset using distributed data loading', 'run_knn_classifier': 'run the k-NN classification algorithm on train and test feature tensors with configurable k and temperature', 'review_extract_feature_pipeline': 'review the extract_feature_pipeline function that prepares datasets, loads a model, and extracts features for train and val sets', 'review_returnindexdataset': 'review the ReturnIndexDataset class that extends ImageFolder to return sample indices alongside images and labels'}
```

## File: facebookresearch_pixio/evaluation/eval_monodepth.py

Prompts

```
['run the k-NN classifier evaluation on ImageNet using a pretrained Pixio model with distributed GPUs', 'extract normalized CLS token features from a model across a dataset using distributed data loading', 'run the k-NN classification algorithm on train and test feature tensors with configurable k and temperature', 'review the extract_feature_pipeline function that prepares datasets, loads a model, and extracts features for train and val sets', 'review the ReturnIndexDataset class that extends ImageFolder to return sample indices alongside images and labels', 'run monocular depth estimation training on KITTI or NYUv2 datasets with distributed data parallel', 'run sliding window inference on images using the infer_model function for depth prediction', 'run the DPTDepth model for monocular depth estimation with a pretrained encoder', 'run the LinearDepth model for monocular depth estimation with a pretrained encoder', 'run depth evaluation metrics including d1, d2, d3, abs_rel, sq_rel, rmse, rmse_log, log10, and silog', 'run the semantic segmentation training loop with DPT or linear head on a dataset using distributed data parallel', 'run sliding window inference to evaluate mIoU on a semantic segmentation validation set with distributed reduction', 'run the Pixio semantic segmentation evaluation CLI with a config file, encoder, and pretrained checkpoint path', 'review the evaluate function that performs sliding window inference and computes per-class IoU and mean IoU metrics', 'review the main function that sets up distributed training with AdamW optimizer, mixed precision, and cosine LR schedule']
```

Usage

```
{'run_monodepth_training': 'run monocular depth estimation training on KITTI or NYUv2 datasets with distributed data parallel', 'run_sliding_window_inference': 'run sliding window inference on images using the infer_model function for depth prediction', 'run_dpt_depth_model': 'run the DPTDepth model for monocular depth estimation with a pretrained encoder', 'run_linear_depth_model': 'run the LinearDepth model for monocular depth estimation with a pretrained encoder', 'run_depth_evaluation': 'run depth evaluation metrics including d1, d2, d3, abs_rel, sq_rel, rmse, rmse_log, log10, and silog'}
```

## File: facebookresearch_pixio/evaluation/eval_semseg.py

Prompts

```
['run the k-NN classifier evaluation on ImageNet using a pretrained Pixio model with distributed GPUs', 'extract normalized CLS token features from a model across a dataset using distributed data loading', 'run the k-NN classification algorithm on train and test feature tensors with configurable k and temperature', 'review the extract_feature_pipeline function that prepares datasets, loads a model, and extracts features for train and val sets', 'review the ReturnIndexDataset class that extends ImageFolder to return sample indices alongside images and labels', 'run monocular depth estimation training on KITTI or NYUv2 datasets with distributed data parallel', 'run sliding window inference on images using the infer_model function for depth prediction', 'run the DPTDepth model for monocular depth estimation with a pretrained encoder', 'run the LinearDepth model for monocular depth estimation with a pretrained encoder', 'run depth evaluation metrics including d1, d2, d3, abs_rel, sq_rel, rmse, rmse_log, log10, and silog', 'run the semantic segmentation training loop with DPT or linear head on a dataset using distributed data parallel', 'run sliding window inference to evaluate mIoU on a semantic segmentation validation set with distributed reduction', 'run the Pixio semantic segmentation evaluation CLI with a config file, encoder, and pretrained checkpoint path', 'review the evaluate function that performs sliding window inference and computes per-class IoU and mean IoU metrics', 'review the main function that sets up distributed training with AdamW optimizer, mixed precision, and cosine LR schedule']
```

Usage

```
{'run_semantic_segmentation_training': 'run the semantic segmentation training loop with DPT or linear head on a dataset using distributed data parallel', 'run_semantic_segmentation_evaluation': 'run sliding window inference to evaluate mIoU on a semantic segmentation validation set with distributed reduction', 'run_pixio_eval_cli': 'run the Pixio semantic segmentation evaluation CLI with a config file, encoder, and pretrained checkpoint path', 'review_evaluate_function': 'review the evaluate function that performs sliding window inference and computes per-class IoU and mean IoU metrics', 'review_main_training_loop': 'review the main function that sets up distributed training with AdamW optimizer, mixed precision, and cosine LR schedule'}
```


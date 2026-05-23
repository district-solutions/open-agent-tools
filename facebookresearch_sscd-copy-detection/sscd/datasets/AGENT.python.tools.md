# Agent Python Tools

- repo: facebookresearch/sscd-copy-detection
- repo_uri: https://github.com/facebookresearch/sscd-copy-detection

## File: facebookresearch_sscd-copy-detection/sscd/datasets/copydays.py

Prompts

```
['compute the average precision of one search from a list of true positive ranks and total positives', 'compute the macro mean average precision, recall, and precision from ground truth and distance matrices', 'split a list of image filenames into groups based on their parent directory names', 'evaluate copy detection results by computing mAP per block and macro AP across all blocks', 'compute precision and recall for each query in a cluster given result IDs and cluster image numbers', 'create a DISCEvalDataset instance from a dataset path with optional transform and train split', 'read image files and metadata from a directory path using the read_files class method', 'run retrieval evaluation on embeddings and targets to get uAP, accuracy-at-1, and recall-at-p90 metrics', 'evaluate retrieval performance on separate query and reference embedding splits with k-NN or global matching', 'get a sample dictionary with input image and metadata by index from the dataset', 'create an ImageFolder dataset from a directory path with optional transforms for self-supervised learning', 'get a sorted list of image file paths from a directory using get_image_paths', 'load an image by index from an ImageFolder dataset using the getitem method', 'apply an image-level transform to the input image before the record-level transform in ImageFolder', 'get the total number of images in an ImageFolder dataset using the len method']
```

Usage

```
{'compute_average_precision': 'compute the average precision of one search from a list of true positive ranks and total positives', 'compute_macro_map': 'compute the macro mean average precision, recall, and precision from ground truth and distance matrices', 'split_filenames_by_directory': 'split a list of image filenames into groups based on their parent directory names', 'evaluate_copydays_results': 'evaluate copy detection results by computing mAP per block and macro AP across all blocks', 'compute_cluster_precision_recall': 'compute precision and recall for each query in a cluster given result IDs and cluster image numbers'}
```

## File: facebookresearch_sscd-copy-detection/sscd/datasets/disc.py

Prompts

```
['compute the average precision of one search from a list of true positive ranks and total positives', 'compute the macro mean average precision, recall, and precision from ground truth and distance matrices', 'split a list of image filenames into groups based on their parent directory names', 'evaluate copy detection results by computing mAP per block and macro AP across all blocks', 'compute precision and recall for each query in a cluster given result IDs and cluster image numbers', 'create a DISCEvalDataset instance from a dataset path with optional transform and train split', 'read image files and metadata from a directory path using the read_files class method', 'run retrieval evaluation on embeddings and targets to get uAP, accuracy-at-1, and recall-at-p90 metrics', 'evaluate retrieval performance on separate query and reference embedding splits with k-NN or global matching', 'get a sample dictionary with input image and metadata by index from the dataset', 'create an ImageFolder dataset from a directory path with optional transforms for self-supervised learning', 'get a sorted list of image file paths from a directory using get_image_paths', 'load an image by index from an ImageFolder dataset using the getitem method', 'apply an image-level transform to the input image before the record-level transform in ImageFolder', 'get the total number of images in an ImageFolder dataset using the len method']
```

Usage

```
{'create_DISCEvalDataset': 'create a DISCEvalDataset instance from a dataset path with optional transform and train split', 'read_files_DISCEvalDataset': 'read image files and metadata from a directory path using the read_files class method', 'retrieval_eval_DISCEvalDataset': 'run retrieval evaluation on embeddings and targets to get uAP, accuracy-at-1, and recall-at-p90 metrics', 'retrieval_eval_splits_DISCEvalDataset': 'evaluate retrieval performance on separate query and reference embedding splits with k-NN or global matching', 'getitem_DISCEvalDataset': 'get a sample dictionary with input image and metadata by index from the dataset'}
```

## File: facebookresearch_sscd-copy-detection/sscd/datasets/image_folder.py

Prompts

```
['compute the average precision of one search from a list of true positive ranks and total positives', 'compute the macro mean average precision, recall, and precision from ground truth and distance matrices', 'split a list of image filenames into groups based on their parent directory names', 'evaluate copy detection results by computing mAP per block and macro AP across all blocks', 'compute precision and recall for each query in a cluster given result IDs and cluster image numbers', 'create a DISCEvalDataset instance from a dataset path with optional transform and train split', 'read image files and metadata from a directory path using the read_files class method', 'run retrieval evaluation on embeddings and targets to get uAP, accuracy-at-1, and recall-at-p90 metrics', 'evaluate retrieval performance on separate query and reference embedding splits with k-NN or global matching', 'get a sample dictionary with input image and metadata by index from the dataset', 'create an ImageFolder dataset from a directory path with optional transforms for self-supervised learning', 'get a sorted list of image file paths from a directory using get_image_paths', 'load an image by index from an ImageFolder dataset using the getitem method', 'apply an image-level transform to the input image before the record-level transform in ImageFolder', 'get the total number of images in an ImageFolder dataset using the len method']
```

Usage

```
{'create_imagefolder_dataset': 'create an ImageFolder dataset from a directory path with optional transforms for self-supervised learning', 'get_image_paths_list': 'get a sorted list of image file paths from a directory using get_image_paths', 'load_image_by_index': 'load an image by index from an ImageFolder dataset using the getitem method', 'apply_img_transform': 'apply an image-level transform to the input image before the record-level transform in ImageFolder', 'get_dataset_length': 'get the total number of images in an ImageFolder dataset using the len method'}
```


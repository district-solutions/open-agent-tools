# Agent Python Tools

- repo: facebookresearch/grounded-video-description
- repo_uri: https://github.com/facebookresearch/grounded-video-description

## File: facebookresearch_grounded-video-description/tools/anet_entities/scripts/attr_prep_tag_NP.py

Prompts

```
['run the ActivityNet-Entities dataset preprocessing script to convert raw annotations to NP/object annotation files', 'extract all attributes from video bounding box annotations in the ActivityNet database for train and val splits', 'define train, validation, and test splits from ActivityNet caption files with a 50/50 val-test split', 'generate object class list using Stanford CoreNLP lemmatization and frequency threshold filtering on noun phrases', 'preprocess the full database to create noun phrase annotations with object class labels and bounding boxes', 'run the ActivityNet entities grounding evaluation script with GT sentences using argparse CLI', 'run the ActivityNet entities grounding evaluation script with generated sentences using argparse CLI', 'review the ANetGrdEval class gt_grd_eval method that computes grounding accuracy for GT sentences', 'review the ANetGrdEval class grd_eval method that computes precision recall and F1 scores', 'review the ANetGrdEval class precision_recall_util method that calculates per-class precision and recall', 'compute IoU overlaps between anchor boxes and ground truth boxes in batch mode using PyTorch tensors', 'compute batched bounding box overlaps with an optional frame mask to filter cross-frame matches', 'generate a boolean frame mask by comparing proposal frame indices against ground truth bounding box frame indices', 'review the bbox_overlaps_batch function that handles both 2D and 3D anchor tensor inputs for IoU calculation', 'refactor the get_frm_mask function to use numpy broadcasting instead of tile for better performance']
```

Usage

```
{'run_preprocess_anet_entities': 'run the ActivityNet-Entities dataset preprocessing script to convert raw annotations to NP/object annotation files', 'extract_attr_from_database': 'extract all attributes from video bounding box annotations in the ActivityNet database for train and val splits', 'define_train_val_test_split': 'define train, validation, and test splits from ActivityNet caption files with a 50/50 val-test split', 'freq_obj_list_with_nlp': 'generate object class list using Stanford CoreNLP lemmatization and frequency threshold filtering on noun phrases', 'prep_all_database_with_noun_phrases': 'preprocess the full database to create noun phrase annotations with object class labels and bounding boxes'}
```

## File: facebookresearch_grounded-video-description/tools/anet_entities/scripts/eval_grd_anet_entities.py

Prompts

```
['run the ActivityNet-Entities dataset preprocessing script to convert raw annotations to NP/object annotation files', 'extract all attributes from video bounding box annotations in the ActivityNet database for train and val splits', 'define train, validation, and test splits from ActivityNet caption files with a 50/50 val-test split', 'generate object class list using Stanford CoreNLP lemmatization and frequency threshold filtering on noun phrases', 'preprocess the full database to create noun phrase annotations with object class labels and bounding boxes', 'run the ActivityNet entities grounding evaluation script with GT sentences using argparse CLI', 'run the ActivityNet entities grounding evaluation script with generated sentences using argparse CLI', 'review the ANetGrdEval class gt_grd_eval method that computes grounding accuracy for GT sentences', 'review the ANetGrdEval class grd_eval method that computes precision recall and F1 scores', 'review the ANetGrdEval class precision_recall_util method that calculates per-class precision and recall', 'compute IoU overlaps between anchor boxes and ground truth boxes in batch mode using PyTorch tensors', 'compute batched bounding box overlaps with an optional frame mask to filter cross-frame matches', 'generate a boolean frame mask by comparing proposal frame indices against ground truth bounding box frame indices', 'review the bbox_overlaps_batch function that handles both 2D and 3D anchor tensor inputs for IoU calculation', 'refactor the get_frm_mask function to use numpy broadcasting instead of tile for better performance']
```

Usage

```
{'run_gt_grounding_evaluation': 'run the ActivityNet entities grounding evaluation script with GT sentences using argparse CLI', 'run_gen_grounding_evaluation': 'run the ActivityNet entities grounding evaluation script with generated sentences using argparse CLI', 'review_ANetGrdEval_gt_grd_eval': 'review the ANetGrdEval class gt_grd_eval method that computes grounding accuracy for GT sentences', 'review_ANetGrdEval_grd_eval': 'review the ANetGrdEval class grd_eval method that computes precision recall and F1 scores', 'review_ANetGrdEval_precision_recall_util': 'review the ANetGrdEval class precision_recall_util method that calculates per-class precision and recall'}
```

## File: facebookresearch_grounded-video-description/tools/anet_entities/scripts/utils.py

Prompts

```
['run the ActivityNet-Entities dataset preprocessing script to convert raw annotations to NP/object annotation files', 'extract all attributes from video bounding box annotations in the ActivityNet database for train and val splits', 'define train, validation, and test splits from ActivityNet caption files with a 50/50 val-test split', 'generate object class list using Stanford CoreNLP lemmatization and frequency threshold filtering on noun phrases', 'preprocess the full database to create noun phrase annotations with object class labels and bounding boxes', 'run the ActivityNet entities grounding evaluation script with GT sentences using argparse CLI', 'run the ActivityNet entities grounding evaluation script with generated sentences using argparse CLI', 'review the ANetGrdEval class gt_grd_eval method that computes grounding accuracy for GT sentences', 'review the ANetGrdEval class grd_eval method that computes precision recall and F1 scores', 'review the ANetGrdEval class precision_recall_util method that calculates per-class precision and recall', 'compute IoU overlaps between anchor boxes and ground truth boxes in batch mode using PyTorch tensors', 'compute batched bounding box overlaps with an optional frame mask to filter cross-frame matches', 'generate a boolean frame mask by comparing proposal frame indices against ground truth bounding box frame indices', 'review the bbox_overlaps_batch function that handles both 2D and 3D anchor tensor inputs for IoU calculation', 'refactor the get_frm_mask function to use numpy broadcasting instead of tile for better performance']
```

Usage

```
{'compute_bbox_overlaps_batch': 'compute IoU overlaps between anchor boxes and ground truth boxes in batch mode using PyTorch tensors', 'compute_bbox_overlaps_with_mask': 'compute batched bounding box overlaps with an optional frame mask to filter cross-frame matches', 'generate_frame_mask': 'generate a boolean frame mask by comparing proposal frame indices against ground truth bounding box frame indices', 'review_bbox_overlaps_batch': 'review the bbox_overlaps_batch function that handles both 2D and 3D anchor tensor inputs for IoU calculation', 'refactor_get_frm_mask': 'refactor the get_frm_mask function to use numpy broadcasting instead of tile for better performance'}
```


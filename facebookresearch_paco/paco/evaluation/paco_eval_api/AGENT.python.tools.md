# Agent Python Tools

- repo: facebookresearch/paco
- repo_uri: https://github.com/facebookresearch/paco

## File: facebookresearch_paco/paco/evaluation/paco_eval_api/eval.py

Prompts

```
['run PACOEval on ground truth and detection results to compute object and attribute AP metrics', 'evaluate a single image and category for PACO object and part detection using PACOEval.evaluate_img', 'evaluate joint object-attribute detection for a single image and category using PACOEval.evaluate_img_attr', 'accumulate per-image joint attribute evaluation results into precision and recall arrays using PACOEval.accumulate_joint_attr', 'summarize accumulated joint attribute evaluation results into AP and AR metrics using PACOEval.summarize_joint_attr', 'initialize a PACO object from an annotation file path to read PACO dataset annotations', 'get a mapping from image id and joint attribute category to ground truth annotation ids', 'build an index of images, annotations, categories, and joint object-attribute pairs for PACO evaluation', 'retrieve all joint object-attribute category ids from the PACO dataset index', 'review the PACO class that extends LVIS to support object-attribute annotations and evaluation indexing', 'initialize a PACOResults object from ground truth annotations and detection results with a max detections limit', 'limit detections per image by sorting annotations by score and keeping only the top N results', 'get top detection results for a given image ID filtered by a minimum score threshold', 'review the PACOResults class that extends PACO to handle detection results with bbox and segmentation support']
```

Usage

```
{'run_paco_evaluation': 'run PACOEval on ground truth and detection results to compute object and attribute AP metrics', 'evaluate_paco_per_image': 'evaluate a single image and category for PACO object and part detection using PACOEval.evaluate_img', 'evaluate_paco_joint_attr': 'evaluate joint object-attribute detection for a single image and category using PACOEval.evaluate_img_attr', 'accumulate_paco_attr_results': 'accumulate per-image joint attribute evaluation results into precision and recall arrays using PACOEval.accumulate_joint_attr', 'summarize_paco_attr_results': 'summarize accumulated joint attribute evaluation results into AP and AR metrics using PACOEval.summarize_joint_attr'}
```

## File: facebookresearch_paco/paco/evaluation/paco_eval_api/paco.py

Prompts

```
['run PACOEval on ground truth and detection results to compute object and attribute AP metrics', 'evaluate a single image and category for PACO object and part detection using PACOEval.evaluate_img', 'evaluate joint object-attribute detection for a single image and category using PACOEval.evaluate_img_attr', 'accumulate per-image joint attribute evaluation results into precision and recall arrays using PACOEval.accumulate_joint_attr', 'summarize accumulated joint attribute evaluation results into AP and AR metrics using PACOEval.summarize_joint_attr', 'initialize a PACO object from an annotation file path to read PACO dataset annotations', 'get a mapping from image id and joint attribute category to ground truth annotation ids', 'build an index of images, annotations, categories, and joint object-attribute pairs for PACO evaluation', 'retrieve all joint object-attribute category ids from the PACO dataset index', 'review the PACO class that extends LVIS to support object-attribute annotations and evaluation indexing', 'initialize a PACOResults object from ground truth annotations and detection results with a max detections limit', 'limit detections per image by sorting annotations by score and keeping only the top N results', 'get top detection results for a given image ID filtered by a minimum score threshold', 'review the PACOResults class that extends PACO to handle detection results with bbox and segmentation support']
```

Usage

```
{'init_PACO': 'initialize a PACO object from an annotation file path to read PACO dataset annotations', 'get_im_joint_attr_cat_to_ann_id': 'get a mapping from image id and joint attribute category to ground truth annotation ids', 'create_index_PACO': 'build an index of images, annotations, categories, and joint object-attribute pairs for PACO evaluation', 'get_joint_attr_ids': 'retrieve all joint object-attribute category ids from the PACO dataset index', 'review_PACO_class': 'review the PACO class that extends LVIS to support object-attribute annotations and evaluation indexing'}
```

## File: facebookresearch_paco/paco/evaluation/paco_eval_api/results.py

Prompts

```
['run PACOEval on ground truth and detection results to compute object and attribute AP metrics', 'evaluate a single image and category for PACO object and part detection using PACOEval.evaluate_img', 'evaluate joint object-attribute detection for a single image and category using PACOEval.evaluate_img_attr', 'accumulate per-image joint attribute evaluation results into precision and recall arrays using PACOEval.accumulate_joint_attr', 'summarize accumulated joint attribute evaluation results into AP and AR metrics using PACOEval.summarize_joint_attr', 'initialize a PACO object from an annotation file path to read PACO dataset annotations', 'get a mapping from image id and joint attribute category to ground truth annotation ids', 'build an index of images, annotations, categories, and joint object-attribute pairs for PACO evaluation', 'retrieve all joint object-attribute category ids from the PACO dataset index', 'review the PACO class that extends LVIS to support object-attribute annotations and evaluation indexing', 'initialize a PACOResults object from ground truth annotations and detection results with a max detections limit', 'limit detections per image by sorting annotations by score and keeping only the top N results', 'get top detection results for a given image ID filtered by a minimum score threshold', 'review the PACOResults class that extends PACO to handle detection results with bbox and segmentation support']
```

Usage

```
{'init_PACOResults': 'initialize a PACOResults object from ground truth annotations and detection results with a max detections limit', 'limit_dets_per_image': 'limit detections per image by sorting annotations by score and keeping only the top N results', 'get_top_results': 'get top detection results for a given image ID filtered by a minimum score threshold', 'get_im_joint_attr_cat_to_ann_id': 'get a mapping of image and joint attribute category pairs to their annotation IDs', 'review_PACOResults_class': 'review the PACOResults class that extends PACO to handle detection results with bbox and segmentation support'}
```


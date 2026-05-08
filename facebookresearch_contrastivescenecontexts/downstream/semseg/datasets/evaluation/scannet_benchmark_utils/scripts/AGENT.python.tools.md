# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/datasets/evaluation/scannet_benchmark_utils/scripts/evaluate_semantic_instance.py

Prompts

```
['run the evaluate_semantic_instance.py CLI with --pred_path and --gt_path to evaluate ScanNet semantic instance predictions', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet 3D semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision scores per class and overlap threshold', 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write prediction instances to benchmark output format with predicted masks and confidence scores', 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'create an Evaluator instance with class labels and valid class IDs for ScanNet benchmark evaluation', 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get the IoU score for a specific label ID using true positives, false positives, and false negatives', 'read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read a tab-delimited scene types file and return a mapping of scene names to integer IDs', 'create a colorized visualization image from a label array and save it to a file', 'create a colorized visualization image from an instance segmentation array and save it to a file', 'check if a given string can be safely converted to an integer', 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'parse a ScanNet instance prediction file into a dictionary of mask paths with label IDs and confidence scores', 'extract Instance objects grouped by class label from vertex IDs using class mapping dictionaries']
```

Usage

```
{'run_semantic_instance_evaluation': 'run the evaluate_semantic_instance.py CLI with --pred_path and --gt_path to evaluate ScanNet semantic instance predictions', 'create_Evaluator': 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet 3D semantic instance evaluation', 'evaluate_matches': 'evaluate matched prediction and ground truth instances to compute average precision scores per class and overlap threshold', 'assign_instances_for_scan': 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write_to_benchmark': 'write prediction instances to benchmark output format with predicted masks and confidence scores'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/datasets/evaluation/scannet_benchmark_utils/scripts/evaluate_semantic_label.py

Prompts

```
['run the evaluate_semantic_instance.py CLI with --pred_path and --gt_path to evaluate ScanNet semantic instance predictions', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet 3D semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision scores per class and overlap threshold', 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write prediction instances to benchmark output format with predicted masks and confidence scores', 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'create an Evaluator instance with class labels and valid class IDs for ScanNet benchmark evaluation', 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get the IoU score for a specific label ID using true positives, false positives, and false negatives', 'read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read a tab-delimited scene types file and return a mapping of scene names to integer IDs', 'create a colorized visualization image from a label array and save it to a file', 'create a colorized visualization image from an instance segmentation array and save it to a file', 'check if a given string can be safely converted to an integer', 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'parse a ScanNet instance prediction file into a dictionary of mask paths with label IDs and confidence scores', 'extract Instance objects grouped by class label from vertex IDs using class mapping dictionaries']
```

Usage

```
{'run_semantic_label_evaluation': 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'create_evaluator': 'create an Evaluator instance with class labels and valid class IDs for ScanNet benchmark evaluation', 'update_confusion_matrix': 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate_confusion_and_write_results': 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get_iou_for_class': 'get the IoU score for a specific label ID using true positives, false positives, and false negatives'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/datasets/evaluation/scannet_benchmark_utils/scripts/util.py

Prompts

```
['run the evaluate_semantic_instance.py CLI with --pred_path and --gt_path to evaluate ScanNet semantic instance predictions', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet 3D semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision scores per class and overlap threshold', 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write prediction instances to benchmark output format with predicted masks and confidence scores', 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'create an Evaluator instance with class labels and valid class IDs for ScanNet benchmark evaluation', 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get the IoU score for a specific label ID using true positives, false positives, and false negatives', 'read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read a tab-delimited scene types file and return a mapping of scene names to integer IDs', 'create a colorized visualization image from a label array and save it to a file', 'create a colorized visualization image from an instance segmentation array and save it to a file', 'check if a given string can be safely converted to an integer', 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'parse a ScanNet instance prediction file into a dictionary of mask paths with label IDs and confidence scores', 'extract Instance objects grouped by class label from vertex IDs using class mapping dictionaries']
```

Usage

```
{'read_label_mapping_from_csv': 'read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read_scene_types_mapping': 'read a tab-delimited scene types file and return a mapping of scene names to integer IDs', 'visualize_label_image': 'create a colorized visualization image from a label array and save it to a file', 'visualize_instance_image': 'create a colorized visualization image from an instance segmentation array and save it to a file', 'represents_int': 'check if a given string can be safely converted to an integer'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/semseg/datasets/evaluation/scannet_benchmark_utils/scripts/util_3d.py

Prompts

```
['run the evaluate_semantic_instance.py CLI with --pred_path and --gt_path to evaluate ScanNet semantic instance predictions', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS for ScanNet 3D semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision scores per class and overlap threshold', 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write prediction instances to benchmark output format with predicted masks and confidence scores', 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'create an Evaluator instance with class labels and valid class IDs for ScanNet benchmark evaluation', 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get the IoU score for a specific label ID using true positives, false positives, and false negatives', 'read a tab-delimited CSV file and return a label mapping dictionary with integer values', 'read a tab-delimited scene types file and return a mapping of scene names to integer IDs', 'create a colorized visualization image from a label array and save it to a file', 'create a colorized visualization image from an instance segmentation array and save it to a file', 'check if a given string can be safely converted to an integer', 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'parse a ScanNet instance prediction file into a dictionary of mask paths with label IDs and confidence scores', 'extract Instance objects grouped by class label from vertex IDs using class mapping dictionaries']
```

Usage

```
{'transform_points_3d': 'apply a 4x4 transformation matrix to an Nx3 numpy array of 3D points', 'read_mesh_vertices_ply': 'read vertex coordinates from a PLY mesh file and return an Nx3 numpy array', 'export_instance_ids_for_eval': 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'read_instance_prediction_file': 'parse a ScanNet instance prediction file into a dictionary of mask paths with label IDs and confidence scores', 'get_instances_from_ids': 'extract Instance objects grouped by class label from vertex IDs using class mapping dictionaries'}
```


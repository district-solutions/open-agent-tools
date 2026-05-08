# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/datasets/evaluation/scannet_benchmark_utils/scripts/evaluate_semantic_instance.py

Prompts

```
['run the evaluate_semantic_instance.py script with --pred_path and --gt_path to evaluate 3D semantic instance segmentation on ScanNet scans', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS to set up ScanNet semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision scores across overlap thresholds', 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write prediction instances and masks to the benchmark output format for ScanNet instance segmentation submission', 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get the IoU score for a specific label ID using true positives, false positives, and false negatives', 'read a tab-delimited CSV file and return a dictionary mapping labels from one column to integer values in another', 'read a tab-delimited text file and return a dictionary mapping scene type names to integer IDs', 'create a colorized visualization of a label segmentation numpy array and save it as an image file', 'create a colorized visualization of an instance segmentation numpy array with unique colors per instance and save it', 'check if a given string can be safely parsed as an integer and return a boolean result', 'transform a set of 3D points using a 4x4 transformation matrix with perspective division', 'read mesh vertices from a PLY file and return them as a numpy array of xyz coordinates', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'read and parse an instance prediction file with mask paths, label IDs, and confidence scores', 'get all instances grouped by class label from mesh vertex instance IDs and class mappings']
```

Usage

```
{'run_semantic_instance_evaluation': 'run the evaluate_semantic_instance.py script with --pred_path and --gt_path to evaluate 3D semantic instance segmentation on ScanNet scans', 'create_evaluator': 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS to set up ScanNet semantic instance evaluation', 'evaluate_matches': 'evaluate matched prediction and ground truth instances to compute average precision scores across overlap thresholds', 'assign_instances_for_scan': 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write_to_benchmark': 'write prediction instances and masks to the benchmark output format for ScanNet instance segmentation submission'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/datasets/evaluation/scannet_benchmark_utils/scripts/evaluate_semantic_label.py

Prompts

```
['run the evaluate_semantic_instance.py script with --pred_path and --gt_path to evaluate 3D semantic instance segmentation on ScanNet scans', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS to set up ScanNet semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision scores across overlap thresholds', 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write prediction instances and masks to the benchmark output format for ScanNet instance segmentation submission', 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get the IoU score for a specific label ID using true positives, false positives, and false negatives', 'read a tab-delimited CSV file and return a dictionary mapping labels from one column to integer values in another', 'read a tab-delimited text file and return a dictionary mapping scene type names to integer IDs', 'create a colorized visualization of a label segmentation numpy array and save it as an image file', 'create a colorized visualization of an instance segmentation numpy array with unique colors per instance and save it', 'check if a given string can be safely parsed as an integer and return a boolean result', 'transform a set of 3D points using a 4x4 transformation matrix with perspective division', 'read mesh vertices from a PLY file and return them as a numpy array of xyz coordinates', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'read and parse an instance prediction file with mask paths, label IDs, and confidence scores', 'get all instances grouped by class label from mesh vertex instance IDs and class mappings']
```

Usage

```
{'run_semantic_label_evaluation': 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'create_evaluator': 'create an Evaluator instance with class labels and valid class IDs for ScanNet benchmark evaluation', 'update_confusion_matrix': 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate_confusion_and_write_results': 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get_iou_for_class': 'get the IoU score for a specific label ID using true positives, false positives, and false negatives'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/datasets/evaluation/scannet_benchmark_utils/scripts/util.py

Prompts

```
['run the evaluate_semantic_instance.py script with --pred_path and --gt_path to evaluate 3D semantic instance segmentation on ScanNet scans', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS to set up ScanNet semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision scores across overlap thresholds', 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write prediction instances and masks to the benchmark output format for ScanNet instance segmentation submission', 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get the IoU score for a specific label ID using true positives, false positives, and false negatives', 'read a tab-delimited CSV file and return a dictionary mapping labels from one column to integer values in another', 'read a tab-delimited text file and return a dictionary mapping scene type names to integer IDs', 'create a colorized visualization of a label segmentation numpy array and save it as an image file', 'create a colorized visualization of an instance segmentation numpy array with unique colors per instance and save it', 'check if a given string can be safely parsed as an integer and return a boolean result', 'transform a set of 3D points using a 4x4 transformation matrix with perspective division', 'read mesh vertices from a PLY file and return them as a numpy array of xyz coordinates', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'read and parse an instance prediction file with mask paths, label IDs, and confidence scores', 'get all instances grouped by class label from mesh vertex instance IDs and class mappings']
```

Usage

```
{'read_label_mapping': 'read a tab-delimited CSV file and return a dictionary mapping labels from one column to integer values in another', 'read_scene_types_mapping': 'read a tab-delimited text file and return a dictionary mapping scene type names to integer IDs', 'visualize_label_image': 'create a colorized visualization of a label segmentation numpy array and save it as an image file', 'visualize_instance_image': 'create a colorized visualization of an instance segmentation numpy array with unique colors per instance and save it', 'represents_int': 'check if a given string can be safely parsed as an integer and return a boolean result'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/insseg/datasets/evaluation/scannet_benchmark_utils/scripts/util_3d.py

Prompts

```
['run the evaluate_semantic_instance.py script with --pred_path and --gt_path to evaluate 3D semantic instance segmentation on ScanNet scans', 'create an Evaluator instance with CLASS_LABELS and VALID_CLASS_IDS to set up ScanNet semantic instance evaluation', 'evaluate matched prediction and ground truth instances to compute average precision scores across overlap thresholds', 'assign predicted instances to ground truth instances for a single scan by computing vertex-level intersections', 'write prediction instances and masks to the benchmark output format for ScanNet instance segmentation submission', 'run the CLI to evaluate semantic label predictions against ground truth for ScanNet scans', 'update the confusion matrix by comparing predicted IDs against ground truth IDs for a scan', 'evaluate the accumulated confusion matrix and write per-class IoU scores and confusion matrix to a file', 'get the IoU score for a specific label ID using true positives, false positives, and false negatives', 'read a tab-delimited CSV file and return a dictionary mapping labels from one column to integer values in another', 'read a tab-delimited text file and return a dictionary mapping scene type names to integer IDs', 'create a colorized visualization of a label segmentation numpy array and save it as an image file', 'create a colorized visualization of an instance segmentation numpy array with unique colors per instance and save it', 'check if a given string can be safely parsed as an integer and return a boolean result', 'transform a set of 3D points using a 4x4 transformation matrix with perspective division', 'read mesh vertices from a PLY file and return them as a numpy array of xyz coordinates', 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'read and parse an instance prediction file with mask paths, label IDs, and confidence scores', 'get all instances grouped by class label from mesh vertex instance IDs and class mappings']
```

Usage

```
{'transform_points_3d': 'transform a set of 3D points using a 4x4 transformation matrix with perspective division', 'read_mesh_vertices_ply': 'read mesh vertices from a PLY file and return them as a numpy array of xyz coordinates', 'export_instance_ids_for_eval': 'export 3D instance labels and predicted masks for ScanNet instance segmentation evaluation', 'read_instance_prediction_file': 'read and parse an instance prediction file with mask paths, label IDs, and confidence scores', 'get_instances_by_class': 'get all instances grouped by class label from mesh vertex instance IDs and class mappings'}
```


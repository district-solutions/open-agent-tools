# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/evaluation/densepose_coco_evaluation.py

Prompts

```
['run DensePose COCO evaluation by creating DensePoseCocoEval with ground truth and detection COCO objects then calling evaluate', 'accumulate per-image per-category DensePose evaluation results into precision and recall arrays using the accumulate method', 'summarize DensePose evaluation metrics including AP and AR at various OGPS thresholds and area ranges using summarize', 'compute OGPS scores between detections and ground truth by calling computeOgps for a given image and category ID', 'configure DensePose evaluation parameters such as IoU thresholds, recall thresholds, and max detections using the Params class', 'build a DensePoseCOCOEvaluator instance for a given dataset name with distributed evaluation and optional mesh alignment', 'create a function that converts model prediction instances into a list of dicts for DensePose evaluation format', 'build a tensor storage object for DensePose evaluation from a config node specifying ram or file storage', 'evaluate mesh alignment metrics using the MeshAlignmentEvaluator to compute GE and GPS per mesh and overall', 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run geodesic distance evaluation between keyvertices of two meshes using vertex embedding similarity', 'review the MeshAlignmentEvaluator evaluate method that computes GE and GPS metrics across mesh pairs', 'summarize how GPS scores are computed from geodesic distances using a Gaussian kernel with sigma 0.255', 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'put a dictionary of named tensors into the storage and get back a record ID', 'get stored tensors by record ID from a SingleProcessTensorStorage instance', 'create a MultiProcessFileTensorStorage mapping process ranks to file paths for multi-process tensor access', 'gather single process tensor storages from multiple ranks into a MultiProcessTensorStorage on the destination rank']
```

Usage

```
{'run_densepose_evaluation': 'run DensePose COCO evaluation by creating DensePoseCocoEval with ground truth and detection COCO objects then calling evaluate', 'accumulate_densepose_results': 'accumulate per-image per-category DensePose evaluation results into precision and recall arrays using the accumulate method', 'summarize_densepose_metrics': 'summarize DensePose evaluation metrics including AP and AR at various OGPS thresholds and area ranges using summarize', 'compute_ogps_iou': 'compute OGPS scores between detections and ground truth by calling computeOgps for a given image and category ID', 'configure_densepose_params': 'configure DensePose evaluation parameters such as IoU thresholds, recall thresholds, and max detections using the Params class'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/evaluation/evaluator.py

Prompts

```
['run DensePose COCO evaluation by creating DensePoseCocoEval with ground truth and detection COCO objects then calling evaluate', 'accumulate per-image per-category DensePose evaluation results into precision and recall arrays using the accumulate method', 'summarize DensePose evaluation metrics including AP and AR at various OGPS thresholds and area ranges using summarize', 'compute OGPS scores between detections and ground truth by calling computeOgps for a given image and category ID', 'configure DensePose evaluation parameters such as IoU thresholds, recall thresholds, and max detections using the Params class', 'build a DensePoseCOCOEvaluator instance for a given dataset name with distributed evaluation and optional mesh alignment', 'create a function that converts model prediction instances into a list of dicts for DensePose evaluation format', 'build a tensor storage object for DensePose evaluation from a config node specifying ram or file storage', 'evaluate mesh alignment metrics using the MeshAlignmentEvaluator to compute GE and GPS per mesh and overall', 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run geodesic distance evaluation between keyvertices of two meshes using vertex embedding similarity', 'review the MeshAlignmentEvaluator evaluate method that computes GE and GPS metrics across mesh pairs', 'summarize how GPS scores are computed from geodesic distances using a Gaussian kernel with sigma 0.255', 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'put a dictionary of named tensors into the storage and get back a record ID', 'get stored tensors by record ID from a SingleProcessTensorStorage instance', 'create a MultiProcessFileTensorStorage mapping process ranks to file paths for multi-process tensor access', 'gather single process tensor storages from multiple ranks into a MultiProcessTensorStorage on the destination rank']
```

Usage

```
{'build_DensePoseCOCOEvaluator': 'build a DensePoseCOCOEvaluator instance for a given dataset name with distributed evaluation and optional mesh alignment', 'run_densepose_evaluation': 'run the DensePoseCOCOEvaluator evaluate method to compute GPS, GPSM, and segmentation metrics on COCO predictions', 'create_prediction_to_dict': 'create a function that converts model prediction instances into a list of dicts for DensePose evaluation format', 'build_densepose_evaluator_storage': 'build a tensor storage object for DensePose evaluation from a config node specifying ram or file storage', 'evaluate_mesh_alignment': 'evaluate mesh alignment metrics using the MeshAlignmentEvaluator to compute GE and GPS per mesh and overall'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/evaluation/mesh_alignment_evaluator.py

Prompts

```
['run DensePose COCO evaluation by creating DensePoseCocoEval with ground truth and detection COCO objects then calling evaluate', 'accumulate per-image per-category DensePose evaluation results into precision and recall arrays using the accumulate method', 'summarize DensePose evaluation metrics including AP and AR at various OGPS thresholds and area ranges using summarize', 'compute OGPS scores between detections and ground truth by calling computeOgps for a given image and category ID', 'configure DensePose evaluation parameters such as IoU thresholds, recall thresholds, and max detections using the Params class', 'build a DensePoseCOCOEvaluator instance for a given dataset name with distributed evaluation and optional mesh alignment', 'create a function that converts model prediction instances into a list of dicts for DensePose evaluation format', 'build a tensor storage object for DensePose evaluation from a config node specifying ram or file storage', 'evaluate mesh alignment metrics using the MeshAlignmentEvaluator to compute GE and GPS per mesh and overall', 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run geodesic distance evaluation between keyvertices of two meshes using vertex embedding similarity', 'review the MeshAlignmentEvaluator evaluate method that computes GE and GPS metrics across mesh pairs', 'summarize how GPS scores are computed from geodesic distances using a Gaussian kernel with sigma 0.255', 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'put a dictionary of named tensors into the storage and get back a record ID', 'get stored tensors by record ID from a SingleProcessTensorStorage instance', 'create a MultiProcessFileTensorStorage mapping process ranks to file paths for multi-process tensor access', 'gather single process tensor storages from multiple ranks into a MultiProcessTensorStorage on the destination rank']
```

Usage

```
{'create_MeshAlignmentEvaluator': 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'evaluate_mesh_alignment': 'evaluate 3D mesh alignment quality across all mesh pairs using the MeshAlignmentEvaluator evaluate method', 'run_geodist_evaluation': 'run geodesic distance evaluation between keyvertices of two meshes using vertex embedding similarity', 'review_MeshAlignmentEvaluator_evaluate': 'review the MeshAlignmentEvaluator evaluate method that computes GE and GPS metrics across mesh pairs', 'summarize_gps_calculation': 'summarize how GPS scores are computed from geodesic distances using a Gaussian kernel with sigma 0.255'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/DensePose/densepose/evaluation/tensor_storage.py

Prompts

```
['run DensePose COCO evaluation by creating DensePoseCocoEval with ground truth and detection COCO objects then calling evaluate', 'accumulate per-image per-category DensePose evaluation results into precision and recall arrays using the accumulate method', 'summarize DensePose evaluation metrics including AP and AR at various OGPS thresholds and area ranges using summarize', 'compute OGPS scores between detections and ground truth by calling computeOgps for a given image and category ID', 'configure DensePose evaluation parameters such as IoU thresholds, recall thresholds, and max detections using the Params class', 'build a DensePoseCOCOEvaluator instance for a given dataset name with distributed evaluation and optional mesh alignment', 'create a function that converts model prediction instances into a list of dicts for DensePose evaluation format', 'build a tensor storage object for DensePose evaluation from a config node specifying ram or file storage', 'evaluate mesh alignment metrics using the MeshAlignmentEvaluator to compute GE and GPS per mesh and overall', 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run geodesic distance evaluation between keyvertices of two meshes using vertex embedding similarity', 'review the MeshAlignmentEvaluator evaluate method that computes GE and GPS metrics across mesh pairs', 'summarize how GPS scores are computed from geodesic distances using a Gaussian kernel with sigma 0.255', 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'put a dictionary of named tensors into the storage and get back a record ID', 'get stored tensors by record ID from a SingleProcessTensorStorage instance', 'create a MultiProcessFileTensorStorage mapping process ranks to file paths for multi-process tensor access', 'gather single process tensor storages from multiple ranks into a MultiProcessTensorStorage on the destination rank']
```

Usage

```
{'create_SingleProcessTensorStorage': 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'put_SingleProcessTensorStorage': 'put a dictionary of named tensors into the storage and get back a record ID', 'get_SingleProcessTensorStorage': 'get stored tensors by record ID from a SingleProcessTensorStorage instance', 'create_MultiProcessFileTensorStorage': 'create a MultiProcessFileTensorStorage mapping process ranks to file paths for multi-process tensor access', 'storage_gather': 'gather single process tensor storages from multiple ranks into a MultiProcessTensorStorage on the destination rank'}
```


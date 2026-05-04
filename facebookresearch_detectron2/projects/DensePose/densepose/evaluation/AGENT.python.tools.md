# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/DensePose/densepose/evaluation/densepose_coco_evaluation.py

Prompts

```
['run DensePoseCocoEval to evaluate dense pose detection results against COCO ground truth annotations', 'compute the OGPS geodesic distance scores between dense pose detections and ground truth for an image', 'compute the mask IoU between dense pose detection masks and ground truth segmentation masks', 'extract IUV point arrays from quantized dense pose detection results for a given detection and ground truth pair', 'extract a binary mask array from a dense pose detection dictionary supporting multiple data formats', 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process model inputs and outputs to collect dense pose predictions for evaluation', 'run the DensePoseCOCOEvaluator evaluate method to compute GPS, GPSM, and segmentation metrics', 'convert dense pose chart predictor output instances into quantized evaluation dictionaries with segmentation masks', 'build a tensor storage backend for dense pose evaluation using a Detectron2 config node', 'build a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run the evaluate method to compute GE and GPS metrics across all mesh pairs', 'create a 3D mesh using create_mesh with a mesh name and device from embeddings', 'review the MeshAlignmentEvaluator evaluate method that computes geodesic errors and GPS scores per mesh pair', 'summarize the MeshAlignmentEvaluator class that evaluates 3D mesh alignment using learned vertex embeddings', 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'use SingleProcessTensorStorage put method to store a dictionary of tensors and get a record ID', 'use SingleProcessTensorStorage get method to load stored tensors by their record ID', 'create a SingleProcessFileTensorStorage that writes tensor data to a file on disk', 'use storage_gather to collect single process tensor storages from multiple ranks into one']
```

Usage

```
{'run_densepose_coco_evaluation': 'run DensePoseCocoEval to evaluate dense pose detection results against COCO ground truth annotations', 'compute_ogps_between_detections_and_gt': 'compute the OGPS geodesic distance scores between dense pose detections and ground truth for an image', 'compute_dp_iou_masks': 'compute the mask IoU between dense pose detection masks and ground truth segmentation masks', 'extract_iuv_from_quantized_results': 'extract IUV point arrays from quantized dense pose detection results for a given detection and ground truth pair', 'extract_mask_from_detection': 'extract a binary mask array from a dense pose detection dictionary supporting multiple data formats'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/evaluation/evaluator.py

Prompts

```
['run DensePoseCocoEval to evaluate dense pose detection results against COCO ground truth annotations', 'compute the OGPS geodesic distance scores between dense pose detections and ground truth for an image', 'compute the mask IoU between dense pose detection masks and ground truth segmentation masks', 'extract IUV point arrays from quantized dense pose detection results for a given detection and ground truth pair', 'extract a binary mask array from a dense pose detection dictionary supporting multiple data formats', 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process model inputs and outputs to collect dense pose predictions for evaluation', 'run the DensePoseCOCOEvaluator evaluate method to compute GPS, GPSM, and segmentation metrics', 'convert dense pose chart predictor output instances into quantized evaluation dictionaries with segmentation masks', 'build a tensor storage backend for dense pose evaluation using a Detectron2 config node', 'build a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run the evaluate method to compute GE and GPS metrics across all mesh pairs', 'create a 3D mesh using create_mesh with a mesh name and device from embeddings', 'review the MeshAlignmentEvaluator evaluate method that computes geodesic errors and GPS scores per mesh pair', 'summarize the MeshAlignmentEvaluator class that evaluates 3D mesh alignment using learned vertex embeddings', 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'use SingleProcessTensorStorage put method to store a dictionary of tensors and get a record ID', 'use SingleProcessTensorStorage get method to load stored tensors by their record ID', 'create a SingleProcessFileTensorStorage that writes tensor data to a file on disk', 'use storage_gather to collect single process tensor storages from multiple ranks into one']
```

Usage

```
{'build_DensePoseCOCOEvaluator': 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process_predictions_DensePoseCOCOEvaluator': 'process model inputs and outputs to collect dense pose predictions for evaluation', 'evaluate_DensePoseCOCOEvaluator': 'run the DensePoseCOCOEvaluator evaluate method to compute GPS, GPSM, and segmentation metrics', 'convert_densepose_chart_predictions': 'convert dense pose chart predictor output instances into quantized evaluation dictionaries with segmentation masks', 'build_densepose_evaluator_storage': 'build a tensor storage backend for dense pose evaluation using a Detectron2 config node'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/evaluation/mesh_alignment_evaluator.py

Prompts

```
['run DensePoseCocoEval to evaluate dense pose detection results against COCO ground truth annotations', 'compute the OGPS geodesic distance scores between dense pose detections and ground truth for an image', 'compute the mask IoU between dense pose detection masks and ground truth segmentation masks', 'extract IUV point arrays from quantized dense pose detection results for a given detection and ground truth pair', 'extract a binary mask array from a dense pose detection dictionary supporting multiple data formats', 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process model inputs and outputs to collect dense pose predictions for evaluation', 'run the DensePoseCOCOEvaluator evaluate method to compute GPS, GPSM, and segmentation metrics', 'convert dense pose chart predictor output instances into quantized evaluation dictionaries with segmentation masks', 'build a tensor storage backend for dense pose evaluation using a Detectron2 config node', 'build a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run the evaluate method to compute GE and GPS metrics across all mesh pairs', 'create a 3D mesh using create_mesh with a mesh name and device from embeddings', 'review the MeshAlignmentEvaluator evaluate method that computes geodesic errors and GPS scores per mesh pair', 'summarize the MeshAlignmentEvaluator class that evaluates 3D mesh alignment using learned vertex embeddings', 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'use SingleProcessTensorStorage put method to store a dictionary of tensors and get a record ID', 'use SingleProcessTensorStorage get method to load stored tensors by their record ID', 'create a SingleProcessFileTensorStorage that writes tensor data to a file on disk', 'use storage_gather to collect single process tensor storages from multiple ranks into one']
```

Usage

```
{'build_mesh_alignment_evaluator': 'build a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run_evaluate_mesh_alignment': 'run the evaluate method to compute GE and GPS metrics across all mesh pairs', 'create_mesh_from_embeddings': 'create a 3D mesh using create_mesh with a mesh name and device from embeddings', 'review_MeshAlignmentEvaluator_evaluate': 'review the MeshAlignmentEvaluator evaluate method that computes geodesic errors and GPS scores per mesh pair', 'summarize_MeshAlignmentEvaluator': 'summarize the MeshAlignmentEvaluator class that evaluates 3D mesh alignment using learned vertex embeddings'}
```

## File: facebookresearch_detectron2/projects/DensePose/densepose/evaluation/tensor_storage.py

Prompts

```
['run DensePoseCocoEval to evaluate dense pose detection results against COCO ground truth annotations', 'compute the OGPS geodesic distance scores between dense pose detections and ground truth for an image', 'compute the mask IoU between dense pose detection masks and ground truth segmentation masks', 'extract IUV point arrays from quantized dense pose detection results for a given detection and ground truth pair', 'extract a binary mask array from a dense pose detection dictionary supporting multiple data formats', 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process model inputs and outputs to collect dense pose predictions for evaluation', 'run the DensePoseCOCOEvaluator evaluate method to compute GPS, GPSM, and segmentation metrics', 'convert dense pose chart predictor output instances into quantized evaluation dictionaries with segmentation masks', 'build a tensor storage backend for dense pose evaluation using a Detectron2 config node', 'build a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run the evaluate method to compute GE and GPS metrics across all mesh pairs', 'create a 3D mesh using create_mesh with a mesh name and device from embeddings', 'review the MeshAlignmentEvaluator evaluate method that computes geodesic errors and GPS scores per mesh pair', 'summarize the MeshAlignmentEvaluator class that evaluates 3D mesh alignment using learned vertex embeddings', 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'use SingleProcessTensorStorage put method to store a dictionary of tensors and get a record ID', 'use SingleProcessTensorStorage get method to load stored tensors by their record ID', 'create a SingleProcessFileTensorStorage that writes tensor data to a file on disk', 'use storage_gather to collect single process tensor storages from multiple ranks into one']
```

Usage

```
{'create_SingleProcessTensorStorage': 'create a SingleProcessTensorStorage with a data schema and BytesIO buffer to store tensors', 'use_SingleProcessTensorStorage_put': 'use SingleProcessTensorStorage put method to store a dictionary of tensors and get a record ID', 'use_SingleProcessTensorStorage_get': 'use SingleProcessTensorStorage get method to load stored tensors by their record ID', 'create_SingleProcessFileTensorStorage': 'create a SingleProcessFileTensorStorage that writes tensor data to a file on disk', 'use_storage_gather': 'use storage_gather to collect single process tensor storages from multiple ranks into one'}
```


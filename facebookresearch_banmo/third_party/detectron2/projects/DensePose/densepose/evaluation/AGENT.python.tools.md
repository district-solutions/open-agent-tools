# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/evaluation/densepose_coco_evaluation.py

Prompts

```
['run DensePoseCocoEval with cocoGt and cocoDt to evaluate dense pose detection results on COCO dataset', 'compute OGPS scores between detections and ground truth using computeOgps method on DensePoseCocoEval', 'compute DensePose mask IoU between detections and ground truth using computeDPIoU method', 'configure DensePose evaluation parameters using Params class to set IoU thresholds and area ranges', 'summarize accumulated DensePose evaluation results using summarize method to display AP and AR metrics', 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process model inputs and outputs to collect dense pose predictions for evaluation', 'run the evaluate method on DensePoseCOCOEvaluator to compute GPS, GPSM, and segmentation metrics', 'convert dense pose chart predictor output instances to quantized dictionary results for COCO evaluation', 'build a tensor storage backend for dense pose evaluator from a Detectron2 config node', 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run the evaluate method on MeshAlignmentEvaluator to compute GE and GPS metrics across meshes', 'review the MeshAlignmentEvaluator class and its evaluate method for 3D mesh alignment evaluation', 'summarize the evaluate method that computes geodesic error and GPS scores between mesh pairs', 'refactor the evaluate method to parameterize the hardcoded Current_Mean_Distances value of 0.255', 'create a SizeData dataclass instance with dtype and shape for tensor schema definition', 'build a SingleProcessTensorStorage to store and retrieve tensors by record ID using a BinaryIO backend', 'create a SingleProcessFileTensorStorage that persists tensor records to a file on disk in binary mode', 'create a SingleProcessRamTensorStorage that keeps tensor records in memory using an io.BytesIO buffer', 'build a MultiProcessTensorStorage to access tensor storages from multiple processes indexed by rank and record ID']
```

Usage

```
{'run_densepose_evaluation': 'run DensePoseCocoEval with cocoGt and cocoDt to evaluate dense pose detection results on COCO dataset', 'compute_ogps_scores': 'compute OGPS scores between detections and ground truth using computeOgps method on DensePoseCocoEval', 'compute_dp_iou': 'compute DensePose mask IoU between detections and ground truth using computeDPIoU method', 'configure_eval_params': 'configure DensePose evaluation parameters using Params class to set IoU thresholds and area ranges', 'summarize_densepose_results': 'summarize accumulated DensePose evaluation results using summarize method to display AP and AR metrics'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/evaluation/evaluator.py

Prompts

```
['run DensePoseCocoEval with cocoGt and cocoDt to evaluate dense pose detection results on COCO dataset', 'compute OGPS scores between detections and ground truth using computeOgps method on DensePoseCocoEval', 'compute DensePose mask IoU between detections and ground truth using computeDPIoU method', 'configure DensePose evaluation parameters using Params class to set IoU thresholds and area ranges', 'summarize accumulated DensePose evaluation results using summarize method to display AP and AR metrics', 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process model inputs and outputs to collect dense pose predictions for evaluation', 'run the evaluate method on DensePoseCOCOEvaluator to compute GPS, GPSM, and segmentation metrics', 'convert dense pose chart predictor output instances to quantized dictionary results for COCO evaluation', 'build a tensor storage backend for dense pose evaluator from a Detectron2 config node', 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run the evaluate method on MeshAlignmentEvaluator to compute GE and GPS metrics across meshes', 'review the MeshAlignmentEvaluator class and its evaluate method for 3D mesh alignment evaluation', 'summarize the evaluate method that computes geodesic error and GPS scores between mesh pairs', 'refactor the evaluate method to parameterize the hardcoded Current_Mean_Distances value of 0.255', 'create a SizeData dataclass instance with dtype and shape for tensor schema definition', 'build a SingleProcessTensorStorage to store and retrieve tensors by record ID using a BinaryIO backend', 'create a SingleProcessFileTensorStorage that persists tensor records to a file on disk in binary mode', 'create a SingleProcessRamTensorStorage that keeps tensor records in memory using an io.BytesIO buffer', 'build a MultiProcessTensorStorage to access tensor storages from multiple processes indexed by rank and record ID']
```

Usage

```
{'build_DensePoseCOCOEvaluator': 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process_predictions_DensePoseCOCOEvaluator': 'process model inputs and outputs to collect dense pose predictions for evaluation', 'evaluate_DensePoseCOCOEvaluator': 'run the evaluate method on DensePoseCOCOEvaluator to compute GPS, GPSM, and segmentation metrics', 'convert_densepose_chart_predictions': 'convert dense pose chart predictor output instances to quantized dictionary results for COCO evaluation', 'build_densepose_evaluator_storage': 'build a tensor storage backend for dense pose evaluator from a Detectron2 config node'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/evaluation/mesh_alignment_evaluator.py

Prompts

```
['run DensePoseCocoEval with cocoGt and cocoDt to evaluate dense pose detection results on COCO dataset', 'compute OGPS scores between detections and ground truth using computeOgps method on DensePoseCocoEval', 'compute DensePose mask IoU between detections and ground truth using computeDPIoU method', 'configure DensePose evaluation parameters using Params class to set IoU thresholds and area ranges', 'summarize accumulated DensePose evaluation results using summarize method to display AP and AR metrics', 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process model inputs and outputs to collect dense pose predictions for evaluation', 'run the evaluate method on DensePoseCOCOEvaluator to compute GPS, GPSM, and segmentation metrics', 'convert dense pose chart predictor output instances to quantized dictionary results for COCO evaluation', 'build a tensor storage backend for dense pose evaluator from a Detectron2 config node', 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run the evaluate method on MeshAlignmentEvaluator to compute GE and GPS metrics across meshes', 'review the MeshAlignmentEvaluator class and its evaluate method for 3D mesh alignment evaluation', 'summarize the evaluate method that computes geodesic error and GPS scores between mesh pairs', 'refactor the evaluate method to parameterize the hardcoded Current_Mean_Distances value of 0.255', 'create a SizeData dataclass instance with dtype and shape for tensor schema definition', 'build a SingleProcessTensorStorage to store and retrieve tensors by record ID using a BinaryIO backend', 'create a SingleProcessFileTensorStorage that persists tensor records to a file on disk in binary mode', 'create a SingleProcessRamTensorStorage that keeps tensor records in memory using an io.BytesIO buffer', 'build a MultiProcessTensorStorage to access tensor storages from multiple processes indexed by rank and record ID']
```

Usage

```
{'create_mesh_alignment_evaluator': 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'evaluate_mesh_alignment': 'run the evaluate method on MeshAlignmentEvaluator to compute GE and GPS metrics across meshes', 'review_mesh_alignment_evaluator_class': 'review the MeshAlignmentEvaluator class and its evaluate method for 3D mesh alignment evaluation', 'summarize_evaluate_method': 'summarize the evaluate method that computes geodesic error and GPS scores between mesh pairs', 'refactor_evaluate_method': 'refactor the evaluate method to parameterize the hardcoded Current_Mean_Distances value of 0.255'}
```

## File: facebookresearch_banmo/third_party/detectron2/projects/DensePose/densepose/evaluation/tensor_storage.py

Prompts

```
['run DensePoseCocoEval with cocoGt and cocoDt to evaluate dense pose detection results on COCO dataset', 'compute OGPS scores between detections and ground truth using computeOgps method on DensePoseCocoEval', 'compute DensePose mask IoU between detections and ground truth using computeDPIoU method', 'configure DensePose evaluation parameters using Params class to set IoU thresholds and area ranges', 'summarize accumulated DensePose evaluation results using summarize method to display AP and AR metrics', 'build a DensePoseCOCOEvaluator instance to evaluate dense pose predictions on a COCO dataset', 'process model inputs and outputs to collect dense pose predictions for evaluation', 'run the evaluate method on DensePoseCOCOEvaluator to compute GPS, GPSM, and segmentation metrics', 'convert dense pose chart predictor output instances to quantized dictionary results for COCO evaluation', 'build a tensor storage backend for dense pose evaluator from a Detectron2 config node', 'create a MeshAlignmentEvaluator instance with an embedder module and optional mesh names list', 'run the evaluate method on MeshAlignmentEvaluator to compute GE and GPS metrics across meshes', 'review the MeshAlignmentEvaluator class and its evaluate method for 3D mesh alignment evaluation', 'summarize the evaluate method that computes geodesic error and GPS scores between mesh pairs', 'refactor the evaluate method to parameterize the hardcoded Current_Mean_Distances value of 0.255', 'create a SizeData dataclass instance with dtype and shape for tensor schema definition', 'build a SingleProcessTensorStorage to store and retrieve tensors by record ID using a BinaryIO backend', 'create a SingleProcessFileTensorStorage that persists tensor records to a file on disk in binary mode', 'create a SingleProcessRamTensorStorage that keeps tensor records in memory using an io.BytesIO buffer', 'build a MultiProcessTensorStorage to access tensor storages from multiple processes indexed by rank and record ID']
```

Usage

```
{'create_SizeData': 'create a SizeData dataclass instance with dtype and shape for tensor schema definition', 'build_SingleProcessTensorStorage': 'build a SingleProcessTensorStorage to store and retrieve tensors by record ID using a BinaryIO backend', 'create_SingleProcessFileTensorStorage': 'create a SingleProcessFileTensorStorage that persists tensor records to a file on disk in binary mode', 'create_SingleProcessRamTensorStorage': 'create a SingleProcessRamTensorStorage that keeps tensor records in memory using an io.BytesIO buffer', 'build_MultiProcessTensorStorage': 'build a MultiProcessTensorStorage to access tensor storages from multiple processes indexed by rank and record ID'}
```


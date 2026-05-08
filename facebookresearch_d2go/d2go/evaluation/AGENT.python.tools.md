# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/evaluation/evaluator.py

Prompts

```
['run inference on a dataset using a model and data loader with optional evaluator checkpointing', 'patch detectron2 DatasetEvaluators to add a has_finished_process method for skipping redundant processing', 'create a ResultCache utility to save and load evaluation cache data across distributed processes', 'load cached evaluation results from a pickle file with optional gathering across ranks', 'save evaluation data to a per-rank pickle cache file in the specified cache directory', 'create a PredictionCountEvaluator instance to count predictions on a hard negative dataset with no annotations', 'run the process method to collect prediction counts and confidence scores from model outputs', 'run the evaluate method to compute mean predictions per image and mean confidence per prediction', 'test the PredictionCountEvaluator in distributed mode to gather prediction counts across all processes', 'review the reset method to clear prediction counts and confidence scores between evaluation runs', 'create a MultiSemSegEvaluator instance to evaluate multiple semantic segmentation predictions for the same target dataset', 'process inputs and outputs through MultiSemSegEvaluator to evaluate multiple predictions per image with per-frame results', 'evaluate all collected predictions and return aggregated semantic segmentation results across all sub-evaluators', 'create a MultiSemSegVidEvaluator to evaluate semantic segmentation results for video clips with per-frame file names', 'create a PerImageEvaluator wrapper to evaluate each image individually and record the N most interesting results for playback']
```

Usage

```
{'run_inference_on_dataset': 'run inference on a dataset using a model and data loader with optional evaluator checkpointing', 'patch_DatasetEvaluators_has_finished_process': 'patch detectron2 DatasetEvaluators to add a has_finished_process method for skipping redundant processing', 'create_ResultCache': 'create a ResultCache utility to save and load evaluation cache data across distributed processes', 'load_ResultCache': 'load cached evaluation results from a pickle file with optional gathering across ranks', 'save_ResultCache': 'save evaluation data to a per-rank pickle cache file in the specified cache directory'}
```

## File: facebookresearch_d2go/d2go/evaluation/prediction_count_evaluation.py

Prompts

```
['run inference on a dataset using a model and data loader with optional evaluator checkpointing', 'patch detectron2 DatasetEvaluators to add a has_finished_process method for skipping redundant processing', 'create a ResultCache utility to save and load evaluation cache data across distributed processes', 'load cached evaluation results from a pickle file with optional gathering across ranks', 'save evaluation data to a per-rank pickle cache file in the specified cache directory', 'create a PredictionCountEvaluator instance to count predictions on a hard negative dataset with no annotations', 'run the process method to collect prediction counts and confidence scores from model outputs', 'run the evaluate method to compute mean predictions per image and mean confidence per prediction', 'test the PredictionCountEvaluator in distributed mode to gather prediction counts across all processes', 'review the reset method to clear prediction counts and confidence scores between evaluation runs', 'create a MultiSemSegEvaluator instance to evaluate multiple semantic segmentation predictions for the same target dataset', 'process inputs and outputs through MultiSemSegEvaluator to evaluate multiple predictions per image with per-frame results', 'evaluate all collected predictions and return aggregated semantic segmentation results across all sub-evaluators', 'create a MultiSemSegVidEvaluator to evaluate semantic segmentation results for video clips with per-frame file names', 'create a PerImageEvaluator wrapper to evaluate each image individually and record the N most interesting results for playback']
```

Usage

```
{'create_PredictionCountEvaluator': 'create a PredictionCountEvaluator instance to count predictions on a hard negative dataset with no annotations', 'run_PredictionCountEvaluator_process': 'run the process method to collect prediction counts and confidence scores from model outputs', 'run_PredictionCountEvaluator_evaluate': 'run the evaluate method to compute mean predictions per image and mean confidence per prediction', 'test_PredictionCountEvaluator_distributed': 'test the PredictionCountEvaluator in distributed mode to gather prediction counts across all processes', 'review_PredictionCountEvaluator_reset': 'review the reset method to clear prediction counts and confidence scores between evaluation runs'}
```

## File: facebookresearch_d2go/d2go/evaluation/sem_seg_evaluation.py

Prompts

```
['run inference on a dataset using a model and data loader with optional evaluator checkpointing', 'patch detectron2 DatasetEvaluators to add a has_finished_process method for skipping redundant processing', 'create a ResultCache utility to save and load evaluation cache data across distributed processes', 'load cached evaluation results from a pickle file with optional gathering across ranks', 'save evaluation data to a per-rank pickle cache file in the specified cache directory', 'create a PredictionCountEvaluator instance to count predictions on a hard negative dataset with no annotations', 'run the process method to collect prediction counts and confidence scores from model outputs', 'run the evaluate method to compute mean predictions per image and mean confidence per prediction', 'test the PredictionCountEvaluator in distributed mode to gather prediction counts across all processes', 'review the reset method to clear prediction counts and confidence scores between evaluation runs', 'create a MultiSemSegEvaluator instance to evaluate multiple semantic segmentation predictions for the same target dataset', 'process inputs and outputs through MultiSemSegEvaluator to evaluate multiple predictions per image with per-frame results', 'evaluate all collected predictions and return aggregated semantic segmentation results across all sub-evaluators', 'create a MultiSemSegVidEvaluator to evaluate semantic segmentation results for video clips with per-frame file names', 'create a PerImageEvaluator wrapper to evaluate each image individually and record the N most interesting results for playback']
```

Usage

```
{'create_MultiSemSegEvaluator': 'create a MultiSemSegEvaluator instance to evaluate multiple semantic segmentation predictions for the same target dataset', 'process_MultiSemSegEvaluator': 'process inputs and outputs through MultiSemSegEvaluator to evaluate multiple predictions per image with per-frame results', 'evaluate_MultiSemSegEvaluator': 'evaluate all collected predictions and return aggregated semantic segmentation results across all sub-evaluators', 'create_MultiSemSegVidEvaluator': 'create a MultiSemSegVidEvaluator to evaluate semantic segmentation results for video clips with per-frame file names', 'create_PerImageEvaluator': 'create a PerImageEvaluator wrapper to evaluate each image individually and record the N most interesting results for playback'}
```


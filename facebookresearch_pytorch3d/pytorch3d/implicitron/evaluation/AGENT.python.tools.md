# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/implicitron/evaluation/evaluate_new_view_synthesis.py

Prompts

```
['run eval_batch to compute PSNR, L1, IoU, and depth metrics for a new view synthesis batch', 'run summarize_nvs_eval_results to compile per-batch evaluation results into aggregate metrics for single or multi sequence tasks', 'run aggregate_nvs_results to average new view synthesis metrics across categories and scenes', 'run pretty_print_nvs_metrics to print a tabulated table of new view synthesis evaluation results', 'run flatten_nvs_results to convert a nested list of result dicts into a flat key-value dictionary', 'run the ImplicitronEvaluator to evaluate a trained model on a test dataloader and return metrics', 'create a subclass of EvaluatorBase to implement custom model evaluation logic with a run method', 'dump evaluation results to a JSON file using the _dump_to_json helper function', 'mask target image data in frame data using _get_eval_frame_data to prevent cheating during evaluation', 'review the ImplicitronEvaluator run method to understand how LPIPS metrics and batch evaluation are computed']
```

Usage

```
{'run_eval_batch': 'run eval_batch to compute PSNR, L1, IoU, and depth metrics for a new view synthesis batch', 'run_summarize_nvs_eval_results': 'run summarize_nvs_eval_results to compile per-batch evaluation results into aggregate metrics for single or multi sequence tasks', 'run_aggregate_nvs_results': 'run aggregate_nvs_results to average new view synthesis metrics across categories and scenes', 'run_pretty_print_nvs_metrics': 'run pretty_print_nvs_metrics to print a tabulated table of new view synthesis evaluation results', 'run_flatten_nvs_results': 'run flatten_nvs_results to convert a nested list of result dicts into a flat key-value dictionary'}
```

## File: facebookresearch_pytorch3d/pytorch3d/implicitron/evaluation/evaluator.py

Prompts

```
['run eval_batch to compute PSNR, L1, IoU, and depth metrics for a new view synthesis batch', 'run summarize_nvs_eval_results to compile per-batch evaluation results into aggregate metrics for single or multi sequence tasks', 'run aggregate_nvs_results to average new view synthesis metrics across categories and scenes', 'run pretty_print_nvs_metrics to print a tabulated table of new view synthesis evaluation results', 'run flatten_nvs_results to convert a nested list of result dicts into a flat key-value dictionary', 'run the ImplicitronEvaluator to evaluate a trained model on a test dataloader and return metrics', 'create a subclass of EvaluatorBase to implement custom model evaluation logic with a run method', 'dump evaluation results to a JSON file using the _dump_to_json helper function', 'mask target image data in frame data using _get_eval_frame_data to prevent cheating during evaluation', 'review the ImplicitronEvaluator run method to understand how LPIPS metrics and batch evaluation are computed']
```

Usage

```
{'run_implicitron_evaluator': 'run the ImplicitronEvaluator to evaluate a trained model on a test dataloader and return metrics', 'create_evaluator_base_subclass': 'create a subclass of EvaluatorBase to implement custom model evaluation logic with a run method', 'dump_evaluation_results_to_json': 'dump evaluation results to a JSON file using the _dump_to_json helper function', 'mask_target_frame_data': 'mask target image data in frame data using _get_eval_frame_data to prevent cheating during evaluation', 'review_implicitron_evaluator_run': 'review the ImplicitronEvaluator run method to understand how LPIPS metrics and batch evaluation are computed'}
```


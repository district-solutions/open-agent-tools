# Agent Python Tools

- repo: facebookresearch/fast3r
- repo_uri: https://github.com/facebookresearch/fast3r

## File: facebookresearch_fast3r/scripts/fast3r_re10k_pose_eval.py

Prompts

```
['run the RealEstate10K camera pose evaluation script across multiple GPUs with optional subset filtering', 'run camera pose inference on a subset of RealEstate10K video folders using a DUSt3R model on a single GPU', 'run image cropping around the principal point and resize to target resolution for DUSt3R inference', 'run a recursive config fix that replaces dust3r module references with fast3r.dust3r paths', 'run the multi-GPU RealEstate10K pose evaluation pipeline that splits folders, runs inference, and aggregates metrics', 'run the Fast3R model evaluation on ScanNet dataset using the rmvd framework with median alignment', 'create a Fast3RWrapperModel instance to wrap Fast3R for use inside the rmvd evaluation pipeline', 'replace dust3r module references with fast3r.dust3r paths in a Hydra config dictionary recursively', 'run the input_adapter method to convert a list of numpy image arrays into DUSt3R view dictionaries', 'run the output_adapter method to extract depth maps and uncertainty from Fast3R model predictions']
```

Usage

```
{'run_fast3r_re10k_pose_eval': 'run the RealEstate10K camera pose evaluation script across multiple GPUs with optional subset filtering', 'run_process_folders': 'run camera pose inference on a subset of RealEstate10K video folders using a DUSt3R model on a single GPU', 'run_crop_resize_if_necessary': 'run image cropping around the principal point and resize to target resolution for DUSt3R inference', 'run_replace_dust3r_in_config': 'run a recursive config fix that replaces dust3r module references with fast3r.dust3r paths', 'run_main': 'run the multi-GPU RealEstate10K pose evaluation pipeline that splits folders, runs inference, and aggregates metrics'}
```

## File: facebookresearch_fast3r/scripts/robustmvd_eval.py

Prompts

```
['run the RealEstate10K camera pose evaluation script across multiple GPUs with optional subset filtering', 'run camera pose inference on a subset of RealEstate10K video folders using a DUSt3R model on a single GPU', 'run image cropping around the principal point and resize to target resolution for DUSt3R inference', 'run a recursive config fix that replaces dust3r module references with fast3r.dust3r paths', 'run the multi-GPU RealEstate10K pose evaluation pipeline that splits folders, runs inference, and aggregates metrics', 'run the Fast3R model evaluation on ScanNet dataset using the rmvd framework with median alignment', 'create a Fast3RWrapperModel instance to wrap Fast3R for use inside the rmvd evaluation pipeline', 'replace dust3r module references with fast3r.dust3r paths in a Hydra config dictionary recursively', 'run the input_adapter method to convert a list of numpy image arrays into DUSt3R view dictionaries', 'run the output_adapter method to extract depth maps and uncertainty from Fast3R model predictions']
```

Usage

```
{'run_robustmvd_evaluation': 'run the Fast3R model evaluation on ScanNet dataset using the rmvd framework with median alignment', 'create_wrapper_model': 'create a Fast3RWrapperModel instance to wrap Fast3R for use inside the rmvd evaluation pipeline', 'replace_dust3r_in_config': 'replace dust3r module references with fast3r.dust3r paths in a Hydra config dictionary recursively', 'run_input_adapter': 'run the input_adapter method to convert a list of numpy image arrays into DUSt3R view dictionaries', 'run_output_adapter': 'run the output_adapter method to extract depth maps and uncertainty from Fast3R model predictions'}
```


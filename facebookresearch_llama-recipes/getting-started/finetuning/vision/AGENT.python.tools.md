# Agent Python Tools

- repo: facebookresearch/llama-recipes
- repo_uri: https://github.com/facebookresearch/llama-recipes.git

## File: facebookresearch_llama-recipes/getting-started/finetuning/vision/evaluate.py

Prompts

```
['run batch evaluation of a vision-language model on W2 tax form images using vLLM server', 'run sequential evaluation of a vision-language model on W2 tax form images for debugging', 'extract and parse JSON from an LLM response with robust error handling and multiple strategies', 'clean common JSON formatting issues from LLM responses including markdown blocks and control characters', 'calculate accuracy metrics and per-field accuracy for W2 form extraction predictions against ground truth', 'run the script to prepare a W-2 dataset with custom train-test splits and save it to disk', 'remove the top-level gt_parse wrapper from ground_truth JSON and flatten the fields', 'create custom train-test splits from a HuggingFace dataset with a configurable ratio and seed', 'apply a custom prompt to all examples in the dataset for vision model fine-tuning', 'validate a HuggingFace dataset has required columns and load it with error handling']
```

Usage

```
{'run_vllm_batch_evaluation': 'run batch evaluation of a vision-language model on W2 tax form images using vLLM server', 'run_vllm_sequential_evaluation': 'run sequential evaluation of a vision-language model on W2 tax form images for debugging', 'extract_json_from_response': 'extract and parse JSON from an LLM response with robust error handling and multiple strategies', 'clean_json_string': 'clean common JSON formatting issues from LLM responses including markdown blocks and control characters', 'calculate_metrics': 'calculate accuracy metrics and per-field accuracy for W2 form extraction predictions against ground truth'}
```

## File: facebookresearch_llama-recipes/getting-started/finetuning/vision/prepare_w2_dataset.py

Prompts

```
['run batch evaluation of a vision-language model on W2 tax form images using vLLM server', 'run sequential evaluation of a vision-language model on W2 tax form images for debugging', 'extract and parse JSON from an LLM response with robust error handling and multiple strategies', 'clean common JSON formatting issues from LLM responses including markdown blocks and control characters', 'calculate accuracy metrics and per-field accuracy for W2 form extraction predictions against ground truth', 'run the script to prepare a W-2 dataset with custom train-test splits and save it to disk', 'remove the top-level gt_parse wrapper from ground_truth JSON and flatten the fields', 'create custom train-test splits from a HuggingFace dataset with a configurable ratio and seed', 'apply a custom prompt to all examples in the dataset for vision model fine-tuning', 'validate a HuggingFace dataset has required columns and load it with error handling']
```

Usage

```
{'run_prepare_w2_dataset': 'run the script to prepare a W-2 dataset with custom train-test splits and save it to disk', 'remove_gt_parse_wrapper': 'remove the top-level gt_parse wrapper from ground_truth JSON and flatten the fields', 'create_custom_splits': 'create custom train-test splits from a HuggingFace dataset with a configurable ratio and seed', 'apply_prompt_transformation': 'apply a custom prompt to all examples in the dataset for vision model fine-tuning', 'validate_and_load_dataset': 'validate a HuggingFace dataset has required columns and load it with error handling'}
```


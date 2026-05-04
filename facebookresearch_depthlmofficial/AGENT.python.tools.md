# Agent Python Tools

- repo: facebookresearch/depthlmofficial
- repo_uri: https://github.com/facebookresearch/depthlm_official

## File: facebookresearch_depthlmofficial/eval.py

Prompts

```
['run the DepthLM evaluation script on a dataset using a specified model path and image folder', 'run inference with a Pixtral-based DepthLM model on visual reasoning examples with image inputs', 'run inference with a Qwen2.5-VL-based DepthLM model using system prompts and batched image-text inputs', 'convert a dataset example into Qwen chat messages with system prompt and image-text content', 'convert a dataset example into Pixtral chat messages with configurable image-before-text ordering', 'run supervised fine-tuning training for vision-language models using the SFTTrainer with custom collate functions', 'convert a dataset example into messages format with system, user, and assistant roles for training', 'collate a batch of examples into input_ids, labels, and image embeddings for model training', 'pad a list of tensors to the same length with right or left padding strategy', 'configure the Pixtral vision tower with compute dtype and device settings for model training']
```

Usage

```
{'run_depthlm_evaluation': 'run the DepthLM evaluation script on a dataset using a specified model path and image folder', 'run_pixtral_inference': 'run inference with a Pixtral-based DepthLM model on visual reasoning examples with image inputs', 'run_qwen_inference': 'run inference with a Qwen2.5-VL-based DepthLM model using system prompts and batched image-text inputs', 'convert_example_for_qwen': 'convert a dataset example into Qwen chat messages with system prompt and image-text content', 'convert_example_for_pixtral': 'convert a dataset example into Pixtral chat messages with configurable image-before-text ordering'}
```

## File: facebookresearch_depthlmofficial/train.py

Prompts

```
['run the DepthLM evaluation script on a dataset using a specified model path and image folder', 'run inference with a Pixtral-based DepthLM model on visual reasoning examples with image inputs', 'run inference with a Qwen2.5-VL-based DepthLM model using system prompts and batched image-text inputs', 'convert a dataset example into Qwen chat messages with system prompt and image-text content', 'convert a dataset example into Pixtral chat messages with configurable image-before-text ordering', 'run supervised fine-tuning training for vision-language models using the SFTTrainer with custom collate functions', 'convert a dataset example into messages format with system, user, and assistant roles for training', 'collate a batch of examples into input_ids, labels, and image embeddings for model training', 'pad a list of tensors to the same length with right or left padding strategy', 'configure the Pixtral vision tower with compute dtype and device settings for model training']
```

Usage

```
{'run_sft_training': 'run supervised fine-tuning training for vision-language models using the SFTTrainer with custom collate functions', 'convert_example_messages': 'convert a dataset example into messages format with system, user, and assistant roles for training', 'collate_fn_batch': 'collate a batch of examples into input_ids, labels, and image embeddings for model training', 'pad_sequence_tensors': 'pad a list of tensors to the same length with right or left padding strategy', 'configure_pixtral_vision': 'configure the Pixtral vision tower with compute dtype and device settings for model training'}
```


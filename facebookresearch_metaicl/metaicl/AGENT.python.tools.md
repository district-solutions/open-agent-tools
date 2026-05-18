# Agent Python Tools

- repo: facebookresearch/metaicl
- repo_uri: https://github.com/facebookresearch/metaicl

## File: facebookresearch_metaicl/metaicl/data.py

Prompts

```
['create a MetaICLData instance with a tokenizer and demonstration settings for in-context learning', 'get a PyTorch DataLoader from tensorized inputs with random or sequential sampling', 'tensorize train and test data into input_ids, attention_mask, and token_type_ids tensors', 'evaluate predictions against ground truths and compute accuracy or F1 score for classification', 'preprocess a single sentence pair into tokenized input_ids, attention_mask, and token_type_ids', 'load a pretrained GPT-2 or GPT-J causal language model from HuggingFace or a local checkpoint file', 'train the loaded MetaICL model on a dataset for a specified number of steps with gradient accumulation', 'run inference on a dataset to compute per-sample losses using the loaded model in evaluation mode', 'generate zero-shot predictions from computed losses by selecting the option with the lowest loss', 'configure an Adafactor, AdamW, or 8-bit Adam optimizer with optional FP16 and learning rate scheduling']
```

Usage

```
{'create_MetaICLData': 'create a MetaICLData instance with a tokenizer and demonstration settings for in-context learning', 'get_dataloader': 'get a PyTorch DataLoader from tensorized inputs with random or sequential sampling', 'tensorize': 'tensorize train and test data into input_ids, attention_mask, and token_type_ids tensors', 'evaluate': 'evaluate predictions against ground truths and compute accuracy or F1 score for classification', 'prepro_sentence_pair_single': 'preprocess a single sentence pair into tokenized input_ids, attention_mask, and token_type_ids'}
```

## File: facebookresearch_metaicl/metaicl/model.py

Prompts

```
['create a MetaICLData instance with a tokenizer and demonstration settings for in-context learning', 'get a PyTorch DataLoader from tensorized inputs with random or sequential sampling', 'tensorize train and test data into input_ids, attention_mask, and token_type_ids tensors', 'evaluate predictions against ground truths and compute accuracy or F1 score for classification', 'preprocess a single sentence pair into tokenized input_ids, attention_mask, and token_type_ids', 'load a pretrained GPT-2 or GPT-J causal language model from HuggingFace or a local checkpoint file', 'train the loaded MetaICL model on a dataset for a specified number of steps with gradient accumulation', 'run inference on a dataset to compute per-sample losses using the loaded model in evaluation mode', 'generate zero-shot predictions from computed losses by selecting the option with the lowest loss', 'configure an Adafactor, AdamW, or 8-bit Adam optimizer with optional FP16 and learning rate scheduling']
```

Usage

```
{'load_gpt_model': 'load a pretrained GPT-2 or GPT-J causal language model from HuggingFace or a local checkpoint file', 'train_model': 'train the loaded MetaICL model on a dataset for a specified number of steps with gradient accumulation', 'run_inference': 'run inference on a dataset to compute per-sample losses using the loaded model in evaluation mode', 'generate_predictions': 'generate zero-shot predictions from computed losses by selecting the option with the lowest loss', 'setup_optimizer': 'configure an Adafactor, AdamW, or 8-bit Adam optimizer with optional FP16 and learning rate scheduling'}
```


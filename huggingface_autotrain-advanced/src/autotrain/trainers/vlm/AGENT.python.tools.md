# Agent Python Tools

- repo: huggingface/autotrain-advanced
- repo_uri: https://github.com/huggingface/autotrain-advanced.git

## File: huggingface_autotrain-advanced/src/autotrain/trainers/vlm/__main__.py

Prompts

```
['run VLM training by passing a training config JSON file path via --training_config argument', 'run VQA training by setting trainer to vqa in the training config JSON file', 'run captioning training by setting trainer to captioning in the training config JSON file', 'review the train function that validates model support and dispatches to vqa or captioning trainers', 'review the parse_args function that defines the --training_config CLI argument', 'run the train function to train a vision language model using a config with dataset paths and model settings', 'use collate_fn to tokenize prompts, labels, and images into processor tokens for a VLM batch', 'load training and validation datasets from disk or Hugging Face Hub using the train function', 'initialize an AutoProcessor for a pretrained VLM model with trust remote code enabled', 'build a Hugging Face Trainer with a VLM model, datasets, and a custom data collator', 'get the target modules for LoRA fine-tuning from a config object', 'create a model card markdown string with peft, dataset, and base model tags', 'check if a Hugging Face model architecture is supported for VLM training', 'configure transformer training arguments including batch size, learning rate, and gradient checkpointing', 'merge a PEFT adapter into a base PaliGemma model and save the merged model']
```

Usage

```
{'run_vlm_training': 'run VLM training by passing a training config JSON file path via --training_config argument', 'run_vqa_training': 'run VQA training by setting trainer to vqa in the training config JSON file', 'run_captioning_training': 'run captioning training by setting trainer to captioning in the training config JSON file', 'review_train_function': 'review the train function that validates model support and dispatches to vqa or captioning trainers', 'review_parse_args': 'review the parse_args function that defines the --training_config CLI argument'}
```

## File: huggingface_autotrain-advanced/src/autotrain/trainers/vlm/train_vlm_generic.py

Prompts

```
['run VLM training by passing a training config JSON file path via --training_config argument', 'run VQA training by setting trainer to vqa in the training config JSON file', 'run captioning training by setting trainer to captioning in the training config JSON file', 'review the train function that validates model support and dispatches to vqa or captioning trainers', 'review the parse_args function that defines the --training_config CLI argument', 'run the train function to train a vision language model using a config with dataset paths and model settings', 'use collate_fn to tokenize prompts, labels, and images into processor tokens for a VLM batch', 'load training and validation datasets from disk or Hugging Face Hub using the train function', 'initialize an AutoProcessor for a pretrained VLM model with trust remote code enabled', 'build a Hugging Face Trainer with a VLM model, datasets, and a custom data collator', 'get the target modules for LoRA fine-tuning from a config object', 'create a model card markdown string with peft, dataset, and base model tags', 'check if a Hugging Face model architecture is supported for VLM training', 'configure transformer training arguments including batch size, learning rate, and gradient checkpointing', 'merge a PEFT adapter into a base PaliGemma model and save the merged model']
```

Usage

```
{'train_vlm_model': 'run the train function to train a vision language model using a config with dataset paths and model settings', 'collate_vlm_examples': 'use collate_fn to tokenize prompts, labels, and images into processor tokens for a VLM batch', 'load_vlm_dataset': 'load training and validation datasets from disk or Hugging Face Hub using the train function', 'configure_vlm_processor': 'initialize an AutoProcessor for a pretrained VLM model with trust remote code enabled', 'create_vlm_trainer': 'build a Hugging Face Trainer with a VLM model, datasets, and a custom data collator'}
```

## File: huggingface_autotrain-advanced/src/autotrain/trainers/vlm/utils.py

Prompts

```
['run VLM training by passing a training config JSON file path via --training_config argument', 'run VQA training by setting trainer to vqa in the training config JSON file', 'run captioning training by setting trainer to captioning in the training config JSON file', 'review the train function that validates model support and dispatches to vqa or captioning trainers', 'review the parse_args function that defines the --training_config CLI argument', 'run the train function to train a vision language model using a config with dataset paths and model settings', 'use collate_fn to tokenize prompts, labels, and images into processor tokens for a VLM batch', 'load training and validation datasets from disk or Hugging Face Hub using the train function', 'initialize an AutoProcessor for a pretrained VLM model with trust remote code enabled', 'build a Hugging Face Trainer with a VLM model, datasets, and a custom data collator', 'get the target modules for LoRA fine-tuning from a config object', 'create a model card markdown string with peft, dataset, and base model tags', 'check if a Hugging Face model architecture is supported for VLM training', 'configure transformer training arguments including batch size, learning rate, and gradient checkpointing', 'merge a PEFT adapter into a base PaliGemma model and save the merged model']
```

Usage

```
{'get_target_modules': 'get the target modules for LoRA fine-tuning from a config object', 'create_model_card': 'create a model card markdown string with peft, dataset, and base model tags', 'check_model_support': 'check if a Hugging Face model architecture is supported for VLM training', 'configure_training_args': 'configure transformer training arguments including batch size, learning rate, and gradient checkpointing', 'merge_adapter': 'merge a PEFT adapter into a base PaliGemma model and save the merged model'}
```


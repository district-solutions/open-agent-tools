# Agent Python Tools

- repo: facebookresearch/metaquery
- repo_uri: https://github.com/facebookresearch/metaquery

## File: facebookresearch_metaquery/app.py

Prompts

```
['run the gradio demo app with a checkpoint path to launch the MetaQuery image generation UI', 'run the MetaQuery pipeline to generate images from text prompts and optional input images via CLI', 'review the randomize_seed_fn function that sets random, numpy, and torch seeds for reproducibility', 'review the process_interleaved_vision_language function that generates images using the MetaQuery pipeline with text and image inputs', 'review the update_negative_prompt function that returns preset negative prompt strings by name', 'create train and eval datasets from CC12M, Inst2M, or OmniEdit with image transforms and collation', 'build a function that removes all keys from a batch dict except the specified ones', 'create an image-to-image batch processor that applies target transforms and 10% random blank image masking', 'create a text-to-image batch processor that applies target transforms and 10% random caption masking', 'build a collate function that stacks targets and tokenizes captions with optional input images', 'run evaluation on multiple datasets using MetaQueryTrainer with automatic metric key prefixing', 'create a custom evaluation DataLoader with persistent workers and a custom data collator', 'run a prediction step that samples images using guidance scale and logs them to W&B', 'review the _maybe_log_save_evaluate method that detects loss and gradient norm spikes to stop training', 'create a TrainerCallback that prints model parameter statistics and connector dimensions at training start', 'seed the random number generators for python numpy and torch with a given seed value', 'find the newest model checkpoint in a directory by checking for pt safetensors or pth files', 'resolve relative output data and logging directories to absolute paths using a base directory', 'override training argument attributes from a YAML config file specified in the override args', 'wrap a HuggingFace processor to extract and squeeze pixel values from a tensor input']
```

Usage

```
{'run_gradio_demo': 'run the gradio demo app with a checkpoint path to launch the MetaQuery image generation UI', 'run_image_generation': 'run the MetaQuery pipeline to generate images from text prompts and optional input images via CLI', 'review_randomize_seed_fn': 'review the randomize_seed_fn function that sets random, numpy, and torch seeds for reproducibility', 'review_process_interleaved_vision_language': 'review the process_interleaved_vision_language function that generates images using the MetaQuery pipeline with text and image inputs', 'review_update_negative_prompt': 'review the update_negative_prompt function that returns preset negative prompt strings by name'}
```

## File: facebookresearch_metaquery/dataset.py

Prompts

```
['run the gradio demo app with a checkpoint path to launch the MetaQuery image generation UI', 'run the MetaQuery pipeline to generate images from text prompts and optional input images via CLI', 'review the randomize_seed_fn function that sets random, numpy, and torch seeds for reproducibility', 'review the process_interleaved_vision_language function that generates images using the MetaQuery pipeline with text and image inputs', 'review the update_negative_prompt function that returns preset negative prompt strings by name', 'create train and eval datasets from CC12M, Inst2M, or OmniEdit with image transforms and collation', 'build a function that removes all keys from a batch dict except the specified ones', 'create an image-to-image batch processor that applies target transforms and 10% random blank image masking', 'create a text-to-image batch processor that applies target transforms and 10% random caption masking', 'build a collate function that stacks targets and tokenizes captions with optional input images', 'run evaluation on multiple datasets using MetaQueryTrainer with automatic metric key prefixing', 'create a custom evaluation DataLoader with persistent workers and a custom data collator', 'run a prediction step that samples images using guidance scale and logs them to W&B', 'review the _maybe_log_save_evaluate method that detects loss and gradient norm spikes to stop training', 'create a TrainerCallback that prints model parameter statistics and connector dimensions at training start', 'seed the random number generators for python numpy and torch with a given seed value', 'find the newest model checkpoint in a directory by checking for pt safetensors or pth files', 'resolve relative output data and logging directories to absolute paths using a base directory', 'override training argument attributes from a YAML config file specified in the override args', 'wrap a HuggingFace processor to extract and squeeze pixel values from a tensor input']
```

Usage

```
{'get_train_datasets': 'create train and eval datasets from CC12M, Inst2M, or OmniEdit with image transforms and collation', 'delete_keys_except': 'build a function that removes all keys from a batch dict except the specified ones', 'i2i_process_fn': 'create an image-to-image batch processor that applies target transforms and 10% random blank image masking', 't2i_process_fn': 'create a text-to-image batch processor that applies target transforms and 10% random caption masking', 'collate_fn': 'build a collate function that stacks targets and tokenizes captions with optional input images'}
```

## File: facebookresearch_metaquery/trainer.py

Prompts

```
['run the gradio demo app with a checkpoint path to launch the MetaQuery image generation UI', 'run the MetaQuery pipeline to generate images from text prompts and optional input images via CLI', 'review the randomize_seed_fn function that sets random, numpy, and torch seeds for reproducibility', 'review the process_interleaved_vision_language function that generates images using the MetaQuery pipeline with text and image inputs', 'review the update_negative_prompt function that returns preset negative prompt strings by name', 'create train and eval datasets from CC12M, Inst2M, or OmniEdit with image transforms and collation', 'build a function that removes all keys from a batch dict except the specified ones', 'create an image-to-image batch processor that applies target transforms and 10% random blank image masking', 'create a text-to-image batch processor that applies target transforms and 10% random caption masking', 'build a collate function that stacks targets and tokenizes captions with optional input images', 'run evaluation on multiple datasets using MetaQueryTrainer with automatic metric key prefixing', 'create a custom evaluation DataLoader with persistent workers and a custom data collator', 'run a prediction step that samples images using guidance scale and logs them to W&B', 'review the _maybe_log_save_evaluate method that detects loss and gradient norm spikes to stop training', 'create a TrainerCallback that prints model parameter statistics and connector dimensions at training start', 'seed the random number generators for python numpy and torch with a given seed value', 'find the newest model checkpoint in a directory by checking for pt safetensors or pth files', 'resolve relative output data and logging directories to absolute paths using a base directory', 'override training argument attributes from a YAML config file specified in the override args', 'wrap a HuggingFace processor to extract and squeeze pixel values from a tensor input']
```

Usage

```
{'run_evaluation_with_metaquery_trainer': 'run evaluation on multiple datasets using MetaQueryTrainer with automatic metric key prefixing', 'create_custom_eval_dataloader': 'create a custom evaluation DataLoader with persistent workers and a custom data collator', 'run_prediction_step_with_image_sampling': 'run a prediction step that samples images using guidance scale and logs them to W&B', 'review_loss_spike_detection': 'review the _maybe_log_save_evaluate method that detects loss and gradient norm spikes to stop training', 'create_trainer_callback_for_param_logging': 'create a TrainerCallback that prints model parameter statistics and connector dimensions at training start'}
```

## File: facebookresearch_metaquery/trainer_utils.py

Prompts

```
['run the gradio demo app with a checkpoint path to launch the MetaQuery image generation UI', 'run the MetaQuery pipeline to generate images from text prompts and optional input images via CLI', 'review the randomize_seed_fn function that sets random, numpy, and torch seeds for reproducibility', 'review the process_interleaved_vision_language function that generates images using the MetaQuery pipeline with text and image inputs', 'review the update_negative_prompt function that returns preset negative prompt strings by name', 'create train and eval datasets from CC12M, Inst2M, or OmniEdit with image transforms and collation', 'build a function that removes all keys from a batch dict except the specified ones', 'create an image-to-image batch processor that applies target transforms and 10% random blank image masking', 'create a text-to-image batch processor that applies target transforms and 10% random caption masking', 'build a collate function that stacks targets and tokenizes captions with optional input images', 'run evaluation on multiple datasets using MetaQueryTrainer with automatic metric key prefixing', 'create a custom evaluation DataLoader with persistent workers and a custom data collator', 'run a prediction step that samples images using guidance scale and logs them to W&B', 'review the _maybe_log_save_evaluate method that detects loss and gradient norm spikes to stop training', 'create a TrainerCallback that prints model parameter statistics and connector dimensions at training start', 'seed the random number generators for python numpy and torch with a given seed value', 'find the newest model checkpoint in a directory by checking for pt safetensors or pth files', 'resolve relative output data and logging directories to absolute paths using a base directory', 'override training argument attributes from a YAML config file specified in the override args', 'wrap a HuggingFace processor to extract and squeeze pixel values from a tensor input']
```

Usage

```
{'seed_everything': 'seed the random number generators for python numpy and torch with a given seed value', 'find_newest_checkpoint': 'find the newest model checkpoint in a directory by checking for pt safetensors or pth files', 'get_full_dirs': 'resolve relative output data and logging directories to absolute paths using a base directory', 'possible_override_args': 'override training argument attributes from a YAML config file specified in the override args', 'ProcessorWrapper': 'wrap a HuggingFace processor to extract and squeeze pixel values from a tensor input'}
```


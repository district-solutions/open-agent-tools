# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/examples/contrastive-image-text/clip_media_pipe.py

Prompts

```
['create a ClipMediaPipe instance to build a media pipeline for CLIP image-text contrastive training on HPU', 'define the media pipe graph that decodes images and applies crop mirror normalization for CLIP', 'create a read_image_text_from_dataset class to read image paths and text tokens from a CLIP dataset', 'implement the iterator protocol on read_image_text_from_dataset to batch image paths with input IDs and attention masks', 'generate output tensor info for the custom reader specifying batch size and text max length dimensions', 'create a HabanaDataloaderTrainer subclass of GaudiTrainer that uses MediaApiDataLoader for Habana media pipeline training', 'build a training dataloader using MediaApiDataLoader with Habana-specific sampler and collator configuration', 'build an evaluation dataloader using MediaApiDataLoader with sequential or shard sampling for distributed runs', 'build a test dataloader using MediaApiDataLoader with the same batch size as evaluation', 'review the _get_train_sampler method that returns RandomSampler, DistributedSampler, or LengthGroupedSampler based on world size and lazy mode', 'run the BridgeTower contrastive image-text model training script on Habana Gaudi hardware', 'create a PyTorch Transform module that resizes, crops, and normalizes images for BridgeTower', 'build a collate function that stacks pixel values, input IDs, and attention masks for batch training', 'tokenize image caption text into input IDs and attention masks with max length truncation', 'transform image data from bytes, paths, or PIL objects into normalized tensors for the model', 'train a CLIP-like dual encoder model using GaudiTrainer on Habana Gaudi hardware', 'evaluate a trained CLIP contrastive image-text model using GaudiTrainer on Habana hardware', 'freeze the vision model or text model parameters before training a CLIP model', 'configure GaudiTrainingArguments and GaudiConfig for mixed-precision CLIP training on Habana', 'preprocess image-caption datasets by tokenizing captions and applying image transformations for CLIP training']
```

Usage

```
{'create_clip_mediapipe': 'create a ClipMediaPipe instance to build a media pipeline for CLIP image-text contrastive training on HPU', 'define_mediapipe_graph': 'define the media pipe graph that decodes images and applies crop mirror normalization for CLIP', 'create_custom_reader': 'create a read_image_text_from_dataset class to read image paths and text tokens from a CLIP dataset', 'implement_reader_iterator': 'implement the iterator protocol on read_image_text_from_dataset to batch image paths with input IDs and attention masks', 'generate_reader_output_info': 'generate output tensor info for the custom reader specifying batch size and text max length dimensions'}
```

## File: huggingface_optimum-habana/examples/contrastive-image-text/habana_dataloader_trainer.py

Prompts

```
['create a ClipMediaPipe instance to build a media pipeline for CLIP image-text contrastive training on HPU', 'define the media pipe graph that decodes images and applies crop mirror normalization for CLIP', 'create a read_image_text_from_dataset class to read image paths and text tokens from a CLIP dataset', 'implement the iterator protocol on read_image_text_from_dataset to batch image paths with input IDs and attention masks', 'generate output tensor info for the custom reader specifying batch size and text max length dimensions', 'create a HabanaDataloaderTrainer subclass of GaudiTrainer that uses MediaApiDataLoader for Habana media pipeline training', 'build a training dataloader using MediaApiDataLoader with Habana-specific sampler and collator configuration', 'build an evaluation dataloader using MediaApiDataLoader with sequential or shard sampling for distributed runs', 'build a test dataloader using MediaApiDataLoader with the same batch size as evaluation', 'review the _get_train_sampler method that returns RandomSampler, DistributedSampler, or LengthGroupedSampler based on world size and lazy mode', 'run the BridgeTower contrastive image-text model training script on Habana Gaudi hardware', 'create a PyTorch Transform module that resizes, crops, and normalizes images for BridgeTower', 'build a collate function that stacks pixel values, input IDs, and attention masks for batch training', 'tokenize image caption text into input IDs and attention masks with max length truncation', 'transform image data from bytes, paths, or PIL objects into normalized tensors for the model', 'train a CLIP-like dual encoder model using GaudiTrainer on Habana Gaudi hardware', 'evaluate a trained CLIP contrastive image-text model using GaudiTrainer on Habana hardware', 'freeze the vision model or text model parameters before training a CLIP model', 'configure GaudiTrainingArguments and GaudiConfig for mixed-precision CLIP training on Habana', 'preprocess image-caption datasets by tokenizing captions and applying image transformations for CLIP training']
```

Usage

```
{'create_HabanaDataloaderTrainer': 'create a HabanaDataloaderTrainer subclass of GaudiTrainer that uses MediaApiDataLoader for Habana media pipeline training', 'build_get_train_dataloader': 'build a training dataloader using MediaApiDataLoader with Habana-specific sampler and collator configuration', 'build_get_eval_dataloader': 'build an evaluation dataloader using MediaApiDataLoader with sequential or shard sampling for distributed runs', 'build_get_test_dataloader': 'build a test dataloader using MediaApiDataLoader with the same batch size as evaluation', 'review_get_train_sampler': 'review the _get_train_sampler method that returns RandomSampler, DistributedSampler, or LengthGroupedSampler based on world size and lazy mode'}
```

## File: huggingface_optimum-habana/examples/contrastive-image-text/run_bridgetower.py

Prompts

```
['create a ClipMediaPipe instance to build a media pipeline for CLIP image-text contrastive training on HPU', 'define the media pipe graph that decodes images and applies crop mirror normalization for CLIP', 'create a read_image_text_from_dataset class to read image paths and text tokens from a CLIP dataset', 'implement the iterator protocol on read_image_text_from_dataset to batch image paths with input IDs and attention masks', 'generate output tensor info for the custom reader specifying batch size and text max length dimensions', 'create a HabanaDataloaderTrainer subclass of GaudiTrainer that uses MediaApiDataLoader for Habana media pipeline training', 'build a training dataloader using MediaApiDataLoader with Habana-specific sampler and collator configuration', 'build an evaluation dataloader using MediaApiDataLoader with sequential or shard sampling for distributed runs', 'build a test dataloader using MediaApiDataLoader with the same batch size as evaluation', 'review the _get_train_sampler method that returns RandomSampler, DistributedSampler, or LengthGroupedSampler based on world size and lazy mode', 'run the BridgeTower contrastive image-text model training script on Habana Gaudi hardware', 'create a PyTorch Transform module that resizes, crops, and normalizes images for BridgeTower', 'build a collate function that stacks pixel values, input IDs, and attention masks for batch training', 'tokenize image caption text into input IDs and attention masks with max length truncation', 'transform image data from bytes, paths, or PIL objects into normalized tensors for the model', 'train a CLIP-like dual encoder model using GaudiTrainer on Habana Gaudi hardware', 'evaluate a trained CLIP contrastive image-text model using GaudiTrainer on Habana hardware', 'freeze the vision model or text model parameters before training a CLIP model', 'configure GaudiTrainingArguments and GaudiConfig for mixed-precision CLIP training on Habana', 'preprocess image-caption datasets by tokenizing captions and applying image transformations for CLIP training']
```

Usage

```
{'run_bridgetower_training': 'run the BridgeTower contrastive image-text model training script on Habana Gaudi hardware', 'create_transform_module': 'create a PyTorch Transform module that resizes, crops, and normalizes images for BridgeTower', 'build_collate_fn': 'build a collate function that stacks pixel values, input IDs, and attention masks for batch training', 'tokenize_captions': 'tokenize image caption text into input IDs and attention masks with max length truncation', 'transform_images': 'transform image data from bytes, paths, or PIL objects into normalized tensors for the model'}
```

## File: huggingface_optimum-habana/examples/contrastive-image-text/run_clip.py

Prompts

```
['create a ClipMediaPipe instance to build a media pipeline for CLIP image-text contrastive training on HPU', 'define the media pipe graph that decodes images and applies crop mirror normalization for CLIP', 'create a read_image_text_from_dataset class to read image paths and text tokens from a CLIP dataset', 'implement the iterator protocol on read_image_text_from_dataset to batch image paths with input IDs and attention masks', 'generate output tensor info for the custom reader specifying batch size and text max length dimensions', 'create a HabanaDataloaderTrainer subclass of GaudiTrainer that uses MediaApiDataLoader for Habana media pipeline training', 'build a training dataloader using MediaApiDataLoader with Habana-specific sampler and collator configuration', 'build an evaluation dataloader using MediaApiDataLoader with sequential or shard sampling for distributed runs', 'build a test dataloader using MediaApiDataLoader with the same batch size as evaluation', 'review the _get_train_sampler method that returns RandomSampler, DistributedSampler, or LengthGroupedSampler based on world size and lazy mode', 'run the BridgeTower contrastive image-text model training script on Habana Gaudi hardware', 'create a PyTorch Transform module that resizes, crops, and normalizes images for BridgeTower', 'build a collate function that stacks pixel values, input IDs, and attention masks for batch training', 'tokenize image caption text into input IDs and attention masks with max length truncation', 'transform image data from bytes, paths, or PIL objects into normalized tensors for the model', 'train a CLIP-like dual encoder model using GaudiTrainer on Habana Gaudi hardware', 'evaluate a trained CLIP contrastive image-text model using GaudiTrainer on Habana hardware', 'freeze the vision model or text model parameters before training a CLIP model', 'configure GaudiTrainingArguments and GaudiConfig for mixed-precision CLIP training on Habana', 'preprocess image-caption datasets by tokenizing captions and applying image transformations for CLIP training']
```

Usage

```
{'train_clip_contrastive_model': 'train a CLIP-like dual encoder model using GaudiTrainer on Habana Gaudi hardware', 'evaluate_clip_model': 'evaluate a trained CLIP contrastive image-text model using GaudiTrainer on Habana hardware', 'freeze_vision_or_text_encoder': 'freeze the vision model or text model parameters before training a CLIP model', 'configure_gaudi_training_args': 'configure GaudiTrainingArguments and GaudiConfig for mixed-precision CLIP training on Habana', 'preprocess_clip_dataset': 'preprocess image-caption datasets by tokenizing captions and applying image transformations for CLIP training'}
```


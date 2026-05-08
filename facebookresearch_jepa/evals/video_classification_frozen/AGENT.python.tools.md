# Agent Python Tools

- repo: facebookresearch/jepa
- repo_uri: https://github.com/facebookresearch/jepa

## File: facebookresearch_jepa/evals/video_classification_frozen/eval.py

Prompts

```
['run the main evaluation loop to train a frozen video classification model on a dataset', 'run one training or evaluation epoch with a frozen encoder and trainable classifier', 'load a pretrained vision transformer encoder from a checkpoint file for video classification', 'create a distributed dataloader for video classification with configurable transforms and segment sampling', 'initialize an AdamW optimizer with warmup cosine learning rate and weight decay schedulers', 'create a FrameAggregation module to process each video frame independently and concatenate all tokens', 'create a ClipAggregation module to process each video clip independently and concatenate all tokens', 'create a VideoTransform object with random resize, flip, auto augment, and random erasing for training', 'create an EvalVideoTransform object to sample multiple spatial views of each video clip for evaluation', 'create video transforms using make_transforms for training or multi-view evaluation pipelines']
```

Usage

```
{'run_video_classification_eval': 'run the main evaluation loop to train a frozen video classification model on a dataset', 'run_one_epoch_training': 'run one training or evaluation epoch with a frozen encoder and trainable classifier', 'load_pretrained_encoder': 'load a pretrained vision transformer encoder from a checkpoint file for video classification', 'make_video_dataloader': 'create a distributed dataloader for video classification with configurable transforms and segment sampling', 'init_optimizer_schedulers': 'initialize an AdamW optimizer with warmup cosine learning rate and weight decay schedulers'}
```

## File: facebookresearch_jepa/evals/video_classification_frozen/utils.py

Prompts

```
['run the main evaluation loop to train a frozen video classification model on a dataset', 'run one training or evaluation epoch with a frozen encoder and trainable classifier', 'load a pretrained vision transformer encoder from a checkpoint file for video classification', 'create a distributed dataloader for video classification with configurable transforms and segment sampling', 'initialize an AdamW optimizer with warmup cosine learning rate and weight decay schedulers', 'create a FrameAggregation module to process each video frame independently and concatenate all tokens', 'create a ClipAggregation module to process each video clip independently and concatenate all tokens', 'create a VideoTransform object with random resize, flip, auto augment, and random erasing for training', 'create an EvalVideoTransform object to sample multiple spatial views of each video clip for evaluation', 'create video transforms using make_transforms for training or multi-view evaluation pipelines']
```

Usage

```
{'create_FrameAggregation': 'create a FrameAggregation module to process each video frame independently and concatenate all tokens', 'create_ClipAggregation': 'create a ClipAggregation module to process each video clip independently and concatenate all tokens', 'create_VideoTransform': 'create a VideoTransform object with random resize, flip, auto augment, and random erasing for training', 'create_EvalVideoTransform': 'create an EvalVideoTransform object to sample multiple spatial views of each video clip for evaluation', 'create_make_transforms': 'create video transforms using make_transforms for training or multi-view evaluation pipelines'}
```


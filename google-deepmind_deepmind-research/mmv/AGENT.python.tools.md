# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/mmv/config.py

Prompts

```
['get the default MMV model configuration dictionary for a given checkpoint path', 'get the MMV model config with s3d visual backbone by passing an s3d checkpoint path', 'get the MMV model config with resnet50tsm backbone by passing a tsm_resnet_x1 checkpoint path', 'get the MMV model config with resnet50tsm backbone and width_mult 2 by passing a tsm_resnet_x2 checkpoint path', 'summarize the get_model_config function which returns MMV model configuration based on checkpoint path', 'run the UCF101 linear evaluation script with a pre-trained MMV checkpoint and SVM classifier', 'run process_samples to preprocess video frames with random sampling, resizing, and cropping for training or testing', 'run sample_linspace_sequence to extract multiple linearly spaced video segments from a sequence for evaluation', 'run compute_accuracy_metrics to calculate top-1 and top-5 accuracy from prediction and ground truth arrays', 'run forward_fn to extract video representations from an AudioTextVideoEmbedding model given images, audio, and word inputs']
```

Usage

```
{'get_model_config_default': 'get the default MMV model configuration dictionary for a given checkpoint path', 'get_model_config_s3d': 'get the MMV model config with s3d visual backbone by passing an s3d checkpoint path', 'get_model_config_tsm_x1': 'get the MMV model config with resnet50tsm backbone by passing a tsm_resnet_x1 checkpoint path', 'get_model_config_tsm_x2': 'get the MMV model config with resnet50tsm backbone and width_mult 2 by passing a tsm_resnet_x2 checkpoint path', 'summarize_get_model_config': 'summarize the get_model_config function which returns MMV model configuration based on checkpoint path'}
```

## File: google-deepmind_deepmind-research/mmv/eval_ucf101.py

Prompts

```
['get the default MMV model configuration dictionary for a given checkpoint path', 'get the MMV model config with s3d visual backbone by passing an s3d checkpoint path', 'get the MMV model config with resnet50tsm backbone by passing a tsm_resnet_x1 checkpoint path', 'get the MMV model config with resnet50tsm backbone and width_mult 2 by passing a tsm_resnet_x2 checkpoint path', 'summarize the get_model_config function which returns MMV model configuration based on checkpoint path', 'run the UCF101 linear evaluation script with a pre-trained MMV checkpoint and SVM classifier', 'run process_samples to preprocess video frames with random sampling, resizing, and cropping for training or testing', 'run sample_linspace_sequence to extract multiple linearly spaced video segments from a sequence for evaluation', 'run compute_accuracy_metrics to calculate top-1 and top-5 accuracy from prediction and ground truth arrays', 'run forward_fn to extract video representations from an AudioTextVideoEmbedding model given images, audio, and word inputs']
```

Usage

```
{'run_ucf101_linear_evaluation': 'run the UCF101 linear evaluation script with a pre-trained MMV checkpoint and SVM classifier', 'run_process_samples': 'run process_samples to preprocess video frames with random sampling, resizing, and cropping for training or testing', 'run_sample_linspace_sequence': 'run sample_linspace_sequence to extract multiple linearly spaced video segments from a sequence for evaluation', 'run_compute_accuracy_metrics': 'run compute_accuracy_metrics to calculate top-1 and top-5 accuracy from prediction and ground truth arrays', 'run_forward_fn': 'run forward_fn to extract video representations from an AudioTextVideoEmbedding model given images, audio, and word inputs'}
```


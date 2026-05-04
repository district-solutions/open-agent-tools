# Agent Python Tools

- repo: facebookresearch/detic
- repo_uri: https://github.com/facebookresearch/detic

## File: facebookresearch_detic/demo.py

Prompts

```
['run the Detic demo on input images using a config file and confidence threshold', 'run the Detic demo on webcam or screen capture input with real-time visualization', 'run the Detic demo on a video file and optionally save annotated output video', 'setup the Detectron2 configuration with CenterNet2 and Detic options from a config file', 'test whether a given OpenCV video codec and file extension are supported', 'run a detectron2 model training loop using a LazyConfig python config file with DDP support', 'run inference on a test dataset using a trained detectron2 model and print results in CSV format', 'run evaluation only mode by loading a checkpoint and testing a model without training', 'run multi-GPU distributed training using detectron2 launch with configurable number of GPUs and machines', 'run training with periodic checkpointing, learning rate scheduling, and evaluation hooks via LazyConfig', 'run the Predictor to detect objects in an image using a built-in vocabulary like lvis or coco', 'run the Predictor with a custom comma-separated vocabulary to detect user-defined object classes', 'run the Predictor setup to initialize the Detic model with SwinB weights and built-in classifiers', 'run get_clip_embeddings to generate CLIP text embeddings for a list of vocabulary terms', 'review the Predictor class that wraps Detic zero-shot object detection with visualization output', 'run DETIC object detection training on a dataset using a config file and GPU', 'run DETIC model evaluation on COCO, LVIS, or OID datasets with a config file', 'run distributed DETIC training across multiple GPUs and machines using SLURM or TCP', 'run DETIC model evaluation only without training by loading pretrained weights from a checkpoint', 'run DETIC training with custom augmentations or DETR-style dataset mappers via config options']
```

Usage

```
{'run_detic_on_images': 'run the Detic demo on input images using a config file and confidence threshold', 'run_detic_on_webcam': 'run the Detic demo on webcam or screen capture input with real-time visualization', 'run_detic_on_video': 'run the Detic demo on a video file and optionally save annotated output video', 'setup_detic_config': 'setup the Detectron2 configuration with CenterNet2 and Detic options from a config file', 'test_opencv_video_format': 'test whether a given OpenCV video codec and file extension are supported'}
```

## File: facebookresearch_detic/lazy_train_net.py

Prompts

```
['run the Detic demo on input images using a config file and confidence threshold', 'run the Detic demo on webcam or screen capture input with real-time visualization', 'run the Detic demo on a video file and optionally save annotated output video', 'setup the Detectron2 configuration with CenterNet2 and Detic options from a config file', 'test whether a given OpenCV video codec and file extension are supported', 'run a detectron2 model training loop using a LazyConfig python config file with DDP support', 'run inference on a test dataset using a trained detectron2 model and print results in CSV format', 'run evaluation only mode by loading a checkpoint and testing a model without training', 'run multi-GPU distributed training using detectron2 launch with configurable number of GPUs and machines', 'run training with periodic checkpointing, learning rate scheduling, and evaluation hooks via LazyConfig', 'run the Predictor to detect objects in an image using a built-in vocabulary like lvis or coco', 'run the Predictor with a custom comma-separated vocabulary to detect user-defined object classes', 'run the Predictor setup to initialize the Detic model with SwinB weights and built-in classifiers', 'run get_clip_embeddings to generate CLIP text embeddings for a list of vocabulary terms', 'review the Predictor class that wraps Detic zero-shot object detection with visualization output', 'run DETIC object detection training on a dataset using a config file and GPU', 'run DETIC model evaluation on COCO, LVIS, or OID datasets with a config file', 'run distributed DETIC training across multiple GPUs and machines using SLURM or TCP', 'run DETIC model evaluation only without training by loading pretrained weights from a checkpoint', 'run DETIC training with custom augmentations or DETR-style dataset mappers via config options']
```

Usage

```
{'run_detection_model_training': 'run a detectron2 model training loop using a LazyConfig python config file with DDP support', 'run_model_evaluation': 'run inference on a test dataset using a trained detectron2 model and print results in CSV format', 'run_eval_only_mode': 'run evaluation only mode by loading a checkpoint and testing a model without training', 'run_multi_gpu_training': 'run multi-GPU distributed training using detectron2 launch with configurable number of GPUs and machines', 'run_training_with_checkpointing': 'run training with periodic checkpointing, learning rate scheduling, and evaluation hooks via LazyConfig'}
```

## File: facebookresearch_detic/predict.py

Prompts

```
['run the Detic demo on input images using a config file and confidence threshold', 'run the Detic demo on webcam or screen capture input with real-time visualization', 'run the Detic demo on a video file and optionally save annotated output video', 'setup the Detectron2 configuration with CenterNet2 and Detic options from a config file', 'test whether a given OpenCV video codec and file extension are supported', 'run a detectron2 model training loop using a LazyConfig python config file with DDP support', 'run inference on a test dataset using a trained detectron2 model and print results in CSV format', 'run evaluation only mode by loading a checkpoint and testing a model without training', 'run multi-GPU distributed training using detectron2 launch with configurable number of GPUs and machines', 'run training with periodic checkpointing, learning rate scheduling, and evaluation hooks via LazyConfig', 'run the Predictor to detect objects in an image using a built-in vocabulary like lvis or coco', 'run the Predictor with a custom comma-separated vocabulary to detect user-defined object classes', 'run the Predictor setup to initialize the Detic model with SwinB weights and built-in classifiers', 'run get_clip_embeddings to generate CLIP text embeddings for a list of vocabulary terms', 'review the Predictor class that wraps Detic zero-shot object detection with visualization output', 'run DETIC object detection training on a dataset using a config file and GPU', 'run DETIC model evaluation on COCO, LVIS, or OID datasets with a config file', 'run distributed DETIC training across multiple GPUs and machines using SLURM or TCP', 'run DETIC model evaluation only without training by loading pretrained weights from a checkpoint', 'run DETIC training with custom augmentations or DETR-style dataset mappers via config options']
```

Usage

```
{'run_Predictor_predict': 'run the Predictor to detect objects in an image using a built-in vocabulary like lvis or coco', 'run_Predictor_custom_vocabulary': 'run the Predictor with a custom comma-separated vocabulary to detect user-defined object classes', 'run_Predictor_setup': 'run the Predictor setup to initialize the Detic model with SwinB weights and built-in classifiers', 'run_get_clip_embeddings': 'run get_clip_embeddings to generate CLIP text embeddings for a list of vocabulary terms', 'review_Predictor_class': 'review the Predictor class that wraps Detic zero-shot object detection with visualization output'}
```

## File: facebookresearch_detic/train_net.py

Prompts

```
['run the Detic demo on input images using a config file and confidence threshold', 'run the Detic demo on webcam or screen capture input with real-time visualization', 'run the Detic demo on a video file and optionally save annotated output video', 'setup the Detectron2 configuration with CenterNet2 and Detic options from a config file', 'test whether a given OpenCV video codec and file extension are supported', 'run a detectron2 model training loop using a LazyConfig python config file with DDP support', 'run inference on a test dataset using a trained detectron2 model and print results in CSV format', 'run evaluation only mode by loading a checkpoint and testing a model without training', 'run multi-GPU distributed training using detectron2 launch with configurable number of GPUs and machines', 'run training with periodic checkpointing, learning rate scheduling, and evaluation hooks via LazyConfig', 'run the Predictor to detect objects in an image using a built-in vocabulary like lvis or coco', 'run the Predictor with a custom comma-separated vocabulary to detect user-defined object classes', 'run the Predictor setup to initialize the Detic model with SwinB weights and built-in classifiers', 'run get_clip_embeddings to generate CLIP text embeddings for a list of vocabulary terms', 'review the Predictor class that wraps Detic zero-shot object detection with visualization output', 'run DETIC object detection training on a dataset using a config file and GPU', 'run DETIC model evaluation on COCO, LVIS, or OID datasets with a config file', 'run distributed DETIC training across multiple GPUs and machines using SLURM or TCP', 'run DETIC model evaluation only without training by loading pretrained weights from a checkpoint', 'run DETIC training with custom augmentations or DETR-style dataset mappers via config options']
```

Usage

```
{'run_detic_training': 'run DETIC object detection training on a dataset using a config file and GPU', 'run_detic_evaluation': 'run DETIC model evaluation on COCO, LVIS, or OID datasets with a config file', 'run_detic_distributed_training': 'run distributed DETIC training across multiple GPUs and machines using SLURM or TCP', 'run_detic_eval_only': 'run DETIC model evaluation only without training by loading pretrained weights from a checkpoint', 'run_detic_custom_augmentation': 'run DETIC training with custom augmentations or DETR-style dataset mappers via config options'}
```


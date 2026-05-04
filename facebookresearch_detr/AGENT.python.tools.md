# Agent Python Tools

- repo: facebookresearch/detr
- repo_uri: https://github.com/facebookresearch/detr.git

## File: facebookresearch_detr/engine.py

Prompts

```
['run one epoch of DETR model training with a criterion, data loader, and optimizer', 'run DETR model evaluation on a test dataset with COCO and panoptic evaluators', 'review the train_one_epoch function for gradient clipping and loss reduction logic', 'review the evaluate function for COCO bbox and segmentation postprocessing steps', 'refactor train_one_epoch to support custom loss weighting or additional metric logging', 'build a DETR ResNet-50 object detection model with 6 encoder and 6 decoder layers', 'build a DETR-DC5 ResNet-101 object detection model with dilation for higher resolution output', 'build a DETR ResNet-50 panoptic segmentation model with configurable confidence threshold', 'run a pretrained DETR model loaded from Facebook AI public weights for object detection', 'run a DETR model with the PostProcess postprocessor returned alongside the model', 'run the DETR transformer detector training on a COCO dataset with configurable backbone and epochs', 'run evaluation of a trained DETR model on a validation dataset and save bbox results', 'build an argparse parser with all DETR training hyperparameters including backbone, transformer, and loss options', 'resume DETR training from a saved checkpoint file with optimizer and lr scheduler state', 'configure DETR for distributed multi-GPU training with configurable world size and batch size', 'run multinode DETR object detection training with submitit on a SLURM cluster', 'submit a Trainer job to a submitit AutoExecutor with GPU and node parameters', 'parse command line arguments for multinode training including ngpus, nodes, timeout, and job_dir', 'checkpoint a Trainer instance to resume training from a saved checkpoint file', 'setup GPU arguments from submitit JobEnvironment including rank, world_size, and output_dir', 'test the DETR ResNet50 detection model by scripting it with torch.jit and comparing outputs', 'test the DETR ResNet50 panoptic model by scripting it with torch.jit and comparing outputs', 'test the HungarianMatcher by matching predicted logits and boxes against target labels and boxes', 'test exporting the DETR detection model to ONNX and validating with onnxruntime', 'test the box coordinate conversion functions box_cxcywh_to_xyxy and box_xyxy_to_cxcywh']
```

Usage

```
{'run_train_one_epoch': 'run one epoch of DETR model training with a criterion, data loader, and optimizer', 'run_evaluate': 'run DETR model evaluation on a test dataset with COCO and panoptic evaluators', 'review_train_one_epoch': 'review the train_one_epoch function for gradient clipping and loss reduction logic', 'review_evaluate': 'review the evaluate function for COCO bbox and segmentation postprocessing steps', 'refactor_train_one_epoch': 'refactor train_one_epoch to support custom loss weighting or additional metric logging'}
```

## File: facebookresearch_detr/hubconf.py

Prompts

```
['run one epoch of DETR model training with a criterion, data loader, and optimizer', 'run DETR model evaluation on a test dataset with COCO and panoptic evaluators', 'review the train_one_epoch function for gradient clipping and loss reduction logic', 'review the evaluate function for COCO bbox and segmentation postprocessing steps', 'refactor train_one_epoch to support custom loss weighting or additional metric logging', 'build a DETR ResNet-50 object detection model with 6 encoder and 6 decoder layers', 'build a DETR-DC5 ResNet-101 object detection model with dilation for higher resolution output', 'build a DETR ResNet-50 panoptic segmentation model with configurable confidence threshold', 'run a pretrained DETR model loaded from Facebook AI public weights for object detection', 'run a DETR model with the PostProcess postprocessor returned alongside the model', 'run the DETR transformer detector training on a COCO dataset with configurable backbone and epochs', 'run evaluation of a trained DETR model on a validation dataset and save bbox results', 'build an argparse parser with all DETR training hyperparameters including backbone, transformer, and loss options', 'resume DETR training from a saved checkpoint file with optimizer and lr scheduler state', 'configure DETR for distributed multi-GPU training with configurable world size and batch size', 'run multinode DETR object detection training with submitit on a SLURM cluster', 'submit a Trainer job to a submitit AutoExecutor with GPU and node parameters', 'parse command line arguments for multinode training including ngpus, nodes, timeout, and job_dir', 'checkpoint a Trainer instance to resume training from a saved checkpoint file', 'setup GPU arguments from submitit JobEnvironment including rank, world_size, and output_dir', 'test the DETR ResNet50 detection model by scripting it with torch.jit and comparing outputs', 'test the DETR ResNet50 panoptic model by scripting it with torch.jit and comparing outputs', 'test the HungarianMatcher by matching predicted logits and boxes against target labels and boxes', 'test exporting the DETR detection model to ONNX and validating with onnxruntime', 'test the box coordinate conversion functions box_cxcywh_to_xyxy and box_xyxy_to_cxcywh']
```

Usage

```
{'build_detr_resnet50_model': 'build a DETR ResNet-50 object detection model with 6 encoder and 6 decoder layers', 'build_detr_resnet101_dc5_model': 'build a DETR-DC5 ResNet-101 object detection model with dilation for higher resolution output', 'build_detr_panoptic_model': 'build a DETR ResNet-50 panoptic segmentation model with configurable confidence threshold', 'run_detr_pretrained_inference': 'run a pretrained DETR model loaded from Facebook AI public weights for object detection', 'run_detr_with_postprocessor': 'run a DETR model with the PostProcess postprocessor returned alongside the model'}
```

## File: facebookresearch_detr/main.py

Prompts

```
['run one epoch of DETR model training with a criterion, data loader, and optimizer', 'run DETR model evaluation on a test dataset with COCO and panoptic evaluators', 'review the train_one_epoch function for gradient clipping and loss reduction logic', 'review the evaluate function for COCO bbox and segmentation postprocessing steps', 'refactor train_one_epoch to support custom loss weighting or additional metric logging', 'build a DETR ResNet-50 object detection model with 6 encoder and 6 decoder layers', 'build a DETR-DC5 ResNet-101 object detection model with dilation for higher resolution output', 'build a DETR ResNet-50 panoptic segmentation model with configurable confidence threshold', 'run a pretrained DETR model loaded from Facebook AI public weights for object detection', 'run a DETR model with the PostProcess postprocessor returned alongside the model', 'run the DETR transformer detector training on a COCO dataset with configurable backbone and epochs', 'run evaluation of a trained DETR model on a validation dataset and save bbox results', 'build an argparse parser with all DETR training hyperparameters including backbone, transformer, and loss options', 'resume DETR training from a saved checkpoint file with optimizer and lr scheduler state', 'configure DETR for distributed multi-GPU training with configurable world size and batch size', 'run multinode DETR object detection training with submitit on a SLURM cluster', 'submit a Trainer job to a submitit AutoExecutor with GPU and node parameters', 'parse command line arguments for multinode training including ngpus, nodes, timeout, and job_dir', 'checkpoint a Trainer instance to resume training from a saved checkpoint file', 'setup GPU arguments from submitit JobEnvironment including rank, world_size, and output_dir', 'test the DETR ResNet50 detection model by scripting it with torch.jit and comparing outputs', 'test the DETR ResNet50 panoptic model by scripting it with torch.jit and comparing outputs', 'test the HungarianMatcher by matching predicted logits and boxes against target labels and boxes', 'test exporting the DETR detection model to ONNX and validating with onnxruntime', 'test the box coordinate conversion functions box_cxcywh_to_xyxy and box_xyxy_to_cxcywh']
```

Usage

```
{'run_DETR_training': 'run the DETR transformer detector training on a COCO dataset with configurable backbone and epochs', 'run_DETR_evaluation': 'run evaluation of a trained DETR model on a validation dataset and save bbox results', 'build_args_parser': 'build an argparse parser with all DETR training hyperparameters including backbone, transformer, and loss options', 'resume_DETR_training': 'resume DETR training from a saved checkpoint file with optimizer and lr scheduler state', 'configure_DETR_distributed_training': 'configure DETR for distributed multi-GPU training with configurable world size and batch size'}
```

## File: facebookresearch_detr/run_with_submitit.py

Prompts

```
['run one epoch of DETR model training with a criterion, data loader, and optimizer', 'run DETR model evaluation on a test dataset with COCO and panoptic evaluators', 'review the train_one_epoch function for gradient clipping and loss reduction logic', 'review the evaluate function for COCO bbox and segmentation postprocessing steps', 'refactor train_one_epoch to support custom loss weighting or additional metric logging', 'build a DETR ResNet-50 object detection model with 6 encoder and 6 decoder layers', 'build a DETR-DC5 ResNet-101 object detection model with dilation for higher resolution output', 'build a DETR ResNet-50 panoptic segmentation model with configurable confidence threshold', 'run a pretrained DETR model loaded from Facebook AI public weights for object detection', 'run a DETR model with the PostProcess postprocessor returned alongside the model', 'run the DETR transformer detector training on a COCO dataset with configurable backbone and epochs', 'run evaluation of a trained DETR model on a validation dataset and save bbox results', 'build an argparse parser with all DETR training hyperparameters including backbone, transformer, and loss options', 'resume DETR training from a saved checkpoint file with optimizer and lr scheduler state', 'configure DETR for distributed multi-GPU training with configurable world size and batch size', 'run multinode DETR object detection training with submitit on a SLURM cluster', 'submit a Trainer job to a submitit AutoExecutor with GPU and node parameters', 'parse command line arguments for multinode training including ngpus, nodes, timeout, and job_dir', 'checkpoint a Trainer instance to resume training from a saved checkpoint file', 'setup GPU arguments from submitit JobEnvironment including rank, world_size, and output_dir', 'test the DETR ResNet50 detection model by scripting it with torch.jit and comparing outputs', 'test the DETR ResNet50 panoptic model by scripting it with torch.jit and comparing outputs', 'test the HungarianMatcher by matching predicted logits and boxes against target labels and boxes', 'test exporting the DETR detection model to ONNX and validating with onnxruntime', 'test the box coordinate conversion functions box_cxcywh_to_xyxy and box_xyxy_to_cxcywh']
```

Usage

```
{'run_multinode_training': 'run multinode DETR object detection training with submitit on a SLURM cluster', 'submit_trainer_job': 'submit a Trainer job to a submitit AutoExecutor with GPU and node parameters', 'parse_args': 'parse command line arguments for multinode training including ngpus, nodes, timeout, and job_dir', 'checkpoint_trainer': 'checkpoint a Trainer instance to resume training from a saved checkpoint file', 'setup_gpu_args': 'setup GPU arguments from submitit JobEnvironment including rank, world_size, and output_dir'}
```

## File: facebookresearch_detr/test_all.py

Prompts

```
['run one epoch of DETR model training with a criterion, data loader, and optimizer', 'run DETR model evaluation on a test dataset with COCO and panoptic evaluators', 'review the train_one_epoch function for gradient clipping and loss reduction logic', 'review the evaluate function for COCO bbox and segmentation postprocessing steps', 'refactor train_one_epoch to support custom loss weighting or additional metric logging', 'build a DETR ResNet-50 object detection model with 6 encoder and 6 decoder layers', 'build a DETR-DC5 ResNet-101 object detection model with dilation for higher resolution output', 'build a DETR ResNet-50 panoptic segmentation model with configurable confidence threshold', 'run a pretrained DETR model loaded from Facebook AI public weights for object detection', 'run a DETR model with the PostProcess postprocessor returned alongside the model', 'run the DETR transformer detector training on a COCO dataset with configurable backbone and epochs', 'run evaluation of a trained DETR model on a validation dataset and save bbox results', 'build an argparse parser with all DETR training hyperparameters including backbone, transformer, and loss options', 'resume DETR training from a saved checkpoint file with optimizer and lr scheduler state', 'configure DETR for distributed multi-GPU training with configurable world size and batch size', 'run multinode DETR object detection training with submitit on a SLURM cluster', 'submit a Trainer job to a submitit AutoExecutor with GPU and node parameters', 'parse command line arguments for multinode training including ngpus, nodes, timeout, and job_dir', 'checkpoint a Trainer instance to resume training from a saved checkpoint file', 'setup GPU arguments from submitit JobEnvironment including rank, world_size, and output_dir', 'test the DETR ResNet50 detection model by scripting it with torch.jit and comparing outputs', 'test the DETR ResNet50 panoptic model by scripting it with torch.jit and comparing outputs', 'test the HungarianMatcher by matching predicted logits and boxes against target labels and boxes', 'test exporting the DETR detection model to ONNX and validating with onnxruntime', 'test the box coordinate conversion functions box_cxcywh_to_xyxy and box_xyxy_to_cxcywh']
```

Usage

```
{'test_DETR_model_torchscript_detection': 'test the DETR ResNet50 detection model by scripting it with torch.jit and comparing outputs', 'test_DETR_model_torchscript_panoptic': 'test the DETR ResNet50 panoptic model by scripting it with torch.jit and comparing outputs', 'test_HungarianMatcher_bipartite_matching': 'test the HungarianMatcher by matching predicted logits and boxes against target labels and boxes', 'test_DETR_model_ONNX_export': 'test exporting the DETR detection model to ONNX and validating with onnxruntime', 'test_box_coordinate_conversion': 'test the box coordinate conversion functions box_cxcywh_to_xyxy and box_xyxy_to_cxcywh'}
```


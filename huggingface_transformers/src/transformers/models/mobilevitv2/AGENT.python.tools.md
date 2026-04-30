# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mobilevitv2/convert_mlcvnets_to_pytorch.py

Prompts

```
['convert a MobileViTV2 checkpoint from ml-cvnets to HuggingFace PyTorch format', 'load and flatten a YAML config file from the ml-cvnets library into an argparse namespace', 'build a MobileViTV2Config from task name and original ml-cvnets config file', 'generate key rename mappings to transform ml-cvnets state dict keys to HuggingFace naming', 'remove unused keys like auxiliary segmentation heads from a state dict', 'create a MobileViTV2Model backbone for feature extraction from image tensors', 'build a MobileViTV2ForImageClassification model with a linear classifier head for ImageNet', 'build a MobileViTV2ForSemanticSegmentation model with DeepLabV3 ASPP head for pixel-level segmentation', 'run a forward pass on MobileViTV2Model to extract hidden states and pooled output from pixel values', 'test MobileViTV2ForSemanticSegmentation forward pass with ground truth labels to compute cross-entropy loss']
```

Usage

```
{'convert_mobilevitv2_checkpoint': 'convert a MobileViTV2 checkpoint from ml-cvnets to HuggingFace PyTorch format', 'load_orig_config_file': 'load and flatten a YAML config file from the ml-cvnets library into an argparse namespace', 'get_mobilevitv2_config': 'build a MobileViTV2Config from task name and original ml-cvnets config file', 'create_rename_keys': 'generate key rename mappings to transform ml-cvnets state dict keys to HuggingFace naming', 'remove_unused_keys': 'remove unused keys like auxiliary segmentation heads from a state dict'}
```

## File: huggingface_transformers/src/transformers/models/mobilevitv2/modeling_mobilevitv2.py

Prompts

```
['convert a MobileViTV2 checkpoint from ml-cvnets to HuggingFace PyTorch format', 'load and flatten a YAML config file from the ml-cvnets library into an argparse namespace', 'build a MobileViTV2Config from task name and original ml-cvnets config file', 'generate key rename mappings to transform ml-cvnets state dict keys to HuggingFace naming', 'remove unused keys like auxiliary segmentation heads from a state dict', 'create a MobileViTV2Model backbone for feature extraction from image tensors', 'build a MobileViTV2ForImageClassification model with a linear classifier head for ImageNet', 'build a MobileViTV2ForSemanticSegmentation model with DeepLabV3 ASPP head for pixel-level segmentation', 'run a forward pass on MobileViTV2Model to extract hidden states and pooled output from pixel values', 'test MobileViTV2ForSemanticSegmentation forward pass with ground truth labels to compute cross-entropy loss']
```

Usage

```
{'create_mobilevitv2_model': 'create a MobileViTV2Model backbone for feature extraction from image tensors', 'build_image_classifier': 'build a MobileViTV2ForImageClassification model with a linear classifier head for ImageNet', 'build_semantic_segmenter': 'build a MobileViTV2ForSemanticSegmentation model with DeepLabV3 ASPP head for pixel-level segmentation', 'run_mobilevitv2_forward': 'run a forward pass on MobileViTV2Model to extract hidden states and pooled output from pixel values', 'test_segmentation_loss': 'test MobileViTV2ForSemanticSegmentation forward pass with ground truth labels to compute cross-entropy loss'}
```


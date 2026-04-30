# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/textnet/convert_textnet_to_hf.py

Prompts

```
['convert a FAST textnet PyTorch checkpoint to HuggingFace TextNetBackbone format and save to a local folder', 'prepare a TextNetConfig from a FAST model configuration URL by downloading and parsing stage and neck parameters', 'run the textnet-to-hf conversion CLI with checkpoint URL, config filename, and output folder arguments', 'test the textnet checkpoint conversion by loading a checkpoint, verifying pixel values and feature map output against expected slices', 'review the checkpoint key renaming mappings that translate FAST backbone keys to HuggingFace TextNet naming conventions', 'create a TextNetImageProcessorPil instance with custom size_divisor for image preprocessing', 'resize an image to shortest edge then round dimensions up to be divisible by size_divisor', 'preprocess images with resize, rescale, normalize using TextNetImageProcessorPil', 'configure TextNetImageProcessorKwargs with a custom size_divisor value', 'run TextNetImageProcessorPil preprocess pipeline on a batch of input images', 'create a TextNetImageProcessor instance with custom size_divisor and preprocessing settings', 'build an image preprocessing pipeline using TextNetImageProcessor to resize, rescale, and normalize images', 'test the TextNetImageProcessor resize method to round image dimensions to multiples of size_divisor', 'test the TextNetImageProcessor preprocess method with batched images and return_tensors option', 'review the TextNetImageProcessorKwargs typed configuration class for size_divisor parameter', 'create a TextNetForImageClassification model for image classification with a linear head on pooled features', 'build a TextNetModel backbone with stem conv layer, encoder stages, and adaptive average pooler for feature extraction', 'run inference with TextNetForImageClassification on image pixel values and return classification logits', 'extract multi-scale feature maps from TextNetBackbone for use with downstream frameworks like DETR and MaskFormer', 'load a pretrained TextNetPreTrainedModel from a HuggingFace model identifier such as czczup/textnet-base']
```

Usage

```
{'build_convert_textnet_checkpoint': 'convert a FAST textnet PyTorch checkpoint to HuggingFace TextNetBackbone format and save to a local folder', 'create_prepare_config': 'prepare a TextNetConfig from a FAST model configuration URL by downloading and parsing stage and neck parameters', 'run_convert_textnet_cli': 'run the textnet-to-hf conversion CLI with checkpoint URL, config filename, and output folder arguments', 'test_convert_textnet_checkpoint': 'test the textnet checkpoint conversion by loading a checkpoint, verifying pixel values and feature map output against expected slices', 'review_rename_key_mappings': 'review the checkpoint key renaming mappings that translate FAST backbone keys to HuggingFace TextNet naming conventions'}
```

## File: huggingface_transformers/src/transformers/models/textnet/image_processing_pil_textnet.py

Prompts

```
['convert a FAST textnet PyTorch checkpoint to HuggingFace TextNetBackbone format and save to a local folder', 'prepare a TextNetConfig from a FAST model configuration URL by downloading and parsing stage and neck parameters', 'run the textnet-to-hf conversion CLI with checkpoint URL, config filename, and output folder arguments', 'test the textnet checkpoint conversion by loading a checkpoint, verifying pixel values and feature map output against expected slices', 'review the checkpoint key renaming mappings that translate FAST backbone keys to HuggingFace TextNet naming conventions', 'create a TextNetImageProcessorPil instance with custom size_divisor for image preprocessing', 'resize an image to shortest edge then round dimensions up to be divisible by size_divisor', 'preprocess images with resize, rescale, normalize using TextNetImageProcessorPil', 'configure TextNetImageProcessorKwargs with a custom size_divisor value', 'run TextNetImageProcessorPil preprocess pipeline on a batch of input images', 'create a TextNetImageProcessor instance with custom size_divisor and preprocessing settings', 'build an image preprocessing pipeline using TextNetImageProcessor to resize, rescale, and normalize images', 'test the TextNetImageProcessor resize method to round image dimensions to multiples of size_divisor', 'test the TextNetImageProcessor preprocess method with batched images and return_tensors option', 'review the TextNetImageProcessorKwargs typed configuration class for size_divisor parameter', 'create a TextNetForImageClassification model for image classification with a linear head on pooled features', 'build a TextNetModel backbone with stem conv layer, encoder stages, and adaptive average pooler for feature extraction', 'run inference with TextNetForImageClassification on image pixel values and return classification logits', 'extract multi-scale feature maps from TextNetBackbone for use with downstream frameworks like DETR and MaskFormer', 'load a pretrained TextNetPreTrainedModel from a HuggingFace model identifier such as czczup/textnet-base']
```

Usage

```
{'create_TextNetImageProcessorPil': 'create a TextNetImageProcessorPil instance with custom size_divisor for image preprocessing', 'resize_TextNetImageProcessorPil': 'resize an image to shortest edge then round dimensions up to be divisible by size_divisor', 'preprocess_TextNetImageProcessorPil': 'preprocess images with resize, rescale, normalize using TextNetImageProcessorPil', 'configure_TextNetImageProcessorKwargs': 'configure TextNetImageProcessorKwargs with a custom size_divisor value', 'run_TextNetImageProcessorPil': 'run TextNetImageProcessorPil preprocess pipeline on a batch of input images'}
```

## File: huggingface_transformers/src/transformers/models/textnet/image_processing_textnet.py

Prompts

```
['convert a FAST textnet PyTorch checkpoint to HuggingFace TextNetBackbone format and save to a local folder', 'prepare a TextNetConfig from a FAST model configuration URL by downloading and parsing stage and neck parameters', 'run the textnet-to-hf conversion CLI with checkpoint URL, config filename, and output folder arguments', 'test the textnet checkpoint conversion by loading a checkpoint, verifying pixel values and feature map output against expected slices', 'review the checkpoint key renaming mappings that translate FAST backbone keys to HuggingFace TextNet naming conventions', 'create a TextNetImageProcessorPil instance with custom size_divisor for image preprocessing', 'resize an image to shortest edge then round dimensions up to be divisible by size_divisor', 'preprocess images with resize, rescale, normalize using TextNetImageProcessorPil', 'configure TextNetImageProcessorKwargs with a custom size_divisor value', 'run TextNetImageProcessorPil preprocess pipeline on a batch of input images', 'create a TextNetImageProcessor instance with custom size_divisor and preprocessing settings', 'build an image preprocessing pipeline using TextNetImageProcessor to resize, rescale, and normalize images', 'test the TextNetImageProcessor resize method to round image dimensions to multiples of size_divisor', 'test the TextNetImageProcessor preprocess method with batched images and return_tensors option', 'review the TextNetImageProcessorKwargs typed configuration class for size_divisor parameter', 'create a TextNetForImageClassification model for image classification with a linear head on pooled features', 'build a TextNetModel backbone with stem conv layer, encoder stages, and adaptive average pooler for feature extraction', 'run inference with TextNetForImageClassification on image pixel values and return classification logits', 'extract multi-scale feature maps from TextNetBackbone for use with downstream frameworks like DETR and MaskFormer', 'load a pretrained TextNetPreTrainedModel from a HuggingFace model identifier such as czczup/textnet-base']
```

Usage

```
{'create_TextNetImageProcessor': 'create a TextNetImageProcessor instance with custom size_divisor and preprocessing settings', 'build_ImageNet_preprocess_pipeline': 'build an image preprocessing pipeline using TextNetImageProcessor to resize, rescale, and normalize images', 'test_TextNetImageProcessor_resize': 'test the TextNetImageProcessor resize method to round image dimensions to multiples of size_divisor', 'test_TextNetImageProcessor_preprocess': 'test the TextNetImageProcessor preprocess method with batched images and return_tensors option', 'review_TextNetImageProcessorKwargs': 'review the TextNetImageProcessorKwargs typed configuration class for size_divisor parameter'}
```

## File: huggingface_transformers/src/transformers/models/textnet/modeling_textnet.py

Prompts

```
['convert a FAST textnet PyTorch checkpoint to HuggingFace TextNetBackbone format and save to a local folder', 'prepare a TextNetConfig from a FAST model configuration URL by downloading and parsing stage and neck parameters', 'run the textnet-to-hf conversion CLI with checkpoint URL, config filename, and output folder arguments', 'test the textnet checkpoint conversion by loading a checkpoint, verifying pixel values and feature map output against expected slices', 'review the checkpoint key renaming mappings that translate FAST backbone keys to HuggingFace TextNet naming conventions', 'create a TextNetImageProcessorPil instance with custom size_divisor for image preprocessing', 'resize an image to shortest edge then round dimensions up to be divisible by size_divisor', 'preprocess images with resize, rescale, normalize using TextNetImageProcessorPil', 'configure TextNetImageProcessorKwargs with a custom size_divisor value', 'run TextNetImageProcessorPil preprocess pipeline on a batch of input images', 'create a TextNetImageProcessor instance with custom size_divisor and preprocessing settings', 'build an image preprocessing pipeline using TextNetImageProcessor to resize, rescale, and normalize images', 'test the TextNetImageProcessor resize method to round image dimensions to multiples of size_divisor', 'test the TextNetImageProcessor preprocess method with batched images and return_tensors option', 'review the TextNetImageProcessorKwargs typed configuration class for size_divisor parameter', 'create a TextNetForImageClassification model for image classification with a linear head on pooled features', 'build a TextNetModel backbone with stem conv layer, encoder stages, and adaptive average pooler for feature extraction', 'run inference with TextNetForImageClassification on image pixel values and return classification logits', 'extract multi-scale feature maps from TextNetBackbone for use with downstream frameworks like DETR and MaskFormer', 'load a pretrained TextNetPreTrainedModel from a HuggingFace model identifier such as czczup/textnet-base']
```

Usage

```
{'create_textnet_image_classifier': 'create a TextNetForImageClassification model for image classification with a linear head on pooled features', 'build_textnet_model': 'build a TextNetModel backbone with stem conv layer, encoder stages, and adaptive average pooler for feature extraction', 'run_textnet_classification': 'run inference with TextNetForImageClassification on image pixel values and return classification logits', 'extract_textnet_features': 'extract multi-scale feature maps from TextNetBackbone for use with downstream frameworks like DETR and MaskFormer', 'load_textnet_pretrained': 'load a pretrained TextNetPreTrainedModel from a HuggingFace model identifier such as czczup/textnet-base'}
```


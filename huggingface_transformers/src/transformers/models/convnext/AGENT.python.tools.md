# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/convnext/convert_convnext_to_pytorch.py

Prompts

```
['run the convert_convnext_checkpoint function to convert a ConvNeXT checkpoint from Facebook to HuggingFace format', 'build a ConvNextConfig from a checkpoint URL with model size and dataset labels', 'test the rename_key function to map original ConvNeXT state dict keys to HuggingFace naming conventions', 'summarize the prepare_img function that downloads a test image from COCO dataset', 'review the convert_convnext_checkpoint function that converts Facebook ConvNeXT weights to HuggingFace ConvNextForImageClassification', 'create a ConvNeXT image processor with custom resize, center crop, rescale, and normalize for image inputs', 'resize a torch tensor image to a target shortest edge with crop_pct-based scaling and center cropping', 'preprocess a batch of torch tensor images with resize, center crop, rescale, and normalize operations', 'test the ConvNextImageProcessorKwargs type definition with crop_pct configuration option', 'summarize the resize method that scales images below 384 with crop_pct and crops to square, or warps to square at 384+', 'create a ConvNextImageProcessorPil instance with custom crop_pct and image preprocessing settings', 'resize a numpy image to a target shortest edge with crop_pct support for ConvNeXT preprocessing', 'preprocess a list of numpy images with resize, rescale, and normalize for ConvNeXT model input', 'review the ConvNextImageProcessorPil class and its resize logic with crop_pct handling', 'summarize the resize method that crops or warps images based on shortest edge threshold of 384', 'create a ConvNext model for image feature extraction with patch embeddings and encoder stages', 'build a ConvNext model with a classification head for image classification on ImageNet', 'build a ConvNext backbone for object detection frameworks like DETR and MaskFormer', 'test the ConvNextLayerNorm class that supports channels_first and channels_last data formats', 'review the drop_path function and ConvNextDropPath class implementing stochastic depth regularization']
```

Usage

```
{'run_convert_convnext_checkpoint': 'run the convert_convnext_checkpoint function to convert a ConvNeXT checkpoint from Facebook to HuggingFace format', 'build_get_convnext_config': 'build a ConvNextConfig from a checkpoint URL with model size and dataset labels', 'test_rename_key': 'test the rename_key function to map original ConvNeXT state dict keys to HuggingFace naming conventions', 'summarize_prepare_img': 'summarize the prepare_img function that downloads a test image from COCO dataset', 'review_convert_convnext_checkpoint': 'review the convert_convnext_checkpoint function that converts Facebook ConvNeXT weights to HuggingFace ConvNextForImageClassification'}
```

## File: huggingface_transformers/src/transformers/models/convnext/image_processing_convnext.py

Prompts

```
['run the convert_convnext_checkpoint function to convert a ConvNeXT checkpoint from Facebook to HuggingFace format', 'build a ConvNextConfig from a checkpoint URL with model size and dataset labels', 'test the rename_key function to map original ConvNeXT state dict keys to HuggingFace naming conventions', 'summarize the prepare_img function that downloads a test image from COCO dataset', 'review the convert_convnext_checkpoint function that converts Facebook ConvNeXT weights to HuggingFace ConvNextForImageClassification', 'create a ConvNeXT image processor with custom resize, center crop, rescale, and normalize for image inputs', 'resize a torch tensor image to a target shortest edge with crop_pct-based scaling and center cropping', 'preprocess a batch of torch tensor images with resize, center crop, rescale, and normalize operations', 'test the ConvNextImageProcessorKwargs type definition with crop_pct configuration option', 'summarize the resize method that scales images below 384 with crop_pct and crops to square, or warps to square at 384+', 'create a ConvNextImageProcessorPil instance with custom crop_pct and image preprocessing settings', 'resize a numpy image to a target shortest edge with crop_pct support for ConvNeXT preprocessing', 'preprocess a list of numpy images with resize, rescale, and normalize for ConvNeXT model input', 'review the ConvNextImageProcessorPil class and its resize logic with crop_pct handling', 'summarize the resize method that crops or warps images based on shortest edge threshold of 384', 'create a ConvNext model for image feature extraction with patch embeddings and encoder stages', 'build a ConvNext model with a classification head for image classification on ImageNet', 'build a ConvNext backbone for object detection frameworks like DETR and MaskFormer', 'test the ConvNextLayerNorm class that supports channels_first and channels_last data formats', 'review the drop_path function and ConvNextDropPath class implementing stochastic depth regularization']
```

Usage

```
{'create_ConvNextImageProcessor': 'create a ConvNeXT image processor with custom resize, center crop, rescale, and normalize for image inputs', 'resize_ConvNextImageProcessor': 'resize a torch tensor image to a target shortest edge with crop_pct-based scaling and center cropping', 'preprocess_ConvNextImageProcessor': 'preprocess a batch of torch tensor images with resize, center crop, rescale, and normalize operations', 'test_ConvNextImageProcessorKwargs': 'test the ConvNextImageProcessorKwargs type definition with crop_pct configuration option', 'summarize_ConvNextImageProcessor_resize': 'summarize the resize method that scales images below 384 with crop_pct and crops to square, or warps to square at 384+'}
```

## File: huggingface_transformers/src/transformers/models/convnext/image_processing_pil_convnext.py

Prompts

```
['run the convert_convnext_checkpoint function to convert a ConvNeXT checkpoint from Facebook to HuggingFace format', 'build a ConvNextConfig from a checkpoint URL with model size and dataset labels', 'test the rename_key function to map original ConvNeXT state dict keys to HuggingFace naming conventions', 'summarize the prepare_img function that downloads a test image from COCO dataset', 'review the convert_convnext_checkpoint function that converts Facebook ConvNeXT weights to HuggingFace ConvNextForImageClassification', 'create a ConvNeXT image processor with custom resize, center crop, rescale, and normalize for image inputs', 'resize a torch tensor image to a target shortest edge with crop_pct-based scaling and center cropping', 'preprocess a batch of torch tensor images with resize, center crop, rescale, and normalize operations', 'test the ConvNextImageProcessorKwargs type definition with crop_pct configuration option', 'summarize the resize method that scales images below 384 with crop_pct and crops to square, or warps to square at 384+', 'create a ConvNextImageProcessorPil instance with custom crop_pct and image preprocessing settings', 'resize a numpy image to a target shortest edge with crop_pct support for ConvNeXT preprocessing', 'preprocess a list of numpy images with resize, rescale, and normalize for ConvNeXT model input', 'review the ConvNextImageProcessorPil class and its resize logic with crop_pct handling', 'summarize the resize method that crops or warps images based on shortest edge threshold of 384', 'create a ConvNext model for image feature extraction with patch embeddings and encoder stages', 'build a ConvNext model with a classification head for image classification on ImageNet', 'build a ConvNext backbone for object detection frameworks like DETR and MaskFormer', 'test the ConvNextLayerNorm class that supports channels_first and channels_last data formats', 'review the drop_path function and ConvNextDropPath class implementing stochastic depth regularization']
```

Usage

```
{'create_convnext_image_processor': 'create a ConvNextImageProcessorPil instance with custom crop_pct and image preprocessing settings', 'resize_convnext_image': 'resize a numpy image to a target shortest edge with crop_pct support for ConvNeXT preprocessing', 'preprocess_convnext_images': 'preprocess a list of numpy images with resize, rescale, and normalize for ConvNeXT model input', 'review_convnext_image_processor': 'review the ConvNextImageProcessorPil class and its resize logic with crop_pct handling', 'summarize_convnext_resize': 'summarize the resize method that crops or warps images based on shortest edge threshold of 384'}
```

## File: huggingface_transformers/src/transformers/models/convnext/modeling_convnext.py

Prompts

```
['run the convert_convnext_checkpoint function to convert a ConvNeXT checkpoint from Facebook to HuggingFace format', 'build a ConvNextConfig from a checkpoint URL with model size and dataset labels', 'test the rename_key function to map original ConvNeXT state dict keys to HuggingFace naming conventions', 'summarize the prepare_img function that downloads a test image from COCO dataset', 'review the convert_convnext_checkpoint function that converts Facebook ConvNeXT weights to HuggingFace ConvNextForImageClassification', 'create a ConvNeXT image processor with custom resize, center crop, rescale, and normalize for image inputs', 'resize a torch tensor image to a target shortest edge with crop_pct-based scaling and center cropping', 'preprocess a batch of torch tensor images with resize, center crop, rescale, and normalize operations', 'test the ConvNextImageProcessorKwargs type definition with crop_pct configuration option', 'summarize the resize method that scales images below 384 with crop_pct and crops to square, or warps to square at 384+', 'create a ConvNextImageProcessorPil instance with custom crop_pct and image preprocessing settings', 'resize a numpy image to a target shortest edge with crop_pct support for ConvNeXT preprocessing', 'preprocess a list of numpy images with resize, rescale, and normalize for ConvNeXT model input', 'review the ConvNextImageProcessorPil class and its resize logic with crop_pct handling', 'summarize the resize method that crops or warps images based on shortest edge threshold of 384', 'create a ConvNext model for image feature extraction with patch embeddings and encoder stages', 'build a ConvNext model with a classification head for image classification on ImageNet', 'build a ConvNext backbone for object detection frameworks like DETR and MaskFormer', 'test the ConvNextLayerNorm class that supports channels_first and channels_last data formats', 'review the drop_path function and ConvNextDropPath class implementing stochastic depth regularization']
```

Usage

```
{'create_model_convnext': 'create a ConvNext model for image feature extraction with patch embeddings and encoder stages', 'build_model_convnext_classification': 'build a ConvNext model with a classification head for image classification on ImageNet', 'build_model_convnext_backbone': 'build a ConvNext backbone for object detection frameworks like DETR and MaskFormer', 'test_convnext_layer_norm': 'test the ConvNextLayerNorm class that supports channels_first and channels_last data formats', 'review_drop_path_stochastic_depth': 'review the drop_path function and ConvNextDropPath class implementing stochastic depth regularization'}
```


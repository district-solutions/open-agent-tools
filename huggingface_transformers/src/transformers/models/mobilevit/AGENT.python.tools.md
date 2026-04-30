# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mobilevit/convert_mlcvnets_to_pytorch.py

Prompts

```
['convert a MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format with image classification', 'convert a DeepLabV3-MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format for semantic segmentation', 'run the argparse CLI to convert ml-cvnets MobileViT checkpoints to HuggingFace PyTorch model files', 'rename and remap ml-cvnets state dict keys to match HuggingFace MobileViT model naming conventions', 'push a converted MobileViT model and image processor to the HuggingFace hub under the apple organization', 'create a MobileViTImageProcessor instance with custom flip_channel_order and reduce_labels settings', 'preprocess images and optional segmentation maps for MobileViT model input', 'reduce label values in segmentation maps by 1 replacing 0 with 255', 'flip RGB channel order to BGR or vice versa on single or batched image tensors', 'post process MobileViTForSemanticSegmentation logits into semantic segmentation maps', 'create a MobileViTImageProcessorPil instance with custom resize, crop, and channel flip settings', 'preprocess images and optional segmentation maps for MobileViT model input', 'build label reduction by replacing 0 with 255 and decrementing all other label values by 1', 'flip channel order of an image from RGB to BGR or vice versa', 'create a MobileViT model for image classification with a linear head on pooled features', 'create a MobileViT model with a DeepLabV3-style semantic segmentation head on top', 'build a MobileViT feature extractor model with conv stem, encoder layers, and global average pooling', 'test the MobileViT transformer layer with self-attention, intermediate MLP, and residual connections', 'summarize the MobileViT layer that applies local convolutions, patch unfolding, global self-attention, and folding back to feature maps']
```

Usage

```
{'convert_mobilevit_checkpoint': 'convert a MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format with image classification', 'convert_deeplabv3_checkpoint': 'convert a DeepLabV3-MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format for semantic segmentation', 'run_cli_conversion': 'run the argparse CLI to convert ml-cvnets MobileViT checkpoints to HuggingFace PyTorch model files', 'rename_state_dict_keys': 'rename and remap ml-cvnets state dict keys to match HuggingFace MobileViT model naming conventions', 'push_converted_model_hub': 'push a converted MobileViT model and image processor to the HuggingFace hub under the apple organization'}
```

## File: huggingface_transformers/src/transformers/models/mobilevit/image_processing_mobilevit.py

Prompts

```
['convert a MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format with image classification', 'convert a DeepLabV3-MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format for semantic segmentation', 'run the argparse CLI to convert ml-cvnets MobileViT checkpoints to HuggingFace PyTorch model files', 'rename and remap ml-cvnets state dict keys to match HuggingFace MobileViT model naming conventions', 'push a converted MobileViT model and image processor to the HuggingFace hub under the apple organization', 'create a MobileViTImageProcessor instance with custom flip_channel_order and reduce_labels settings', 'preprocess images and optional segmentation maps for MobileViT model input', 'reduce label values in segmentation maps by 1 replacing 0 with 255', 'flip RGB channel order to BGR or vice versa on single or batched image tensors', 'post process MobileViTForSemanticSegmentation logits into semantic segmentation maps', 'create a MobileViTImageProcessorPil instance with custom resize, crop, and channel flip settings', 'preprocess images and optional segmentation maps for MobileViT model input', 'build label reduction by replacing 0 with 255 and decrementing all other label values by 1', 'flip channel order of an image from RGB to BGR or vice versa', 'create a MobileViT model for image classification with a linear head on pooled features', 'create a MobileViT model with a DeepLabV3-style semantic segmentation head on top', 'build a MobileViT feature extractor model with conv stem, encoder layers, and global average pooling', 'test the MobileViT transformer layer with self-attention, intermediate MLP, and residual connections', 'summarize the MobileViT layer that applies local convolutions, patch unfolding, global self-attention, and folding back to feature maps']
```

Usage

```
{'create_MobileViTImageProcessor': 'create a MobileViTImageProcessor instance with custom flip_channel_order and reduce_labels settings', 'preprocess_images_mobilevit': 'preprocess images and optional segmentation maps for MobileViT model input', 'reduce_label_segmentation_maps': 'reduce label values in segmentation maps by 1 replacing 0 with 255', 'flip_channel_order_images': 'flip RGB channel order to BGR or vice versa on single or batched image tensors', 'post_process_semantic_segmentation': 'post process MobileViTForSemanticSegmentation logits into semantic segmentation maps'}
```

## File: huggingface_transformers/src/transformers/models/mobilevit/image_processing_pil_mobilevit.py

Prompts

```
['convert a MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format with image classification', 'convert a DeepLabV3-MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format for semantic segmentation', 'run the argparse CLI to convert ml-cvnets MobileViT checkpoints to HuggingFace PyTorch model files', 'rename and remap ml-cvnets state dict keys to match HuggingFace MobileViT model naming conventions', 'push a converted MobileViT model and image processor to the HuggingFace hub under the apple organization', 'create a MobileViTImageProcessor instance with custom flip_channel_order and reduce_labels settings', 'preprocess images and optional segmentation maps for MobileViT model input', 'reduce label values in segmentation maps by 1 replacing 0 with 255', 'flip RGB channel order to BGR or vice versa on single or batched image tensors', 'post process MobileViTForSemanticSegmentation logits into semantic segmentation maps', 'create a MobileViTImageProcessorPil instance with custom resize, crop, and channel flip settings', 'preprocess images and optional segmentation maps for MobileViT model input', 'build label reduction by replacing 0 with 255 and decrementing all other label values by 1', 'flip channel order of an image from RGB to BGR or vice versa', 'create a MobileViT model for image classification with a linear head on pooled features', 'create a MobileViT model with a DeepLabV3-style semantic segmentation head on top', 'build a MobileViT feature extractor model with conv stem, encoder layers, and global average pooling', 'test the MobileViT transformer layer with self-attention, intermediate MLP, and residual connections', 'summarize the MobileViT layer that applies local convolutions, patch unfolding, global self-attention, and folding back to feature maps']
```

Usage

```
{'create_MobileViTImageProcessorPil': 'create a MobileViTImageProcessorPil instance with custom resize, crop, and channel flip settings', 'preprocess_MobileViTImageProcessorPil': 'preprocess images and optional segmentation maps for MobileViT model input', 'build_reduce_label': 'build label reduction by replacing 0 with 255 and decrementing all other label values by 1', 'flip_channel_order_image': 'flip channel order of an image from RGB to BGR or vice versa', 'post_process_semantic_segmentation': 'post-process semantic segmentation logits into segmentation maps with target sizes'}
```

## File: huggingface_transformers/src/transformers/models/mobilevit/modeling_mobilevit.py

Prompts

```
['convert a MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format with image classification', 'convert a DeepLabV3-MobileViT ml-cvnets checkpoint to HuggingFace PyTorch format for semantic segmentation', 'run the argparse CLI to convert ml-cvnets MobileViT checkpoints to HuggingFace PyTorch model files', 'rename and remap ml-cvnets state dict keys to match HuggingFace MobileViT model naming conventions', 'push a converted MobileViT model and image processor to the HuggingFace hub under the apple organization', 'create a MobileViTImageProcessor instance with custom flip_channel_order and reduce_labels settings', 'preprocess images and optional segmentation maps for MobileViT model input', 'reduce label values in segmentation maps by 1 replacing 0 with 255', 'flip RGB channel order to BGR or vice versa on single or batched image tensors', 'post process MobileViTForSemanticSegmentation logits into semantic segmentation maps', 'create a MobileViTImageProcessorPil instance with custom resize, crop, and channel flip settings', 'preprocess images and optional segmentation maps for MobileViT model input', 'build label reduction by replacing 0 with 255 and decrementing all other label values by 1', 'flip channel order of an image from RGB to BGR or vice versa', 'create a MobileViT model for image classification with a linear head on pooled features', 'create a MobileViT model with a DeepLabV3-style semantic segmentation head on top', 'build a MobileViT feature extractor model with conv stem, encoder layers, and global average pooling', 'test the MobileViT transformer layer with self-attention, intermediate MLP, and residual connections', 'summarize the MobileViT layer that applies local convolutions, patch unfolding, global self-attention, and folding back to feature maps']
```

Usage

```
{'create_MobileViTForImageClassification': 'create a MobileViT model for image classification with a linear head on pooled features', 'create_MobileViTForSemanticSegmentation': 'create a MobileViT model with a DeepLabV3-style semantic segmentation head on top', 'build_MobileViTModel': 'build a MobileViT feature extractor model with conv stem, encoder layers, and global average pooling', 'test_MobileViTTransformerLayer': 'test the MobileViT transformer layer with self-attention, intermediate MLP, and residual connections', 'summarize_MobileViTLayer': 'summarize the MobileViT layer that applies local convolutions, patch unfolding, global self-attention, and folding back to feature maps'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/poolformer/convert_poolformer_original_to_pytorch.py

Prompts

```
['convert a PoolFormer checkpoint from the original repository to HuggingFace PyTorch format', 'rename state dict keys from original PoolFormer to HuggingFace PoolFormerForImageClassification format', 'replace state dict keys by subtracting an offset from the original layer block number', 'download and prepare a COCO validation image for verifying converted model outputs', 'run the PoolFormer checkpoint conversion script via argparse CLI with model name, checkpoint path, and output folder', 'create a PoolFormerImageProcessorPil instance with custom crop_pct and resize settings', 'resize a numpy image array using PoolFormerImageProcessorPil with a custom crop_pct factor', 'preprocess a list of numpy images through resize, center crop, rescale, and normalize for PoolFormer', 'review the PoolFormerImageProcessorKwargs TypedDict for valid keyword arguments', 'summarize the PoolFormerImageProcessorPil resize method and its crop_pct scaling behavior', 'create a PoolFormerImageProcessor instance with custom crop_pct, size, and resample settings', 'preprocess a list of torch tensor images with resize, center crop, rescale, and normalize for PoolFormer', 'group a list of images by their shape for batched processing with PoolFormerImageProcessor', 'center crop and normalize a batch of images using PoolFormerImageProcessor for PoolFormer model input', 'create a PoolFormerModel for image feature extraction with configurable encoder blocks and patch embeddings', 'build a PoolFormerForImageClassification model with a classifier head for image classification tasks', 'run the PoolFormerModel forward pass on image pixel values to extract hidden state representations', 'test PoolFormerForImageClassification training with labels to compute classification loss and logits', 'review the PoolFormerEncoder architecture with patch embeddings, residual pooling blocks, and stochastic depth']
```

Usage

```
{'convert_poolformer_checkpoint': 'convert a PoolFormer checkpoint from the original repository to HuggingFace PyTorch format', 'rename_keys': 'rename state dict keys from original PoolFormer to HuggingFace PoolFormerForImageClassification format', 'replace_key_with_offset': 'replace state dict keys by subtracting an offset from the original layer block number', 'prepare_img': 'download and prepare a COCO validation image for verifying converted model outputs', 'convert_poolformer_checkpoint_cli': 'run the PoolFormer checkpoint conversion script via argparse CLI with model name, checkpoint path, and output folder'}
```

## File: huggingface_transformers/src/transformers/models/poolformer/image_processing_pil_poolformer.py

Prompts

```
['convert a PoolFormer checkpoint from the original repository to HuggingFace PyTorch format', 'rename state dict keys from original PoolFormer to HuggingFace PoolFormerForImageClassification format', 'replace state dict keys by subtracting an offset from the original layer block number', 'download and prepare a COCO validation image for verifying converted model outputs', 'run the PoolFormer checkpoint conversion script via argparse CLI with model name, checkpoint path, and output folder', 'create a PoolFormerImageProcessorPil instance with custom crop_pct and resize settings', 'resize a numpy image array using PoolFormerImageProcessorPil with a custom crop_pct factor', 'preprocess a list of numpy images through resize, center crop, rescale, and normalize for PoolFormer', 'review the PoolFormerImageProcessorKwargs TypedDict for valid keyword arguments', 'summarize the PoolFormerImageProcessorPil resize method and its crop_pct scaling behavior', 'create a PoolFormerImageProcessor instance with custom crop_pct, size, and resample settings', 'preprocess a list of torch tensor images with resize, center crop, rescale, and normalize for PoolFormer', 'group a list of images by their shape for batched processing with PoolFormerImageProcessor', 'center crop and normalize a batch of images using PoolFormerImageProcessor for PoolFormer model input', 'create a PoolFormerModel for image feature extraction with configurable encoder blocks and patch embeddings', 'build a PoolFormerForImageClassification model with a classifier head for image classification tasks', 'run the PoolFormerModel forward pass on image pixel values to extract hidden state representations', 'test PoolFormerForImageClassification training with labels to compute classification loss and logits', 'review the PoolFormerEncoder architecture with patch embeddings, residual pooling blocks, and stochastic depth']
```

Usage

```
{'create_PoolFormerImageProcessorPil': 'create a PoolFormerImageProcessorPil instance with custom crop_pct and resize settings', 'resize_image_with_crop_pct': 'resize a numpy image array using PoolFormerImageProcessorPil with a custom crop_pct factor', 'preprocess_poolformer_images': 'preprocess a list of numpy images through resize, center crop, rescale, and normalize for PoolFormer', 'review_PoolFormerImageProcessorKwargs': 'review the PoolFormerImageProcessorKwargs TypedDict for valid keyword arguments', 'summarize_PoolFormerImageProcessorPil_resize': 'summarize the PoolFormerImageProcessorPil resize method and its crop_pct scaling behavior'}
```

## File: huggingface_transformers/src/transformers/models/poolformer/image_processing_poolformer.py

Prompts

```
['convert a PoolFormer checkpoint from the original repository to HuggingFace PyTorch format', 'rename state dict keys from original PoolFormer to HuggingFace PoolFormerForImageClassification format', 'replace state dict keys by subtracting an offset from the original layer block number', 'download and prepare a COCO validation image for verifying converted model outputs', 'run the PoolFormer checkpoint conversion script via argparse CLI with model name, checkpoint path, and output folder', 'create a PoolFormerImageProcessorPil instance with custom crop_pct and resize settings', 'resize a numpy image array using PoolFormerImageProcessorPil with a custom crop_pct factor', 'preprocess a list of numpy images through resize, center crop, rescale, and normalize for PoolFormer', 'review the PoolFormerImageProcessorKwargs TypedDict for valid keyword arguments', 'summarize the PoolFormerImageProcessorPil resize method and its crop_pct scaling behavior', 'create a PoolFormerImageProcessor instance with custom crop_pct, size, and resample settings', 'preprocess a list of torch tensor images with resize, center crop, rescale, and normalize for PoolFormer', 'group a list of images by their shape for batched processing with PoolFormerImageProcessor', 'center crop and normalize a batch of images using PoolFormerImageProcessor for PoolFormer model input', 'create a PoolFormerModel for image feature extraction with configurable encoder blocks and patch embeddings', 'build a PoolFormerForImageClassification model with a classifier head for image classification tasks', 'run the PoolFormerModel forward pass on image pixel values to extract hidden state representations', 'test PoolFormerForImageClassification training with labels to compute classification loss and logits', 'review the PoolFormerEncoder architecture with patch embeddings, residual pooling blocks, and stochastic depth']
```

Usage

```
{'create_poolformer_image_processor': 'create a PoolFormerImageProcessor instance with custom crop_pct, size, and resample settings', 'resize_image_with_crop_pct': 'resize a torch tensor image using PoolFormerImageProcessor.resize with a custom crop_pct value', 'preprocess_images_for_poolformer': 'preprocess a list of torch tensor images with resize, center crop, rescale, and normalize for PoolFormer', 'group_images_by_shape': 'group a list of images by their shape for batched processing with PoolFormerImageProcessor', 'center_crop_and_normalize_images': 'center crop and normalize a batch of images using PoolFormerImageProcessor for PoolFormer model input'}
```

## File: huggingface_transformers/src/transformers/models/poolformer/modeling_poolformer.py

Prompts

```
['convert a PoolFormer checkpoint from the original repository to HuggingFace PyTorch format', 'rename state dict keys from original PoolFormer to HuggingFace PoolFormerForImageClassification format', 'replace state dict keys by subtracting an offset from the original layer block number', 'download and prepare a COCO validation image for verifying converted model outputs', 'run the PoolFormer checkpoint conversion script via argparse CLI with model name, checkpoint path, and output folder', 'create a PoolFormerImageProcessorPil instance with custom crop_pct and resize settings', 'resize a numpy image array using PoolFormerImageProcessorPil with a custom crop_pct factor', 'preprocess a list of numpy images through resize, center crop, rescale, and normalize for PoolFormer', 'review the PoolFormerImageProcessorKwargs TypedDict for valid keyword arguments', 'summarize the PoolFormerImageProcessorPil resize method and its crop_pct scaling behavior', 'create a PoolFormerImageProcessor instance with custom crop_pct, size, and resample settings', 'preprocess a list of torch tensor images with resize, center crop, rescale, and normalize for PoolFormer', 'group a list of images by their shape for batched processing with PoolFormerImageProcessor', 'center crop and normalize a batch of images using PoolFormerImageProcessor for PoolFormer model input', 'create a PoolFormerModel for image feature extraction with configurable encoder blocks and patch embeddings', 'build a PoolFormerForImageClassification model with a classifier head for image classification tasks', 'run the PoolFormerModel forward pass on image pixel values to extract hidden state representations', 'test PoolFormerForImageClassification training with labels to compute classification loss and logits', 'review the PoolFormerEncoder architecture with patch embeddings, residual pooling blocks, and stochastic depth']
```

Usage

```
{'create_poolformer_model': 'create a PoolFormerModel for image feature extraction with configurable encoder blocks and patch embeddings', 'build_poolformer_classifier': 'build a PoolFormerForImageClassification model with a classifier head for image classification tasks', 'run_poolformer_forward': 'run the PoolFormerModel forward pass on image pixel values to extract hidden state representations', 'test_poolformer_training': 'test PoolFormerForImageClassification training with labels to compute classification loss and logits', 'review_poolformer_encoder': 'review the PoolFormerEncoder architecture with patch embeddings, residual pooling blocks, and stochastic depth'}
```


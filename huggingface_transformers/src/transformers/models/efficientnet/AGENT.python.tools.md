# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/efficientnet/convert_efficientnet_to_pytorch.py

Prompts

```
['convert an EfficientNet Keras checkpoint from the original repository to a HuggingFace PyTorch model', 'run the EfficientNet checkpoint converter CLI with model_name, output path, and save or push flags', 'test the EfficientNet checkpoint converter by verifying HuggingFace and original model outputs match', 'create an EfficientNetConfig from model name with ImageNet-1k labels and architecture hyperparameters', 'create an EfficientNetImageProcessor with model-specific size, normalization mean and std values', 'create an EfficientNetImageProcessor instance with custom rescale_offset and include_top settings', 'rescale a torch.Tensor image by a given scale factor with optional offset subtraction', 'rescale and normalize a batch of EfficientNet images with fused mean/std computation', 'fuse mean, standard deviation, and rescale factor into optimized normalization parameters', 'preprocess a list of images for EfficientNet with resize, crop, rescale, normalize, and return pixel values', 'create an EfficientNetImageProcessorPil instance with custom rescale_offset and include_top settings', 'rescale an EfficientNet image array with an optional offset applied after scaling', 'preprocess a batch of EfficientNet images with resize, rescale, normalize, and include_top steps', 'configure EfficientNetImageProcessorKwargs with rescale_offset and include_top keyword arguments', 'normalize an EfficientNet image using ImageNet standard mean and standard deviation', 'create an EfficientNetModel from config for extracting image features with pooling', 'build an EfficientNetForImageClassification model with a linear classification head for ImageNet', 'run the EfficientNetModel forward pass on pixel values to get hidden states and pooled output', 'train the EfficientNetForImageClassification model with labels to compute classification loss', 'review the EfficientNetBlock class that implements expansion, depthwise conv, squeeze-excite, and projection phases']
```

Usage

```
{'build_convert_efficientnet_checkpoint': 'convert an EfficientNet Keras checkpoint from the original repository to a HuggingFace PyTorch model', 'run_convert_efficientnet_checkpoint': 'run the EfficientNet checkpoint converter CLI with model_name, output path, and save or push flags', 'test_convert_efficientnet_checkpoint': 'test the EfficientNet checkpoint converter by verifying HuggingFace and original model outputs match', 'create_get_efficientnet_config': 'create an EfficientNetConfig from model name with ImageNet-1k labels and architecture hyperparameters', 'create_convert_image_processor': 'create an EfficientNetImageProcessor with model-specific size, normalization mean and std values'}
```

## File: huggingface_transformers/src/transformers/models/efficientnet/image_processing_efficientnet.py

Prompts

```
['convert an EfficientNet Keras checkpoint from the original repository to a HuggingFace PyTorch model', 'run the EfficientNet checkpoint converter CLI with model_name, output path, and save or push flags', 'test the EfficientNet checkpoint converter by verifying HuggingFace and original model outputs match', 'create an EfficientNetConfig from model name with ImageNet-1k labels and architecture hyperparameters', 'create an EfficientNetImageProcessor with model-specific size, normalization mean and std values', 'create an EfficientNetImageProcessor instance with custom rescale_offset and include_top settings', 'rescale a torch.Tensor image by a given scale factor with optional offset subtraction', 'rescale and normalize a batch of EfficientNet images with fused mean/std computation', 'fuse mean, standard deviation, and rescale factor into optimized normalization parameters', 'preprocess a list of images for EfficientNet with resize, crop, rescale, normalize, and return pixel values', 'create an EfficientNetImageProcessorPil instance with custom rescale_offset and include_top settings', 'rescale an EfficientNet image array with an optional offset applied after scaling', 'preprocess a batch of EfficientNet images with resize, rescale, normalize, and include_top steps', 'configure EfficientNetImageProcessorKwargs with rescale_offset and include_top keyword arguments', 'normalize an EfficientNet image using ImageNet standard mean and standard deviation', 'create an EfficientNetModel from config for extracting image features with pooling', 'build an EfficientNetForImageClassification model with a linear classification head for ImageNet', 'run the EfficientNetModel forward pass on pixel values to get hidden states and pooled output', 'train the EfficientNetForImageClassification model with labels to compute classification loss', 'review the EfficientNetBlock class that implements expansion, depthwise conv, squeeze-excite, and projection phases']
```

Usage

```
{'create_efficientnet_image_processor': 'create an EfficientNetImageProcessor instance with custom rescale_offset and include_top settings', 'rescale_image_tensor': 'rescale a torch.Tensor image by a given scale factor with optional offset subtraction', 'rescale_and_normalize_efficientnet': 'rescale and normalize a batch of EfficientNet images with fused mean/std computation', 'fuse_mean_std_and_rescale_factor': 'fuse mean, standard deviation, and rescale factor into optimized normalization parameters', 'preprocess_efficientnet_images': 'preprocess a list of images for EfficientNet with resize, crop, rescale, normalize, and return pixel values'}
```

## File: huggingface_transformers/src/transformers/models/efficientnet/image_processing_pil_efficientnet.py

Prompts

```
['convert an EfficientNet Keras checkpoint from the original repository to a HuggingFace PyTorch model', 'run the EfficientNet checkpoint converter CLI with model_name, output path, and save or push flags', 'test the EfficientNet checkpoint converter by verifying HuggingFace and original model outputs match', 'create an EfficientNetConfig from model name with ImageNet-1k labels and architecture hyperparameters', 'create an EfficientNetImageProcessor with model-specific size, normalization mean and std values', 'create an EfficientNetImageProcessor instance with custom rescale_offset and include_top settings', 'rescale a torch.Tensor image by a given scale factor with optional offset subtraction', 'rescale and normalize a batch of EfficientNet images with fused mean/std computation', 'fuse mean, standard deviation, and rescale factor into optimized normalization parameters', 'preprocess a list of images for EfficientNet with resize, crop, rescale, normalize, and return pixel values', 'create an EfficientNetImageProcessorPil instance with custom rescale_offset and include_top settings', 'rescale an EfficientNet image array with an optional offset applied after scaling', 'preprocess a batch of EfficientNet images with resize, rescale, normalize, and include_top steps', 'configure EfficientNetImageProcessorKwargs with rescale_offset and include_top keyword arguments', 'normalize an EfficientNet image using ImageNet standard mean and standard deviation', 'create an EfficientNetModel from config for extracting image features with pooling', 'build an EfficientNetForImageClassification model with a linear classification head for ImageNet', 'run the EfficientNetModel forward pass on pixel values to get hidden states and pooled output', 'train the EfficientNetForImageClassification model with labels to compute classification loss', 'review the EfficientNetBlock class that implements expansion, depthwise conv, squeeze-excite, and projection phases']
```

Usage

```
{'create_EfficientNetImageProcessorPil': 'create an EfficientNetImageProcessorPil instance with custom rescale_offset and include_top settings', 'rescale_image_EfficientNet': 'rescale an EfficientNet image array with an optional offset applied after scaling', 'preprocess_EfficientNet_images': 'preprocess a batch of EfficientNet images with resize, rescale, normalize, and include_top steps', 'configure_EfficientNetImageProcessorKwargs': 'configure EfficientNetImageProcessorKwargs with rescale_offset and include_top keyword arguments', 'normalize_EfficientNet_image': 'normalize an EfficientNet image using ImageNet standard mean and standard deviation'}
```

## File: huggingface_transformers/src/transformers/models/efficientnet/modeling_efficientnet.py

Prompts

```
['convert an EfficientNet Keras checkpoint from the original repository to a HuggingFace PyTorch model', 'run the EfficientNet checkpoint converter CLI with model_name, output path, and save or push flags', 'test the EfficientNet checkpoint converter by verifying HuggingFace and original model outputs match', 'create an EfficientNetConfig from model name with ImageNet-1k labels and architecture hyperparameters', 'create an EfficientNetImageProcessor with model-specific size, normalization mean and std values', 'create an EfficientNetImageProcessor instance with custom rescale_offset and include_top settings', 'rescale a torch.Tensor image by a given scale factor with optional offset subtraction', 'rescale and normalize a batch of EfficientNet images with fused mean/std computation', 'fuse mean, standard deviation, and rescale factor into optimized normalization parameters', 'preprocess a list of images for EfficientNet with resize, crop, rescale, normalize, and return pixel values', 'create an EfficientNetImageProcessorPil instance with custom rescale_offset and include_top settings', 'rescale an EfficientNet image array with an optional offset applied after scaling', 'preprocess a batch of EfficientNet images with resize, rescale, normalize, and include_top steps', 'configure EfficientNetImageProcessorKwargs with rescale_offset and include_top keyword arguments', 'normalize an EfficientNet image using ImageNet standard mean and standard deviation', 'create an EfficientNetModel from config for extracting image features with pooling', 'build an EfficientNetForImageClassification model with a linear classification head for ImageNet', 'run the EfficientNetModel forward pass on pixel values to get hidden states and pooled output', 'train the EfficientNetForImageClassification model with labels to compute classification loss', 'review the EfficientNetBlock class that implements expansion, depthwise conv, squeeze-excite, and projection phases']
```

Usage

```
{'create_efficientnet_model': 'create an EfficientNetModel from config for extracting image features with pooling', 'build_image_classifier': 'build an EfficientNetForImageClassification model with a linear classification head for ImageNet', 'run_efficientnet_forward': 'run the EfficientNetModel forward pass on pixel values to get hidden states and pooled output', 'train_classification_model': 'train the EfficientNetForImageClassification model with labels to compute classification loss', 'review_efficientnet_block': 'review the EfficientNetBlock class that implements expansion, depthwise conv, squeeze-excite, and projection phases'}
```


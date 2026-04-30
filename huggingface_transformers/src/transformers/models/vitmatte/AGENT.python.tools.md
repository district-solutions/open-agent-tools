# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vitmatte/convert_vitmatte_to_hf.py

Prompts

```
['convert a VitMatte checkpoint from the original repository to Hugging Face format', 'get the VitMatte config for a given model name with appropriate hidden size and attention heads', 'create a list of key renaming rules to map original checkpoint keys to Hugging Face naming', 'rename a dictionary key from the old name to the new name in-place', 'run the convert_vitmatte_to_hf script via CLI to convert and optionally push a VitMatte model to the hub', 'create a VitMatteImageProcessorPil instance for preprocessing images and trimaps with configurable size_divisor', 'build padded images by padding to dimensions divisible by a size_divisor using constant zero padding', 'test the preprocess method that rescales, normalizes, concatenates images with trimaps, and pads to size_divisor', 'summarize the VitMatteImageProcessorKwargs TypedDict that defines size_divisor configuration', 'review the _preprocess method that rescales, normalizes, concatenates images with trimaps, pads, and returns BatchFeature', 'create a VitMatteImageProcessor instance to preprocess images and trimaps for matting models', 'preprocess images and trimaps by rescaling, normalizing, concatenating, and padding to size_divisor', 'pad a torch tensor image so its width and height are divisible by a given size_divisor', 'group images by identical shape to batch them efficiently before processing', 'rescale image tensors by a factor and normalize with ImageNet mean and standard deviation', 'build a ViTMatte model for image matting that produces alpha matte predictions from input images', 'create a convolution stream that extracts detail feature maps from input pixel values', 'fuse vision transformer features with convolution detail features using fusion blocks', 'run image matting inference to produce alpha matte predictions from pixel values and trimaps', 'initialize weights for convolution and batch normalization layers in the ViTMatte model']
```

Usage

```
{'convert_vitmatte_checkpoint': 'convert a VitMatte checkpoint from the original repository to Hugging Face format', 'get_config': 'get the VitMatte config for a given model name with appropriate hidden size and attention heads', 'create_rename_keys': 'create a list of key renaming rules to map original checkpoint keys to Hugging Face naming', 'rename_key': 'rename a dictionary key from the old name to the new name in-place', 'run_convert_cli': 'run the convert_vitmatte_to_hf script via CLI to convert and optionally push a VitMatte model to the hub'}
```

## File: huggingface_transformers/src/transformers/models/vitmatte/image_processing_pil_vitmatte.py

Prompts

```
['convert a VitMatte checkpoint from the original repository to Hugging Face format', 'get the VitMatte config for a given model name with appropriate hidden size and attention heads', 'create a list of key renaming rules to map original checkpoint keys to Hugging Face naming', 'rename a dictionary key from the old name to the new name in-place', 'run the convert_vitmatte_to_hf script via CLI to convert and optionally push a VitMatte model to the hub', 'create a VitMatteImageProcessorPil instance for preprocessing images and trimaps with configurable size_divisor', 'build padded images by padding to dimensions divisible by a size_divisor using constant zero padding', 'test the preprocess method that rescales, normalizes, concatenates images with trimaps, and pads to size_divisor', 'summarize the VitMatteImageProcessorKwargs TypedDict that defines size_divisor configuration', 'review the _preprocess method that rescales, normalizes, concatenates images with trimaps, pads, and returns BatchFeature', 'create a VitMatteImageProcessor instance to preprocess images and trimaps for matting models', 'preprocess images and trimaps by rescaling, normalizing, concatenating, and padding to size_divisor', 'pad a torch tensor image so its width and height are divisible by a given size_divisor', 'group images by identical shape to batch them efficiently before processing', 'rescale image tensors by a factor and normalize with ImageNet mean and standard deviation', 'build a ViTMatte model for image matting that produces alpha matte predictions from input images', 'create a convolution stream that extracts detail feature maps from input pixel values', 'fuse vision transformer features with convolution detail features using fusion blocks', 'run image matting inference to produce alpha matte predictions from pixel values and trimaps', 'initialize weights for convolution and batch normalization layers in the ViTMatte model']
```

Usage

```
{'create_VitMatteImageProcessorPil': 'create a VitMatteImageProcessorPil instance for preprocessing images and trimaps with configurable size_divisor', 'build_pad_image': 'build padded images by padding to dimensions divisible by a size_divisor using constant zero padding', 'test_preprocess': 'test the preprocess method that rescales, normalizes, concatenates images with trimaps, and pads to size_divisor', 'summarize_VitMatteImageProcessorKwargs': 'summarize the VitMatteImageProcessorKwargs TypedDict that defines size_divisor configuration', 'review__preprocess': 'review the _preprocess method that rescales, normalizes, concatenates images with trimaps, pads, and returns BatchFeature'}
```

## File: huggingface_transformers/src/transformers/models/vitmatte/image_processing_vitmatte.py

Prompts

```
['convert a VitMatte checkpoint from the original repository to Hugging Face format', 'get the VitMatte config for a given model name with appropriate hidden size and attention heads', 'create a list of key renaming rules to map original checkpoint keys to Hugging Face naming', 'rename a dictionary key from the old name to the new name in-place', 'run the convert_vitmatte_to_hf script via CLI to convert and optionally push a VitMatte model to the hub', 'create a VitMatteImageProcessorPil instance for preprocessing images and trimaps with configurable size_divisor', 'build padded images by padding to dimensions divisible by a size_divisor using constant zero padding', 'test the preprocess method that rescales, normalizes, concatenates images with trimaps, and pads to size_divisor', 'summarize the VitMatteImageProcessorKwargs TypedDict that defines size_divisor configuration', 'review the _preprocess method that rescales, normalizes, concatenates images with trimaps, pads, and returns BatchFeature', 'create a VitMatteImageProcessor instance to preprocess images and trimaps for matting models', 'preprocess images and trimaps by rescaling, normalizing, concatenating, and padding to size_divisor', 'pad a torch tensor image so its width and height are divisible by a given size_divisor', 'group images by identical shape to batch them efficiently before processing', 'rescale image tensors by a factor and normalize with ImageNet mean and standard deviation', 'build a ViTMatte model for image matting that produces alpha matte predictions from input images', 'create a convolution stream that extracts detail feature maps from input pixel values', 'fuse vision transformer features with convolution detail features using fusion blocks', 'run image matting inference to produce alpha matte predictions from pixel values and trimaps', 'initialize weights for convolution and batch normalization layers in the ViTMatte model']
```

Usage

```
{'create_VitMatteImageProcessor': 'create a VitMatteImageProcessor instance to preprocess images and trimaps for matting models', 'preprocess_images_with_trimaps': 'preprocess images and trimaps by rescaling, normalizing, concatenating, and padding to size_divisor', 'pad_image_to_divisor': 'pad a torch tensor image so its width and height are divisible by a given size_divisor', 'group_images_by_shape': 'group images by identical shape to batch them efficiently before processing', 'rescale_and_normalize_inputs': 'rescale image tensors by a factor and normalize with ImageNet mean and standard deviation'}
```

## File: huggingface_transformers/src/transformers/models/vitmatte/modeling_vitmatte.py

Prompts

```
['convert a VitMatte checkpoint from the original repository to Hugging Face format', 'get the VitMatte config for a given model name with appropriate hidden size and attention heads', 'create a list of key renaming rules to map original checkpoint keys to Hugging Face naming', 'rename a dictionary key from the old name to the new name in-place', 'run the convert_vitmatte_to_hf script via CLI to convert and optionally push a VitMatte model to the hub', 'create a VitMatteImageProcessorPil instance for preprocessing images and trimaps with configurable size_divisor', 'build padded images by padding to dimensions divisible by a size_divisor using constant zero padding', 'test the preprocess method that rescales, normalizes, concatenates images with trimaps, and pads to size_divisor', 'summarize the VitMatteImageProcessorKwargs TypedDict that defines size_divisor configuration', 'review the _preprocess method that rescales, normalizes, concatenates images with trimaps, pads, and returns BatchFeature', 'create a VitMatteImageProcessor instance to preprocess images and trimaps for matting models', 'preprocess images and trimaps by rescaling, normalizing, concatenating, and padding to size_divisor', 'pad a torch tensor image so its width and height are divisible by a given size_divisor', 'group images by identical shape to batch them efficiently before processing', 'rescale image tensors by a factor and normalize with ImageNet mean and standard deviation', 'build a ViTMatte model for image matting that produces alpha matte predictions from input images', 'create a convolution stream that extracts detail feature maps from input pixel values', 'fuse vision transformer features with convolution detail features using fusion blocks', 'run image matting inference to produce alpha matte predictions from pixel values and trimaps', 'initialize weights for convolution and batch normalization layers in the ViTMatte model']
```

Usage

```
{'build_image_matting_model': 'build a ViTMatte model for image matting that produces alpha matte predictions from input images', 'create_conv_stream_features': 'create a convolution stream that extracts detail feature maps from input pixel values', 'fuse_vit_conv_features': 'fuse vision transformer features with convolution detail features using fusion blocks', 'run_image_matting_inference': 'run image matting inference to produce alpha matte predictions from pixel values and trimaps', 'init_conv_batchnorm_weights': 'initialize weights for convolution and batch normalization layers in the ViTMatte model'}
```


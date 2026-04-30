# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pp_lcnet/configuration_pp_lcnet.py

Prompts

```
['create a PPLCNetConfig instance with custom scale, block_configs, and stem_channels parameters', 'build a PPLCNetConfig using default block configs with scale 1.0 and hardswish activation', 'validate a PPLCNetConfig architecture ensuring block_configs has exactly 5 stages', 'customize a PPLCNetConfig with custom block_configs, reduction, and class_expand values', 'configure a PPLCNetConfig with specific out_indices and out_features for multi-scale outputs', 'create a PPLCNetImageProcessor instance with custom resize_short and size_divisor settings', 'run the PPLCNetImageProcessor _preprocess method to resize, crop, rescale, normalize, and convert RGB to BGR', 'test the PPLCNetImageProcessor get_image_size method to compute target dimensions preserving aspect ratio', 'build batched image preprocessing with grouped resizing and center cropping for PPLCNet', 'review the PPLCNetImageProcessorKwargs TypedDict defining resize_short and size_divisor configuration options', 'create a PPLCNetBackbone model for feature extraction from image tensors', 'create a PPLCNetForImageClassification model for image classification with configurable number of labels', 'build a PPLCNetEncoder with stem convolution and depthwise separable convolution stages', 'test the Squeeze-and-Excitation module that performs adaptive channel-wise feature recalibration', 'run a depthwise separable convolution layer with optional SE module for lightweight feature extraction', 'build a depthwise separable convolution layer with optional squeeze-excitation module for lightweight feature extraction']
```

Usage

```
{'create_PPLCNetConfig': 'create a PPLCNetConfig instance with custom scale, block_configs, and stem_channels parameters', 'build_PPLCNetConfig_default': 'build a PPLCNetConfig using default block configs with scale 1.0 and hardswish activation', 'validate_PPLCNetConfig': 'validate a PPLCNetConfig architecture ensuring block_configs has exactly 5 stages', 'customize_PPLCNetConfig': 'customize a PPLCNetConfig with custom block_configs, reduction, and class_expand values', 'configure_PPLCNetConfig_output': 'configure a PPLCNetConfig with specific out_indices and out_features for multi-scale outputs'}
```

## File: huggingface_transformers/src/transformers/models/pp_lcnet/image_processing_pp_lcnet.py

Prompts

```
['create a PPLCNetConfig instance with custom scale, block_configs, and stem_channels parameters', 'build a PPLCNetConfig using default block configs with scale 1.0 and hardswish activation', 'validate a PPLCNetConfig architecture ensuring block_configs has exactly 5 stages', 'customize a PPLCNetConfig with custom block_configs, reduction, and class_expand values', 'configure a PPLCNetConfig with specific out_indices and out_features for multi-scale outputs', 'create a PPLCNetImageProcessor instance with custom resize_short and size_divisor settings', 'run the PPLCNetImageProcessor _preprocess method to resize, crop, rescale, normalize, and convert RGB to BGR', 'test the PPLCNetImageProcessor get_image_size method to compute target dimensions preserving aspect ratio', 'build batched image preprocessing with grouped resizing and center cropping for PPLCNet', 'review the PPLCNetImageProcessorKwargs TypedDict defining resize_short and size_divisor configuration options', 'create a PPLCNetBackbone model for feature extraction from image tensors', 'create a PPLCNetForImageClassification model for image classification with configurable number of labels', 'build a PPLCNetEncoder with stem convolution and depthwise separable convolution stages', 'test the Squeeze-and-Excitation module that performs adaptive channel-wise feature recalibration', 'run a depthwise separable convolution layer with optional SE module for lightweight feature extraction', 'build a depthwise separable convolution layer with optional squeeze-excitation module for lightweight feature extraction']
```

Usage

```
{'create_PPLCNetImageProcessor': 'create a PPLCNetImageProcessor instance with custom resize_short and size_divisor settings', 'run_PPLCNetImageProcessor_preprocess': 'run the PPLCNetImageProcessor _preprocess method to resize, crop, rescale, normalize, and convert RGB to BGR', 'test_PPLCNetImageProcessor_get_image_size': 'test the PPLCNetImageProcessor get_image_size method to compute target dimensions preserving aspect ratio', 'build_PPLCNetImageProcessor_batch': 'build batched image preprocessing with grouped resizing and center cropping for PPLCNet', 'review_PPLCNetImageProcessorKwargs': 'review the PPLCNetImageProcessorKwargs TypedDict defining resize_short and size_divisor configuration options'}
```

## File: huggingface_transformers/src/transformers/models/pp_lcnet/modeling_pp_lcnet.py

Prompts

```
['create a PPLCNetConfig instance with custom scale, block_configs, and stem_channels parameters', 'build a PPLCNetConfig using default block configs with scale 1.0 and hardswish activation', 'validate a PPLCNetConfig architecture ensuring block_configs has exactly 5 stages', 'customize a PPLCNetConfig with custom block_configs, reduction, and class_expand values', 'configure a PPLCNetConfig with specific out_indices and out_features for multi-scale outputs', 'create a PPLCNetImageProcessor instance with custom resize_short and size_divisor settings', 'run the PPLCNetImageProcessor _preprocess method to resize, crop, rescale, normalize, and convert RGB to BGR', 'test the PPLCNetImageProcessor get_image_size method to compute target dimensions preserving aspect ratio', 'build batched image preprocessing with grouped resizing and center cropping for PPLCNet', 'review the PPLCNetImageProcessorKwargs TypedDict defining resize_short and size_divisor configuration options', 'create a PPLCNetBackbone model for feature extraction from image tensors', 'create a PPLCNetForImageClassification model for image classification with configurable number of labels', 'build a PPLCNetEncoder with stem convolution and depthwise separable convolution stages', 'test the Squeeze-and-Excitation module that performs adaptive channel-wise feature recalibration', 'run a depthwise separable convolution layer with optional SE module for lightweight feature extraction', 'build a depthwise separable convolution layer with optional squeeze-excitation module for lightweight feature extraction']
```

Usage

```
{'create_PPLCNetBackbone': 'create a PPLCNetBackbone model for feature extraction from image tensors', 'create_PPLCNetForImageClassification': 'create a PPLCNetForImageClassification model for image classification with configurable number of labels', 'build_PPLCNetEncoder': 'build a PPLCNetEncoder with stem convolution and depthwise separable convolution stages', 'test_PPLCNetSqueezeExcitationModule': 'test the Squeeze-and-Excitation module that performs adaptive channel-wise feature recalibration', 'run_PPLCNetDepthwiseSeparableConvLayer': 'run a depthwise separable convolution layer with optional SE module for lightweight feature extraction'}
```

## File: huggingface_transformers/src/transformers/models/pp_lcnet/modular_pp_lcnet.py

Prompts

```
['create a PPLCNetConfig instance with custom scale, block_configs, and stem_channels parameters', 'build a PPLCNetConfig using default block configs with scale 1.0 and hardswish activation', 'validate a PPLCNetConfig architecture ensuring block_configs has exactly 5 stages', 'customize a PPLCNetConfig with custom block_configs, reduction, and class_expand values', 'configure a PPLCNetConfig with specific out_indices and out_features for multi-scale outputs', 'create a PPLCNetImageProcessor instance with custom resize_short and size_divisor settings', 'run the PPLCNetImageProcessor _preprocess method to resize, crop, rescale, normalize, and convert RGB to BGR', 'test the PPLCNetImageProcessor get_image_size method to compute target dimensions preserving aspect ratio', 'build batched image preprocessing with grouped resizing and center cropping for PPLCNet', 'review the PPLCNetImageProcessorKwargs TypedDict defining resize_short and size_divisor configuration options', 'create a PPLCNetBackbone model for feature extraction from image tensors', 'create a PPLCNetForImageClassification model for image classification with configurable number of labels', 'build a PPLCNetEncoder with stem convolution and depthwise separable convolution stages', 'test the Squeeze-and-Excitation module that performs adaptive channel-wise feature recalibration', 'run a depthwise separable convolution layer with optional SE module for lightweight feature extraction', 'build a depthwise separable convolution layer with optional squeeze-excitation module for lightweight feature extraction']
```

Usage

```
{'create_PPLCNetConfig': 'create a PPLCNetConfig with configurable scale, block configs, and stem parameters for PP-LCNet architecture', 'create_PPLCNetImageProcessor': 'create a PPLCNetImageProcessor that resizes, crops, normalizes, and converts images from RGB to BGR for model input', 'create_PPLCNetBackbone': 'create a PPLCNetBackbone model for multi-stage feature map extraction from image tensors', 'create_PPLCNetForImageClassification': 'create a PPLCNetForImageClassification model with adaptive pooling, classification head, and configurable number of labels', 'build_PPLCNetDepthwiseSeparableConvLayer': 'build a depthwise separable convolution layer with optional squeeze-excitation module for lightweight feature extraction'}
```


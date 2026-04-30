# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/bridgetower/image_processing_bridgetower.py

Prompts

```
['create a BridgeTowerImageProcessor instance for preprocessing images with CLIP normalization and padding', 'resize a torch tensor image to a shortest edge with size_divisor alignment for BridgeTower input', 'calculate the output height and width for an image resized to a shortest edge with size_divisor rounding', 'preprocess a batch of torch tensor images with resize, center crop, rescale, normalize, and pad for BridgeTower', 'configure BridgeTowerImageProcessorKwargs with a custom size_divisor value for image dimension alignment', 'create a BridgeTowerImageProcessorPil instance to preprocess images for the BridgeTower multimodal model', 'run get_resize_output_image_size to compute resized height and width with size_divisor alignment for an input image', 'test the BridgeTowerImageProcessorPil resize method to resize images to a shortest edge with size_divisor padding', 'summarize the BridgeTowerImageProcessorPil _preprocess method that applies resize, crop, rescale, normalize, and pad to image batches', 'review the BridgeTowerImageProcessorKwargs TypedDict that defines optional size_divisor configuration for the image processor', 'build a BridgeTowerModel to extract joint text and image features from multimodal inputs', 'create a BridgeTowerForMaskedLM model to perform masked language modeling on text with image context', 'run BridgeTowerForContrastiveLearning to compute image-text contrastive loss with normalized embeddings', 'test BridgeTowerForImageAndTextRetrieval to classify whether an image and text pair match', 'review the BridgeTowerPreTrainedModel base class for initializing and managing BridgeTower model weights']
```

Usage

```
{'create_bridgetower_image_processor': 'create a BridgeTowerImageProcessor instance for preprocessing images with CLIP normalization and padding', 'resize_image_bridgetower': 'resize a torch tensor image to a shortest edge with size_divisor alignment for BridgeTower input', 'calculate_resize_output_size': 'calculate the output height and width for an image resized to a shortest edge with size_divisor rounding', 'preprocess_bridgetower_images': 'preprocess a batch of torch tensor images with resize, center crop, rescale, normalize, and pad for BridgeTower', 'configure_size_divisor_kwargs': 'configure BridgeTowerImageProcessorKwargs with a custom size_divisor value for image dimension alignment'}
```

## File: huggingface_transformers/src/transformers/models/bridgetower/image_processing_pil_bridgetower.py

Prompts

```
['create a BridgeTowerImageProcessor instance for preprocessing images with CLIP normalization and padding', 'resize a torch tensor image to a shortest edge with size_divisor alignment for BridgeTower input', 'calculate the output height and width for an image resized to a shortest edge with size_divisor rounding', 'preprocess a batch of torch tensor images with resize, center crop, rescale, normalize, and pad for BridgeTower', 'configure BridgeTowerImageProcessorKwargs with a custom size_divisor value for image dimension alignment', 'create a BridgeTowerImageProcessorPil instance to preprocess images for the BridgeTower multimodal model', 'run get_resize_output_image_size to compute resized height and width with size_divisor alignment for an input image', 'test the BridgeTowerImageProcessorPil resize method to resize images to a shortest edge with size_divisor padding', 'summarize the BridgeTowerImageProcessorPil _preprocess method that applies resize, crop, rescale, normalize, and pad to image batches', 'review the BridgeTowerImageProcessorKwargs TypedDict that defines optional size_divisor configuration for the image processor', 'build a BridgeTowerModel to extract joint text and image features from multimodal inputs', 'create a BridgeTowerForMaskedLM model to perform masked language modeling on text with image context', 'run BridgeTowerForContrastiveLearning to compute image-text contrastive loss with normalized embeddings', 'test BridgeTowerForImageAndTextRetrieval to classify whether an image and text pair match', 'review the BridgeTowerPreTrainedModel base class for initializing and managing BridgeTower model weights']
```

Usage

```
{'create_BridgeTowerImageProcessorPil': 'create a BridgeTowerImageProcessorPil instance to preprocess images for the BridgeTower multimodal model', 'run_get_resize_output_image_size': 'run get_resize_output_image_size to compute resized height and width with size_divisor alignment for an input image', 'test_BridgeTowerImageProcessorPil_resize': 'test the BridgeTowerImageProcessorPil resize method to resize images to a shortest edge with size_divisor padding', 'summarize_BridgeTowerImageProcessorPil__preprocess': 'summarize the BridgeTowerImageProcessorPil _preprocess method that applies resize, crop, rescale, normalize, and pad to image batches', 'review_BridgeTowerImageProcessorKwargs': 'review the BridgeTowerImageProcessorKwargs TypedDict that defines optional size_divisor configuration for the image processor'}
```

## File: huggingface_transformers/src/transformers/models/bridgetower/modeling_bridgetower.py

Prompts

```
['create a BridgeTowerImageProcessor instance for preprocessing images with CLIP normalization and padding', 'resize a torch tensor image to a shortest edge with size_divisor alignment for BridgeTower input', 'calculate the output height and width for an image resized to a shortest edge with size_divisor rounding', 'preprocess a batch of torch tensor images with resize, center crop, rescale, normalize, and pad for BridgeTower', 'configure BridgeTowerImageProcessorKwargs with a custom size_divisor value for image dimension alignment', 'create a BridgeTowerImageProcessorPil instance to preprocess images for the BridgeTower multimodal model', 'run get_resize_output_image_size to compute resized height and width with size_divisor alignment for an input image', 'test the BridgeTowerImageProcessorPil resize method to resize images to a shortest edge with size_divisor padding', 'summarize the BridgeTowerImageProcessorPil _preprocess method that applies resize, crop, rescale, normalize, and pad to image batches', 'review the BridgeTowerImageProcessorKwargs TypedDict that defines optional size_divisor configuration for the image processor', 'build a BridgeTowerModel to extract joint text and image features from multimodal inputs', 'create a BridgeTowerForMaskedLM model to perform masked language modeling on text with image context', 'run BridgeTowerForContrastiveLearning to compute image-text contrastive loss with normalized embeddings', 'test BridgeTowerForImageAndTextRetrieval to classify whether an image and text pair match', 'review the BridgeTowerPreTrainedModel base class for initializing and managing BridgeTower model weights']
```

Usage

```
{'build_bridgetower_model': 'build a BridgeTowerModel to extract joint text and image features from multimodal inputs', 'create_masked_lm_bridgetower': 'create a BridgeTowerForMaskedLM model to perform masked language modeling on text with image context', 'run_contrastive_learning': 'run BridgeTowerForContrastiveLearning to compute image-text contrastive loss with normalized embeddings', 'test_image_text_retrieval': 'test BridgeTowerForImageAndTextRetrieval to classify whether an image and text pair match', 'review_bridgetower_pretrained_model': 'review the BridgeTowerPreTrainedModel base class for initializing and managing BridgeTower model weights'}
```


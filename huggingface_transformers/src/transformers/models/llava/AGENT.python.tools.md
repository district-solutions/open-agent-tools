# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/llava/convert_llava_weights_to_hf.py

Prompts

```
['run the CLI script to convert LLaVA model weights from original format to HuggingFace format', 'build a conversion pipeline that loads original LLaVA state dict and transforms keys to HuggingFace format', 'create a HuggingFace LlavaForConditionalGeneration model with converted weights and push to hub', 'summarize how the state dict keys are mapped from original LLaVA naming to HuggingFace naming conventions', 'review the convert_state_dict_to_hf function that applies KEYS_TO_MODIFY_MAPPING transformations to state dict keys', 'create an LlavaImageProcessor instance to preprocess images for LLaVa multimodal models', 'pad non-square torch tensor images to square using the longest edge and a background color', 'preprocess a batch of images with resize, center crop, rescale, and normalize for LLaVa input', 'resize a batch of images grouped by shape for efficient batched processing', 'center crop images and apply rescale and normalize using OpenAI CLIP mean and std', 'create a LlavaImageProcessorPil instance for preprocessing images with LLaVa vision-language model pipeline', 'run pad_to_square on a numpy image array to center-pad it to a square with configurable background color', 'run _preprocess on a list of numpy image arrays to resize, crop, rescale, and normalize for LLaVa model input', 'test the LlavaImageProcessorPil class default configuration with BICUBIC resampling and 224x224 crop size', 'review the LlavaImageProcessorPil PIL backend class and its image preprocessing pipeline methods', 'build a LlavaModel instance with a vision tower and language model for multimodal processing', 'create a LlavaForConditionalGeneration model with vision backbone and language model for image-text generation', 'run get_image_features to extract projected image hidden states from pixel values using the vision tower', 'test get_placeholder_mask to verify image token count matches image feature dimensions', 'review prepare_inputs_for_generation to conditionally forward pixel values only on the first iteration']
```

Usage

```
{'run_convert_llava_weights': 'run the CLI script to convert LLaVA model weights from original format to HuggingFace format', 'build_llava_conversion_pipeline': 'build a conversion pipeline that loads original LLaVA state dict and transforms keys to HuggingFace format', 'create_hf_llava_model': 'create a HuggingFace LlavaForConditionalGeneration model with converted weights and push to hub', 'summarize_state_dict_conversion': 'summarize how the state dict keys are mapped from original LLaVA naming to HuggingFace naming conventions', 'review_convert_state_dict_to_hf': 'review the convert_state_dict_to_hf function that applies KEYS_TO_MODIFY_MAPPING transformations to state dict keys'}
```

## File: huggingface_transformers/src/transformers/models/llava/image_processing_llava.py

Prompts

```
['run the CLI script to convert LLaVA model weights from original format to HuggingFace format', 'build a conversion pipeline that loads original LLaVA state dict and transforms keys to HuggingFace format', 'create a HuggingFace LlavaForConditionalGeneration model with converted weights and push to hub', 'summarize how the state dict keys are mapped from original LLaVA naming to HuggingFace naming conventions', 'review the convert_state_dict_to_hf function that applies KEYS_TO_MODIFY_MAPPING transformations to state dict keys', 'create an LlavaImageProcessor instance to preprocess images for LLaVa multimodal models', 'pad non-square torch tensor images to square using the longest edge and a background color', 'preprocess a batch of images with resize, center crop, rescale, and normalize for LLaVa input', 'resize a batch of images grouped by shape for efficient batched processing', 'center crop images and apply rescale and normalize using OpenAI CLIP mean and std', 'create a LlavaImageProcessorPil instance for preprocessing images with LLaVa vision-language model pipeline', 'run pad_to_square on a numpy image array to center-pad it to a square with configurable background color', 'run _preprocess on a list of numpy image arrays to resize, crop, rescale, and normalize for LLaVa model input', 'test the LlavaImageProcessorPil class default configuration with BICUBIC resampling and 224x224 crop size', 'review the LlavaImageProcessorPil PIL backend class and its image preprocessing pipeline methods', 'build a LlavaModel instance with a vision tower and language model for multimodal processing', 'create a LlavaForConditionalGeneration model with vision backbone and language model for image-text generation', 'run get_image_features to extract projected image hidden states from pixel values using the vision tower', 'test get_placeholder_mask to verify image token count matches image feature dimensions', 'review prepare_inputs_for_generation to conditionally forward pixel values only on the first iteration']
```

Usage

```
{'create_LlavaImageProcessor': 'create an LlavaImageProcessor instance to preprocess images for LLaVa multimodal models', 'pad_to_square_images': 'pad non-square torch tensor images to square using the longest edge and a background color', 'preprocess_image_batch': 'preprocess a batch of images with resize, center crop, rescale, and normalize for LLaVa input', 'resize_image_batch': 'resize a batch of images grouped by shape for efficient batched processing', 'center_crop_and_normalize': 'center crop images and apply rescale and normalize using OpenAI CLIP mean and std'}
```

## File: huggingface_transformers/src/transformers/models/llava/image_processing_pil_llava.py

Prompts

```
['run the CLI script to convert LLaVA model weights from original format to HuggingFace format', 'build a conversion pipeline that loads original LLaVA state dict and transforms keys to HuggingFace format', 'create a HuggingFace LlavaForConditionalGeneration model with converted weights and push to hub', 'summarize how the state dict keys are mapped from original LLaVA naming to HuggingFace naming conventions', 'review the convert_state_dict_to_hf function that applies KEYS_TO_MODIFY_MAPPING transformations to state dict keys', 'create an LlavaImageProcessor instance to preprocess images for LLaVa multimodal models', 'pad non-square torch tensor images to square using the longest edge and a background color', 'preprocess a batch of images with resize, center crop, rescale, and normalize for LLaVa input', 'resize a batch of images grouped by shape for efficient batched processing', 'center crop images and apply rescale and normalize using OpenAI CLIP mean and std', 'create a LlavaImageProcessorPil instance for preprocessing images with LLaVa vision-language model pipeline', 'run pad_to_square on a numpy image array to center-pad it to a square with configurable background color', 'run _preprocess on a list of numpy image arrays to resize, crop, rescale, and normalize for LLaVa model input', 'test the LlavaImageProcessorPil class default configuration with BICUBIC resampling and 224x224 crop size', 'review the LlavaImageProcessorPil PIL backend class and its image preprocessing pipeline methods', 'build a LlavaModel instance with a vision tower and language model for multimodal processing', 'create a LlavaForConditionalGeneration model with vision backbone and language model for image-text generation', 'run get_image_features to extract projected image hidden states from pixel values using the vision tower', 'test get_placeholder_mask to verify image token count matches image feature dimensions', 'review prepare_inputs_for_generation to conditionally forward pixel values only on the first iteration']
```

Usage

```
{'create_LlavaImageProcessorPil': 'create a LlavaImageProcessorPil instance for preprocessing images with LLaVa vision-language model pipeline', 'run_pad_to_square': 'run pad_to_square on a numpy image array to center-pad it to a square with configurable background color', 'run_preprocess_images': 'run _preprocess on a list of numpy image arrays to resize, crop, rescale, and normalize for LLaVa model input', 'test_LlavaImageProcessorPil_defaults': 'test the LlavaImageProcessorPil class default configuration with BICUBIC resampling and 224x224 crop size', 'review_LlavaImageProcessorPil_backend': 'review the LlavaImageProcessorPil PIL backend class and its image preprocessing pipeline methods'}
```

## File: huggingface_transformers/src/transformers/models/llava/modeling_llava.py

Prompts

```
['run the CLI script to convert LLaVA model weights from original format to HuggingFace format', 'build a conversion pipeline that loads original LLaVA state dict and transforms keys to HuggingFace format', 'create a HuggingFace LlavaForConditionalGeneration model with converted weights and push to hub', 'summarize how the state dict keys are mapped from original LLaVA naming to HuggingFace naming conventions', 'review the convert_state_dict_to_hf function that applies KEYS_TO_MODIFY_MAPPING transformations to state dict keys', 'create an LlavaImageProcessor instance to preprocess images for LLaVa multimodal models', 'pad non-square torch tensor images to square using the longest edge and a background color', 'preprocess a batch of images with resize, center crop, rescale, and normalize for LLaVa input', 'resize a batch of images grouped by shape for efficient batched processing', 'center crop images and apply rescale and normalize using OpenAI CLIP mean and std', 'create a LlavaImageProcessorPil instance for preprocessing images with LLaVa vision-language model pipeline', 'run pad_to_square on a numpy image array to center-pad it to a square with configurable background color', 'run _preprocess on a list of numpy image arrays to resize, crop, rescale, and normalize for LLaVa model input', 'test the LlavaImageProcessorPil class default configuration with BICUBIC resampling and 224x224 crop size', 'review the LlavaImageProcessorPil PIL backend class and its image preprocessing pipeline methods', 'build a LlavaModel instance with a vision tower and language model for multimodal processing', 'create a LlavaForConditionalGeneration model with vision backbone and language model for image-text generation', 'run get_image_features to extract projected image hidden states from pixel values using the vision tower', 'test get_placeholder_mask to verify image token count matches image feature dimensions', 'review prepare_inputs_for_generation to conditionally forward pixel values only on the first iteration']
```

Usage

```
{'build_llava_model': 'build a LlavaModel instance with a vision tower and language model for multimodal processing', 'create_llava_for_conditional_generation': 'create a LlavaForConditionalGeneration model with vision backbone and language model for image-text generation', 'run_get_image_features': 'run get_image_features to extract projected image hidden states from pixel values using the vision tower', 'test_get_placeholder_mask': 'test get_placeholder_mask to verify image token count matches image feature dimensions', 'review_prepare_inputs_for_generation': 'review prepare_inputs_for_generation to conditionally forward pixel values only on the first iteration'}
```


# Agent Python Tools

- repo: huggingface/text-generation-inference
- repo_uri: https://github.com/huggingface/text-generation-inference.git

## File: huggingface_text-generation-inference/server/text_generation_server/models/custom_modeling/gemma3/image_processing_gemma3.py

Prompts

```
['create a Gemma3ImageProcessor instance with custom resize, normalize, and pan_and_scan settings', 'preprocess images for Gemma3 using resize, rescale, normalize, and pan_and_scan transformations', 'apply pan_and_scan cropping to split wide or tall images into multiple crops', 'configure the Gemma3ImageProcessor with custom image_mean and image_std normalization values', 'review the Gemma3ImageProcessor class and its preprocess method for image preprocessing logic', 'create a Gemma3Processor instance with a custom image processor and tokenizer for multimodal processing', 'call the Gemma3Processor with text and images to get tokenized input and image features as a BatchFeature', 'use Gemma3Processor batch_decode to decode a batch of token IDs back into text strings', 'use Gemma3Processor decode to decode a single token ID sequence back into text', 'review the Gemma3ProcessorKwargs defaults for pan-and-scan image cropping settings and text padding options', 'check if a list contains valid images using is_valid_list_of_images', 'convert a single image or flat list of images into a nested list format', 'pass through an already batched list of lists of images unchanged', 'wrap a single PIL image in a double nested list for batch processing', 'convert a 4D numpy array of images into a nested list structure']
```

Usage

```
{'create_gemma3_image_processor': 'create a Gemma3ImageProcessor instance with custom resize, normalize, and pan_and_scan settings', 'preprocess_images_for_gemma3': 'preprocess images for Gemma3 using resize, rescale, normalize, and pan_and_scan transformations', 'apply_pan_and_scan_cropping': 'apply pan_and_scan cropping to split wide or tall images into multiple crops', 'configure_gemma3_normalization': 'configure the Gemma3ImageProcessor with custom image_mean and image_std normalization values', 'review_gemma3_image_processor': 'review the Gemma3ImageProcessor class and its preprocess method for image preprocessing logic'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/models/custom_modeling/gemma3/processing_gemma3.py

Prompts

```
['create a Gemma3ImageProcessor instance with custom resize, normalize, and pan_and_scan settings', 'preprocess images for Gemma3 using resize, rescale, normalize, and pan_and_scan transformations', 'apply pan_and_scan cropping to split wide or tall images into multiple crops', 'configure the Gemma3ImageProcessor with custom image_mean and image_std normalization values', 'review the Gemma3ImageProcessor class and its preprocess method for image preprocessing logic', 'create a Gemma3Processor instance with a custom image processor and tokenizer for multimodal processing', 'call the Gemma3Processor with text and images to get tokenized input and image features as a BatchFeature', 'use Gemma3Processor batch_decode to decode a batch of token IDs back into text strings', 'use Gemma3Processor decode to decode a single token ID sequence back into text', 'review the Gemma3ProcessorKwargs defaults for pan-and-scan image cropping settings and text padding options', 'check if a list contains valid images using is_valid_list_of_images', 'convert a single image or flat list of images into a nested list format', 'pass through an already batched list of lists of images unchanged', 'wrap a single PIL image in a double nested list for batch processing', 'convert a 4D numpy array of images into a nested list structure']
```

Usage

```
{'create_gemma3_processor': 'create a Gemma3Processor instance with a custom image processor and tokenizer for multimodal processing', 'call_gemma3_processor': 'call the Gemma3Processor with text and images to get tokenized input and image features as a BatchFeature', 'batch_decode_gemma3': 'use Gemma3Processor batch_decode to decode a batch of token IDs back into text strings', 'decode_gemma3': 'use Gemma3Processor decode to decode a single token ID sequence back into text', 'review_gemma3_processor_kwargs': 'review the Gemma3ProcessorKwargs defaults for pan-and-scan image cropping settings and text padding options'}
```

## File: huggingface_text-generation-inference/server/text_generation_server/models/custom_modeling/gemma3/utils.py

Prompts

```
['create a Gemma3ImageProcessor instance with custom resize, normalize, and pan_and_scan settings', 'preprocess images for Gemma3 using resize, rescale, normalize, and pan_and_scan transformations', 'apply pan_and_scan cropping to split wide or tall images into multiple crops', 'configure the Gemma3ImageProcessor with custom image_mean and image_std normalization values', 'review the Gemma3ImageProcessor class and its preprocess method for image preprocessing logic', 'create a Gemma3Processor instance with a custom image processor and tokenizer for multimodal processing', 'call the Gemma3Processor with text and images to get tokenized input and image features as a BatchFeature', 'use Gemma3Processor batch_decode to decode a batch of token IDs back into text strings', 'use Gemma3Processor decode to decode a single token ID sequence back into text', 'review the Gemma3ProcessorKwargs defaults for pan-and-scan image cropping settings and text padding options', 'check if a list contains valid images using is_valid_list_of_images', 'convert a single image or flat list of images into a nested list format', 'pass through an already batched list of lists of images unchanged', 'wrap a single PIL image in a double nested list for batch processing', 'convert a 4D numpy array of images into a nested list structure']
```

Usage

```
{'validate_list_of_images': 'check if a list contains valid images using is_valid_list_of_images', 'normalize_images_to_nested_list': 'convert a single image or flat list of images into a nested list format', 'handle_batched_images': 'pass through an already batched list of lists of images unchanged', 'convert_single_pil_image': 'wrap a single PIL image in a double nested list for batch processing', 'convert_4d_array_images': 'convert a 4D numpy array of images into a nested list structure'}
```


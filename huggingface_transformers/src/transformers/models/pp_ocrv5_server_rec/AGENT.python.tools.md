# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pp_ocrv5_server_rec/image_processing_pp_ocrv5_server_rec.py

Prompts

```
['create a PPOCRV5ServerRecImageProcessor instance for text recognition image preprocessing', 'run the image processor _preprocess method to resize, normalize, and pad a batch of images into pixel values', 'run the image processor get_target_size method to calculate target dimensions from a list of image shapes', 'run the image processor post_process_text_recognition method to decode model logits into recognized text strings with confidence scores', 'review the PPOCRV5ServerRecImageProcessorKwargs typed dict for max_image_width and character_list configuration options', 'build a PPOCRV5ServerRecForTextRecognition model for scene text recognition from pixel values', 'create a PPOCRV5ServerRecModel backbone that extracts feature maps and applies average pooling', 'run the PPOCRV5ServerRecEncoderWithSVTR encoder with conv blocks and SVTR transformer blocks', 'test the eager_attention_forward function for multi-headed attention with query key and value tensors', 'review the PPOCRV5ServerRecHead that applies SVTR encoder and softmax classification head', 'create a PPOCRV5ServerRecForTextRecognition model from a config for scene text recognition', 'build a text recognition pipeline using PPOCRV5ServerRecConfig and PPOCRV5ServerRecImageProcessor', 'run text recognition on a batch of images using PPOCRV5ServerRecForTextRecognition and get decoded text results', 'process images with PPOCRV5ServerRecImageProcessor to resize, normalize, and pad for text recognition input', 'summarize the PPOCRV5ServerRecEncoderWithSVTR class that implements SVTR for scene text recognition']
```

Usage

```
{'create_image_processor_pp_ocrv5_server_rec': 'create a PPOCRV5ServerRecImageProcessor instance for text recognition image preprocessing', 'run_image_processor_preprocess': 'run the image processor _preprocess method to resize, normalize, and pad a batch of images into pixel values', 'run_image_processor_get_target_size': 'run the image processor get_target_size method to calculate target dimensions from a list of image shapes', 'run_image_processor_post_process_text': 'run the image processor post_process_text_recognition method to decode model logits into recognized text strings with confidence scores', 'review_image_processor_kwargs': 'review the PPOCRV5ServerRecImageProcessorKwargs typed dict for max_image_width and character_list configuration options'}
```

## File: huggingface_transformers/src/transformers/models/pp_ocrv5_server_rec/modeling_pp_ocrv5_server_rec.py

Prompts

```
['create a PPOCRV5ServerRecImageProcessor instance for text recognition image preprocessing', 'run the image processor _preprocess method to resize, normalize, and pad a batch of images into pixel values', 'run the image processor get_target_size method to calculate target dimensions from a list of image shapes', 'run the image processor post_process_text_recognition method to decode model logits into recognized text strings with confidence scores', 'review the PPOCRV5ServerRecImageProcessorKwargs typed dict for max_image_width and character_list configuration options', 'build a PPOCRV5ServerRecForTextRecognition model for scene text recognition from pixel values', 'create a PPOCRV5ServerRecModel backbone that extracts feature maps and applies average pooling', 'run the PPOCRV5ServerRecEncoderWithSVTR encoder with conv blocks and SVTR transformer blocks', 'test the eager_attention_forward function for multi-headed attention with query key and value tensors', 'review the PPOCRV5ServerRecHead that applies SVTR encoder and softmax classification head', 'create a PPOCRV5ServerRecForTextRecognition model from a config for scene text recognition', 'build a text recognition pipeline using PPOCRV5ServerRecConfig and PPOCRV5ServerRecImageProcessor', 'run text recognition on a batch of images using PPOCRV5ServerRecForTextRecognition and get decoded text results', 'process images with PPOCRV5ServerRecImageProcessor to resize, normalize, and pad for text recognition input', 'summarize the PPOCRV5ServerRecEncoderWithSVTR class that implements SVTR for scene text recognition']
```

Usage

```
{'build_text_recognition_model': 'build a PPOCRV5ServerRecForTextRecognition model for scene text recognition from pixel values', 'create_model_backbone': 'create a PPOCRV5ServerRecModel backbone that extracts feature maps and applies average pooling', 'run_encoder_svtr': 'run the PPOCRV5ServerRecEncoderWithSVTR encoder with conv blocks and SVTR transformer blocks', 'test_attention_forward': 'test the eager_attention_forward function for multi-headed attention with query key and value tensors', 'review_text_recognition_head': 'review the PPOCRV5ServerRecHead that applies SVTR encoder and softmax classification head'}
```

## File: huggingface_transformers/src/transformers/models/pp_ocrv5_server_rec/modular_pp_ocrv5_server_rec.py

Prompts

```
['create a PPOCRV5ServerRecImageProcessor instance for text recognition image preprocessing', 'run the image processor _preprocess method to resize, normalize, and pad a batch of images into pixel values', 'run the image processor get_target_size method to calculate target dimensions from a list of image shapes', 'run the image processor post_process_text_recognition method to decode model logits into recognized text strings with confidence scores', 'review the PPOCRV5ServerRecImageProcessorKwargs typed dict for max_image_width and character_list configuration options', 'build a PPOCRV5ServerRecForTextRecognition model for scene text recognition from pixel values', 'create a PPOCRV5ServerRecModel backbone that extracts feature maps and applies average pooling', 'run the PPOCRV5ServerRecEncoderWithSVTR encoder with conv blocks and SVTR transformer blocks', 'test the eager_attention_forward function for multi-headed attention with query key and value tensors', 'review the PPOCRV5ServerRecHead that applies SVTR encoder and softmax classification head', 'create a PPOCRV5ServerRecForTextRecognition model from a config for scene text recognition', 'build a text recognition pipeline using PPOCRV5ServerRecConfig and PPOCRV5ServerRecImageProcessor', 'run text recognition on a batch of images using PPOCRV5ServerRecForTextRecognition and get decoded text results', 'process images with PPOCRV5ServerRecImageProcessor to resize, normalize, and pad for text recognition input', 'summarize the PPOCRV5ServerRecEncoderWithSVTR class that implements SVTR for scene text recognition']
```

Usage

```
{'create_text_recognition_model': 'create a PPOCRV5ServerRecForTextRecognition model from a config for scene text recognition', 'build_text_recognition_pipeline': 'build a text recognition pipeline using PPOCRV5ServerRecConfig and PPOCRV5ServerRecImageProcessor', 'run_text_recognition_on_images': 'run text recognition on a batch of images using PPOCRV5ServerRecForTextRecognition and get decoded text results', 'process_images_for_recognition': 'process images with PPOCRV5ServerRecImageProcessor to resize, normalize, and pad for text recognition input', 'summarize_svtr_encoder': 'summarize the PPOCRV5ServerRecEncoderWithSVTR class that implements SVTR for scene text recognition'}
```


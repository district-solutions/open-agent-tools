# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/video_llava/convert_video_llava_weights_to_hf.py

Prompts

```
['convert Video-LLaVA model weights from LanguageBind format to HuggingFace format using text model, vision model, and state dict IDs', 'convert a Video-LLaVA state dict to HuggingFace key naming convention by remapping module prefixes', 'build a VideoLlavaProcessor with tokenizer extended for <image> and <video> tokens and a CLIP image processor', 'resize VideoLlava token embeddings by sampling from the pre-expansion embedding distribution for new tokens', 'run the Video-LLaVA weight conversion CLI with text_model_id, vision_model_id, output_hub_path, and old_state_dict_id arguments', 'create a VideoLlavaImageProcessor with custom resize size, crop size, and normalization settings', 'build an image preprocessing pipeline that resizes, crops, rescales, and normalizes images for Video-LLaVA', 'test the VideoLlavaImageProcessor resize method to scale images by shortest edge while preserving aspect ratio', 'review the VideoLlavaImageProcessor preprocess method that handles batch image preprocessing with configurable transforms', 'summarize the VideoLlavaImageProcessor class that preprocesses images for the Video-LLaVA multimodal model', 'generate a description for a video using VideoLlavaForConditionalGeneration with pixel_values_videos input', 'build an inference pipeline for VideoLlavaForConditionalGeneration that processes images and videos with language model output', 'extract image features from VideoLlavaModel using get_image_features with pixel_values_images and vision_feature_layer', 'extract video features from VideoLlavaModel using get_video_features with pixel_values_videos and vision_feature_layer', 'compute the language modeling loss for VideoLlavaForConditionalGeneration using forward pass with labels for next-token prediction']
```

Usage

```
{'convert_video_llava_weights_to_hf': 'convert Video-LLaVA model weights from LanguageBind format to HuggingFace format using text model, vision model, and state dict IDs', 'convert_state_dict_to_hf': 'convert a Video-LLaVA state dict to HuggingFace key naming convention by remapping module prefixes', 'build_video_llava_processor': 'build a VideoLlavaProcessor with tokenizer extended for <image> and <video> tokens and a CLIP image processor', 'resize_video_llava_embeddings': 'resize VideoLlava token embeddings by sampling from the pre-expansion embedding distribution for new tokens', 'run_convert_cli': 'run the Video-LLaVA weight conversion CLI with text_model_id, vision_model_id, output_hub_path, and old_state_dict_id arguments'}
```

## File: huggingface_transformers/src/transformers/models/video_llava/image_processing_video_llava.py

Prompts

```
['convert Video-LLaVA model weights from LanguageBind format to HuggingFace format using text model, vision model, and state dict IDs', 'convert a Video-LLaVA state dict to HuggingFace key naming convention by remapping module prefixes', 'build a VideoLlavaProcessor with tokenizer extended for <image> and <video> tokens and a CLIP image processor', 'resize VideoLlava token embeddings by sampling from the pre-expansion embedding distribution for new tokens', 'run the Video-LLaVA weight conversion CLI with text_model_id, vision_model_id, output_hub_path, and old_state_dict_id arguments', 'create a VideoLlavaImageProcessor with custom resize size, crop size, and normalization settings', 'build an image preprocessing pipeline that resizes, crops, rescales, and normalizes images for Video-LLaVA', 'test the VideoLlavaImageProcessor resize method to scale images by shortest edge while preserving aspect ratio', 'review the VideoLlavaImageProcessor preprocess method that handles batch image preprocessing with configurable transforms', 'summarize the VideoLlavaImageProcessor class that preprocesses images for the Video-LLaVA multimodal model', 'generate a description for a video using VideoLlavaForConditionalGeneration with pixel_values_videos input', 'build an inference pipeline for VideoLlavaForConditionalGeneration that processes images and videos with language model output', 'extract image features from VideoLlavaModel using get_image_features with pixel_values_images and vision_feature_layer', 'extract video features from VideoLlavaModel using get_video_features with pixel_values_videos and vision_feature_layer', 'compute the language modeling loss for VideoLlavaForConditionalGeneration using forward pass with labels for next-token prediction']
```

Usage

```
{'create_video_llava_image_processor': 'create a VideoLlavaImageProcessor with custom resize size, crop size, and normalization settings', 'build_image_preprocess_pipeline': 'build an image preprocessing pipeline that resizes, crops, rescales, and normalizes images for Video-LLaVA', 'test_video_llava_resize': 'test the VideoLlavaImageProcessor resize method to scale images by shortest edge while preserving aspect ratio', 'review_video_llava_preprocess': 'review the VideoLlavaImageProcessor preprocess method that handles batch image preprocessing with configurable transforms', 'summarize_video_llava_processor': 'summarize the VideoLlavaImageProcessor class that preprocesses images for the Video-LLaVA multimodal model'}
```

## File: huggingface_transformers/src/transformers/models/video_llava/modeling_video_llava.py

Prompts

```
['convert Video-LLaVA model weights from LanguageBind format to HuggingFace format using text model, vision model, and state dict IDs', 'convert a Video-LLaVA state dict to HuggingFace key naming convention by remapping module prefixes', 'build a VideoLlavaProcessor with tokenizer extended for <image> and <video> tokens and a CLIP image processor', 'resize VideoLlava token embeddings by sampling from the pre-expansion embedding distribution for new tokens', 'run the Video-LLaVA weight conversion CLI with text_model_id, vision_model_id, output_hub_path, and old_state_dict_id arguments', 'create a VideoLlavaImageProcessor with custom resize size, crop size, and normalization settings', 'build an image preprocessing pipeline that resizes, crops, rescales, and normalizes images for Video-LLaVA', 'test the VideoLlavaImageProcessor resize method to scale images by shortest edge while preserving aspect ratio', 'review the VideoLlavaImageProcessor preprocess method that handles batch image preprocessing with configurable transforms', 'summarize the VideoLlavaImageProcessor class that preprocesses images for the Video-LLaVA multimodal model', 'generate a description for a video using VideoLlavaForConditionalGeneration with pixel_values_videos input', 'build an inference pipeline for VideoLlavaForConditionalGeneration that processes images and videos with language model output', 'extract image features from VideoLlavaModel using get_image_features with pixel_values_images and vision_feature_layer', 'extract video features from VideoLlavaModel using get_video_features with pixel_values_videos and vision_feature_layer', 'compute the language modeling loss for VideoLlavaForConditionalGeneration using forward pass with labels for next-token prediction']
```

Usage

```
{'generate_video_description': 'generate a description for a video using VideoLlavaForConditionalGeneration with pixel_values_videos input', 'build_multimodal_inference_pipeline': 'build an inference pipeline for VideoLlavaForConditionalGeneration that processes images and videos with language model output', 'extract_image_features': 'extract image features from VideoLlavaModel using get_image_features with pixel_values_images and vision_feature_layer', 'extract_video_features': 'extract video features from VideoLlavaModel using get_video_features with pixel_values_videos and vision_feature_layer', 'compute_training_loss': 'compute the language modeling loss for VideoLlavaForConditionalGeneration using forward pass with labels for next-token prediction'}
```


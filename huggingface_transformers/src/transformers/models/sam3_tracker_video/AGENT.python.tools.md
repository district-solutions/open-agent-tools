# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/sam3_tracker_video/configuration_sam3_tracker_video.py

Prompts

```
['create a Sam3TrackerVideoConfig with default vision, prompt encoder, and mask decoder configs', 'build a Sam3TrackerVideoConfig with custom vision, prompt encoder, and mask decoder configs', 'create a Sam3TrackerVideoPromptEncoderConfig with custom hidden size, image size, and scale parameters', 'create a Sam3TrackerVideoMaskDecoderConfig with custom MLP dim, attention heads, and multimask output settings', 'test the Sam3TrackerVideoConfig __post_init__ method to initialize sub-configs and compute feature sizes', 'build a Sam3TrackerVideoModel from a Sam3TrackerVideoConfig for video object segmentation and tracking', 'run the Sam3TrackerVideoModel forward method to propagate objects through a streamed video frame', 'create a Sam3TrackerVideoInferenceSession for managing video inference state, caching, and object tracking', 'run propagate_in_video_iterator on Sam3TrackerVideoModel to yield segmentation outputs for each frame in a video', 'test the Sam3TrackerVideoMaskDecoder class that predicts masks given image and prompt embeddings', 'run get_image_features on a Sam3TrackerVideoModel to extract vision encoder feature maps and positional embeddings', 'test a Sam3TrackerVideoInferenceSession for video sequence inference with memory caching', 'review the Sam3TrackerVideoMaskDecoderConfig class and its mask decoder configuration parameters', 'initialize a video inference session for SAM3 Tracker with configurable devices and dtype', 'add points, boxes, or masks to a video inference session for a specific frame and object IDs', 'process and add point or box prompts to a video frame in the inference session', 'process and add mask inputs to a video frame in the inference session', 'post-process output masks by removing padding and upscaling to original image size']
```

Usage

```
{'create_Sam3TrackerVideoConfig': 'create a Sam3TrackerVideoConfig with default vision, prompt encoder, and mask decoder configs', 'build_Sam3TrackerVideoConfig_custom': 'build a Sam3TrackerVideoConfig with custom vision, prompt encoder, and mask decoder configs', 'create_Sam3TrackerVideoPromptEncoderConfig': 'create a Sam3TrackerVideoPromptEncoderConfig with custom hidden size, image size, and scale parameters', 'create_Sam3TrackerVideoMaskDecoderConfig': 'create a Sam3TrackerVideoMaskDecoderConfig with custom MLP dim, attention heads, and multimask output settings', 'test_Sam3TrackerVideoConfig_post_init': 'test the Sam3TrackerVideoConfig __post_init__ method to initialize sub-configs and compute feature sizes'}
```

## File: huggingface_transformers/src/transformers/models/sam3_tracker_video/modeling_sam3_tracker_video.py

Prompts

```
['create a Sam3TrackerVideoConfig with default vision, prompt encoder, and mask decoder configs', 'build a Sam3TrackerVideoConfig with custom vision, prompt encoder, and mask decoder configs', 'create a Sam3TrackerVideoPromptEncoderConfig with custom hidden size, image size, and scale parameters', 'create a Sam3TrackerVideoMaskDecoderConfig with custom MLP dim, attention heads, and multimask output settings', 'test the Sam3TrackerVideoConfig __post_init__ method to initialize sub-configs and compute feature sizes', 'build a Sam3TrackerVideoModel from a Sam3TrackerVideoConfig for video object segmentation and tracking', 'run the Sam3TrackerVideoModel forward method to propagate objects through a streamed video frame', 'create a Sam3TrackerVideoInferenceSession for managing video inference state, caching, and object tracking', 'run propagate_in_video_iterator on Sam3TrackerVideoModel to yield segmentation outputs for each frame in a video', 'test the Sam3TrackerVideoMaskDecoder class that predicts masks given image and prompt embeddings', 'run get_image_features on a Sam3TrackerVideoModel to extract vision encoder feature maps and positional embeddings', 'test a Sam3TrackerVideoInferenceSession for video sequence inference with memory caching', 'review the Sam3TrackerVideoMaskDecoderConfig class and its mask decoder configuration parameters', 'initialize a video inference session for SAM3 Tracker with configurable devices and dtype', 'add points, boxes, or masks to a video inference session for a specific frame and object IDs', 'process and add point or box prompts to a video frame in the inference session', 'process and add mask inputs to a video frame in the inference session', 'post-process output masks by removing padding and upscaling to original image size']
```

Usage

```
{'build_Sam3TrackerVideoModel': 'build a Sam3TrackerVideoModel from a Sam3TrackerVideoConfig for video object segmentation and tracking', 'run_Sam3TrackerVideoModel_forward': 'run the Sam3TrackerVideoModel forward method to propagate objects through a streamed video frame', 'create_Sam3TrackerVideoInferenceSession': 'create a Sam3TrackerVideoInferenceSession for managing video inference state, caching, and object tracking', 'run_Sam3TrackerVideoModel_propagate_in_video_iterator': 'run propagate_in_video_iterator on Sam3TrackerVideoModel to yield segmentation outputs for each frame in a video', 'test_Sam3TrackerVideoMaskDecoder': 'test the Sam3TrackerVideoMaskDecoder class that predicts masks given image and prompt embeddings'}
```

## File: huggingface_transformers/src/transformers/models/sam3_tracker_video/modular_sam3_tracker_video.py

Prompts

```
['create a Sam3TrackerVideoConfig with default vision, prompt encoder, and mask decoder configs', 'build a Sam3TrackerVideoConfig with custom vision, prompt encoder, and mask decoder configs', 'create a Sam3TrackerVideoPromptEncoderConfig with custom hidden size, image size, and scale parameters', 'create a Sam3TrackerVideoMaskDecoderConfig with custom MLP dim, attention heads, and multimask output settings', 'test the Sam3TrackerVideoConfig __post_init__ method to initialize sub-configs and compute feature sizes', 'build a Sam3TrackerVideoModel from a Sam3TrackerVideoConfig for video object segmentation and tracking', 'run the Sam3TrackerVideoModel forward method to propagate objects through a streamed video frame', 'create a Sam3TrackerVideoInferenceSession for managing video inference state, caching, and object tracking', 'run propagate_in_video_iterator on Sam3TrackerVideoModel to yield segmentation outputs for each frame in a video', 'test the Sam3TrackerVideoMaskDecoder class that predicts masks given image and prompt embeddings', 'run get_image_features on a Sam3TrackerVideoModel to extract vision encoder feature maps and positional embeddings', 'test a Sam3TrackerVideoInferenceSession for video sequence inference with memory caching', 'review the Sam3TrackerVideoMaskDecoderConfig class and its mask decoder configuration parameters', 'initialize a video inference session for SAM3 Tracker with configurable devices and dtype', 'add points, boxes, or masks to a video inference session for a specific frame and object IDs', 'process and add point or box prompts to a video frame in the inference session', 'process and add mask inputs to a video frame in the inference session', 'post-process output masks by removing padding and upscaling to original image size']
```

Usage

```
{'create_Sam3TrackerVideoConfig': 'create a Sam3TrackerVideoConfig instance with default or custom vision, prompt encoder, and mask decoder configurations', 'build_Sam3TrackerVideoModel': 'build a Sam3TrackerVideoModel from a Sam3TrackerVideoConfig with optional vision encoder removal', 'run_get_image_features': 'run get_image_features on a Sam3TrackerVideoModel to extract vision encoder feature maps and positional embeddings', 'test_Sam3TrackerVideoInferenceSession': 'test a Sam3TrackerVideoInferenceSession for video sequence inference with memory caching', 'review_Sam3TrackerVideoMaskDecoderConfig': 'review the Sam3TrackerVideoMaskDecoderConfig class and its mask decoder configuration parameters'}
```

## File: huggingface_transformers/src/transformers/models/sam3_tracker_video/processing_sam3_tracker_video.py

Prompts

```
['create a Sam3TrackerVideoConfig with default vision, prompt encoder, and mask decoder configs', 'build a Sam3TrackerVideoConfig with custom vision, prompt encoder, and mask decoder configs', 'create a Sam3TrackerVideoPromptEncoderConfig with custom hidden size, image size, and scale parameters', 'create a Sam3TrackerVideoMaskDecoderConfig with custom MLP dim, attention heads, and multimask output settings', 'test the Sam3TrackerVideoConfig __post_init__ method to initialize sub-configs and compute feature sizes', 'build a Sam3TrackerVideoModel from a Sam3TrackerVideoConfig for video object segmentation and tracking', 'run the Sam3TrackerVideoModel forward method to propagate objects through a streamed video frame', 'create a Sam3TrackerVideoInferenceSession for managing video inference state, caching, and object tracking', 'run propagate_in_video_iterator on Sam3TrackerVideoModel to yield segmentation outputs for each frame in a video', 'test the Sam3TrackerVideoMaskDecoder class that predicts masks given image and prompt embeddings', 'run get_image_features on a Sam3TrackerVideoModel to extract vision encoder feature maps and positional embeddings', 'test a Sam3TrackerVideoInferenceSession for video sequence inference with memory caching', 'review the Sam3TrackerVideoMaskDecoderConfig class and its mask decoder configuration parameters', 'initialize a video inference session for SAM3 Tracker with configurable devices and dtype', 'add points, boxes, or masks to a video inference session for a specific frame and object IDs', 'process and add point or box prompts to a video frame in the inference session', 'process and add mask inputs to a video frame in the inference session', 'post-process output masks by removing padding and upscaling to original image size']
```

Usage

```
{'init_video_session': 'initialize a video inference session for SAM3 Tracker with configurable devices and dtype', 'add_inputs_to_inference_session': 'add points, boxes, or masks to a video inference session for a specific frame and object IDs', 'process_new_points_or_boxes_for_video_frame': 'process and add point or box prompts to a video frame in the inference session', 'process_new_mask_for_video_frame': 'process and add mask inputs to a video frame in the inference session', 'post_process_masks': 'post-process output masks by removing padding and upscaling to original image size'}
```


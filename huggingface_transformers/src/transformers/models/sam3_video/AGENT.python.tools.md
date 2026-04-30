# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/sam3_video/configuration_sam3_video.py

Prompts

```
['create a Sam3VideoConfig instance with default detector and tracker sub-configs', 'build a Sam3VideoConfig by passing detector_config and tracker_config as dictionaries', 'test the validate_architecture method to check hotstart parameter consistency', 'read the image_size property from a Sam3VideoConfig instance', 'set the image_size property to propagate the value to nested detector and tracker configs', 'convert a SAM3 checkpoint from original Meta format to HuggingFace format and save to output directory', 'split combined QKV weight projections into separate q_proj, k_proj, v_proj tensors in a state dict', 'convert original SAM3 checkpoint keys to HuggingFace model key names using regex mapping patterns', 'load a SAM3 checkpoint file and extract the state dict from model, state_dict, or top-level format', 'create a Sam3VideoConfig with optional vision and text configuration overrides', 'create a Sam3VideoInferenceSession to manage video inference state, frames, and object tracking', 'run Sam3VideoModel forward propagation to detect and track objects through video frames', 'build a Sam3VideoModel propagate_in_video_iterator to yield segmentation outputs for each frame in a video', 'test the nms_masks function that applies non-maximum suppression to filter overlapping detection masks', 'test the fill_holes_in_mask_scores function that removes small holes and sprinkles from segmentation masks', 'init a video inference session for SAM3-Video with configurable devices and dtype', 'add text prompts to a SAM3-Video inference session for segmentation', 'post-process SAM3-Video model outputs to extract masks, boxes, and scores', 'call the SAM3-Video processor to encode images and segmentation maps', 'apply non-overlapping constraints to segmentation masks to suppress overlapping regions']
```

Usage

```
{'create_Sam3VideoConfig': 'create a Sam3VideoConfig instance with default detector and tracker sub-configs', 'build_Sam3VideoConfig_with_dict': 'build a Sam3VideoConfig by passing detector_config and tracker_config as dictionaries', 'test_validate_architecture': 'test the validate_architecture method to check hotstart parameter consistency', 'read_image_size': 'read the image_size property from a Sam3VideoConfig instance', 'set_image_size': 'set the image_size property to propagate the value to nested detector and tracker configs'}
```

## File: huggingface_transformers/src/transformers/models/sam3_video/convert_sam3_video_to_hf.py

Prompts

```
['create a Sam3VideoConfig instance with default detector and tracker sub-configs', 'build a Sam3VideoConfig by passing detector_config and tracker_config as dictionaries', 'test the validate_architecture method to check hotstart parameter consistency', 'read the image_size property from a Sam3VideoConfig instance', 'set the image_size property to propagate the value to nested detector and tracker configs', 'convert a SAM3 checkpoint from original Meta format to HuggingFace format and save to output directory', 'split combined QKV weight projections into separate q_proj, k_proj, v_proj tensors in a state dict', 'convert original SAM3 checkpoint keys to HuggingFace model key names using regex mapping patterns', 'load a SAM3 checkpoint file and extract the state dict from model, state_dict, or top-level format', 'create a Sam3VideoConfig with optional vision and text configuration overrides', 'create a Sam3VideoInferenceSession to manage video inference state, frames, and object tracking', 'run Sam3VideoModel forward propagation to detect and track objects through video frames', 'build a Sam3VideoModel propagate_in_video_iterator to yield segmentation outputs for each frame in a video', 'test the nms_masks function that applies non-maximum suppression to filter overlapping detection masks', 'test the fill_holes_in_mask_scores function that removes small holes and sprinkles from segmentation masks', 'init a video inference session for SAM3-Video with configurable devices and dtype', 'add text prompts to a SAM3-Video inference session for segmentation', 'post-process SAM3-Video model outputs to extract masks, boxes, and scores', 'call the SAM3-Video processor to encode images and segmentation maps', 'apply non-overlapping constraints to segmentation masks to suppress overlapping regions']
```

Usage

```
{'convert_sam3_checkpoint': 'convert a SAM3 checkpoint from original Meta format to HuggingFace format and save to output directory', 'split_qkv_weights': 'split combined QKV weight projections into separate q_proj, k_proj, v_proj tensors in a state dict', 'convert_old_keys_to_new_keys': 'convert original SAM3 checkpoint keys to HuggingFace model key names using regex mapping patterns', 'load_original_state_dict': 'load a SAM3 checkpoint file and extract the state dict from model, state_dict, or top-level format', 'get_sam3_video_config': 'create a Sam3VideoConfig with optional vision and text configuration overrides'}
```

## File: huggingface_transformers/src/transformers/models/sam3_video/modeling_sam3_video.py

Prompts

```
['create a Sam3VideoConfig instance with default detector and tracker sub-configs', 'build a Sam3VideoConfig by passing detector_config and tracker_config as dictionaries', 'test the validate_architecture method to check hotstart parameter consistency', 'read the image_size property from a Sam3VideoConfig instance', 'set the image_size property to propagate the value to nested detector and tracker configs', 'convert a SAM3 checkpoint from original Meta format to HuggingFace format and save to output directory', 'split combined QKV weight projections into separate q_proj, k_proj, v_proj tensors in a state dict', 'convert original SAM3 checkpoint keys to HuggingFace model key names using regex mapping patterns', 'load a SAM3 checkpoint file and extract the state dict from model, state_dict, or top-level format', 'create a Sam3VideoConfig with optional vision and text configuration overrides', 'create a Sam3VideoInferenceSession to manage video inference state, frames, and object tracking', 'run Sam3VideoModel forward propagation to detect and track objects through video frames', 'build a Sam3VideoModel propagate_in_video_iterator to yield segmentation outputs for each frame in a video', 'test the nms_masks function that applies non-maximum suppression to filter overlapping detection masks', 'test the fill_holes_in_mask_scores function that removes small holes and sprinkles from segmentation masks', 'init a video inference session for SAM3-Video with configurable devices and dtype', 'add text prompts to a SAM3-Video inference session for segmentation', 'post-process SAM3-Video model outputs to extract masks, boxes, and scores', 'call the SAM3-Video processor to encode images and segmentation maps', 'apply non-overlapping constraints to segmentation masks to suppress overlapping regions']
```

Usage

```
{'create_sam3_video_inference_session': 'create a Sam3VideoInferenceSession to manage video inference state, frames, and object tracking', 'run_sam3_video_propagation': 'run Sam3VideoModel forward propagation to detect and track objects through video frames', 'build_sam3_video_propagate_iterator': 'build a Sam3VideoModel propagate_in_video_iterator to yield segmentation outputs for each frame in a video', 'test_nms_masks_post_processing': 'test the nms_masks function that applies non-maximum suppression to filter overlapping detection masks', 'test_fill_holes_in_mask_scores': 'test the fill_holes_in_mask_scores function that removes small holes and sprinkles from segmentation masks'}
```

## File: huggingface_transformers/src/transformers/models/sam3_video/processing_sam3_video.py

Prompts

```
['create a Sam3VideoConfig instance with default detector and tracker sub-configs', 'build a Sam3VideoConfig by passing detector_config and tracker_config as dictionaries', 'test the validate_architecture method to check hotstart parameter consistency', 'read the image_size property from a Sam3VideoConfig instance', 'set the image_size property to propagate the value to nested detector and tracker configs', 'convert a SAM3 checkpoint from original Meta format to HuggingFace format and save to output directory', 'split combined QKV weight projections into separate q_proj, k_proj, v_proj tensors in a state dict', 'convert original SAM3 checkpoint keys to HuggingFace model key names using regex mapping patterns', 'load a SAM3 checkpoint file and extract the state dict from model, state_dict, or top-level format', 'create a Sam3VideoConfig with optional vision and text configuration overrides', 'create a Sam3VideoInferenceSession to manage video inference state, frames, and object tracking', 'run Sam3VideoModel forward propagation to detect and track objects through video frames', 'build a Sam3VideoModel propagate_in_video_iterator to yield segmentation outputs for each frame in a video', 'test the nms_masks function that applies non-maximum suppression to filter overlapping detection masks', 'test the fill_holes_in_mask_scores function that removes small holes and sprinkles from segmentation masks', 'init a video inference session for SAM3-Video with configurable devices and dtype', 'add text prompts to a SAM3-Video inference session for segmentation', 'post-process SAM3-Video model outputs to extract masks, boxes, and scores', 'call the SAM3-Video processor to encode images and segmentation maps', 'apply non-overlapping constraints to segmentation masks to suppress overlapping regions']
```

Usage

```
{'init_video_session': 'init a video inference session for SAM3-Video with configurable devices and dtype', 'add_text_prompt': 'add text prompts to a SAM3-Video inference session for segmentation', 'postprocess_outputs': 'post-process SAM3-Video model outputs to extract masks, boxes, and scores', 'call_processor': 'call the SAM3-Video processor to encode images and segmentation maps', 'apply_non_overlapping_constraints': 'apply non-overlapping constraints to segmentation masks to suppress overlapping regions'}
```


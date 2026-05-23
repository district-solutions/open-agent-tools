# Agent Python Tools

- repo: facebookresearch/sam2
- repo_uri: https://github.com/facebookresearch/sam2

## File: facebookresearch_sam2/sam2/automatic_mask_generator.py

Prompts

```
['generate segmentation masks for an entire image using SAM2AutomaticMaskGenerator with a SAM2 model', 'load a pretrained SAM2AutomaticMaskGenerator from a Hugging Face model repository ID', 'postprocess mask data to remove small disconnected regions and holes below a minimum area threshold', 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs and point prompts', 'configure a SAM2AutomaticMaskGenerator with custom thresholds for IoU, stability score, and NMS filtering', 'build a SAM 2 model from a Hydra config file and optional checkpoint path', 'build a SAM 2 video predictor model for segmenting objects in video frames', 'build a SAM 2 model by downloading config and weights from a Hugging Face model ID', 'build a SAM 2 video predictor by downloading config and weights from Hugging Face', 'load a PyTorch checkpoint into a SAM 2 model and validate keys match', 'build a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'create image embeddings by calling set_image with a numpy array or PIL Image', 'predict segmentation masks from point prompts, box prompts, or mask input using predict', 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get the image embedding tensor for the currently set image using get_image_embedding', 'initialize a SAM2 video predictor inference state by loading video frames from a video path', 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add a binary mask input to a specific frame to guide object tracking in the video', 'propagate object tracking across all video frames starting from conditioned frames with user inputs', 'remove a tracked object by its ID from the video predictor inference state', 'load a pretrained SAM2 video predictor model from a Hugging Face hub repository ID', 'propagate object tracking inputs across all video frames and yield per-frame mask predictions']
```

Usage

```
{'generate_masks_for_image': 'generate segmentation masks for an entire image using SAM2AutomaticMaskGenerator with a SAM2 model', 'load_pretrained_mask_generator': 'load a pretrained SAM2AutomaticMaskGenerator from a Hugging Face model repository ID', 'postprocess_small_regions': 'postprocess mask data to remove small disconnected regions and holes below a minimum area threshold', 'refine_masks_with_m2m': 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs and point prompts', 'configure_mask_generator': 'configure a SAM2AutomaticMaskGenerator with custom thresholds for IoU, stability score, and NMS filtering'}
```

## File: facebookresearch_sam2/sam2/build_sam.py

Prompts

```
['generate segmentation masks for an entire image using SAM2AutomaticMaskGenerator with a SAM2 model', 'load a pretrained SAM2AutomaticMaskGenerator from a Hugging Face model repository ID', 'postprocess mask data to remove small disconnected regions and holes below a minimum area threshold', 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs and point prompts', 'configure a SAM2AutomaticMaskGenerator with custom thresholds for IoU, stability score, and NMS filtering', 'build a SAM 2 model from a Hydra config file and optional checkpoint path', 'build a SAM 2 video predictor model for segmenting objects in video frames', 'build a SAM 2 model by downloading config and weights from a Hugging Face model ID', 'build a SAM 2 video predictor by downloading config and weights from Hugging Face', 'load a PyTorch checkpoint into a SAM 2 model and validate keys match', 'build a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'create image embeddings by calling set_image with a numpy array or PIL Image', 'predict segmentation masks from point prompts, box prompts, or mask input using predict', 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get the image embedding tensor for the currently set image using get_image_embedding', 'initialize a SAM2 video predictor inference state by loading video frames from a video path', 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add a binary mask input to a specific frame to guide object tracking in the video', 'propagate object tracking across all video frames starting from conditioned frames with user inputs', 'remove a tracked object by its ID from the video predictor inference state', 'load a pretrained SAM2 video predictor model from a Hugging Face hub repository ID', 'propagate object tracking inputs across all video frames and yield per-frame mask predictions']
```

Usage

```
{'build_sam2_model': 'build a SAM 2 model from a Hydra config file and optional checkpoint path', 'build_sam2_video_predictor': 'build a SAM 2 video predictor model for segmenting objects in video frames', 'build_sam2_hf': 'build a SAM 2 model by downloading config and weights from a Hugging Face model ID', 'build_sam2_video_predictor_hf': 'build a SAM 2 video predictor by downloading config and weights from Hugging Face', 'load_checkpoint_sam2': 'load a PyTorch checkpoint into a SAM 2 model and validate keys match'}
```

## File: facebookresearch_sam2/sam2/sam2_image_predictor.py

Prompts

```
['generate segmentation masks for an entire image using SAM2AutomaticMaskGenerator with a SAM2 model', 'load a pretrained SAM2AutomaticMaskGenerator from a Hugging Face model repository ID', 'postprocess mask data to remove small disconnected regions and holes below a minimum area threshold', 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs and point prompts', 'configure a SAM2AutomaticMaskGenerator with custom thresholds for IoU, stability score, and NMS filtering', 'build a SAM 2 model from a Hydra config file and optional checkpoint path', 'build a SAM 2 video predictor model for segmenting objects in video frames', 'build a SAM 2 model by downloading config and weights from a Hugging Face model ID', 'build a SAM 2 video predictor by downloading config and weights from Hugging Face', 'load a PyTorch checkpoint into a SAM 2 model and validate keys match', 'build a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'create image embeddings by calling set_image with a numpy array or PIL Image', 'predict segmentation masks from point prompts, box prompts, or mask input using predict', 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get the image embedding tensor for the currently set image using get_image_embedding', 'initialize a SAM2 video predictor inference state by loading video frames from a video path', 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add a binary mask input to a specific frame to guide object tracking in the video', 'propagate object tracking across all video frames starting from conditioned frames with user inputs', 'remove a tracked object by its ID from the video predictor inference state', 'load a pretrained SAM2 video predictor model from a Hugging Face hub repository ID', 'propagate object tracking inputs across all video frames and yield per-frame mask predictions']
```

Usage

```
{'build_sam2_predictor_from_pretrained': 'build a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'create_image_embedding': 'create image embeddings by calling set_image with a numpy array or PIL Image', 'predict_masks_from_prompts': 'predict segmentation masks from point prompts, box prompts, or mask input using predict', 'predict_batch_masks': 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get_image_embedding': 'get the image embedding tensor for the currently set image using get_image_embedding'}
```

## File: facebookresearch_sam2/sam2/sam2_video_predictor.py

Prompts

```
['generate segmentation masks for an entire image using SAM2AutomaticMaskGenerator with a SAM2 model', 'load a pretrained SAM2AutomaticMaskGenerator from a Hugging Face model repository ID', 'postprocess mask data to remove small disconnected regions and holes below a minimum area threshold', 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs and point prompts', 'configure a SAM2AutomaticMaskGenerator with custom thresholds for IoU, stability score, and NMS filtering', 'build a SAM 2 model from a Hydra config file and optional checkpoint path', 'build a SAM 2 video predictor model for segmenting objects in video frames', 'build a SAM 2 model by downloading config and weights from a Hugging Face model ID', 'build a SAM 2 video predictor by downloading config and weights from Hugging Face', 'load a PyTorch checkpoint into a SAM 2 model and validate keys match', 'build a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'create image embeddings by calling set_image with a numpy array or PIL Image', 'predict segmentation masks from point prompts, box prompts, or mask input using predict', 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get the image embedding tensor for the currently set image using get_image_embedding', 'initialize a SAM2 video predictor inference state by loading video frames from a video path', 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add a binary mask input to a specific frame to guide object tracking in the video', 'propagate object tracking across all video frames starting from conditioned frames with user inputs', 'remove a tracked object by its ID from the video predictor inference state', 'load a pretrained SAM2 video predictor model from a Hugging Face hub repository ID', 'propagate object tracking inputs across all video frames and yield per-frame mask predictions']
```

Usage

```
{'init_video_tracking_state': 'initialize a SAM2 video predictor inference state by loading video frames from a video path', 'add_points_or_box_to_frame': 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add_mask_to_frame': 'add a binary mask input to a specific frame to guide object tracking in the video', 'propagate_tracking_in_video': 'propagate object tracking across all video frames starting from conditioned frames with user inputs', 'remove_object_from_tracking': 'remove a tracked object by its ID from the video predictor inference state'}
```

## File: facebookresearch_sam2/sam2/sam2_video_predictor_legacy.py

Prompts

```
['generate segmentation masks for an entire image using SAM2AutomaticMaskGenerator with a SAM2 model', 'load a pretrained SAM2AutomaticMaskGenerator from a Hugging Face model repository ID', 'postprocess mask data to remove small disconnected regions and holes below a minimum area threshold', 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs and point prompts', 'configure a SAM2AutomaticMaskGenerator with custom thresholds for IoU, stability score, and NMS filtering', 'build a SAM 2 model from a Hydra config file and optional checkpoint path', 'build a SAM 2 video predictor model for segmenting objects in video frames', 'build a SAM 2 model by downloading config and weights from a Hugging Face model ID', 'build a SAM 2 video predictor by downloading config and weights from Hugging Face', 'load a PyTorch checkpoint into a SAM 2 model and validate keys match', 'build a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'create image embeddings by calling set_image with a numpy array or PIL Image', 'predict segmentation masks from point prompts, box prompts, or mask input using predict', 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get the image embedding tensor for the currently set image using get_image_embedding', 'initialize a SAM2 video predictor inference state by loading video frames from a video path', 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add a binary mask input to a specific frame to guide object tracking in the video', 'propagate object tracking across all video frames starting from conditioned frames with user inputs', 'remove a tracked object by its ID from the video predictor inference state', 'load a pretrained SAM2 video predictor model from a Hugging Face hub repository ID', 'propagate object tracking inputs across all video frames and yield per-frame mask predictions']
```

Usage

```
{'init_video_tracking_state': 'initialize a SAM2VideoPredictor inference state by loading video frames from a given video path', 'load_pretrained_predictor': 'load a pretrained SAM2 video predictor model from a Hugging Face hub repository ID', 'add_points_or_box_to_frame': 'add new point clicks or a bounding box prompt to a specific video frame for object tracking', 'add_mask_to_frame': 'add a binary mask input to a specific video frame to guide object segmentation and tracking', 'propagate_tracking_across_video': 'propagate object tracking inputs across all video frames and yield per-frame mask predictions'}
```


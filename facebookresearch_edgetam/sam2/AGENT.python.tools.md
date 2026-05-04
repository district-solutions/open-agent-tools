# Agent Python Tools

- repo: facebookresearch/edgetam
- repo_uri: https://github.com/facebookresearch/edgetam

## File: facebookresearch_edgetam/sam2/automatic_mask_generator.py

Prompts

```
['generate segmentation masks for an image using SAM2AutomaticMaskGenerator with default settings', 'load a pretrained SAM2 automatic mask generator from a Hugging Face model ID', 'generate masks using crop layers for finer detail on large images with SAM2', 'postprocess mask data to remove small disconnected regions and holes below a minimum area', 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs', 'build a SAM 2 model from a config file and checkpoint path for image segmentation', 'build a SAM 2 video predictor model from a config file for video segmentation tasks', 'build a SAM 2 model by downloading weights from a Hugging Face model ID', 'build a SAM 2 video predictor by downloading weights from a Hugging Face model ID', 'load a PyTorch checkpoint into a SAM 2 model and validate missing or unexpected keys', 'create a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'set an RGB image on the predictor to compute embeddings for mask prediction', 'predict segmentation masks from point coordinates, labels, or box prompts on a set image', 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get the image embedding tensor for the currently set image from the predictor', 'initialize a SAM2VideoPredictor inference state by loading video frames from a given video path', 'propagate input points across all video frames to track objects throughout the entire video', 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add a binary mask input to a specific frame to correct or refine tracked object segmentation', 'remove an object id from the tracking state and update masks for remaining tracked objects']
```

Usage

```
{'generate_masks_for_image': 'generate segmentation masks for an image using SAM2AutomaticMaskGenerator with default settings', 'load_pretrained_mask_generator': 'load a pretrained SAM2 automatic mask generator from a Hugging Face model ID', 'generate_masks_with_crop_layers': 'generate masks using crop layers for finer detail on large images with SAM2', 'postprocess_small_regions': 'postprocess mask data to remove small disconnected regions and holes below a minimum area', 'refine_masks_with_m2m': 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs'}
```

## File: facebookresearch_edgetam/sam2/build_sam.py

Prompts

```
['generate segmentation masks for an image using SAM2AutomaticMaskGenerator with default settings', 'load a pretrained SAM2 automatic mask generator from a Hugging Face model ID', 'generate masks using crop layers for finer detail on large images with SAM2', 'postprocess mask data to remove small disconnected regions and holes below a minimum area', 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs', 'build a SAM 2 model from a config file and checkpoint path for image segmentation', 'build a SAM 2 video predictor model from a config file for video segmentation tasks', 'build a SAM 2 model by downloading weights from a Hugging Face model ID', 'build a SAM 2 video predictor by downloading weights from a Hugging Face model ID', 'load a PyTorch checkpoint into a SAM 2 model and validate missing or unexpected keys', 'create a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'set an RGB image on the predictor to compute embeddings for mask prediction', 'predict segmentation masks from point coordinates, labels, or box prompts on a set image', 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get the image embedding tensor for the currently set image from the predictor', 'initialize a SAM2VideoPredictor inference state by loading video frames from a given video path', 'propagate input points across all video frames to track objects throughout the entire video', 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add a binary mask input to a specific frame to correct or refine tracked object segmentation', 'remove an object id from the tracking state and update masks for remaining tracked objects']
```

Usage

```
{'build_sam2_model': 'build a SAM 2 model from a config file and checkpoint path for image segmentation', 'build_sam2_video_predictor': 'build a SAM 2 video predictor model from a config file for video segmentation tasks', 'build_sam2_hf': 'build a SAM 2 model by downloading weights from a Hugging Face model ID', 'build_sam2_video_predictor_hf': 'build a SAM 2 video predictor by downloading weights from a Hugging Face model ID', 'load_checkpoint_sam2': 'load a PyTorch checkpoint into a SAM 2 model and validate missing or unexpected keys'}
```

## File: facebookresearch_edgetam/sam2/sam2_image_predictor.py

Prompts

```
['generate segmentation masks for an image using SAM2AutomaticMaskGenerator with default settings', 'load a pretrained SAM2 automatic mask generator from a Hugging Face model ID', 'generate masks using crop layers for finer detail on large images with SAM2', 'postprocess mask data to remove small disconnected regions and holes below a minimum area', 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs', 'build a SAM 2 model from a config file and checkpoint path for image segmentation', 'build a SAM 2 video predictor model from a config file for video segmentation tasks', 'build a SAM 2 model by downloading weights from a Hugging Face model ID', 'build a SAM 2 video predictor by downloading weights from a Hugging Face model ID', 'load a PyTorch checkpoint into a SAM 2 model and validate missing or unexpected keys', 'create a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'set an RGB image on the predictor to compute embeddings for mask prediction', 'predict segmentation masks from point coordinates, labels, or box prompts on a set image', 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get the image embedding tensor for the currently set image from the predictor', 'initialize a SAM2VideoPredictor inference state by loading video frames from a given video path', 'propagate input points across all video frames to track objects throughout the entire video', 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add a binary mask input to a specific frame to correct or refine tracked object segmentation', 'remove an object id from the tracking state and update masks for remaining tracked objects']
```

Usage

```
{'create_predictor_from_pretrained': 'create a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'set_image_for_prediction': 'set an RGB image on the predictor to compute embeddings for mask prediction', 'predict_masks_from_prompts': 'predict segmentation masks from point coordinates, labels, or box prompts on a set image', 'predict_batch_masks': 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get_image_embedding': 'get the image embedding tensor for the currently set image from the predictor'}
```

## File: facebookresearch_edgetam/sam2/sam2_video_predictor.py

Prompts

```
['generate segmentation masks for an image using SAM2AutomaticMaskGenerator with default settings', 'load a pretrained SAM2 automatic mask generator from a Hugging Face model ID', 'generate masks using crop layers for finer detail on large images with SAM2', 'postprocess mask data to remove small disconnected regions and holes below a minimum area', 'refine mask predictions using mask-to-mask refinement with low resolution mask inputs', 'build a SAM 2 model from a config file and checkpoint path for image segmentation', 'build a SAM 2 video predictor model from a config file for video segmentation tasks', 'build a SAM 2 model by downloading weights from a Hugging Face model ID', 'build a SAM 2 video predictor by downloading weights from a Hugging Face model ID', 'load a PyTorch checkpoint into a SAM 2 model and validate missing or unexpected keys', 'create a SAM2ImagePredictor from a pretrained Hugging Face model using from_pretrained', 'set an RGB image on the predictor to compute embeddings for mask prediction', 'predict segmentation masks from point coordinates, labels, or box prompts on a set image', 'predict segmentation masks for a batch of images using set_image_batch and predict_batch', 'get the image embedding tensor for the currently set image from the predictor', 'initialize a SAM2VideoPredictor inference state by loading video frames from a given video path', 'propagate input points across all video frames to track objects throughout the entire video', 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add a binary mask input to a specific frame to correct or refine tracked object segmentation', 'remove an object id from the tracking state and update masks for remaining tracked objects']
```

Usage

```
{'init_state': 'initialize a SAM2VideoPredictor inference state by loading video frames from a given video path', 'propagate_in_video': 'propagate input points across all video frames to track objects throughout the entire video', 'add_new_points_or_box': 'add new point clicks or a bounding box prompt to a specific frame for object segmentation', 'add_new_mask': 'add a binary mask input to a specific frame to correct or refine tracked object segmentation', 'remove_object': 'remove an object id from the tracking state and update masks for remaining tracked objects'}
```


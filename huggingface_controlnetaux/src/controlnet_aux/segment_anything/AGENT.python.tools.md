# Agent Python Tools

- repo: huggingface/controlnetaux
- repo_uri: https://github.com/huggingface/controlnet_aux

## File: huggingface_controlnetaux/src/controlnet_aux/segment_anything/automatic_mask_generator.py

Prompts

```
['generate masks for an entire image using a SAM model with configurable point grid sampling and quality thresholds', 'create a SamAutomaticMaskGenerator with a SAM model and custom parameters like points_per_side, pred_iou_thresh, and output_mode', 'remove small disconnected regions and holes from mask data using a minimum area threshold and NMS filtering', 'generate masks for a cropped region of an image with batched point prompt processing and duplicate removal', 'set the mask output format to binary_mask, uncompressed_rle, or coco_rle when initializing the mask generator', 'build a SAM model with ViT-Huge image encoder and optional checkpoint weights', 'build a SAM model with ViT-Large image encoder and optional checkpoint weights', 'build a SAM model with ViT-Base image encoder and optional checkpoint weights', 'build a MobileSAM model with TinyViT image encoder and optional checkpoint weights', 'lookup a SAM model builder function by key like vit_h, vit_l, vit_b, or vit_t', 'use SamPredictor to predict segmentation masks from a box prompt on a set image', 'use SamPredictor to predict segmentation masks from point coordinates and labels on a set image', 'use SamPredictor set_image to load an RGB numpy array and compute image embeddings', 'use SamPredictor get_image_embedding to retrieve the 1xCxHxW feature tensor for the set image', 'use SamPredictor reset_image to clear the currently set image and its features']
```

Usage

```
{'generate_masks_from_image': 'generate masks for an entire image using a SAM model with configurable point grid sampling and quality thresholds', 'initialize_mask_generator': 'create a SamAutomaticMaskGenerator with a SAM model and custom parameters like points_per_side, pred_iou_thresh, and output_mode', 'postprocess_small_regions': 'remove small disconnected regions and holes from mask data using a minimum area threshold and NMS filtering', 'process_crop_masks': 'generate masks for a cropped region of an image with batched point prompt processing and duplicate removal', 'configure_output_mode': 'set the mask output format to binary_mask, uncompressed_rle, or coco_rle when initializing the mask generator'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/segment_anything/build_sam.py

Prompts

```
['generate masks for an entire image using a SAM model with configurable point grid sampling and quality thresholds', 'create a SamAutomaticMaskGenerator with a SAM model and custom parameters like points_per_side, pred_iou_thresh, and output_mode', 'remove small disconnected regions and holes from mask data using a minimum area threshold and NMS filtering', 'generate masks for a cropped region of an image with batched point prompt processing and duplicate removal', 'set the mask output format to binary_mask, uncompressed_rle, or coco_rle when initializing the mask generator', 'build a SAM model with ViT-Huge image encoder and optional checkpoint weights', 'build a SAM model with ViT-Large image encoder and optional checkpoint weights', 'build a SAM model with ViT-Base image encoder and optional checkpoint weights', 'build a MobileSAM model with TinyViT image encoder and optional checkpoint weights', 'lookup a SAM model builder function by key like vit_h, vit_l, vit_b, or vit_t', 'use SamPredictor to predict segmentation masks from a box prompt on a set image', 'use SamPredictor to predict segmentation masks from point coordinates and labels on a set image', 'use SamPredictor set_image to load an RGB numpy array and compute image embeddings', 'use SamPredictor get_image_embedding to retrieve the 1xCxHxW feature tensor for the set image', 'use SamPredictor reset_image to clear the currently set image and its features']
```

Usage

```
{'build_sam_vit_h': 'build a SAM model with ViT-Huge image encoder and optional checkpoint weights', 'build_sam_vit_l': 'build a SAM model with ViT-Large image encoder and optional checkpoint weights', 'build_sam_vit_b': 'build a SAM model with ViT-Base image encoder and optional checkpoint weights', 'build_sam_vit_t': 'build a MobileSAM model with TinyViT image encoder and optional checkpoint weights', 'sam_model_registry': 'lookup a SAM model builder function by key like vit_h, vit_l, vit_b, or vit_t'}
```

## File: huggingface_controlnetaux/src/controlnet_aux/segment_anything/predictor.py

Prompts

```
['generate masks for an entire image using a SAM model with configurable point grid sampling and quality thresholds', 'create a SamAutomaticMaskGenerator with a SAM model and custom parameters like points_per_side, pred_iou_thresh, and output_mode', 'remove small disconnected regions and holes from mask data using a minimum area threshold and NMS filtering', 'generate masks for a cropped region of an image with batched point prompt processing and duplicate removal', 'set the mask output format to binary_mask, uncompressed_rle, or coco_rle when initializing the mask generator', 'build a SAM model with ViT-Huge image encoder and optional checkpoint weights', 'build a SAM model with ViT-Large image encoder and optional checkpoint weights', 'build a SAM model with ViT-Base image encoder and optional checkpoint weights', 'build a MobileSAM model with TinyViT image encoder and optional checkpoint weights', 'lookup a SAM model builder function by key like vit_h, vit_l, vit_b, or vit_t', 'use SamPredictor to predict segmentation masks from a box prompt on a set image', 'use SamPredictor to predict segmentation masks from point coordinates and labels on a set image', 'use SamPredictor set_image to load an RGB numpy array and compute image embeddings', 'use SamPredictor get_image_embedding to retrieve the 1xCxHxW feature tensor for the set image', 'use SamPredictor reset_image to clear the currently set image and its features']
```

Usage

```
{'predict_masks_with_box_prompt': 'use SamPredictor to predict segmentation masks from a box prompt on a set image', 'predict_masks_with_point_prompt': 'use SamPredictor to predict segmentation masks from point coordinates and labels on a set image', 'set_image_for_prediction': 'use SamPredictor set_image to load an RGB numpy array and compute image embeddings', 'get_image_embedding': 'use SamPredictor get_image_embedding to retrieve the 1xCxHxW feature tensor for the set image', 'reset_image_state': 'use SamPredictor reset_image to clear the currently set image and its features'}
```


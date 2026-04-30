# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pp_doclayout_v3/image_processing_pp_doclayout_v3.py

Prompts

```
['preprocess a list of torch tensors with resize, center crop, rescale, normalize, and optional padding', 'compute ranked order sequences from stacked order logits using sigmoid activation and vote ranking', 'extract custom polygon vertices from a polygon by detecting sharp angles near 45 degrees and subdividing edges', 'post-process raw object detection outputs into final bounding boxes with polygon points, scores, labels, and order sequences', 'convert binary masks to approximated polygon contours using opencv contour detection and epsilon-based simplification', 'run PPDocLayoutV3ForObjectDetection to detect document layout bounding boxes and class logits from input images', 'create a PPDocLayoutV3Model with a backbone, hybrid encoder, and decoder for document layout analysis', 'build an encoder-decoder pipeline using PPDocLayoutV3HybridEncoder and PPDocLayoutV3Decoder for multi-scale feature processing', 'test contrastive denoising training with noisy labels and bounding boxes for improved model convergence', 'summarize mask_to_box_coordinate to convert binary masks into normalized bounding box coordinates', 'create a PPDocLayoutV3Config with backbone, encoder, decoder, and global pointer head settings for document layout detection', 'build a PPDocLayoutV3MaskFeatFPN with scale heads and FPN blocks for multi-scale mask feature generation', 'extract polygon points from object detection masks by cropping, resizing, and approximating contours with opencv']
```

Usage

```
{'preprocess_images': 'preprocess a list of torch tensors with resize, center crop, rescale, normalize, and optional padding', 'compute_order_sequences': 'compute ranked order sequences from stacked order logits using sigmoid activation and vote ranking', 'extract_custom_vertices': 'extract custom polygon vertices from a polygon by detecting sharp angles near 45 degrees and subdividing edges', 'post_process_object_detection': 'post-process raw object detection outputs into final bounding boxes with polygon points, scores, labels, and order sequences', 'convert_masks_to_polygons': 'convert binary masks to approximated polygon contours using opencv contour detection and epsilon-based simplification'}
```

## File: huggingface_transformers/src/transformers/models/pp_doclayout_v3/modeling_pp_doclayout_v3.py

Prompts

```
['preprocess a list of torch tensors with resize, center crop, rescale, normalize, and optional padding', 'compute ranked order sequences from stacked order logits using sigmoid activation and vote ranking', 'extract custom polygon vertices from a polygon by detecting sharp angles near 45 degrees and subdividing edges', 'post-process raw object detection outputs into final bounding boxes with polygon points, scores, labels, and order sequences', 'convert binary masks to approximated polygon contours using opencv contour detection and epsilon-based simplification', 'run PPDocLayoutV3ForObjectDetection to detect document layout bounding boxes and class logits from input images', 'create a PPDocLayoutV3Model with a backbone, hybrid encoder, and decoder for document layout analysis', 'build an encoder-decoder pipeline using PPDocLayoutV3HybridEncoder and PPDocLayoutV3Decoder for multi-scale feature processing', 'test contrastive denoising training with noisy labels and bounding boxes for improved model convergence', 'summarize mask_to_box_coordinate to convert binary masks into normalized bounding box coordinates', 'create a PPDocLayoutV3Config with backbone, encoder, decoder, and global pointer head settings for document layout detection', 'build a PPDocLayoutV3MaskFeatFPN with scale heads and FPN blocks for multi-scale mask feature generation', 'extract polygon points from object detection masks by cropping, resizing, and approximating contours with opencv']
```

Usage

```
{'run_pp_doclayout_v3_for_detection': 'run PPDocLayoutV3ForObjectDetection to detect document layout bounding boxes and class logits from input images', 'create_pp_doclayout_v3_model': 'create a PPDocLayoutV3Model with a backbone, hybrid encoder, and decoder for document layout analysis', 'build_encoder_decoder_pipeline': 'build an encoder-decoder pipeline using PPDocLayoutV3HybridEncoder and PPDocLayoutV3Decoder for multi-scale feature processing', 'test_contrastive_denoising_training': 'test contrastive denoising training with noisy labels and bounding boxes for improved model convergence', 'summarize_mask_to_box_coordinate': 'summarize mask_to_box_coordinate to convert binary masks into normalized bounding box coordinates'}
```

## File: huggingface_transformers/src/transformers/models/pp_doclayout_v3/modular_pp_doclayout_v3.py

Prompts

```
['preprocess a list of torch tensors with resize, center crop, rescale, normalize, and optional padding', 'compute ranked order sequences from stacked order logits using sigmoid activation and vote ranking', 'extract custom polygon vertices from a polygon by detecting sharp angles near 45 degrees and subdividing edges', 'post-process raw object detection outputs into final bounding boxes with polygon points, scores, labels, and order sequences', 'convert binary masks to approximated polygon contours using opencv contour detection and epsilon-based simplification', 'run PPDocLayoutV3ForObjectDetection to detect document layout bounding boxes and class logits from input images', 'create a PPDocLayoutV3Model with a backbone, hybrid encoder, and decoder for document layout analysis', 'build an encoder-decoder pipeline using PPDocLayoutV3HybridEncoder and PPDocLayoutV3Decoder for multi-scale feature processing', 'test contrastive denoising training with noisy labels and bounding boxes for improved model convergence', 'summarize mask_to_box_coordinate to convert binary masks into normalized bounding box coordinates', 'create a PPDocLayoutV3Config with backbone, encoder, decoder, and global pointer head settings for document layout detection', 'build a PPDocLayoutV3MaskFeatFPN with scale heads and FPN blocks for multi-scale mask feature generation', 'extract polygon points from object detection masks by cropping, resizing, and approximating contours with opencv']
```

Usage

```
{'create_pp_doclayout_v3_config': 'create a PPDocLayoutV3Config with backbone, encoder, decoder, and global pointer head settings for document layout detection', 'run_pp_doclayout_v3_for_detection': 'run PPDocLayoutV3ForObjectDetection to detect document layout bounding boxes, class logits, and reading order from input images', 'build_mask_feature_fpn': 'build a PPDocLayoutV3MaskFeatFPN with scale heads and FPN blocks for multi-scale mask feature generation', 'compute_order_sequences': 'compute ranked reading order sequences from stacked decoder order logits using sigmoid activation and vote ranking', 'extract_polygon_points_from_masks': 'extract polygon points from object detection masks by cropping, resizing, and approximating contours with opencv'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pp_ocrv5_server_det/image_processing_pp_ocrv5_server_det.py

Prompts

```
['create a PPOCRV5ServerDetImageProcessor instance for preprocessing text detection images', 'run post_process_object_detection to convert model logits into detected text bounding boxes', 'get the target resize size for an image using limit_side_len and limit_type parameters', 'build bounding boxes from a binary bitmap segmentation map using contour detection and unclipping', 'summarize the PPOCRV5ServerDetImageProcessor class and its image preprocessing pipeline', 'create a PPOCRV5ServerDetModel for text detection using a configuration object', 'build a PPOCRV5ServerDetForObjectDetection model with segmentation head and local refinement', 'run inference on input images to produce text region probability maps', 'configure the PPOCRV5ServerDetNeck with top-down and bottom-up path aggregation', 'refine initial detection probability maps with local refinement module', 'create a PPOCRV5ServerDetForObjectDetection model from a pretrained config for text detection', 'build a PPOCRV5ServerDetImageProcessor to resize, normalize, and preprocess images for text detection', 'run text detection on images using PPOCRV5ServerDetForObjectDetection and return bounding boxes with scores', 'summarize the PPOCRV5ServerDetNeck large kernel PAN architecture for multi-scale feature fusion', 'review the PPOCRV5ServerDetIntraclassBlock module that captures long-range spatial dependencies with multi-scale convolutions']
```

Usage

```
{'create_ppocrv5_image_processor': 'create a PPOCRV5ServerDetImageProcessor instance for preprocessing text detection images', 'run_post_process_object_detection': 'run post_process_object_detection to convert model logits into detected text bounding boxes', 'get_image_size_for_resize': 'get the target resize size for an image using limit_side_len and limit_type parameters', 'build_text_boxes_from_bitmap': 'build bounding boxes from a binary bitmap segmentation map using contour detection and unclipping', 'summarize_ppocrv5_image_processor': 'summarize the PPOCRV5ServerDetImageProcessor class and its image preprocessing pipeline'}
```

## File: huggingface_transformers/src/transformers/models/pp_ocrv5_server_det/modeling_pp_ocrv5_server_det.py

Prompts

```
['create a PPOCRV5ServerDetImageProcessor instance for preprocessing text detection images', 'run post_process_object_detection to convert model logits into detected text bounding boxes', 'get the target resize size for an image using limit_side_len and limit_type parameters', 'build bounding boxes from a binary bitmap segmentation map using contour detection and unclipping', 'summarize the PPOCRV5ServerDetImageProcessor class and its image preprocessing pipeline', 'create a PPOCRV5ServerDetModel for text detection using a configuration object', 'build a PPOCRV5ServerDetForObjectDetection model with segmentation head and local refinement', 'run inference on input images to produce text region probability maps', 'configure the PPOCRV5ServerDetNeck with top-down and bottom-up path aggregation', 'refine initial detection probability maps with local refinement module', 'create a PPOCRV5ServerDetForObjectDetection model from a pretrained config for text detection', 'build a PPOCRV5ServerDetImageProcessor to resize, normalize, and preprocess images for text detection', 'run text detection on images using PPOCRV5ServerDetForObjectDetection and return bounding boxes with scores', 'summarize the PPOCRV5ServerDetNeck large kernel PAN architecture for multi-scale feature fusion', 'review the PPOCRV5ServerDetIntraclassBlock module that captures long-range spatial dependencies with multi-scale convolutions']
```

Usage

```
{'create_pp_ocrv5_det_model': 'create a PPOCRV5ServerDetModel for text detection using a configuration object', 'build_object_detection_head': 'build a PPOCRV5ServerDetForObjectDetection model with segmentation head and local refinement', 'run_inference_on_images': 'run inference on input images to produce text region probability maps', 'configure_neck_fusion': 'configure the PPOCRV5ServerDetNeck with top-down and bottom-up path aggregation', 'refine_detection_maps': 'refine initial detection probability maps with local refinement module'}
```

## File: huggingface_transformers/src/transformers/models/pp_ocrv5_server_det/modular_pp_ocrv5_server_det.py

Prompts

```
['create a PPOCRV5ServerDetImageProcessor instance for preprocessing text detection images', 'run post_process_object_detection to convert model logits into detected text bounding boxes', 'get the target resize size for an image using limit_side_len and limit_type parameters', 'build bounding boxes from a binary bitmap segmentation map using contour detection and unclipping', 'summarize the PPOCRV5ServerDetImageProcessor class and its image preprocessing pipeline', 'create a PPOCRV5ServerDetModel for text detection using a configuration object', 'build a PPOCRV5ServerDetForObjectDetection model with segmentation head and local refinement', 'run inference on input images to produce text region probability maps', 'configure the PPOCRV5ServerDetNeck with top-down and bottom-up path aggregation', 'refine initial detection probability maps with local refinement module', 'create a PPOCRV5ServerDetForObjectDetection model from a pretrained config for text detection', 'build a PPOCRV5ServerDetImageProcessor to resize, normalize, and preprocess images for text detection', 'run text detection on images using PPOCRV5ServerDetForObjectDetection and return bounding boxes with scores', 'summarize the PPOCRV5ServerDetNeck large kernel PAN architecture for multi-scale feature fusion', 'review the PPOCRV5ServerDetIntraclassBlock module that captures long-range spatial dependencies with multi-scale convolutions']
```

Usage

```
{'create_pp_ocrv5_detection_model': 'create a PPOCRV5ServerDetForObjectDetection model from a pretrained config for text detection', 'build_pp_ocrv5_image_processor': 'build a PPOCRV5ServerDetImageProcessor to resize, normalize, and preprocess images for text detection', 'run_pp_ocrv5_text_detection': 'run text detection on images using PPOCRV5ServerDetForObjectDetection and return bounding boxes with scores', 'summarize_pp_ocrv5_neck_architecture': 'summarize the PPOCRV5ServerDetNeck large kernel PAN architecture for multi-scale feature fusion', 'review_pp_ocrv5_intraclass_block': 'review the PPOCRV5ServerDetIntraclassBlock module that captures long-range spatial dependencies with multi-scale convolutions'}
```


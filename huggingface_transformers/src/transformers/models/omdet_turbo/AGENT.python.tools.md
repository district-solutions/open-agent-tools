# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/omdet_turbo/configuration_omdet_turbo.py

Prompts

```
['create an OmDetTurboConfig instance with default omlab/omdet-turbo-swin-tiny-hf style settings', 'build an OmDetTurboConfig for object detection with custom encoder and decoder dimensions', 'configure the OmDetTurboConfig with a custom swin transformer vision backbone', 'initialize the OmDetTurboConfig with a clip_text_model text encoder configuration', 'export the OmDetTurboConfig to a dictionary excluding internal timm_kwargs', 'convert an OmDet-Turbo checkpoint from the original repository to Hugging Face format', 'get the OmDet-Turbo configuration for a given model name and timm backbone option', 'create rename key mappings for vision backbone state dict keys', 'create rename key mappings for language backbone state dict keys', 'run an end-to-end consistency test on the converted model with a sample image', 'run OmDetTurboForObjectDetection to detect objects in images using class names and task prompts', 'create cached class and task language embeddings using OmDetTurboPreTrainedModel.get_language_embedding', 'build hybrid encoder features with FPN and PAN using OmDetTurboHybridEncoder for multi-scale vision representations', 'test OmDetTurboDecoder to predict bounding boxes and class logits from vision and task features', 'review OmDetTurboMultiscaleDeformableAttention for multi-scale deformable cross-attention in the decoder', 'process images and text labels for OmDet-Turbo object detection using the processor', 'post process raw OmDet-Turbo model outputs into final bounding boxes with text class labels', 'compute sigmoid scores and class indices from predicted class logits tensor', 'clip predicted bounding boxes to image height and width boundaries', 'filter and sort top-k detections, apply confidence thresholding and non-maximum suppression']
```

Usage

```
{'create_omdet_turbo_config': 'create an OmDetTurboConfig instance with default omlab/omdet-turbo-swin-tiny-hf style settings', 'build_omdet_turbo_detection_config': 'build an OmDetTurboConfig for object detection with custom encoder and decoder dimensions', 'configure_omdet_backbone': 'configure the OmDetTurboConfig with a custom swin transformer vision backbone', 'initialize_omdet_text_config': 'initialize the OmDetTurboConfig with a clip_text_model text encoder configuration', 'export_omdet_config_to_dict': 'export the OmDetTurboConfig to a dictionary excluding internal timm_kwargs'}
```

## File: huggingface_transformers/src/transformers/models/omdet_turbo/convert_omdet_turbo_to_hf.py

Prompts

```
['create an OmDetTurboConfig instance with default omlab/omdet-turbo-swin-tiny-hf style settings', 'build an OmDetTurboConfig for object detection with custom encoder and decoder dimensions', 'configure the OmDetTurboConfig with a custom swin transformer vision backbone', 'initialize the OmDetTurboConfig with a clip_text_model text encoder configuration', 'export the OmDetTurboConfig to a dictionary excluding internal timm_kwargs', 'convert an OmDet-Turbo checkpoint from the original repository to Hugging Face format', 'get the OmDet-Turbo configuration for a given model name and timm backbone option', 'create rename key mappings for vision backbone state dict keys', 'create rename key mappings for language backbone state dict keys', 'run an end-to-end consistency test on the converted model with a sample image', 'run OmDetTurboForObjectDetection to detect objects in images using class names and task prompts', 'create cached class and task language embeddings using OmDetTurboPreTrainedModel.get_language_embedding', 'build hybrid encoder features with FPN and PAN using OmDetTurboHybridEncoder for multi-scale vision representations', 'test OmDetTurboDecoder to predict bounding boxes and class logits from vision and task features', 'review OmDetTurboMultiscaleDeformableAttention for multi-scale deformable cross-attention in the decoder', 'process images and text labels for OmDet-Turbo object detection using the processor', 'post process raw OmDet-Turbo model outputs into final bounding boxes with text class labels', 'compute sigmoid scores and class indices from predicted class logits tensor', 'clip predicted bounding boxes to image height and width boundaries', 'filter and sort top-k detections, apply confidence thresholding and non-maximum suppression']
```

Usage

```
{'convert_omdet_turbo_checkpoint': 'convert an OmDet-Turbo checkpoint from the original repository to Hugging Face format', 'get_omdet_turbo_config': 'get the OmDet-Turbo configuration for a given model name and timm backbone option', 'create_rename_keys_vision': 'create rename key mappings for vision backbone state dict keys', 'create_rename_keys_language': 'create rename key mappings for language backbone state dict keys', 'run_test': 'run an end-to-end consistency test on the converted model with a sample image'}
```

## File: huggingface_transformers/src/transformers/models/omdet_turbo/modeling_omdet_turbo.py

Prompts

```
['create an OmDetTurboConfig instance with default omlab/omdet-turbo-swin-tiny-hf style settings', 'build an OmDetTurboConfig for object detection with custom encoder and decoder dimensions', 'configure the OmDetTurboConfig with a custom swin transformer vision backbone', 'initialize the OmDetTurboConfig with a clip_text_model text encoder configuration', 'export the OmDetTurboConfig to a dictionary excluding internal timm_kwargs', 'convert an OmDet-Turbo checkpoint from the original repository to Hugging Face format', 'get the OmDet-Turbo configuration for a given model name and timm backbone option', 'create rename key mappings for vision backbone state dict keys', 'create rename key mappings for language backbone state dict keys', 'run an end-to-end consistency test on the converted model with a sample image', 'run OmDetTurboForObjectDetection to detect objects in images using class names and task prompts', 'create cached class and task language embeddings using OmDetTurboPreTrainedModel.get_language_embedding', 'build hybrid encoder features with FPN and PAN using OmDetTurboHybridEncoder for multi-scale vision representations', 'test OmDetTurboDecoder to predict bounding boxes and class logits from vision and task features', 'review OmDetTurboMultiscaleDeformableAttention for multi-scale deformable cross-attention in the decoder', 'process images and text labels for OmDet-Turbo object detection using the processor', 'post process raw OmDet-Turbo model outputs into final bounding boxes with text class labels', 'compute sigmoid scores and class indices from predicted class logits tensor', 'clip predicted bounding boxes to image height and width boundaries', 'filter and sort top-k detections, apply confidence thresholding and non-maximum suppression']
```

Usage

```
{'run_object_detection': 'run OmDetTurboForObjectDetection to detect objects in images using class names and task prompts', 'create_language_embeddings': 'create cached class and task language embeddings using OmDetTurboPreTrainedModel.get_language_embedding', 'build_encoder_features': 'build hybrid encoder features with FPN and PAN using OmDetTurboHybridEncoder for multi-scale vision representations', 'test_decoder_predictions': 'test OmDetTurboDecoder to predict bounding boxes and class logits from vision and task features', 'review_deformable_attention': 'review OmDetTurboMultiscaleDeformableAttention for multi-scale deformable cross-attention in the decoder'}
```

## File: huggingface_transformers/src/transformers/models/omdet_turbo/processing_omdet_turbo.py

Prompts

```
['create an OmDetTurboConfig instance with default omlab/omdet-turbo-swin-tiny-hf style settings', 'build an OmDetTurboConfig for object detection with custom encoder and decoder dimensions', 'configure the OmDetTurboConfig with a custom swin transformer vision backbone', 'initialize the OmDetTurboConfig with a clip_text_model text encoder configuration', 'export the OmDetTurboConfig to a dictionary excluding internal timm_kwargs', 'convert an OmDet-Turbo checkpoint from the original repository to Hugging Face format', 'get the OmDet-Turbo configuration for a given model name and timm backbone option', 'create rename key mappings for vision backbone state dict keys', 'create rename key mappings for language backbone state dict keys', 'run an end-to-end consistency test on the converted model with a sample image', 'run OmDetTurboForObjectDetection to detect objects in images using class names and task prompts', 'create cached class and task language embeddings using OmDetTurboPreTrainedModel.get_language_embedding', 'build hybrid encoder features with FPN and PAN using OmDetTurboHybridEncoder for multi-scale vision representations', 'test OmDetTurboDecoder to predict bounding boxes and class logits from vision and task features', 'review OmDetTurboMultiscaleDeformableAttention for multi-scale deformable cross-attention in the decoder', 'process images and text labels for OmDet-Turbo object detection using the processor', 'post process raw OmDet-Turbo model outputs into final bounding boxes with text class labels', 'compute sigmoid scores and class indices from predicted class logits tensor', 'clip predicted bounding boxes to image height and width boundaries', 'filter and sort top-k detections, apply confidence thresholding and non-maximum suppression']
```

Usage

```
{'process_images_for_object_detection': 'process images and text labels for OmDet-Turbo object detection using the processor', 'post_process_detection_results': 'post process raw OmDet-Turbo model outputs into final bounding boxes with text class labels', 'compute_box_scores_and_classes': 'compute sigmoid scores and class indices from predicted class logits tensor', 'clip_boxes_to_image_bounds': 'clip predicted bounding boxes to image height and width boundaries', 'filter_detections_with_nms': 'filter and sort top-k detections, apply confidence thresholding and non-maximum suppression'}
```


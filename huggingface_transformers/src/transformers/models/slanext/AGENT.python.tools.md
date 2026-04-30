# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/slanext/image_processing_slanext.py

Prompts

```
['build a SLANeXtImageProcessor instance to preprocess images for table structure recognition', 'build the decoder vocabulary for SLANeXt table structure recognition with HTML token mappings', 'resize a torch tensor image using fixed-point bilinear interpolation without resampling warnings', 'preprocess a batch of torch tensor images with resize, rescale, normalize, and pad operations', 'post-process SLANeXt model outputs to decode predicted table structure into an HTML token sequence', 'run the SLANeXtForTableRecognition model on input images to predict table structure as HTML tokens', 'create a SLANeXtConfig with vision, hidden size, max text length and vocabulary parameters', 'run the SLANeXtSLAHead autoregressive decoder to predict table structure tokens from backbone features', 'build a SLANeXtBackbone vision encoder that extracts features from input pixel values', 'build a SLANeXtForTableRecognition model with SLANeXtConfig for table structure recognition', 'create an SLANeXtImageProcessor that resizes normalizes and pads images for table recognition', 'run SLANeXtForTableRecognition inference on image tensors to predict table structure tokens', 'post-process SLANeXtForTableRecognitionOutput into HTML table structure with post_process_table_recognition', 'configure SLANeXtConfig with vision_config hidden_size and max_text_length for table recognition']
```

Usage

```
{'build_slanext_image_processor': 'build a SLANeXtImageProcessor instance to preprocess images for table structure recognition', 'init_slanext_decoder_vocabulary': 'build the decoder vocabulary for SLANeXt table structure recognition with HTML token mappings', 'resize_image_fixed_point_bilinear': 'resize a torch tensor image using fixed-point bilinear interpolation without resampling warnings', 'preprocess_images_batch': 'preprocess a batch of torch tensor images with resize, rescale, normalize, and pad operations', 'post_process_table_recognition': 'post-process SLANeXt model outputs to decode predicted table structure into an HTML token sequence'}
```

## File: huggingface_transformers/src/transformers/models/slanext/modeling_slanext.py

Prompts

```
['build a SLANeXtImageProcessor instance to preprocess images for table structure recognition', 'build the decoder vocabulary for SLANeXt table structure recognition with HTML token mappings', 'resize a torch tensor image using fixed-point bilinear interpolation without resampling warnings', 'preprocess a batch of torch tensor images with resize, rescale, normalize, and pad operations', 'post-process SLANeXt model outputs to decode predicted table structure into an HTML token sequence', 'run the SLANeXtForTableRecognition model on input images to predict table structure as HTML tokens', 'create a SLANeXtConfig with vision, hidden size, max text length and vocabulary parameters', 'run the SLANeXtSLAHead autoregressive decoder to predict table structure tokens from backbone features', 'build a SLANeXtBackbone vision encoder that extracts features from input pixel values', 'build a SLANeXtForTableRecognition model with SLANeXtConfig for table structure recognition', 'create an SLANeXtImageProcessor that resizes normalizes and pads images for table recognition', 'run SLANeXtForTableRecognition inference on image tensors to predict table structure tokens', 'post-process SLANeXtForTableRecognitionOutput into HTML table structure with post_process_table_recognition', 'configure SLANeXtConfig with vision_config hidden_size and max_text_length for table recognition']
```

Usage

```
{'run_slanext_table_recognition': 'run the SLANeXtForTableRecognition model on input images to predict table structure as HTML tokens', 'build_slanext_image_processor': 'build a SLANeXtImageProcessor that resizes, pads, rescales and normalizes input images for the model', 'create_slanext_config': 'create a SLANeXtConfig with vision, hidden size, max text length and vocabulary parameters', 'run_slanext_sla_head': 'run the SLANeXtSLAHead autoregressive decoder to predict table structure tokens from backbone features', 'build_slanext_backbone': 'build a SLANeXtBackbone vision encoder that extracts features from input pixel values'}
```

## File: huggingface_transformers/src/transformers/models/slanext/modular_slanext.py

Prompts

```
['build a SLANeXtImageProcessor instance to preprocess images for table structure recognition', 'build the decoder vocabulary for SLANeXt table structure recognition with HTML token mappings', 'resize a torch tensor image using fixed-point bilinear interpolation without resampling warnings', 'preprocess a batch of torch tensor images with resize, rescale, normalize, and pad operations', 'post-process SLANeXt model outputs to decode predicted table structure into an HTML token sequence', 'run the SLANeXtForTableRecognition model on input images to predict table structure as HTML tokens', 'create a SLANeXtConfig with vision, hidden size, max text length and vocabulary parameters', 'run the SLANeXtSLAHead autoregressive decoder to predict table structure tokens from backbone features', 'build a SLANeXtBackbone vision encoder that extracts features from input pixel values', 'build a SLANeXtForTableRecognition model with SLANeXtConfig for table structure recognition', 'create an SLANeXtImageProcessor that resizes normalizes and pads images for table recognition', 'run SLANeXtForTableRecognition inference on image tensors to predict table structure tokens', 'post-process SLANeXtForTableRecognitionOutput into HTML table structure with post_process_table_recognition', 'configure SLANeXtConfig with vision_config hidden_size and max_text_length for table recognition']
```

Usage

```
{'build_table_recognition_model': 'build a SLANeXtForTableRecognition model with SLANeXtConfig for table structure recognition', 'create_image_processor': 'create an SLANeXtImageProcessor that resizes normalizes and pads images for table recognition', 'run_table_structure_prediction': 'run SLANeXtForTableRecognition inference on image tensors to predict table structure tokens', 'post_process_table_outputs': 'post-process SLANeXtForTableRecognitionOutput into HTML table structure with post_process_table_recognition', 'configure_slanext_model': 'configure SLANeXtConfig with vision_config hidden_size and max_text_length for table recognition'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/rt_detr_v2/convert_rt_detr_v2_weights_to_hf.py

Prompts

```
['convert RT-DETR V2 PyTorch checkpoint weights to HuggingFace transformers format for a given model name', 'run the convert_rt_detr_v2_weights_to_hf CLI script with model_name, output_dir, and push_to_hub arguments', 'get an RTDetrV2Config with backbone settings for rtdetr_v2_r18vd, r34vd, r50vd, or r101vd model variants', 'convert original checkpoint state dict keys to HuggingFace key names using regex-based mapping', 'split concatenated query/key/value projection matrices into separate q_proj, k_proj, v_proj weights in the state dict', 'create an RT-DETR V2 object detection model that outputs bounding boxes and class logits for images', 'run inference with RT-DETR V2 to detect objects and return bounding boxes with confidence scores', 'build the RT-DETR V2 encoder-decoder pipeline with hybrid CNN backbone and transformer decoder', 'test contrastive denoising training setup with noisy bounding boxes and label noise for object detection', 'review the RT-DETR V2 multiscale deformable attention mechanism with sampling offsets and bilinear interpolation', 'create an RTDetrV2Config with custom detection parameters like encoder layers, decoder layers, and focal loss settings', 'build an RTDetrV2Model with a backbone and encoder-decoder architecture for multi-scale object detection', 'run RTDetrV2ForObjectDetection inference on input images to produce bounding box and class predictions', 'configure RTDetrV2MultiscaleDeformableAttention with sampling offsets, attention weights, and discrete or default sampling methods', 'customize RTDetrV2Decoder with V2-specific decoder layers that override encoder attention with multiscale deformable attention']
```

Usage

```
{'convert_rt_detr_v2_weights_to_hf': 'convert RT-DETR V2 PyTorch checkpoint weights to HuggingFace transformers format for a given model name', 'run_convert_cli': 'run the convert_rt_detr_v2_weights_to_hf CLI script with model_name, output_dir, and push_to_hub arguments', 'get_rt_detr_v2_config': 'get an RTDetrV2Config with backbone settings for rtdetr_v2_r18vd, r34vd, r50vd, or r101vd model variants', 'convert_old_keys_to_new_keys': 'convert original checkpoint state dict keys to HuggingFace key names using regex-based mapping', 'read_in_q_k_v': 'split concatenated query/key/value projection matrices into separate q_proj, k_proj, v_proj weights in the state dict'}
```

## File: huggingface_transformers/src/transformers/models/rt_detr_v2/modeling_rt_detr_v2.py

Prompts

```
['convert RT-DETR V2 PyTorch checkpoint weights to HuggingFace transformers format for a given model name', 'run the convert_rt_detr_v2_weights_to_hf CLI script with model_name, output_dir, and push_to_hub arguments', 'get an RTDetrV2Config with backbone settings for rtdetr_v2_r18vd, r34vd, r50vd, or r101vd model variants', 'convert original checkpoint state dict keys to HuggingFace key names using regex-based mapping', 'split concatenated query/key/value projection matrices into separate q_proj, k_proj, v_proj weights in the state dict', 'create an RT-DETR V2 object detection model that outputs bounding boxes and class logits for images', 'run inference with RT-DETR V2 to detect objects and return bounding boxes with confidence scores', 'build the RT-DETR V2 encoder-decoder pipeline with hybrid CNN backbone and transformer decoder', 'test contrastive denoising training setup with noisy bounding boxes and label noise for object detection', 'review the RT-DETR V2 multiscale deformable attention mechanism with sampling offsets and bilinear interpolation', 'create an RTDetrV2Config with custom detection parameters like encoder layers, decoder layers, and focal loss settings', 'build an RTDetrV2Model with a backbone and encoder-decoder architecture for multi-scale object detection', 'run RTDetrV2ForObjectDetection inference on input images to produce bounding box and class predictions', 'configure RTDetrV2MultiscaleDeformableAttention with sampling offsets, attention weights, and discrete or default sampling methods', 'customize RTDetrV2Decoder with V2-specific decoder layers that override encoder attention with multiscale deformable attention']
```

Usage

```
{'create_object_detection_model': 'create an RT-DETR V2 object detection model that outputs bounding boxes and class logits for images', 'run_object_detection_inference': 'run inference with RT-DETR V2 to detect objects and return bounding boxes with confidence scores', 'build_encoder_decoder_pipeline': 'build the RT-DETR V2 encoder-decoder pipeline with hybrid CNN backbone and transformer decoder', 'test_denoising_training_setup': 'test contrastive denoising training setup with noisy bounding boxes and label noise for object detection', 'review_multiscale_attention': 'review the RT-DETR V2 multiscale deformable attention mechanism with sampling offsets and bilinear interpolation'}
```

## File: huggingface_transformers/src/transformers/models/rt_detr_v2/modular_rt_detr_v2.py

Prompts

```
['convert RT-DETR V2 PyTorch checkpoint weights to HuggingFace transformers format for a given model name', 'run the convert_rt_detr_v2_weights_to_hf CLI script with model_name, output_dir, and push_to_hub arguments', 'get an RTDetrV2Config with backbone settings for rtdetr_v2_r18vd, r34vd, r50vd, or r101vd model variants', 'convert original checkpoint state dict keys to HuggingFace key names using regex-based mapping', 'split concatenated query/key/value projection matrices into separate q_proj, k_proj, v_proj weights in the state dict', 'create an RT-DETR V2 object detection model that outputs bounding boxes and class logits for images', 'run inference with RT-DETR V2 to detect objects and return bounding boxes with confidence scores', 'build the RT-DETR V2 encoder-decoder pipeline with hybrid CNN backbone and transformer decoder', 'test contrastive denoising training setup with noisy bounding boxes and label noise for object detection', 'review the RT-DETR V2 multiscale deformable attention mechanism with sampling offsets and bilinear interpolation', 'create an RTDetrV2Config with custom detection parameters like encoder layers, decoder layers, and focal loss settings', 'build an RTDetrV2Model with a backbone and encoder-decoder architecture for multi-scale object detection', 'run RTDetrV2ForObjectDetection inference on input images to produce bounding box and class predictions', 'configure RTDetrV2MultiscaleDeformableAttention with sampling offsets, attention weights, and discrete or default sampling methods', 'customize RTDetrV2Decoder with V2-specific decoder layers that override encoder attention with multiscale deformable attention']
```

Usage

```
{'create_rtdetr_v2_config': 'create an RTDetrV2Config with custom detection parameters like encoder layers, decoder layers, and focal loss settings', 'build_rtdetr_v2_model': 'build an RTDetrV2Model with a backbone and encoder-decoder architecture for multi-scale object detection', 'run_rtdetr_v2_detection': 'run RTDetrV2ForObjectDetection inference on input images to produce bounding box and class predictions', 'configure_multiscale_deformable_attention': 'configure RTDetrV2MultiscaleDeformableAttention with sampling offsets, attention weights, and discrete or default sampling methods', 'customize_rtdetr_v2_decoder': 'customize RTDetrV2Decoder with V2-specific decoder layers that override encoder attention with multiscale deformable attention'}
```


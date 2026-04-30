# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/deimv2/configuration_deimv2.py

Prompts

```
['create a Deimv2Config instance with custom num_queries and decoder_layers for object detection', 'initialize a Deimv2Config from a pretrained checkpoint like Intellindust/DEIMv2_HGNetv2_N_COCO', 'validate the Deimv2Config architecture to ensure decoder_n_points matches num_feature_levels', 'customize the Deimv2Config encoder by setting encoder_type to lite and encoder_fuse_op to sum', 'configure the Deimv2Config loss weights for weight_loss_vfl, weight_loss_bbox, and weight_loss_giou', 'run the DEIMv2 checkpoint conversion script to convert an original PyTorch checkpoint to HuggingFace format', 'build a Deimv2Config object from a model name by downloading and parsing the original config from the HuggingFace Hub', 'refactor the original state dict keys to match the HuggingFace transformers model key naming conventions', 'create separate query, key, and value projection weights from the fused in_proj_weight matrices in the state dict', 'split fused SwiGLU w12 weights into separate gate_proj and up_proj parameters for the decoder layers', 'build a DEIMv2ForObjectDetection model to detect objects and return bounding boxes with class logits from an image', 'run the Deimv2Model to get encoder-decoder hidden states and intermediate reference points for object queries', 'create a Deimv2HybridEncoder with AIFI layers and FPN-PAN topology to process multi-scale feature maps', 'test the Deimv2Decoder forward pass with reference points and encoder memory to get intermediate logits and predicted corners', 'refactor the multi_scale_deformable_attention_v2 function to support a new sampling method for feature aggregation', 'build a DEIMv2 object detection model using Deimv2ForObjectDetection for COCO dataset inference', 'create a Deimv2Config with custom encoder type lite and sum fusion for smaller variants', 'run a forward pass with Deimv2ForObjectDetection to get logits and bounding boxes from an image', 'review the Deimv2HybridEncoder forward method to understand FPN top-down and PAN bottom-up feature fusion', 'refactor the Deimv2DecoderLayer to toggle gateway cross-attention gating or RMSNorm fallback behavior']
```

Usage

```
{'create_deimv2_config': 'create a Deimv2Config instance with custom num_queries and decoder_layers for object detection', 'initialize_deimv2_config_from_pretrained': 'initialize a Deimv2Config from a pretrained checkpoint like Intellindust/DEIMv2_HGNetv2_N_COCO', 'validate_deimv2_architecture': 'validate the Deimv2Config architecture to ensure decoder_n_points matches num_feature_levels', 'customize_deimv2_encoder': 'customize the Deimv2Config encoder by setting encoder_type to lite and encoder_fuse_op to sum', 'configure_deimv2_loss_weights': 'configure the Deimv2Config loss weights for weight_loss_vfl, weight_loss_bbox, and weight_loss_giou'}
```

## File: huggingface_transformers/src/transformers/models/deimv2/convert_deimv2_original_pytorch_checkpoint_to_hf.py

Prompts

```
['create a Deimv2Config instance with custom num_queries and decoder_layers for object detection', 'initialize a Deimv2Config from a pretrained checkpoint like Intellindust/DEIMv2_HGNetv2_N_COCO', 'validate the Deimv2Config architecture to ensure decoder_n_points matches num_feature_levels', 'customize the Deimv2Config encoder by setting encoder_type to lite and encoder_fuse_op to sum', 'configure the Deimv2Config loss weights for weight_loss_vfl, weight_loss_bbox, and weight_loss_giou', 'run the DEIMv2 checkpoint conversion script to convert an original PyTorch checkpoint to HuggingFace format', 'build a Deimv2Config object from a model name by downloading and parsing the original config from the HuggingFace Hub', 'refactor the original state dict keys to match the HuggingFace transformers model key naming conventions', 'create separate query, key, and value projection weights from the fused in_proj_weight matrices in the state dict', 'split fused SwiGLU w12 weights into separate gate_proj and up_proj parameters for the decoder layers', 'build a DEIMv2ForObjectDetection model to detect objects and return bounding boxes with class logits from an image', 'run the Deimv2Model to get encoder-decoder hidden states and intermediate reference points for object queries', 'create a Deimv2HybridEncoder with AIFI layers and FPN-PAN topology to process multi-scale feature maps', 'test the Deimv2Decoder forward pass with reference points and encoder memory to get intermediate logits and predicted corners', 'refactor the multi_scale_deformable_attention_v2 function to support a new sampling method for feature aggregation', 'build a DEIMv2 object detection model using Deimv2ForObjectDetection for COCO dataset inference', 'create a Deimv2Config with custom encoder type lite and sum fusion for smaller variants', 'run a forward pass with Deimv2ForObjectDetection to get logits and bounding boxes from an image', 'review the Deimv2HybridEncoder forward method to understand FPN top-down and PAN bottom-up feature fusion', 'refactor the Deimv2DecoderLayer to toggle gateway cross-attention gating or RMSNorm fallback behavior']
```

Usage

```
{'convert_deimv2_checkpoint': 'run the DEIMv2 checkpoint conversion script to convert an original PyTorch checkpoint to HuggingFace format', 'get_deimv2_config': 'build a Deimv2Config object from a model name by downloading and parsing the original config from the HuggingFace Hub', 'convert_old_keys_to_new_keys': 'refactor the original state dict keys to match the HuggingFace transformers model key naming conventions', 'read_in_q_k_v': 'create separate query, key, and value projection weights from the fused in_proj_weight matrices in the state dict', 'split_swiglu_fused_weights': 'split fused SwiGLU w12 weights into separate gate_proj and up_proj parameters for the decoder layers'}
```

## File: huggingface_transformers/src/transformers/models/deimv2/modeling_deimv2.py

Prompts

```
['create a Deimv2Config instance with custom num_queries and decoder_layers for object detection', 'initialize a Deimv2Config from a pretrained checkpoint like Intellindust/DEIMv2_HGNetv2_N_COCO', 'validate the Deimv2Config architecture to ensure decoder_n_points matches num_feature_levels', 'customize the Deimv2Config encoder by setting encoder_type to lite and encoder_fuse_op to sum', 'configure the Deimv2Config loss weights for weight_loss_vfl, weight_loss_bbox, and weight_loss_giou', 'run the DEIMv2 checkpoint conversion script to convert an original PyTorch checkpoint to HuggingFace format', 'build a Deimv2Config object from a model name by downloading and parsing the original config from the HuggingFace Hub', 'refactor the original state dict keys to match the HuggingFace transformers model key naming conventions', 'create separate query, key, and value projection weights from the fused in_proj_weight matrices in the state dict', 'split fused SwiGLU w12 weights into separate gate_proj and up_proj parameters for the decoder layers', 'build a DEIMv2ForObjectDetection model to detect objects and return bounding boxes with class logits from an image', 'run the Deimv2Model to get encoder-decoder hidden states and intermediate reference points for object queries', 'create a Deimv2HybridEncoder with AIFI layers and FPN-PAN topology to process multi-scale feature maps', 'test the Deimv2Decoder forward pass with reference points and encoder memory to get intermediate logits and predicted corners', 'refactor the multi_scale_deformable_attention_v2 function to support a new sampling method for feature aggregation', 'build a DEIMv2 object detection model using Deimv2ForObjectDetection for COCO dataset inference', 'create a Deimv2Config with custom encoder type lite and sum fusion for smaller variants', 'run a forward pass with Deimv2ForObjectDetection to get logits and bounding boxes from an image', 'review the Deimv2HybridEncoder forward method to understand FPN top-down and PAN bottom-up feature fusion', 'refactor the Deimv2DecoderLayer to toggle gateway cross-attention gating or RMSNorm fallback behavior']
```

Usage

```
{'build_object_detection_model': 'build a DEIMv2ForObjectDetection model to detect objects and return bounding boxes with class logits from an image', 'run_deimv2_model_inference': 'run the Deimv2Model to get encoder-decoder hidden states and intermediate reference points for object queries', 'create_hybrid_encoder': 'create a Deimv2HybridEncoder with AIFI layers and FPN-PAN topology to process multi-scale feature maps', 'test_decoder_fdr': 'test the Deimv2Decoder forward pass with reference points and encoder memory to get intermediate logits and predicted corners', 'refactor_multiscale_deformable_attention': 'refactor the multi_scale_deformable_attention_v2 function to support a new sampling method for feature aggregation'}
```

## File: huggingface_transformers/src/transformers/models/deimv2/modular_deimv2.py

Prompts

```
['create a Deimv2Config instance with custom num_queries and decoder_layers for object detection', 'initialize a Deimv2Config from a pretrained checkpoint like Intellindust/DEIMv2_HGNetv2_N_COCO', 'validate the Deimv2Config architecture to ensure decoder_n_points matches num_feature_levels', 'customize the Deimv2Config encoder by setting encoder_type to lite and encoder_fuse_op to sum', 'configure the Deimv2Config loss weights for weight_loss_vfl, weight_loss_bbox, and weight_loss_giou', 'run the DEIMv2 checkpoint conversion script to convert an original PyTorch checkpoint to HuggingFace format', 'build a Deimv2Config object from a model name by downloading and parsing the original config from the HuggingFace Hub', 'refactor the original state dict keys to match the HuggingFace transformers model key naming conventions', 'create separate query, key, and value projection weights from the fused in_proj_weight matrices in the state dict', 'split fused SwiGLU w12 weights into separate gate_proj and up_proj parameters for the decoder layers', 'build a DEIMv2ForObjectDetection model to detect objects and return bounding boxes with class logits from an image', 'run the Deimv2Model to get encoder-decoder hidden states and intermediate reference points for object queries', 'create a Deimv2HybridEncoder with AIFI layers and FPN-PAN topology to process multi-scale feature maps', 'test the Deimv2Decoder forward pass with reference points and encoder memory to get intermediate logits and predicted corners', 'refactor the multi_scale_deformable_attention_v2 function to support a new sampling method for feature aggregation', 'build a DEIMv2 object detection model using Deimv2ForObjectDetection for COCO dataset inference', 'create a Deimv2Config with custom encoder type lite and sum fusion for smaller variants', 'run a forward pass with Deimv2ForObjectDetection to get logits and bounding boxes from an image', 'review the Deimv2HybridEncoder forward method to understand FPN top-down and PAN bottom-up feature fusion', 'refactor the Deimv2DecoderLayer to toggle gateway cross-attention gating or RMSNorm fallback behavior']
```

Usage

```
{'build_DEIMv2_object_detection_model': 'build a DEIMv2 object detection model using Deimv2ForObjectDetection for COCO dataset inference', 'create_DEIMv2_config': 'create a Deimv2Config with custom encoder type lite and sum fusion for smaller variants', 'run_DEIMv2_forward_pass': 'run a forward pass with Deimv2ForObjectDetection to get logits and bounding boxes from an image', 'review_Deimv2HybridEncoder_forward': 'review the Deimv2HybridEncoder forward method to understand FPN top-down and PAN bottom-up feature fusion', 'refactor_Deimv2DecoderLayer_gateway': 'refactor the Deimv2DecoderLayer to toggle gateway cross-attention gating or RMSNorm fallback behavior'}
```


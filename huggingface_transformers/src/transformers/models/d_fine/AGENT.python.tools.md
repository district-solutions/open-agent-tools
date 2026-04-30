# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/d_fine/configuration_d_fine.py

Prompts

```
['create a DFineConfig instance for object detection model with custom encoder and decoder settings', 'build a DFineConfig from a pretrained checkpoint like ustc-community/dfine-xlarge-coco', 'validate the DFineConfig architecture ensuring d_model is divisible by decoder_attention_heads', 'review the DFineConfig loss parameters including focal loss, bbox loss, and giou loss weights', 'summarize the DFineConfig decoder options including denoising, box refine, and query settings', 'convert a D-FINE PyTorch checkpoint to HuggingFace format for a given model name', 'get a DFineConfig for a specific model name like dfine_s_coco or dfine_x_obj365', 'load the original PyTorch state dict from a HuggingFace Hub checkpoint file', 'rename PyTorch checkpoint keys to match HuggingFace DFine model structure', 'split concatenated query-key-value projection matrices into separate projection layers', 'run DFineForObjectDetection forward pass to detect objects and return bounding boxes with class logits', 'build DFineModel encoder-decoder to extract hidden states from image features without detection heads', 'test DFineMultiscaleDeformableAttention forward pass with sampling offsets and attention weights', 'review DFineDecoder iterative refinement loop with location quality estimation and distribution refinement', 'summarize get_contrastive_denoising_training_group denoising training helper that adds noise to ground truth queries', 'build a DFineForObjectDetection model for object detection using pretrained weights from ustk-community/dfine-xlarge-coco', 'configure a DFineConfig with custom encoder, decoder, and loss hyperparameters for object detection', 'run a forward pass on a DFineForObjectDetection model with image inputs to get bounding box predictions', 'refine bounding box predictions using DFineDecoder with fine-grained distribution refinement and location quality estimation', 'initialize DFine model weights with proper bias priors, sampling offsets, and attention weight initialization']
```

Usage

```
{'create_DFineConfig': 'create a DFineConfig instance for object detection model with custom encoder and decoder settings', 'build_DFineConfig_from_pretrained': 'build a DFineConfig from a pretrained checkpoint like ustc-community/dfine-xlarge-coco', 'validate_DFineConfig_architecture': 'validate the DFineConfig architecture ensuring d_model is divisible by decoder_attention_heads', 'review_DFineConfig_loss_params': 'review the DFineConfig loss parameters including focal loss, bbox loss, and giou loss weights', 'summarize_DFineConfig_decoder_options': 'summarize the DFineConfig decoder options including denoising, box refine, and query settings'}
```

## File: huggingface_transformers/src/transformers/models/d_fine/convert_d_fine_original_pytorch_checkpoint_to_hf.py

Prompts

```
['create a DFineConfig instance for object detection model with custom encoder and decoder settings', 'build a DFineConfig from a pretrained checkpoint like ustc-community/dfine-xlarge-coco', 'validate the DFineConfig architecture ensuring d_model is divisible by decoder_attention_heads', 'review the DFineConfig loss parameters including focal loss, bbox loss, and giou loss weights', 'summarize the DFineConfig decoder options including denoising, box refine, and query settings', 'convert a D-FINE PyTorch checkpoint to HuggingFace format for a given model name', 'get a DFineConfig for a specific model name like dfine_s_coco or dfine_x_obj365', 'load the original PyTorch state dict from a HuggingFace Hub checkpoint file', 'rename PyTorch checkpoint keys to match HuggingFace DFine model structure', 'split concatenated query-key-value projection matrices into separate projection layers', 'run DFineForObjectDetection forward pass to detect objects and return bounding boxes with class logits', 'build DFineModel encoder-decoder to extract hidden states from image features without detection heads', 'test DFineMultiscaleDeformableAttention forward pass with sampling offsets and attention weights', 'review DFineDecoder iterative refinement loop with location quality estimation and distribution refinement', 'summarize get_contrastive_denoising_training_group denoising training helper that adds noise to ground truth queries', 'build a DFineForObjectDetection model for object detection using pretrained weights from ustk-community/dfine-xlarge-coco', 'configure a DFineConfig with custom encoder, decoder, and loss hyperparameters for object detection', 'run a forward pass on a DFineForObjectDetection model with image inputs to get bounding box predictions', 'refine bounding box predictions using DFineDecoder with fine-grained distribution refinement and location quality estimation', 'initialize DFine model weights with proper bias priors, sampling offsets, and attention weight initialization']
```

Usage

```
{'convert_d_fine_checkpoint': 'convert a D-FINE PyTorch checkpoint to HuggingFace format for a given model name', 'get_d_fine_config': 'get a DFineConfig for a specific model name like dfine_s_coco or dfine_x_obj365', 'load_original_state_dict': 'load the original PyTorch state dict from a HuggingFace Hub checkpoint file', 'convert_old_keys_to_new_keys': 'rename PyTorch checkpoint keys to match HuggingFace DFine model structure', 'read_in_q_k_v': 'split concatenated query-key-value projection matrices into separate projection layers'}
```

## File: huggingface_transformers/src/transformers/models/d_fine/modeling_d_fine.py

Prompts

```
['create a DFineConfig instance for object detection model with custom encoder and decoder settings', 'build a DFineConfig from a pretrained checkpoint like ustc-community/dfine-xlarge-coco', 'validate the DFineConfig architecture ensuring d_model is divisible by decoder_attention_heads', 'review the DFineConfig loss parameters including focal loss, bbox loss, and giou loss weights', 'summarize the DFineConfig decoder options including denoising, box refine, and query settings', 'convert a D-FINE PyTorch checkpoint to HuggingFace format for a given model name', 'get a DFineConfig for a specific model name like dfine_s_coco or dfine_x_obj365', 'load the original PyTorch state dict from a HuggingFace Hub checkpoint file', 'rename PyTorch checkpoint keys to match HuggingFace DFine model structure', 'split concatenated query-key-value projection matrices into separate projection layers', 'run DFineForObjectDetection forward pass to detect objects and return bounding boxes with class logits', 'build DFineModel encoder-decoder to extract hidden states from image features without detection heads', 'test DFineMultiscaleDeformableAttention forward pass with sampling offsets and attention weights', 'review DFineDecoder iterative refinement loop with location quality estimation and distribution refinement', 'summarize get_contrastive_denoising_training_group denoising training helper that adds noise to ground truth queries', 'build a DFineForObjectDetection model for object detection using pretrained weights from ustk-community/dfine-xlarge-coco', 'configure a DFineConfig with custom encoder, decoder, and loss hyperparameters for object detection', 'run a forward pass on a DFineForObjectDetection model with image inputs to get bounding box predictions', 'refine bounding box predictions using DFineDecoder with fine-grained distribution refinement and location quality estimation', 'initialize DFine model weights with proper bias priors, sampling offsets, and attention weight initialization']
```

Usage

```
{'run_DFineForObjectDetection': 'run DFineForObjectDetection forward pass to detect objects and return bounding boxes with class logits', 'build_DFineModel': 'build DFineModel encoder-decoder to extract hidden states from image features without detection heads', 'test_DFineMultiscaleDeformableAttention': 'test DFineMultiscaleDeformableAttention forward pass with sampling offsets and attention weights', 'review_DFineDecoder': 'review DFineDecoder iterative refinement loop with location quality estimation and distribution refinement', 'summarize_get_contrastive_denoising_training_group': 'summarize get_contrastive_denoising_training_group denoising training helper that adds noise to ground truth queries'}
```

## File: huggingface_transformers/src/transformers/models/d_fine/modular_d_fine.py

Prompts

```
['create a DFineConfig instance for object detection model with custom encoder and decoder settings', 'build a DFineConfig from a pretrained checkpoint like ustc-community/dfine-xlarge-coco', 'validate the DFineConfig architecture ensuring d_model is divisible by decoder_attention_heads', 'review the DFineConfig loss parameters including focal loss, bbox loss, and giou loss weights', 'summarize the DFineConfig decoder options including denoising, box refine, and query settings', 'convert a D-FINE PyTorch checkpoint to HuggingFace format for a given model name', 'get a DFineConfig for a specific model name like dfine_s_coco or dfine_x_obj365', 'load the original PyTorch state dict from a HuggingFace Hub checkpoint file', 'rename PyTorch checkpoint keys to match HuggingFace DFine model structure', 'split concatenated query-key-value projection matrices into separate projection layers', 'run DFineForObjectDetection forward pass to detect objects and return bounding boxes with class logits', 'build DFineModel encoder-decoder to extract hidden states from image features without detection heads', 'test DFineMultiscaleDeformableAttention forward pass with sampling offsets and attention weights', 'review DFineDecoder iterative refinement loop with location quality estimation and distribution refinement', 'summarize get_contrastive_denoising_training_group denoising training helper that adds noise to ground truth queries', 'build a DFineForObjectDetection model for object detection using pretrained weights from ustk-community/dfine-xlarge-coco', 'configure a DFineConfig with custom encoder, decoder, and loss hyperparameters for object detection', 'run a forward pass on a DFineForObjectDetection model with image inputs to get bounding box predictions', 'refine bounding box predictions using DFineDecoder with fine-grained distribution refinement and location quality estimation', 'initialize DFine model weights with proper bias priors, sampling offsets, and attention weight initialization']
```

Usage

```
{'build_dfine_object_detection_model': 'build a DFineForObjectDetection model for object detection using pretrained weights from ustk-community/dfine-xlarge-coco', 'configure_dfine_model': 'configure a DFineConfig with custom encoder, decoder, and loss hyperparameters for object detection', 'run_dfine_forward_pass': 'run a forward pass on a DFineForObjectDetection model with image inputs to get bounding box predictions', 'refine_bounding_box_predictions': 'refine bounding box predictions using DFineDecoder with fine-grained distribution refinement and location quality estimation', 'initialize_dfine_model_weights': 'initialize DFine model weights with proper bias priors, sampling offsets, and attention weight initialization'}
```


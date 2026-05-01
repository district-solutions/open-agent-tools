# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/maskformer/test_image_processing_maskformer.py

Prompts

```
['run the MaskFormer image processing unit tests to verify resize, normalize, and segmentation map handling', 'test the MaskFormer image processor integration with instance segmentation annotations and class label mapping', 'test the MaskFormer image processor integration with semantic segmentation annotations from the HuggingFace hub', 'test the MaskFormer image processor integration with panoptic segmentation using RGB-to-ID conversion and segment info', 'test the binary_mask_to_rle function that converts a binary mask numpy array into run-length encoded format', 'test the MaskFormerModel forward pass with pixel values and pixel mask inputs', 'test the MaskFormerForInstanceSegmentation model inference and loss computation', 'test MaskFormerModel output hidden states across encoder, pixel decoder, and transformer decoder', 'test gradient retention for hidden states and attention outputs during backward pass', 'test auxiliary loss and auxiliary logits output with use_auxiliary_loss enabled', 'run the MaskFormerSwinModelTester to prepare config and inputs for the MaskFormer Swin model', 'test the MaskFormerSwinModel by running create_and_check_model to verify output tensor shapes', 'test the MaskFormerSwinBackbone by running create_and_check_backbone to verify feature maps and channels', 'test that tuple and dict outputs are equivalent for MaskFormerSwinModel with return_dict flag']
```

Usage

```
{'test_maskformer_image_processing': 'run the MaskFormer image processing unit tests to verify resize, normalize, and segmentation map handling', 'test_instance_segmentation_integration': 'test the MaskFormer image processor integration with instance segmentation annotations and class label mapping', 'test_semantic_segmentation_integration': 'test the MaskFormer image processor integration with semantic segmentation annotations from the HuggingFace hub', 'test_panoptic_segmentation_integration': 'test the MaskFormer image processor integration with panoptic segmentation using RGB-to-ID conversion and segment info', 'test_binary_mask_to_rle': 'test the binary_mask_to_rle function that converts a binary mask numpy array into run-length encoded format'}
```

## File: huggingface_transformers/tests/models/maskformer/test_modeling_maskformer.py

Prompts

```
['run the MaskFormer image processing unit tests to verify resize, normalize, and segmentation map handling', 'test the MaskFormer image processor integration with instance segmentation annotations and class label mapping', 'test the MaskFormer image processor integration with semantic segmentation annotations from the HuggingFace hub', 'test the MaskFormer image processor integration with panoptic segmentation using RGB-to-ID conversion and segment info', 'test the binary_mask_to_rle function that converts a binary mask numpy array into run-length encoded format', 'test the MaskFormerModel forward pass with pixel values and pixel mask inputs', 'test the MaskFormerForInstanceSegmentation model inference and loss computation', 'test MaskFormerModel output hidden states across encoder, pixel decoder, and transformer decoder', 'test gradient retention for hidden states and attention outputs during backward pass', 'test auxiliary loss and auxiliary logits output with use_auxiliary_loss enabled', 'run the MaskFormerSwinModelTester to prepare config and inputs for the MaskFormer Swin model', 'test the MaskFormerSwinModel by running create_and_check_model to verify output tensor shapes', 'test the MaskFormerSwinBackbone by running create_and_check_backbone to verify feature maps and channels', 'test that tuple and dict outputs are equivalent for MaskFormerSwinModel with return_dict flag']
```

Usage

```
{'test_maskformer_model': 'test the MaskFormerModel forward pass with pixel values and pixel mask inputs', 'test_maskformer_instance_segmentation_head_model': 'test the MaskFormerForInstanceSegmentation model inference and loss computation', 'test_hidden_states_output': 'test MaskFormerModel output hidden states across encoder, pixel decoder, and transformer decoder', 'test_retain_grad_hidden_states_attentions': 'test gradient retention for hidden states and attention outputs during backward pass', 'test_forward_auxiliary_loss': 'test auxiliary loss and auxiliary logits output with use_auxiliary_loss enabled'}
```

## File: huggingface_transformers/tests/models/maskformer/test_modeling_maskformer_swin.py

Prompts

```
['run the MaskFormer image processing unit tests to verify resize, normalize, and segmentation map handling', 'test the MaskFormer image processor integration with instance segmentation annotations and class label mapping', 'test the MaskFormer image processor integration with semantic segmentation annotations from the HuggingFace hub', 'test the MaskFormer image processor integration with panoptic segmentation using RGB-to-ID conversion and segment info', 'test the binary_mask_to_rle function that converts a binary mask numpy array into run-length encoded format', 'test the MaskFormerModel forward pass with pixel values and pixel mask inputs', 'test the MaskFormerForInstanceSegmentation model inference and loss computation', 'test MaskFormerModel output hidden states across encoder, pixel decoder, and transformer decoder', 'test gradient retention for hidden states and attention outputs during backward pass', 'test auxiliary loss and auxiliary logits output with use_auxiliary_loss enabled', 'run the MaskFormerSwinModelTester to prepare config and inputs for the MaskFormer Swin model', 'test the MaskFormerSwinModel by running create_and_check_model to verify output tensor shapes', 'test the MaskFormerSwinBackbone by running create_and_check_backbone to verify feature maps and channels', 'test that tuple and dict outputs are equivalent for MaskFormerSwinModel with return_dict flag']
```

Usage

```
{'run_MaskFormerSwinModelTester': 'run the MaskFormerSwinModelTester to prepare config and inputs for the MaskFormer Swin model', 'test_MaskFormerSwinModel': 'test the MaskFormerSwinModel by running create_and_check_model to verify output tensor shapes', 'test_MaskFormerSwinBackbone': 'test the MaskFormerSwinBackbone by running create_and_check_backbone to verify feature maps and channels', 'test_hidden_states_output': 'test the hidden states output for MaskFormerSwinModel and MaskFormerSwinBackbone with output_hidden_states enabled', 'test_model_outputs_equivalence': 'test that tuple and dict outputs are equivalent for MaskFormerSwinModel with return_dict flag'}
```


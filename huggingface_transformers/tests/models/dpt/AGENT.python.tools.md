# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/dpt/test_image_processing_dpt.py

Prompts

```
['test the DPTImageProcessingTest class for image processing unit tests', 'create a DPTImageProcessingTester instance with configurable image processor parameters', 'test image padding with size_divisor for torch and numpy backends', 'test calling image processor with segmentation maps for batched and unbatched inputs', 'test reducing label values by subtracting 1 when do_reduce_labels is enabled', 'test the DPTModel forward pass by creating a model and verifying last_hidden_state output shape', 'test the DPTForDepthEstimation model by running a forward pass and verifying predicted_depth output shape', 'test the DPTForSemanticSegmentation model by running a forward pass with labels and verifying logits output shape', 'run tests that validate both timm and HuggingFace backbone initialization with custom out_indices for DPT models', 'run inference with a pretrained Intel/dpt-large model on a sample image and verify predicted depth values', 'test DPTModelTester to prepare config and inputs for DPT depth estimation model testing', 'test DPTModelTest test_for_depth_estimation to run a forward pass and validate depth estimation output', 'test DPTModelIntegrationTest inference with facebook/dpt-dinov2-small-kitti pretrained model and verify predicted depth values', 'test DPTModelIntegrationTest inference with Intel/dpt-swinv2-tiny-256 pretrained model and verify predicted depth output shape', 'test the DPTForDepthEstimation model for depth estimation inference on input images', 'test the DPTForSemanticSegmentation model for semantic segmentation inference on input images', 'test the DPTModel forward pass producing last_hidden_state output tensor', 'test the DPT models training loop with loss computation and gradient backpropagation', 'test loading the Intel/dpt-hybrid-midas pretrained DPT model from HuggingFace Hub']
```

Usage

```
{'test_DPTImageProcessingTest': 'test the DPTImageProcessingTest class for image processing unit tests', 'create_DPTImageProcessingTester': 'create a DPTImageProcessingTester instance with configurable image processor parameters', 'test_padding': 'test image padding with size_divisor for torch and numpy backends', 'test_call_segmentation_maps': 'test calling image processor with segmentation maps for batched and unbatched inputs', 'test_reduce_labels': 'test reducing label values by subtracting 1 when do_reduce_labels is enabled'}
```

## File: huggingface_transformers/tests/models/dpt/test_modeling_dpt.py

Prompts

```
['test the DPTImageProcessingTest class for image processing unit tests', 'create a DPTImageProcessingTester instance with configurable image processor parameters', 'test image padding with size_divisor for torch and numpy backends', 'test calling image processor with segmentation maps for batched and unbatched inputs', 'test reducing label values by subtracting 1 when do_reduce_labels is enabled', 'test the DPTModel forward pass by creating a model and verifying last_hidden_state output shape', 'test the DPTForDepthEstimation model by running a forward pass and verifying predicted_depth output shape', 'test the DPTForSemanticSegmentation model by running a forward pass with labels and verifying logits output shape', 'run tests that validate both timm and HuggingFace backbone initialization with custom out_indices for DPT models', 'run inference with a pretrained Intel/dpt-large model on a sample image and verify predicted depth values', 'test DPTModelTester to prepare config and inputs for DPT depth estimation model testing', 'test DPTModelTest test_for_depth_estimation to run a forward pass and validate depth estimation output', 'test DPTModelIntegrationTest inference with facebook/dpt-dinov2-small-kitti pretrained model and verify predicted depth values', 'test DPTModelIntegrationTest inference with Intel/dpt-swinv2-tiny-256 pretrained model and verify predicted depth output shape', 'test the DPTForDepthEstimation model for depth estimation inference on input images', 'test the DPTForSemanticSegmentation model for semantic segmentation inference on input images', 'test the DPTModel forward pass producing last_hidden_state output tensor', 'test the DPT models training loop with loss computation and gradient backpropagation', 'test loading the Intel/dpt-hybrid-midas pretrained DPT model from HuggingFace Hub']
```

Usage

```
{'test_DPTModelTester_create_and_check_model': 'test the DPTModel forward pass by creating a model and verifying last_hidden_state output shape', 'test_DPTModelTester_create_and_check_for_depth_estimation': 'test the DPTForDepthEstimation model by running a forward pass and verifying predicted_depth output shape', 'test_DPTModelTester_create_and_check_for_semantic_segmentation': 'test the DPTForSemanticSegmentation model by running a forward pass with labels and verifying logits output shape', 'run_DPTModelTest_test_backbone_selection': 'run tests that validate both timm and HuggingFace backbone initialization with custom out_indices for DPT models', 'run_DPTModelIntegrationTest_test_inference_depth_estimation': 'run inference with a pretrained Intel/dpt-large model on a sample image and verify predicted depth values'}
```

## File: huggingface_transformers/tests/models/dpt/test_modeling_dpt_auto_backbone.py

Prompts

```
['test the DPTImageProcessingTest class for image processing unit tests', 'create a DPTImageProcessingTester instance with configurable image processor parameters', 'test image padding with size_divisor for torch and numpy backends', 'test calling image processor with segmentation maps for batched and unbatched inputs', 'test reducing label values by subtracting 1 when do_reduce_labels is enabled', 'test the DPTModel forward pass by creating a model and verifying last_hidden_state output shape', 'test the DPTForDepthEstimation model by running a forward pass and verifying predicted_depth output shape', 'test the DPTForSemanticSegmentation model by running a forward pass with labels and verifying logits output shape', 'run tests that validate both timm and HuggingFace backbone initialization with custom out_indices for DPT models', 'run inference with a pretrained Intel/dpt-large model on a sample image and verify predicted depth values', 'test DPTModelTester to prepare config and inputs for DPT depth estimation model testing', 'test DPTModelTest test_for_depth_estimation to run a forward pass and validate depth estimation output', 'test DPTModelIntegrationTest inference with facebook/dpt-dinov2-small-kitti pretrained model and verify predicted depth values', 'test DPTModelIntegrationTest inference with Intel/dpt-swinv2-tiny-256 pretrained model and verify predicted depth output shape', 'test the DPTForDepthEstimation model for depth estimation inference on input images', 'test the DPTForSemanticSegmentation model for semantic segmentation inference on input images', 'test the DPTModel forward pass producing last_hidden_state output tensor', 'test the DPT models training loop with loss computation and gradient backpropagation', 'test loading the Intel/dpt-hybrid-midas pretrained DPT model from HuggingFace Hub']
```

Usage

```
{'test_DPTModelTester_prepare_config_and_inputs': 'test DPTModelTester to prepare config and inputs for DPT depth estimation model testing', 'test_DPTModelTester_create_and_check_for_depth_estimation': 'test DPTModelTester create_and_check_for_depth_estimation to verify predicted depth output shape matches expected dimensions', 'test_DPTModelTest_test_for_depth_estimation': 'test DPTModelTest test_for_depth_estimation to run a forward pass and validate depth estimation output', 'test_DPTModelIntegrationTest_test_inference_depth_estimation_dinov2': 'test DPTModelIntegrationTest inference with facebook/dpt-dinov2-small-kitti pretrained model and verify predicted depth values', 'test_DPTModelIntegrationTest_test_inference_depth_estimation_swinv2': 'test DPTModelIntegrationTest inference with Intel/dpt-swinv2-tiny-256 pretrained model and verify predicted depth output shape'}
```

## File: huggingface_transformers/tests/models/dpt/test_modeling_dpt_hybrid.py

Prompts

```
['test the DPTImageProcessingTest class for image processing unit tests', 'create a DPTImageProcessingTester instance with configurable image processor parameters', 'test image padding with size_divisor for torch and numpy backends', 'test calling image processor with segmentation maps for batched and unbatched inputs', 'test reducing label values by subtracting 1 when do_reduce_labels is enabled', 'test the DPTModel forward pass by creating a model and verifying last_hidden_state output shape', 'test the DPTForDepthEstimation model by running a forward pass and verifying predicted_depth output shape', 'test the DPTForSemanticSegmentation model by running a forward pass with labels and verifying logits output shape', 'run tests that validate both timm and HuggingFace backbone initialization with custom out_indices for DPT models', 'run inference with a pretrained Intel/dpt-large model on a sample image and verify predicted depth values', 'test DPTModelTester to prepare config and inputs for DPT depth estimation model testing', 'test DPTModelTest test_for_depth_estimation to run a forward pass and validate depth estimation output', 'test DPTModelIntegrationTest inference with facebook/dpt-dinov2-small-kitti pretrained model and verify predicted depth values', 'test DPTModelIntegrationTest inference with Intel/dpt-swinv2-tiny-256 pretrained model and verify predicted depth output shape', 'test the DPTForDepthEstimation model for depth estimation inference on input images', 'test the DPTForSemanticSegmentation model for semantic segmentation inference on input images', 'test the DPTModel forward pass producing last_hidden_state output tensor', 'test the DPT models training loop with loss computation and gradient backpropagation', 'test loading the Intel/dpt-hybrid-midas pretrained DPT model from HuggingFace Hub']
```

Usage

```
{'test_DPTForDepthEstimation_inference': 'test the DPTForDepthEstimation model for depth estimation inference on input images', 'test_DPTForSemanticSegmentation_inference': 'test the DPTForSemanticSegmentation model for semantic segmentation inference on input images', 'test_DPTModel_forward': 'test the DPTModel forward pass producing last_hidden_state output tensor', 'test_DPT_training': 'test the DPT models training loop with loss computation and gradient backpropagation', 'test_DPT_from_pretrained': 'test loading the Intel/dpt-hybrid-midas pretrained DPT model from HuggingFace Hub'}
```


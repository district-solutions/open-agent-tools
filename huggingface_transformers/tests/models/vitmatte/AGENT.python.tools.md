# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/vitmatte/test_image_processing_vitmatte.py

Prompts

```
['test the VitMatteImageProcessingTester class that prepares image processor configuration dicts and random image inputs', 'test the VitMatte image processor with numpy array inputs and trimaps returning pytorch tensors', 'test the VitMatte image processor with pytorch tensor inputs including batched and non-batched scenarios', 'test the VitMatte image processor padding logic for both PIL and torchvision backends', 'test that all VitMatte image processing backends produce equivalent encoded outputs for the same input', 'run the VitMatteModelTester to create and check model output shape for image matting', 'test the VitMatteForImageMatting model by preparing config and inputs and validating alpha output', 'test loading the hustvl vitmatte-small-composition-1k pretrained model from the HuggingFace hub', 'test backbone selection with timm resnet18 and HF dinov2-small backbones for VitMatte', 'run end-to-end inference with VitMatteImageProcessorPil and VitMatteForImageMatting on an image and trimap']
```

Usage

```
{'test_VitMatteImageProcessingTester': 'test the VitMatteImageProcessingTester class that prepares image processor configuration dicts and random image inputs', 'test_VitMatteImageProcessingTest_call_numpy': 'test the VitMatte image processor with numpy array inputs and trimaps returning pytorch tensors', 'test_VitMatteImageProcessingTest_call_pytorch': 'test the VitMatte image processor with pytorch tensor inputs including batched and non-batched scenarios', 'test_VitMatteImageProcessingTest_padding': 'test the VitMatte image processor padding logic for both PIL and torchvision backends', 'test_VitMatteImageProcessingTest_backends_equivalence': 'test that all VitMatte image processing backends produce equivalent encoded outputs for the same input'}
```

## File: huggingface_transformers/tests/models/vitmatte/test_modeling_vitmatte.py

Prompts

```
['test the VitMatteImageProcessingTester class that prepares image processor configuration dicts and random image inputs', 'test the VitMatte image processor with numpy array inputs and trimaps returning pytorch tensors', 'test the VitMatte image processor with pytorch tensor inputs including batched and non-batched scenarios', 'test the VitMatte image processor padding logic for both PIL and torchvision backends', 'test that all VitMatte image processing backends produce equivalent encoded outputs for the same input', 'run the VitMatteModelTester to create and check model output shape for image matting', 'test the VitMatteForImageMatting model by preparing config and inputs and validating alpha output', 'test loading the hustvl vitmatte-small-composition-1k pretrained model from the HuggingFace hub', 'test backbone selection with timm resnet18 and HF dinov2-small backbones for VitMatte', 'run end-to-end inference with VitMatteImageProcessorPil and VitMatteForImageMatting on an image and trimap']
```

Usage

```
{'run_VitMatteModelTester_create_and_check_model': 'run the VitMatteModelTester to create and check model output shape for image matting', 'test_VitMatteModelTest_test_model': 'test the VitMatteForImageMatting model by preparing config and inputs and validating alpha output', 'test_VitMatteModelTest_test_model_from_pretrained': 'test loading the hustvl vitmatte-small-composition-1k pretrained model from the HuggingFace hub', 'test_VitMatteModelTest_test_backbone_selection': 'test backbone selection with timm resnet18 and HF dinov2-small backbones for VitMatte', 'run_VitMatteModelIntegrationTest_test_inference': 'run end-to-end inference with VitMatteImageProcessorPil and VitMatteForImageMatting on an image and trimap'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/vitpose/test_image_processing_vitpose.py

Prompts

```
['test the VitPoseImageProcessingTester class that prepares image processor configuration dicts and dummy image inputs', 'test the VitPose image processor with PIL image inputs in both batched and non-batched modes', 'test the VitPose image processor with numpy array inputs including 4 channel images', 'test that all VitPose image processing backends produce equivalent output tensors for the same input', 'test that the VitPose torchvision backend image processor can be compiled with torch.compile', 'test the VitPoseModelTester to prepare config and input tensors for the VitPose model', 'test the VitPoseModelTester to create and verify pose estimation model output shapes', 'test the VitPoseModelTest to verify the forward method signature accepts pixel_values', 'test the VitPoseModelIntegrationTest to run single image pose estimation inference with expected heatmaps', 'test the VitPoseModelIntegrationTest to run batched pose estimation inference on multiple images']
```

Usage

```
{'test_VitPoseImageProcessingTester': 'test the VitPoseImageProcessingTester class that prepares image processor configuration dicts and dummy image inputs', 'test_VitPoseImageProcessingTest_call_pil': 'test the VitPose image processor with PIL image inputs in both batched and non-batched modes', 'test_VitPoseImageProcessingTest_call_numpy': 'test the VitPose image processor with numpy array inputs including 4 channel images', 'test_VitPoseImageProcessingTest_backends_equivalence': 'test that all VitPose image processing backends produce equivalent output tensors for the same input', 'test_VitPoseImageProcessingTest_torch_compile': 'test that the VitPose torchvision backend image processor can be compiled with torch.compile'}
```

## File: huggingface_transformers/tests/models/vitpose/test_modeling_vitpose.py

Prompts

```
['test the VitPoseImageProcessingTester class that prepares image processor configuration dicts and dummy image inputs', 'test the VitPose image processor with PIL image inputs in both batched and non-batched modes', 'test the VitPose image processor with numpy array inputs including 4 channel images', 'test that all VitPose image processing backends produce equivalent output tensors for the same input', 'test that the VitPose torchvision backend image processor can be compiled with torch.compile', 'test the VitPoseModelTester to prepare config and input tensors for the VitPose model', 'test the VitPoseModelTester to create and verify pose estimation model output shapes', 'test the VitPoseModelTest to verify the forward method signature accepts pixel_values', 'test the VitPoseModelIntegrationTest to run single image pose estimation inference with expected heatmaps', 'test the VitPoseModelIntegrationTest to run batched pose estimation inference on multiple images']
```

Usage

```
{'test_VitPoseModelTester_prepare_config_and_inputs': 'test the VitPoseModelTester to prepare config and input tensors for the VitPose model', 'test_VitPoseModelTester_create_and_check_for_pose_estimation': 'test the VitPoseModelTester to create and verify pose estimation model output shapes', 'test_VitPoseModelTest_forward_signature': 'test the VitPoseModelTest to verify the forward method signature accepts pixel_values', 'test_VitPoseModelIntegrationTest_inference_pose_estimation': 'test the VitPoseModelIntegrationTest to run single image pose estimation inference with expected heatmaps', 'test_VitPoseModelIntegrationTest_batched_inference': 'test the VitPoseModelIntegrationTest to run batched pose estimation inference on multiple images'}
```


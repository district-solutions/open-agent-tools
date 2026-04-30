# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/tvp/test_image_processing_tvp.py

Prompts

```
['test TvpImageProcessingTester to prepare an image processor configuration dictionary with normalization and padding settings', 'test TvpImageProcessingTester to compute expected output height and width for batched or single video inputs', 'test TvpImageProcessingTester to generate dummy video inputs as PIL images, numpy arrays, or PyTorch tensors', 'test TvpImageProcessingTest to process single and batched PIL video inputs and verify output tensor shapes', 'test TvpImageProcessingTest to verify PIL and torchvision backends produce equivalent encoded video pixel values', 'test TVPModelTester to prepare config and inputs for TVP model testing', 'test TVPModelTester get_config method to create TvpConfig with ResNet backbone', 'test TVPModelTest backbone selection with timm and HF backbone configs', 'test TvpModel integration inference without head using pretrained tiny-random-tvp model', 'test TvpModel integration inference with interpolated positional encoding for non-square images']
```

Usage

```
{'test_TvpImageProcessingTester_prepare_processor_dict': 'test TvpImageProcessingTester to prepare an image processor configuration dictionary with normalization and padding settings', 'test_TvpImageProcessingTester_get_expected_values': 'test TvpImageProcessingTester to compute expected output height and width for batched or single video inputs', 'test_TvpImageProcessingTester_prepare_video_inputs': 'test TvpImageProcessingTester to generate dummy video inputs as PIL images, numpy arrays, or PyTorch tensors', 'test_TvpImageProcessingTest_call_pil': 'test TvpImageProcessingTest to process single and batched PIL video inputs and verify output tensor shapes', 'test_TvpImageProcessingTest_backends_equivalence': 'test TvpImageProcessingTest to verify PIL and torchvision backends produce equivalent encoded video pixel values'}
```

## File: huggingface_transformers/tests/models/tvp/test_modeling_tvp.py

Prompts

```
['test TvpImageProcessingTester to prepare an image processor configuration dictionary with normalization and padding settings', 'test TvpImageProcessingTester to compute expected output height and width for batched or single video inputs', 'test TvpImageProcessingTester to generate dummy video inputs as PIL images, numpy arrays, or PyTorch tensors', 'test TvpImageProcessingTest to process single and batched PIL video inputs and verify output tensor shapes', 'test TvpImageProcessingTest to verify PIL and torchvision backends produce equivalent encoded video pixel values', 'test TVPModelTester to prepare config and inputs for TVP model testing', 'test TVPModelTester get_config method to create TvpConfig with ResNet backbone', 'test TVPModelTest backbone selection with timm and HF backbone configs', 'test TvpModel integration inference without head using pretrained tiny-random-tvp model', 'test TvpModel integration inference with interpolated positional encoding for non-square images']
```

Usage

```
{'test_TVPModelTester_prepare_config_and_inputs': 'test TVPModelTester to prepare config and inputs for TVP model testing', 'test_TVPModelTester_get_config': 'test TVPModelTester get_config method to create TvpConfig with ResNet backbone', 'test_TVPModelTest_backbone_selection': 'test TVPModelTest backbone selection with timm and HF backbone configs', 'test_TvpModelIntegrationTests_inference_no_head': 'test TvpModel integration inference without head using pretrained tiny-random-tvp model', 'test_TvpModelIntegrationTests_interpolate_inference': 'test TvpModel integration inference with interpolated positional encoding for non-square images'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/vivit/test_image_processing_vivit.py

Prompts

```
['create a VivitImageProcessor instance with configurable size, crop_size, mean, std, and normalization settings', 'test VivitImageProcessor has image_mean, image_std, do_normalize, do_resize, do_center_crop, and size attributes', 'build a VivitImageProcessor from a config dict with optional kwargs to override size and crop_size', 'test rescaling video frames between -1 and 1 or 0 and 1 with configurable scale and offset parameters', 'test processing PIL image video inputs through VivitImageProcessor with batched and unbatched modes', 'test processing numpy array video inputs through VivitImageProcessor with batched and unbatched modes', 'test processing PyTorch tensor video inputs through VivitImageProcessor with batched and unbatched modes', 'test processing 4-channel numpy video inputs with custom mean, std, and channels_first input format', 'build a VivitImageProcessingTester with configurable batch_size, num_frames, image_size, and preprocessing parameters', 'test the VivitModelTester class that prepares configs and inputs for ViViT model unit tests', 'test the VivitModelTest class that validates VivitModel and VivitForVideoClassification forward passes and attention outputs', 'test the VivitModelIntegrationTest class that runs inference on pretrained Vivit models with video input', 'run VivitModel.from_pretrained with google/vivit-b-16x2-kinetics400 and verify model loads correctly', 'test the VivitConfig class that configures ViViT model hyperparameters including hidden_size, num_hidden_layers, and tubelet_size']
```

Usage

```
{'create_VivitImageProcessor': 'create a VivitImageProcessor instance with configurable size, crop_size, mean, std, and normalization settings', 'test_VivitImageProcessor_properties': 'test VivitImageProcessor has image_mean, image_std, do_normalize, do_resize, do_center_crop, and size attributes', 'test_VivitImageProcessor_from_dict': 'build a VivitImageProcessor from a config dict with optional kwargs to override size and crop_size', 'test_VivitImageProcessor_rescale': 'test rescaling video frames between -1 and 1 or 0 and 1 with configurable scale and offset parameters', 'test_VivitImageProcessor_call_pil': 'test processing PIL image video inputs through VivitImageProcessor with batched and unbatched modes', 'test_VivitImageProcessor_call_numpy': 'test processing numpy array video inputs through VivitImageProcessor with batched and unbatched modes', 'test_VivitImageProcessor_call_pytorch': 'test processing PyTorch tensor video inputs through VivitImageProcessor with batched and unbatched modes', 'test_VivitImageProcessor_4_channels': 'test processing 4-channel numpy video inputs with custom mean, std, and channels_first input format', 'build_VivitImageProcessingTester': 'build a VivitImageProcessingTester with configurable batch_size, num_frames, image_size, and preprocessing parameters'}
```

## File: huggingface_transformers/tests/models/vivit/test_modeling_vivit.py

Prompts

```
['create a VivitImageProcessor instance with configurable size, crop_size, mean, std, and normalization settings', 'test VivitImageProcessor has image_mean, image_std, do_normalize, do_resize, do_center_crop, and size attributes', 'build a VivitImageProcessor from a config dict with optional kwargs to override size and crop_size', 'test rescaling video frames between -1 and 1 or 0 and 1 with configurable scale and offset parameters', 'test processing PIL image video inputs through VivitImageProcessor with batched and unbatched modes', 'test processing numpy array video inputs through VivitImageProcessor with batched and unbatched modes', 'test processing PyTorch tensor video inputs through VivitImageProcessor with batched and unbatched modes', 'test processing 4-channel numpy video inputs with custom mean, std, and channels_first input format', 'build a VivitImageProcessingTester with configurable batch_size, num_frames, image_size, and preprocessing parameters', 'test the VivitModelTester class that prepares configs and inputs for ViViT model unit tests', 'test the VivitModelTest class that validates VivitModel and VivitForVideoClassification forward passes and attention outputs', 'test the VivitModelIntegrationTest class that runs inference on pretrained Vivit models with video input', 'run VivitModel.from_pretrained with google/vivit-b-16x2-kinetics400 and verify model loads correctly', 'test the VivitConfig class that configures ViViT model hyperparameters including hidden_size, num_hidden_layers, and tubelet_size']
```

Usage

```
{'test_VivitModelTester': 'test the VivitModelTester class that prepares configs and inputs for ViViT model unit tests', 'test_VivitModelTest': 'test the VivitModelTest class that validates VivitModel and VivitForVideoClassification forward passes and attention outputs', 'test_VivitModelIntegrationTest': 'test the VivitModelIntegrationTest class that runs inference on pretrained Vivit models with video input', 'run_VivitModel_from_pretrained': 'run VivitModel.from_pretrained with google/vivit-b-16x2-kinetics400 and verify model loads correctly', 'test_VivitConfig': 'test the VivitConfig class that configures ViViT model hyperparameters including hidden_size, num_hidden_layers, and tubelet_size'}
```


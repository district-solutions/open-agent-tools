# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/swin2sr/test_image_processing_swin2sr.py

Prompts

```
['test the Swin2SRImageProcessingTest class to verify image processor properties like do_rescale and size_divisor', 'test the Swin2SR image processor with PIL images and verify output shape matches expected padded dimensions', 'test the Swin2SR image processor with numpy arrays and verify output shape matches expected padded dimensions', 'test the Swin2SR image processor with PyTorch tensors and verify output shape matches expected padded dimensions', 'test the Swin2SR image processor backends equivalence by comparing pixel values across multiple backends', 'test the Swin2SRModel forward pass and verify output shape matches expected dimensions', 'test Swin2SRForImageSuperResolution and verify reconstruction output shape with upscale factor', 'test Swin2SRModel attention output shapes and verify number of attention layers matches config depths', 'test Swin2SRConfig common properties including image_size, patch_size, and num_channels', 'run Swin2SRForImageSuperResolution inference on a COCO image and verify reconstruction shape and pixel values']
```

Usage

```
{'test_swin2sr_image_processor_properties': 'test the Swin2SRImageProcessingTest class to verify image processor properties like do_rescale and size_divisor', 'test_swin2sr_pil_input': 'test the Swin2SR image processor with PIL images and verify output shape matches expected padded dimensions', 'test_swin2sr_numpy_input': 'test the Swin2SR image processor with numpy arrays and verify output shape matches expected padded dimensions', 'test_swin2sr_pytorch_input': 'test the Swin2SR image processor with PyTorch tensors and verify output shape matches expected padded dimensions', 'test_swin2sr_backends_equivalence': 'test the Swin2SR image processor backends equivalence by comparing pixel values across multiple backends'}
```

## File: huggingface_transformers/tests/models/swin2sr/test_modeling_swin2sr.py

Prompts

```
['test the Swin2SRImageProcessingTest class to verify image processor properties like do_rescale and size_divisor', 'test the Swin2SR image processor with PIL images and verify output shape matches expected padded dimensions', 'test the Swin2SR image processor with numpy arrays and verify output shape matches expected padded dimensions', 'test the Swin2SR image processor with PyTorch tensors and verify output shape matches expected padded dimensions', 'test the Swin2SR image processor backends equivalence by comparing pixel values across multiple backends', 'test the Swin2SRModel forward pass and verify output shape matches expected dimensions', 'test Swin2SRForImageSuperResolution and verify reconstruction output shape with upscale factor', 'test Swin2SRModel attention output shapes and verify number of attention layers matches config depths', 'test Swin2SRConfig common properties including image_size, patch_size, and num_channels', 'run Swin2SRForImageSuperResolution inference on a COCO image and verify reconstruction shape and pixel values']
```

Usage

```
{'test_swin2sr_model_forward': 'test the Swin2SRModel forward pass and verify output shape matches expected dimensions', 'test_swin2sr_super_resolution': 'test Swin2SRForImageSuperResolution and verify reconstruction output shape with upscale factor', 'test_swin2sr_attention_outputs': 'test Swin2SRModel attention output shapes and verify number of attention layers matches config depths', 'test_swin2sr_config': 'test Swin2SRConfig common properties including image_size, patch_size, and num_channels', 'test_swin2sr_inference_sr': 'run Swin2SRForImageSuperResolution inference on a COCO image and verify reconstruction shape and pixel values'}
```


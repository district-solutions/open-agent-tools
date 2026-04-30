# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/glpn/test_image_processing_glpn.py

Prompts

```
['test the GLPNImageProcessingTest class verifies image processor properties like do_resize and size_divisor', 'test the GLPNImageProcessor with PIL image inputs and verify encoded output shape', 'test the GLPNImageProcessor with numpy array inputs and verify encoded output shape', 'test the GLPNImageProcessor with PyTorch tensor inputs and verify encoded output shape', 'test that multiple GLPN backend image processors produce equivalent batched outputs', 'test the GLPNModel class for correct forward pass output shapes with given config and pixel values', 'test GLPNForDepthEstimation model produces predicted depth tensors with correct batch and image dimensions', 'test GLPN attention output shapes across encoder blocks with output_attentions enabled', 'test GLPN hidden states output shapes at each encoder block with output_hidden_states enabled', 'test GLPN model training loop with loss computation and backward pass for depth estimation']
```

Usage

```
{'test_image_processor_properties': 'test the GLPNImageProcessingTest class verifies image processor properties like do_resize and size_divisor', 'test_call_pil': 'test the GLPNImageProcessor with PIL image inputs and verify encoded output shape', 'test_call_numpy': 'test the GLPNImageProcessor with numpy array inputs and verify encoded output shape', 'test_call_pytorch': 'test the GLPNImageProcessor with PyTorch tensor inputs and verify encoded output shape', 'test_backends_equivalence_batched': 'test that multiple GLPN backend image processors produce equivalent batched outputs'}
```

## File: huggingface_transformers/tests/models/glpn/test_modeling_glpn.py

Prompts

```
['test the GLPNImageProcessingTest class verifies image processor properties like do_resize and size_divisor', 'test the GLPNImageProcessor with PIL image inputs and verify encoded output shape', 'test the GLPNImageProcessor with numpy array inputs and verify encoded output shape', 'test the GLPNImageProcessor with PyTorch tensor inputs and verify encoded output shape', 'test that multiple GLPN backend image processors produce equivalent batched outputs', 'test the GLPNModel class for correct forward pass output shapes with given config and pixel values', 'test GLPNForDepthEstimation model produces predicted depth tensors with correct batch and image dimensions', 'test GLPN attention output shapes across encoder blocks with output_attentions enabled', 'test GLPN hidden states output shapes at each encoder block with output_hidden_states enabled', 'test GLPN model training loop with loss computation and backward pass for depth estimation']
```

Usage

```
{'test_model_glpn': 'test the GLPNModel class for correct forward pass output shapes with given config and pixel values', 'test_depth_estimation': 'test GLPNForDepthEstimation model produces predicted depth tensors with correct batch and image dimensions', 'test_attention_outputs': 'test GLPN attention output shapes across encoder blocks with output_attentions enabled', 'test_hidden_states': 'test GLPN hidden states output shapes at each encoder block with output_hidden_states enabled', 'test_training': 'test GLPN model training loop with loss computation and backward pass for depth estimation'}
```


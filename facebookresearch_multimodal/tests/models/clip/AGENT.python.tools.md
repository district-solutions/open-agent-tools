# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/tests/models/clip/test_checkpoint.py

Prompts

```
['run the pytest test for the CLIP ViT-B/16 pretrained checkpoint model', 'run the pytest test for the CLIP ViT-L/14 pretrained checkpoint model', 'run the pytest test for the CLIP ResNet-50 pretrained checkpoint model', 'run the pytest test for the CLIP ResNet-50x64 pretrained checkpoint model', 'test the TestCLIPCheckpoint class to verify all pretrained CLIP model embeddings and output shapes', 'test the CLIP model forward pass with Linear encoders and verify embedding outputs', 'test the CLIP model forward pass using a ResNet image encoder and CLIPTextEncoder', 'test the CLIP model forward pass using a VisionTransformer image encoder and CLIPTextEncoder', 'create a CLIP model with a ResNetForCLIP image encoder and CLIPTextEncoder text encoder', 'create a CLIP model with a VisionTransformer image encoder and CLIPTextEncoder text encoder', 'test the ResNetForCLIP encoder by passing a random image tensor and verifying output shape and sum', 'test the CLIPViTEncoder forward pass with a ones tensor and assert expected output values', 'test that CLIPViTEncoder raises ValueError when given mismatched image dimensions or channel count', 'review the ResNetForCLIP class constructor to understand layers, output_dim, and heads parameters', 'review the CLIPViTEncoder class constructor to understand embedding_dim, heads, layers, patch_size, image_size, and width parameters', 'test CLIPTextEncoder token and positional embedding weight initialization standard deviations', 'test CLIPTextEncoder build_attention_mask method produces a causal lower triangular mask', 'test CLIPTextEncoder forward pass with clip initialization and expected output values', 'test CLIPTextEncoder forward pass returning hidden states with return_hidden_state flag', 'test CLIPTextEncoder compatibility with torch.jit.script for TorchScript compilation']
```

Usage

```
{'run_test_clip_vit_b16': 'run the pytest test for the CLIP ViT-B/16 pretrained checkpoint model', 'run_test_clip_vit_l14': 'run the pytest test for the CLIP ViT-L/14 pretrained checkpoint model', 'run_test_clip_rn50': 'run the pytest test for the CLIP ResNet-50 pretrained checkpoint model', 'run_test_clip_rn50x64': 'run the pytest test for the CLIP ResNet-50x64 pretrained checkpoint model', 'test_TestCLIPCheckpoint': 'test the TestCLIPCheckpoint class to verify all pretrained CLIP model embeddings and output shapes'}
```

## File: facebookresearch_multimodal/tests/models/clip/test_clip.py

Prompts

```
['run the pytest test for the CLIP ViT-B/16 pretrained checkpoint model', 'run the pytest test for the CLIP ViT-L/14 pretrained checkpoint model', 'run the pytest test for the CLIP ResNet-50 pretrained checkpoint model', 'run the pytest test for the CLIP ResNet-50x64 pretrained checkpoint model', 'test the TestCLIPCheckpoint class to verify all pretrained CLIP model embeddings and output shapes', 'test the CLIP model forward pass with Linear encoders and verify embedding outputs', 'test the CLIP model forward pass using a ResNet image encoder and CLIPTextEncoder', 'test the CLIP model forward pass using a VisionTransformer image encoder and CLIPTextEncoder', 'create a CLIP model with a ResNetForCLIP image encoder and CLIPTextEncoder text encoder', 'create a CLIP model with a VisionTransformer image encoder and CLIPTextEncoder text encoder', 'test the ResNetForCLIP encoder by passing a random image tensor and verifying output shape and sum', 'test the CLIPViTEncoder forward pass with a ones tensor and assert expected output values', 'test that CLIPViTEncoder raises ValueError when given mismatched image dimensions or channel count', 'review the ResNetForCLIP class constructor to understand layers, output_dim, and heads parameters', 'review the CLIPViTEncoder class constructor to understand embedding_dim, heads, layers, patch_size, image_size, and width parameters', 'test CLIPTextEncoder token and positional embedding weight initialization standard deviations', 'test CLIPTextEncoder build_attention_mask method produces a causal lower triangular mask', 'test CLIPTextEncoder forward pass with clip initialization and expected output values', 'test CLIPTextEncoder forward pass returning hidden states with return_hidden_state flag', 'test CLIPTextEncoder compatibility with torch.jit.script for TorchScript compilation']
```

Usage

```
{'test_CLIP_forward': 'test the CLIP model forward pass with Linear encoders and verify embedding outputs', 'test_CLIP_resnet_forward': 'test the CLIP model forward pass using a ResNet image encoder and CLIPTextEncoder', 'test_CLIP_vit_forward': 'test the CLIP model forward pass using a VisionTransformer image encoder and CLIPTextEncoder', 'create_CLIP_with_ResNet': 'create a CLIP model with a ResNetForCLIP image encoder and CLIPTextEncoder text encoder', 'create_CLIP_with_VisionTransformer': 'create a CLIP model with a VisionTransformer image encoder and CLIPTextEncoder text encoder'}
```

## File: facebookresearch_multimodal/tests/models/clip/test_image_encoder.py

Prompts

```
['run the pytest test for the CLIP ViT-B/16 pretrained checkpoint model', 'run the pytest test for the CLIP ViT-L/14 pretrained checkpoint model', 'run the pytest test for the CLIP ResNet-50 pretrained checkpoint model', 'run the pytest test for the CLIP ResNet-50x64 pretrained checkpoint model', 'test the TestCLIPCheckpoint class to verify all pretrained CLIP model embeddings and output shapes', 'test the CLIP model forward pass with Linear encoders and verify embedding outputs', 'test the CLIP model forward pass using a ResNet image encoder and CLIPTextEncoder', 'test the CLIP model forward pass using a VisionTransformer image encoder and CLIPTextEncoder', 'create a CLIP model with a ResNetForCLIP image encoder and CLIPTextEncoder text encoder', 'create a CLIP model with a VisionTransformer image encoder and CLIPTextEncoder text encoder', 'test the ResNetForCLIP encoder by passing a random image tensor and verifying output shape and sum', 'test the CLIPViTEncoder forward pass with a ones tensor and assert expected output values', 'test that CLIPViTEncoder raises ValueError when given mismatched image dimensions or channel count', 'review the ResNetForCLIP class constructor to understand layers, output_dim, and heads parameters', 'review the CLIPViTEncoder class constructor to understand embedding_dim, heads, layers, patch_size, image_size, and width parameters', 'test CLIPTextEncoder token and positional embedding weight initialization standard deviations', 'test CLIPTextEncoder build_attention_mask method produces a causal lower triangular mask', 'test CLIPTextEncoder forward pass with clip initialization and expected output values', 'test CLIPTextEncoder forward pass returning hidden states with return_hidden_state flag', 'test CLIPTextEncoder compatibility with torch.jit.script for TorchScript compilation']
```

Usage

```
{'test_ResNetForCLIP_forward': 'test the ResNetForCLIP encoder by passing a random image tensor and verifying output shape and sum', 'test_CLIPViTEncoder_forward': 'test the CLIPViTEncoder forward pass with a ones tensor and assert expected output values', 'test_CLIPViTEncoder_invalid_input': 'test that CLIPViTEncoder raises ValueError when given mismatched image dimensions or channel count', 'review_ResNetForCLIP_constructor': 'review the ResNetForCLIP class constructor to understand layers, output_dim, and heads parameters', 'review_CLIPViTEncoder_constructor': 'review the CLIPViTEncoder class constructor to understand embedding_dim, heads, layers, patch_size, image_size, and width parameters'}
```

## File: facebookresearch_multimodal/tests/models/clip/test_text_encoder.py

Prompts

```
['run the pytest test for the CLIP ViT-B/16 pretrained checkpoint model', 'run the pytest test for the CLIP ViT-L/14 pretrained checkpoint model', 'run the pytest test for the CLIP ResNet-50 pretrained checkpoint model', 'run the pytest test for the CLIP ResNet-50x64 pretrained checkpoint model', 'test the TestCLIPCheckpoint class to verify all pretrained CLIP model embeddings and output shapes', 'test the CLIP model forward pass with Linear encoders and verify embedding outputs', 'test the CLIP model forward pass using a ResNet image encoder and CLIPTextEncoder', 'test the CLIP model forward pass using a VisionTransformer image encoder and CLIPTextEncoder', 'create a CLIP model with a ResNetForCLIP image encoder and CLIPTextEncoder text encoder', 'create a CLIP model with a VisionTransformer image encoder and CLIPTextEncoder text encoder', 'test the ResNetForCLIP encoder by passing a random image tensor and verifying output shape and sum', 'test the CLIPViTEncoder forward pass with a ones tensor and assert expected output values', 'test that CLIPViTEncoder raises ValueError when given mismatched image dimensions or channel count', 'review the ResNetForCLIP class constructor to understand layers, output_dim, and heads parameters', 'review the CLIPViTEncoder class constructor to understand embedding_dim, heads, layers, patch_size, image_size, and width parameters', 'test CLIPTextEncoder token and positional embedding weight initialization standard deviations', 'test CLIPTextEncoder build_attention_mask method produces a causal lower triangular mask', 'test CLIPTextEncoder forward pass with clip initialization and expected output values', 'test CLIPTextEncoder forward pass returning hidden states with return_hidden_state flag', 'test CLIPTextEncoder compatibility with torch.jit.script for TorchScript compilation']
```

Usage

```
{'test_CLIPTextEncoder_parameters': 'test CLIPTextEncoder token and positional embedding weight initialization standard deviations', 'test_CLIPTextEncoder_attention_mask': 'test CLIPTextEncoder build_attention_mask method produces a causal lower triangular mask', 'test_CLIPTextEncoder_forward': 'test CLIPTextEncoder forward pass with clip initialization and expected output values', 'test_CLIPTextEncoder_hidden_state': 'test CLIPTextEncoder forward pass returning hidden states with return_hidden_state flag', 'test_CLIPTextEncoder_torchscript': 'test CLIPTextEncoder compatibility with torch.jit.script for TorchScript compilation'}
```


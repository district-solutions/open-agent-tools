# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/aimv2/test_modeling_aimv2.py

Prompts

```
['test the Aimv2VisionModel forward pass with pixel values and verify output shapes', 'test the Aimv2TextModel forward pass with input ids and attention mask and verify output shapes', 'test the Aimv2Model multimodal forward pass with text and image inputs and verify cross-modal logits', 'test that SDPA and eager attention implementations produce matching inference results for Aimv2Model', 'run slow inference tests against the pretrained apple/aimv2-large-patch14-224 vision model']
```

Usage

```
{'test_aimv2_vision_model': 'test the Aimv2VisionModel forward pass with pixel values and verify output shapes', 'test_aimv2_text_model': 'test the Aimv2TextModel forward pass with input ids and attention mask and verify output shapes', 'test_aimv2_multimodal_model': 'test the Aimv2Model multimodal forward pass with text and image inputs and verify cross-modal logits', 'test_aimv2_sdpa_attention': 'test that SDPA and eager attention implementations produce matching inference results for Aimv2Model', 'test_aimv2_vision_integration': 'run slow inference tests against the pretrained apple/aimv2-large-patch14-224 vision model'}
```


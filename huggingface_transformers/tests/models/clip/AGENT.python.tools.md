# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/clip/test_modeling_clip.py

Prompts

```
['test the CLIPVisionModel class with pixel values and verify output shapes for last_hidden_state and pooler_output', 'test the CLIPTextModel class with input_ids and attention_mask and verify output shapes for last_hidden_state and pooler_output', 'test the CLIPModel class with input_ids, pixel_values, and attention_mask and verify logits_per_image and logits_per_text shapes', 'test the CLIPForImageClassification model with pixel_values and verify inference output', 'test that SDPA attention implementation is correctly dispatched to vision_model and text_model submodules in composite CLIP models', 'test CLIPModel inference with a real image and text prompts and verify logits match expected values', 'test CLIPModel position encoding interpolation for higher resolution images and verify hidden state shapes', 'create a CLIPTokenizer by loading the openai/clip-vit-base-patch32 model from Hugging Face Hub', 'create a CLIPTokenizer from a custom vocab dictionary and BPE merges list', 'test the CLIPTokenizer padding behavior with a skipped padding-to-multiple-of test', 'test the CLIPTokenizer tokenization using TokenizerTesterMixin inherited test methods', 'save a pretrained CLIPTokenizer to a local directory with pad_token configured']
```

Usage

```
{'test_clip_vision_model': 'test the CLIPVisionModel class with pixel values and verify output shapes for last_hidden_state and pooler_output', 'test_clip_text_model': 'test the CLIPTextModel class with input_ids and attention_mask and verify output shapes for last_hidden_state and pooler_output', 'test_clip_model': 'test the CLIPModel class with input_ids, pixel_values, and attention_mask and verify logits_per_image and logits_per_text shapes', 'test_clip_image_classification': 'test the CLIPForImageClassification model with pixel_values and verify inference output', 'test_sdpa_attention_dispatch': 'test that SDPA attention implementation is correctly dispatched to vision_model and text_model submodules in composite CLIP models', 'test_clip_model_integration': 'test CLIPModel inference with a real image and text prompts and verify logits match expected values', 'test_clip_pos_encoding_interpolation': 'test CLIPModel position encoding interpolation for higher resolution images and verify hidden state shapes'}
```

## File: huggingface_transformers/tests/models/clip/test_tokenization_clip.py

Prompts

```
['test the CLIPVisionModel class with pixel values and verify output shapes for last_hidden_state and pooler_output', 'test the CLIPTextModel class with input_ids and attention_mask and verify output shapes for last_hidden_state and pooler_output', 'test the CLIPModel class with input_ids, pixel_values, and attention_mask and verify logits_per_image and logits_per_text shapes', 'test the CLIPForImageClassification model with pixel_values and verify inference output', 'test that SDPA attention implementation is correctly dispatched to vision_model and text_model submodules in composite CLIP models', 'test CLIPModel inference with a real image and text prompts and verify logits match expected values', 'test CLIPModel position encoding interpolation for higher resolution images and verify hidden state shapes', 'create a CLIPTokenizer by loading the openai/clip-vit-base-patch32 model from Hugging Face Hub', 'create a CLIPTokenizer from a custom vocab dictionary and BPE merges list', 'test the CLIPTokenizer padding behavior with a skipped padding-to-multiple-of test', 'test the CLIPTokenizer tokenization using TokenizerTesterMixin inherited test methods', 'save a pretrained CLIPTokenizer to a local directory with pad_token configured']
```

Usage

```
{'create_cliptokenizer_from_pretrained': 'create a CLIPTokenizer by loading the openai/clip-vit-base-patch32 model from Hugging Face Hub', 'create_cliptokenizer_from_vocab': 'create a CLIPTokenizer from a custom vocab dictionary and BPE merges list', 'test_cliptokenizer_padding': 'test the CLIPTokenizer padding behavior with a skipped padding-to-multiple-of test', 'test_cliptokenizer_tokenization': 'test the CLIPTokenizer tokenization using TokenizerTesterMixin inherited test methods', 'save_cliptokenizer_pretrained': 'save a pretrained CLIPTokenizer to a local directory with pad_token configured'}
```


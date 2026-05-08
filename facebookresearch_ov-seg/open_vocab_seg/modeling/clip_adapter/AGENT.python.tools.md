# Agent Python Tools

- repo: facebookresearch/ov-seg
- repo_uri: https://github.com/facebookresearch/ov-seg

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/clip_adapter/adapter.py

Prompts

```
['build a ClipAdapter module to compute similarity logits between CLIP image and text features', 'create a MaskFormerClipAdapter to extract image features from masked regions and compare with text', 'test the get_sim_logits method to compute temperature-scaled dot product between text and image features', 'review the ClipAdapter forward pass that preprocesses images and computes text-image similarity', 'refactor the MaskFormerClipAdapter _preprocess_image method to crop, normalize, and resize masked image regions', 'create a PredefinedPromptExtractor with custom text templates for CLIP text feature extraction', 'run the ImageNetPromptExtractor to encode class names using 100 ImageNet-style prompt templates', 'run the VILDPromptExtractor to encode class names using 14 VILD-style prompt templates', 'review the PromptExtractor base class and its init_buffer and forward interface', 'summarize the IMAGENET_PROMPT list of 100 text templates for zero-shot classification', 'build a CLIP model from a name string with optional frozen parameters for open vocabulary segmentation', 'expand a bounding box by a ratio and clamp coordinates to image dimensions', 'convert a binary mask tensor into a bounding box with min and max coordinates', 'crop an image tensor using a mask and bounding box with configurable fill values', 'review the expand_box function to understand bounding box expansion and clamping logic']
```

Usage

```
{'build_clip_adapter': 'build a ClipAdapter module to compute similarity logits between CLIP image and text features', 'create_mask_former_clip_adapter': 'create a MaskFormerClipAdapter to extract image features from masked regions and compare with text', 'test_get_sim_logits': 'test the get_sim_logits method to compute temperature-scaled dot product between text and image features', 'review_clip_adapter_forward': 'review the ClipAdapter forward pass that preprocesses images and computes text-image similarity', 'refactor_preprocess_image': 'refactor the MaskFormerClipAdapter _preprocess_image method to crop, normalize, and resize masked image regions'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/clip_adapter/text_template.py

Prompts

```
['build a ClipAdapter module to compute similarity logits between CLIP image and text features', 'create a MaskFormerClipAdapter to extract image features from masked regions and compare with text', 'test the get_sim_logits method to compute temperature-scaled dot product between text and image features', 'review the ClipAdapter forward pass that preprocesses images and computes text-image similarity', 'refactor the MaskFormerClipAdapter _preprocess_image method to crop, normalize, and resize masked image regions', 'create a PredefinedPromptExtractor with custom text templates for CLIP text feature extraction', 'run the ImageNetPromptExtractor to encode class names using 100 ImageNet-style prompt templates', 'run the VILDPromptExtractor to encode class names using 14 VILD-style prompt templates', 'review the PromptExtractor base class and its init_buffer and forward interface', 'summarize the IMAGENET_PROMPT list of 100 text templates for zero-shot classification', 'build a CLIP model from a name string with optional frozen parameters for open vocabulary segmentation', 'expand a bounding box by a ratio and clamp coordinates to image dimensions', 'convert a binary mask tensor into a bounding box with min and max coordinates', 'crop an image tensor using a mask and bounding box with configurable fill values', 'review the expand_box function to understand bounding box expansion and clamping logic']
```

Usage

```
{'create_PredefinedPromptExtractor': 'create a PredefinedPromptExtractor with custom text templates for CLIP text feature extraction', 'run_ImageNetPromptExtractor': 'run the ImageNetPromptExtractor to encode class names using 100 ImageNet-style prompt templates', 'run_VILDPromptExtractor': 'run the VILDPromptExtractor to encode class names using 14 VILD-style prompt templates', 'review_PromptExtractor': 'review the PromptExtractor base class and its init_buffer and forward interface', 'summarize_IMAGENET_PROMPT': 'summarize the IMAGENET_PROMPT list of 100 text templates for zero-shot classification'}
```

## File: facebookresearch_ov-seg/open_vocab_seg/modeling/clip_adapter/utils.py

Prompts

```
['build a ClipAdapter module to compute similarity logits between CLIP image and text features', 'create a MaskFormerClipAdapter to extract image features from masked regions and compare with text', 'test the get_sim_logits method to compute temperature-scaled dot product between text and image features', 'review the ClipAdapter forward pass that preprocesses images and computes text-image similarity', 'refactor the MaskFormerClipAdapter _preprocess_image method to crop, normalize, and resize masked image regions', 'create a PredefinedPromptExtractor with custom text templates for CLIP text feature extraction', 'run the ImageNetPromptExtractor to encode class names using 100 ImageNet-style prompt templates', 'run the VILDPromptExtractor to encode class names using 14 VILD-style prompt templates', 'review the PromptExtractor base class and its init_buffer and forward interface', 'summarize the IMAGENET_PROMPT list of 100 text templates for zero-shot classification', 'build a CLIP model from a name string with optional frozen parameters for open vocabulary segmentation', 'expand a bounding box by a ratio and clamp coordinates to image dimensions', 'convert a binary mask tensor into a bounding box with min and max coordinates', 'crop an image tensor using a mask and bounding box with configurable fill values', 'review the expand_box function to understand bounding box expansion and clamping logic']
```

Usage

```
{'build_clip_model': 'build a CLIP model from a name string with optional frozen parameters for open vocabulary segmentation', 'expand_box': 'expand a bounding box by a ratio and clamp coordinates to image dimensions', 'mask2box': 'convert a binary mask tensor into a bounding box with min and max coordinates', 'crop_with_mask': 'crop an image tensor using a mask and bounding box with configurable fill values', 'review_expand_box': 'review the expand_box function to understand bounding box expansion and clamping logic'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/clipseg/test_modeling_clipseg.py

Prompts

```
['test the CLIPSegVisionModel class for image encoding with pixel values and configuration', 'test the CLIPSegTextModel class for text encoding with input ids and attention masks', 'test the CLIPSegModel class combining vision and text for cross-modal retrieval', 'test the CLIPSegForImageSegmentation class for generating image segmentation masks from text prompts', 'run CLIPSegForImageSegmentation inference on an image with text prompts to produce segmentation masks', 'test CLIPSegProcessor with text input and images to produce input_ids, attention_mask, and pixel_values', 'test CLIPSegProcessor with visual_prompt input to produce pixel_values and conditional_pixel_values', 'setup a CLIP tokenizer with a minimal vocab and merges file for CLIPSeg processor testing', 'setup a CLIPSeg image processor with resize, crop, and normalization parameters', 'test that CLIPSegProcessor raises ValueError when called with no input']
```

Usage

```
{'test_CLIPSegVisionModel': 'test the CLIPSegVisionModel class for image encoding with pixel values and configuration', 'test_CLIPSegTextModel': 'test the CLIPSegTextModel class for text encoding with input ids and attention masks', 'test_CLIPSegModel': 'test the CLIPSegModel class combining vision and text for cross-modal retrieval', 'test_CLIPSegForImageSegmentation': 'test the CLIPSegForImageSegmentation class for generating image segmentation masks from text prompts', 'run_CLIPSeg_inference': 'run CLIPSegForImageSegmentation inference on an image with text prompts to produce segmentation masks'}
```

## File: huggingface_transformers/tests/models/clipseg/test_processing_clipseg.py

Prompts

```
['test the CLIPSegVisionModel class for image encoding with pixel values and configuration', 'test the CLIPSegTextModel class for text encoding with input ids and attention masks', 'test the CLIPSegModel class combining vision and text for cross-modal retrieval', 'test the CLIPSegForImageSegmentation class for generating image segmentation masks from text prompts', 'run CLIPSegForImageSegmentation inference on an image with text prompts to produce segmentation masks', 'test CLIPSegProcessor with text input and images to produce input_ids, attention_mask, and pixel_values', 'test CLIPSegProcessor with visual_prompt input to produce pixel_values and conditional_pixel_values', 'setup a CLIP tokenizer with a minimal vocab and merges file for CLIPSeg processor testing', 'setup a CLIPSeg image processor with resize, crop, and normalization parameters', 'test that CLIPSegProcessor raises ValueError when called with no input']
```

Usage

```
{'test_processor_text': 'test CLIPSegProcessor with text input and images to produce input_ids, attention_mask, and pixel_values', 'test_processor_visual_prompt': 'test CLIPSegProcessor with visual_prompt input to produce pixel_values and conditional_pixel_values', 'setup_tokenizer': 'setup a CLIP tokenizer with a minimal vocab and merges file for CLIPSeg processor testing', 'setup_image_processor': 'setup a CLIPSeg image processor with resize, crop, and normalization parameters', 'test_processor_no_input': 'test that CLIPSegProcessor raises ValueError when called with no input'}
```


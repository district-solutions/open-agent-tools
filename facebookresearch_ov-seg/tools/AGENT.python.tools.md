# Agent Python Tools

- repo: facebookresearch/ov-seg
- repo_uri: https://github.com/facebookresearch/ov-seg

## File: facebookresearch_ov-seg/tools/convert-pretrained-clip-model-to-d2.py

Prompts

```
['run the script to convert a pretrained CLIP model pth file to a Detectron2 compatible pkl file', 'run the transform function to rename and prefix keys in a pretrained model state dict for Detectron2', 'convert a Swin Transformer pretrained checkpoint to a Detectron2 pickle format with backbone key prefixes', 'refactor the transform function to add or remove key renaming rules for model state dict conversion', 'review the transform function logic that filters visual_model keys and renames relative_coords, atten_mask_matrix, and channel_reduction', 'run the OVSeg Gradio web demo for open-vocabulary semantic segmentation', 'run open-vocabulary segmentation inference on an image with specified class names', 'setup and load the Detectron2 OVSeg configuration from a YAML config file', 'review the inference function that runs OVSeg on an image and returns a segmentation map', 'refactor the inference function to accept a configurable model config file path']
```

Usage

```
{'run_convert_pretrained_clip_to_d2': 'run the script to convert a pretrained CLIP model pth file to a Detectron2 compatible pkl file', 'run_transform_state_dict': 'run the transform function to rename and prefix keys in a pretrained model state dict for Detectron2', 'convert_swin_model_to_d2': 'convert a Swin Transformer pretrained checkpoint to a Detectron2 pickle format with backbone key prefixes', 'refactor_transform_key_renaming': 'refactor the transform function to add or remove key renaming rules for model state dict conversion', 'review_transform_visual_model_filter': 'review the transform function logic that filters visual_model keys and renames relative_coords, atten_mask_matrix, and channel_reduction'}
```

## File: facebookresearch_ov-seg/tools/web_demo.py

Prompts

```
['run the script to convert a pretrained CLIP model pth file to a Detectron2 compatible pkl file', 'run the transform function to rename and prefix keys in a pretrained model state dict for Detectron2', 'convert a Swin Transformer pretrained checkpoint to a Detectron2 pickle format with backbone key prefixes', 'refactor the transform function to add or remove key renaming rules for model state dict conversion', 'review the transform function logic that filters visual_model keys and renames relative_coords, atten_mask_matrix, and channel_reduction', 'run the OVSeg Gradio web demo for open-vocabulary semantic segmentation', 'run open-vocabulary segmentation inference on an image with specified class names', 'setup and load the Detectron2 OVSeg configuration from a YAML config file', 'review the inference function that runs OVSeg on an image and returns a segmentation map', 'refactor the inference function to accept a configurable model config file path']
```

Usage

```
{'run_gradio_demo': 'run the OVSeg Gradio web demo for open-vocabulary semantic segmentation', 'run_inference': 'run open-vocabulary segmentation inference on an image with specified class names', 'setup_cfg': 'setup and load the Detectron2 OVSeg configuration from a YAML config file', 'review_inference': 'review the inference function that runs OVSeg on an image and returns a segmentation map', 'refactor_inference': 'refactor the inference function to accept a configurable model config file path'}
```


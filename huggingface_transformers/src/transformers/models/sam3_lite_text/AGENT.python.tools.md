# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/sam3_lite_text/configuration_sam3_lite_text.py

Prompts

```
['create a Sam3LiteTextConfig instance with custom vision, text, and decoder sub-configs', 'build a Sam3LiteTextVisionConfig with custom backbone, FPN hidden size, and scale factors', 'create a Sam3LiteTextTextConfig with custom RepMixer blocks and layer scale values', 'configure a Sam3LiteTextMaskDecoderConfig with custom upsampling stages and attention heads', 'initialize a Sam3LiteTextGeometryEncoderConfig with custom ROI size and transformer layers', 'convert an EfficientSAM3 LiteText checkpoint to HuggingFace format and save to a directory', 'infer Sam3LiteTextTextConfig hyperparameters automatically from a raw checkpoint state dict', 'split combined QKV projections into separate Q, K, V projections in a state dict', 'convert original SAM3 LiteText checkpoint keys to HuggingFace format using regex patterns', 'run the CLI tool to download, convert, and optionally push a SAM3 LiteText model to the Hugging Face Hub', 'run SAM3 Lite Text model to segment an image given a text prompt and optional bounding box inputs', 'create pre-computed text embeddings from input_ids for reuse across multiple image inference calls', 'create pre-computed vision embeddings from pixel_values for reuse across multiple text prompt inference calls', 'encode geometric bounding box prompts with ROI-aligned vision features for spatial conditioning', 'build image segmentation output with predicted masks, boxes, logits, and semantic segmentation from model forward pass', 'build a Sam3LiteTextModel with Sam3LiteTextConfig for vision-language processing', 'create a Sam3LiteTextConfig with custom vision, text, DETR, and mask decoder settings', 'run a Sam3LiteTextTextModel forward pass on input_ids to get pooled output and hidden states', 'build a Sam3LiteTextVisionConfig with backbone and FPN multi-scale feature settings', 'review the Sam3LiteTextRepMixerBlock token mixer with depthwise conv and layer-scale residual']
```

Usage

```
{'create_Sam3LiteTextConfig': 'create a Sam3LiteTextConfig instance with custom vision, text, and decoder sub-configs', 'build_Sam3LiteTextVisionConfig': 'build a Sam3LiteTextVisionConfig with custom backbone, FPN hidden size, and scale factors', 'create_Sam3LiteTextTextConfig': 'create a Sam3LiteTextTextConfig with custom RepMixer blocks and layer scale values', 'configure_Sam3LiteTextMaskDecoderConfig': 'configure a Sam3LiteTextMaskDecoderConfig with custom upsampling stages and attention heads', 'initialize_Sam3LiteTextGeometryEncoderConfig': 'initialize a Sam3LiteTextGeometryEncoderConfig with custom ROI size and transformer layers'}
```

## File: huggingface_transformers/src/transformers/models/sam3_lite_text/convert_sam3_lite_text_to_hf.py

Prompts

```
['create a Sam3LiteTextConfig instance with custom vision, text, and decoder sub-configs', 'build a Sam3LiteTextVisionConfig with custom backbone, FPN hidden size, and scale factors', 'create a Sam3LiteTextTextConfig with custom RepMixer blocks and layer scale values', 'configure a Sam3LiteTextMaskDecoderConfig with custom upsampling stages and attention heads', 'initialize a Sam3LiteTextGeometryEncoderConfig with custom ROI size and transformer layers', 'convert an EfficientSAM3 LiteText checkpoint to HuggingFace format and save to a directory', 'infer Sam3LiteTextTextConfig hyperparameters automatically from a raw checkpoint state dict', 'split combined QKV projections into separate Q, K, V projections in a state dict', 'convert original SAM3 LiteText checkpoint keys to HuggingFace format using regex patterns', 'run the CLI tool to download, convert, and optionally push a SAM3 LiteText model to the Hugging Face Hub', 'run SAM3 Lite Text model to segment an image given a text prompt and optional bounding box inputs', 'create pre-computed text embeddings from input_ids for reuse across multiple image inference calls', 'create pre-computed vision embeddings from pixel_values for reuse across multiple text prompt inference calls', 'encode geometric bounding box prompts with ROI-aligned vision features for spatial conditioning', 'build image segmentation output with predicted masks, boxes, logits, and semantic segmentation from model forward pass', 'build a Sam3LiteTextModel with Sam3LiteTextConfig for vision-language processing', 'create a Sam3LiteTextConfig with custom vision, text, DETR, and mask decoder settings', 'run a Sam3LiteTextTextModel forward pass on input_ids to get pooled output and hidden states', 'build a Sam3LiteTextVisionConfig with backbone and FPN multi-scale feature settings', 'review the Sam3LiteTextRepMixerBlock token mixer with depthwise conv and layer-scale residual']
```

Usage

```
{'convert_checkpoint_to_hf_format': 'convert an EfficientSAM3 LiteText checkpoint to HuggingFace format and save to a directory', 'infer_text_config_from_checkpoint': 'infer Sam3LiteTextTextConfig hyperparameters automatically from a raw checkpoint state dict', 'split_qkv_projections': 'split combined QKV projections into separate Q, K, V projections in a state dict', 'convert_key_mapping': 'convert original SAM3 LiteText checkpoint keys to HuggingFace format using regex patterns', 'run_conversion_cli': 'run the CLI tool to download, convert, and optionally push a SAM3 LiteText model to the Hugging Face Hub'}
```

## File: huggingface_transformers/src/transformers/models/sam3_lite_text/modeling_sam3_lite_text.py

Prompts

```
['create a Sam3LiteTextConfig instance with custom vision, text, and decoder sub-configs', 'build a Sam3LiteTextVisionConfig with custom backbone, FPN hidden size, and scale factors', 'create a Sam3LiteTextTextConfig with custom RepMixer blocks and layer scale values', 'configure a Sam3LiteTextMaskDecoderConfig with custom upsampling stages and attention heads', 'initialize a Sam3LiteTextGeometryEncoderConfig with custom ROI size and transformer layers', 'convert an EfficientSAM3 LiteText checkpoint to HuggingFace format and save to a directory', 'infer Sam3LiteTextTextConfig hyperparameters automatically from a raw checkpoint state dict', 'split combined QKV projections into separate Q, K, V projections in a state dict', 'convert original SAM3 LiteText checkpoint keys to HuggingFace format using regex patterns', 'run the CLI tool to download, convert, and optionally push a SAM3 LiteText model to the Hugging Face Hub', 'run SAM3 Lite Text model to segment an image given a text prompt and optional bounding box inputs', 'create pre-computed text embeddings from input_ids for reuse across multiple image inference calls', 'create pre-computed vision embeddings from pixel_values for reuse across multiple text prompt inference calls', 'encode geometric bounding box prompts with ROI-aligned vision features for spatial conditioning', 'build image segmentation output with predicted masks, boxes, logits, and semantic segmentation from model forward pass', 'build a Sam3LiteTextModel with Sam3LiteTextConfig for vision-language processing', 'create a Sam3LiteTextConfig with custom vision, text, DETR, and mask decoder settings', 'run a Sam3LiteTextTextModel forward pass on input_ids to get pooled output and hidden states', 'build a Sam3LiteTextVisionConfig with backbone and FPN multi-scale feature settings', 'review the Sam3LiteTextRepMixerBlock token mixer with depthwise conv and layer-scale residual']
```

Usage

```
{'run_sam3_lite_text_segmentation': 'run SAM3 Lite Text model to segment an image given a text prompt and optional bounding box inputs', 'create_text_embeddings': 'create pre-computed text embeddings from input_ids for reuse across multiple image inference calls', 'create_vision_embeddings': 'create pre-computed vision embeddings from pixel_values for reuse across multiple text prompt inference calls', 'encode_geometry_prompts': 'encode geometric bounding box prompts with ROI-aligned vision features for spatial conditioning', 'build_image_segmentation_output': 'build image segmentation output with predicted masks, boxes, logits, and semantic segmentation from model forward pass'}
```

## File: huggingface_transformers/src/transformers/models/sam3_lite_text/modular_sam3_lite_text.py

Prompts

```
['create a Sam3LiteTextConfig instance with custom vision, text, and decoder sub-configs', 'build a Sam3LiteTextVisionConfig with custom backbone, FPN hidden size, and scale factors', 'create a Sam3LiteTextTextConfig with custom RepMixer blocks and layer scale values', 'configure a Sam3LiteTextMaskDecoderConfig with custom upsampling stages and attention heads', 'initialize a Sam3LiteTextGeometryEncoderConfig with custom ROI size and transformer layers', 'convert an EfficientSAM3 LiteText checkpoint to HuggingFace format and save to a directory', 'infer Sam3LiteTextTextConfig hyperparameters automatically from a raw checkpoint state dict', 'split combined QKV projections into separate Q, K, V projections in a state dict', 'convert original SAM3 LiteText checkpoint keys to HuggingFace format using regex patterns', 'run the CLI tool to download, convert, and optionally push a SAM3 LiteText model to the Hugging Face Hub', 'run SAM3 Lite Text model to segment an image given a text prompt and optional bounding box inputs', 'create pre-computed text embeddings from input_ids for reuse across multiple image inference calls', 'create pre-computed vision embeddings from pixel_values for reuse across multiple text prompt inference calls', 'encode geometric bounding box prompts with ROI-aligned vision features for spatial conditioning', 'build image segmentation output with predicted masks, boxes, logits, and semantic segmentation from model forward pass', 'build a Sam3LiteTextModel with Sam3LiteTextConfig for vision-language processing', 'create a Sam3LiteTextConfig with custom vision, text, DETR, and mask decoder settings', 'run a Sam3LiteTextTextModel forward pass on input_ids to get pooled output and hidden states', 'build a Sam3LiteTextVisionConfig with backbone and FPN multi-scale feature settings', 'review the Sam3LiteTextRepMixerBlock token mixer with depthwise conv and layer-scale residual']
```

Usage

```
{'build_sam3_lite_text_model': 'build a Sam3LiteTextModel with Sam3LiteTextConfig for vision-language processing', 'create_sam3_lite_text_config': 'create a Sam3LiteTextConfig with custom vision, text, DETR, and mask decoder settings', 'run_sam3_lite_text_text_model': 'run a Sam3LiteTextTextModel forward pass on input_ids to get pooled output and hidden states', 'build_sam3_lite_text_vision_config': 'build a Sam3LiteTextVisionConfig with backbone and FPN multi-scale feature settings', 'review_sam3_lite_text_repmixer_block': 'review the Sam3LiteTextRepMixerBlock token mixer with depthwise conv and layer-scale residual'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/clipseg/configuration_clipseg.py

Prompts

```
['create a CLIPSegTextConfig instance with custom transformer text encoder settings for CLIPSeg', 'create a CLIPSegVisionConfig instance with custom transformer vision encoder settings for CLIPSeg', 'create a CLIPSegConfig instance combining text and vision sub-configs for segmentation model initialization', 'build a CLIPSegConfig from separate CLIPSegTextConfig and CLIPSegVisionConfig instances', 'review the CLIPSegConfig __post_init__ method that merges text and vision config dicts with conflict logging', 'convert a CLIPSeg original PyTorch checkpoint to HuggingFace format for a given model', 'get a CLIPSeg config object for a model name with correct vision and text settings', 'rename state dict keys from the original CLIPSeg repository format to HuggingFace format', 'convert and split concatenated projection weights from original CLIPSeg state dict to HuggingFace format', 'run the CLIPSeg checkpoint conversion script from the command line with model name and checkpoint path', 'create a CLIPSegForImageSegmentation model to perform zero-shot image segmentation with text prompts', 'run CLIPSegModel to extract text embeddings from input token IDs and attention masks', 'run CLIPSegModel to extract image embeddings from pixel values for visual feature representation', 'build image-text contrastive loss using CLIPSeg similarity scores for training vision-language alignment', 'test CLIPSegDecoder to generate pixel-level segmentation logits from multi-scale vision activations and conditional embeddings', 'build a CLIPSegForImageSegmentation model for zero-shot image segmentation from text prompts', 'run CLIPSegForImageSegmentation forward pass to produce pixel-level segmentation logits from text and images', 'get conditional embeddings from text input_ids or conditional pixel values for segmentation conditioning', 'test the CLIPSegDecoder that applies FiLM modulation and transposed convolution to predict segmentation masks']
```

Usage

```
{'create_CLIPSegTextConfig': 'create a CLIPSegTextConfig instance with custom transformer text encoder settings for CLIPSeg', 'create_CLIPSegVisionConfig': 'create a CLIPSegVisionConfig instance with custom transformer vision encoder settings for CLIPSeg', 'create_CLIPSegConfig': 'create a CLIPSegConfig instance combining text and vision sub-configs for segmentation model initialization', 'build_CLIPSegConfig_from_subconfigs': 'build a CLIPSegConfig from separate CLIPSegTextConfig and CLIPSegVisionConfig instances', 'review_CLIPSegConfig_validate': 'review the CLIPSegConfig __post_init__ method that merges text and vision config dicts with conflict logging'}
```

## File: huggingface_transformers/src/transformers/models/clipseg/convert_clipseg_original_pytorch_to_hf.py

Prompts

```
['create a CLIPSegTextConfig instance with custom transformer text encoder settings for CLIPSeg', 'create a CLIPSegVisionConfig instance with custom transformer vision encoder settings for CLIPSeg', 'create a CLIPSegConfig instance combining text and vision sub-configs for segmentation model initialization', 'build a CLIPSegConfig from separate CLIPSegTextConfig and CLIPSegVisionConfig instances', 'review the CLIPSegConfig __post_init__ method that merges text and vision config dicts with conflict logging', 'convert a CLIPSeg original PyTorch checkpoint to HuggingFace format for a given model', 'get a CLIPSeg config object for a model name with correct vision and text settings', 'rename state dict keys from the original CLIPSeg repository format to HuggingFace format', 'convert and split concatenated projection weights from original CLIPSeg state dict to HuggingFace format', 'run the CLIPSeg checkpoint conversion script from the command line with model name and checkpoint path', 'create a CLIPSegForImageSegmentation model to perform zero-shot image segmentation with text prompts', 'run CLIPSegModel to extract text embeddings from input token IDs and attention masks', 'run CLIPSegModel to extract image embeddings from pixel values for visual feature representation', 'build image-text contrastive loss using CLIPSeg similarity scores for training vision-language alignment', 'test CLIPSegDecoder to generate pixel-level segmentation logits from multi-scale vision activations and conditional embeddings', 'build a CLIPSegForImageSegmentation model for zero-shot image segmentation from text prompts', 'run CLIPSegForImageSegmentation forward pass to produce pixel-level segmentation logits from text and images', 'get conditional embeddings from text input_ids or conditional pixel values for segmentation conditioning', 'test the CLIPSegDecoder that applies FiLM modulation and transposed convolution to predict segmentation masks']
```

Usage

```
{'convert_clipseg_checkpoint': 'convert a CLIPSeg original PyTorch checkpoint to HuggingFace format for a given model', 'get_clipseg_config': 'get a CLIPSeg config object for a model name with correct vision and text settings', 'rename_key': 'rename state dict keys from the original CLIPSeg repository format to HuggingFace format', 'convert_state_dict': 'convert and split concatenated projection weights from original CLIPSeg state dict to HuggingFace format', 'run_convert_clipseg_cli': 'run the CLIPSeg checkpoint conversion script from the command line with model name and checkpoint path'}
```

## File: huggingface_transformers/src/transformers/models/clipseg/modeling_clipseg.py

Prompts

```
['create a CLIPSegTextConfig instance with custom transformer text encoder settings for CLIPSeg', 'create a CLIPSegVisionConfig instance with custom transformer vision encoder settings for CLIPSeg', 'create a CLIPSegConfig instance combining text and vision sub-configs for segmentation model initialization', 'build a CLIPSegConfig from separate CLIPSegTextConfig and CLIPSegVisionConfig instances', 'review the CLIPSegConfig __post_init__ method that merges text and vision config dicts with conflict logging', 'convert a CLIPSeg original PyTorch checkpoint to HuggingFace format for a given model', 'get a CLIPSeg config object for a model name with correct vision and text settings', 'rename state dict keys from the original CLIPSeg repository format to HuggingFace format', 'convert and split concatenated projection weights from original CLIPSeg state dict to HuggingFace format', 'run the CLIPSeg checkpoint conversion script from the command line with model name and checkpoint path', 'create a CLIPSegForImageSegmentation model to perform zero-shot image segmentation with text prompts', 'run CLIPSegModel to extract text embeddings from input token IDs and attention masks', 'run CLIPSegModel to extract image embeddings from pixel values for visual feature representation', 'build image-text contrastive loss using CLIPSeg similarity scores for training vision-language alignment', 'test CLIPSegDecoder to generate pixel-level segmentation logits from multi-scale vision activations and conditional embeddings', 'build a CLIPSegForImageSegmentation model for zero-shot image segmentation from text prompts', 'run CLIPSegForImageSegmentation forward pass to produce pixel-level segmentation logits from text and images', 'get conditional embeddings from text input_ids or conditional pixel values for segmentation conditioning', 'test the CLIPSegDecoder that applies FiLM modulation and transposed convolution to predict segmentation masks']
```

Usage

```
{'create_clipseg_image_segmentation': 'create a CLIPSegForImageSegmentation model to perform zero-shot image segmentation with text prompts', 'run_clipseg_text_features': 'run CLIPSegModel to extract text embeddings from input token IDs and attention masks', 'run_clipseg_image_features': 'run CLIPSegModel to extract image embeddings from pixel values for visual feature representation', 'build_clipseg_contrastive_loss': 'build image-text contrastive loss using CLIPSeg similarity scores for training vision-language alignment', 'test_clipseg_decoder': 'test CLIPSegDecoder to generate pixel-level segmentation logits from multi-scale vision activations and conditional embeddings'}
```

## File: huggingface_transformers/src/transformers/models/clipseg/modular_clipseg.py

Prompts

```
['create a CLIPSegTextConfig instance with custom transformer text encoder settings for CLIPSeg', 'create a CLIPSegVisionConfig instance with custom transformer vision encoder settings for CLIPSeg', 'create a CLIPSegConfig instance combining text and vision sub-configs for segmentation model initialization', 'build a CLIPSegConfig from separate CLIPSegTextConfig and CLIPSegVisionConfig instances', 'review the CLIPSegConfig __post_init__ method that merges text and vision config dicts with conflict logging', 'convert a CLIPSeg original PyTorch checkpoint to HuggingFace format for a given model', 'get a CLIPSeg config object for a model name with correct vision and text settings', 'rename state dict keys from the original CLIPSeg repository format to HuggingFace format', 'convert and split concatenated projection weights from original CLIPSeg state dict to HuggingFace format', 'run the CLIPSeg checkpoint conversion script from the command line with model name and checkpoint path', 'create a CLIPSegForImageSegmentation model to perform zero-shot image segmentation with text prompts', 'run CLIPSegModel to extract text embeddings from input token IDs and attention masks', 'run CLIPSegModel to extract image embeddings from pixel values for visual feature representation', 'build image-text contrastive loss using CLIPSeg similarity scores for training vision-language alignment', 'test CLIPSegDecoder to generate pixel-level segmentation logits from multi-scale vision activations and conditional embeddings', 'build a CLIPSegForImageSegmentation model for zero-shot image segmentation from text prompts', 'run CLIPSegForImageSegmentation forward pass to produce pixel-level segmentation logits from text and images', 'get conditional embeddings from text input_ids or conditional pixel values for segmentation conditioning', 'test the CLIPSegDecoder that applies FiLM modulation and transposed convolution to predict segmentation masks']
```

Usage

```
{'create_CLIPSegConfig': 'create a CLIPSegConfig with extract_layers, reduce_dim, and decoder_num_attention_heads settings', 'build_CLIPSegForImageSegmentation': 'build a CLIPSegForImageSegmentation model for zero-shot image segmentation from text prompts', 'run_CLIPSegSegmentation': 'run CLIPSegForImageSegmentation forward pass to produce pixel-level segmentation logits from text and images', 'get_conditional_embeddings': 'get conditional embeddings from text input_ids or conditional pixel values for segmentation conditioning', 'test_CLIPSegDecoder': 'test the CLIPSegDecoder that applies FiLM modulation and transposed convolution to predict segmentation masks'}
```


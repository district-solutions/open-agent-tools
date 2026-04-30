# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/paligemma/convert_paligemma2_weights_to_hf.py

Prompts

```
['convert a PaliGemma2 Flax checkpoint to HuggingFace PyTorch format using variant and precision', 'build a PaliGemma2 config for a given variant string and precision level', 'slice and reshape a Flax state dict into HuggingFace PaliGemma2 PyTorch state dict format', 'flatten a nested Flax params dictionary into a flat key-value state dict', 'run the PaliGemma2 checkpoint conversion CLI with checkpoint path, variant, and precision arguments', 'convert a PaliGemma Flax checkpoint from .npz format to Hugging Face PyTorch weights', 'build a PaliGemmaConfig object for a specified variant and precision from available model variants', 'test the convert_paligemma_checkpoint function with a checkpoint path and output directory', 'run PaliGemmaForConditionalGeneration to generate text conditioned on image input using forward pass', 'create a PaliGemmaModel with vision tower and language model for multimodal feature extraction', "build image hidden states from pixel values using PaliGemmaModel's get_image_features method", 'test create_causal_mask_mapping for generating causal attention masks with token type ids', 'review PaliGemmaMultiModalProjector linear projection from vision to text hidden size', 'create a PaliGemmaProcessor instance with an image processor and tokenizer for multimodal image-text input', 'call PaliGemmaProcessor with images and text to produce input_ids, attention_mask, pixel_values, and labels for model training', 'build a string from input prompt by inserting image tokens and bos token for PaliGemma multimodal formatting', 'test PaliGemmaTextKwargs class for suffix and padding parameters used in finetuning text processing', 'summarize PaliGemmaProcessorKwargs defaults for text_kwargs padding and images_kwargs data_format settings']
```

Usage

```
{'convert_paligemma2_checkpoint': 'convert a PaliGemma2 Flax checkpoint to HuggingFace PyTorch format using variant and precision', 'build_paligemma2_config': 'build a PaliGemma2 config for a given variant string and precision level', 'slice_state_dict': 'slice and reshape a Flax state dict into HuggingFace PaliGemma2 PyTorch state dict format', 'flatten_nested_dict': 'flatten a nested Flax params dictionary into a flat key-value state dict', 'run_paligemma2_conversion_cli': 'run the PaliGemma2 checkpoint conversion CLI with checkpoint path, variant, and precision arguments'}
```

## File: huggingface_transformers/src/transformers/models/paligemma/convert_paligemma_weights_to_hf.py

Prompts

```
['convert a PaliGemma2 Flax checkpoint to HuggingFace PyTorch format using variant and precision', 'build a PaliGemma2 config for a given variant string and precision level', 'slice and reshape a Flax state dict into HuggingFace PaliGemma2 PyTorch state dict format', 'flatten a nested Flax params dictionary into a flat key-value state dict', 'run the PaliGemma2 checkpoint conversion CLI with checkpoint path, variant, and precision arguments', 'convert a PaliGemma Flax checkpoint from .npz format to Hugging Face PyTorch weights', 'build a PaliGemmaConfig object for a specified variant and precision from available model variants', 'test the convert_paligemma_checkpoint function with a checkpoint path and output directory', 'run PaliGemmaForConditionalGeneration to generate text conditioned on image input using forward pass', 'create a PaliGemmaModel with vision tower and language model for multimodal feature extraction', "build image hidden states from pixel values using PaliGemmaModel's get_image_features method", 'test create_causal_mask_mapping for generating causal attention masks with token type ids', 'review PaliGemmaMultiModalProjector linear projection from vision to text hidden size', 'create a PaliGemmaProcessor instance with an image processor and tokenizer for multimodal image-text input', 'call PaliGemmaProcessor with images and text to produce input_ids, attention_mask, pixel_values, and labels for model training', 'build a string from input prompt by inserting image tokens and bos token for PaliGemma multimodal formatting', 'test PaliGemmaTextKwargs class for suffix and padding parameters used in finetuning text processing', 'summarize PaliGemmaProcessorKwargs defaults for text_kwargs padding and images_kwargs data_format settings']
```

Usage

```
{'convert_paligemma_checkpoint': 'convert a PaliGemma Flax checkpoint from .npz format to Hugging Face PyTorch weights', 'build_paligemma_config': 'build a PaliGemmaConfig object for a specified variant and precision from available model variants', 'slice_state_dict': 'slice and reshape a Flax state dict into Hugging Face PaliGemma PyTorch state dict format', 'flatten_nested_dict': 'flatten a nested dictionary with slash-separated keys into a flat dictionary', 'test_convert_paligemma_checkpoint': 'test the convert_paligemma_checkpoint function with a checkpoint path and output directory'}
```

## File: huggingface_transformers/src/transformers/models/paligemma/modeling_paligemma.py

Prompts

```
['convert a PaliGemma2 Flax checkpoint to HuggingFace PyTorch format using variant and precision', 'build a PaliGemma2 config for a given variant string and precision level', 'slice and reshape a Flax state dict into HuggingFace PaliGemma2 PyTorch state dict format', 'flatten a nested Flax params dictionary into a flat key-value state dict', 'run the PaliGemma2 checkpoint conversion CLI with checkpoint path, variant, and precision arguments', 'convert a PaliGemma Flax checkpoint from .npz format to Hugging Face PyTorch weights', 'build a PaliGemmaConfig object for a specified variant and precision from available model variants', 'test the convert_paligemma_checkpoint function with a checkpoint path and output directory', 'run PaliGemmaForConditionalGeneration to generate text conditioned on image input using forward pass', 'create a PaliGemmaModel with vision tower and language model for multimodal feature extraction', "build image hidden states from pixel values using PaliGemmaModel's get_image_features method", 'test create_causal_mask_mapping for generating causal attention masks with token type ids', 'review PaliGemmaMultiModalProjector linear projection from vision to text hidden size', 'create a PaliGemmaProcessor instance with an image processor and tokenizer for multimodal image-text input', 'call PaliGemmaProcessor with images and text to produce input_ids, attention_mask, pixel_values, and labels for model training', 'build a string from input prompt by inserting image tokens and bos token for PaliGemma multimodal formatting', 'test PaliGemmaTextKwargs class for suffix and padding parameters used in finetuning text processing', 'summarize PaliGemmaProcessorKwargs defaults for text_kwargs padding and images_kwargs data_format settings']
```

Usage

```
{'run_paligemma_for_conditional_generation': 'run PaliGemmaForConditionalGeneration to generate text conditioned on image input using forward pass', 'create_paligemma_model': 'create a PaliGemmaModel with vision tower and language model for multimodal feature extraction', 'build_paligemma_image_features': "build image hidden states from pixel values using PaliGemmaModel's get_image_features method", 'test_paligemma_causal_mask': 'test create_causal_mask_mapping for generating causal attention masks with token type ids', 'review_paligemma_projector': 'review PaliGemmaMultiModalProjector linear projection from vision to text hidden size'}
```

## File: huggingface_transformers/src/transformers/models/paligemma/processing_paligemma.py

Prompts

```
['convert a PaliGemma2 Flax checkpoint to HuggingFace PyTorch format using variant and precision', 'build a PaliGemma2 config for a given variant string and precision level', 'slice and reshape a Flax state dict into HuggingFace PaliGemma2 PyTorch state dict format', 'flatten a nested Flax params dictionary into a flat key-value state dict', 'run the PaliGemma2 checkpoint conversion CLI with checkpoint path, variant, and precision arguments', 'convert a PaliGemma Flax checkpoint from .npz format to Hugging Face PyTorch weights', 'build a PaliGemmaConfig object for a specified variant and precision from available model variants', 'test the convert_paligemma_checkpoint function with a checkpoint path and output directory', 'run PaliGemmaForConditionalGeneration to generate text conditioned on image input using forward pass', 'create a PaliGemmaModel with vision tower and language model for multimodal feature extraction', "build image hidden states from pixel values using PaliGemmaModel's get_image_features method", 'test create_causal_mask_mapping for generating causal attention masks with token type ids', 'review PaliGemmaMultiModalProjector linear projection from vision to text hidden size', 'create a PaliGemmaProcessor instance with an image processor and tokenizer for multimodal image-text input', 'call PaliGemmaProcessor with images and text to produce input_ids, attention_mask, pixel_values, and labels for model training', 'build a string from input prompt by inserting image tokens and bos token for PaliGemma multimodal formatting', 'test PaliGemmaTextKwargs class for suffix and padding parameters used in finetuning text processing', 'summarize PaliGemmaProcessorKwargs defaults for text_kwargs padding and images_kwargs data_format settings']
```

Usage

```
{'create_PaliGemmaProcessor': 'create a PaliGemmaProcessor instance with an image processor and tokenizer for multimodal image-text input', 'call_PaliGemmaProcessor': 'call PaliGemmaProcessor with images and text to produce input_ids, attention_mask, pixel_values, and labels for model training', 'build_string_from_input': 'build a string from input prompt by inserting image tokens and bos token for PaliGemma multimodal formatting', 'test_PaliGemmaTextKwargs': 'test PaliGemmaTextKwargs class for suffix and padding parameters used in finetuning text processing', 'summarize_PaliGemmaProcessorKwargs': 'summarize PaliGemmaProcessorKwargs defaults for text_kwargs padding and images_kwargs data_format settings'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vilt/convert_vilt_original_to_pytorch.py

Prompts

```
['convert a ViLT checkpoint from the original GitHub repository to a HuggingFace PyTorch model', 'create key rename mappings between original ViLT and HuggingFace model architectures', 'split combined query-key-value projection weights into separate attention layers', 'remove classification head weights from a model state dictionary', 'run the ViLT checkpoint conversion CLI with a checkpoint URL and output directory path', 'create a ViltImageProcessorPil instance to resize, rescale, and normalize images for ViLT model input', 'build the output image size for resizing based on shorter/longer edge constraints and size divisor alignment', 'create a pixel mask array marking valid pixels as 1 and padding regions as 0 for padded image batches', 'test padding a batch of images to uniform dimensions with corresponding pixel masks for variable-size inputs', 'summarize the preprocessing pipeline that resizes, rescales, normalizes, and pads image batches for ViLT', 'build a ViltImageProcessor instance to preprocess images for the VILT vision-language model', 'resize a batch of images to a specified shortest edge while preserving aspect ratio and applying a size divisor', 'pad a batch of differently-sized images to the maximum dimensions and generate corresponding pixel masks', 'preprocess a batch of images by resizing, rescaling, normalizing, and optionally padding for model input', 'test the ViltImageProcessorKwargs configuration class for optional size_divisor parameter validation', 'create a ViLT model with a masked language modeling head for image-text pretraining', 'build a ViLT model with a classifier head for visual question answering tasks like VQAv2', 'run a ViLT model for image-to-text or text-to-image retrieval on datasets like MSCOCO and F30K', 'test a ViLT model with a classifier head for natural language visual reasoning on NLVR2', 'review a ViLT model for token classification that outputs per-token logits for text sequences']
```

Usage

```
{'convert_vilt_checkpoint': 'convert a ViLT checkpoint from the original GitHub repository to a HuggingFace PyTorch model', 'create_rename_keys': 'create key rename mappings between original ViLT and HuggingFace model architectures', 'read_in_q_k_v': 'split combined query-key-value projection weights into separate attention layers', 'remove_classification_head_': 'remove classification head weights from a model state dictionary', 'run_convert_cli': 'run the ViLT checkpoint conversion CLI with a checkpoint URL and output directory path'}
```

## File: huggingface_transformers/src/transformers/models/vilt/image_processing_pil_vilt.py

Prompts

```
['convert a ViLT checkpoint from the original GitHub repository to a HuggingFace PyTorch model', 'create key rename mappings between original ViLT and HuggingFace model architectures', 'split combined query-key-value projection weights into separate attention layers', 'remove classification head weights from a model state dictionary', 'run the ViLT checkpoint conversion CLI with a checkpoint URL and output directory path', 'create a ViltImageProcessorPil instance to resize, rescale, and normalize images for ViLT model input', 'build the output image size for resizing based on shorter/longer edge constraints and size divisor alignment', 'create a pixel mask array marking valid pixels as 1 and padding regions as 0 for padded image batches', 'test padding a batch of images to uniform dimensions with corresponding pixel masks for variable-size inputs', 'summarize the preprocessing pipeline that resizes, rescales, normalizes, and pads image batches for ViLT', 'build a ViltImageProcessor instance to preprocess images for the VILT vision-language model', 'resize a batch of images to a specified shortest edge while preserving aspect ratio and applying a size divisor', 'pad a batch of differently-sized images to the maximum dimensions and generate corresponding pixel masks', 'preprocess a batch of images by resizing, rescaling, normalizing, and optionally padding for model input', 'test the ViltImageProcessorKwargs configuration class for optional size_divisor parameter validation', 'create a ViLT model with a masked language modeling head for image-text pretraining', 'build a ViLT model with a classifier head for visual question answering tasks like VQAv2', 'run a ViLT model for image-to-text or text-to-image retrieval on datasets like MSCOCO and F30K', 'test a ViLT model with a classifier head for natural language visual reasoning on NLVR2', 'review a ViLT model for token classification that outputs per-token logits for text sequences']
```

Usage

```
{'create_ViltImageProcessorPil': 'create a ViltImageProcessorPil instance to resize, rescale, and normalize images for ViLT model input', 'build_resize_output_image_size': 'build the output image size for resizing based on shorter/longer edge constraints and size divisor alignment', 'create_make_pixel_mask': 'create a pixel mask array marking valid pixels as 1 and padding regions as 0 for padded image batches', 'test_pad_batch': 'test padding a batch of images to uniform dimensions with corresponding pixel masks for variable-size inputs', 'summarize_preprocess': 'summarize the preprocessing pipeline that resizes, rescales, normalizes, and pads image batches for ViLT'}
```

## File: huggingface_transformers/src/transformers/models/vilt/image_processing_vilt.py

Prompts

```
['convert a ViLT checkpoint from the original GitHub repository to a HuggingFace PyTorch model', 'create key rename mappings between original ViLT and HuggingFace model architectures', 'split combined query-key-value projection weights into separate attention layers', 'remove classification head weights from a model state dictionary', 'run the ViLT checkpoint conversion CLI with a checkpoint URL and output directory path', 'create a ViltImageProcessorPil instance to resize, rescale, and normalize images for ViLT model input', 'build the output image size for resizing based on shorter/longer edge constraints and size divisor alignment', 'create a pixel mask array marking valid pixels as 1 and padding regions as 0 for padded image batches', 'test padding a batch of images to uniform dimensions with corresponding pixel masks for variable-size inputs', 'summarize the preprocessing pipeline that resizes, rescales, normalizes, and pads image batches for ViLT', 'build a ViltImageProcessor instance to preprocess images for the VILT vision-language model', 'resize a batch of images to a specified shortest edge while preserving aspect ratio and applying a size divisor', 'pad a batch of differently-sized images to the maximum dimensions and generate corresponding pixel masks', 'preprocess a batch of images by resizing, rescaling, normalizing, and optionally padding for model input', 'test the ViltImageProcessorKwargs configuration class for optional size_divisor parameter validation', 'create a ViLT model with a masked language modeling head for image-text pretraining', 'build a ViLT model with a classifier head for visual question answering tasks like VQAv2', 'run a ViLT model for image-to-text or text-to-image retrieval on datasets like MSCOCO and F30K', 'test a ViLT model with a classifier head for natural language visual reasoning on NLVR2', 'review a ViLT model for token classification that outputs per-token logits for text sequences']
```

Usage

```
{'build_vilt_image_processor': 'build a ViltImageProcessor instance to preprocess images for the VILT vision-language model', 'resize_vilt_images': 'resize a batch of images to a specified shortest edge while preserving aspect ratio and applying a size divisor', 'pad_vilt_image_batch': 'pad a batch of differently-sized images to the maximum dimensions and generate corresponding pixel masks', 'preprocess_vilt_images': 'preprocess a batch of images by resizing, rescaling, normalizing, and optionally padding for model input', 'test_vilt_image_processor_kwargs': 'test the ViltImageProcessorKwargs configuration class for optional size_divisor parameter validation'}
```

## File: huggingface_transformers/src/transformers/models/vilt/modeling_vilt.py

Prompts

```
['convert a ViLT checkpoint from the original GitHub repository to a HuggingFace PyTorch model', 'create key rename mappings between original ViLT and HuggingFace model architectures', 'split combined query-key-value projection weights into separate attention layers', 'remove classification head weights from a model state dictionary', 'run the ViLT checkpoint conversion CLI with a checkpoint URL and output directory path', 'create a ViltImageProcessorPil instance to resize, rescale, and normalize images for ViLT model input', 'build the output image size for resizing based on shorter/longer edge constraints and size divisor alignment', 'create a pixel mask array marking valid pixels as 1 and padding regions as 0 for padded image batches', 'test padding a batch of images to uniform dimensions with corresponding pixel masks for variable-size inputs', 'summarize the preprocessing pipeline that resizes, rescales, normalizes, and pads image batches for ViLT', 'build a ViltImageProcessor instance to preprocess images for the VILT vision-language model', 'resize a batch of images to a specified shortest edge while preserving aspect ratio and applying a size divisor', 'pad a batch of differently-sized images to the maximum dimensions and generate corresponding pixel masks', 'preprocess a batch of images by resizing, rescaling, normalizing, and optionally padding for model input', 'test the ViltImageProcessorKwargs configuration class for optional size_divisor parameter validation', 'create a ViLT model with a masked language modeling head for image-text pretraining', 'build a ViLT model with a classifier head for visual question answering tasks like VQAv2', 'run a ViLT model for image-to-text or text-to-image retrieval on datasets like MSCOCO and F30K', 'test a ViLT model with a classifier head for natural language visual reasoning on NLVR2', 'review a ViLT model for token classification that outputs per-token logits for text sequences']
```

Usage

```
{'create_model_vilt_for_masked_lm': 'create a ViLT model with a masked language modeling head for image-text pretraining', 'build_model_vilt_for_question_answering': 'build a ViLT model with a classifier head for visual question answering tasks like VQAv2', 'run_model_vilt_for_image_and_text_retrieval': 'run a ViLT model for image-to-text or text-to-image retrieval on datasets like MSCOCO and F30K', 'test_model_vilt_for_images_and_text_classification': 'test a ViLT model with a classifier head for natural language visual reasoning on NLVR2', 'review_model_vilt_for_token_classification': 'review a ViLT model for token classification that outputs per-token logits for text sequences'}
```


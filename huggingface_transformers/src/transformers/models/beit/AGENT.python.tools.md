# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/beit/convert_beit_unilm_to_pytorch.py

Prompts

```
['convert a BEiT checkpoint from the unilm repository to a HuggingFace PyTorch model', 'create a mapping of weight keys to rename from the original unilm checkpoint to HuggingFace BEiT format', 'split concatenated query-key-value weight matrices into separate attention weights for each encoder layer', 'run the BEiT checkpoint conversion CLI with a checkpoint URL and output folder path', 'review the convert_beit_checkpoint function that transforms unilm BEiT checkpoints to HuggingFace models', 'create a BeitImageProcessor instance to preprocess images and segmentation maps for BEiT models', 'run the preprocess method on a BeitImageProcessor to resize, rescale, and normalize input images into pixel values', 'run the preprocess method on a BeitImageProcessor with segmentation maps to produce labels for semantic segmentation', 'run the reduce_label method on a BeitImageProcessor to reduce segmentation label values by 1 replacing 0 with 255', 'run post_process_semantic_segmentation on a BeitImageProcessor to convert model logits into semantic segmentation maps', 'preprocess images and optional segmentation maps for BEiT with resize, rescale, and normalize operations', 'reduce label values in segmentation maps by 1, replacing 0 with 255 for background handling', 'post-process BEiT model logits into semantic segmentation maps resized to target image dimensions', 'build a BEiT image processing pipeline that handles pixel values and segmentation label conversion', 'create a BEiT base model with embeddings, encoder, and pooling for image feature extraction', 'build a BEiT model with an image classification head for ImageNet-style classification', 'run BEiT masked image modeling to predict visual tokens from masked patches', 'build a BEiT model with UPerNet head for pixel-level semantic segmentation', 'create a BEiT backbone with optional FPN feature pyramid for DETR and MaskFormer']
```

Usage

```
{'convert_beit_checkpoint': 'convert a BEiT checkpoint from the unilm repository to a HuggingFace PyTorch model', 'create_rename_keys': 'create a mapping of weight keys to rename from the original unilm checkpoint to HuggingFace BEiT format', 'read_in_q_k_v': 'split concatenated query-key-value weight matrices into separate attention weights for each encoder layer', 'run_convert_cli': 'run the BEiT checkpoint conversion CLI with a checkpoint URL and output folder path', 'review_convert_beit_checkpoint': 'review the convert_beit_checkpoint function that transforms unilm BEiT checkpoints to HuggingFace models'}
```

## File: huggingface_transformers/src/transformers/models/beit/image_processing_beit.py

Prompts

```
['convert a BEiT checkpoint from the unilm repository to a HuggingFace PyTorch model', 'create a mapping of weight keys to rename from the original unilm checkpoint to HuggingFace BEiT format', 'split concatenated query-key-value weight matrices into separate attention weights for each encoder layer', 'run the BEiT checkpoint conversion CLI with a checkpoint URL and output folder path', 'review the convert_beit_checkpoint function that transforms unilm BEiT checkpoints to HuggingFace models', 'create a BeitImageProcessor instance to preprocess images and segmentation maps for BEiT models', 'run the preprocess method on a BeitImageProcessor to resize, rescale, and normalize input images into pixel values', 'run the preprocess method on a BeitImageProcessor with segmentation maps to produce labels for semantic segmentation', 'run the reduce_label method on a BeitImageProcessor to reduce segmentation label values by 1 replacing 0 with 255', 'run post_process_semantic_segmentation on a BeitImageProcessor to convert model logits into semantic segmentation maps', 'preprocess images and optional segmentation maps for BEiT with resize, rescale, and normalize operations', 'reduce label values in segmentation maps by 1, replacing 0 with 255 for background handling', 'post-process BEiT model logits into semantic segmentation maps resized to target image dimensions', 'build a BEiT image processing pipeline that handles pixel values and segmentation label conversion', 'create a BEiT base model with embeddings, encoder, and pooling for image feature extraction', 'build a BEiT model with an image classification head for ImageNet-style classification', 'run BEiT masked image modeling to predict visual tokens from masked patches', 'build a BEiT model with UPerNet head for pixel-level semantic segmentation', 'create a BEiT backbone with optional FPN feature pyramid for DETR and MaskFormer']
```

Usage

```
{'create_beit_image_processor': 'create a BeitImageProcessor instance to preprocess images and segmentation maps for BEiT models', 'run_preprocess_images': 'run the preprocess method on a BeitImageProcessor to resize, rescale, and normalize input images into pixel values', 'run_preprocess_segmentation_maps': 'run the preprocess method on a BeitImageProcessor with segmentation maps to produce labels for semantic segmentation', 'run_reduce_label': 'run the reduce_label method on a BeitImageProcessor to reduce segmentation label values by 1 replacing 0 with 255', 'run_post_process_semantic_segmentation': 'run post_process_semantic_segmentation on a BeitImageProcessor to convert model logits into semantic segmentation maps'}
```

## File: huggingface_transformers/src/transformers/models/beit/image_processing_pil_beit.py

Prompts

```
['convert a BEiT checkpoint from the unilm repository to a HuggingFace PyTorch model', 'create a mapping of weight keys to rename from the original unilm checkpoint to HuggingFace BEiT format', 'split concatenated query-key-value weight matrices into separate attention weights for each encoder layer', 'run the BEiT checkpoint conversion CLI with a checkpoint URL and output folder path', 'review the convert_beit_checkpoint function that transforms unilm BEiT checkpoints to HuggingFace models', 'create a BeitImageProcessor instance to preprocess images and segmentation maps for BEiT models', 'run the preprocess method on a BeitImageProcessor to resize, rescale, and normalize input images into pixel values', 'run the preprocess method on a BeitImageProcessor with segmentation maps to produce labels for semantic segmentation', 'run the reduce_label method on a BeitImageProcessor to reduce segmentation label values by 1 replacing 0 with 255', 'run post_process_semantic_segmentation on a BeitImageProcessor to convert model logits into semantic segmentation maps', 'preprocess images and optional segmentation maps for BEiT with resize, rescale, and normalize operations', 'reduce label values in segmentation maps by 1, replacing 0 with 255 for background handling', 'post-process BEiT model logits into semantic segmentation maps resized to target image dimensions', 'build a BEiT image processing pipeline that handles pixel values and segmentation label conversion', 'create a BEiT base model with embeddings, encoder, and pooling for image feature extraction', 'build a BEiT model with an image classification head for ImageNet-style classification', 'run BEiT masked image modeling to predict visual tokens from masked patches', 'build a BEiT model with UPerNet head for pixel-level semantic segmentation', 'create a BEiT backbone with optional FPN feature pyramid for DETR and MaskFormer']
```

Usage

```
{'create_beit_image_processor': 'create a BeitImageProcessorPil instance to preprocess images for the BEiT model with configurable segmentation map support', 'preprocess_beit_images': 'preprocess images and optional segmentation maps for BEiT with resize, rescale, and normalize operations', 'reduce_beit_labels': 'reduce label values in segmentation maps by 1, replacing 0 with 255 for background handling', 'post_process_semantic_segmentation': 'post-process BEiT model logits into semantic segmentation maps resized to target image dimensions', 'build_beit_image_pipeline': 'build a BEiT image processing pipeline that handles pixel values and segmentation label conversion'}
```

## File: huggingface_transformers/src/transformers/models/beit/modeling_beit.py

Prompts

```
['convert a BEiT checkpoint from the unilm repository to a HuggingFace PyTorch model', 'create a mapping of weight keys to rename from the original unilm checkpoint to HuggingFace BEiT format', 'split concatenated query-key-value weight matrices into separate attention weights for each encoder layer', 'run the BEiT checkpoint conversion CLI with a checkpoint URL and output folder path', 'review the convert_beit_checkpoint function that transforms unilm BEiT checkpoints to HuggingFace models', 'create a BeitImageProcessor instance to preprocess images and segmentation maps for BEiT models', 'run the preprocess method on a BeitImageProcessor to resize, rescale, and normalize input images into pixel values', 'run the preprocess method on a BeitImageProcessor with segmentation maps to produce labels for semantic segmentation', 'run the reduce_label method on a BeitImageProcessor to reduce segmentation label values by 1 replacing 0 with 255', 'run post_process_semantic_segmentation on a BeitImageProcessor to convert model logits into semantic segmentation maps', 'preprocess images and optional segmentation maps for BEiT with resize, rescale, and normalize operations', 'reduce label values in segmentation maps by 1, replacing 0 with 255 for background handling', 'post-process BEiT model logits into semantic segmentation maps resized to target image dimensions', 'build a BEiT image processing pipeline that handles pixel values and segmentation label conversion', 'create a BEiT base model with embeddings, encoder, and pooling for image feature extraction', 'build a BEiT model with an image classification head for ImageNet-style classification', 'run BEiT masked image modeling to predict visual tokens from masked patches', 'build a BEiT model with UPerNet head for pixel-level semantic segmentation', 'create a BEiT backbone with optional FPN feature pyramid for DETR and MaskFormer']
```

Usage

```
{'create_beit_model': 'create a BEiT base model with embeddings, encoder, and pooling for image feature extraction', 'build_beit_image_classifier': 'build a BEiT model with an image classification head for ImageNet-style classification', 'run_beit_masked_image_modeling': 'run BEiT masked image modeling to predict visual tokens from masked patches', 'build_beit_semantic_segmentation': 'build a BEiT model with UPerNet head for pixel-level semantic segmentation', 'create_beit_backbone': 'create a BEiT backbone with optional FPN feature pyramid for DETR and MaskFormer'}
```


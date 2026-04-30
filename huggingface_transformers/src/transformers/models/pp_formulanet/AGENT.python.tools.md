# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pp_formulanet/image_processing_pp_formulanet.py

Prompts

```
['preprocess images for PPFormulaNet model using the PPFormulaNetImageProcessor with crop, resize, and normalize steps', 'crop the margin of an image by removing gray pixels below a configurable threshold value', 'align the long axis of an image to match the longest axis of the specified output size', 'resize an image to create a thumbnail where no dimension exceeds the specified output size', 'pad a batch of images to a specified size at the top, bottom, left, and right edges', 'build a PPFormulaNetForConditionalGeneration model to recognize mathematical formulas from images using pixel values', 'create a PPFormulaNetVisionModel encoder that processes images through patch embeddings and vision transformer layers', 'run PPFormulaNetTextModel decoder to generate text sequences using cross-attention with encoder visual features', 'build a PPFormulaNetModel combining vision encoder and text decoder for image-to-formula sequence-to-sequence generation', 'test PPFormulaNetVisionAttention with relative positional embeddings and window partitioning for efficient visual attention']
```

Usage

```
{'preprocess_images': 'preprocess images for PPFormulaNet model using the PPFormulaNetImageProcessor with crop, resize, and normalize steps', 'crop_margin': 'crop the margin of an image by removing gray pixels below a configurable threshold value', 'align_long_axis': 'align the long axis of an image to match the longest axis of the specified output size', 'thumbnail_resize': 'resize an image to create a thumbnail where no dimension exceeds the specified output size', 'pad_images': 'pad a batch of images to a specified size at the top, bottom, left, and right edges'}
```

## File: huggingface_transformers/src/transformers/models/pp_formulanet/modeling_pp_formulanet.py

Prompts

```
['preprocess images for PPFormulaNet model using the PPFormulaNetImageProcessor with crop, resize, and normalize steps', 'crop the margin of an image by removing gray pixels below a configurable threshold value', 'align the long axis of an image to match the longest axis of the specified output size', 'resize an image to create a thumbnail where no dimension exceeds the specified output size', 'pad a batch of images to a specified size at the top, bottom, left, and right edges', 'build a PPFormulaNetForConditionalGeneration model to recognize mathematical formulas from images using pixel values', 'create a PPFormulaNetVisionModel encoder that processes images through patch embeddings and vision transformer layers', 'run PPFormulaNetTextModel decoder to generate text sequences using cross-attention with encoder visual features', 'build a PPFormulaNetModel combining vision encoder and text decoder for image-to-formula sequence-to-sequence generation', 'test PPFormulaNetVisionAttention with relative positional embeddings and window partitioning for efficient visual attention']
```

Usage

```
{'build_formula_recognition_model': 'build a PPFormulaNetForConditionalGeneration model to recognize mathematical formulas from images using pixel values', 'create_vision_encoder': 'create a PPFormulaNetVisionModel encoder that processes images through patch embeddings and vision transformer layers', 'run_decoder_generation': 'run PPFormulaNetTextModel decoder to generate text sequences using cross-attention with encoder visual features', 'build_seq2seq_model': 'build a PPFormulaNetModel combining vision encoder and text decoder for image-to-formula sequence-to-sequence generation', 'test_attention_mechanism': 'test PPFormulaNetVisionAttention with relative positional embeddings and window partitioning for efficient visual attention'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pp_formulanet/image_processing_pp_formulanet.py

Prompts

```
['preprocess images for PPFormulaNet model using the PPFormulaNetImageProcessor with crop, resize, and normalize steps', 'crop the margin of an image by removing gray pixels below a configurable threshold value', 'align the long axis of an image to match the longest axis of the specified output size', 'resize an image to create a thumbnail where no dimension exceeds the specified output size', 'pad a batch of images to a specified size at the top, bottom, left, and right edges', 'build a PPFormulaNetForConditionalGeneration model to recognize mathematical formulas from images using pixel values', 'create a PPFormulaNetVisionModel encoder that processes images through patch embeddings and vision transformer layers', 'run PPFormulaNetTextModel decoder to generate text sequences using cross-attention with encoder visual features', 'build a PPFormulaNetModel combining vision encoder and text decoder for image-to-formula sequence-to-sequence generation', 'test PPFormulaNetVisionAttention with relative positional embeddings and window partitioning for efficient visual attention', 'create a PPFormulaNetProcessor to preprocess images for formula recognition', 'run PPFormulaNetForConditionalGeneration forward pass with pixel values to generate formula logits', 'review the PPFormulaNetVisionModel encoder that extracts features from input images', 'test PPFormulaNetConfig initialization with custom vision and text sub-configs', 'create a PPFormulaNetProcessor instance with an image processor and tokenizer for formula image processing', 'call the PPFormulaNetProcessor with images to get pixel values as a BatchFeature for model input', 'post process generated formula text by removing Chinese wrapping, fixing unicode, and normalizing spaces', 'normalize LaTeX formula text by removing unnecessary spaces between non-letter and letter characters', 'post process model generation outputs by decoding tokens and applying text normalization to each generated formula']
```

Usage

```
{'preprocess_images': 'preprocess images for PPFormulaNet model using the PPFormulaNetImageProcessor with crop, resize, and normalize steps', 'crop_margin': 'crop the margin of an image by removing gray pixels below a configurable threshold value', 'align_long_axis': 'align the long axis of an image to match the longest axis of the specified output size', 'thumbnail_resize': 'resize an image to create a thumbnail where no dimension exceeds the specified output size', 'pad_images': 'pad a batch of images to a specified size at the top, bottom, left, and right edges'}
```

## File: huggingface_transformers/src/transformers/models/pp_formulanet/modeling_pp_formulanet.py

Prompts

```
['preprocess images for PPFormulaNet model using the PPFormulaNetImageProcessor with crop, resize, and normalize steps', 'crop the margin of an image by removing gray pixels below a configurable threshold value', 'align the long axis of an image to match the longest axis of the specified output size', 'resize an image to create a thumbnail where no dimension exceeds the specified output size', 'pad a batch of images to a specified size at the top, bottom, left, and right edges', 'build a PPFormulaNetForConditionalGeneration model to recognize mathematical formulas from images using pixel values', 'create a PPFormulaNetVisionModel encoder that processes images through patch embeddings and vision transformer layers', 'run PPFormulaNetTextModel decoder to generate text sequences using cross-attention with encoder visual features', 'build a PPFormulaNetModel combining vision encoder and text decoder for image-to-formula sequence-to-sequence generation', 'test PPFormulaNetVisionAttention with relative positional embeddings and window partitioning for efficient visual attention', 'create a PPFormulaNetProcessor to preprocess images for formula recognition', 'run PPFormulaNetForConditionalGeneration forward pass with pixel values to generate formula logits', 'review the PPFormulaNetVisionModel encoder that extracts features from input images', 'test PPFormulaNetConfig initialization with custom vision and text sub-configs', 'create a PPFormulaNetProcessor instance with an image processor and tokenizer for formula image processing', 'call the PPFormulaNetProcessor with images to get pixel values as a BatchFeature for model input', 'post process generated formula text by removing Chinese wrapping, fixing unicode, and normalizing spaces', 'normalize LaTeX formula text by removing unnecessary spaces between non-letter and letter characters', 'post process model generation outputs by decoding tokens and applying text normalization to each generated formula']
```

Usage

```
{'build_formula_recognition_model': 'build a PPFormulaNetForConditionalGeneration model to recognize mathematical formulas from images using pixel values', 'create_vision_encoder': 'create a PPFormulaNetVisionModel encoder that processes images through patch embeddings and vision transformer layers', 'run_decoder_generation': 'run PPFormulaNetTextModel decoder to generate text sequences using cross-attention with encoder visual features', 'build_seq2seq_model': 'build a PPFormulaNetModel combining vision encoder and text decoder for image-to-formula sequence-to-sequence generation', 'test_attention_mechanism': 'test PPFormulaNetVisionAttention with relative positional embeddings and window partitioning for efficient visual attention'}
```

## File: huggingface_transformers/src/transformers/models/pp_formulanet/modular_pp_formulanet.py

Prompts

```
['preprocess images for PPFormulaNet model using the PPFormulaNetImageProcessor with crop, resize, and normalize steps', 'crop the margin of an image by removing gray pixels below a configurable threshold value', 'align the long axis of an image to match the longest axis of the specified output size', 'resize an image to create a thumbnail where no dimension exceeds the specified output size', 'pad a batch of images to a specified size at the top, bottom, left, and right edges', 'build a PPFormulaNetForConditionalGeneration model to recognize mathematical formulas from images using pixel values', 'create a PPFormulaNetVisionModel encoder that processes images through patch embeddings and vision transformer layers', 'run PPFormulaNetTextModel decoder to generate text sequences using cross-attention with encoder visual features', 'build a PPFormulaNetModel combining vision encoder and text decoder for image-to-formula sequence-to-sequence generation', 'test PPFormulaNetVisionAttention with relative positional embeddings and window partitioning for efficient visual attention', 'create a PPFormulaNetProcessor to preprocess images for formula recognition', 'run PPFormulaNetForConditionalGeneration forward pass with pixel values to generate formula logits', 'review the PPFormulaNetVisionModel encoder that extracts features from input images', 'test PPFormulaNetConfig initialization with custom vision and text sub-configs', 'create a PPFormulaNetProcessor instance with an image processor and tokenizer for formula image processing', 'call the PPFormulaNetProcessor with images to get pixel values as a BatchFeature for model input', 'post process generated formula text by removing Chinese wrapping, fixing unicode, and normalizing spaces', 'normalize LaTeX formula text by removing unnecessary spaces between non-letter and letter characters', 'post process model generation outputs by decoding tokens and applying text normalization to each generated formula']
```

Usage

```
{'build_formula_recognition_model': 'build a PPFormulaNetForConditionalGeneration model to recognize mathematical formulas from images', 'create_processor_for_images': 'create a PPFormulaNetProcessor to preprocess images for formula recognition', 'run_conditional_generation': 'run PPFormulaNetForConditionalGeneration forward pass with pixel values to generate formula logits', 'review_vision_model_encoder': 'review the PPFormulaNetVisionModel encoder that extracts features from input images', 'test_config_initialization': 'test PPFormulaNetConfig initialization with custom vision and text sub-configs'}
```

## File: huggingface_transformers/src/transformers/models/pp_formulanet/processing_pp_formulanet.py

Prompts

```
['preprocess images for PPFormulaNet model using the PPFormulaNetImageProcessor with crop, resize, and normalize steps', 'crop the margin of an image by removing gray pixels below a configurable threshold value', 'align the long axis of an image to match the longest axis of the specified output size', 'resize an image to create a thumbnail where no dimension exceeds the specified output size', 'pad a batch of images to a specified size at the top, bottom, left, and right edges', 'build a PPFormulaNetForConditionalGeneration model to recognize mathematical formulas from images using pixel values', 'create a PPFormulaNetVisionModel encoder that processes images through patch embeddings and vision transformer layers', 'run PPFormulaNetTextModel decoder to generate text sequences using cross-attention with encoder visual features', 'build a PPFormulaNetModel combining vision encoder and text decoder for image-to-formula sequence-to-sequence generation', 'test PPFormulaNetVisionAttention with relative positional embeddings and window partitioning for efficient visual attention', 'create a PPFormulaNetProcessor to preprocess images for formula recognition', 'run PPFormulaNetForConditionalGeneration forward pass with pixel values to generate formula logits', 'review the PPFormulaNetVisionModel encoder that extracts features from input images', 'test PPFormulaNetConfig initialization with custom vision and text sub-configs', 'create a PPFormulaNetProcessor instance with an image processor and tokenizer for formula image processing', 'call the PPFormulaNetProcessor with images to get pixel values as a BatchFeature for model input', 'post process generated formula text by removing Chinese wrapping, fixing unicode, and normalizing spaces', 'normalize LaTeX formula text by removing unnecessary spaces between non-letter and letter characters', 'post process model generation outputs by decoding tokens and applying text normalization to each generated formula']
```

Usage

```
{'create_PPFormulaNetProcessor': 'create a PPFormulaNetProcessor instance with an image processor and tokenizer for formula image processing', 'call_PPFormulaNetProcessor': 'call the PPFormulaNetProcessor with images to get pixel values as a BatchFeature for model input', 'post_process_generation': 'post process generated formula text by removing Chinese wrapping, fixing unicode, and normalizing spaces', 'normalize_latex_spaces': 'normalize LaTeX formula text by removing unnecessary spaces between non-letter and letter characters', 'post_process_model_outputs': 'post process model generation outputs by decoding tokens and applying text normalization to each generated formula'}
```


# Agent Python Tools

- repo: google-deepmind/gemma
- repo_uri: https://github.com/google-deepmind/gemma

## File: google-deepmind_gemma/gemma/gm/nn/vision/_image.py

Prompts

```
['normalize an image tensor to zero mean and unit variance using JAX', 'pre-process an image by resizing with bilinear interpolation and normalizing pixel values', 'extract fixed-size patches from a batch of images using convolution-based patch extraction', 'load image files from disk paths and return pre-processed patched tensors for a batch', 'review the Gemma vision encoder image preprocessing pipeline including normalization and patching', 'check that a token sequence contains the correct number of placeholder blocks for image tokens', 'check that input data contains the correct special vision tokens at expected positions', 'initialize vision token embeddings by inserting image placeholders into a token buffer for inference', 'build a Flax module that spatially avg-pools vision soft tokens to a required output length', 'build a SigLIP vision encoder that processes patched images into soft tokens for multimodal models']
```

Usage

```
{'normalize_images': 'normalize an image tensor to zero mean and unit variance using JAX', 'pre_process_image': 'pre-process an image by resizing with bilinear interpolation and normalizing pixel values', 'patchify_images': 'extract fixed-size patches from a batch of images using convolution-based patch extraction', 'load_image_files': 'load image files from disk paths and return pre-processed patched tensors for a batch', 'review_image_pipeline': 'review the Gemma vision encoder image preprocessing pipeline including normalization and patching'}
```

## File: google-deepmind_gemma/gemma/gm/nn/vision/_vision.py

Prompts

```
['normalize an image tensor to zero mean and unit variance using JAX', 'pre-process an image by resizing with bilinear interpolation and normalizing pixel values', 'extract fixed-size patches from a batch of images using convolution-based patch extraction', 'load image files from disk paths and return pre-processed patched tensors for a batch', 'review the Gemma vision encoder image preprocessing pipeline including normalization and patching', 'check that a token sequence contains the correct number of placeholder blocks for image tokens', 'check that input data contains the correct special vision tokens at expected positions', 'initialize vision token embeddings by inserting image placeholders into a token buffer for inference', 'build a Flax module that spatially avg-pools vision soft tokens to a required output length', 'build a SigLIP vision encoder that processes patched images into soft tokens for multimodal models']
```

Usage

```
{'check_mask': 'check that a token sequence contains the correct number of placeholder blocks for image tokens', 'check_special_vision_token': 'check that input data contains the correct special vision tokens at expected positions', 'initialize_vision_tokens': 'initialize vision token embeddings by inserting image placeholders into a token buffer for inference', 'VisionExit': 'build a Flax module that spatially avg-pools vision soft tokens to a required output length', 'SigLiPFromPatches': 'build a SigLIP vision encoder that processes patched images into soft tokens for multimodal models'}
```


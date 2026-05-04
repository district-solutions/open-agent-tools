# Agent Python Tools

- repo: google-deepmind/gemma
- repo_uri: https://github.com/google-deepmind/gemma

## File: google-deepmind_gemma/gemma/gm/vision/_preprocess.py

Prompts

```
['build a python module that resizes and normalizes an image using pre_process_image with bilinear resize', 'build a python module that extracts patches from a batch of images using patchify_images with a given patch size', 'build a python module that normalizes an image to zero mean and unit variance using the normalize function', 'test the pre_process_image function by resizing a JAX array image to a target shape and clipping values', 'test the patchify_images function by extracting patches from a batch of images and verifying output shape', 'calculate the total number of multimodal tokens needed given max images and tokens per image', 'add extra image placeholder tokens to text tokens for multimodal Gemma model inference', 'insert a sequence of tokens at every occurrence of a target token in a batch', 'merge text embeddings with vision embeddings using a boolean mask to place vision tokens', 'remove multimodal logits from model output to recover the original text-only logit sequence', 'test add_extra_tokens_for_images expands image placeholder tokens into full image token sequences with padding', 'test merge_embeddings combines text and vision embeddings using a boolean mask to select positions', 'test get_num_mm_tokens returns the total multimodal token count for a given image configuration', 'refactor add_extra_tokens_for_images to support a different number of tokens per image placeholder', 'review merge_embeddings to verify correct handling of batched text and vision embedding arrays']
```

Usage

```
{'build_preprocess_image': 'build a python module that resizes and normalizes an image using pre_process_image with bilinear resize', 'build_patchify_images': 'build a python module that extracts patches from a batch of images using patchify_images with a given patch size', 'build_normalize_images': 'build a python module that normalizes an image to zero mean and unit variance using the normalize function', 'test_pre_process_image': 'test the pre_process_image function by resizing a JAX array image to a target shape and clipping values', 'test_patchify_images': 'test the patchify_images function by extracting patches from a batch of images and verifying output shape'}
```

## File: google-deepmind_gemma/gemma/gm/vision/_token_utils.py

Prompts

```
['build a python module that resizes and normalizes an image using pre_process_image with bilinear resize', 'build a python module that extracts patches from a batch of images using patchify_images with a given patch size', 'build a python module that normalizes an image to zero mean and unit variance using the normalize function', 'test the pre_process_image function by resizing a JAX array image to a target shape and clipping values', 'test the patchify_images function by extracting patches from a batch of images and verifying output shape', 'calculate the total number of multimodal tokens needed given max images and tokens per image', 'add extra image placeholder tokens to text tokens for multimodal Gemma model inference', 'insert a sequence of tokens at every occurrence of a target token in a batch', 'merge text embeddings with vision embeddings using a boolean mask to place vision tokens', 'remove multimodal logits from model output to recover the original text-only logit sequence', 'test add_extra_tokens_for_images expands image placeholder tokens into full image token sequences with padding', 'test merge_embeddings combines text and vision embeddings using a boolean mask to select positions', 'test get_num_mm_tokens returns the total multimodal token count for a given image configuration', 'refactor add_extra_tokens_for_images to support a different number of tokens per image placeholder', 'review merge_embeddings to verify correct handling of batched text and vision embedding arrays']
```

Usage

```
{'calculate_mm_tokens': 'calculate the total number of multimodal tokens needed given max images and tokens per image', 'add_image_tokens': 'add extra image placeholder tokens to text tokens for multimodal Gemma model inference', 'insert_token_sequence': 'insert a sequence of tokens at every occurrence of a target token in a batch', 'merge_embeddings': 'merge text embeddings with vision embeddings using a boolean mask to place vision tokens', 'remove_mm_logits': 'remove multimodal logits from model output to recover the original text-only logit sequence'}
```

## File: google-deepmind_gemma/gemma/gm/vision/_token_utils_test.py

Prompts

```
['build a python module that resizes and normalizes an image using pre_process_image with bilinear resize', 'build a python module that extracts patches from a batch of images using patchify_images with a given patch size', 'build a python module that normalizes an image to zero mean and unit variance using the normalize function', 'test the pre_process_image function by resizing a JAX array image to a target shape and clipping values', 'test the patchify_images function by extracting patches from a batch of images and verifying output shape', 'calculate the total number of multimodal tokens needed given max images and tokens per image', 'add extra image placeholder tokens to text tokens for multimodal Gemma model inference', 'insert a sequence of tokens at every occurrence of a target token in a batch', 'merge text embeddings with vision embeddings using a boolean mask to place vision tokens', 'remove multimodal logits from model output to recover the original text-only logit sequence', 'test add_extra_tokens_for_images expands image placeholder tokens into full image token sequences with padding', 'test merge_embeddings combines text and vision embeddings using a boolean mask to select positions', 'test get_num_mm_tokens returns the total multimodal token count for a given image configuration', 'refactor add_extra_tokens_for_images to support a different number of tokens per image placeholder', 'review merge_embeddings to verify correct handling of batched text and vision embedding arrays']
```

Usage

```
{'test_add_extra_tokens_for_images': 'test add_extra_tokens_for_images expands image placeholder tokens into full image token sequences with padding', 'test_merge_embeddings': 'test merge_embeddings combines text and vision embeddings using a boolean mask to select positions', 'test_get_num_mm_tokens': 'test get_num_mm_tokens returns the total multimodal token count for a given image configuration', 'refactor_add_extra_tokens_for_images': 'refactor add_extra_tokens_for_images to support a different number of tokens per image placeholder', 'review_merge_embeddings': 'review merge_embeddings to verify correct handling of batched text and vision embedding arrays'}
```


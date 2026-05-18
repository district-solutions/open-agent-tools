# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/third_party/clip/clip/clip.py

Prompts

```
['load a CLIP model by name like ViT-B/32 onto cuda or cpu device', 'tokenize a string or list of strings into CLIP token tensors with context length 77', 'list all available CLIP model names like RN50, ViT-B/16, and ViT-L/14', 'download a CLIP model checkpoint from OpenAI with SHA256 verification and progress bar', 'create a torchvision transform pipeline that resizes, crops, and normalizes a PIL image for CLIP', 'build a CLIP model from a PyTorch state dict using build_model', 'encode an image tensor into normalized feature vectors using CLIP encode_image', 'encode tokenized text into normalized feature vectors using CLIP encode_text', 'compute cosine similarity logits between images and text using CLIP forward', 'convert a CLIP model parameters to fp16 using convert_weights', 'create a SimpleTokenizer and encode text into BPE token IDs for CLIP model input', 'use SimpleTokenizer decode method to convert BPE token IDs back into readable text', 'run the SimpleTokenizer bpe method to apply byte pair encoding merges on a single token', 'use basic_clean function to fix text encoding issues and unescape HTML entities', 'use whitespace_clean function to collapse multiple whitespace characters into single spaces']
```

Usage

```
{'load_CLIP_model': 'load a CLIP model by name like ViT-B/32 onto cuda or cpu device', 'tokenize_text': 'tokenize a string or list of strings into CLIP token tensors with context length 77', 'list_available_models': 'list all available CLIP model names like RN50, ViT-B/16, and ViT-L/14', 'download_CLIP_checkpoint': 'download a CLIP model checkpoint from OpenAI with SHA256 verification and progress bar', 'transform_image': 'create a torchvision transform pipeline that resizes, crops, and normalizes a PIL image for CLIP'}
```

## File: facebookresearch_metaseq/third_party/clip/clip/model.py

Prompts

```
['load a CLIP model by name like ViT-B/32 onto cuda or cpu device', 'tokenize a string or list of strings into CLIP token tensors with context length 77', 'list all available CLIP model names like RN50, ViT-B/16, and ViT-L/14', 'download a CLIP model checkpoint from OpenAI with SHA256 verification and progress bar', 'create a torchvision transform pipeline that resizes, crops, and normalizes a PIL image for CLIP', 'build a CLIP model from a PyTorch state dict using build_model', 'encode an image tensor into normalized feature vectors using CLIP encode_image', 'encode tokenized text into normalized feature vectors using CLIP encode_text', 'compute cosine similarity logits between images and text using CLIP forward', 'convert a CLIP model parameters to fp16 using convert_weights', 'create a SimpleTokenizer and encode text into BPE token IDs for CLIP model input', 'use SimpleTokenizer decode method to convert BPE token IDs back into readable text', 'run the SimpleTokenizer bpe method to apply byte pair encoding merges on a single token', 'use basic_clean function to fix text encoding issues and unescape HTML entities', 'use whitespace_clean function to collapse multiple whitespace characters into single spaces']
```

Usage

```
{'build_CLIP_model_from_state_dict': 'build a CLIP model from a PyTorch state dict using build_model', 'encode_image_features': 'encode an image tensor into normalized feature vectors using CLIP encode_image', 'encode_text_features': 'encode tokenized text into normalized feature vectors using CLIP encode_text', 'compute_image_text_similarity': 'compute cosine similarity logits between images and text using CLIP forward', 'convert_model_weights_to_fp16': 'convert a CLIP model parameters to fp16 using convert_weights'}
```

## File: facebookresearch_metaseq/third_party/clip/clip/simple_tokenizer.py

Prompts

```
['load a CLIP model by name like ViT-B/32 onto cuda or cpu device', 'tokenize a string or list of strings into CLIP token tensors with context length 77', 'list all available CLIP model names like RN50, ViT-B/16, and ViT-L/14', 'download a CLIP model checkpoint from OpenAI with SHA256 verification and progress bar', 'create a torchvision transform pipeline that resizes, crops, and normalizes a PIL image for CLIP', 'build a CLIP model from a PyTorch state dict using build_model', 'encode an image tensor into normalized feature vectors using CLIP encode_image', 'encode tokenized text into normalized feature vectors using CLIP encode_text', 'compute cosine similarity logits between images and text using CLIP forward', 'convert a CLIP model parameters to fp16 using convert_weights', 'create a SimpleTokenizer and encode text into BPE token IDs for CLIP model input', 'use SimpleTokenizer decode method to convert BPE token IDs back into readable text', 'run the SimpleTokenizer bpe method to apply byte pair encoding merges on a single token', 'use basic_clean function to fix text encoding issues and unescape HTML entities', 'use whitespace_clean function to collapse multiple whitespace characters into single spaces']
```

Usage

```
{'encode_text_to_bpe_tokens': 'create a SimpleTokenizer and encode text into BPE token IDs for CLIP model input', 'decode_bpe_tokens_to_text': 'use SimpleTokenizer decode method to convert BPE token IDs back into readable text', 'apply_bpe_merging': 'run the SimpleTokenizer bpe method to apply byte pair encoding merges on a single token', 'clean_text_with_basic_clean': 'use basic_clean function to fix text encoding issues and unescape HTML entities', 'normalize_whitespace_with_whitespace_clean': 'use whitespace_clean function to collapse multiple whitespace characters into single spaces'}
```


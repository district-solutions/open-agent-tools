# Agent Python Tools

- repo: facebookresearch/mils
- repo_uri: https://github.com/facebookresearch/mils

## File: facebookresearch_mils/task_utils/video/simple_tokenizer.py

Prompts

```
['create a SimpleTokenizer and encode text into BPE token IDs using the encode method', 'use SimpleTokenizer decode method to convert a list of BPE token IDs back to text', 'call the bpe method on a SimpleTokenizer instance to apply byte pair encoding merges to a token', 'use the basic_clean function to fix text encoding issues and unescape HTML entities', 'use the whitespace_clean function to collapse multiple whitespace characters into single spaces', 'get a ViCLIP model and tokenizer instance for video-language feature extraction', 'get text feature embeddings for a list of text strings using a CLIP model', 'get video feature embeddings from a tensor of video frames using a CLIP model', 'convert a list of video frames into a normalized PyTorch tensor for model input', 'retrieve the top-k most relevant text descriptions for video frames using ViCLIP', 'build a ViCLIP model with pretrained weights and frozen text encoder', 'encode video frames into vision embeddings using the ViCLIP vision encoder', 'encode raw text strings into text embeddings using the ViCLIP text encoder', 'get normalized video features from input frames using the vision encoder', 'build a CLIP text encoder model using clip_text_l14 with pretrained ViT-L/14 weights', 'tokenize input text strings into CLIP token tensors using the CLIP_TEXT tokenize method', 'create a CLIP_TEXT transformer encoder module with configurable embedding dimensions and transformer layers', 'build a CLIP text model dynamically from a config object using the build_clip factory function', 'review the ResidualAttentionBlock class implementing multihead attention with QuickGELU feed-forward network', 'build a VisionTransformer model with configurable patch size, layers, heads, and temporal embeddings for video processing', 'build a ViT-L/14 ViCLIP vision transformer model with optional pretrained weights and configurable kernel size', 'load pretrained 2D weights into a 3D video model by inflating conv weights and interpolating positional embeddings', 'load temporal embeddings with mismatched frame counts by zero-padding or interpolating to match the new model', "interpolate vision and text positional embeddings in a state dict to match a new model's frame count"]
```

Usage

```
{'encode_text_to_bpe_tokens': 'create a SimpleTokenizer and encode text into BPE token IDs using the encode method', 'decode_bpe_tokens_to_text': 'use SimpleTokenizer decode method to convert a list of BPE token IDs back to text', 'apply_bpe_merges_to_token': 'call the bpe method on a SimpleTokenizer instance to apply byte pair encoding merges to a token', 'clean_text_with_basic_clean': 'use the basic_clean function to fix text encoding issues and unescape HTML entities', 'normalize_whitespace_with_whitespace_clean': 'use the whitespace_clean function to collapse multiple whitespace characters into single spaces'}
```

## File: facebookresearch_mils/task_utils/video/utils.py

Prompts

```
['create a SimpleTokenizer and encode text into BPE token IDs using the encode method', 'use SimpleTokenizer decode method to convert a list of BPE token IDs back to text', 'call the bpe method on a SimpleTokenizer instance to apply byte pair encoding merges to a token', 'use the basic_clean function to fix text encoding issues and unescape HTML entities', 'use the whitespace_clean function to collapse multiple whitespace characters into single spaces', 'get a ViCLIP model and tokenizer instance for video-language feature extraction', 'get text feature embeddings for a list of text strings using a CLIP model', 'get video feature embeddings from a tensor of video frames using a CLIP model', 'convert a list of video frames into a normalized PyTorch tensor for model input', 'retrieve the top-k most relevant text descriptions for video frames using ViCLIP', 'build a ViCLIP model with pretrained weights and frozen text encoder', 'encode video frames into vision embeddings using the ViCLIP vision encoder', 'encode raw text strings into text embeddings using the ViCLIP text encoder', 'get normalized video features from input frames using the vision encoder', 'build a CLIP text encoder model using clip_text_l14 with pretrained ViT-L/14 weights', 'tokenize input text strings into CLIP token tensors using the CLIP_TEXT tokenize method', 'create a CLIP_TEXT transformer encoder module with configurable embedding dimensions and transformer layers', 'build a CLIP text model dynamically from a config object using the build_clip factory function', 'review the ResidualAttentionBlock class implementing multihead attention with QuickGELU feed-forward network', 'build a VisionTransformer model with configurable patch size, layers, heads, and temporal embeddings for video processing', 'build a ViT-L/14 ViCLIP vision transformer model with optional pretrained weights and configurable kernel size', 'load pretrained 2D weights into a 3D video model by inflating conv weights and interpolating positional embeddings', 'load temporal embeddings with mismatched frame counts by zero-padding or interpolating to match the new model', "interpolate vision and text positional embeddings in a state dict to match a new model's frame count"]
```

Usage

```
{'get_clip_model': 'get a ViCLIP model and tokenizer instance for video-language feature extraction', 'get_text_features': 'get text feature embeddings for a list of text strings using a CLIP model', 'get_video_features': 'get video feature embeddings from a tensor of video frames using a CLIP model', 'frames_to_tensor': 'convert a list of video frames into a normalized PyTorch tensor for model input', 'retrieve_matching_text': 'retrieve the top-k most relevant text descriptions for video frames using ViCLIP'}
```

## File: facebookresearch_mils/task_utils/video/viclip.py

Prompts

```
['create a SimpleTokenizer and encode text into BPE token IDs using the encode method', 'use SimpleTokenizer decode method to convert a list of BPE token IDs back to text', 'call the bpe method on a SimpleTokenizer instance to apply byte pair encoding merges to a token', 'use the basic_clean function to fix text encoding issues and unescape HTML entities', 'use the whitespace_clean function to collapse multiple whitespace characters into single spaces', 'get a ViCLIP model and tokenizer instance for video-language feature extraction', 'get text feature embeddings for a list of text strings using a CLIP model', 'get video feature embeddings from a tensor of video frames using a CLIP model', 'convert a list of video frames into a normalized PyTorch tensor for model input', 'retrieve the top-k most relevant text descriptions for video frames using ViCLIP', 'build a ViCLIP model with pretrained weights and frozen text encoder', 'encode video frames into vision embeddings using the ViCLIP vision encoder', 'encode raw text strings into text embeddings using the ViCLIP text encoder', 'get normalized video features from input frames using the vision encoder', 'build a CLIP text encoder model using clip_text_l14 with pretrained ViT-L/14 weights', 'tokenize input text strings into CLIP token tensors using the CLIP_TEXT tokenize method', 'create a CLIP_TEXT transformer encoder module with configurable embedding dimensions and transformer layers', 'build a CLIP text model dynamically from a config object using the build_clip factory function', 'review the ResidualAttentionBlock class implementing multihead attention with QuickGELU feed-forward network', 'build a VisionTransformer model with configurable patch size, layers, heads, and temporal embeddings for video processing', 'build a ViT-L/14 ViCLIP vision transformer model with optional pretrained weights and configurable kernel size', 'load pretrained 2D weights into a 3D video model by inflating conv weights and interpolating positional embeddings', 'load temporal embeddings with mismatched frame counts by zero-padding or interpolating to match the new model', "interpolate vision and text positional embeddings in a state dict to match a new model's frame count"]
```

Usage

```
{'build_viclip_model': 'build a ViCLIP model with pretrained weights and frozen text encoder', 'encode_vision_frames': 'encode video frames into vision embeddings using the ViCLIP vision encoder', 'encode_text_tokens': 'encode raw text strings into text embeddings using the ViCLIP text encoder', 'get_text_features': 'get normalized text features for a given input text string with caching', 'get_vid_features': 'get normalized video features from input frames using the vision encoder'}
```

## File: facebookresearch_mils/task_utils/video/viclip_text.py

Prompts

```
['create a SimpleTokenizer and encode text into BPE token IDs using the encode method', 'use SimpleTokenizer decode method to convert a list of BPE token IDs back to text', 'call the bpe method on a SimpleTokenizer instance to apply byte pair encoding merges to a token', 'use the basic_clean function to fix text encoding issues and unescape HTML entities', 'use the whitespace_clean function to collapse multiple whitespace characters into single spaces', 'get a ViCLIP model and tokenizer instance for video-language feature extraction', 'get text feature embeddings for a list of text strings using a CLIP model', 'get video feature embeddings from a tensor of video frames using a CLIP model', 'convert a list of video frames into a normalized PyTorch tensor for model input', 'retrieve the top-k most relevant text descriptions for video frames using ViCLIP', 'build a ViCLIP model with pretrained weights and frozen text encoder', 'encode video frames into vision embeddings using the ViCLIP vision encoder', 'encode raw text strings into text embeddings using the ViCLIP text encoder', 'get normalized video features from input frames using the vision encoder', 'build a CLIP text encoder model using clip_text_l14 with pretrained ViT-L/14 weights', 'tokenize input text strings into CLIP token tensors using the CLIP_TEXT tokenize method', 'create a CLIP_TEXT transformer encoder module with configurable embedding dimensions and transformer layers', 'build a CLIP text model dynamically from a config object using the build_clip factory function', 'review the ResidualAttentionBlock class implementing multihead attention with QuickGELU feed-forward network', 'build a VisionTransformer model with configurable patch size, layers, heads, and temporal embeddings for video processing', 'build a ViT-L/14 ViCLIP vision transformer model with optional pretrained weights and configurable kernel size', 'load pretrained 2D weights into a 3D video model by inflating conv weights and interpolating positional embeddings', 'load temporal embeddings with mismatched frame counts by zero-padding or interpolating to match the new model', "interpolate vision and text positional embeddings in a state dict to match a new model's frame count"]
```

Usage

```
{'build_clip_text_model': 'build a CLIP text encoder model using clip_text_l14 with pretrained ViT-L/14 weights', 'tokenize_text_with_clip': 'tokenize input text strings into CLIP token tensors using the CLIP_TEXT tokenize method', 'create_clip_text_encoder': 'create a CLIP_TEXT transformer encoder module with configurable embedding dimensions and transformer layers', 'build_clip_from_config': 'build a CLIP text model dynamically from a config object using the build_clip factory function', 'review_residual_attention_block': 'review the ResidualAttentionBlock class implementing multihead attention with QuickGELU feed-forward network'}
```

## File: facebookresearch_mils/task_utils/video/viclip_vision.py

Prompts

```
['create a SimpleTokenizer and encode text into BPE token IDs using the encode method', 'use SimpleTokenizer decode method to convert a list of BPE token IDs back to text', 'call the bpe method on a SimpleTokenizer instance to apply byte pair encoding merges to a token', 'use the basic_clean function to fix text encoding issues and unescape HTML entities', 'use the whitespace_clean function to collapse multiple whitespace characters into single spaces', 'get a ViCLIP model and tokenizer instance for video-language feature extraction', 'get text feature embeddings for a list of text strings using a CLIP model', 'get video feature embeddings from a tensor of video frames using a CLIP model', 'convert a list of video frames into a normalized PyTorch tensor for model input', 'retrieve the top-k most relevant text descriptions for video frames using ViCLIP', 'build a ViCLIP model with pretrained weights and frozen text encoder', 'encode video frames into vision embeddings using the ViCLIP vision encoder', 'encode raw text strings into text embeddings using the ViCLIP text encoder', 'get normalized video features from input frames using the vision encoder', 'build a CLIP text encoder model using clip_text_l14 with pretrained ViT-L/14 weights', 'tokenize input text strings into CLIP token tensors using the CLIP_TEXT tokenize method', 'create a CLIP_TEXT transformer encoder module with configurable embedding dimensions and transformer layers', 'build a CLIP text model dynamically from a config object using the build_clip factory function', 'review the ResidualAttentionBlock class implementing multihead attention with QuickGELU feed-forward network', 'build a VisionTransformer model with configurable patch size, layers, heads, and temporal embeddings for video processing', 'build a ViT-L/14 ViCLIP vision transformer model with optional pretrained weights and configurable kernel size', 'load pretrained 2D weights into a 3D video model by inflating conv weights and interpolating positional embeddings', 'load temporal embeddings with mismatched frame counts by zero-padding or interpolating to match the new model', "interpolate vision and text positional embeddings in a state dict to match a new model's frame count"]
```

Usage

```
{'build_VisionTransformer': 'build a VisionTransformer model with configurable patch size, layers, heads, and temporal embeddings for video processing', 'build_clip_joint_l14': 'build a ViT-L/14 ViCLIP vision transformer model with optional pretrained weights and configurable kernel size', 'load_state_dict': 'load pretrained 2D weights into a 3D video model by inflating conv weights and interpolating positional embeddings', 'load_temp_embed_with_mismatch': 'load temporal embeddings with mismatched frame counts by zero-padding or interpolating to match the new model', 'interpolate_pos_embed_vit': "interpolate vision and text positional embeddings in a state dict to match a new model's frame count"}
```


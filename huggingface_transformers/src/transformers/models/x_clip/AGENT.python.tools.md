# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/x_clip/convert_x_clip_original_pytorch_to_hf.py

Prompts

```
['convert an X-CLIP PyTorch checkpoint to Hugging Face transformers format and save locally', 'get the X-CLIP configuration object for a given model name and number of frames', 'rename state dict keys from original X-CLIP format to Hugging Face transformer naming convention', 'transform the original X-CLIP state dict into Hugging Face compatible state dict format', 'download and load a sample spaghetti video from Hugging Face hub for testing the converter', 'create an XCLIP model for video-text contrastive learning with pretrained weights', 'run the XCLIPModel forward pass to compute video-text similarity logits and contrastive loss', 'get text features from XCLIPModel by passing tokenized input_ids through the text encoder', 'get video features from XCLIPModel by passing pixel_values through the vision encoder and multiframe integration transformer', 'build an XCLIPVisionModel with vision embeddings, encoder layers, and projection for video feature extraction', 'run XCLIPModel forward pass to compute video-text similarity scores with contrastive loss', 'create text embeddings using XCLIPTextModel from tokenized input text strings', 'create video embeddings using XCLIPVisionModel and XCLIPMultiframeIntegrationTransformer from pixel values', 'test XCLIPPromptGenerator that generates video-specific prompts via cross-attention between text and visual features', 'review XCLIPVisionEncoderLayer that implements cross-frame attention with message passing across video frames']
```

Usage

```
{'convert_xclip_checkpoint': 'convert an X-CLIP PyTorch checkpoint to Hugging Face transformers format and save locally', 'get_xclip_config': 'get the X-CLIP configuration object for a given model name and number of frames', 'rename_key': 'rename state dict keys from original X-CLIP format to Hugging Face transformer naming convention', 'convert_state_dict': 'transform the original X-CLIP state dict into Hugging Face compatible state dict format', 'prepare_video': 'download and load a sample spaghetti video from Hugging Face hub for testing the converter'}
```

## File: huggingface_transformers/src/transformers/models/x_clip/modeling_x_clip.py

Prompts

```
['convert an X-CLIP PyTorch checkpoint to Hugging Face transformers format and save locally', 'get the X-CLIP configuration object for a given model name and number of frames', 'rename state dict keys from original X-CLIP format to Hugging Face transformer naming convention', 'transform the original X-CLIP state dict into Hugging Face compatible state dict format', 'download and load a sample spaghetti video from Hugging Face hub for testing the converter', 'create an XCLIP model for video-text contrastive learning with pretrained weights', 'run the XCLIPModel forward pass to compute video-text similarity logits and contrastive loss', 'get text features from XCLIPModel by passing tokenized input_ids through the text encoder', 'get video features from XCLIPModel by passing pixel_values through the vision encoder and multiframe integration transformer', 'build an XCLIPVisionModel with vision embeddings, encoder layers, and projection for video feature extraction', 'run XCLIPModel forward pass to compute video-text similarity scores with contrastive loss', 'create text embeddings using XCLIPTextModel from tokenized input text strings', 'create video embeddings using XCLIPVisionModel and XCLIPMultiframeIntegrationTransformer from pixel values', 'test XCLIPPromptGenerator that generates video-specific prompts via cross-attention between text and visual features', 'review XCLIPVisionEncoderLayer that implements cross-frame attention with message passing across video frames']
```

Usage

```
{'create_xclip_model': 'create an XCLIP model for video-text contrastive learning with pretrained weights', 'run_xclip_forward': 'run the XCLIPModel forward pass to compute video-text similarity logits and contrastive loss', 'get_text_features': 'get text features from XCLIPModel by passing tokenized input_ids through the text encoder', 'get_video_features': 'get video features from XCLIPModel by passing pixel_values through the vision encoder and multiframe integration transformer', 'build_xclip_vision_encoder': 'build an XCLIPVisionModel with vision embeddings, encoder layers, and projection for video feature extraction'}
```

## File: huggingface_transformers/src/transformers/models/x_clip/modular_x_clip.py

Prompts

```
['convert an X-CLIP PyTorch checkpoint to Hugging Face transformers format and save locally', 'get the X-CLIP configuration object for a given model name and number of frames', 'rename state dict keys from original X-CLIP format to Hugging Face transformer naming convention', 'transform the original X-CLIP state dict into Hugging Face compatible state dict format', 'download and load a sample spaghetti video from Hugging Face hub for testing the converter', 'create an XCLIP model for video-text contrastive learning with pretrained weights', 'run the XCLIPModel forward pass to compute video-text similarity logits and contrastive loss', 'get text features from XCLIPModel by passing tokenized input_ids through the text encoder', 'get video features from XCLIPModel by passing pixel_values through the vision encoder and multiframe integration transformer', 'build an XCLIPVisionModel with vision embeddings, encoder layers, and projection for video feature extraction', 'run XCLIPModel forward pass to compute video-text similarity scores with contrastive loss', 'create text embeddings using XCLIPTextModel from tokenized input text strings', 'create video embeddings using XCLIPVisionModel and XCLIPMultiframeIntegrationTransformer from pixel values', 'test XCLIPPromptGenerator that generates video-specific prompts via cross-attention between text and visual features', 'review XCLIPVisionEncoderLayer that implements cross-frame attention with message passing across video frames']
```

Usage

```
{'run_xclip_video_text_similarity': 'run XCLIPModel forward pass to compute video-text similarity scores with contrastive loss', 'create_xclip_text_features': 'create text embeddings using XCLIPTextModel from tokenized input text strings', 'create_xclip_video_features': 'create video embeddings using XCLIPVisionModel and XCLIPMultiframeIntegrationTransformer from pixel values', 'test_xclip_prompt_generator': 'test XCLIPPromptGenerator that generates video-specific prompts via cross-attention between text and visual features', 'review_xclip_vision_encoder_layer': 'review XCLIPVisionEncoderLayer that implements cross-frame attention with message passing across video frames'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/blip/convert_blip_original_pytorch_to_hf.py

Prompts

```
['convert a Salesforce BLIP checkpoint to HuggingFace transformers format and save to disk', 'rename BLIP state dict keys to match HuggingFace BlipModel layer naming conventions', 'load and preprocess a demo image from a URL with normalization for BLIP model input', 'run BLIP image captioning by converting original PyTorch model to BlipForConditionalGeneration', 'run BLIP visual question answering and image-text retrieval with converted checkpoints', 'generate image captions using BlipForConditionalGeneration with pixel values and optional text prompts', 'answer visual questions using BlipForQuestionAnswering generate method with image and question text', 'retrieve matching image-text pairs using BlipForImageTextRetrieval with image and text inputs', 'compute image-text contrastive loss using image_text_contrastive_loss function with similarity tensor', 'extract normalized image and text embeddings using BlipModel for image-text similarity scoring', 'build a BlipTextModel that encodes input text with self-attention and optional cross-attention layers', 'create a BlipTextLMHeadModel for next-token prediction and causal language modeling with cross-attention', 'test the BlipTextEncoder that stacks BlipTextLayer modules for multi-layer text encoding', 'refactor the BlipTextSelfAttention class to support both self-attention and cross-attention modes with KV cache', 'review the BlipTextEmbeddings class that combines word and position embeddings with layer normalization and dropout', 'create a BlipProcessor instance with an image_processor and tokenizer for multimodal BLIP model inputs', 'call the BlipProcessor with text input to tokenize and encode text for BLIP model inference', 'call the BlipProcessor with image input to preprocess and encode images for BLIP model inference', 'call the BlipProcessor with both images and text to produce combined multimodal encoding for BLIP', 'get the BlipProcessor model_input_names property to list all expected model input tensor names']
```

Usage

```
{'convert_blip_checkpoint': 'convert a Salesforce BLIP checkpoint to HuggingFace transformers format and save to disk', 'rename_key': 'rename BLIP state dict keys to match HuggingFace BlipModel layer naming conventions', 'load_demo_image': 'load and preprocess a demo image from a URL with normalization for BLIP model input', 'run_blip_conditional_generation': 'run BLIP image captioning by converting original PyTorch model to BlipForConditionalGeneration', 'run_blip_vqa_retrieval': 'run BLIP visual question answering and image-text retrieval with converted checkpoints'}
```

## File: huggingface_transformers/src/transformers/models/blip/modeling_blip.py

Prompts

```
['convert a Salesforce BLIP checkpoint to HuggingFace transformers format and save to disk', 'rename BLIP state dict keys to match HuggingFace BlipModel layer naming conventions', 'load and preprocess a demo image from a URL with normalization for BLIP model input', 'run BLIP image captioning by converting original PyTorch model to BlipForConditionalGeneration', 'run BLIP visual question answering and image-text retrieval with converted checkpoints', 'generate image captions using BlipForConditionalGeneration with pixel values and optional text prompts', 'answer visual questions using BlipForQuestionAnswering generate method with image and question text', 'retrieve matching image-text pairs using BlipForImageTextRetrieval with image and text inputs', 'compute image-text contrastive loss using image_text_contrastive_loss function with similarity tensor', 'extract normalized image and text embeddings using BlipModel for image-text similarity scoring', 'build a BlipTextModel that encodes input text with self-attention and optional cross-attention layers', 'create a BlipTextLMHeadModel for next-token prediction and causal language modeling with cross-attention', 'test the BlipTextEncoder that stacks BlipTextLayer modules for multi-layer text encoding', 'refactor the BlipTextSelfAttention class to support both self-attention and cross-attention modes with KV cache', 'review the BlipTextEmbeddings class that combines word and position embeddings with layer normalization and dropout', 'create a BlipProcessor instance with an image_processor and tokenizer for multimodal BLIP model inputs', 'call the BlipProcessor with text input to tokenize and encode text for BLIP model inference', 'call the BlipProcessor with image input to preprocess and encode images for BLIP model inference', 'call the BlipProcessor with both images and text to produce combined multimodal encoding for BLIP', 'get the BlipProcessor model_input_names property to list all expected model input tensor names']
```

Usage

```
{'generate_image_caption': 'generate image captions using BlipForConditionalGeneration with pixel values and optional text prompts', 'answer_visual_question': 'answer visual questions using BlipForQuestionAnswering generate method with image and question text', 'retrieve_image_text_pairs': 'retrieve matching image-text pairs using BlipForImageTextRetrieval with image and text inputs', 'compute_contrastive_loss': 'compute image-text contrastive loss using image_text_contrastive_loss function with similarity tensor', 'extract_image_text_embeddings': 'extract normalized image and text embeddings using BlipModel for image-text similarity scoring'}
```

## File: huggingface_transformers/src/transformers/models/blip/modeling_blip_text.py

Prompts

```
['convert a Salesforce BLIP checkpoint to HuggingFace transformers format and save to disk', 'rename BLIP state dict keys to match HuggingFace BlipModel layer naming conventions', 'load and preprocess a demo image from a URL with normalization for BLIP model input', 'run BLIP image captioning by converting original PyTorch model to BlipForConditionalGeneration', 'run BLIP visual question answering and image-text retrieval with converted checkpoints', 'generate image captions using BlipForConditionalGeneration with pixel values and optional text prompts', 'answer visual questions using BlipForQuestionAnswering generate method with image and question text', 'retrieve matching image-text pairs using BlipForImageTextRetrieval with image and text inputs', 'compute image-text contrastive loss using image_text_contrastive_loss function with similarity tensor', 'extract normalized image and text embeddings using BlipModel for image-text similarity scoring', 'build a BlipTextModel that encodes input text with self-attention and optional cross-attention layers', 'create a BlipTextLMHeadModel for next-token prediction and causal language modeling with cross-attention', 'test the BlipTextEncoder that stacks BlipTextLayer modules for multi-layer text encoding', 'refactor the BlipTextSelfAttention class to support both self-attention and cross-attention modes with KV cache', 'review the BlipTextEmbeddings class that combines word and position embeddings with layer normalization and dropout', 'create a BlipProcessor instance with an image_processor and tokenizer for multimodal BLIP model inputs', 'call the BlipProcessor with text input to tokenize and encode text for BLIP model inference', 'call the BlipProcessor with image input to preprocess and encode images for BLIP model inference', 'call the BlipProcessor with both images and text to produce combined multimodal encoding for BLIP', 'get the BlipProcessor model_input_names property to list all expected model input tensor names']
```

Usage

```
{'build_blip_text_model': 'build a BlipTextModel that encodes input text with self-attention and optional cross-attention layers', 'create_blip_text_lm_head_model': 'create a BlipTextLMHeadModel for next-token prediction and causal language modeling with cross-attention', 'test_blip_text_encoder': 'test the BlipTextEncoder that stacks BlipTextLayer modules for multi-layer text encoding', 'refactor_blip_text_self_attention': 'refactor the BlipTextSelfAttention class to support both self-attention and cross-attention modes with KV cache', 'review_blip_text_embeddings': 'review the BlipTextEmbeddings class that combines word and position embeddings with layer normalization and dropout'}
```

## File: huggingface_transformers/src/transformers/models/blip/processing_blip.py

Prompts

```
['convert a Salesforce BLIP checkpoint to HuggingFace transformers format and save to disk', 'rename BLIP state dict keys to match HuggingFace BlipModel layer naming conventions', 'load and preprocess a demo image from a URL with normalization for BLIP model input', 'run BLIP image captioning by converting original PyTorch model to BlipForConditionalGeneration', 'run BLIP visual question answering and image-text retrieval with converted checkpoints', 'generate image captions using BlipForConditionalGeneration with pixel values and optional text prompts', 'answer visual questions using BlipForQuestionAnswering generate method with image and question text', 'retrieve matching image-text pairs using BlipForImageTextRetrieval with image and text inputs', 'compute image-text contrastive loss using image_text_contrastive_loss function with similarity tensor', 'extract normalized image and text embeddings using BlipModel for image-text similarity scoring', 'build a BlipTextModel that encodes input text with self-attention and optional cross-attention layers', 'create a BlipTextLMHeadModel for next-token prediction and causal language modeling with cross-attention', 'test the BlipTextEncoder that stacks BlipTextLayer modules for multi-layer text encoding', 'refactor the BlipTextSelfAttention class to support both self-attention and cross-attention modes with KV cache', 'review the BlipTextEmbeddings class that combines word and position embeddings with layer normalization and dropout', 'create a BlipProcessor instance with an image_processor and tokenizer for multimodal BLIP model inputs', 'call the BlipProcessor with text input to tokenize and encode text for BLIP model inference', 'call the BlipProcessor with image input to preprocess and encode images for BLIP model inference', 'call the BlipProcessor with both images and text to produce combined multimodal encoding for BLIP', 'get the BlipProcessor model_input_names property to list all expected model input tensor names']
```

Usage

```
{'create_blip_processor': 'create a BlipProcessor instance with an image_processor and tokenizer for multimodal BLIP model inputs', 'call_blip_processor_with_text': 'call the BlipProcessor with text input to tokenize and encode text for BLIP model inference', 'call_blip_processor_with_images': 'call the BlipProcessor with image input to preprocess and encode images for BLIP model inference', 'call_blip_processor_with_text_and_images': 'call the BlipProcessor with both images and text to produce combined multimodal encoding for BLIP', 'get_blip_processor_model_input_names': 'get the BlipProcessor model_input_names property to list all expected model input tensor names'}
```


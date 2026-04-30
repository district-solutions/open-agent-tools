# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/instructblipvideo/convert_instructblipvideo_original_to_pytorch.py

Prompts

```
['convert an InstructBlipVideo original Salesforce LAVIS checkpoint to a Hugging Face PyTorch model', 'build an InstructBlipVideoConfig from a model name with vision, text, and QFormer configurations', 'create a list of weight key renames mapping original LAVIS checkpoint keys to Hugging Face keys', 'read and concatenate q and v biases from original model into a single qkv bias tensor', 'load a demo image from a URL for verifying checkpoint conversion correctness', 'generate a caption for a video using InstructBlipVideoForConditionalGeneration with pixel values and a prompt', 'get video features by running pixel values through the vision encoder and QFormer to produce language model inputs', 'run the forward pass of InstructBlipVideoForConditionalGeneration with pixel values, input ids, and optional labels for training', 'build an InstructBlipVideoModel with vision encoder, QFormer, and language model from configuration', 'test the QFormer attention mechanism with cross-attention between query tokens and image embeddings', 'create an InstructBlipVideoProcessor instance with video_processor, tokenizer, and qformer_tokenizer for video-text model input preparation', 'call the InstructBlipVideoProcessor with video frames and text input to produce tokenized encodings with qformer input ids and attention masks', 'encode video token placeholders into text encoding by prepending <video> tokens before user text for multimodal model input', 'process video frames through the video processor to produce image encodings compatible with the InstructBlIP model', 'get the combined model input names from tokenizer, video processor, and qformer tokenizer for InstructBlipVideoProcessor']
```

Usage

```
{'convert_instructblipvideo_checkpoint': 'convert an InstructBlipVideo original Salesforce LAVIS checkpoint to a Hugging Face PyTorch model', 'build_blip2_config': 'build an InstructBlipVideoConfig from a model name with vision, text, and QFormer configurations', 'create_rename_keys': 'create a list of weight key renames mapping original LAVIS checkpoint keys to Hugging Face keys', 'read_q_v_bias': 'read and concatenate q and v biases from original model into a single qkv bias tensor', 'load_demo_image': 'load a demo image from a URL for verifying checkpoint conversion correctness'}
```

## File: huggingface_transformers/src/transformers/models/instructblipvideo/modeling_instructblipvideo.py

Prompts

```
['convert an InstructBlipVideo original Salesforce LAVIS checkpoint to a Hugging Face PyTorch model', 'build an InstructBlipVideoConfig from a model name with vision, text, and QFormer configurations', 'create a list of weight key renames mapping original LAVIS checkpoint keys to Hugging Face keys', 'read and concatenate q and v biases from original model into a single qkv bias tensor', 'load a demo image from a URL for verifying checkpoint conversion correctness', 'generate a caption for a video using InstructBlipVideoForConditionalGeneration with pixel values and a prompt', 'get video features by running pixel values through the vision encoder and QFormer to produce language model inputs', 'run the forward pass of InstructBlipVideoForConditionalGeneration with pixel values, input ids, and optional labels for training', 'build an InstructBlipVideoModel with vision encoder, QFormer, and language model from configuration', 'test the QFormer attention mechanism with cross-attention between query tokens and image embeddings', 'create an InstructBlipVideoProcessor instance with video_processor, tokenizer, and qformer_tokenizer for video-text model input preparation', 'call the InstructBlipVideoProcessor with video frames and text input to produce tokenized encodings with qformer input ids and attention masks', 'encode video token placeholders into text encoding by prepending <video> tokens before user text for multimodal model input', 'process video frames through the video processor to produce image encodings compatible with the InstructBlIP model', 'get the combined model input names from tokenizer, video processor, and qformer tokenizer for InstructBlipVideoProcessor']
```

Usage

```
{'generate_video_caption': 'generate a caption for a video using InstructBlipVideoForConditionalGeneration with pixel values and a prompt', 'get_video_features': 'get video features by running pixel values through the vision encoder and QFormer to produce language model inputs', 'run_instructblipvideo_forward': 'run the forward pass of InstructBlipVideoForConditionalGeneration with pixel values, input ids, and optional labels for training', 'build_instructblipvideo_model': 'build an InstructBlipVideoModel with vision encoder, QFormer, and language model from configuration', 'test_qformer_attention': 'test the QFormer attention mechanism with cross-attention between query tokens and image embeddings'}
```

## File: huggingface_transformers/src/transformers/models/instructblipvideo/modular_instructblipvideo.py

Prompts

```
['convert an InstructBlipVideo original Salesforce LAVIS checkpoint to a Hugging Face PyTorch model', 'build an InstructBlipVideoConfig from a model name with vision, text, and QFormer configurations', 'create a list of weight key renames mapping original LAVIS checkpoint keys to Hugging Face keys', 'read and concatenate q and v biases from original model into a single qkv bias tensor', 'load a demo image from a URL for verifying checkpoint conversion correctness', 'generate a caption for a video using InstructBlipVideoForConditionalGeneration with pixel values and a prompt', 'get video features by running pixel values through the vision encoder and QFormer to produce language model inputs', 'run the forward pass of InstructBlipVideoForConditionalGeneration with pixel values, input ids, and optional labels for training', 'build an InstructBlipVideoModel with vision encoder, QFormer, and language model from configuration', 'test the QFormer attention mechanism with cross-attention between query tokens and image embeddings', 'create an InstructBlipVideoProcessor instance with video_processor, tokenizer, and qformer_tokenizer for video-text model input preparation', 'call the InstructBlipVideoProcessor with video frames and text input to produce tokenized encodings with qformer input ids and attention masks', 'encode video token placeholders into text encoding by prepending <video> tokens before user text for multimodal model input', 'process video frames through the video processor to produce image encodings compatible with the InstructBlIP model', 'get the combined model input names from tokenizer, video processor, and qformer tokenizer for InstructBlipVideoProcessor']
```

Usage

```
{'generate_video_caption': 'generate a caption for a video using InstructBlipVideoForConditionalGeneration with pixel values and a prompt', 'get_video_features': 'get video features by running pixel values through the vision encoder and QFormer to produce language model inputs', 'run_instructblipvideo_forward': 'run the forward pass of InstructBlipVideoForConditionalGeneration with pixel values, input ids, and optional labels for training', 'build_instructblipvideo_model': 'build an InstructBlipVideoModel with vision encoder, QFormer, and language model from configuration', 'test_qformer_attention': 'test the QFormer attention mechanism with cross-attention between query tokens and image embeddings'}
```

## File: huggingface_transformers/src/transformers/models/instructblipvideo/processing_instructblipvideo.py

Prompts

```
['convert an InstructBlipVideo original Salesforce LAVIS checkpoint to a Hugging Face PyTorch model', 'build an InstructBlipVideoConfig from a model name with vision, text, and QFormer configurations', 'create a list of weight key renames mapping original LAVIS checkpoint keys to Hugging Face keys', 'read and concatenate q and v biases from original model into a single qkv bias tensor', 'load a demo image from a URL for verifying checkpoint conversion correctness', 'generate a caption for a video using InstructBlipVideoForConditionalGeneration with pixel values and a prompt', 'get video features by running pixel values through the vision encoder and QFormer to produce language model inputs', 'run the forward pass of InstructBlipVideoForConditionalGeneration with pixel values, input ids, and optional labels for training', 'build an InstructBlipVideoModel with vision encoder, QFormer, and language model from configuration', 'test the QFormer attention mechanism with cross-attention between query tokens and image embeddings', 'create an InstructBlipVideoProcessor instance with video_processor, tokenizer, and qformer_tokenizer for video-text model input preparation', 'call the InstructBlipVideoProcessor with video frames and text input to produce tokenized encodings with qformer input ids and attention masks', 'encode video token placeholders into text encoding by prepending <video> tokens before user text for multimodal model input', 'process video frames through the video processor to produce image encodings compatible with the InstructBlIP model', 'get the combined model input names from tokenizer, video processor, and qformer tokenizer for InstructBlipVideoProcessor']
```

Usage

```
{'create_instructblipvideo_processor': 'create an InstructBlipVideoProcessor instance with video_processor, tokenizer, and qformer_tokenizer for video-text model input preparation', 'call_processor_video_text': 'call the InstructBlipVideoProcessor with video frames and text input to produce tokenized encodings with qformer input ids and attention masks', 'encode_video_with_tokenizer': 'encode video token placeholders into text encoding by prepending <video> tokens before user text for multimodal model input', 'process_video_frames': 'process video frames through the video processor to produce image encodings compatible with the InstructBlIP model', 'get_model_input_names': 'get the combined model input names from tokenizer, video processor, and qformer tokenizer for InstructBlipVideoProcessor'}
```


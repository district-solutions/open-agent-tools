# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/florence2/convert_florence2_original_pytorch_to_hf.py

Prompts

```
['convert a microsoft Florence-2 checkpoint to a HuggingFace checkpoint using argparse CLI', 'create a Florence2Config from original model config with vision and text configurations', 'rename vision convolution embedding and spatial block layer weights for Florence-2 model conversion', 'rename language model state dict keys from original format to HuggingFace format', 'build a Florence2Processor with image processor, tokenizer, and post processor configuration', 'create a Florence-2 model for conditional text generation from images using Florence2ForConditionalGeneration', 'build a multimodal pipeline that processes images and text inputs through Florence2Model for image captioning', 'run Florence-2 to extract image features from pixel values using get_image_features method', 'test the Florence-2 forward pass with input_ids, pixel_values, and attention_mask for seq2seq generation', 'summarize the Florence2VisionBackbone architecture with conv embeddings, spatial blocks, and channel blocks', 'create a Florence2ForConditionalGeneration model from a Florence2Config for vision-language tasks', 'run Florence2ForConditionalGeneration.generate() to produce text or structured outputs from images', 'parse Florence-2 OCR output into quadrilateral bounding boxes and text regions', 'parse Florence-2 detection output into bounding boxes or polygons with category labels', 'post-process Florence-2 model generation outputs by task type into structured results like bboxes, polygons, or text', 'construct prompts by replacing Florence-2 task tokens with their corresponding natural language prompt strings', 'run Florence-2 processor on images and text inputs to produce tokenized inputs with pixel values and input_ids', 'parse OCR results with quadrilateral bounding boxes from Florence-2 generated text output', 'parse phrase grounding results mapping text phrases to bounding box coordinates from model output']
```

Usage

```
{'convert_florence2_checkpoint': 'convert a microsoft Florence-2 checkpoint to a HuggingFace checkpoint using argparse CLI', 'create_florence2_config': 'create a Florence2Config from original model config with vision and text configurations', 'rename_vision_weights': 'rename vision convolution embedding and spatial block layer weights for Florence-2 model conversion', 'rename_language_weights': 'rename language model state dict keys from original format to HuggingFace format', 'build_florence2_processor': 'build a Florence2Processor with image processor, tokenizer, and post processor configuration'}
```

## File: huggingface_transformers/src/transformers/models/florence2/modeling_florence2.py

Prompts

```
['convert a microsoft Florence-2 checkpoint to a HuggingFace checkpoint using argparse CLI', 'create a Florence2Config from original model config with vision and text configurations', 'rename vision convolution embedding and spatial block layer weights for Florence-2 model conversion', 'rename language model state dict keys from original format to HuggingFace format', 'build a Florence2Processor with image processor, tokenizer, and post processor configuration', 'create a Florence-2 model for conditional text generation from images using Florence2ForConditionalGeneration', 'build a multimodal pipeline that processes images and text inputs through Florence2Model for image captioning', 'run Florence-2 to extract image features from pixel values using get_image_features method', 'test the Florence-2 forward pass with input_ids, pixel_values, and attention_mask for seq2seq generation', 'summarize the Florence2VisionBackbone architecture with conv embeddings, spatial blocks, and channel blocks', 'create a Florence2ForConditionalGeneration model from a Florence2Config for vision-language tasks', 'run Florence2ForConditionalGeneration.generate() to produce text or structured outputs from images', 'parse Florence-2 OCR output into quadrilateral bounding boxes and text regions', 'parse Florence-2 detection output into bounding boxes or polygons with category labels', 'post-process Florence-2 model generation outputs by task type into structured results like bboxes, polygons, or text', 'construct prompts by replacing Florence-2 task tokens with their corresponding natural language prompt strings', 'run Florence-2 processor on images and text inputs to produce tokenized inputs with pixel values and input_ids', 'parse OCR results with quadrilateral bounding boxes from Florence-2 generated text output', 'parse phrase grounding results mapping text phrases to bounding box coordinates from model output']
```

Usage

```
{'create_florence2_conditional_generation': 'create a Florence-2 model for conditional text generation from images using Florence2ForConditionalGeneration', 'build_florence2_multimodal_pipeline': 'build a multimodal pipeline that processes images and text inputs through Florence2Model for image captioning', 'run_florence2_image_features': 'run Florence-2 to extract image features from pixel values using get_image_features method', 'test_florence2_forward_pass': 'test the Florence-2 forward pass with input_ids, pixel_values, and attention_mask for seq2seq generation', 'summarize_florence2_vision_backbone': 'summarize the Florence2VisionBackbone architecture with conv embeddings, spatial blocks, and channel blocks'}
```

## File: huggingface_transformers/src/transformers/models/florence2/modular_florence2.py

Prompts

```
['convert a microsoft Florence-2 checkpoint to a HuggingFace checkpoint using argparse CLI', 'create a Florence2Config from original model config with vision and text configurations', 'rename vision convolution embedding and spatial block layer weights for Florence-2 model conversion', 'rename language model state dict keys from original format to HuggingFace format', 'build a Florence2Processor with image processor, tokenizer, and post processor configuration', 'create a Florence-2 model for conditional text generation from images using Florence2ForConditionalGeneration', 'build a multimodal pipeline that processes images and text inputs through Florence2Model for image captioning', 'run Florence-2 to extract image features from pixel values using get_image_features method', 'test the Florence-2 forward pass with input_ids, pixel_values, and attention_mask for seq2seq generation', 'summarize the Florence2VisionBackbone architecture with conv embeddings, spatial blocks, and channel blocks', 'create a Florence2ForConditionalGeneration model from a Florence2Config for vision-language tasks', 'run Florence2ForConditionalGeneration.generate() to produce text or structured outputs from images', 'parse Florence-2 OCR output into quadrilateral bounding boxes and text regions', 'parse Florence-2 detection output into bounding boxes or polygons with category labels', 'post-process Florence-2 model generation outputs by task type into structured results like bboxes, polygons, or text', 'construct prompts by replacing Florence-2 task tokens with their corresponding natural language prompt strings', 'run Florence-2 processor on images and text inputs to produce tokenized inputs with pixel values and input_ids', 'parse OCR results with quadrilateral bounding boxes from Florence-2 generated text output', 'parse phrase grounding results mapping text phrases to bounding box coordinates from model output']
```

Usage

```
{'create_florence2_model': 'create a Florence2ForConditionalGeneration model from a Florence2Config for vision-language tasks', 'build_florence2_processor': 'build a Florence2Processor that tokenizes images and task prompts for Florence-2 inference', 'run_florence2_generation': 'run Florence2ForConditionalGeneration.generate() to produce text or structured outputs from images', 'parse_florence2_ocr': 'parse Florence-2 OCR output into quadrilateral bounding boxes and text regions', 'parse_florence2_detection': 'parse Florence-2 detection output into bounding boxes or polygons with category labels'}
```

## File: huggingface_transformers/src/transformers/models/florence2/processing_florence2.py

Prompts

```
['convert a microsoft Florence-2 checkpoint to a HuggingFace checkpoint using argparse CLI', 'create a Florence2Config from original model config with vision and text configurations', 'rename vision convolution embedding and spatial block layer weights for Florence-2 model conversion', 'rename language model state dict keys from original format to HuggingFace format', 'build a Florence2Processor with image processor, tokenizer, and post processor configuration', 'create a Florence-2 model for conditional text generation from images using Florence2ForConditionalGeneration', 'build a multimodal pipeline that processes images and text inputs through Florence2Model for image captioning', 'run Florence-2 to extract image features from pixel values using get_image_features method', 'test the Florence-2 forward pass with input_ids, pixel_values, and attention_mask for seq2seq generation', 'summarize the Florence2VisionBackbone architecture with conv embeddings, spatial blocks, and channel blocks', 'create a Florence2ForConditionalGeneration model from a Florence2Config for vision-language tasks', 'run Florence2ForConditionalGeneration.generate() to produce text or structured outputs from images', 'parse Florence-2 OCR output into quadrilateral bounding boxes and text regions', 'parse Florence-2 detection output into bounding boxes or polygons with category labels', 'post-process Florence-2 model generation outputs by task type into structured results like bboxes, polygons, or text', 'construct prompts by replacing Florence-2 task tokens with their corresponding natural language prompt strings', 'run Florence-2 processor on images and text inputs to produce tokenized inputs with pixel values and input_ids', 'parse OCR results with quadrilateral bounding boxes from Florence-2 generated text output', 'parse phrase grounding results mapping text phrases to bounding box coordinates from model output']
```

Usage

```
{'post_process_florence2_generation': 'post-process Florence-2 model generation outputs by task type into structured results like bboxes, polygons, or text', 'construct_florence2_prompts': 'construct prompts by replacing Florence-2 task tokens with their corresponding natural language prompt strings', 'run_florence2_image_text_processing': 'run Florence-2 processor on images and text inputs to produce tokenized inputs with pixel values and input_ids', 'parse_ocr_from_image_text': 'parse OCR results with quadrilateral bounding boxes from Florence-2 generated text output', 'parse_phrase_grounding_from_text': 'parse phrase grounding results mapping text phrases to bounding box coordinates from model output'}
```


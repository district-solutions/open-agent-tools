# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/layoutxlm/configuration_layoutxlm.py

Prompts

```
['create a LayoutXLMConfig instance with default microsoft/layoutxlm-base configuration', 'create a LayoutXLMConfig instance with custom hidden_size, num_hidden_layers, and num_attention_heads values', 'build a detectron2 config object from LayoutXLMConfig detectron2_config_args dictionary', 'get the default detectron2 config dictionary with ResNet-101 backbone and FPN settings', 'review the LayoutXLMConfig class attributes and methods for initializing a LayoutXLM model configuration', 'create a LayoutXLMProcessor instance with an image processor and tokenizer for document layout analysis', 'call the LayoutXLMProcessor to encode images, text, bounding boxes, and word labels into model inputs', 'get the get_overflowing_images method to map overflowing token samples back to their corresponding images', 'read the model_input_names property to get the list of expected model input names for LayoutXLM', 'test the LayoutXLMProcessor with apply_ocr enabled to verify it rejects provided bounding boxes and word labels', 'create a LayoutXLMTokenizer instance with vocab, special token boxes, and word label settings', 'encode pretokenized text with bounding boxes and optional word labels using LayoutXLMTokenizer', 'batch encode multiple pretokenized text sequences with bounding boxes and word labels', 'pad encoded inputs to a maximum length with bounding boxes and attention masks', 'build model inputs from token sequences by concatenating and adding special tokens']
```

Usage

```
{'create_layoutxlm_config': 'create a LayoutXLMConfig instance with default microsoft/layoutxlm-base configuration', 'create_layoutxlm_config_custom': 'create a LayoutXLMConfig instance with custom hidden_size, num_hidden_layers, and num_attention_heads values', 'build_detectron2_config': 'build a detectron2 config object from LayoutXLMConfig detectron2_config_args dictionary', 'get_default_detectron2_config': 'get the default detectron2 config dictionary with ResNet-101 backbone and FPN settings', 'review_layoutxlm_config': 'review the LayoutXLMConfig class attributes and methods for initializing a LayoutXLM model configuration'}
```

## File: huggingface_transformers/src/transformers/models/layoutxlm/processing_layoutxlm.py

Prompts

```
['create a LayoutXLMConfig instance with default microsoft/layoutxlm-base configuration', 'create a LayoutXLMConfig instance with custom hidden_size, num_hidden_layers, and num_attention_heads values', 'build a detectron2 config object from LayoutXLMConfig detectron2_config_args dictionary', 'get the default detectron2 config dictionary with ResNet-101 backbone and FPN settings', 'review the LayoutXLMConfig class attributes and methods for initializing a LayoutXLM model configuration', 'create a LayoutXLMProcessor instance with an image processor and tokenizer for document layout analysis', 'call the LayoutXLMProcessor to encode images, text, bounding boxes, and word labels into model inputs', 'get the get_overflowing_images method to map overflowing token samples back to their corresponding images', 'read the model_input_names property to get the list of expected model input names for LayoutXLM', 'test the LayoutXLMProcessor with apply_ocr enabled to verify it rejects provided bounding boxes and word labels', 'create a LayoutXLMTokenizer instance with vocab, special token boxes, and word label settings', 'encode pretokenized text with bounding boxes and optional word labels using LayoutXLMTokenizer', 'batch encode multiple pretokenized text sequences with bounding boxes and word labels', 'pad encoded inputs to a maximum length with bounding boxes and attention masks', 'build model inputs from token sequences by concatenating and adding special tokens']
```

Usage

```
{'create_layoutxlm_processor': 'create a LayoutXLMProcessor instance with an image processor and tokenizer for document layout analysis', 'call_layoutxlm_processor': 'call the LayoutXLMProcessor to encode images, text, bounding boxes, and word labels into model inputs', 'get_overflowing_images': 'get the get_overflowing_images method to map overflowing token samples back to their corresponding images', 'read_model_input_names': 'read the model_input_names property to get the list of expected model input names for LayoutXLM', 'test_layoutxlm_processor_ocr': 'test the LayoutXLMProcessor with apply_ocr enabled to verify it rejects provided bounding boxes and word labels'}
```

## File: huggingface_transformers/src/transformers/models/layoutxlm/tokenization_layoutxlm.py

Prompts

```
['create a LayoutXLMConfig instance with default microsoft/layoutxlm-base configuration', 'create a LayoutXLMConfig instance with custom hidden_size, num_hidden_layers, and num_attention_heads values', 'build a detectron2 config object from LayoutXLMConfig detectron2_config_args dictionary', 'get the default detectron2 config dictionary with ResNet-101 backbone and FPN settings', 'review the LayoutXLMConfig class attributes and methods for initializing a LayoutXLM model configuration', 'create a LayoutXLMProcessor instance with an image processor and tokenizer for document layout analysis', 'call the LayoutXLMProcessor to encode images, text, bounding boxes, and word labels into model inputs', 'get the get_overflowing_images method to map overflowing token samples back to their corresponding images', 'read the model_input_names property to get the list of expected model input names for LayoutXLM', 'test the LayoutXLMProcessor with apply_ocr enabled to verify it rejects provided bounding boxes and word labels', 'create a LayoutXLMTokenizer instance with vocab, special token boxes, and word label settings', 'encode pretokenized text with bounding boxes and optional word labels using LayoutXLMTokenizer', 'batch encode multiple pretokenized text sequences with bounding boxes and word labels', 'pad encoded inputs to a maximum length with bounding boxes and attention masks', 'build model inputs from token sequences by concatenating and adding special tokens']
```

Usage

```
{'create_tokenizer_layoutxlm': 'create a LayoutXLMTokenizer instance with vocab, special token boxes, and word label settings', 'encode_text_with_boxes': 'encode pretokenized text with bounding boxes and optional word labels using LayoutXLMTokenizer', 'batch_encode_text_boxes': 'batch encode multiple pretokenized text sequences with bounding boxes and word labels', 'pad_encoded_inputs_bbox': 'pad encoded inputs to a maximum length with bounding boxes and attention masks', 'build_inputs_special_tokens': 'build model inputs from token sequences by concatenating and adding special tokens'}
```


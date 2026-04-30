# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/layoutlmv3/test_image_processing_layoutlmv3.py

Prompts

```
['test the LayoutLMv3ImageProcessingTest class to verify image processing with OCR integration', 'test the LayoutLMv3 image processor has do_resize, size, and apply_ocr attributes', 'test the LayoutLMv3 image processor from_dict method with default and overridden size parameters', 'test the LayoutLMv3 image processor integration with a real document image and Tesseract OCR output', 'build a LayoutLMv3ImageProcessingTest instance with custom batch size, image size, and OCR settings', 'test the LayoutLMv3Model class with text, image, and bounding box inputs for multimodal document understanding', 'test the LayoutLMv3ForSequenceClassification class to classify document images into label categories', 'test the LayoutLMv3ForTokenClassification class to perform token-level labeling on document text with bounding boxes', 'test the LayoutLMv3ForQuestionAnswering class to extract start and end positions from document text for QA tasks', 'run inference on the pretrained microsoft/layoutlmv3-base model with an image and bounding box inputs', 'test LayoutLMv3Processor with apply_ocr=True for document image classification and token classification', 'test LayoutLMv3Processor with apply_ocr=False using explicit words and bounding boxes', 'test LayoutLMv3Processor with word_labels for token classification training', 'test LayoutLMv3Processor with apply_ocr=True for visual question answering inference', 'test LayoutLMv3Processor with apply_ocr=False for visual question answering using explicit words and boxes', 'test the LayoutLMv3TokenizationTest class that validates LayoutLMv3 tokenizer integration with words and bounding boxes', 'test LayoutLMv3 tokenizer encoding, decoding, and roundtrip with hardcoded expectations for input words and boxes', 'test LayoutLMv3 tokenizer BPE tokenization with a minimal vocabulary fixture for words and boxes', 'test LayoutLMv3 tokenizer padding behavior comparing slow and fast tokenizers with words and bounding boxes', 'test LayoutLMv3 tokenizer all three use cases: document classification, token classification with labels, and visual question answering']
```

Usage

```
{'test_LayoutLMv3_image_processing': 'test the LayoutLMv3ImageProcessingTest class to verify image processing with OCR integration', 'test_image_processor_properties': 'test the LayoutLMv3 image processor has do_resize, size, and apply_ocr attributes', 'test_image_processor_from_dict': 'test the LayoutLMv3 image processor from_dict method with default and overridden size parameters', 'test_LayoutLMv3_integration': 'test the LayoutLMv3 image processor integration with a real document image and Tesseract OCR output', 'build_LayoutLMv3_image_processor': 'build a LayoutLMv3ImageProcessingTest instance with custom batch size, image size, and OCR settings'}
```

## File: huggingface_transformers/tests/models/layoutlmv3/test_modeling_layoutlmv3.py

Prompts

```
['test the LayoutLMv3ImageProcessingTest class to verify image processing with OCR integration', 'test the LayoutLMv3 image processor has do_resize, size, and apply_ocr attributes', 'test the LayoutLMv3 image processor from_dict method with default and overridden size parameters', 'test the LayoutLMv3 image processor integration with a real document image and Tesseract OCR output', 'build a LayoutLMv3ImageProcessingTest instance with custom batch size, image size, and OCR settings', 'test the LayoutLMv3Model class with text, image, and bounding box inputs for multimodal document understanding', 'test the LayoutLMv3ForSequenceClassification class to classify document images into label categories', 'test the LayoutLMv3ForTokenClassification class to perform token-level labeling on document text with bounding boxes', 'test the LayoutLMv3ForQuestionAnswering class to extract start and end positions from document text for QA tasks', 'run inference on the pretrained microsoft/layoutlmv3-base model with an image and bounding box inputs', 'test LayoutLMv3Processor with apply_ocr=True for document image classification and token classification', 'test LayoutLMv3Processor with apply_ocr=False using explicit words and bounding boxes', 'test LayoutLMv3Processor with word_labels for token classification training', 'test LayoutLMv3Processor with apply_ocr=True for visual question answering inference', 'test LayoutLMv3Processor with apply_ocr=False for visual question answering using explicit words and boxes', 'test the LayoutLMv3TokenizationTest class that validates LayoutLMv3 tokenizer integration with words and bounding boxes', 'test LayoutLMv3 tokenizer encoding, decoding, and roundtrip with hardcoded expectations for input words and boxes', 'test LayoutLMv3 tokenizer BPE tokenization with a minimal vocabulary fixture for words and boxes', 'test LayoutLMv3 tokenizer padding behavior comparing slow and fast tokenizers with words and bounding boxes', 'test LayoutLMv3 tokenizer all three use cases: document classification, token classification with labels, and visual question answering']
```

Usage

```
{'test_model_layoutlmv3': 'test the LayoutLMv3Model class with text, image, and bounding box inputs for multimodal document understanding', 'test_model_sequence_classification': 'test the LayoutLMv3ForSequenceClassification class to classify document images into label categories', 'test_model_token_classification': 'test the LayoutLMv3ForTokenClassification class to perform token-level labeling on document text with bounding boxes', 'test_model_question_answering': 'test the LayoutLMv3ForQuestionAnswering class to extract start and end positions from document text for QA tasks', 'test_model_from_pretrained': 'run inference on the pretrained microsoft/layoutlmv3-base model with an image and bounding box inputs'}
```

## File: huggingface_transformers/tests/models/layoutlmv3/test_processing_layoutlmv3.py

Prompts

```
['test the LayoutLMv3ImageProcessingTest class to verify image processing with OCR integration', 'test the LayoutLMv3 image processor has do_resize, size, and apply_ocr attributes', 'test the LayoutLMv3 image processor from_dict method with default and overridden size parameters', 'test the LayoutLMv3 image processor integration with a real document image and Tesseract OCR output', 'build a LayoutLMv3ImageProcessingTest instance with custom batch size, image size, and OCR settings', 'test the LayoutLMv3Model class with text, image, and bounding box inputs for multimodal document understanding', 'test the LayoutLMv3ForSequenceClassification class to classify document images into label categories', 'test the LayoutLMv3ForTokenClassification class to perform token-level labeling on document text with bounding boxes', 'test the LayoutLMv3ForQuestionAnswering class to extract start and end positions from document text for QA tasks', 'run inference on the pretrained microsoft/layoutlmv3-base model with an image and bounding box inputs', 'test LayoutLMv3Processor with apply_ocr=True for document image classification and token classification', 'test LayoutLMv3Processor with apply_ocr=False using explicit words and bounding boxes', 'test LayoutLMv3Processor with word_labels for token classification training', 'test LayoutLMv3Processor with apply_ocr=True for visual question answering inference', 'test LayoutLMv3Processor with apply_ocr=False for visual question answering using explicit words and boxes', 'test the LayoutLMv3TokenizationTest class that validates LayoutLMv3 tokenizer integration with words and bounding boxes', 'test LayoutLMv3 tokenizer encoding, decoding, and roundtrip with hardcoded expectations for input words and boxes', 'test LayoutLMv3 tokenizer BPE tokenization with a minimal vocabulary fixture for words and boxes', 'test LayoutLMv3 tokenizer padding behavior comparing slow and fast tokenizers with words and bounding boxes', 'test LayoutLMv3 tokenizer all three use cases: document classification, token classification with labels, and visual question answering']
```

Usage

```
{'test_processor_case_1': 'test LayoutLMv3Processor with apply_ocr=True for document image classification and token classification', 'test_processor_case_2': 'test LayoutLMv3Processor with apply_ocr=False using explicit words and bounding boxes', 'test_processor_case_3': 'test LayoutLMv3Processor with word_labels for token classification training', 'test_processor_case_4': 'test LayoutLMv3Processor with apply_ocr=True for visual question answering inference', 'test_processor_case_5': 'test LayoutLMv3Processor with apply_ocr=False for visual question answering using explicit words and boxes'}
```

## File: huggingface_transformers/tests/models/layoutlmv3/test_tokenization_layoutlmv3.py

Prompts

```
['test the LayoutLMv3ImageProcessingTest class to verify image processing with OCR integration', 'test the LayoutLMv3 image processor has do_resize, size, and apply_ocr attributes', 'test the LayoutLMv3 image processor from_dict method with default and overridden size parameters', 'test the LayoutLMv3 image processor integration with a real document image and Tesseract OCR output', 'build a LayoutLMv3ImageProcessingTest instance with custom batch size, image size, and OCR settings', 'test the LayoutLMv3Model class with text, image, and bounding box inputs for multimodal document understanding', 'test the LayoutLMv3ForSequenceClassification class to classify document images into label categories', 'test the LayoutLMv3ForTokenClassification class to perform token-level labeling on document text with bounding boxes', 'test the LayoutLMv3ForQuestionAnswering class to extract start and end positions from document text for QA tasks', 'run inference on the pretrained microsoft/layoutlmv3-base model with an image and bounding box inputs', 'test LayoutLMv3Processor with apply_ocr=True for document image classification and token classification', 'test LayoutLMv3Processor with apply_ocr=False using explicit words and bounding boxes', 'test LayoutLMv3Processor with word_labels for token classification training', 'test LayoutLMv3Processor with apply_ocr=True for visual question answering inference', 'test LayoutLMv3Processor with apply_ocr=False for visual question answering using explicit words and boxes', 'test the LayoutLMv3TokenizationTest class that validates LayoutLMv3 tokenizer integration with words and bounding boxes', 'test LayoutLMv3 tokenizer encoding, decoding, and roundtrip with hardcoded expectations for input words and boxes', 'test LayoutLMv3 tokenizer BPE tokenization with a minimal vocabulary fixture for words and boxes', 'test LayoutLMv3 tokenizer padding behavior comparing slow and fast tokenizers with words and bounding boxes', 'test LayoutLMv3 tokenizer all three use cases: document classification, token classification with labels, and visual question answering']
```

Usage

```
{'test_tokenization_layoutlmv3': 'test the LayoutLMv3TokenizationTest class that validates LayoutLMv3 tokenizer integration with words and bounding boxes', 'test_integration': 'test LayoutLMv3 tokenizer encoding, decoding, and roundtrip with hardcoded expectations for input words and boxes', 'test_full_tokenizer': 'test LayoutLMv3 tokenizer BPE tokenization with a minimal vocabulary fixture for words and boxes', 'test_padding': 'test LayoutLMv3 tokenizer padding behavior comparing slow and fast tokenizers with words and bounding boxes', 'test_layoutlmv3_integration_test': 'test LayoutLMv3 tokenizer all three use cases: document classification, token classification with labels, and visual question answering'}
```


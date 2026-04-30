# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/layoutlmv2/test_image_processing_layoutlmv2.py

Prompts

```
['test that LayoutLMv2 image processor has do_resize, size, and apply_ocr properties', 'test creating a LayoutLMv2 image processor from a config dict with override kwargs', 'test LayoutLMv2 image processing with OCR on a DocVQA dataset image and verify words and boxes', 'test that LayoutLMv2 image processing produces equivalent pixel values across different backends', 'test that the LayoutLMv2 torchvision image processor can be compiled with torch.compile', 'test the LayoutLMv2ModelTester to prepare config and inputs for model testing', 'test the LayoutLMv2ModelTester to create and check the base LayoutLMv2 model output shapes', 'test the LayoutLMv2ModelTester to create and check sequence classification model outputs', 'test the LayoutLMv2ModelTester to create and check token classification model outputs', 'test the LayoutLMv2ModelTester to create and check question answering model outputs', 'test LayoutLMv2Processor save and load with pretrained additional features including slow and fast tokenizers', 'test LayoutLMv2Processor with apply_ocr=True for document image classification and token classification', 'test LayoutLMv2Processor with apply_ocr=False for document image classification using provided words and boxes', 'test LayoutLMv2Processor for token classification training with apply_ocr=False and word_labels', 'test LayoutLMv2Processor for visual question answering inference with apply_ocr=True', 'test the LayoutLMv2 tokenizer with words and bounding boxes for document image understanding', 'test LayoutLMv2 tokenizer encode_plus with left and right padding strategies', 'test LayoutLMv2 batch_encode_plus produces equivalent results to individual encode_plus calls', 'test training a new LayoutLMv2 tokenizer from a small corpus with preserved special tokens']
```

Usage

```
{'test_image_processor_properties': 'test that LayoutLMv2 image processor has do_resize, size, and apply_ocr properties', 'test_image_processor_from_dict_with_kwargs': 'test creating a LayoutLMv2 image processor from a config dict with override kwargs', 'test_layoutlmv2_integration_test': 'test LayoutLMv2 image processing with OCR on a DocVQA dataset image and verify words and boxes', 'test_backends_equivalence': 'test that LayoutLMv2 image processing produces equivalent pixel values across different backends', 'test_can_compile_torchvision_backend': 'test that the LayoutLMv2 torchvision image processor can be compiled with torch.compile'}
```

## File: huggingface_transformers/tests/models/layoutlmv2/test_modeling_layoutlmv2.py

Prompts

```
['test that LayoutLMv2 image processor has do_resize, size, and apply_ocr properties', 'test creating a LayoutLMv2 image processor from a config dict with override kwargs', 'test LayoutLMv2 image processing with OCR on a DocVQA dataset image and verify words and boxes', 'test that LayoutLMv2 image processing produces equivalent pixel values across different backends', 'test that the LayoutLMv2 torchvision image processor can be compiled with torch.compile', 'test the LayoutLMv2ModelTester to prepare config and inputs for model testing', 'test the LayoutLMv2ModelTester to create and check the base LayoutLMv2 model output shapes', 'test the LayoutLMv2ModelTester to create and check sequence classification model outputs', 'test the LayoutLMv2ModelTester to create and check token classification model outputs', 'test the LayoutLMv2ModelTester to create and check question answering model outputs', 'test LayoutLMv2Processor save and load with pretrained additional features including slow and fast tokenizers', 'test LayoutLMv2Processor with apply_ocr=True for document image classification and token classification', 'test LayoutLMv2Processor with apply_ocr=False for document image classification using provided words and boxes', 'test LayoutLMv2Processor for token classification training with apply_ocr=False and word_labels', 'test LayoutLMv2Processor for visual question answering inference with apply_ocr=True', 'test the LayoutLMv2 tokenizer with words and bounding boxes for document image understanding', 'test LayoutLMv2 tokenizer encode_plus with left and right padding strategies', 'test LayoutLMv2 batch_encode_plus produces equivalent results to individual encode_plus calls', 'test training a new LayoutLMv2 tokenizer from a small corpus with preserved special tokens']
```

Usage

```
{'test_LayoutLMv2ModelTester_prepare_config_and_inputs': 'test the LayoutLMv2ModelTester to prepare config and inputs for model testing', 'test_LayoutLMv2ModelTester_create_and_check_model': 'test the LayoutLMv2ModelTester to create and check the base LayoutLMv2 model output shapes', 'test_LayoutLMv2ModelTester_create_and_check_for_sequence_classification': 'test the LayoutLMv2ModelTester to create and check sequence classification model outputs', 'test_LayoutLMv2ModelTester_create_and_check_for_token_classification': 'test the LayoutLMv2ModelTester to create and check token classification model outputs', 'test_LayoutLMv2ModelTester_create_and_check_for_question_answering': 'test the LayoutLMv2ModelTester to create and check question answering model outputs'}
```

## File: huggingface_transformers/tests/models/layoutlmv2/test_processing_layoutlmv2.py

Prompts

```
['test that LayoutLMv2 image processor has do_resize, size, and apply_ocr properties', 'test creating a LayoutLMv2 image processor from a config dict with override kwargs', 'test LayoutLMv2 image processing with OCR on a DocVQA dataset image and verify words and boxes', 'test that LayoutLMv2 image processing produces equivalent pixel values across different backends', 'test that the LayoutLMv2 torchvision image processor can be compiled with torch.compile', 'test the LayoutLMv2ModelTester to prepare config and inputs for model testing', 'test the LayoutLMv2ModelTester to create and check the base LayoutLMv2 model output shapes', 'test the LayoutLMv2ModelTester to create and check sequence classification model outputs', 'test the LayoutLMv2ModelTester to create and check token classification model outputs', 'test the LayoutLMv2ModelTester to create and check question answering model outputs', 'test LayoutLMv2Processor save and load with pretrained additional features including slow and fast tokenizers', 'test LayoutLMv2Processor with apply_ocr=True for document image classification and token classification', 'test LayoutLMv2Processor with apply_ocr=False for document image classification using provided words and boxes', 'test LayoutLMv2Processor for token classification training with apply_ocr=False and word_labels', 'test LayoutLMv2Processor for visual question answering inference with apply_ocr=True', 'test the LayoutLMv2 tokenizer with words and bounding boxes for document image understanding', 'test LayoutLMv2 tokenizer encode_plus with left and right padding strategies', 'test LayoutLMv2 batch_encode_plus produces equivalent results to individual encode_plus calls', 'test training a new LayoutLMv2 tokenizer from a small corpus with preserved special tokens']
```

Usage

```
{'test_processor_save_load_pretrained_additional_features': 'test LayoutLMv2Processor save and load with pretrained additional features including slow and fast tokenizers', 'test_processor_case_1_ocr': 'test LayoutLMv2Processor with apply_ocr=True for document image classification and token classification', 'test_processor_case_2_no_ocr': 'test LayoutLMv2Processor with apply_ocr=False for document image classification using provided words and boxes', 'test_processor_case_3_token_classification': 'test LayoutLMv2Processor for token classification training with apply_ocr=False and word_labels', 'test_processor_case_4_vqa_ocr': 'test LayoutLMv2Processor for visual question answering inference with apply_ocr=True'}
```

## File: huggingface_transformers/tests/models/layoutlmv2/test_tokenization_layoutlmv2.py

Prompts

```
['test that LayoutLMv2 image processor has do_resize, size, and apply_ocr properties', 'test creating a LayoutLMv2 image processor from a config dict with override kwargs', 'test LayoutLMv2 image processing with OCR on a DocVQA dataset image and verify words and boxes', 'test that LayoutLMv2 image processing produces equivalent pixel values across different backends', 'test that the LayoutLMv2 torchvision image processor can be compiled with torch.compile', 'test the LayoutLMv2ModelTester to prepare config and inputs for model testing', 'test the LayoutLMv2ModelTester to create and check the base LayoutLMv2 model output shapes', 'test the LayoutLMv2ModelTester to create and check sequence classification model outputs', 'test the LayoutLMv2ModelTester to create and check token classification model outputs', 'test the LayoutLMv2ModelTester to create and check question answering model outputs', 'test LayoutLMv2Processor save and load with pretrained additional features including slow and fast tokenizers', 'test LayoutLMv2Processor with apply_ocr=True for document image classification and token classification', 'test LayoutLMv2Processor with apply_ocr=False for document image classification using provided words and boxes', 'test LayoutLMv2Processor for token classification training with apply_ocr=False and word_labels', 'test LayoutLMv2Processor for visual question answering inference with apply_ocr=True', 'test the LayoutLMv2 tokenizer with words and bounding boxes for document image understanding', 'test LayoutLMv2 tokenizer encode_plus with left and right padding strategies', 'test LayoutLMv2 batch_encode_plus produces equivalent results to individual encode_plus calls', 'test training a new LayoutLMv2 tokenizer from a small corpus with preserved special tokens']
```

Usage

```
{'test_tokenization_layoutlmv2': 'test the LayoutLMv2 tokenizer with words and bounding boxes for document image understanding', 'test_encode_plus_with_padding': 'test LayoutLMv2 tokenizer encode_plus with left and right padding strategies', 'test_batch_encode_plus_padding': 'test LayoutLMv2 batch_encode_plus produces equivalent results to individual encode_plus calls', 'test_layoutlmv2_integration_test': 'test LayoutLMv2 tokenizer integration across classification, token classification, and VQA use cases', 'test_training_new_tokenizer': 'test training a new LayoutLMv2 tokenizer from a small corpus with preserved special tokens'}
```


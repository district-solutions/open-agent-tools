# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/udop/test_modeling_udop.py

Prompts

```
['test the UdopModel forward pass with input_ids, bbox, and decoder_input_ids tensors', 'test UdopForConditionalGeneration with labels for language modeling loss computation', 'test UdopForConditionalGeneration generate produces identical outputs with and without past key value cache', 'test UdopEncoderModel forward pass with input_ids and bbox returning last_hidden_state', 'test UdopForConditionalGeneration and UdopEncoderModel fp16 forward pass produces no NaN outputs', 'test the UdopProcessor text_target encoding to verify input_ids and attention_mask match expected tokenized output', 'test UdopProcessor with overflowing tokens to verify 1-to-1 mapping between images and input_ids on long sequences', 'test UdopProcessor document image classification and token classification inference with apply_ocr=True for both slow and fast tokenizers', 'test UdopProcessor document image classification with apply_ocr=False passing words and bounding boxes as input', 'test UdopProcessor token classification training with word_labels and verify labels padding with -100', 'test UdopProcessor visual question answering inference with apply_ocr=True combining OCR text with question input', 'test UdopProcessor visual question answering inference with apply_ocr=False using text_pair for words and boxes']
```

Usage

```
{'test_udop_model_forward': 'test the UdopModel forward pass with input_ids, bbox, and decoder_input_ids tensors', 'test_udop_conditional_generation': 'test UdopForConditionalGeneration with labels for language modeling loss computation', 'test_udop_generate_with_past_cache': 'test UdopForConditionalGeneration generate produces identical outputs with and without past key value cache', 'test_udop_encoder_model_forward': 'test UdopEncoderModel forward pass with input_ids and bbox returning last_hidden_state', 'test_udop_fp16_forward': 'test UdopForConditionalGeneration and UdopEncoderModel fp16 forward pass produces no NaN outputs'}
```

## File: huggingface_transformers/tests/models/udop/test_processing_udop.py

Prompts

```
['test the UdopModel forward pass with input_ids, bbox, and decoder_input_ids tensors', 'test UdopForConditionalGeneration with labels for language modeling loss computation', 'test UdopForConditionalGeneration generate produces identical outputs with and without past key value cache', 'test UdopEncoderModel forward pass with input_ids and bbox returning last_hidden_state', 'test UdopForConditionalGeneration and UdopEncoderModel fp16 forward pass produces no NaN outputs', 'test the UdopProcessor text_target encoding to verify input_ids and attention_mask match expected tokenized output', 'test UdopProcessor with overflowing tokens to verify 1-to-1 mapping between images and input_ids on long sequences', 'test UdopProcessor document image classification and token classification inference with apply_ocr=True for both slow and fast tokenizers', 'test UdopProcessor document image classification with apply_ocr=False passing words and bounding boxes as input', 'test UdopProcessor token classification training with word_labels and verify labels padding with -100', 'test UdopProcessor visual question answering inference with apply_ocr=True combining OCR text with question input', 'test UdopProcessor visual question answering inference with apply_ocr=False using text_pair for words and boxes']
```

Usage

```
{'test_udop_processor_text_target': 'test the UdopProcessor text_target encoding to verify input_ids and attention_mask match expected tokenized output', 'test_udop_processor_overflowing_tokens': 'test UdopProcessor with overflowing tokens to verify 1-to-1 mapping between images and input_ids on long sequences', 'test_udop_processor_case_1': 'test UdopProcessor document image classification and token classification inference with apply_ocr=True for both slow and fast tokenizers', 'test_udop_processor_case_2': 'test UdopProcessor document image classification with apply_ocr=False passing words and bounding boxes as input', 'test_udop_processor_case_3': 'test UdopProcessor token classification training with word_labels and verify labels padding with -100', 'test_udop_processor_case_4': 'test UdopProcessor visual question answering inference with apply_ocr=True combining OCR text with question input', 'test_udop_processor_case_5': 'test UdopProcessor visual question answering inference with apply_ocr=False using text_pair for words and boxes'}
```


# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/perceiver/test_image_processing_perceiver.py

Prompts

```
['test that PerceiverImageProcessingTester initializes with correct crop size, resize, rescale, and normalize properties', 'test Perceiver image processor with numpy array inputs for batched and single image encoding', 'test Perceiver image processor with PIL Image inputs for batched and single image encoding', 'test Perceiver image processor with PyTorch tensor inputs for batched and single image encoding', 'review the PerceiverImageProcessingTester class methods for preparing image processor dicts and expected output shapes', 'test the PerceiverModelTester class that generates configs and inputs for all Perceiver model variants', 'test the attention output shapes and counts for self-attention and cross-attention layers in Perceiver models', 'test saving and loading all Perceiver model variants with output equivalence verification', 'test that model forward passes produce deterministic outputs across repeated runs', 'test inference of the PerceiverForMaskedLM model on masked text tokens', 'test the PerceiverTokenizer to encode and decode multibyte Unicode characters like euro sign and accented letters', 'test the PerceiverTokenizer batch encoding with padding and PyTorch tensor output for multiple input texts', 'test saving and loading a PerceiverTokenizer with custom tokens and model max length settings', 'test the PerceiverTokenizer with max length truncation and padding for target text sequences', 'test the PerceiverTokenizer convert_tokens_to_string method with single character tokens and special tokens']
```

Usage

```
{'test_perceiver_image_processor_properties': 'test that PerceiverImageProcessingTester initializes with correct crop size, resize, rescale, and normalize properties', 'test_perceiver_numpy_image_processing': 'test Perceiver image processor with numpy array inputs for batched and single image encoding', 'test_perceiver_pil_image_processing': 'test Perceiver image processor with PIL Image inputs for batched and single image encoding', 'test_perceiver_pytorch_image_processing': 'test Perceiver image processor with PyTorch tensor inputs for batched and single image encoding', 'review_perceiver_image_processing_tester': 'review the PerceiverImageProcessingTester class methods for preparing image processor dicts and expected output shapes'}
```

## File: huggingface_transformers/tests/models/perceiver/test_modeling_perceiver.py

Prompts

```
['test that PerceiverImageProcessingTester initializes with correct crop size, resize, rescale, and normalize properties', 'test Perceiver image processor with numpy array inputs for batched and single image encoding', 'test Perceiver image processor with PIL Image inputs for batched and single image encoding', 'test Perceiver image processor with PyTorch tensor inputs for batched and single image encoding', 'review the PerceiverImageProcessingTester class methods for preparing image processor dicts and expected output shapes', 'test the PerceiverModelTester class that generates configs and inputs for all Perceiver model variants', 'test the attention output shapes and counts for self-attention and cross-attention layers in Perceiver models', 'test saving and loading all Perceiver model variants with output equivalence verification', 'test that model forward passes produce deterministic outputs across repeated runs', 'test inference of the PerceiverForMaskedLM model on masked text tokens', 'test the PerceiverTokenizer to encode and decode multibyte Unicode characters like euro sign and accented letters', 'test the PerceiverTokenizer batch encoding with padding and PyTorch tensor output for multiple input texts', 'test saving and loading a PerceiverTokenizer with custom tokens and model max length settings', 'test the PerceiverTokenizer with max length truncation and padding for target text sequences', 'test the PerceiverTokenizer convert_tokens_to_string method with single character tokens and special tokens']
```

Usage

```
{'test_PERceiverModelTester': 'test the PerceiverModelTester class that generates configs and inputs for all Perceiver model variants', 'test_attention_outputs': 'test the attention output shapes and counts for self-attention and cross-attention layers in Perceiver models', 'test_save_load': 'test saving and loading all Perceiver model variants with output equivalence verification', 'test_determinism': 'test that model forward passes produce deterministic outputs across repeated runs', 'test_inference_masked_lm': 'test inference of the PerceiverForMaskedLM model on masked text tokens'}
```

## File: huggingface_transformers/tests/models/perceiver/test_tokenization_perceiver.py

Prompts

```
['test that PerceiverImageProcessingTester initializes with correct crop size, resize, rescale, and normalize properties', 'test Perceiver image processor with numpy array inputs for batched and single image encoding', 'test Perceiver image processor with PIL Image inputs for batched and single image encoding', 'test Perceiver image processor with PyTorch tensor inputs for batched and single image encoding', 'review the PerceiverImageProcessingTester class methods for preparing image processor dicts and expected output shapes', 'test the PerceiverModelTester class that generates configs and inputs for all Perceiver model variants', 'test the attention output shapes and counts for self-attention and cross-attention layers in Perceiver models', 'test saving and loading all Perceiver model variants with output equivalence verification', 'test that model forward passes produce deterministic outputs across repeated runs', 'test inference of the PerceiverForMaskedLM model on masked text tokens', 'test the PerceiverTokenizer to encode and decode multibyte Unicode characters like euro sign and accented letters', 'test the PerceiverTokenizer batch encoding with padding and PyTorch tensor output for multiple input texts', 'test saving and loading a PerceiverTokenizer with custom tokens and model max length settings', 'test the PerceiverTokenizer with max length truncation and padding for target text sequences', 'test the PerceiverTokenizer convert_tokens_to_string method with single character tokens and special tokens']
```

Usage

```
{'test_multibyte_tokenization': 'test the PerceiverTokenizer to encode and decode multibyte Unicode characters like euro sign and accented letters', 'test_batch_encoding': 'test the PerceiverTokenizer batch encoding with padding and PyTorch tensor output for multiple input texts', 'test_save_load_tokenizer': 'test saving and loading a PerceiverTokenizer with custom tokens and model max length settings', 'test_max_length_truncation': 'test the PerceiverTokenizer with max length truncation and padding for target text sequences', 'test_convert_tokens_to_string': 'test the PerceiverTokenizer convert_tokens_to_string method with single character tokens and special tokens'}
```


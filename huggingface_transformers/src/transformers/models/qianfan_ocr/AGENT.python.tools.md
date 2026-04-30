# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/qianfan_ocr/modeling_qianfan_ocr.py

Prompts

```
['create a QianfanOCRForConditionalGeneration model for OCR text recognition from images', 'build a QianfanOCRVisionModel vision encoder that extracts image features using transformer layers', 'run QianfanOCRForConditionalGeneration forward pass with pixel values and input IDs to generate OCR text', 'extract image features from QianfanOCRModel using get_image_features with vision feature layer selection', 'configure QianfanOCRVisionLayer with attention, MLP, layer normalization, and stochastic depth drop paths', 'create a QianfanOCRConfig with vision and text sub-configs for conditional generation', 'build a QianfanOCRVisionModel with stochastic depth layers and mean pooling output', 'configure QianfanOCRVisionLayer with attention, MLP, and drop path rate for transformer encoding', 'process images and text with QianfanOCRProcessor replacing image placeholders with token sequences', 'create a QianfanOCRProcessor instance with image_processor and tokenizer for OCR text-image processing', 'call the QianfanOCRProcessor to process images and interleaved text with image placeholders into tokenized input', 'insert media placeholders by replacing <image> tokens with image token sequences in interleaved text prompts', 'get the number of multimodal tokens for given image sizes including BOI, EOI, and sequence tokens', 'get the combined model input names from tokenizer and image_processor for QianfanOCRProcessor']
```

Usage

```
{'create_qianfan_ocr_model': 'create a QianfanOCRForConditionalGeneration model for OCR text recognition from images', 'build_vision_encoder': 'build a QianfanOCRVisionModel vision encoder that extracts image features using transformer layers', 'run_ocr_inference': 'run QianfanOCRForConditionalGeneration forward pass with pixel values and input IDs to generate OCR text', 'extract_image_features': 'extract image features from QianfanOCRModel using get_image_features with vision feature layer selection', 'configure_vision_transformer': 'configure QianfanOCRVisionLayer with attention, MLP, layer normalization, and stochastic depth drop paths'}
```

## File: huggingface_transformers/src/transformers/models/qianfan_ocr/modular_qianfan_ocr.py

Prompts

```
['create a QianfanOCRForConditionalGeneration model for OCR text recognition from images', 'build a QianfanOCRVisionModel vision encoder that extracts image features using transformer layers', 'run QianfanOCRForConditionalGeneration forward pass with pixel values and input IDs to generate OCR text', 'extract image features from QianfanOCRModel using get_image_features with vision feature layer selection', 'configure QianfanOCRVisionLayer with attention, MLP, layer normalization, and stochastic depth drop paths', 'create a QianfanOCRConfig with vision and text sub-configs for conditional generation', 'build a QianfanOCRVisionModel with stochastic depth layers and mean pooling output', 'configure QianfanOCRVisionLayer with attention, MLP, and drop path rate for transformer encoding', 'process images and text with QianfanOCRProcessor replacing image placeholders with token sequences', 'create a QianfanOCRProcessor instance with image_processor and tokenizer for OCR text-image processing', 'call the QianfanOCRProcessor to process images and interleaved text with image placeholders into tokenized input', 'insert media placeholders by replacing <image> tokens with image token sequences in interleaved text prompts', 'get the number of multimodal tokens for given image sizes including BOI, EOI, and sequence tokens', 'get the combined model input names from tokenizer and image_processor for QianfanOCRProcessor']
```

Usage

```
{'create_ocr_config': 'create a QianfanOCRConfig with vision and text sub-configs for conditional generation', 'build_vision_model': 'build a QianfanOCRVisionModel with stochastic depth layers and mean pooling output', 'run_ocr_inference': 'run QianfanOCRForConditionalGeneration forward pass with pixel values to generate OCR text output', 'configure_vision_layers': 'configure QianfanOCRVisionLayer with attention, MLP, and drop path rate for transformer encoding', 'process_image_text': 'process images and text with QianfanOCRProcessor replacing image placeholders with token sequences'}
```

## File: huggingface_transformers/src/transformers/models/qianfan_ocr/processing_qianfan_ocr.py

Prompts

```
['create a QianfanOCRForConditionalGeneration model for OCR text recognition from images', 'build a QianfanOCRVisionModel vision encoder that extracts image features using transformer layers', 'run QianfanOCRForConditionalGeneration forward pass with pixel values and input IDs to generate OCR text', 'extract image features from QianfanOCRModel using get_image_features with vision feature layer selection', 'configure QianfanOCRVisionLayer with attention, MLP, layer normalization, and stochastic depth drop paths', 'create a QianfanOCRConfig with vision and text sub-configs for conditional generation', 'build a QianfanOCRVisionModel with stochastic depth layers and mean pooling output', 'configure QianfanOCRVisionLayer with attention, MLP, and drop path rate for transformer encoding', 'process images and text with QianfanOCRProcessor replacing image placeholders with token sequences', 'create a QianfanOCRProcessor instance with image_processor and tokenizer for OCR text-image processing', 'call the QianfanOCRProcessor to process images and interleaved text with image placeholders into tokenized input', 'insert media placeholders by replacing <image> tokens with image token sequences in interleaved text prompts', 'get the number of multimodal tokens for given image sizes including BOI, EOI, and sequence tokens', 'get the combined model input names from tokenizer and image_processor for QianfanOCRProcessor']
```

Usage

```
{'create_QianfanOCRProcessor': 'create a QianfanOCRProcessor instance with image_processor and tokenizer for OCR text-image processing', 'call_QianfanOCRProcessor': 'call the QianfanOCRProcessor to process images and interleaved text with image placeholders into tokenized input', 'insert_media_placeholders': 'insert media placeholders by replacing <image> tokens with image token sequences in interleaved text prompts', 'get_num_multimodal_tokens': 'get the number of multimodal tokens for given image sizes including BOI, EOI, and sequence tokens', 'get_model_input_names': 'get the combined model input names from tokenizer and image_processor for QianfanOCRProcessor'}
```


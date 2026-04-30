# Agent Python Tools

- repo: datalab-to/surya
- repo_uri: https://github.com/datalab-to/surya

## File: datalab-to_surya/surya/ocr_error/model/config.py

Prompts

```
['create a DistilBertConfig instance with custom dim, n_layers, and n_heads for the OCR error model', 'build a DistilBertOnnxConfig to define ONNX input schemas for batch and sequence axes', "test the ID2LABEL mapping that converts 0 to 'good' and 1 to 'bad' for OCR error classification", 'refactor the DistilBertConfig class to support additional dropout parameters for fine-tuning', 'review the DistilBertOnnxConfig inputs property that returns dynamic axis mappings for ONNX export', 'build a DistilBertModel with DistilBertConfig for sequence encoding', 'create a DistilBertForSequenceClassification model for OCR error classification', 'run the Transformer encoder with attention masks and head masks for hidden state extraction', 'test MultiHeadSelfAttention with query, key, value tensors and causal masking', 'refactor DistilBertFlashAttention2 to use flash attention for padded sequence handling']
```

Usage

```
{'create_DistilBertConfig': 'create a DistilBertConfig instance with custom dim, n_layers, and n_heads for the OCR error model', 'build_DistilBertOnnxConfig': 'build a DistilBertOnnxConfig to define ONNX input schemas for batch and sequence axes', 'test_ID2LABEL': "test the ID2LABEL mapping that converts 0 to 'good' and 1 to 'bad' for OCR error classification", 'refactor_DistilBertConfig': 'refactor the DistilBertConfig class to support additional dropout parameters for fine-tuning', 'review_DistilBertOnnxConfig_inputs': 'review the DistilBertOnnxConfig inputs property that returns dynamic axis mappings for ONNX export'}
```

## File: datalab-to_surya/surya/ocr_error/model/encoder.py

Prompts

```
['create a DistilBertConfig instance with custom dim, n_layers, and n_heads for the OCR error model', 'build a DistilBertOnnxConfig to define ONNX input schemas for batch and sequence axes', "test the ID2LABEL mapping that converts 0 to 'good' and 1 to 'bad' for OCR error classification", 'refactor the DistilBertConfig class to support additional dropout parameters for fine-tuning', 'review the DistilBertOnnxConfig inputs property that returns dynamic axis mappings for ONNX export', 'build a DistilBertModel with DistilBertConfig for sequence encoding', 'create a DistilBertForSequenceClassification model for OCR error classification', 'run the Transformer encoder with attention masks and head masks for hidden state extraction', 'test MultiHeadSelfAttention with query, key, value tensors and causal masking', 'refactor DistilBertFlashAttention2 to use flash attention for padded sequence handling']
```

Usage

```
{'build_distilbert_model': 'build a DistilBertModel with DistilBertConfig for sequence encoding', 'create_sequence_classifier': 'create a DistilBertForSequenceClassification model for OCR error classification', 'run_transformer_encoder': 'run the Transformer encoder with attention masks and head masks for hidden state extraction', 'test_multi_head_attention': 'test MultiHeadSelfAttention with query, key, value tensors and causal masking', 'refactor_flash_attention': 'refactor DistilBertFlashAttention2 to use flash attention for padded sequence handling'}
```


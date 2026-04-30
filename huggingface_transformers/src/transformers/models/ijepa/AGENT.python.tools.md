# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/ijepa/convert_ijepa_to_hf.py

Prompts

```
['convert an IJEPA checkpoint from the original Facebook repository to HuggingFace transformers format', 'run the IJEPA conversion CLI tool to download and convert a model checkpoint to HuggingFace format', 'load a converted IJEPA model from a local directory using IJepaModel.from_pretrained', 'verify IJEPA model conversion by checking output logits against expected values on a test image', 'push a converted IJEPA model and image processor to the Hugging Face Hub', 'create an IJepaModel instance with IJepaConfig for self-supervised masked image modeling', 'build an IJepaForImageClassification model with a linear classifier head on top of IJepa embeddings', 'run a forward pass through IJepaModel with pixel values and optional boolean masked positions', 'test IJepaEmbeddings position encoding interpolation for higher resolution input images', 'review the IJepaSelfAttention class implementing multi-head self-attention with QKV linear projections', 'create IJepaEmbeddings with IJepaConfig and optional use_mask_token for patch embeddings with positional encoding', 'create IJepaModel with IJepaConfig and optional add_pooling_layer and use_mask_token parameters', 'create IJepaForImageClassification with IJepaConfig for image classification using masked image modeling', 'run IJepaModel forward pass with pixel_values, optional bool_masked_pos and interpolate_pos_encoding', 'run IJepaForImageClassification forward pass with pixel_values, optional labels and interpolate_pos_encoding']
```

Usage

```
{'convert_ijepa_checkpoint': 'convert an IJEPA checkpoint from the original Facebook repository to HuggingFace transformers format', 'run_ijepa_conversion_cli': 'run the IJEPA conversion CLI tool to download and convert a model checkpoint to HuggingFace format', 'load_ijepa_model_from_converted_checkpoint': 'load a converted IJEPA model from a local directory using IJepaModel.from_pretrained', 'verify_ijepa_conversion_logits': 'verify IJEPA model conversion by checking output logits against expected values on a test image', 'push_converted_ijepa_to_hub': 'push a converted IJEPA model and image processor to the Hugging Face Hub'}
```

## File: huggingface_transformers/src/transformers/models/ijepa/modeling_ijepa.py

Prompts

```
['convert an IJEPA checkpoint from the original Facebook repository to HuggingFace transformers format', 'run the IJEPA conversion CLI tool to download and convert a model checkpoint to HuggingFace format', 'load a converted IJEPA model from a local directory using IJepaModel.from_pretrained', 'verify IJEPA model conversion by checking output logits against expected values on a test image', 'push a converted IJEPA model and image processor to the Hugging Face Hub', 'create an IJepaModel instance with IJepaConfig for self-supervised masked image modeling', 'build an IJepaForImageClassification model with a linear classifier head on top of IJepa embeddings', 'run a forward pass through IJepaModel with pixel values and optional boolean masked positions', 'test IJepaEmbeddings position encoding interpolation for higher resolution input images', 'review the IJepaSelfAttention class implementing multi-head self-attention with QKV linear projections', 'create IJepaEmbeddings with IJepaConfig and optional use_mask_token for patch embeddings with positional encoding', 'create IJepaModel with IJepaConfig and optional add_pooling_layer and use_mask_token parameters', 'create IJepaForImageClassification with IJepaConfig for image classification using masked image modeling', 'run IJepaModel forward pass with pixel_values, optional bool_masked_pos and interpolate_pos_encoding', 'run IJepaForImageClassification forward pass with pixel_values, optional labels and interpolate_pos_encoding']
```

Usage

```
{'create_ijepa_model': 'create an IJepaModel instance with IJepaConfig for self-supervised masked image modeling', 'build_ijepa_classification_head': 'build an IJepaForImageClassification model with a linear classifier head on top of IJepa embeddings', 'run_ijepa_forward_pass': 'run a forward pass through IJepaModel with pixel values and optional boolean masked positions', 'test_ijepa_position_encoding_interpolation': 'test IJepaEmbeddings position encoding interpolation for higher resolution input images', 'review_ijepa_attention_mechanism': 'review the IJepaSelfAttention class implementing multi-head self-attention with QKV linear projections'}
```

## File: huggingface_transformers/src/transformers/models/ijepa/modular_ijepa.py

Prompts

```
['convert an IJEPA checkpoint from the original Facebook repository to HuggingFace transformers format', 'run the IJEPA conversion CLI tool to download and convert a model checkpoint to HuggingFace format', 'load a converted IJEPA model from a local directory using IJepaModel.from_pretrained', 'verify IJEPA model conversion by checking output logits against expected values on a test image', 'push a converted IJEPA model and image processor to the Hugging Face Hub', 'create an IJepaModel instance with IJepaConfig for self-supervised masked image modeling', 'build an IJepaForImageClassification model with a linear classifier head on top of IJepa embeddings', 'run a forward pass through IJepaModel with pixel values and optional boolean masked positions', 'test IJepaEmbeddings position encoding interpolation for higher resolution input images', 'review the IJepaSelfAttention class implementing multi-head self-attention with QKV linear projections', 'create IJepaEmbeddings with IJepaConfig and optional use_mask_token for patch embeddings with positional encoding', 'create IJepaModel with IJepaConfig and optional add_pooling_layer and use_mask_token parameters', 'create IJepaForImageClassification with IJepaConfig for image classification using masked image modeling', 'run IJepaModel forward pass with pixel_values, optional bool_masked_pos and interpolate_pos_encoding', 'run IJepaForImageClassification forward pass with pixel_values, optional labels and interpolate_pos_encoding']
```

Usage

```
{'create_IJepaEmbeddings': 'create IJepaEmbeddings with IJepaConfig and optional use_mask_token for patch embeddings with positional encoding', 'create_IJepaModel': 'create IJepaModel with IJepaConfig and optional add_pooling_layer and use_mask_token parameters', 'create_IJepaForImageClassification': 'create IJepaForImageClassification with IJepaConfig for image classification using masked image modeling', 'run_IJepaModel_forward': 'run IJepaModel forward pass with pixel_values, optional bool_masked_pos and interpolate_pos_encoding', 'run_IJepaForImageClassification_forward': 'run IJepaForImageClassification forward pass with pixel_values, optional labels and interpolate_pos_encoding'}
```


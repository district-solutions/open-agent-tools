# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/table_transformer/convert_table_transformer_to_hf.py

Prompts

```
['convert a Microsoft Table Transformer checkpoint to HuggingFace TableTransformerForObjectDetection format and verify output', 'rename a single key in a PyTorch state dict from the original checkpoint name to the HuggingFace name', 'rename backbone convolutional encoder keys from the original checkpoint to the HuggingFace conv_encoder structure', 'split PyTorch MultiHeadAttention in_proj_weight and in_proj_bias into separate q_proj, k_proj, v_proj matrices', 'resize a PIL image to a target max dimension of 800 for detection or 1000 for structure recognition', 'create a mapping of state dict key names from the original Table Transformer to the HuggingFace model structure', 'run the Table Transformer checkpoint conversion script via argparse CLI with checkpoint URL and output path', 'verify the converted model produces expected logits and bounding box shapes on a sample image', 'create a TableTransformerForObjectDetection model for detecting tables in images with bounding boxes', 'build a TableTransformerModel encoder-decoder to extract hidden states from table images', 'run object detection inference with TableTransformerForObjectDetection to get class logits and predicted bounding boxes', 'train TableTransformerForObjectDetection by passing pixel values and labels to compute classification and bounding box losses', 'build a TableTransformerMLPPredictionHead multi-layer perceptron to predict normalized bounding box coordinates']
```

Usage

```
{'convert_table_transformer_checkpoint': 'convert a Microsoft Table Transformer checkpoint to HuggingFace TableTransformerForObjectDetection format and verify output', 'rename_key': 'rename a single key in a PyTorch state dict from the original checkpoint name to the HuggingFace name', 'rename_backbone_keys': 'rename backbone convolutional encoder keys from the original checkpoint to the HuggingFace conv_encoder structure', 'read_in_q_k_v': 'split PyTorch MultiHeadAttention in_proj_weight and in_proj_bias into separate q_proj, k_proj, v_proj matrices', 'resize': 'resize a PIL image to a target max dimension of 800 for detection or 1000 for structure recognition'}
```

## File: huggingface_transformers/src/transformers/models/table_transformer/convert_table_transformer_to_hf_no_timm.py

Prompts

```
['convert a Microsoft Table Transformer checkpoint to HuggingFace TableTransformerForObjectDetection format and verify output', 'rename a single key in a PyTorch state dict from the original checkpoint name to the HuggingFace name', 'rename backbone convolutional encoder keys from the original checkpoint to the HuggingFace conv_encoder structure', 'split PyTorch MultiHeadAttention in_proj_weight and in_proj_bias into separate q_proj, k_proj, v_proj matrices', 'resize a PIL image to a target max dimension of 800 for detection or 1000 for structure recognition', 'create a mapping of state dict key names from the original Table Transformer to the HuggingFace model structure', 'run the Table Transformer checkpoint conversion script via argparse CLI with checkpoint URL and output path', 'verify the converted model produces expected logits and bounding box shapes on a sample image', 'create a TableTransformerForObjectDetection model for detecting tables in images with bounding boxes', 'build a TableTransformerModel encoder-decoder to extract hidden states from table images', 'run object detection inference with TableTransformerForObjectDetection to get class logits and predicted bounding boxes', 'train TableTransformerForObjectDetection by passing pixel values and labels to compute classification and bounding box losses', 'build a TableTransformerMLPPredictionHead multi-layer perceptron to predict normalized bounding box coordinates']
```

Usage

```
{'convert_table_transformer_checkpoint': 'convert a Microsoft Table Transformer checkpoint to HuggingFace DETR format and save locally', 'create_rename_keys': 'create a mapping of state dict key names from the original Table Transformer to the HuggingFace model structure', 'read_in_q_k_v': 'split concatenated query-key-value projection weights into separate projection layers for encoder and decoder', 'run_conversion_cli': 'run the Table Transformer checkpoint conversion script via argparse CLI with checkpoint URL and output path', 'verify_conversion_output': 'verify the converted model produces expected logits and bounding box shapes on a sample image'}
```

## File: huggingface_transformers/src/transformers/models/table_transformer/modeling_table_transformer.py

Prompts

```
['convert a Microsoft Table Transformer checkpoint to HuggingFace TableTransformerForObjectDetection format and verify output', 'rename a single key in a PyTorch state dict from the original checkpoint name to the HuggingFace name', 'rename backbone convolutional encoder keys from the original checkpoint to the HuggingFace conv_encoder structure', 'split PyTorch MultiHeadAttention in_proj_weight and in_proj_bias into separate q_proj, k_proj, v_proj matrices', 'resize a PIL image to a target max dimension of 800 for detection or 1000 for structure recognition', 'create a mapping of state dict key names from the original Table Transformer to the HuggingFace model structure', 'run the Table Transformer checkpoint conversion script via argparse CLI with checkpoint URL and output path', 'verify the converted model produces expected logits and bounding box shapes on a sample image', 'create a TableTransformerForObjectDetection model for detecting tables in images with bounding boxes', 'build a TableTransformerModel encoder-decoder to extract hidden states from table images', 'run object detection inference with TableTransformerForObjectDetection to get class logits and predicted bounding boxes', 'train TableTransformerForObjectDetection by passing pixel values and labels to compute classification and bounding box losses', 'build a TableTransformerMLPPredictionHead multi-layer perceptron to predict normalized bounding box coordinates']
```

Usage

```
{'create_table_detection_model': 'create a TableTransformerForObjectDetection model for detecting tables in images with bounding boxes', 'build_table_transformer_encoder_decoder': 'build a TableTransformerModel encoder-decoder to extract hidden states from table images', 'run_object_detection_inference': 'run object detection inference with TableTransformerForObjectDetection to get class logits and predicted bounding boxes', 'train_table_detection_with_labels': 'train TableTransformerForObjectDetection by passing pixel values and labels to compute classification and bounding box losses', 'build_mlp_prediction_head': 'build a TableTransformerMLPPredictionHead multi-layer perceptron to predict normalized bounding box coordinates'}
```


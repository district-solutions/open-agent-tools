# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/cvt/convert_cvt_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a Microsoft CvT PyTorch checkpoint to a HuggingFace transformers model', 'run the CvT checkpoint conversion CLI with model name, image size, and output path arguments', 'rename CvT embedding layer weights from original model format to HuggingFace format', 'rename CvT attention block weights including query, key, value projections and MLP layers', 'rename CvT cls_token weights from original model to HuggingFace stage format', 'create a CvT model for image classification using CvtForImageClassification with a pretrained config', 'build a CvT model forward pass with CvtModel to extract hidden states and CLS tokens from image tensors', 'test the CvtDropPath stochastic depth regularization module for reducing overfitting during training', 'review the CvtSelfAttention class that applies convolutional projections before multi-head attention', 'summarize the CvtEncoder module that stacks CvtStage blocks to process images through hierarchical convolutions']
```

Usage

```
{'convert_cvt_checkpoint': 'convert a Microsoft CvT PyTorch checkpoint to a HuggingFace transformers model', 'run_convert_cli_cvt': 'run the CvT checkpoint conversion CLI with model name, image size, and output path arguments', 'rename_embeddings_weights': 'rename CvT embedding layer weights from original model format to HuggingFace format', 'rename_attention_weights': 'rename CvT attention block weights including query, key, value projections and MLP layers', 'rename_cls_token_weights': 'rename CvT cls_token weights from original model to HuggingFace stage format'}
```

## File: huggingface_transformers/src/transformers/models/cvt/modeling_cvt.py

Prompts

```
['convert a Microsoft CvT PyTorch checkpoint to a HuggingFace transformers model', 'run the CvT checkpoint conversion CLI with model name, image size, and output path arguments', 'rename CvT embedding layer weights from original model format to HuggingFace format', 'rename CvT attention block weights including query, key, value projections and MLP layers', 'rename CvT cls_token weights from original model to HuggingFace stage format', 'create a CvT model for image classification using CvtForImageClassification with a pretrained config', 'build a CvT model forward pass with CvtModel to extract hidden states and CLS tokens from image tensors', 'test the CvtDropPath stochastic depth regularization module for reducing overfitting during training', 'review the CvtSelfAttention class that applies convolutional projections before multi-head attention', 'summarize the CvtEncoder module that stacks CvtStage blocks to process images through hierarchical convolutions']
```

Usage

```
{'create_cvT_image_classifier': 'create a CvT model for image classification using CvtForImageClassification with a pretrained config', 'build_cvT_model_forward': 'build a CvT model forward pass with CvtModel to extract hidden states and CLS tokens from image tensors', 'test_drop_path_regularization': 'test the CvtDropPath stochastic depth regularization module for reducing overfitting during training', 'review_cvT_self_attention': 'review the CvtSelfAttention class that applies convolutional projections before multi-head attention', 'summarize_cvT_encoder_stages': 'summarize the CvtEncoder module that stacks CvtStage blocks to process images through hierarchical convolutions'}
```


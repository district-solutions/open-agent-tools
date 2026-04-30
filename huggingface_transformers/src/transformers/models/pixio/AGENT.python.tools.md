# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/pixio/convert_pixio_to_pytorch.py

Prompts

```
['convert a Pixio checkpoint from the original Meta repository to HuggingFace PyTorch format', 'get the Pixio configuration for a given model name like pixio_vith16 or pixio_vitb16', 'create key renaming rules to map original Pixio checkpoint keys to HuggingFace PixioModel structure', 'split the combined qkv projection matrix into separate query, key, and value weight matrices', 'prepare a test image from the COCO dataset for verifying the converted model outputs', 'create a PixioModel for vision transformer image encoding with patch embeddings and positional encodings', 'run a forward pass on PixioModel to encode pixel values into hidden states with pooled output', 'build a PixioBackbone for multi-stage feature extraction suitable with DETR and MaskFormer', 'test the PixioSelfAttention class with query key value projections and configurable attention heads', 'review the PixioEncoder composed of stacked PixioLayers with self-attention and MLP blocks', 'test the PixioModel forward pass with pixel values and return BaseModelOutputWithPooling', 'summarize the PixioConfig parameters including hidden_size, num_layers, and n_cls_tokens', 'review the PixioEmbeddings class that constructs CLS tokens, position and patch embeddings']
```

Usage

```
{'convert_pixio_checkpoint': 'convert a Pixio checkpoint from the original Meta repository to HuggingFace PyTorch format', 'get_pixio_config': 'get the Pixio configuration for a given model name like pixio_vith16 or pixio_vitb16', 'create_rename_keys': 'create key renaming rules to map original Pixio checkpoint keys to HuggingFace PixioModel structure', 'read_in_q_k_v': 'split the combined qkv projection matrix into separate query, key, and value weight matrices', 'prepare_img': 'prepare a test image from the COCO dataset for verifying the converted model outputs'}
```

## File: huggingface_transformers/src/transformers/models/pixio/modeling_pixio.py

Prompts

```
['convert a Pixio checkpoint from the original Meta repository to HuggingFace PyTorch format', 'get the Pixio configuration for a given model name like pixio_vith16 or pixio_vitb16', 'create key renaming rules to map original Pixio checkpoint keys to HuggingFace PixioModel structure', 'split the combined qkv projection matrix into separate query, key, and value weight matrices', 'prepare a test image from the COCO dataset for verifying the converted model outputs', 'create a PixioModel for vision transformer image encoding with patch embeddings and positional encodings', 'run a forward pass on PixioModel to encode pixel values into hidden states with pooled output', 'build a PixioBackbone for multi-stage feature extraction suitable with DETR and MaskFormer', 'test the PixioSelfAttention class with query key value projections and configurable attention heads', 'review the PixioEncoder composed of stacked PixioLayers with self-attention and MLP blocks', 'test the PixioModel forward pass with pixel values and return BaseModelOutputWithPooling', 'summarize the PixioConfig parameters including hidden_size, num_layers, and n_cls_tokens', 'review the PixioEmbeddings class that constructs CLS tokens, position and patch embeddings']
```

Usage

```
{'create_pixio_model': 'create a PixioModel for vision transformer image encoding with patch embeddings and positional encodings', 'run_pixio_forward_pass': 'run a forward pass on PixioModel to encode pixel values into hidden states with pooled output', 'build_pixio_backbone': 'build a PixioBackbone for multi-stage feature extraction suitable with DETR and MaskFormer', 'test_pixio_attention': 'test the PixioSelfAttention class with query key value projections and configurable attention heads', 'review_pixio_encoder': 'review the PixioEncoder composed of stacked PixioLayers with self-attention and MLP blocks'}
```

## File: huggingface_transformers/src/transformers/models/pixio/modular_pixio.py

Prompts

```
['convert a Pixio checkpoint from the original Meta repository to HuggingFace PyTorch format', 'get the Pixio configuration for a given model name like pixio_vith16 or pixio_vitb16', 'create key renaming rules to map original Pixio checkpoint keys to HuggingFace PixioModel structure', 'split the combined qkv projection matrix into separate query, key, and value weight matrices', 'prepare a test image from the COCO dataset for verifying the converted model outputs', 'create a PixioModel for vision transformer image encoding with patch embeddings and positional encodings', 'run a forward pass on PixioModel to encode pixel values into hidden states with pooled output', 'build a PixioBackbone for multi-stage feature extraction suitable with DETR and MaskFormer', 'test the PixioSelfAttention class with query key value projections and configurable attention heads', 'review the PixioEncoder composed of stacked PixioLayers with self-attention and MLP blocks', 'test the PixioModel forward pass with pixel values and return BaseModelOutputWithPooling', 'summarize the PixioConfig parameters including hidden_size, num_layers, and n_cls_tokens', 'review the PixioEmbeddings class that constructs CLS tokens, position and patch embeddings']
```

Usage

```
{'create_pixio_model': 'create a Pixio model with the facebook/pixio-huge configuration for image feature extraction', 'build_pixio_backbone': 'build a Pixio backbone model for use with DETR and MaskFormer object detection frameworks', 'test_pixio_forward': 'test the PixioModel forward pass with pixel values and return BaseModelOutputWithPooling', 'summarize_pixio_config': 'summarize the PixioConfig parameters including hidden_size, num_layers, and n_cls_tokens', 'review_pixio_embeddings': 'review the PixioEmbeddings class that constructs CLS tokens, position and patch embeddings'}
```


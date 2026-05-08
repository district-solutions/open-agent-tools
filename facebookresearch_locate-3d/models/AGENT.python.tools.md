# Agent Python Tools

- repo: facebookresearch/locate-3d
- repo_uri: https://github.com/facebookresearch/locate-3d

## File: facebookresearch_locate-3d/models/encoder_3djepa.py

Prompts

```
['create an Encoder3DJEPA model with configurable input feature dimension and embedding size', 'load pretrained weights from a checkpoint file into the Encoder3DJEPA model', 'run a featurized scene dictionary through the Encoder3DJEPA forward pass to extract 3D features', 'review the Encoder3DJEPA initialization with RGB harmonic embedding and PointTransformerV3 configuration', 'summarize the Encoder3DJEPA forward pass that fuses CLIP and DINO features with RGB data', 'build a Locate3D model from a config object with encoder and decoder modules', 'run inference on a featurized scene dict and query text using the Locate3D model', 'load a Locate3D model state from a checkpoint file path', 'downsample a pointcloud dictionary to a specified number of points randomly', 'extract text from specific token indices using a HuggingFace tokenizer and offset mapping', 'build a Locate3DDecoder model with CLIP text encoder and transformer layers for 3D object localization', 'create a LearnedPosEmbeddings module to generate learned 3D positional embeddings from XYZ coordinates', 'create a DropPath module for stochastic depth regularization in transformer residual blocks', 'create a TransformerModule with query self-attention, cross-attention to point cloud features, and checkpointing support', 'create a BBoxHead module to predict 3D bounding boxes from query and point cloud features', 'build a PointTransformerV3 model for 3D point cloud segmentation with configurable encoder decoder stages', 'run the PointTransformerV3 forward pass on a batched point cloud data dictionary to get features', 'create serialized point cloud codes using z-order or hilbert space-filling curves for attention patches', 'create a spconv SparseConvTensor from point cloud features and grid coordinates for sparse convolution', 'review the SerializedAttention module to understand flash attention and relative positional encoding support']
```

Usage

```
{'create_encoder_3djepa': 'create an Encoder3DJEPA model with configurable input feature dimension and embedding size', 'load_weights_encoder': 'load pretrained weights from a checkpoint file into the Encoder3DJEPA model', 'forward_encoder_3djepa': 'run a featurized scene dictionary through the Encoder3DJEPA forward pass to extract 3D features', 'review_encoder_3djepa_init': 'review the Encoder3DJEPA initialization with RGB harmonic embedding and PointTransformerV3 configuration', 'summarize_encoder_3djepa_forward': 'summarize the Encoder3DJEPA forward pass that fuses CLIP and DINO features with RGB data'}
```

## File: facebookresearch_locate-3d/models/locate_3d.py

Prompts

```
['create an Encoder3DJEPA model with configurable input feature dimension and embedding size', 'load pretrained weights from a checkpoint file into the Encoder3DJEPA model', 'run a featurized scene dictionary through the Encoder3DJEPA forward pass to extract 3D features', 'review the Encoder3DJEPA initialization with RGB harmonic embedding and PointTransformerV3 configuration', 'summarize the Encoder3DJEPA forward pass that fuses CLIP and DINO features with RGB data', 'build a Locate3D model from a config object with encoder and decoder modules', 'run inference on a featurized scene dict and query text using the Locate3D model', 'load a Locate3D model state from a checkpoint file path', 'downsample a pointcloud dictionary to a specified number of points randomly', 'extract text from specific token indices using a HuggingFace tokenizer and offset mapping', 'build a Locate3DDecoder model with CLIP text encoder and transformer layers for 3D object localization', 'create a LearnedPosEmbeddings module to generate learned 3D positional embeddings from XYZ coordinates', 'create a DropPath module for stochastic depth regularization in transformer residual blocks', 'create a TransformerModule with query self-attention, cross-attention to point cloud features, and checkpointing support', 'create a BBoxHead module to predict 3D bounding boxes from query and point cloud features', 'build a PointTransformerV3 model for 3D point cloud segmentation with configurable encoder decoder stages', 'run the PointTransformerV3 forward pass on a batched point cloud data dictionary to get features', 'create serialized point cloud codes using z-order or hilbert space-filling curves for attention patches', 'create a spconv SparseConvTensor from point cloud features and grid coordinates for sparse convolution', 'review the SerializedAttention module to understand flash attention and relative positional encoding support']
```

Usage

```
{'build_locate3d_model': 'build a Locate3D model from a config object with encoder and decoder modules', 'run_locate3d_inference': 'run inference on a featurized scene dict and query text using the Locate3D model', 'load_locate3d_checkpoint': 'load a Locate3D model state from a checkpoint file path', 'downsample_pointcloud': 'downsample a pointcloud dictionary to a specified number of points randomly', 'extract_text_from_tokens': 'extract text from specific token indices using a HuggingFace tokenizer and offset mapping'}
```

## File: facebookresearch_locate-3d/models/locate_3d_decoder.py

Prompts

```
['create an Encoder3DJEPA model with configurable input feature dimension and embedding size', 'load pretrained weights from a checkpoint file into the Encoder3DJEPA model', 'run a featurized scene dictionary through the Encoder3DJEPA forward pass to extract 3D features', 'review the Encoder3DJEPA initialization with RGB harmonic embedding and PointTransformerV3 configuration', 'summarize the Encoder3DJEPA forward pass that fuses CLIP and DINO features with RGB data', 'build a Locate3D model from a config object with encoder and decoder modules', 'run inference on a featurized scene dict and query text using the Locate3D model', 'load a Locate3D model state from a checkpoint file path', 'downsample a pointcloud dictionary to a specified number of points randomly', 'extract text from specific token indices using a HuggingFace tokenizer and offset mapping', 'build a Locate3DDecoder model with CLIP text encoder and transformer layers for 3D object localization', 'create a LearnedPosEmbeddings module to generate learned 3D positional embeddings from XYZ coordinates', 'create a DropPath module for stochastic depth regularization in transformer residual blocks', 'create a TransformerModule with query self-attention, cross-attention to point cloud features, and checkpointing support', 'create a BBoxHead module to predict 3D bounding boxes from query and point cloud features', 'build a PointTransformerV3 model for 3D point cloud segmentation with configurable encoder decoder stages', 'run the PointTransformerV3 forward pass on a batched point cloud data dictionary to get features', 'create serialized point cloud codes using z-order or hilbert space-filling curves for attention patches', 'create a spconv SparseConvTensor from point cloud features and grid coordinates for sparse convolution', 'review the SerializedAttention module to understand flash attention and relative positional encoding support']
```

Usage

```
{'build_Locate3DDecoder': 'build a Locate3DDecoder model with CLIP text encoder and transformer layers for 3D object localization', 'create_LearnedPosEmbeddings': 'create a LearnedPosEmbeddings module to generate learned 3D positional embeddings from XYZ coordinates', 'create_DropPath': 'create a DropPath module for stochastic depth regularization in transformer residual blocks', 'create_TransformerModule': 'create a TransformerModule with query self-attention, cross-attention to point cloud features, and checkpointing support', 'create_BBoxHead': 'create a BBoxHead module to predict 3D bounding boxes from query and point cloud features'}
```

## File: facebookresearch_locate-3d/models/point_transformer_v3.py

Prompts

```
['create an Encoder3DJEPA model with configurable input feature dimension and embedding size', 'load pretrained weights from a checkpoint file into the Encoder3DJEPA model', 'run a featurized scene dictionary through the Encoder3DJEPA forward pass to extract 3D features', 'review the Encoder3DJEPA initialization with RGB harmonic embedding and PointTransformerV3 configuration', 'summarize the Encoder3DJEPA forward pass that fuses CLIP and DINO features with RGB data', 'build a Locate3D model from a config object with encoder and decoder modules', 'run inference on a featurized scene dict and query text using the Locate3D model', 'load a Locate3D model state from a checkpoint file path', 'downsample a pointcloud dictionary to a specified number of points randomly', 'extract text from specific token indices using a HuggingFace tokenizer and offset mapping', 'build a Locate3DDecoder model with CLIP text encoder and transformer layers for 3D object localization', 'create a LearnedPosEmbeddings module to generate learned 3D positional embeddings from XYZ coordinates', 'create a DropPath module for stochastic depth regularization in transformer residual blocks', 'create a TransformerModule with query self-attention, cross-attention to point cloud features, and checkpointing support', 'create a BBoxHead module to predict 3D bounding boxes from query and point cloud features', 'build a PointTransformerV3 model for 3D point cloud segmentation with configurable encoder decoder stages', 'run the PointTransformerV3 forward pass on a batched point cloud data dictionary to get features', 'create serialized point cloud codes using z-order or hilbert space-filling curves for attention patches', 'create a spconv SparseConvTensor from point cloud features and grid coordinates for sparse convolution', 'review the SerializedAttention module to understand flash attention and relative positional encoding support']
```

Usage

```
{'build_PointTransformerV3_model': 'build a PointTransformerV3 model for 3D point cloud segmentation with configurable encoder decoder stages', 'run_PointTransformerV3_forward': 'run the PointTransformerV3 forward pass on a batched point cloud data dictionary to get features', 'create_Point_serialization': 'create serialized point cloud codes using z-order or hilbert space-filling curves for attention patches', 'create_Point_sparsify': 'create a spconv SparseConvTensor from point cloud features and grid coordinates for sparse convolution', 'review_SerializedAttention_flash': 'review the SerializedAttention module to understand flash attention and relative positional encoding support'}
```


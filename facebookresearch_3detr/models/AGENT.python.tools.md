# Agent Python Tools

- repo: facebookresearch/3detr
- repo_uri: https://github.com/facebookresearch/3detr

## File: facebookresearch_3detr/models/helpers.py

Prompts

```
['create a GenericMLP with specified input, hidden, and output dimensions using linear layers', 'create a GenericMLP using 1D convolution layers instead of linear layers for feature processing', 'use BatchNormDim1Swap to apply batch normalization on tensors in HW x N x C format', 'clone a PyTorch module N times using get_clones to create a ModuleList of deep copies', 'initialize MLP weights using xavier_uniform initialization via the do_weight_init method', 'build a 3DETR model and BoxProcessor from args and dataset_config using build_3detr', 'build a vanilla or masked TransformerEncoder from args using build_encoder', 'build a TransformerDecoder with intermediate outputs from args using build_decoder', 'run the Model3DETR forward pass on point cloud inputs to get box predictions', 'compute 3D bounding box predictions from decoder box features using get_box_predictions', 'create sine positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'create fourier positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'build a PositionEmbeddingCoordsSine module with configurable temperature, normalization, and embedding type', 'test the get_sine_embeddings method with batched xyz coordinates and num_channels', 'test the get_fourier_embeddings method with batched xyz coordinates and gauss_B matrix', 'build a TransformerEncoder with cloned encoder layers, optional normalization, and configurable weight initialization', 'build a TransformerDecoder that returns intermediate activations from all decoding layers with optional attention weights', 'build a MaskedTransformerEncoder with per-layer masking radius and interim downsampling for 3D point cloud data', 'build a TransformerEncoderLayer with multihead self-attention, optional FFN, and pre or post layer normalization', 'build a TransformerDecoderLayer with self-attention, cross-attention, feedforward network, and positional embeddings']
```

Usage

```
{'create_GenericMLP': 'create a GenericMLP with specified input, hidden, and output dimensions using linear layers', 'create_GenericMLP_conv': 'create a GenericMLP using 1D convolution layers instead of linear layers for feature processing', 'use_BatchNormDim1Swap': 'use BatchNormDim1Swap to apply batch normalization on tensors in HW x N x C format', 'clone_module_with_get_clones': 'clone a PyTorch module N times using get_clones to create a ModuleList of deep copies', 'init_weights_xavier': 'initialize MLP weights using xavier_uniform initialization via the do_weight_init method'}
```

## File: facebookresearch_3detr/models/model_3detr.py

Prompts

```
['create a GenericMLP with specified input, hidden, and output dimensions using linear layers', 'create a GenericMLP using 1D convolution layers instead of linear layers for feature processing', 'use BatchNormDim1Swap to apply batch normalization on tensors in HW x N x C format', 'clone a PyTorch module N times using get_clones to create a ModuleList of deep copies', 'initialize MLP weights using xavier_uniform initialization via the do_weight_init method', 'build a 3DETR model and BoxProcessor from args and dataset_config using build_3detr', 'build a vanilla or masked TransformerEncoder from args using build_encoder', 'build a TransformerDecoder with intermediate outputs from args using build_decoder', 'run the Model3DETR forward pass on point cloud inputs to get box predictions', 'compute 3D bounding box predictions from decoder box features using get_box_predictions', 'create sine positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'create fourier positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'build a PositionEmbeddingCoordsSine module with configurable temperature, normalization, and embedding type', 'test the get_sine_embeddings method with batched xyz coordinates and num_channels', 'test the get_fourier_embeddings method with batched xyz coordinates and gauss_B matrix', 'build a TransformerEncoder with cloned encoder layers, optional normalization, and configurable weight initialization', 'build a TransformerDecoder that returns intermediate activations from all decoding layers with optional attention weights', 'build a MaskedTransformerEncoder with per-layer masking radius and interim downsampling for 3D point cloud data', 'build a TransformerEncoderLayer with multihead self-attention, optional FFN, and pre or post layer normalization', 'build a TransformerDecoderLayer with self-attention, cross-attention, feedforward network, and positional embeddings']
```

Usage

```
{'build_3detr_model': 'build a 3DETR model and BoxProcessor from args and dataset_config using build_3detr', 'build_encoder': 'build a vanilla or masked TransformerEncoder from args using build_encoder', 'build_decoder': 'build a TransformerDecoder with intermediate outputs from args using build_decoder', 'run_Model3DETR_forward': 'run the Model3DETR forward pass on point cloud inputs to get box predictions', 'compute_box_predictions': 'compute 3D bounding box predictions from decoder box features using get_box_predictions'}
```

## File: facebookresearch_3detr/models/position_embedding.py

Prompts

```
['create a GenericMLP with specified input, hidden, and output dimensions using linear layers', 'create a GenericMLP using 1D convolution layers instead of linear layers for feature processing', 'use BatchNormDim1Swap to apply batch normalization on tensors in HW x N x C format', 'clone a PyTorch module N times using get_clones to create a ModuleList of deep copies', 'initialize MLP weights using xavier_uniform initialization via the do_weight_init method', 'build a 3DETR model and BoxProcessor from args and dataset_config using build_3detr', 'build a vanilla or masked TransformerEncoder from args using build_encoder', 'build a TransformerDecoder with intermediate outputs from args using build_decoder', 'run the Model3DETR forward pass on point cloud inputs to get box predictions', 'compute 3D bounding box predictions from decoder box features using get_box_predictions', 'create sine positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'create fourier positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'build a PositionEmbeddingCoordsSine module with configurable temperature, normalization, and embedding type', 'test the get_sine_embeddings method with batched xyz coordinates and num_channels', 'test the get_fourier_embeddings method with batched xyz coordinates and gauss_B matrix', 'build a TransformerEncoder with cloned encoder layers, optional normalization, and configurable weight initialization', 'build a TransformerDecoder that returns intermediate activations from all decoding layers with optional attention weights', 'build a MaskedTransformerEncoder with per-layer masking radius and interim downsampling for 3D point cloud data', 'build a TransformerEncoderLayer with multihead self-attention, optional FFN, and pre or post layer normalization', 'build a TransformerDecoderLayer with self-attention, cross-attention, feedforward network, and positional embeddings']
```

Usage

```
{'create_sine_positional_embeddings': 'create sine positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'create_fourier_positional_embeddings': 'create fourier positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'build_position_embedding_module': 'build a PositionEmbeddingCoordsSine module with configurable temperature, normalization, and embedding type', 'test_sine_embeddings_method': 'test the get_sine_embeddings method with batched xyz coordinates and num_channels', 'test_fourier_embeddings_method': 'test the get_fourier_embeddings method with batched xyz coordinates and gauss_B matrix'}
```

## File: facebookresearch_3detr/models/transformer.py

Prompts

```
['create a GenericMLP with specified input, hidden, and output dimensions using linear layers', 'create a GenericMLP using 1D convolution layers instead of linear layers for feature processing', 'use BatchNormDim1Swap to apply batch normalization on tensors in HW x N x C format', 'clone a PyTorch module N times using get_clones to create a ModuleList of deep copies', 'initialize MLP weights using xavier_uniform initialization via the do_weight_init method', 'build a 3DETR model and BoxProcessor from args and dataset_config using build_3detr', 'build a vanilla or masked TransformerEncoder from args using build_encoder', 'build a TransformerDecoder with intermediate outputs from args using build_decoder', 'run the Model3DETR forward pass on point cloud inputs to get box predictions', 'compute 3D bounding box predictions from decoder box features using get_box_predictions', 'create sine positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'create fourier positional embeddings for 3D point cloud coordinates using PositionEmbeddingCoordsSine', 'build a PositionEmbeddingCoordsSine module with configurable temperature, normalization, and embedding type', 'test the get_sine_embeddings method with batched xyz coordinates and num_channels', 'test the get_fourier_embeddings method with batched xyz coordinates and gauss_B matrix', 'build a TransformerEncoder with cloned encoder layers, optional normalization, and configurable weight initialization', 'build a TransformerDecoder that returns intermediate activations from all decoding layers with optional attention weights', 'build a MaskedTransformerEncoder with per-layer masking radius and interim downsampling for 3D point cloud data', 'build a TransformerEncoderLayer with multihead self-attention, optional FFN, and pre or post layer normalization', 'build a TransformerDecoderLayer with self-attention, cross-attention, feedforward network, and positional embeddings']
```

Usage

```
{'build_TransformerEncoder': 'build a TransformerEncoder with cloned encoder layers, optional normalization, and configurable weight initialization', 'build_TransformerDecoder': 'build a TransformerDecoder that returns intermediate activations from all decoding layers with optional attention weights', 'build_MaskedTransformerEncoder': 'build a MaskedTransformerEncoder with per-layer masking radius and interim downsampling for 3D point cloud data', 'build_TransformerEncoderLayer': 'build a TransformerEncoderLayer with multihead self-attention, optional FFN, and pre or post layer normalization', 'build_TransformerDecoderLayer': 'build a TransformerDecoderLayer with self-attention, cross-attention, feedforward network, and positional embeddings'}
```


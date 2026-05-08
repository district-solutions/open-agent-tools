# Agent Python Tools

- repo: facebookresearch/ppuda
- repo_uri: https://github.com/facebookresearch/ppuda

## File: facebookresearch_ppuda/ppuda/ghn/decoder.py

Prompts

```
['build a ConvDecoder module to predict 1D-4D parameter tensors from node embeddings using convolutions', 'build an MLPDecoder module to predict 1D-4D parameter tensors from node embeddings using an MLP', 'run the ConvDecoder forward pass with node embeddings and optional class prediction', 'run the MLPDecoder forward pass with node embeddings and optional class prediction', 'review the ConvDecoder class_layer_predictor for class prediction on graph neural network outputs', 'build a GatedGNN model with 32 input features and default traversal steps', 'build a GatedGNN model with virtual edges enabled for multi-hop message passing', 'build a GatedGNN model with multiple forward and backward graph traversal steps', 'run the GatedGNN forward pass with node features, edges, and graph indices', 'review the GatedGNN forward method that performs node feature propagation via GRUCell', 'get a PyTorch activation layer module from a string name like relu or sigmoid', 'create a ShapeEncoder module with hidden size, num classes, and max shape dimensions', 'convert a 1D, 2D, or 3D tensor shape tuple into a 4D shape tuple', 'run the ShapeEncoder forward pass to add shape embeddings to input tensor x', 'review the ShapeEncoder class and its channel and spatial lookup embedding logic', 'build a PyTorch MLP with configurable hidden layers and activation functions using the MLP class', 'create an MLP with custom hidden layer sizes and a specific activation function like sigmoid', 'run the MLP forward pass on input tensor data to get predictions through the sequential layers', 'test the MLP class initialization with various hidden layer configurations and activation types', 'review the MLP forward method that handles tuple inputs and passes data through the sequential network', 'load a pretrained GHN-1 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a pretrained GHN-2 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a GHN model from an arbitrary checkpoint file using GHN.load', 'predict neural network parameters by passing a network through GHN forward pass', 'wrap a GHN model in DataParallel for multi-GPU training using ghn_parallel']
```

Usage

```
{'build_ConvDecoder': 'build a ConvDecoder module to predict 1D-4D parameter tensors from node embeddings using convolutions', 'build_MLPDecoder': 'build an MLPDecoder module to predict 1D-4D parameter tensors from node embeddings using an MLP', 'run_ConvDecoder_forward': 'run the ConvDecoder forward pass with node embeddings and optional class prediction', 'run_MLPDecoder_forward': 'run the MLPDecoder forward pass with node embeddings and optional class prediction', 'review_ConvDecoder_class_prediction': 'review the ConvDecoder class_layer_predictor for class prediction on graph neural network outputs'}
```

## File: facebookresearch_ppuda/ppuda/ghn/gatedgnn.py

Prompts

```
['build a ConvDecoder module to predict 1D-4D parameter tensors from node embeddings using convolutions', 'build an MLPDecoder module to predict 1D-4D parameter tensors from node embeddings using an MLP', 'run the ConvDecoder forward pass with node embeddings and optional class prediction', 'run the MLPDecoder forward pass with node embeddings and optional class prediction', 'review the ConvDecoder class_layer_predictor for class prediction on graph neural network outputs', 'build a GatedGNN model with 32 input features and default traversal steps', 'build a GatedGNN model with virtual edges enabled for multi-hop message passing', 'build a GatedGNN model with multiple forward and backward graph traversal steps', 'run the GatedGNN forward pass with node features, edges, and graph indices', 'review the GatedGNN forward method that performs node feature propagation via GRUCell', 'get a PyTorch activation layer module from a string name like relu or sigmoid', 'create a ShapeEncoder module with hidden size, num classes, and max shape dimensions', 'convert a 1D, 2D, or 3D tensor shape tuple into a 4D shape tuple', 'run the ShapeEncoder forward pass to add shape embeddings to input tensor x', 'review the ShapeEncoder class and its channel and spatial lookup embedding logic', 'build a PyTorch MLP with configurable hidden layers and activation functions using the MLP class', 'create an MLP with custom hidden layer sizes and a specific activation function like sigmoid', 'run the MLP forward pass on input tensor data to get predictions through the sequential layers', 'test the MLP class initialization with various hidden layer configurations and activation types', 'review the MLP forward method that handles tuple inputs and passes data through the sequential network', 'load a pretrained GHN-1 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a pretrained GHN-2 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a GHN model from an arbitrary checkpoint file using GHN.load', 'predict neural network parameters by passing a network through GHN forward pass', 'wrap a GHN model in DataParallel for multi-GPU training using ghn_parallel']
```

Usage

```
{'build_gatedgnn_model': 'build a GatedGNN model with 32 input features and default traversal steps', 'build_gatedgnn_with_virtual_edges': 'build a GatedGNN model with virtual edges enabled for multi-hop message passing', 'build_gatedgnn_multi_step': 'build a GatedGNN model with multiple forward and backward graph traversal steps', 'run_gatedgnn_forward': 'run the GatedGNN forward pass with node features, edges, and graph indices', 'review_gatedgnn_forward': 'review the GatedGNN forward method that performs node feature propagation via GRUCell'}
```

## File: facebookresearch_ppuda/ppuda/ghn/layers.py

Prompts

```
['build a ConvDecoder module to predict 1D-4D parameter tensors from node embeddings using convolutions', 'build an MLPDecoder module to predict 1D-4D parameter tensors from node embeddings using an MLP', 'run the ConvDecoder forward pass with node embeddings and optional class prediction', 'run the MLPDecoder forward pass with node embeddings and optional class prediction', 'review the ConvDecoder class_layer_predictor for class prediction on graph neural network outputs', 'build a GatedGNN model with 32 input features and default traversal steps', 'build a GatedGNN model with virtual edges enabled for multi-hop message passing', 'build a GatedGNN model with multiple forward and backward graph traversal steps', 'run the GatedGNN forward pass with node features, edges, and graph indices', 'review the GatedGNN forward method that performs node feature propagation via GRUCell', 'get a PyTorch activation layer module from a string name like relu or sigmoid', 'create a ShapeEncoder module with hidden size, num classes, and max shape dimensions', 'convert a 1D, 2D, or 3D tensor shape tuple into a 4D shape tuple', 'run the ShapeEncoder forward pass to add shape embeddings to input tensor x', 'review the ShapeEncoder class and its channel and spatial lookup embedding logic', 'build a PyTorch MLP with configurable hidden layers and activation functions using the MLP class', 'create an MLP with custom hidden layer sizes and a specific activation function like sigmoid', 'run the MLP forward pass on input tensor data to get predictions through the sequential layers', 'test the MLP class initialization with various hidden layer configurations and activation types', 'review the MLP forward method that handles tuple inputs and passes data through the sequential network', 'load a pretrained GHN-1 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a pretrained GHN-2 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a GHN model from an arbitrary checkpoint file using GHN.load', 'predict neural network parameters by passing a network through GHN forward pass', 'wrap a GHN model in DataParallel for multi-GPU training using ghn_parallel']
```

Usage

```
{'get_activation': 'get a PyTorch activation layer module from a string name like relu or sigmoid', 'create_ShapeEncoder': 'create a ShapeEncoder module with hidden size, num classes, and max shape dimensions', 'tensor_shape_to_4d': 'convert a 1D, 2D, or 3D tensor shape tuple into a 4D shape tuple', 'ShapeEncoder_forward': 'run the ShapeEncoder forward pass to add shape embeddings to input tensor x', 'review_ShapeEncoder': 'review the ShapeEncoder class and its channel and spatial lookup embedding logic'}
```

## File: facebookresearch_ppuda/ppuda/ghn/mlp.py

Prompts

```
['build a ConvDecoder module to predict 1D-4D parameter tensors from node embeddings using convolutions', 'build an MLPDecoder module to predict 1D-4D parameter tensors from node embeddings using an MLP', 'run the ConvDecoder forward pass with node embeddings and optional class prediction', 'run the MLPDecoder forward pass with node embeddings and optional class prediction', 'review the ConvDecoder class_layer_predictor for class prediction on graph neural network outputs', 'build a GatedGNN model with 32 input features and default traversal steps', 'build a GatedGNN model with virtual edges enabled for multi-hop message passing', 'build a GatedGNN model with multiple forward and backward graph traversal steps', 'run the GatedGNN forward pass with node features, edges, and graph indices', 'review the GatedGNN forward method that performs node feature propagation via GRUCell', 'get a PyTorch activation layer module from a string name like relu or sigmoid', 'create a ShapeEncoder module with hidden size, num classes, and max shape dimensions', 'convert a 1D, 2D, or 3D tensor shape tuple into a 4D shape tuple', 'run the ShapeEncoder forward pass to add shape embeddings to input tensor x', 'review the ShapeEncoder class and its channel and spatial lookup embedding logic', 'build a PyTorch MLP with configurable hidden layers and activation functions using the MLP class', 'create an MLP with custom hidden layer sizes and a specific activation function like sigmoid', 'run the MLP forward pass on input tensor data to get predictions through the sequential layers', 'test the MLP class initialization with various hidden layer configurations and activation types', 'review the MLP forward method that handles tuple inputs and passes data through the sequential network', 'load a pretrained GHN-1 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a pretrained GHN-2 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a GHN model from an arbitrary checkpoint file using GHN.load', 'predict neural network parameters by passing a network through GHN forward pass', 'wrap a GHN model in DataParallel for multi-GPU training using ghn_parallel']
```

Usage

```
{'build_MLP': 'build a PyTorch MLP with configurable hidden layers and activation functions using the MLP class', 'create_MLP_custom_layers': 'create an MLP with custom hidden layer sizes and a specific activation function like sigmoid', 'run_MLP_forward': 'run the MLP forward pass on input tensor data to get predictions through the sequential layers', 'test_MLP_initialization': 'test the MLP class initialization with various hidden layer configurations and activation types', 'review_MLP_forward': 'review the MLP forward method that handles tuple inputs and passes data through the sequential network'}
```

## File: facebookresearch_ppuda/ppuda/ghn/nn.py

Prompts

```
['build a ConvDecoder module to predict 1D-4D parameter tensors from node embeddings using convolutions', 'build an MLPDecoder module to predict 1D-4D parameter tensors from node embeddings using an MLP', 'run the ConvDecoder forward pass with node embeddings and optional class prediction', 'run the MLPDecoder forward pass with node embeddings and optional class prediction', 'review the ConvDecoder class_layer_predictor for class prediction on graph neural network outputs', 'build a GatedGNN model with 32 input features and default traversal steps', 'build a GatedGNN model with virtual edges enabled for multi-hop message passing', 'build a GatedGNN model with multiple forward and backward graph traversal steps', 'run the GatedGNN forward pass with node features, edges, and graph indices', 'review the GatedGNN forward method that performs node feature propagation via GRUCell', 'get a PyTorch activation layer module from a string name like relu or sigmoid', 'create a ShapeEncoder module with hidden size, num classes, and max shape dimensions', 'convert a 1D, 2D, or 3D tensor shape tuple into a 4D shape tuple', 'run the ShapeEncoder forward pass to add shape embeddings to input tensor x', 'review the ShapeEncoder class and its channel and spatial lookup embedding logic', 'build a PyTorch MLP with configurable hidden layers and activation functions using the MLP class', 'create an MLP with custom hidden layer sizes and a specific activation function like sigmoid', 'run the MLP forward pass on input tensor data to get predictions through the sequential layers', 'test the MLP class initialization with various hidden layer configurations and activation types', 'review the MLP forward method that handles tuple inputs and passes data through the sequential network', 'load a pretrained GHN-1 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a pretrained GHN-2 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load a GHN model from an arbitrary checkpoint file using GHN.load', 'predict neural network parameters by passing a network through GHN forward pass', 'wrap a GHN model in DataParallel for multi-GPU training using ghn_parallel']
```

Usage

```
{'load_GHN1': 'load a pretrained GHN-1 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load_GHN2': 'load a pretrained GHN-2 Graph HyperNetwork model for ImageNet or CIFAR-10', 'load_GHN_checkpoint': 'load a GHN model from an arbitrary checkpoint file using GHN.load', 'predict_GHN_forward': 'predict neural network parameters by passing a network through GHN forward pass', 'parallelize_ghn': 'wrap a GHN model in DataParallel for multi-GPU training using ghn_parallel'}
```


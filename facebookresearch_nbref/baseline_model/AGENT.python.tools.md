# Agent Python Tools

- repo: facebookresearch/nbref
- repo_uri: https://github.com/facebookresearch/nbref

## File: facebookresearch_nbref/baseline_model/config.py

Prompts

```
['build an argparse parser for vulnerability detection with GNN model hyperparameters and training controls', 'build an argparse parser for code similarity checking with contrastive learning parameters', 'build an argparse parser for transformer tree model training with distributed GPU support', 'build an argparse parser for dumping trace data from golden C samples', 'review the get_arg_parser function that returns task-specific argparse parsers by title', 'run the tree transformer model training pipeline on assembly graph data with GNN encoding', 'create a collate function that batches torchtext Dataset examples by preprocessing and processing each field', 'load or preprocess a single graph from pickle cache or compute it via preprocessing_graph', 'load and preprocess multiple assembly graphs in batch using cached pickle files', 'test the trained tree transformer model on a test dataset and report loss and accuracy', 'run the tree transformer model on multiple GPUs for assembly to AST translation', 'load and preprocess assembly graphs from cached pickle files or compute them on demand', 'load a single graph from disk or preprocess source elements and edge elements into a graph', 'create a collate function that batches dataset examples by preprocessing fields into tensors', 'generate argument tuples for parallel graph loading across multiple GPU processes', 'run the vulnerability detection model training on assembly graph datasets using GNN and transformer encoder', 'run preprocessing on a batch of DGL graphs to pad nodes and batch them for GPU inference', 'build a vulnerability detection model combining a GNN graph neural network with a transformer encoder', 'train the vulnerability detection model on assembly code graphs with cross entropy or BCE loss', 'evaluate the trained vulnerability detection model on validation data and report precision recall metrics']
```

Usage

```
{'build_vulnerability_detection_parser': 'build an argparse parser for vulnerability detection with GNN model hyperparameters and training controls', 'build_similarity_check_parser': 'build an argparse parser for code similarity checking with contrastive learning parameters', 'build_trf_tree_parser': 'build an argparse parser for transformer tree model training with distributed GPU support', 'build_dump_trace_parser': 'build an argparse parser for dumping trace data from golden C samples', 'review_get_arg_parser': 'review the get_arg_parser function that returns task-specific argparse parsers by title'}
```

## File: facebookresearch_nbref/baseline_model/run_tree_transformer.py

Prompts

```
['build an argparse parser for vulnerability detection with GNN model hyperparameters and training controls', 'build an argparse parser for code similarity checking with contrastive learning parameters', 'build an argparse parser for transformer tree model training with distributed GPU support', 'build an argparse parser for dumping trace data from golden C samples', 'review the get_arg_parser function that returns task-specific argparse parsers by title', 'run the tree transformer model training pipeline on assembly graph data with GNN encoding', 'create a collate function that batches torchtext Dataset examples by preprocessing and processing each field', 'load or preprocess a single graph from pickle cache or compute it via preprocessing_graph', 'load and preprocess multiple assembly graphs in batch using cached pickle files', 'test the trained tree transformer model on a test dataset and report loss and accuracy', 'run the tree transformer model on multiple GPUs for assembly to AST translation', 'load and preprocess assembly graphs from cached pickle files or compute them on demand', 'load a single graph from disk or preprocess source elements and edge elements into a graph', 'create a collate function that batches dataset examples by preprocessing fields into tensors', 'generate argument tuples for parallel graph loading across multiple GPU processes', 'run the vulnerability detection model training on assembly graph datasets using GNN and transformer encoder', 'run preprocessing on a batch of DGL graphs to pad nodes and batch them for GPU inference', 'build a vulnerability detection model combining a GNN graph neural network with a transformer encoder', 'train the vulnerability detection model on assembly code graphs with cross entropy or BCE loss', 'evaluate the trained vulnerability detection model on validation data and report precision recall metrics']
```

Usage

```
{'run_tree_transformer_training': 'run the tree transformer model training pipeline on assembly graph data with GNN encoding', 'create_text_data_collator': 'create a collate function that batches torchtext Dataset examples by preprocessing and processing each field', 'load_graph_with_cache': 'load or preprocess a single graph from pickle cache or compute it via preprocessing_graph', 'load_graphs_batch': 'load and preprocess multiple assembly graphs in batch using cached pickle files', 'test_tree_transformer_model': 'test the trained tree transformer model on a test dataset and report loss and accuracy'}
```

## File: facebookresearch_nbref/baseline_model/run_tree_transformer_multi_gpu.py

Prompts

```
['build an argparse parser for vulnerability detection with GNN model hyperparameters and training controls', 'build an argparse parser for code similarity checking with contrastive learning parameters', 'build an argparse parser for transformer tree model training with distributed GPU support', 'build an argparse parser for dumping trace data from golden C samples', 'review the get_arg_parser function that returns task-specific argparse parsers by title', 'run the tree transformer model training pipeline on assembly graph data with GNN encoding', 'create a collate function that batches torchtext Dataset examples by preprocessing and processing each field', 'load or preprocess a single graph from pickle cache or compute it via preprocessing_graph', 'load and preprocess multiple assembly graphs in batch using cached pickle files', 'test the trained tree transformer model on a test dataset and report loss and accuracy', 'run the tree transformer model on multiple GPUs for assembly to AST translation', 'load and preprocess assembly graphs from cached pickle files or compute them on demand', 'load a single graph from disk or preprocess source elements and edge elements into a graph', 'create a collate function that batches dataset examples by preprocessing fields into tensors', 'generate argument tuples for parallel graph loading across multiple GPU processes', 'run the vulnerability detection model training on assembly graph datasets using GNN and transformer encoder', 'run preprocessing on a batch of DGL graphs to pad nodes and batch them for GPU inference', 'build a vulnerability detection model combining a GNN graph neural network with a transformer encoder', 'train the vulnerability detection model on assembly code graphs with cross entropy or BCE loss', 'evaluate the trained vulnerability detection model on validation data and report precision recall metrics']
```

Usage

```
{'run_tree_transformer_multi_gpu': 'run the tree transformer model on multiple GPUs for assembly to AST translation', 'load_graphs': 'load and preprocess assembly graphs from cached pickle files or compute them on demand', 'load_graph': 'load a single graph from disk or preprocess source elements and edge elements into a graph', 'text_data_collator': 'create a collate function that batches dataset examples by preprocessing fields into tensors', 'gen_args_multi_gpu': 'generate argument tuples for parallel graph loading across multiple GPU processes'}
```

## File: facebookresearch_nbref/baseline_model/run_vulnerability_detection.py

Prompts

```
['build an argparse parser for vulnerability detection with GNN model hyperparameters and training controls', 'build an argparse parser for code similarity checking with contrastive learning parameters', 'build an argparse parser for transformer tree model training with distributed GPU support', 'build an argparse parser for dumping trace data from golden C samples', 'review the get_arg_parser function that returns task-specific argparse parsers by title', 'run the tree transformer model training pipeline on assembly graph data with GNN encoding', 'create a collate function that batches torchtext Dataset examples by preprocessing and processing each field', 'load or preprocess a single graph from pickle cache or compute it via preprocessing_graph', 'load and preprocess multiple assembly graphs in batch using cached pickle files', 'test the trained tree transformer model on a test dataset and report loss and accuracy', 'run the tree transformer model on multiple GPUs for assembly to AST translation', 'load and preprocess assembly graphs from cached pickle files or compute them on demand', 'load a single graph from disk or preprocess source elements and edge elements into a graph', 'create a collate function that batches dataset examples by preprocessing fields into tensors', 'generate argument tuples for parallel graph loading across multiple GPU processes', 'run the vulnerability detection model training on assembly graph datasets using GNN and transformer encoder', 'run preprocessing on a batch of DGL graphs to pad nodes and batch them for GPU inference', 'build a vulnerability detection model combining a GNN graph neural network with a transformer encoder', 'train the vulnerability detection model on assembly code graphs with cross entropy or BCE loss', 'evaluate the trained vulnerability detection model on validation data and report precision recall metrics']
```

Usage

```
{'run_vulnerability_detection_training': 'run the vulnerability detection model training on assembly graph datasets using GNN and transformer encoder', 'run_preprocessing_batch': 'run preprocessing on a batch of DGL graphs to pad nodes and batch them for GPU inference', 'build_vul_detect_model': 'build a vulnerability detection model combining a GNN graph neural network with a transformer encoder', 'train_vul_detection_model': 'train the vulnerability detection model on assembly code graphs with cross entropy or BCE loss', 'evaluate_vul_detection_model': 'evaluate the trained vulnerability detection model on validation data and report precision recall metrics'}
```


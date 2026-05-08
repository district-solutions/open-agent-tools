# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/examples/gnn_cost_model/compiler_gym_dataset.py

Prompts

```
['create a CompilerGymDataset from a SQLite database filepath for supervised learning on compiler graphs', 'build a DGL graph from a NetworkX graph using process_networkx_graph with a vocabulary mapping', 'convert a NetworkX graph to a DGL graph with node and edge attributes using fast_networkx_to_dgl', 'update NetworkX graph node or edge features with vocabulary indices using update_graph_with_vocab', 'query the CompilerGym SQLite database for observations and states using get_observation_from_table', 'build a GNNEncoder with GatedGraphConv layers for graph neural network cost model prediction', 'run the GNNEncoder forward pass on a DGL graph to predict rewards and graph embeddings', 'test the GNNEncoder get_loss method with scaled labels using the R2D2 loss function', 'refactor the GNNEncoder featurize_nodes method to support custom node feature extraction beyond text embeddings', 'summarize the rescale and inv_rescale functions that transform reward values using R2D2-style scaling', 'run the GNN cost model training on an LLVM-IR transition dataset with configurable epochs and batch size', 'run the dataset_looper function to iterate over a data loader and compute training or validation loss', 'run the train function to execute multiple epochs of GNN model training with train and dev splits', 'run download_and_unpack_database to fetch a tar archive by URL, verify its SHA256, and unpack it to cache', 'run the main entry point to download datasets, build a GNNEncoder model, and start training via absl flags', 'test the GNN cost model training by running a smoke test with a small dataset on CPU', 'run the GNN cost model training main function with custom dataset size, batch size, and epoch flags', 'test the training output by capturing stdout and asserting epoch training messages appear', 'test the GNN cost model CLI entry point using absl flags and sys.argv configuration', 'review the train_test module smoke test that validates GNN cost model training with pytest']
```

Usage

```
{'create_CompilerGymDataset': 'create a CompilerGymDataset from a SQLite database filepath for supervised learning on compiler graphs', 'build_dgl_graph_from_networkx': 'build a DGL graph from a NetworkX graph using process_networkx_graph with a vocabulary mapping', 'convert_networkx_to_dgl': 'convert a NetworkX graph to a DGL graph with node and edge attributes using fast_networkx_to_dgl', 'update_graph_features_with_vocab': 'update NetworkX graph node or edge features with vocabulary indices using update_graph_with_vocab', 'query_compiler_gym_database': 'query the CompilerGym SQLite database for observations and states using get_observation_from_table'}
```

## File: facebookresearch_compilergym/examples/gnn_cost_model/model.py

Prompts

```
['create a CompilerGymDataset from a SQLite database filepath for supervised learning on compiler graphs', 'build a DGL graph from a NetworkX graph using process_networkx_graph with a vocabulary mapping', 'convert a NetworkX graph to a DGL graph with node and edge attributes using fast_networkx_to_dgl', 'update NetworkX graph node or edge features with vocabulary indices using update_graph_with_vocab', 'query the CompilerGym SQLite database for observations and states using get_observation_from_table', 'build a GNNEncoder with GatedGraphConv layers for graph neural network cost model prediction', 'run the GNNEncoder forward pass on a DGL graph to predict rewards and graph embeddings', 'test the GNNEncoder get_loss method with scaled labels using the R2D2 loss function', 'refactor the GNNEncoder featurize_nodes method to support custom node feature extraction beyond text embeddings', 'summarize the rescale and inv_rescale functions that transform reward values using R2D2-style scaling', 'run the GNN cost model training on an LLVM-IR transition dataset with configurable epochs and batch size', 'run the dataset_looper function to iterate over a data loader and compute training or validation loss', 'run the train function to execute multiple epochs of GNN model training with train and dev splits', 'run download_and_unpack_database to fetch a tar archive by URL, verify its SHA256, and unpack it to cache', 'run the main entry point to download datasets, build a GNNEncoder model, and start training via absl flags', 'test the GNN cost model training by running a smoke test with a small dataset on CPU', 'run the GNN cost model training main function with custom dataset size, batch size, and epoch flags', 'test the training output by capturing stdout and asserting epoch training messages appear', 'test the GNN cost model CLI entry point using absl flags and sys.argv configuration', 'review the train_test module smoke test that validates GNN cost model training with pytest']
```

Usage

```
{'build_gnn_encoder': 'build a GNNEncoder with GatedGraphConv layers for graph neural network cost model prediction', 'run_gnn_forward': 'run the GNNEncoder forward pass on a DGL graph to predict rewards and graph embeddings', 'test_gnn_loss': 'test the GNNEncoder get_loss method with scaled labels using the R2D2 loss function', 'refactor_featurize_nodes': 'refactor the GNNEncoder featurize_nodes method to support custom node feature extraction beyond text embeddings', 'summarize_rescale_functions': 'summarize the rescale and inv_rescale functions that transform reward values using R2D2-style scaling'}
```

## File: facebookresearch_compilergym/examples/gnn_cost_model/train.py

Prompts

```
['create a CompilerGymDataset from a SQLite database filepath for supervised learning on compiler graphs', 'build a DGL graph from a NetworkX graph using process_networkx_graph with a vocabulary mapping', 'convert a NetworkX graph to a DGL graph with node and edge attributes using fast_networkx_to_dgl', 'update NetworkX graph node or edge features with vocabulary indices using update_graph_with_vocab', 'query the CompilerGym SQLite database for observations and states using get_observation_from_table', 'build a GNNEncoder with GatedGraphConv layers for graph neural network cost model prediction', 'run the GNNEncoder forward pass on a DGL graph to predict rewards and graph embeddings', 'test the GNNEncoder get_loss method with scaled labels using the R2D2 loss function', 'refactor the GNNEncoder featurize_nodes method to support custom node feature extraction beyond text embeddings', 'summarize the rescale and inv_rescale functions that transform reward values using R2D2-style scaling', 'run the GNN cost model training on an LLVM-IR transition dataset with configurable epochs and batch size', 'run the dataset_looper function to iterate over a data loader and compute training or validation loss', 'run the train function to execute multiple epochs of GNN model training with train and dev splits', 'run download_and_unpack_database to fetch a tar archive by URL, verify its SHA256, and unpack it to cache', 'run the main entry point to download datasets, build a GNNEncoder model, and start training via absl flags', 'test the GNN cost model training by running a smoke test with a small dataset on CPU', 'run the GNN cost model training main function with custom dataset size, batch size, and epoch flags', 'test the training output by capturing stdout and asserting epoch training messages appear', 'test the GNN cost model CLI entry point using absl flags and sys.argv configuration', 'review the train_test module smoke test that validates GNN cost model training with pytest']
```

Usage

```
{'run_gnn_cost_model_training': 'run the GNN cost model training on an LLVM-IR transition dataset with configurable epochs and batch size', 'run_dataset_looper': 'run the dataset_looper function to iterate over a data loader and compute training or validation loss', 'run_train_function': 'run the train function to execute multiple epochs of GNN model training with train and dev splits', 'run_download_and_unpack_database': 'run download_and_unpack_database to fetch a tar archive by URL, verify its SHA256, and unpack it to cache', 'run_main_entry': 'run the main entry point to download datasets, build a GNNEncoder model, and start training via absl flags'}
```

## File: facebookresearch_compilergym/examples/gnn_cost_model/train_test.py

Prompts

```
['create a CompilerGymDataset from a SQLite database filepath for supervised learning on compiler graphs', 'build a DGL graph from a NetworkX graph using process_networkx_graph with a vocabulary mapping', 'convert a NetworkX graph to a DGL graph with node and edge attributes using fast_networkx_to_dgl', 'update NetworkX graph node or edge features with vocabulary indices using update_graph_with_vocab', 'query the CompilerGym SQLite database for observations and states using get_observation_from_table', 'build a GNNEncoder with GatedGraphConv layers for graph neural network cost model prediction', 'run the GNNEncoder forward pass on a DGL graph to predict rewards and graph embeddings', 'test the GNNEncoder get_loss method with scaled labels using the R2D2 loss function', 'refactor the GNNEncoder featurize_nodes method to support custom node feature extraction beyond text embeddings', 'summarize the rescale and inv_rescale functions that transform reward values using R2D2-style scaling', 'run the GNN cost model training on an LLVM-IR transition dataset with configurable epochs and batch size', 'run the dataset_looper function to iterate over a data loader and compute training or validation loss', 'run the train function to execute multiple epochs of GNN model training with train and dev splits', 'run download_and_unpack_database to fetch a tar archive by URL, verify its SHA256, and unpack it to cache', 'run the main entry point to download datasets, build a GNNEncoder model, and start training via absl flags', 'test the GNN cost model training by running a smoke test with a small dataset on CPU', 'run the GNN cost model training main function with custom dataset size, batch size, and epoch flags', 'test the training output by capturing stdout and asserting epoch training messages appear', 'test the GNN cost model CLI entry point using absl flags and sys.argv configuration', 'review the train_test module smoke test that validates GNN cost model training with pytest']
```

Usage

```
{'test_run_train_smoke_test': 'test the GNN cost model training by running a smoke test with a small dataset on CPU', 'run_train_with_flags': 'run the GNN cost model training main function with custom dataset size, batch size, and epoch flags', 'test_capture_output_training': 'test the training output by capturing stdout and asserting epoch training messages appear', 'test_gnn_cost_model_cli': 'test the GNN cost model CLI entry point using absl flags and sys.argv configuration', 'review_train_test_smoke': 'review the train_test module smoke test that validates GNN cost model training with pytest'}
```


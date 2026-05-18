# Agent Python Tools

- repo: facebookresearch/neural-rewriter
- repo_uri: https://github.com/facebookresearch/neural-rewriter

## File: facebookresearch_neural-rewriter/src/models/modules/HalideInputEncoder.py

Prompts

```
['create an InputEmbedding module to compute terminal node embeddings using character-level LSTM encoding', 'build a TreeLSTM module to embed each node in a tree structure for expression simplification', 'test the TreeLSTM calc_root method to compute LSTM gate outputs from child hidden and cell states', 'run calc_embedding on tree managers to compute embeddings for all terminal and non-terminal nodes in trees', 'review the update_embedding method to selectively recompute embeddings for changed nodes in tree managers', 'build a SeqLSTM module to embed DAG job scheduling inputs as a sequence using PyTorch LSTM', 'build a DagLSTM module to embed DAG structures using custom LSTM gates with parent-child aggregation', 'test the SeqLSTM calc_embedding method to compute node states from a batch of dag_managers', 'test the DagLSTM calc_embedding method to compute node states by traversing the DAG top-down from the root', 'test the DagLSTM update_embedding method to recompute node states for a subset of nodes specified by init_queues', 'create an MLPModel with configurable num_layers, input_size, hidden_size, output_size, and dropout_rate', 'build a forward pass through the MLPModel by passing input tensors to the model', 'test the MLPModel initialization with custom num_layers, hidden_size, and output_size parameters', 'refactor the MLPModel to add a custom activation function after the output layer', 'review the MLPModel dropout configuration and how dropout_rate is applied to the network', 'build a bidirectional LSTM encoder module to embed VRP input sequences as hidden state representations', 'create a SeqLSTM instance with configurable hidden size, embedding size, num layers, and dropout rate', 'review the SeqLSTM calc_embedding method and its zero-padding logic for variable-length route sequences', 'test the SeqLSTM encoder with cuda flag enabled to verify GPU tensor conversion and forward pass']
```

Usage

```
{'create_InputEmbedding': 'create an InputEmbedding module to compute terminal node embeddings using character-level LSTM encoding', 'build_TreeLSTM': 'build a TreeLSTM module to embed each node in a tree structure for expression simplification', 'test_calc_root': 'test the TreeLSTM calc_root method to compute LSTM gate outputs from child hidden and cell states', 'run_calc_embedding': 'run calc_embedding on tree managers to compute embeddings for all terminal and non-terminal nodes in trees', 'review_update_embedding': 'review the update_embedding method to selectively recompute embeddings for changed nodes in tree managers'}
```

## File: facebookresearch_neural-rewriter/src/models/modules/jspInputEncoder.py

Prompts

```
['create an InputEmbedding module to compute terminal node embeddings using character-level LSTM encoding', 'build a TreeLSTM module to embed each node in a tree structure for expression simplification', 'test the TreeLSTM calc_root method to compute LSTM gate outputs from child hidden and cell states', 'run calc_embedding on tree managers to compute embeddings for all terminal and non-terminal nodes in trees', 'review the update_embedding method to selectively recompute embeddings for changed nodes in tree managers', 'build a SeqLSTM module to embed DAG job scheduling inputs as a sequence using PyTorch LSTM', 'build a DagLSTM module to embed DAG structures using custom LSTM gates with parent-child aggregation', 'test the SeqLSTM calc_embedding method to compute node states from a batch of dag_managers', 'test the DagLSTM calc_embedding method to compute node states by traversing the DAG top-down from the root', 'test the DagLSTM update_embedding method to recompute node states for a subset of nodes specified by init_queues', 'create an MLPModel with configurable num_layers, input_size, hidden_size, output_size, and dropout_rate', 'build a forward pass through the MLPModel by passing input tensors to the model', 'test the MLPModel initialization with custom num_layers, hidden_size, and output_size parameters', 'refactor the MLPModel to add a custom activation function after the output layer', 'review the MLPModel dropout configuration and how dropout_rate is applied to the network', 'build a bidirectional LSTM encoder module to embed VRP input sequences as hidden state representations', 'create a SeqLSTM instance with configurable hidden size, embedding size, num layers, and dropout rate', 'review the SeqLSTM calc_embedding method and its zero-padding logic for variable-length route sequences', 'test the SeqLSTM encoder with cuda flag enabled to verify GPU tensor conversion and forward pass']
```

Usage

```
{'build_SeqLSTM_sequence_embeddings': 'build a SeqLSTM module to embed DAG job scheduling inputs as a sequence using PyTorch LSTM', 'build_DagLSTM_dag_embeddings': 'build a DagLSTM module to embed DAG structures using custom LSTM gates with parent-child aggregation', 'test_SeqLSTM_calc_embedding': 'test the SeqLSTM calc_embedding method to compute node states from a batch of dag_managers', 'test_DagLSTM_calc_embedding': 'test the DagLSTM calc_embedding method to compute node states by traversing the DAG top-down from the root', 'test_DagLSTM_update_embedding': 'test the DagLSTM update_embedding method to recompute node states for a subset of nodes specified by init_queues'}
```

## File: facebookresearch_neural-rewriter/src/models/modules/mlp.py

Prompts

```
['create an InputEmbedding module to compute terminal node embeddings using character-level LSTM encoding', 'build a TreeLSTM module to embed each node in a tree structure for expression simplification', 'test the TreeLSTM calc_root method to compute LSTM gate outputs from child hidden and cell states', 'run calc_embedding on tree managers to compute embeddings for all terminal and non-terminal nodes in trees', 'review the update_embedding method to selectively recompute embeddings for changed nodes in tree managers', 'build a SeqLSTM module to embed DAG job scheduling inputs as a sequence using PyTorch LSTM', 'build a DagLSTM module to embed DAG structures using custom LSTM gates with parent-child aggregation', 'test the SeqLSTM calc_embedding method to compute node states from a batch of dag_managers', 'test the DagLSTM calc_embedding method to compute node states by traversing the DAG top-down from the root', 'test the DagLSTM update_embedding method to recompute node states for a subset of nodes specified by init_queues', 'create an MLPModel with configurable num_layers, input_size, hidden_size, output_size, and dropout_rate', 'build a forward pass through the MLPModel by passing input tensors to the model', 'test the MLPModel initialization with custom num_layers, hidden_size, and output_size parameters', 'refactor the MLPModel to add a custom activation function after the output layer', 'review the MLPModel dropout configuration and how dropout_rate is applied to the network', 'build a bidirectional LSTM encoder module to embed VRP input sequences as hidden state representations', 'create a SeqLSTM instance with configurable hidden size, embedding size, num layers, and dropout rate', 'review the SeqLSTM calc_embedding method and its zero-padding logic for variable-length route sequences', 'test the SeqLSTM encoder with cuda flag enabled to verify GPU tensor conversion and forward pass']
```

Usage

```
{'create_mlp_model': 'create an MLPModel with configurable num_layers, input_size, hidden_size, output_size, and dropout_rate', 'build_mlp_forward_pass': 'build a forward pass through the MLPModel by passing input tensors to the model', 'test_mlpmodel_init': 'test the MLPModel initialization with custom num_layers, hidden_size, and output_size parameters', 'refactor_mlpmodel_activation': 'refactor the MLPModel to add a custom activation function after the output layer', 'review_mlpmodel_dropout': 'review the MLPModel dropout configuration and how dropout_rate is applied to the network'}
```

## File: facebookresearch_neural-rewriter/src/models/modules/vrpInputEncoder.py

Prompts

```
['create an InputEmbedding module to compute terminal node embeddings using character-level LSTM encoding', 'build a TreeLSTM module to embed each node in a tree structure for expression simplification', 'test the TreeLSTM calc_root method to compute LSTM gate outputs from child hidden and cell states', 'run calc_embedding on tree managers to compute embeddings for all terminal and non-terminal nodes in trees', 'review the update_embedding method to selectively recompute embeddings for changed nodes in tree managers', 'build a SeqLSTM module to embed DAG job scheduling inputs as a sequence using PyTorch LSTM', 'build a DagLSTM module to embed DAG structures using custom LSTM gates with parent-child aggregation', 'test the SeqLSTM calc_embedding method to compute node states from a batch of dag_managers', 'test the DagLSTM calc_embedding method to compute node states by traversing the DAG top-down from the root', 'test the DagLSTM update_embedding method to recompute node states for a subset of nodes specified by init_queues', 'create an MLPModel with configurable num_layers, input_size, hidden_size, output_size, and dropout_rate', 'build a forward pass through the MLPModel by passing input tensors to the model', 'test the MLPModel initialization with custom num_layers, hidden_size, and output_size parameters', 'refactor the MLPModel to add a custom activation function after the output layer', 'review the MLPModel dropout configuration and how dropout_rate is applied to the network', 'build a bidirectional LSTM encoder module to embed VRP input sequences as hidden state representations', 'create a SeqLSTM instance with configurable hidden size, embedding size, num layers, and dropout rate', 'review the SeqLSTM calc_embedding method and its zero-padding logic for variable-length route sequences', 'test the SeqLSTM encoder with cuda flag enabled to verify GPU tensor conversion and forward pass']
```

Usage

```
{'build_seqLSTM_encoder': 'build a bidirectional LSTM encoder module to embed VRP input sequences as hidden state representations', 'create_seqLSTM_instance': 'create a SeqLSTM instance with configurable hidden size, embedding size, num layers, and dropout rate', 'run_calc_embedding': 'run calc_embedding on a list of seq_managers to compute LSTM encoder outputs for each route sequence', 'review_seqLSTM_padding': 'review the SeqLSTM calc_embedding method and its zero-padding logic for variable-length route sequences', 'test_seqLSTM_cuda': 'test the SeqLSTM encoder with cuda flag enabled to verify GPU tensor conversion and forward pass'}
```


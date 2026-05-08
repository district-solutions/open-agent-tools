# Agent Python Tools

- repo: facebookresearch/hgnn
- repo_uri: https://github.com/facebookresearch/hgnn

## File: facebookresearch_hgnn/dataset/EthereumDataset.py

Prompts

```
['read weighted average Ether price from a JSON file and return a date-to-price dictionary', 'read Ether price data, sort chronologically, and truncate entries after a specified cutoff date', 'create an EthereumDataset instance for train, dev, or test split using price data and day splits', 'compute price features including normalized exact prices and up/down indicators for a date range', 'convert adjacency matrix and weight dictionaries to trimmed lists with max or random neighbor selection', 'build a NodeClassificationDataset instance that loads graph node classification data from pickle files', 'create a call to load_data to load and preprocess graph features, labels, and adjacency matrices', 'test the parse_index_file function to parse integer indices from a text file line by line', 'refactor preprocess_features to row-normalize a scipy sparse feature matrix for graph neural networks', 'review the sample_mask function that creates a boolean mask array from a list of indices', 'create a SyntheticDataset instance from pickled graph data files for train, dev, or test splits', 'get graph node features, adjacency matrix, weights, labels, and masks by index from the dataset', 'create a one-hot encoded vector for node degree values in the graph dataset', 'build adjacency matrices and normalized weights from graph edge lists with self connections', 'load a pickled graph dataset file for training, development, or testing splits']
```

Usage

```
{'read_ether_price': 'read weighted average Ether price from a JSON file and return a date-to-price dictionary', 'read_truncated_ether_price': 'read Ether price data, sort chronologically, and truncate entries after a specified cutoff date', 'EthereumDataset_init': 'create an EthereumDataset instance for train, dev, or test split using price data and day splits', 'EthereumDataset_get_price_feature': 'compute price features including normalized exact prices and up/down indicators for a date range', 'EthereumDataset_defaultdict2list': 'convert adjacency matrix and weight dictionaries to trimmed lists with max or random neighbor selection'}
```

## File: facebookresearch_hgnn/dataset/NodeClassificationDataset.py

Prompts

```
['read weighted average Ether price from a JSON file and return a date-to-price dictionary', 'read Ether price data, sort chronologically, and truncate entries after a specified cutoff date', 'create an EthereumDataset instance for train, dev, or test split using price data and day splits', 'compute price features including normalized exact prices and up/down indicators for a date range', 'convert adjacency matrix and weight dictionaries to trimmed lists with max or random neighbor selection', 'build a NodeClassificationDataset instance that loads graph node classification data from pickle files', 'create a call to load_data to load and preprocess graph features, labels, and adjacency matrices', 'test the parse_index_file function to parse integer indices from a text file line by line', 'refactor preprocess_features to row-normalize a scipy sparse feature matrix for graph neural networks', 'review the sample_mask function that creates a boolean mask array from a list of indices', 'create a SyntheticDataset instance from pickled graph data files for train, dev, or test splits', 'get graph node features, adjacency matrix, weights, labels, and masks by index from the dataset', 'create a one-hot encoded vector for node degree values in the graph dataset', 'build adjacency matrices and normalized weights from graph edge lists with self connections', 'load a pickled graph dataset file for training, development, or testing splits']
```

Usage

```
{'build_NodeClassificationDataset': 'build a NodeClassificationDataset instance that loads graph node classification data from pickle files', 'create_load_data': 'create a call to load_data to load and preprocess graph features, labels, and adjacency matrices', 'test_parse_index_file': 'test the parse_index_file function to parse integer indices from a text file line by line', 'refactor_preprocess_features': 'refactor preprocess_features to row-normalize a scipy sparse feature matrix for graph neural networks', 'review_sample_mask': 'review the sample_mask function that creates a boolean mask array from a list of indices'}
```

## File: facebookresearch_hgnn/dataset/SyntheticDataset.py

Prompts

```
['read weighted average Ether price from a JSON file and return a date-to-price dictionary', 'read Ether price data, sort chronologically, and truncate entries after a specified cutoff date', 'create an EthereumDataset instance for train, dev, or test split using price data and day splits', 'compute price features including normalized exact prices and up/down indicators for a date range', 'convert adjacency matrix and weight dictionaries to trimmed lists with max or random neighbor selection', 'build a NodeClassificationDataset instance that loads graph node classification data from pickle files', 'create a call to load_data to load and preprocess graph features, labels, and adjacency matrices', 'test the parse_index_file function to parse integer indices from a text file line by line', 'refactor preprocess_features to row-normalize a scipy sparse feature matrix for graph neural networks', 'review the sample_mask function that creates a boolean mask array from a list of indices', 'create a SyntheticDataset instance from pickled graph data files for train, dev, or test splits', 'get graph node features, adjacency matrix, weights, labels, and masks by index from the dataset', 'create a one-hot encoded vector for node degree values in the graph dataset', 'build adjacency matrices and normalized weights from graph edge lists with self connections', 'load a pickled graph dataset file for training, development, or testing splits']
```

Usage

```
{'create_synthetic_dataset': 'create a SyntheticDataset instance from pickled graph data files for train, dev, or test splits', 'getitem_graph_features': 'get graph node features, adjacency matrix, weights, labels, and masks by index from the dataset', 'one_hot_encode_degree': 'create a one-hot encoded vector for node degree values in the graph dataset', 'build_graph_adjacency': 'build adjacency matrices and normalized weights from graph edge lists with self connections', 'load_pickle_dataset': 'load a pickled graph dataset file for training, development, or testing splits'}
```


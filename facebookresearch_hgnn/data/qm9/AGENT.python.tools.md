# Agent Python Tools

- repo: facebookresearch/hgnn
- repo_uri: https://github.com/facebookresearch/hgnn

## File: facebookresearch_hgnn/data/qm9/get_data.py

Prompts

```
['download the QM9 gdb9 dataset from deepchem S3 and extract the tar.gz archive', 'create a function that reads gdb9.sdf.csv and returns a dictionary mapping molecule indices to property values', 'run the train validation test split of QM9 molecules using RDKit SDMolSupplier and split index JSON files', 'preprocess raw molecule data by converting SMILES strings to graph representations with node features and edges', 'load validation split indices from valid_idx_qm9.json and return a list of integer file indices', 'convert an RDKit molecule to nodes and edges for graph neural network input', 'get atom types, maximum valence, and number to atom mapping for a dataset', 'check if an RDKit molecule needs kekulization based on bond types', 'create a one-hot encoded list for a given index and length', 'map bond type strings to integers and integers back to RDKit bond types']
```

Usage

```
{'download_qm9_dataset': 'download the QM9 gdb9 dataset from deepchem S3 and extract the tar.gz archive', 'read_csv_properties': 'create a function that reads gdb9.sdf.csv and returns a dictionary mapping molecule indices to property values', 'split_train_valid_test': 'run the train validation test split of QM9 molecules using RDKit SDMolSupplier and split index JSON files', 'preprocess_molecules_to_graphs': 'preprocess raw molecule data by converting SMILES strings to graph representations with node features and edges', 'get_validation_indices': 'load validation split indices from valid_idx_qm9.json and return a list of integer file indices'}
```

## File: facebookresearch_hgnn/data/qm9/utils.py

Prompts

```
['download the QM9 gdb9 dataset from deepchem S3 and extract the tar.gz archive', 'create a function that reads gdb9.sdf.csv and returns a dictionary mapping molecule indices to property values', 'run the train validation test split of QM9 molecules using RDKit SDMolSupplier and split index JSON files', 'preprocess raw molecule data by converting SMILES strings to graph representations with node features and edges', 'load validation split indices from valid_idx_qm9.json and return a list of integer file indices', 'convert an RDKit molecule to nodes and edges for graph neural network input', 'get atom types, maximum valence, and number to atom mapping for a dataset', 'check if an RDKit molecule needs kekulization based on bond types', 'create a one-hot encoded list for a given index and length', 'map bond type strings to integers and integers back to RDKit bond types']
```

Usage

```
{'convert_mol_to_graph': 'convert an RDKit molecule to nodes and edges for graph neural network input', 'get_dataset_info': 'get atom types, maximum valence, and number to atom mapping for a dataset', 'check_kekulize_needed': 'check if an RDKit molecule needs kekulization based on bond types', 'create_onehot_encoding': 'create a one-hot encoded list for a given index and length', 'map_bond_types': 'map bond type strings to integers and integers back to RDKit bond types'}
```


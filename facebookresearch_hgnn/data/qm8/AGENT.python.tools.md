# Agent Python Tools

- repo: facebookresearch/hgnn
- repo_uri: https://github.com/facebookresearch/hgnn

## File: facebookresearch_hgnn/data/qm8/get_data.py

Prompts

```
['download the QM8 gdb8 dataset from DeepChem S3 and extract the tar.gz archive', 'create a function that reads qm8.sdf.csv and returns a dictionary mapping indices to molecular property lists', 'run the train valid test split of QM8 molecules using RDKit SDMolSupplier and JSON index files', 'preprocess raw molecular data by converting SMILES strings to graph representations with node features and edges', 'load validation split file indices from valid_idx_qm8.json and return a list of integer file indices', 'convert an RDKit molecule into a graph representation with nodes and edges for the QM8 dataset', 'check if an RDKit molecule needs Kekulization by inspecting its bond types', 'create a one-hot encoded list for a given index and total length', 'get atom types, maximum valence, and number-to-atom mappings for a molecular dataset', 'map between bond type strings and RDKit BondType enums using bond_dict and number_to_bond']
```

Usage

```
{'download_qm8_dataset': 'download the QM8 gdb8 dataset from DeepChem S3 and extract the tar.gz archive', 'read_csv_properties': 'create a function that reads qm8.sdf.csv and returns a dictionary mapping indices to molecular property lists', 'split_train_valid_test': 'run the train valid test split of QM8 molecules using RDKit SDMolSupplier and JSON index files', 'preprocess_molecules_to_graphs': 'preprocess raw molecular data by converting SMILES strings to graph representations with node features and edges', 'get_validation_indices': 'load validation split file indices from valid_idx_qm8.json and return a list of integer file indices'}
```

## File: facebookresearch_hgnn/data/qm8/utils.py

Prompts

```
['download the QM8 gdb8 dataset from DeepChem S3 and extract the tar.gz archive', 'create a function that reads qm8.sdf.csv and returns a dictionary mapping indices to molecular property lists', 'run the train valid test split of QM8 molecules using RDKit SDMolSupplier and JSON index files', 'preprocess raw molecular data by converting SMILES strings to graph representations with node features and edges', 'load validation split file indices from valid_idx_qm8.json and return a list of integer file indices', 'convert an RDKit molecule into a graph representation with nodes and edges for the QM8 dataset', 'check if an RDKit molecule needs Kekulization by inspecting its bond types', 'create a one-hot encoded list for a given index and total length', 'get atom types, maximum valence, and number-to-atom mappings for a molecular dataset', 'map between bond type strings and RDKit BondType enums using bond_dict and number_to_bond']
```

Usage

```
{'convert_molecule_to_graph': 'convert an RDKit molecule into a graph representation with nodes and edges for the QM8 dataset', 'check_kekulize_needed': 'check if an RDKit molecule needs Kekulization by inspecting its bond types', 'create_onehot_encoding': 'create a one-hot encoded list for a given index and total length', 'get_dataset_info': 'get atom types, maximum valence, and number-to-atom mappings for a molecular dataset', 'map_bond_types': 'map between bond type strings and RDKit BondType enums using bond_dict and number_to_bond'}
```


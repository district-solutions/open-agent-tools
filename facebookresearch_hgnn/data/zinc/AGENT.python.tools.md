# Agent Python Tools

- repo: facebookresearch/hgnn
- repo_uri: https://github.com/facebookresearch/hgnn

## File: facebookresearch_hgnn/data/zinc/get_data.py

Prompts

```
['run the script to download the ZINC 250k drugs CSV dataset from GitHub', 'run the dataset_split function to split ZINC molecules into train, valid, and test sets', 'run the preprocess function to convert SMILES strings into molecular graph representations', 'run the main pipeline to download, split, and preprocess the ZINC dataset into JSON files', 'refactor the download_file function to use requests instead of os.system wget', 'convert a SMILES string to molecular graph nodes and edges using to_graph', 'get atom types, maximum valence, and number-to-atom mappings for a dataset using dataset_info', 'create a one-hot encoded list for a given index and length using onehot', 'check if an RDKit molecule needs Kekulization based on bond types using need_kekulize', 'review the bond_dict and number_to_bond mappings for bond type conversions']
```

Usage

```
{'run_download_zinc_dataset': 'run the script to download the ZINC 250k drugs CSV dataset from GitHub', 'run_dataset_split': 'run the dataset_split function to split ZINC molecules into train, valid, and test sets', 'run_preprocess_smiles_to_graphs': 'run the preprocess function to convert SMILES strings into molecular graph representations', 'run_full_pipeline': 'run the main pipeline to download, split, and preprocess the ZINC dataset into JSON files', 'refactor_download_file': 'refactor the download_file function to use requests instead of os.system wget'}
```

## File: facebookresearch_hgnn/data/zinc/utils.py

Prompts

```
['run the script to download the ZINC 250k drugs CSV dataset from GitHub', 'run the dataset_split function to split ZINC molecules into train, valid, and test sets', 'run the preprocess function to convert SMILES strings into molecular graph representations', 'run the main pipeline to download, split, and preprocess the ZINC dataset into JSON files', 'refactor the download_file function to use requests instead of os.system wget', 'convert a SMILES string to molecular graph nodes and edges using to_graph', 'get atom types, maximum valence, and number-to-atom mappings for a dataset using dataset_info', 'create a one-hot encoded list for a given index and length using onehot', 'check if an RDKit molecule needs Kekulization based on bond types using need_kekulize', 'review the bond_dict and number_to_bond mappings for bond type conversions']
```

Usage

```
{'convert_smiles_to_graph': 'convert a SMILES string to molecular graph nodes and edges using to_graph', 'get_dataset_info': 'get atom types, maximum valence, and number-to-atom mappings for a dataset using dataset_info', 'create_onehot_encoding': 'create a one-hot encoded list for a given index and length using onehot', 'check_kekulize_needed': 'check if an RDKit molecule needs Kekulization based on bond types using need_kekulize', 'review_bond_mappings': 'review the bond_dict and number_to_bond mappings for bond type conversions'}
```


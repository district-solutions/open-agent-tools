# Agent Python Tools

- repo: facebookresearch/all-atom-diffusion-transformer
- repo_uri: https://github.com/facebookresearch/all-atom-diffusion-transformer

## File: facebookresearch_all-atom-diffusion-transformer/src/data/components/mp20_dataset.py

Prompts

```
['create an MP20 InMemoryDataset instance from a root directory for crystal graph machine learning', 'download the MP20 raw CSV dataset from Hugging Face hub into the root directory', 'process raw MP20 CSV data into PyG Data objects with scaled lattice vectors and save to disk', 'review the MP20 class to understand how it preprocesses crystal structures with Niggli reduction and CrystalNN graph construction', 'refactor the MP20 process method to customize lattice normalization or add additional graph features', 'build a crystal structure from a CIF string with optional Niggli reduction and primitive cell extraction', 'build a crystal graph with edge indices and fractional coordinates using the CrystalNN local environment strategy', 'convert fractional coordinates to Cartesian coordinates using lattice lengths and angles with periodic boundary regularization', 'compute periodic boundary condition aware distances between atom pairs given edge indices and lattice parameters', 'preprocess a CSV file of crystal structures in parallel to build graphs and extract symmetry information', 'create a QMOF150 PyG InMemoryDataset from a root directory with optional transforms and filters', 'download the QMOF150 relaxed structures zip from HuggingFace and extract to raw directory', 'process raw CIF files into PyG Data objects with atom types, fractional coords, and lattice info', 'process a single MOF CIF file and validate it using MOFChecker descriptors', 'build a crystal graph from a CIF string with Niggli reduction and graph arrays']
```

Usage

```
{'create_MP20_dataset': 'create an MP20 InMemoryDataset instance from a root directory for crystal graph machine learning', 'download_MP20_raw_data': 'download the MP20 raw CSV dataset from Hugging Face hub into the root directory', 'process_MP20_dataset': 'process raw MP20 CSV data into PyG Data objects with scaled lattice vectors and save to disk', 'review_MP20_class': 'review the MP20 class to understand how it preprocesses crystal structures with Niggli reduction and CrystalNN graph construction', 'refactor_MP20_process': 'refactor the MP20 process method to customize lattice normalization or add additional graph features'}
```

## File: facebookresearch_all-atom-diffusion-transformer/src/data/components/preprocessing_utils.py

Prompts

```
['create an MP20 InMemoryDataset instance from a root directory for crystal graph machine learning', 'download the MP20 raw CSV dataset from Hugging Face hub into the root directory', 'process raw MP20 CSV data into PyG Data objects with scaled lattice vectors and save to disk', 'review the MP20 class to understand how it preprocesses crystal structures with Niggli reduction and CrystalNN graph construction', 'refactor the MP20 process method to customize lattice normalization or add additional graph features', 'build a crystal structure from a CIF string with optional Niggli reduction and primitive cell extraction', 'build a crystal graph with edge indices and fractional coordinates using the CrystalNN local environment strategy', 'convert fractional coordinates to Cartesian coordinates using lattice lengths and angles with periodic boundary regularization', 'compute periodic boundary condition aware distances between atom pairs given edge indices and lattice parameters', 'preprocess a CSV file of crystal structures in parallel to build graphs and extract symmetry information', 'create a QMOF150 PyG InMemoryDataset from a root directory with optional transforms and filters', 'download the QMOF150 relaxed structures zip from HuggingFace and extract to raw directory', 'process raw CIF files into PyG Data objects with atom types, fractional coords, and lattice info', 'process a single MOF CIF file and validate it using MOFChecker descriptors', 'build a crystal graph from a CIF string with Niggli reduction and graph arrays']
```

Usage

```
{'build_crystal_from_cif': 'build a crystal structure from a CIF string with optional Niggli reduction and primitive cell extraction', 'build_crystal_graph': 'build a crystal graph with edge indices and fractional coordinates using the CrystalNN local environment strategy', 'convert_frac_to_cart_coords': 'convert fractional coordinates to Cartesian coordinates using lattice lengths and angles with periodic boundary regularization', 'compute_pbc_distances': 'compute periodic boundary condition aware distances between atom pairs given edge indices and lattice parameters', 'preprocess_crystal_csv': 'preprocess a CSV file of crystal structures in parallel to build graphs and extract symmetry information'}
```

## File: facebookresearch_all-atom-diffusion-transformer/src/data/components/qmof150_dataset.py

Prompts

```
['create an MP20 InMemoryDataset instance from a root directory for crystal graph machine learning', 'download the MP20 raw CSV dataset from Hugging Face hub into the root directory', 'process raw MP20 CSV data into PyG Data objects with scaled lattice vectors and save to disk', 'review the MP20 class to understand how it preprocesses crystal structures with Niggli reduction and CrystalNN graph construction', 'refactor the MP20 process method to customize lattice normalization or add additional graph features', 'build a crystal structure from a CIF string with optional Niggli reduction and primitive cell extraction', 'build a crystal graph with edge indices and fractional coordinates using the CrystalNN local environment strategy', 'convert fractional coordinates to Cartesian coordinates using lattice lengths and angles with periodic boundary regularization', 'compute periodic boundary condition aware distances between atom pairs given edge indices and lattice parameters', 'preprocess a CSV file of crystal structures in parallel to build graphs and extract symmetry information', 'create a QMOF150 PyG InMemoryDataset from a root directory with optional transforms and filters', 'download the QMOF150 relaxed structures zip from HuggingFace and extract to raw directory', 'process raw CIF files into PyG Data objects with atom types, fractional coords, and lattice info', 'process a single MOF CIF file and validate it using MOFChecker descriptors', 'build a crystal graph from a CIF string with Niggli reduction and graph arrays']
```

Usage

```
{'create_QMOF150_dataset': 'create a QMOF150 PyG InMemoryDataset from a root directory with optional transforms and filters', 'download_QMOF150_raw_data': 'download the QMOF150 relaxed structures zip from HuggingFace and extract to raw directory', 'process_QMOF150_dataset': 'process raw CIF files into PyG Data objects with atom types, fractional coords, and lattice info', 'process_one_MOF_file': 'process a single MOF CIF file and validate it using MOFChecker descriptors', 'build_crystal_graph_from_CIF': 'build a crystal graph from a CIF string with Niggli reduction and graph arrays'}
```


# Agent Python Tools

- repo: facebookresearch/adjointsampling
- repo_uri: https://github.com/facebookresearch/adjoint_sampling

## File: facebookresearch_adjointsampling/adjoint_sampling/utils/data_utils.py

Prompts

```
['build a fully connected molecule graph with edge indices and one-hot atomic species from an atom list', 'subtract the center of mass from batched particle positions using a batch index tensor', 'convert batched particle positions from graph format to a flat vector for standard torch models', 'create a PyTorch Dataset wrapper that yields pre-batched input and target tuples by index', 'subtract the center of mass from particle position samples reshaped as a vector array', 'init a PyTorch distributed process group from env vars or SLURM and set the NCCL backend', 'setup print to only output on the master process with timestamps in distributed training', 'check if PyTorch distributed is available and initialized before calling distributed APIs', 'get the total number of processes in the distributed group or return 1 if not initialized', 'get the current process rank in the distributed group or return 0 if not initialized', 'generate RDKit molecule conformers from a PyTorch graph state tensor with optional geometry relaxation using ASE LBFGS', 'read a SMILES string and generate multiple 3D conformers using RDKit ETKDG with optional MMFF optimization and ASE relaxation', 'calculate pairwise RMSD between lists of generated and reference RDKit molecules with automatic atom mapping and hydrogen removal', 'compute coverage recall, coverage precision, AMR recall, and AMR precision metrics from an RMSD array across threshold ranges', 'integrate an SDE over all time steps using Euler-Maruyama with uniform or quadratic-linear discretization and return graph states and controls', 'convert a matplotlib figure object to a PIL Image using fig2img', 'compute pairwise interatomic distances from particle position samples using interatomic_dist', 'generate a histogram figure of interatomic distances and energies using get_dataset_fig', 'convert atom positions and types to an RDKit Mol object with SMILES using to_mol', 'visualize generated molecular conformations as a grid image with SMILES legends using visualize_conformations']
```

Usage

```
{'build_atomic_graph': 'build a fully connected molecule graph with edge indices and one-hot atomic species from an atom list', 'subtract_com_batch': 'subtract the center of mass from batched particle positions using a batch index tensor', 'convert_graph_to_vector': 'convert batched particle positions from graph format to a flat vector for standard torch models', 'create_prebatched_dataset': 'create a PyTorch Dataset wrapper that yields pre-batched input and target tuples by index', 'subtract_com_vector': 'subtract the center of mass from particle position samples reshaped as a vector array'}
```

## File: facebookresearch_adjointsampling/adjoint_sampling/utils/distributed_mode.py

Prompts

```
['build a fully connected molecule graph with edge indices and one-hot atomic species from an atom list', 'subtract the center of mass from batched particle positions using a batch index tensor', 'convert batched particle positions from graph format to a flat vector for standard torch models', 'create a PyTorch Dataset wrapper that yields pre-batched input and target tuples by index', 'subtract the center of mass from particle position samples reshaped as a vector array', 'init a PyTorch distributed process group from env vars or SLURM and set the NCCL backend', 'setup print to only output on the master process with timestamps in distributed training', 'check if PyTorch distributed is available and initialized before calling distributed APIs', 'get the total number of processes in the distributed group or return 1 if not initialized', 'get the current process rank in the distributed group or return 0 if not initialized', 'generate RDKit molecule conformers from a PyTorch graph state tensor with optional geometry relaxation using ASE LBFGS', 'read a SMILES string and generate multiple 3D conformers using RDKit ETKDG with optional MMFF optimization and ASE relaxation', 'calculate pairwise RMSD between lists of generated and reference RDKit molecules with automatic atom mapping and hydrogen removal', 'compute coverage recall, coverage precision, AMR recall, and AMR precision metrics from an RMSD array across threshold ranges', 'integrate an SDE over all time steps using Euler-Maruyama with uniform or quadratic-linear discretization and return graph states and controls', 'convert a matplotlib figure object to a PIL Image using fig2img', 'compute pairwise interatomic distances from particle position samples using interatomic_dist', 'generate a histogram figure of interatomic distances and energies using get_dataset_fig', 'convert atom positions and types to an RDKit Mol object with SMILES using to_mol', 'visualize generated molecular conformations as a grid image with SMILES legends using visualize_conformations']
```

Usage

```
{'init_distributed_mode': 'init a PyTorch distributed process group from env vars or SLURM and set the NCCL backend', 'setup_for_distributed': 'setup print to only output on the master process with timestamps in distributed training', 'is_dist_avail_and_initialized': 'check if PyTorch distributed is available and initialized before calling distributed APIs', 'get_world_size': 'get the total number of processes in the distributed group or return 1 if not initialized', 'get_rank': 'get the current process rank in the distributed group or return 0 if not initialized'}
```

## File: facebookresearch_adjointsampling/adjoint_sampling/utils/eval_utils.py

Prompts

```
['build a fully connected molecule graph with edge indices and one-hot atomic species from an atom list', 'subtract the center of mass from batched particle positions using a batch index tensor', 'convert batched particle positions from graph format to a flat vector for standard torch models', 'create a PyTorch Dataset wrapper that yields pre-batched input and target tuples by index', 'subtract the center of mass from particle position samples reshaped as a vector array', 'init a PyTorch distributed process group from env vars or SLURM and set the NCCL backend', 'setup print to only output on the master process with timestamps in distributed training', 'check if PyTorch distributed is available and initialized before calling distributed APIs', 'get the total number of processes in the distributed group or return 1 if not initialized', 'get the current process rank in the distributed group or return 0 if not initialized', 'generate RDKit molecule conformers from a PyTorch graph state tensor with optional geometry relaxation using ASE LBFGS', 'read a SMILES string and generate multiple 3D conformers using RDKit ETKDG with optional MMFF optimization and ASE relaxation', 'calculate pairwise RMSD between lists of generated and reference RDKit molecules with automatic atom mapping and hydrogen removal', 'compute coverage recall, coverage precision, AMR recall, and AMR precision metrics from an RMSD array across threshold ranges', 'integrate an SDE over all time steps using Euler-Maruyama with uniform or quadratic-linear discretization and return graph states and controls', 'convert a matplotlib figure object to a PIL Image using fig2img', 'compute pairwise interatomic distances from particle position samples using interatomic_dist', 'generate a histogram figure of interatomic distances and energies using get_dataset_fig', 'convert atom positions and types to an RDKit Mol object with SMILES using to_mol', 'visualize generated molecular conformations as a grid image with SMILES legends using visualize_conformations']
```

Usage

```
{'generate_conformers_from_graph_state': 'generate RDKit molecule conformers from a PyTorch graph state tensor with optional geometry relaxation using ASE LBFGS', 'read_rdkit_mols_from_smiles': 'read a SMILES string and generate multiple 3D conformers using RDKit ETKDG with optional MMFF optimization and ASE relaxation', 'calc_rmsd_between_molecule_lists': 'calculate pairwise RMSD between lists of generated and reference RDKit molecules with automatic atom mapping and hydrogen removal', 'calc_performance_stats_from_rmsd': 'compute coverage recall, coverage precision, AMR recall, and AMR precision metrics from an RMSD array across threshold ranges', 'integrate_sde_all_states': 'integrate an SDE over all time steps using Euler-Maruyama with uniform or quadratic-linear discretization and return graph states and controls'}
```

## File: facebookresearch_adjointsampling/adjoint_sampling/utils/visualize_utils.py

Prompts

```
['build a fully connected molecule graph with edge indices and one-hot atomic species from an atom list', 'subtract the center of mass from batched particle positions using a batch index tensor', 'convert batched particle positions from graph format to a flat vector for standard torch models', 'create a PyTorch Dataset wrapper that yields pre-batched input and target tuples by index', 'subtract the center of mass from particle position samples reshaped as a vector array', 'init a PyTorch distributed process group from env vars or SLURM and set the NCCL backend', 'setup print to only output on the master process with timestamps in distributed training', 'check if PyTorch distributed is available and initialized before calling distributed APIs', 'get the total number of processes in the distributed group or return 1 if not initialized', 'get the current process rank in the distributed group or return 0 if not initialized', 'generate RDKit molecule conformers from a PyTorch graph state tensor with optional geometry relaxation using ASE LBFGS', 'read a SMILES string and generate multiple 3D conformers using RDKit ETKDG with optional MMFF optimization and ASE relaxation', 'calculate pairwise RMSD between lists of generated and reference RDKit molecules with automatic atom mapping and hydrogen removal', 'compute coverage recall, coverage precision, AMR recall, and AMR precision metrics from an RMSD array across threshold ranges', 'integrate an SDE over all time steps using Euler-Maruyama with uniform or quadratic-linear discretization and return graph states and controls', 'convert a matplotlib figure object to a PIL Image using fig2img', 'compute pairwise interatomic distances from particle position samples using interatomic_dist', 'generate a histogram figure of interatomic distances and energies using get_dataset_fig', 'convert atom positions and types to an RDKit Mol object with SMILES using to_mol', 'visualize generated molecular conformations as a grid image with SMILES legends using visualize_conformations']
```

Usage

```
{'convert_matplotlib_figure_to_pil_image': 'convert a matplotlib figure object to a PIL Image using fig2img', 'compute_pairwise_interatomic_distances': 'compute pairwise interatomic distances from particle position samples using interatomic_dist', 'generate_dataset_visualization_figure': 'generate a histogram figure of interatomic distances and energies using get_dataset_fig', 'convert_positions_to_rdkit_molecule': 'convert atom positions and types to an RDKit Mol object with SMILES using to_mol', 'visualize_molecular_conformations': 'visualize generated molecular conformations as a grid image with SMILES legends using visualize_conformations'}
```


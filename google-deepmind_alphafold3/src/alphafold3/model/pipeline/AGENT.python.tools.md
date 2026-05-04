# Agent Python Tools

- repo: google-deepmind/alphafold3
- repo_uri: https://github.com/google-deepmind/alphafold3

## File: google-deepmind_alphafold3/src/alphafold3/model/pipeline/inter_chain_bonds.py

Prompts

```
['get polymer-ligand and ligand-ligand inter-residue bonds from a Structure object with optional glycan filtering', 'get ligand-ligand inter-residue bonds from a Structure object with configurable glycan-only mode and bond deduplication', 'get polymer-ligand interchain bonds from a Structure object with optional custom bond distance threshold', 'compute bond layout between two sets of chain types filtered by distance, bond type, and residue name', 'create a NamedTuple holding chain_id, chain_type, res_id, res_name, atom_name, and coords arrays for bond atoms', 'calculate the bucket size to pad input tokens to based on a sequence of bucket thresholds', 'create a WholePdbPipeline Config object to set max atoms per token, MSA crop size, and bucket sizes', 'process a Structure with MSAs and templates through the AlphaFold 3 data pipeline to produce a feature Batch', 'process a folding Input request through the pipeline and return a numpy feature dictionary with NaN validation', 'review the WholePdbPipeline class and its structure cleaning, tokenization, MSA, template, and frame construction steps', 'clean a PDB structure by dropping missing sequences, non-standard atoms, waters, hydrogens, leaving atoms, and bad bonds', 'create a zero-coordinate structure and flat atom layout from all physical residues of a PDB structure', 'compute a boolean mask identifying leaving atoms to drop for a given residue in a structure', 'review the clean_structure function to understand how it filters waters, hydrogens, and leaving atoms from a PDB', 'refactor the clean_structure function to add a new filter option for dropping specific residue types']
```

Usage

```
{'get_polymer_ligand_and_ligand_ligand_bonds': 'get polymer-ligand and ligand-ligand inter-residue bonds from a Structure object with optional glycan filtering', 'get_ligand_ligand_bonds': 'get ligand-ligand inter-residue bonds from a Structure object with configurable glycan-only mode and bond deduplication', 'get_polymer_ligand_bonds': 'get polymer-ligand interchain bonds from a Structure object with optional custom bond distance threshold', 'get_bond_layout': 'compute bond layout between two sets of chain types filtered by distance, bond type, and residue name', 'BondAtomArrays': 'create a NamedTuple holding chain_id, chain_type, res_id, res_name, atom_name, and coords arrays for bond atoms'}
```

## File: google-deepmind_alphafold3/src/alphafold3/model/pipeline/pipeline.py

Prompts

```
['get polymer-ligand and ligand-ligand inter-residue bonds from a Structure object with optional glycan filtering', 'get ligand-ligand inter-residue bonds from a Structure object with configurable glycan-only mode and bond deduplication', 'get polymer-ligand interchain bonds from a Structure object with optional custom bond distance threshold', 'compute bond layout between two sets of chain types filtered by distance, bond type, and residue name', 'create a NamedTuple holding chain_id, chain_type, res_id, res_name, atom_name, and coords arrays for bond atoms', 'calculate the bucket size to pad input tokens to based on a sequence of bucket thresholds', 'create a WholePdbPipeline Config object to set max atoms per token, MSA crop size, and bucket sizes', 'process a Structure with MSAs and templates through the AlphaFold 3 data pipeline to produce a feature Batch', 'process a folding Input request through the pipeline and return a numpy feature dictionary with NaN validation', 'review the WholePdbPipeline class and its structure cleaning, tokenization, MSA, template, and frame construction steps', 'clean a PDB structure by dropping missing sequences, non-standard atoms, waters, hydrogens, leaving atoms, and bad bonds', 'create a zero-coordinate structure and flat atom layout from all physical residues of a PDB structure', 'compute a boolean mask identifying leaving atoms to drop for a given residue in a structure', 'review the clean_structure function to understand how it filters waters, hydrogens, and leaving atoms from a PDB', 'refactor the clean_structure function to add a new filter option for dropping specific residue types']
```

Usage

```
{'calculate_bucket_size': 'calculate the bucket size to pad input tokens to based on a sequence of bucket thresholds', 'create_WholePdbPipeline_Config': 'create a WholePdbPipeline Config object to set max atoms per token, MSA crop size, and bucket sizes', 'process_structure': 'process a Structure with MSAs and templates through the AlphaFold 3 data pipeline to produce a feature Batch', 'process_item': 'process a folding Input request through the pipeline and return a numpy feature dictionary with NaN validation', 'review_WholePdbPipeline': 'review the WholePdbPipeline class and its structure cleaning, tokenization, MSA, template, and frame construction steps'}
```

## File: google-deepmind_alphafold3/src/alphafold3/model/pipeline/structure_cleaning.py

Prompts

```
['get polymer-ligand and ligand-ligand inter-residue bonds from a Structure object with optional glycan filtering', 'get ligand-ligand inter-residue bonds from a Structure object with configurable glycan-only mode and bond deduplication', 'get polymer-ligand interchain bonds from a Structure object with optional custom bond distance threshold', 'compute bond layout between two sets of chain types filtered by distance, bond type, and residue name', 'create a NamedTuple holding chain_id, chain_type, res_id, res_name, atom_name, and coords arrays for bond atoms', 'calculate the bucket size to pad input tokens to based on a sequence of bucket thresholds', 'create a WholePdbPipeline Config object to set max atoms per token, MSA crop size, and bucket sizes', 'process a Structure with MSAs and templates through the AlphaFold 3 data pipeline to produce a feature Batch', 'process a folding Input request through the pipeline and return a numpy feature dictionary with NaN validation', 'review the WholePdbPipeline class and its structure cleaning, tokenization, MSA, template, and frame construction steps', 'clean a PDB structure by dropping missing sequences, non-standard atoms, waters, hydrogens, leaving atoms, and bad bonds', 'create a zero-coordinate structure and flat atom layout from all physical residues of a PDB structure', 'compute a boolean mask identifying leaving atoms to drop for a given residue in a structure', 'review the clean_structure function to understand how it filters waters, hydrogens, and leaving atoms from a PDB', 'refactor the clean_structure function to add a new filter option for dropping specific residue types']
```

Usage

```
{'clean_structure': 'clean a PDB structure by dropping missing sequences, non-standard atoms, waters, hydrogens, leaving atoms, and bad bonds', 'create_empty_output_struc_and_layout': 'create a zero-coordinate structure and flat atom layout from all physical residues of a PDB structure', 'get_leaving_atom_mask': 'compute a boolean mask identifying leaving atoms to drop for a given residue in a structure', 'review_clean_structure': 'review the clean_structure function to understand how it filters waters, hydrogens, and leaving atoms from a PDB', 'refactor_clean_structure': 'refactor the clean_structure function to add a new filter option for dropping specific residue types'}
```


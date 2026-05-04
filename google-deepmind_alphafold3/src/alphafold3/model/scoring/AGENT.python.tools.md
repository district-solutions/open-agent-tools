# Agent Python Tools

- repo: google-deepmind/alphafold3
- repo_uri: https://github.com/google-deepmind/alphafold3

## File: google-deepmind_alphafold3/src/alphafold3/model/scoring/alignment.py

Prompts

```
['compute the aligned RMSD between two sets of decoy and ground truth atom coordinates', 'align a set of 3D coordinates to a reference structure using a rigid transformation', 'compute per-atom deviations between aligned decoy and ground truth coordinates for RMSD analysis', 'find the least squares best fit rotation matrix between two sets of N points', 'test the rmsd_from_coords function with sample decoy and ground truth coordinate arrays', 'compare chirality of ligands in a structure against reference molecules or CCD entries', 'find chiral centres and detect their chirality for carbon and sulfur atoms in a molecule', 'compare chirality of two RDKit Mol objects and check if mol1 is a subset match of mol2', 'create an RDKit Mol object from a ligand structure and reference mol with 3D stereochemistry', 'create an RDKit Mol object from CCD chemical components database given a residue name', 'create pseudo beta atom positions and masks from dense atom positions and amino acid types', 'build pseudo beta atom positions using numpy instead of jax for offline analysis', 'test the pseudo_beta_fn function with sample amino acid types and atom position arrays', 'refactor pseudo_beta_fn to support additional residue types beyond standard polymers and ligands', 'summarize the pseudo_beta_fn function that extracts pseudo beta atom positions for scoring model outputs']
```

Usage

```
{'compute_rmsd_between_coords': 'compute the aligned RMSD between two sets of decoy and ground truth atom coordinates', 'align_coords_to_reference': 'align a set of 3D coordinates to a reference structure using a rigid transformation', 'compute_per_atom_deviations': 'compute per-atom deviations between aligned decoy and ground truth coordinates for RMSD analysis', 'find_least_squares_rotation': 'find the least squares best fit rotation matrix between two sets of N points', 'test_rmsd_from_coords': 'test the rmsd_from_coords function with sample decoy and ground truth coordinate arrays'}
```

## File: google-deepmind_alphafold3/src/alphafold3/model/scoring/chirality.py

Prompts

```
['compute the aligned RMSD between two sets of decoy and ground truth atom coordinates', 'align a set of 3D coordinates to a reference structure using a rigid transformation', 'compute per-atom deviations between aligned decoy and ground truth coordinates for RMSD analysis', 'find the least squares best fit rotation matrix between two sets of N points', 'test the rmsd_from_coords function with sample decoy and ground truth coordinate arrays', 'compare chirality of ligands in a structure against reference molecules or CCD entries', 'find chiral centres and detect their chirality for carbon and sulfur atoms in a molecule', 'compare chirality of two RDKit Mol objects and check if mol1 is a subset match of mol2', 'create an RDKit Mol object from a ligand structure and reference mol with 3D stereochemistry', 'create an RDKit Mol object from CCD chemical components database given a residue name', 'create pseudo beta atom positions and masks from dense atom positions and amino acid types', 'build pseudo beta atom positions using numpy instead of jax for offline analysis', 'test the pseudo_beta_fn function with sample amino acid types and atom position arrays', 'refactor pseudo_beta_fn to support additional residue types beyond standard polymers and ligands', 'summarize the pseudo_beta_fn function that extracts pseudo beta atom positions for scoring model outputs']
```

Usage

```
{'compare_chirality': 'compare chirality of ligands in a structure against reference molecules or CCD entries', 'find_chiral_centres': 'find chiral centres and detect their chirality for carbon and sulfur atoms in a molecule', 'chiral_match': 'compare chirality of two RDKit Mol objects and check if mol1 is a subset match of mol2', 'mol_from_ligand_struc': 'create an RDKit Mol object from a ligand structure and reference mol with 3D stereochemistry', 'maybe_mol_from_ccd': 'create an RDKit Mol object from CCD chemical components database given a residue name'}
```

## File: google-deepmind_alphafold3/src/alphafold3/model/scoring/scoring.py

Prompts

```
['compute the aligned RMSD between two sets of decoy and ground truth atom coordinates', 'align a set of 3D coordinates to a reference structure using a rigid transformation', 'compute per-atom deviations between aligned decoy and ground truth coordinates for RMSD analysis', 'find the least squares best fit rotation matrix between two sets of N points', 'test the rmsd_from_coords function with sample decoy and ground truth coordinate arrays', 'compare chirality of ligands in a structure against reference molecules or CCD entries', 'find chiral centres and detect their chirality for carbon and sulfur atoms in a molecule', 'compare chirality of two RDKit Mol objects and check if mol1 is a subset match of mol2', 'create an RDKit Mol object from a ligand structure and reference mol with 3D stereochemistry', 'create an RDKit Mol object from CCD chemical components database given a residue name', 'create pseudo beta atom positions and masks from dense atom positions and amino acid types', 'build pseudo beta atom positions using numpy instead of jax for offline analysis', 'test the pseudo_beta_fn function with sample amino acid types and atom position arrays', 'refactor pseudo_beta_fn to support additional residue types beyond standard polymers and ligands', 'summarize the pseudo_beta_fn function that extracts pseudo beta atom positions for scoring model outputs']
```

Usage

```
{'create_pseudo_beta_positions': 'create pseudo beta atom positions and masks from dense atom positions and amino acid types', 'build_pseudo_beta_with_numpy': 'build pseudo beta atom positions using numpy instead of jax for offline analysis', 'test_pseudo_beta_fn': 'test the pseudo_beta_fn function with sample amino acid types and atom position arrays', 'refactor_pseudo_beta_fn': 'refactor pseudo_beta_fn to support additional residue types beyond standard polymers and ligands', 'summarize_pseudo_beta_fn': 'summarize the pseudo_beta_fn function that extracts pseudo beta atom positions for scoring model outputs'}
```


# Agent Python Tools

- repo: google-deepmind/alphafold3
- repo_uri: https://github.com/google-deepmind/alphafold3

## File: google-deepmind_alphafold3/src/alphafold3/model/atom_layout/atom_layout.py

Prompts

```
['create a flat AtomLayout from a Residues object using CCD chemical component data and bond information', 'compute gather indices and mask to convert atom data from a source layout to a target layout', 'convert a numpy or jax array from one atom layout to another using GatherInfo indices', 'build a Structure object from a flat AtomLayout and atom coordinate arrays with optional B-factors', 'extract a Residues object with terminus and deprotonation info from a Structure including missing residues']
```

Usage

```
{'make_flat_atom_layout': 'create a flat AtomLayout from a Residues object using CCD chemical component data and bond information', 'compute_gather_idxs': 'compute gather indices and mask to convert atom data from a source layout to a target layout', 'convert': 'convert a numpy or jax array from one atom layout to another using GatherInfo indices', 'make_structure': 'build a Structure object from a flat AtomLayout and atom coordinate arrays with optional B-factors', 'residues_from_structure': 'extract a Residues object with terminus and deprotonation info from a Structure including missing residues'}
```


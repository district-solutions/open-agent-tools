# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/data/omol/orca/calc.py

Prompts

```
['write ORCA input files for an ASE Atoms object with specified charge, multiplicity, and NBO options', 'estimate the memory requirement in MB for an ORCA calculation given an ASE Atoms object and spin multiplicity', 'count the number of basis functions for an ASE Atoms object using the def2-TZVPD basis set', 'generate an ORCA SCF rotate block to break symmetry for open-shell singlet calculations', 'review the LOOSE_OPT_PARAMETERS, OPT_PARAMETERS, TIGHT_OPT_PARAMETERS, and EVAL_OPT_PARAMETERS optimization configurations for geometry optimization', 'run a single-point energy and gradient calculation for a molecule using ORCA', 'run a geometry optimization for a molecule using ORCA with ASE relaxation', 'run an ORCA single-point calculation with Natural Bond Orbital analysis enabled', 'run an ORCA calculation with symmetry breaking for metal-organic systems', 'run an ORCA calculation parallelized across multiple CPU cores']
```

Usage

```
{'write_orca_input_files': 'write ORCA input files for an ASE Atoms object with specified charge, multiplicity, and NBO options', 'estimate_orca_memory': 'estimate the memory requirement in MB for an ORCA calculation given an ASE Atoms object and spin multiplicity', 'count_basis_functions': 'count the number of basis functions for an ASE Atoms object using the def2-TZVPD basis set', 'generate_symmetry_break_block': 'generate an ORCA SCF rotate block to break symmetry for open-shell singlet calculations', 'review_optimization_parameters': 'review the LOOSE_OPT_PARAMETERS, OPT_PARAMETERS, TIGHT_OPT_PARAMETERS, and EVAL_OPT_PARAMETERS optimization configurations for geometry optimization'}
```

## File: facebookresearch_fairchem/src/fairchem/data/omol/orca/recipes.py

Prompts

```
['write ORCA input files for an ASE Atoms object with specified charge, multiplicity, and NBO options', 'estimate the memory requirement in MB for an ORCA calculation given an ASE Atoms object and spin multiplicity', 'count the number of basis functions for an ASE Atoms object using the def2-TZVPD basis set', 'generate an ORCA SCF rotate block to break symmetry for open-shell singlet calculations', 'review the LOOSE_OPT_PARAMETERS, OPT_PARAMETERS, TIGHT_OPT_PARAMETERS, and EVAL_OPT_PARAMETERS optimization configurations for geometry optimization', 'run a single-point energy and gradient calculation for a molecule using ORCA', 'run a geometry optimization for a molecule using ORCA with ASE relaxation', 'run an ORCA single-point calculation with Natural Bond Orbital analysis enabled', 'run an ORCA calculation with symmetry breaking for metal-organic systems', 'run an ORCA calculation parallelized across multiple CPU cores']
```

Usage

```
{'run_single_point_orca': 'run a single-point energy and gradient calculation for a molecule using ORCA', 'run_geometry_optimization_orca': 'run a geometry optimization for a molecule using ORCA with ASE relaxation', 'run_orca_with_nbo': 'run an ORCA single-point calculation with Natural Bond Orbital analysis enabled', 'run_orca_metal_organics': 'run an ORCA calculation with symmetry breaking for metal-organic systems', 'run_orca_parallel': 'run an ORCA calculation parallelized across multiple CPU cores'}
```


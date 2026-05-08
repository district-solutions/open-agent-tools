# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/lammps/lammps_fc.py

Prompts

```
['lookup atomic numbers from atomic mass values using closest match within 0.1 tolerance', 'create an AtomicData object from LAMMPS simulation positions, atomic numbers, cell, and periodicity', 'run a LAMMPS molecular dynamics simulation using a FairChem MLIP predictor for force calculations', 'create a FixExternalCallback to compute MLIP forces and virial for LAMMPS external fix integration', 'separate LAMMPS input script lines into setup commands and run commands for controlled execution']
```

Usage

```
{'lookup_atomic_number_by_mass': 'lookup atomic numbers from atomic mass values using closest match within 0.1 tolerance', 'create_atomic_data_from_lammps_data': 'create an AtomicData object from LAMMPS simulation positions, atomic numbers, cell, and periodicity', 'run_lammps_with_fairchem': 'run a LAMMPS molecular dynamics simulation using a FairChem MLIP predictor for force calculations', 'create_fix_external_callback': 'create a FixExternalCallback to compute MLIP forces and virial for LAMMPS external fix integration', 'separate_run_commands': 'separate LAMMPS input script lines into setup commands and run commands for controlled execution'}
```


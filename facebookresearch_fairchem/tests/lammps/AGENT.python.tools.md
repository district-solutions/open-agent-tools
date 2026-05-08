# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/lammps/test_ase_vs_lammps.py

Prompts

```
['run an ASE Langevin dynamics simulation on an FCC carbon lattice with a FAIRChem MLIP predictor', 'run an ASE NVE ensemble simulation using VelocityVerlet on an FCC carbon lattice with a FAIRChem MLIP predictor', 'run an ASE NPT ensemble simulation using IsotropicMTKNPT on an FCC carbon lattice with a FAIRChem MLIP predictor', 'run a LAMMPS simulation with a FAIRChem MLIP predictor and return kinetic and potential energy', 'test that ASE NVE and LAMMPS NVE simulations produce close kinetic and potential energy values', 'create a LAMMPS data file for a triclinic box with atom positions, cell matrix, and masses', 'test that scaled atomic positions computed by ASE match those from LAMMPS for triclinic boxes', 'test that restricted_cell_from_lammps_box preserves cell volume across cubic, orthorhombic, and triclinic boxes', 'run a LAMMPS simulation with atoms in a triclinic box and extract box parameters and positions', 'review the restricted_cell_from_lammps_box function that converts LAMMPS box parameters to an ASE cell matrix']
```

Usage

```
{'run_ase_langevin': 'run an ASE Langevin dynamics simulation on an FCC carbon lattice with a FAIRChem MLIP predictor', 'run_ase_nve': 'run an ASE NVE ensemble simulation using VelocityVerlet on an FCC carbon lattice with a FAIRChem MLIP predictor', 'run_ase_npt': 'run an ASE NPT ensemble simulation using IsotropicMTKNPT on an FCC carbon lattice with a FAIRChem MLIP predictor', 'run_lammps': 'run a LAMMPS simulation with a FAIRChem MLIP predictor and return kinetic and potential energy', 'test_ase_vs_lammps_nve': 'test that ASE NVE and LAMMPS NVE simulations produce close kinetic and potential energy values'}
```

## File: facebookresearch_fairchem/tests/lammps/test_lammps_fc.py

Prompts

```
['run an ASE Langevin dynamics simulation on an FCC carbon lattice with a FAIRChem MLIP predictor', 'run an ASE NVE ensemble simulation using VelocityVerlet on an FCC carbon lattice with a FAIRChem MLIP predictor', 'run an ASE NPT ensemble simulation using IsotropicMTKNPT on an FCC carbon lattice with a FAIRChem MLIP predictor', 'run a LAMMPS simulation with a FAIRChem MLIP predictor and return kinetic and potential energy', 'test that ASE NVE and LAMMPS NVE simulations produce close kinetic and potential energy values', 'create a LAMMPS data file for a triclinic box with atom positions, cell matrix, and masses', 'test that scaled atomic positions computed by ASE match those from LAMMPS for triclinic boxes', 'test that restricted_cell_from_lammps_box preserves cell volume across cubic, orthorhombic, and triclinic boxes', 'run a LAMMPS simulation with atoms in a triclinic box and extract box parameters and positions', 'review the restricted_cell_from_lammps_box function that converts LAMMPS box parameters to an ASE cell matrix']
```

Usage

```
{'create_lammps_data_file': 'create a LAMMPS data file for a triclinic box with atom positions, cell matrix, and masses', 'test_scaled_positions_lammps_vs_ase': 'test that scaled atomic positions computed by ASE match those from LAMMPS for triclinic boxes', 'test_cell_conversion_preserves_volume': 'test that restricted_cell_from_lammps_box preserves cell volume across cubic, orthorhombic, and triclinic boxes', 'run_lammps_triclinic_simulation': 'run a LAMMPS simulation with atoms in a triclinic box and extract box parameters and positions', 'review_restricted_cell_from_lammps_box': 'review the restricted_cell_from_lammps_box function that converts LAMMPS box parameters to an ASE cell matrix'}
```


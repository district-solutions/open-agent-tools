# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/data/oc/tests/old_tests/check_energy_and_forces.py

Prompts

```
['run check_relaxed_forces to verify final frame forces are below a threshold', 'run check_adsorption_energy to validate adsorption energy against reference and expected values', 'run check_DFT_energy to verify final energy is lower than initial and monotonically decreasing', 'run check_positions_across_frames_are_different to ensure consecutive trajectory frames have unique positions', 'run run_checks to validate forces, adsorption energy, DFT energy, and positions across systems', 'load adsorbed bulk metadata from a pickle file given an input directory and data split tag', 'create a pandas DataFrame from a list of adslab metadata tuples and save it to CSV', 'test if a DataFrame of adslab metadata contains any duplicate entries based on fingerprint columns', 'check for common adsorbate or bulk materials between two dataset splits in a DataFrame', 'verify all adsorbate atoms are connected after placement on an ASE Atoms adslab structure', 'run the CLI tool to compare trajectory first frames against input atoms objects using multiprocessing', 'create an argparse parser with sysid_file, traj_path_by_sysid, input_dir_by_sysid, and num_workers arguments', 'compare the first frame of a trajectory file against its reference atoms object input', 'calculate atom-wise distances between two ASE atoms objects accounting for periodic boundary conditions', 'get the starting atomic structure from an input directory using metadata.pkl and ase-sort.dat files', 'run the CLI tool to compare potential energies between two ASE trajectory or XML files', 'run compare_runs to check if two atomic structure files have matching potential energy within tolerance', 'test the compare_runs function by comparing a reference XML file against a current vasprun.xml file', 'create an argparse parser with path1, path2, type, and tolerance arguments for structure comparison', 'refactor compare_runs to support additional reference file types beyond xml and traj']
```

Usage

```
{'run_check_relaxed_forces': 'run check_relaxed_forces to verify final frame forces are below a threshold', 'run_check_adsorption_energy': 'run check_adsorption_energy to validate adsorption energy against reference and expected values', 'run_check_DFT_energy': 'run check_DFT_energy to verify final energy is lower than initial and monotonically decreasing', 'run_check_positions_across_frames': 'run check_positions_across_frames_are_different to ensure consecutive trajectory frames have unique positions', 'run_checks_multiprocess': 'run run_checks to validate forces, adsorption energy, DFT energy, and positions across systems'}
```

## File: facebookresearch_fairchem/tests/data/oc/tests/old_tests/check_inputs.py

Prompts

```
['run check_relaxed_forces to verify final frame forces are below a threshold', 'run check_adsorption_energy to validate adsorption energy against reference and expected values', 'run check_DFT_energy to verify final energy is lower than initial and monotonically decreasing', 'run check_positions_across_frames_are_different to ensure consecutive trajectory frames have unique positions', 'run run_checks to validate forces, adsorption energy, DFT energy, and positions across systems', 'load adsorbed bulk metadata from a pickle file given an input directory and data split tag', 'create a pandas DataFrame from a list of adslab metadata tuples and save it to CSV', 'test if a DataFrame of adslab metadata contains any duplicate entries based on fingerprint columns', 'check for common adsorbate or bulk materials between two dataset splits in a DataFrame', 'verify all adsorbate atoms are connected after placement on an ASE Atoms adslab structure', 'run the CLI tool to compare trajectory first frames against input atoms objects using multiprocessing', 'create an argparse parser with sysid_file, traj_path_by_sysid, input_dir_by_sysid, and num_workers arguments', 'compare the first frame of a trajectory file against its reference atoms object input', 'calculate atom-wise distances between two ASE atoms objects accounting for periodic boundary conditions', 'get the starting atomic structure from an input directory using metadata.pkl and ase-sort.dat files', 'run the CLI tool to compare potential energies between two ASE trajectory or XML files', 'run compare_runs to check if two atomic structure files have matching potential energy within tolerance', 'test the compare_runs function by comparing a reference XML file against a current vasprun.xml file', 'create an argparse parser with path1, path2, type, and tolerance arguments for structure comparison', 'refactor compare_runs to support additional reference file types beyond xml and traj']
```

Usage

```
{'obtain_metadata': 'load adsorbed bulk metadata from a pickle file given an input directory and data split tag', 'create_df': 'create a pandas DataFrame from a list of adslab metadata tuples and save it to CSV', 'adslabs_are_unique': 'test if a DataFrame of adslab metadata contains any duplicate entries based on fingerprint columns', 'check_commonelems': 'check for common adsorbate or bulk materials between two dataset splits in a DataFrame', 'is_adsorbate_placed_correct': 'verify all adsorbate atoms are connected after placement on an ASE Atoms adslab structure'}
```

## File: facebookresearch_fairchem/tests/data/oc/tests/old_tests/compare_inputs_and_trajectory.py

Prompts

```
['run check_relaxed_forces to verify final frame forces are below a threshold', 'run check_adsorption_energy to validate adsorption energy against reference and expected values', 'run check_DFT_energy to verify final energy is lower than initial and monotonically decreasing', 'run check_positions_across_frames_are_different to ensure consecutive trajectory frames have unique positions', 'run run_checks to validate forces, adsorption energy, DFT energy, and positions across systems', 'load adsorbed bulk metadata from a pickle file given an input directory and data split tag', 'create a pandas DataFrame from a list of adslab metadata tuples and save it to CSV', 'test if a DataFrame of adslab metadata contains any duplicate entries based on fingerprint columns', 'check for common adsorbate or bulk materials between two dataset splits in a DataFrame', 'verify all adsorbate atoms are connected after placement on an ASE Atoms adslab structure', 'run the CLI tool to compare trajectory first frames against input atoms objects using multiprocessing', 'create an argparse parser with sysid_file, traj_path_by_sysid, input_dir_by_sysid, and num_workers arguments', 'compare the first frame of a trajectory file against its reference atoms object input', 'calculate atom-wise distances between two ASE atoms objects accounting for periodic boundary conditions', 'get the starting atomic structure from an input directory using metadata.pkl and ase-sort.dat files', 'run the CLI tool to compare potential energies between two ASE trajectory or XML files', 'run compare_runs to check if two atomic structure files have matching potential energy within tolerance', 'test the compare_runs function by comparing a reference XML file against a current vasprun.xml file', 'create an argparse parser with path1, path2, type, and tolerance arguments for structure comparison', 'refactor compare_runs to support additional reference file types beyond xml and traj']
```

Usage

```
{'run_compare_trajectory_inputs': 'run the CLI tool to compare trajectory first frames against input atoms objects using multiprocessing', 'create_parser_argparse': 'create an argparse parser with sysid_file, traj_path_by_sysid, input_dir_by_sysid, and num_workers arguments', 'compare_trajectory_first_frame': 'compare the first frame of a trajectory file against its reference atoms object input', 'calculate_min_diff_pbc': 'calculate atom-wise distances between two ASE atoms objects accounting for periodic boundary conditions', 'get_starting_structure_from_input_dir': 'get the starting atomic structure from an input directory using metadata.pkl and ase-sort.dat files'}
```

## File: facebookresearch_fairchem/tests/data/oc/tests/old_tests/verify_correctness.py

Prompts

```
['run check_relaxed_forces to verify final frame forces are below a threshold', 'run check_adsorption_energy to validate adsorption energy against reference and expected values', 'run check_DFT_energy to verify final energy is lower than initial and monotonically decreasing', 'run check_positions_across_frames_are_different to ensure consecutive trajectory frames have unique positions', 'run run_checks to validate forces, adsorption energy, DFT energy, and positions across systems', 'load adsorbed bulk metadata from a pickle file given an input directory and data split tag', 'create a pandas DataFrame from a list of adslab metadata tuples and save it to CSV', 'test if a DataFrame of adslab metadata contains any duplicate entries based on fingerprint columns', 'check for common adsorbate or bulk materials between two dataset splits in a DataFrame', 'verify all adsorbate atoms are connected after placement on an ASE Atoms adslab structure', 'run the CLI tool to compare trajectory first frames against input atoms objects using multiprocessing', 'create an argparse parser with sysid_file, traj_path_by_sysid, input_dir_by_sysid, and num_workers arguments', 'compare the first frame of a trajectory file against its reference atoms object input', 'calculate atom-wise distances between two ASE atoms objects accounting for periodic boundary conditions', 'get the starting atomic structure from an input directory using metadata.pkl and ase-sort.dat files', 'run the CLI tool to compare potential energies between two ASE trajectory or XML files', 'run compare_runs to check if two atomic structure files have matching potential energy within tolerance', 'test the compare_runs function by comparing a reference XML file against a current vasprun.xml file', 'create an argparse parser with path1, path2, type, and tolerance arguments for structure comparison', 'refactor compare_runs to support additional reference file types beyond xml and traj']
```

Usage

```
{'run_verify_correctness_cli': 'run the CLI tool to compare potential energies between two ASE trajectory or XML files', 'run_compare_runs': 'run compare_runs to check if two atomic structure files have matching potential energy within tolerance', 'test_compare_runs': 'test the compare_runs function by comparing a reference XML file against a current vasprun.xml file', 'create_parser_verify_correctness': 'create an argparse parser with path1, path2, type, and tolerance arguments for structure comparison', 'refactor_compare_runs': 'refactor compare_runs to support additional reference file types beyond xml and traj'}
```


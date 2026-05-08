# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/data/oc/experimental/get_energies.py

Prompts

```
['run the script to extract final potential energies from VASP relaxation trajectories across multiple directories', 'extract a specific file from a ZIP archive to a target directory using extract_file', 'process a batch of directories to extract vasprun.xml and compute final potential energies', 'review the extract_file function that uses zipfile to unzip a single file from a ZIP archive', 'refactor the process_func to support reading energies from formats other than VASP XML', 'run merge_traj.py to merge intermediate checkpoints into a single full trajectory for all adsorbate runs', 'extract a specific file from a zip archive to a target directory using extract_file', 'merge sorted checkpoint vasprun.xml files into a complete ASE trajectory file', 'read a vasprun.xml file and construct an ASE trajectory using ase.io.read with vasp-xml format', 'write the merged full trajectory to a .traj file using ase.io.write', 'check if the initial POSCAR structure matches the first frame of a full trajectory', 'detect whether a trajectory has cyclical energy values indicating a checkpoint restart bug', 'plot and save the energy profile of a trajectory as a PNG image', 'review the v0_check function that compares initial POSCAR positions against trajectory positions', 'refactor the restart_bug_check function to improve detection of cyclical checkpoint restart behavior']
```

Usage

```
{'run_get_energies': 'run the script to extract final potential energies from VASP relaxation trajectories across multiple directories', 'extract_file': 'extract a specific file from a ZIP archive to a target directory using extract_file', 'process_func': 'process a batch of directories to extract vasprun.xml and compute final potential energies', 'review_extract_file': 'review the extract_file function that uses zipfile to unzip a single file from a ZIP archive', 'refactor_process_func': 'refactor the process_func to support reading energies from formats other than VASP XML'}
```

## File: facebookresearch_fairchem/src/fairchem/data/oc/experimental/merge_traj.py

Prompts

```
['run the script to extract final potential energies from VASP relaxation trajectories across multiple directories', 'extract a specific file from a ZIP archive to a target directory using extract_file', 'process a batch of directories to extract vasprun.xml and compute final potential energies', 'review the extract_file function that uses zipfile to unzip a single file from a ZIP archive', 'refactor the process_func to support reading energies from formats other than VASP XML', 'run merge_traj.py to merge intermediate checkpoints into a single full trajectory for all adsorbate runs', 'extract a specific file from a zip archive to a target directory using extract_file', 'merge sorted checkpoint vasprun.xml files into a complete ASE trajectory file', 'read a vasprun.xml file and construct an ASE trajectory using ase.io.read with vasp-xml format', 'write the merged full trajectory to a .traj file using ase.io.write', 'check if the initial POSCAR structure matches the first frame of a full trajectory', 'detect whether a trajectory has cyclical energy values indicating a checkpoint restart bug', 'plot and save the energy profile of a trajectory as a PNG image', 'review the v0_check function that compares initial POSCAR positions against trajectory positions', 'refactor the restart_bug_check function to improve detection of cyclical checkpoint restart behavior']
```

Usage

```
{'run_merge_traj': 'run merge_traj.py to merge intermediate checkpoints into a single full trajectory for all adsorbate runs', 'extract_file_from_zip': 'extract a specific file from a zip archive to a target directory using extract_file', 'merge_checkpoints_to_trajectory': 'merge sorted checkpoint vasprun.xml files into a complete ASE trajectory file', 'read_vasprun_xml': 'read a vasprun.xml file and construct an ASE trajectory using ase.io.read with vasp-xml format', 'write_full_trajectory': 'write the merged full trajectory to a .traj file using ase.io.write'}
```

## File: facebookresearch_fairchem/src/fairchem/data/oc/experimental/utils.py

Prompts

```
['run the script to extract final potential energies from VASP relaxation trajectories across multiple directories', 'extract a specific file from a ZIP archive to a target directory using extract_file', 'process a batch of directories to extract vasprun.xml and compute final potential energies', 'review the extract_file function that uses zipfile to unzip a single file from a ZIP archive', 'refactor the process_func to support reading energies from formats other than VASP XML', 'run merge_traj.py to merge intermediate checkpoints into a single full trajectory for all adsorbate runs', 'extract a specific file from a zip archive to a target directory using extract_file', 'merge sorted checkpoint vasprun.xml files into a complete ASE trajectory file', 'read a vasprun.xml file and construct an ASE trajectory using ase.io.read with vasp-xml format', 'write the merged full trajectory to a .traj file using ase.io.write', 'check if the initial POSCAR structure matches the first frame of a full trajectory', 'detect whether a trajectory has cyclical energy values indicating a checkpoint restart bug', 'plot and save the energy profile of a trajectory as a PNG image', 'review the v0_check function that compares initial POSCAR positions against trajectory positions', 'refactor the restart_bug_check function to improve detection of cyclical checkpoint restart behavior']
```

Usage

```
{'check_v0_trajectory_consistency': 'check if the initial POSCAR structure matches the first frame of a full trajectory', 'detect_restart_bug_in_trajectory': 'detect whether a trajectory has cyclical energy values indicating a checkpoint restart bug', 'plot_trajectory_energy_profile': 'plot and save the energy profile of a trajectory as a PNG image', 'review_v0_check_function': 'review the v0_check function that compares initial POSCAR positions against trajectory positions', 'refactor_restart_bug_check': 'refactor the restart_bug_check function to improve detection of cyclical checkpoint restart behavior'}
```


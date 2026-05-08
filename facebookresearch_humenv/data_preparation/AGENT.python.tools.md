# Agent Python Tools

- repo: facebookresearch/humenv
- repo_uri: https://github.com/facebookresearch/humenv

## File: facebookresearch_humenv/data_preparation/goal_pose_selection.py

Prompts

```
['generate goal pose datasets from AMASS motion capture data and save as JSON and image files', 'update the quaternion heading in a MuJoCo qpos array by multiplying with a given orientation quaternion', 'create a quaternion from a rotation axis vector and angle in degrees', 'multiply two quaternions together and return the resulting quaternion as a numpy array', 'run the goal pose selection script to extract and render human body poses from motion capture data', 'run the AMASS dataset processing script with --data_path and --num_workers arguments', 'save an episode dictionary of numpy arrays to an HDF5 file with gzip compression', 'replay SMPL motion sequences through HumEnv and save qpos qvel observations as HDF5', 'filter AMASS .npz motion files across datasets and map names to numeric IDs', 'process AMASS motion sequences into HDF5 files using optional multiprocessing workers']
```

Usage

```
{'generate_goal_pose_datasets': 'generate goal pose datasets from AMASS motion capture data and save as JSON and image files', 'update_qpos_heading': 'update the quaternion heading in a MuJoCo qpos array by multiplying with a given orientation quaternion', 'create_angle_axis_quaternion': 'create a quaternion from a rotation axis vector and angle in degrees', 'multiply_quaternions': 'multiply two quaternions together and return the resulting quaternion as a numpy array', 'run_goal_pose_selection': 'run the goal pose selection script to extract and render human body poses from motion capture data'}
```

## File: facebookresearch_humenv/data_preparation/process_amass.py

Prompts

```
['generate goal pose datasets from AMASS motion capture data and save as JSON and image files', 'update the quaternion heading in a MuJoCo qpos array by multiplying with a given orientation quaternion', 'create a quaternion from a rotation axis vector and angle in degrees', 'multiply two quaternions together and return the resulting quaternion as a numpy array', 'run the goal pose selection script to extract and render human body poses from motion capture data', 'run the AMASS dataset processing script with --data_path and --num_workers arguments', 'save an episode dictionary of numpy arrays to an HDF5 file with gzip compression', 'replay SMPL motion sequences through HumEnv and save qpos qvel observations as HDF5', 'filter AMASS .npz motion files across datasets and map names to numeric IDs', 'process AMASS motion sequences into HDF5 files using optional multiprocessing workers']
```

Usage

```
{'run_process_amass_cli': 'run the AMASS dataset processing script with --data_path and --num_workers arguments', 'save_hdf5_episode': 'save an episode dictionary of numpy arrays to an HDF5 file with gzip compression', 'replay_and_save_motions': 'replay SMPL motion sequences through HumEnv and save qpos qvel observations as HDF5', 'filter_amass_datasets': 'filter AMASS .npz motion files across datasets and map names to numeric IDs', 'hdf5_step_parallel': 'process AMASS motion sequences into HDF5 files using optional multiprocessing workers'}
```


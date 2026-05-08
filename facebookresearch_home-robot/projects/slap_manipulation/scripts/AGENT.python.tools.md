# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/projects/slap_manipulation/scripts/add_detic_features_to_h5.py

Prompts

```
['run the script in read mode to predict and save semantic frames from H5 episode data', 'run the script in write mode to add Detic semantic frames and masks to H5 files', 'run the script in visualize mode to display existing semantic frames from processed H5 files', 'refactor the sandwich function to wrap a list of object categories between other tokens', 'review the TASK_TO_OBJECT_MAP dictionary that maps task names to target object categories for detection', 'run the script to move opening actions farther back by 10 cm along y-axis for drawer tasks', 'edit HDF5 demonstration files to shift end-effector pose positions along the y-axis by 0.1 meters', 'process all HDF5 files in a directory to adjust opening actions for open-object-drawer manipulation tasks', 'skip already processed HDF5 demonstration groups that contain an edited flag to avoid duplicate edits', 'batch edit end-effector pose data across multiple HDF5 demonstration files using a glob template pattern', 'run the label interaction points script in read mode to show labeled points from H5 dataset files', 'run the label interaction points script in write mode to label interaction points on point clouds', 'run the pick points function to interactively select points from an Open3D point cloud visualization', 'review the pick points function that uses Open3D VisualizerWithEditing for interactive point selection', 'summarize the main CLI entry point that iterates H5 files and labels interaction points in read or write mode', 'run the full_rename CLI to batch rename task names in H5 files using a YAML config mapping', 'run the rename_edits CLI to rename a specific task name from one key to another in H5 files', 'refactor the full_rename function to support additional file formats beyond H5 for task name renaming', 'review the rename_edits function that renames task names from a source key to a target key in H5 groups', 'summarize the full_rename function that reads a YAML config and renames task names across all matching H5 files']
```

Usage

```
{'run_detic_features_read': 'run the script in read mode to predict and save semantic frames from H5 episode data', 'run_detic_features_write': 'run the script in write mode to add Detic semantic frames and masks to H5 files', 'run_detic_features_visualize': 'run the script in visualize mode to display existing semantic frames from processed H5 files', 'refactor_sandwich': 'refactor the sandwich function to wrap a list of object categories between other tokens', 'review_TASK_TO_OBJECT_MAP': 'review the TASK_TO_OBJECT_MAP dictionary that maps task names to target object categories for detection'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/scripts/edit_demonstrations.py

Prompts

```
['run the script in read mode to predict and save semantic frames from H5 episode data', 'run the script in write mode to add Detic semantic frames and masks to H5 files', 'run the script in visualize mode to display existing semantic frames from processed H5 files', 'refactor the sandwich function to wrap a list of object categories between other tokens', 'review the TASK_TO_OBJECT_MAP dictionary that maps task names to target object categories for detection', 'run the script to move opening actions farther back by 10 cm along y-axis for drawer tasks', 'edit HDF5 demonstration files to shift end-effector pose positions along the y-axis by 0.1 meters', 'process all HDF5 files in a directory to adjust opening actions for open-object-drawer manipulation tasks', 'skip already processed HDF5 demonstration groups that contain an edited flag to avoid duplicate edits', 'batch edit end-effector pose data across multiple HDF5 demonstration files using a glob template pattern', 'run the label interaction points script in read mode to show labeled points from H5 dataset files', 'run the label interaction points script in write mode to label interaction points on point clouds', 'run the pick points function to interactively select points from an Open3D point cloud visualization', 'review the pick points function that uses Open3D VisualizerWithEditing for interactive point selection', 'summarize the main CLI entry point that iterates H5 files and labels interaction points in read or write mode', 'run the full_rename CLI to batch rename task names in H5 files using a YAML config mapping', 'run the rename_edits CLI to rename a specific task name from one key to another in H5 files', 'refactor the full_rename function to support additional file formats beyond H5 for task name renaming', 'review the rename_edits function that renames task names from a source key to a target key in H5 groups', 'summarize the full_rename function that reads a YAML config and renames task names across all matching H5 files']
```

Usage

```
{'run_edit_opening_drawer': 'run the script to move opening actions farther back by 10 cm along y-axis for drawer tasks', 'edit_h5_demonstrations': 'edit HDF5 demonstration files to shift end-effector pose positions along the y-axis by 0.1 meters', 'process_drawer_demonstrations': 'process all HDF5 files in a directory to adjust opening actions for open-object-drawer manipulation tasks', 'skip_edited_demonstrations': 'skip already processed HDF5 demonstration groups that contain an edited flag to avoid duplicate edits', 'batch_edit_ee_pose': 'batch edit end-effector pose data across multiple HDF5 demonstration files using a glob template pattern'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/scripts/label_interaction_points.py

Prompts

```
['run the script in read mode to predict and save semantic frames from H5 episode data', 'run the script in write mode to add Detic semantic frames and masks to H5 files', 'run the script in visualize mode to display existing semantic frames from processed H5 files', 'refactor the sandwich function to wrap a list of object categories between other tokens', 'review the TASK_TO_OBJECT_MAP dictionary that maps task names to target object categories for detection', 'run the script to move opening actions farther back by 10 cm along y-axis for drawer tasks', 'edit HDF5 demonstration files to shift end-effector pose positions along the y-axis by 0.1 meters', 'process all HDF5 files in a directory to adjust opening actions for open-object-drawer manipulation tasks', 'skip already processed HDF5 demonstration groups that contain an edited flag to avoid duplicate edits', 'batch edit end-effector pose data across multiple HDF5 demonstration files using a glob template pattern', 'run the label interaction points script in read mode to show labeled points from H5 dataset files', 'run the label interaction points script in write mode to label interaction points on point clouds', 'run the pick points function to interactively select points from an Open3D point cloud visualization', 'review the pick points function that uses Open3D VisualizerWithEditing for interactive point selection', 'summarize the main CLI entry point that iterates H5 files and labels interaction points in read or write mode', 'run the full_rename CLI to batch rename task names in H5 files using a YAML config mapping', 'run the rename_edits CLI to rename a specific task name from one key to another in H5 files', 'refactor the full_rename function to support additional file formats beyond H5 for task name renaming', 'review the rename_edits function that renames task names from a source key to a target key in H5 groups', 'summarize the full_rename function that reads a YAML config and renames task names across all matching H5 files']
```

Usage

```
{'run_label_interaction_points_read': 'run the label interaction points script in read mode to show labeled points from H5 dataset files', 'run_label_interaction_points_write': 'run the label interaction points script in write mode to label interaction points on point clouds', 'run_pick_points': 'run the pick points function to interactively select points from an Open3D point cloud visualization', 'review_pick_points': 'review the pick points function that uses Open3D VisualizerWithEditing for interactive point selection', 'summarize_main': 'summarize the main CLI entry point that iterates H5 files and labels interaction points in read or write mode'}
```

## File: facebookresearch_home-robot/projects/slap_manipulation/scripts/rename_task_names.py

Prompts

```
['run the script in read mode to predict and save semantic frames from H5 episode data', 'run the script in write mode to add Detic semantic frames and masks to H5 files', 'run the script in visualize mode to display existing semantic frames from processed H5 files', 'refactor the sandwich function to wrap a list of object categories between other tokens', 'review the TASK_TO_OBJECT_MAP dictionary that maps task names to target object categories for detection', 'run the script to move opening actions farther back by 10 cm along y-axis for drawer tasks', 'edit HDF5 demonstration files to shift end-effector pose positions along the y-axis by 0.1 meters', 'process all HDF5 files in a directory to adjust opening actions for open-object-drawer manipulation tasks', 'skip already processed HDF5 demonstration groups that contain an edited flag to avoid duplicate edits', 'batch edit end-effector pose data across multiple HDF5 demonstration files using a glob template pattern', 'run the label interaction points script in read mode to show labeled points from H5 dataset files', 'run the label interaction points script in write mode to label interaction points on point clouds', 'run the pick points function to interactively select points from an Open3D point cloud visualization', 'review the pick points function that uses Open3D VisualizerWithEditing for interactive point selection', 'summarize the main CLI entry point that iterates H5 files and labels interaction points in read or write mode', 'run the full_rename CLI to batch rename task names in H5 files using a YAML config mapping', 'run the rename_edits CLI to rename a specific task name from one key to another in H5 files', 'refactor the full_rename function to support additional file formats beyond H5 for task name renaming', 'review the rename_edits function that renames task names from a source key to a target key in H5 groups', 'summarize the full_rename function that reads a YAML config and renames task names across all matching H5 files']
```

Usage

```
{'run_full_rename': 'run the full_rename CLI to batch rename task names in H5 files using a YAML config mapping', 'run_rename_edits': 'run the rename_edits CLI to rename a specific task name from one key to another in H5 files', 'refactor_full_rename': 'refactor the full_rename function to support additional file formats beyond H5 for task name renaming', 'review_rename_edits': 'review the rename_edits function that renames task names from a source key to a target key in H5 groups', 'summarize_full_rename': 'summarize the full_rename function that reads a YAML config and renames task names across all matching H5 files'}
```


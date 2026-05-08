# Agent Python Tools

- repo: facebookresearch/quaternet
- repo_uri: https://github.com/facebookresearch/quaternet

## File: facebookresearch_quaternet/prepare_data_long_term.py

Prompts

```
['run the script to download and prepare the Holden et al. locomotion dataset as a compressed npz file', 'run the script to process BVH motion capture files into root trajectories and quaternion rotations', 'run the script to download, extract, and convert the MotionSynth dataset to numpy format', 'review the process_file function that loads BVH files and extracts positions, rotations, and action classes', 'review the get_files function that lists BVH files in a directory excluding rest.bvh', 'run the script to download and prepare the Human3.6M dataset as a compressed NPZ file', 'run the script to read an expmap format CSV file and return a NumPy tensor', 'run the script to convert exponential map data to quaternion format with antipodal fixes', 'run the script to save trajectories, rotations, subjects, and actions to a compressed NPZ file', 'run the script to download and extract the Human3.6M dataset zip archive', 'run the short-term human pose prediction evaluation on H3.6M test subjects and actions', 'find random test sequence indices for SRNN-style motion prediction evaluation with a fixed seed', 'build a sequence map from H3.6M mocap data filtering for valid action-subject rotation sequences', 'get test data sequences for a specific action and subject from the H3.6M dataset', 'evaluate a pose prediction model on test data and compute per-frame prediction errors']
```

Usage

```
{'run_prepare_locomotion_dataset': 'run the script to download and prepare the Holden et al. locomotion dataset as a compressed npz file', 'run_process_bvh_files': 'run the script to process BVH motion capture files into root trajectories and quaternion rotations', 'run_extract_motionsynth_data': 'run the script to download, extract, and convert the MotionSynth dataset to numpy format', 'review_process_file_function': 'review the process_file function that loads BVH files and extracts positions, rotations, and action classes', 'review_get_files_function': 'review the get_files function that lists BVH files in a directory excluding rest.bvh'}
```

## File: facebookresearch_quaternet/prepare_data_short_term.py

Prompts

```
['run the script to download and prepare the Holden et al. locomotion dataset as a compressed npz file', 'run the script to process BVH motion capture files into root trajectories and quaternion rotations', 'run the script to download, extract, and convert the MotionSynth dataset to numpy format', 'review the process_file function that loads BVH files and extracts positions, rotations, and action classes', 'review the get_files function that lists BVH files in a directory excluding rest.bvh', 'run the script to download and prepare the Human3.6M dataset as a compressed NPZ file', 'run the script to read an expmap format CSV file and return a NumPy tensor', 'run the script to convert exponential map data to quaternion format with antipodal fixes', 'run the script to save trajectories, rotations, subjects, and actions to a compressed NPZ file', 'run the script to download and extract the Human3.6M dataset zip archive', 'run the short-term human pose prediction evaluation on H3.6M test subjects and actions', 'find random test sequence indices for SRNN-style motion prediction evaluation with a fixed seed', 'build a sequence map from H3.6M mocap data filtering for valid action-subject rotation sequences', 'get test data sequences for a specific action and subject from the H3.6M dataset', 'evaluate a pose prediction model on test data and compute per-frame prediction errors']
```

Usage

```
{'run_prepare_h36m_dataset': 'run the script to download and prepare the Human3.6M dataset as a compressed NPZ file', 'run_read_expmap_file': 'run the script to read an expmap format CSV file and return a NumPy tensor', 'run_convert_expmap_to_quaternion': 'run the script to convert exponential map data to quaternion format with antipodal fixes', 'run_save_dataset_npz': 'run the script to save trajectories, rotations, subjects, and actions to a compressed NPZ file', 'run_extract_h36m_zip': 'run the script to download and extract the Human3.6M dataset zip archive'}
```

## File: facebookresearch_quaternet/test_short_term.py

Prompts

```
['run the script to download and prepare the Holden et al. locomotion dataset as a compressed npz file', 'run the script to process BVH motion capture files into root trajectories and quaternion rotations', 'run the script to download, extract, and convert the MotionSynth dataset to numpy format', 'review the process_file function that loads BVH files and extracts positions, rotations, and action classes', 'review the get_files function that lists BVH files in a directory excluding rest.bvh', 'run the script to download and prepare the Human3.6M dataset as a compressed NPZ file', 'run the script to read an expmap format CSV file and return a NumPy tensor', 'run the script to convert exponential map data to quaternion format with antipodal fixes', 'run the script to save trajectories, rotations, subjects, and actions to a compressed NPZ file', 'run the script to download and extract the Human3.6M dataset zip archive', 'run the short-term human pose prediction evaluation on H3.6M test subjects and actions', 'find random test sequence indices for SRNN-style motion prediction evaluation with a fixed seed', 'build a sequence map from H3.6M mocap data filtering for valid action-subject rotation sequences', 'get test data sequences for a specific action and subject from the H3.6M dataset', 'evaluate a pose prediction model on test data and compute per-frame prediction errors']
```

Usage

```
{'run_evaluation_short_term_pose': 'run the short-term human pose prediction evaluation on H3.6M test subjects and actions', 'find_indices_srnn': 'find random test sequence indices for SRNN-style motion prediction evaluation with a fixed seed', 'build_sequence_map_srnn': 'build a sequence map from H3.6M mocap data filtering for valid action-subject rotation sequences', 'get_test_data': 'get test data sequences for a specific action and subject from the H3.6M dataset', 'evaluate_pose_model': 'evaluate a pose prediction model on test data and compute per-frame prediction errors'}
```


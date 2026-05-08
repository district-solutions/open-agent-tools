# Agent Python Tools

- repo: facebookresearch/fairmotion
- repo_uri: https://github.com/facebookresearch/fairmotion

## File: facebookresearch_fairmotion/fairmotion/data/amass.py

Prompts

```
['load an AMASS npz motion capture file into a fairmotion Motion object using a SMPL body model path', 'load multiple AMASS npz files in parallel using a configurable number of CPU cores', 'create a fairmotion Skeleton from a SMPL body model, betas, joint count, and joint names', 'create a fairmotion Motion object from an AMASS npz file and a loaded SMPL body model', 'load a SMPL or SMPL-H body model from a file path with configurable beta count', 'load an AMASS motion capture pickle file into a fairmotion Motion object with skeleton and pose data', 'load only the SMPL skeleton structure from an AMASS pickle file without loading motion frames', 'load AMASS motion data into an existing Motion object that already has a skeleton attached', 'load an AMASS pickle file with a custom scale factor to normalize joint offsets', 'load an AMASS pickle file with custom up and face vectors for skeleton orientation', 'parse an ASF skeleton file and extract joint data including direction, length, axis, and hierarchy', 'parse an AMC motion file with joint degrees and return a Motion object with pose data', 'load ASF skeleton and AMC motion data from files into a Motion or Skeleton object', 'set rotation matrices on joints using Euler-to-rotation conversion and propagate to child joints', 'read and split a line from a text stream at a given index and advance the index', 'load a BVH motion capture file into a Motion object with skeleton and frame data', 'save a Motion object to a BVH file with configurable rotation order and scale', 'load a BVH file and compute velocity data for each frame in the motion', 'load multiple BVH files in parallel using a specified number of CPU cores', 'review the load function to understand BVH hierarchy parsing and motion data extraction', 'load a FrankMoCap pickle file into a Motion object with skeleton and pose data', 'load a specific motion key from a FrankMoCap pickle file using the motion_key parameter', 'load a FrankMoCap motion file with a custom body model path via bm_path', 'review the load function to understand how FrankMoCap pickle data is converted to Motion objects', 'summarize the load function parameters including scale, skeleton vectors, and motion loading options']
```

Usage

```
{'load_amass_motion': 'load an AMASS npz motion capture file into a fairmotion Motion object using a SMPL body model path', 'load_amass_motion_parallel': 'load multiple AMASS npz files in parallel using a configurable number of CPU cores', 'create_skeleton_from_amass_bodymodel': 'create a fairmotion Skeleton from a SMPL body model, betas, joint count, and joint names', 'create_motion_from_amass_data': 'create a fairmotion Motion object from an AMASS npz file and a loaded SMPL body model', 'load_smpl_body_model': 'load a SMPL or SMPL-H body model from a file path with configurable beta count'}
```

## File: facebookresearch_fairmotion/fairmotion/data/amass_dip.py

Prompts

```
['load an AMASS npz motion capture file into a fairmotion Motion object using a SMPL body model path', 'load multiple AMASS npz files in parallel using a configurable number of CPU cores', 'create a fairmotion Skeleton from a SMPL body model, betas, joint count, and joint names', 'create a fairmotion Motion object from an AMASS npz file and a loaded SMPL body model', 'load a SMPL or SMPL-H body model from a file path with configurable beta count', 'load an AMASS motion capture pickle file into a fairmotion Motion object with skeleton and pose data', 'load only the SMPL skeleton structure from an AMASS pickle file without loading motion frames', 'load AMASS motion data into an existing Motion object that already has a skeleton attached', 'load an AMASS pickle file with a custom scale factor to normalize joint offsets', 'load an AMASS pickle file with custom up and face vectors for skeleton orientation', 'parse an ASF skeleton file and extract joint data including direction, length, axis, and hierarchy', 'parse an AMC motion file with joint degrees and return a Motion object with pose data', 'load ASF skeleton and AMC motion data from files into a Motion or Skeleton object', 'set rotation matrices on joints using Euler-to-rotation conversion and propagate to child joints', 'read and split a line from a text stream at a given index and advance the index', 'load a BVH motion capture file into a Motion object with skeleton and frame data', 'save a Motion object to a BVH file with configurable rotation order and scale', 'load a BVH file and compute velocity data for each frame in the motion', 'load multiple BVH files in parallel using a specified number of CPU cores', 'review the load function to understand BVH hierarchy parsing and motion data extraction', 'load a FrankMoCap pickle file into a Motion object with skeleton and pose data', 'load a specific motion key from a FrankMoCap pickle file using the motion_key parameter', 'load a FrankMoCap motion file with a custom body model path via bm_path', 'review the load function to understand how FrankMoCap pickle data is converted to Motion objects', 'summarize the load function parameters including scale, skeleton vectors, and motion loading options']
```

Usage

```
{'load_amass_motion_from_pickle': 'load an AMASS motion capture pickle file into a fairmotion Motion object with skeleton and pose data', 'load_amass_skeleton_only': 'load only the SMPL skeleton structure from an AMASS pickle file without loading motion frames', 'load_amass_motion_into_existing': 'load AMASS motion data into an existing Motion object that already has a skeleton attached', 'load_amass_with_custom_scale': 'load an AMASS pickle file with a custom scale factor to normalize joint offsets', 'load_amass_with_custom_orientation': 'load an AMASS pickle file with custom up and face vectors for skeleton orientation'}
```

## File: facebookresearch_fairmotion/fairmotion/data/asfamc.py

Prompts

```
['load an AMASS npz motion capture file into a fairmotion Motion object using a SMPL body model path', 'load multiple AMASS npz files in parallel using a configurable number of CPU cores', 'create a fairmotion Skeleton from a SMPL body model, betas, joint count, and joint names', 'create a fairmotion Motion object from an AMASS npz file and a loaded SMPL body model', 'load a SMPL or SMPL-H body model from a file path with configurable beta count', 'load an AMASS motion capture pickle file into a fairmotion Motion object with skeleton and pose data', 'load only the SMPL skeleton structure from an AMASS pickle file without loading motion frames', 'load AMASS motion data into an existing Motion object that already has a skeleton attached', 'load an AMASS pickle file with a custom scale factor to normalize joint offsets', 'load an AMASS pickle file with custom up and face vectors for skeleton orientation', 'parse an ASF skeleton file and extract joint data including direction, length, axis, and hierarchy', 'parse an AMC motion file with joint degrees and return a Motion object with pose data', 'load ASF skeleton and AMC motion data from files into a Motion or Skeleton object', 'set rotation matrices on joints using Euler-to-rotation conversion and propagate to child joints', 'read and split a line from a text stream at a given index and advance the index', 'load a BVH motion capture file into a Motion object with skeleton and frame data', 'save a Motion object to a BVH file with configurable rotation order and scale', 'load a BVH file and compute velocity data for each frame in the motion', 'load multiple BVH files in parallel using a specified number of CPU cores', 'review the load function to understand BVH hierarchy parsing and motion data extraction', 'load a FrankMoCap pickle file into a Motion object with skeleton and pose data', 'load a specific motion key from a FrankMoCap pickle file using the motion_key parameter', 'load a FrankMoCap motion file with a custom body model path via bm_path', 'review the load function to understand how FrankMoCap pickle data is converted to Motion objects', 'summarize the load function parameters including scale, skeleton vectors, and motion loading options']
```

Usage

```
{'parse_asf_skeleton': 'parse an ASF skeleton file and extract joint data including direction, length, axis, and hierarchy', 'parse_amc_motion': 'parse an AMC motion file with joint degrees and return a Motion object with pose data', 'load_asfamc_data': 'load ASF skeleton and AMC motion data from files into a Motion or Skeleton object', 'set_rotation_joints': 'set rotation matrices on joints using Euler-to-rotation conversion and propagate to child joints', 'read_line_stream': 'read and split a line from a text stream at a given index and advance the index'}
```

## File: facebookresearch_fairmotion/fairmotion/data/bvh.py

Prompts

```
['load an AMASS npz motion capture file into a fairmotion Motion object using a SMPL body model path', 'load multiple AMASS npz files in parallel using a configurable number of CPU cores', 'create a fairmotion Skeleton from a SMPL body model, betas, joint count, and joint names', 'create a fairmotion Motion object from an AMASS npz file and a loaded SMPL body model', 'load a SMPL or SMPL-H body model from a file path with configurable beta count', 'load an AMASS motion capture pickle file into a fairmotion Motion object with skeleton and pose data', 'load only the SMPL skeleton structure from an AMASS pickle file without loading motion frames', 'load AMASS motion data into an existing Motion object that already has a skeleton attached', 'load an AMASS pickle file with a custom scale factor to normalize joint offsets', 'load an AMASS pickle file with custom up and face vectors for skeleton orientation', 'parse an ASF skeleton file and extract joint data including direction, length, axis, and hierarchy', 'parse an AMC motion file with joint degrees and return a Motion object with pose data', 'load ASF skeleton and AMC motion data from files into a Motion or Skeleton object', 'set rotation matrices on joints using Euler-to-rotation conversion and propagate to child joints', 'read and split a line from a text stream at a given index and advance the index', 'load a BVH motion capture file into a Motion object with skeleton and frame data', 'save a Motion object to a BVH file with configurable rotation order and scale', 'load a BVH file and compute velocity data for each frame in the motion', 'load multiple BVH files in parallel using a specified number of CPU cores', 'review the load function to understand BVH hierarchy parsing and motion data extraction', 'load a FrankMoCap pickle file into a Motion object with skeleton and pose data', 'load a specific motion key from a FrankMoCap pickle file using the motion_key parameter', 'load a FrankMoCap motion file with a custom body model path via bm_path', 'review the load function to understand how FrankMoCap pickle data is converted to Motion objects', 'summarize the load function parameters including scale, skeleton vectors, and motion loading options']
```

Usage

```
{'load_bvh_file': 'load a BVH motion capture file into a Motion object with skeleton and frame data', 'save_bvh_file': 'save a Motion object to a BVH file with configurable rotation order and scale', 'load_bvh_with_velocity': 'load a BVH file and compute velocity data for each frame in the motion', 'load_parallel_bvh_files': 'load multiple BVH files in parallel using a specified number of CPU cores', 'review_bvh_load_function': 'review the load function to understand BVH hierarchy parsing and motion data extraction'}
```

## File: facebookresearch_fairmotion/fairmotion/data/frankmocap.py

Prompts

```
['load an AMASS npz motion capture file into a fairmotion Motion object using a SMPL body model path', 'load multiple AMASS npz files in parallel using a configurable number of CPU cores', 'create a fairmotion Skeleton from a SMPL body model, betas, joint count, and joint names', 'create a fairmotion Motion object from an AMASS npz file and a loaded SMPL body model', 'load a SMPL or SMPL-H body model from a file path with configurable beta count', 'load an AMASS motion capture pickle file into a fairmotion Motion object with skeleton and pose data', 'load only the SMPL skeleton structure from an AMASS pickle file without loading motion frames', 'load AMASS motion data into an existing Motion object that already has a skeleton attached', 'load an AMASS pickle file with a custom scale factor to normalize joint offsets', 'load an AMASS pickle file with custom up and face vectors for skeleton orientation', 'parse an ASF skeleton file and extract joint data including direction, length, axis, and hierarchy', 'parse an AMC motion file with joint degrees and return a Motion object with pose data', 'load ASF skeleton and AMC motion data from files into a Motion or Skeleton object', 'set rotation matrices on joints using Euler-to-rotation conversion and propagate to child joints', 'read and split a line from a text stream at a given index and advance the index', 'load a BVH motion capture file into a Motion object with skeleton and frame data', 'save a Motion object to a BVH file with configurable rotation order and scale', 'load a BVH file and compute velocity data for each frame in the motion', 'load multiple BVH files in parallel using a specified number of CPU cores', 'review the load function to understand BVH hierarchy parsing and motion data extraction', 'load a FrankMoCap pickle file into a Motion object with skeleton and pose data', 'load a specific motion key from a FrankMoCap pickle file using the motion_key parameter', 'load a FrankMoCap motion file with a custom body model path via bm_path', 'review the load function to understand how FrankMoCap pickle data is converted to Motion objects', 'summarize the load function parameters including scale, skeleton vectors, and motion loading options']
```

Usage

```
{'load_frankmocap_motion': 'load a FrankMoCap pickle file into a Motion object with skeleton and pose data', 'load_frankmocap_with_key': 'load a specific motion key from a FrankMoCap pickle file using the motion_key parameter', 'load_frankmocap_with_bodymodel': 'load a FrankMoCap motion file with a custom body model path via bm_path', 'review_load_function': 'review the load function to understand how FrankMoCap pickle data is converted to Motion objects', 'summarize_load_function': 'summarize the load function parameters including scale, skeleton vectors, and motion loading options'}
```


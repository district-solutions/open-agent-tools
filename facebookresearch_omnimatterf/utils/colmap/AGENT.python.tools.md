# Agent Python Tools

- repo: facebookresearch/omnimatterf
- repo_uri: https://github.com/facebookresearch/omnimatterf

## File: facebookresearch_omnimatterf/utils/colmap/colmap_read_model.py

Prompts

```
['run the script to read a COLMAP model folder and print camera, image, and 3D point counts', 'read a COLMAP reconstruction model from text or binary format returning cameras, images, and 3D points', 'convert a COLMAP quaternion vector into a 3x3 rotation matrix using qvec2rotmat', 'convert a 3x3 rotation matrix back into a COLMAP quaternion vector using rotmat2qvec', 'read COLMAP camera parameters from a text or binary file and return a dict of Camera namedtuples', 'run gen_poses to convert a COLMAP sparse output directory into poses_bounds.npy', 'run load_colmap_data to read COLMAP cameras, images, and points3D binary files into numpy arrays', 'run save_poses to compute depth bounds and save camera poses with visibility masks to disk', 'run the CLI module with --input flag pointing to a COLMAP output directory to generate poses', 'review load_colmap_data to understand how COLMAP binary data is parsed and coordinate frames are converted']
```

Usage

```
{'run_read_model': 'run the script to read a COLMAP model folder and print camera, image, and 3D point counts', 'read_model_cameras_images_points3D': 'read a COLMAP reconstruction model from text or binary format returning cameras, images, and 3D points', 'convert_qvec_to_rotmat': 'convert a COLMAP quaternion vector into a 3x3 rotation matrix using qvec2rotmat', 'convert_rotmat_to_qvec': 'convert a 3x3 rotation matrix back into a COLMAP quaternion vector using rotmat2qvec', 'read_cameras_text_or_binary': 'read COLMAP camera parameters from a text or binary file and return a dict of Camera namedtuples'}
```

## File: facebookresearch_omnimatterf/utils/colmap/colmap_utils.py

Prompts

```
['run the script to read a COLMAP model folder and print camera, image, and 3D point counts', 'read a COLMAP reconstruction model from text or binary format returning cameras, images, and 3D points', 'convert a COLMAP quaternion vector into a 3x3 rotation matrix using qvec2rotmat', 'convert a 3x3 rotation matrix back into a COLMAP quaternion vector using rotmat2qvec', 'read COLMAP camera parameters from a text or binary file and return a dict of Camera namedtuples', 'run gen_poses to convert a COLMAP sparse output directory into poses_bounds.npy', 'run load_colmap_data to read COLMAP cameras, images, and points3D binary files into numpy arrays', 'run save_poses to compute depth bounds and save camera poses with visibility masks to disk', 'run the CLI module with --input flag pointing to a COLMAP output directory to generate poses', 'review load_colmap_data to understand how COLMAP binary data is parsed and coordinate frames are converted']
```

Usage

```
{'run_gen_poses': 'run gen_poses to convert a COLMAP sparse output directory into poses_bounds.npy', 'run_load_colmap_data': 'run load_colmap_data to read COLMAP cameras, images, and points3D binary files into numpy arrays', 'run_save_poses': 'run save_poses to compute depth bounds and save camera poses with visibility masks to disk', 'run_main_cli': 'run the CLI module with --input flag pointing to a COLMAP output directory to generate poses', 'review_load_colmap_data': 'review load_colmap_data to understand how COLMAP binary data is parsed and coordinate frames are converted'}
```


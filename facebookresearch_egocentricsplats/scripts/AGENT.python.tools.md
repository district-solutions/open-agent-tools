# Agent Python Tools

- repo: facebookresearch/egocentricsplats
- repo_uri: https://github.com/facebookresearch/egocentric_splats

## File: facebookresearch_egocentricsplats/scripts/aria_utils.py

Prompts

```
['undistort a raw Aria camera frame using fisheye624 calibration to linear or spherical output', 'process an Aria frame by undistorting the image and saving it to an output folder with metadata', 'interpolate a closed-loop trajectory pose at a given capture timestamp using bisection search', 'read and parse frame metadata from a transforms JSON file into a list of AriaFrame objects', 'store 3D point cloud data with xyz coordinates, normals, and rgb colors to a PLY file', 'run the python downloader script to download all sequences and data types from a CDN file', 'run the python downloader script to download specific sequences by name from a CDN file', 'run the python downloader script to download specific data types by index from a CDN file', 'run the python downloader script with overwrite flag to redownload previously downloaded sequences', 'review the python parse_args function that defines CLI arguments for CDN file, output folder, and data types', 'extract Aria VRS frames with camera poses and calibration into JSON format using the CLI', 'run a single Aria VRS recording extraction with trajectory and semi-dense point cloud inputs', 'convert raw Aria VRS sensor data into structured image frames with rolling shutter timestamps', 'create sparse depth maps for SLAM camera frames using semi-dense point cloud observations', 'fetch and project sparse depth points from SLAM cameras into the RGB camera frustum']
```

Usage

```
{'undistort_image': 'undistort a raw Aria camera frame using fisheye624 calibration to linear or spherical output', 'process_frame': 'process an Aria frame by undistorting the image and saving it to an output folder with metadata', 'interpolate_aria_pose': 'interpolate a closed-loop trajectory pose at a given capture timestamp using bisection search', 'read_frames_from_metadata': 'read and parse frame metadata from a transforms JSON file into a list of AriaFrame objects', 'storePly': 'store 3D point cloud data with xyz coordinates, normals, and rgb colors to a PLY file'}
```

## File: facebookresearch_egocentricsplats/scripts/downloader.py

Prompts

```
['undistort a raw Aria camera frame using fisheye624 calibration to linear or spherical output', 'process an Aria frame by undistorting the image and saving it to an output folder with metadata', 'interpolate a closed-loop trajectory pose at a given capture timestamp using bisection search', 'read and parse frame metadata from a transforms JSON file into a list of AriaFrame objects', 'store 3D point cloud data with xyz coordinates, normals, and rgb colors to a PLY file', 'run the python downloader script to download all sequences and data types from a CDN file', 'run the python downloader script to download specific sequences by name from a CDN file', 'run the python downloader script to download specific data types by index from a CDN file', 'run the python downloader script with overwrite flag to redownload previously downloaded sequences', 'review the python parse_args function that defines CLI arguments for CDN file, output folder, and data types', 'extract Aria VRS frames with camera poses and calibration into JSON format using the CLI', 'run a single Aria VRS recording extraction with trajectory and semi-dense point cloud inputs', 'convert raw Aria VRS sensor data into structured image frames with rolling shutter timestamps', 'create sparse depth maps for SLAM camera frames using semi-dense point cloud observations', 'fetch and project sparse depth points from SLAM cameras into the RGB camera frustum']
```

Usage

```
{'run_downloader_all': 'run the python downloader script to download all sequences and data types from a CDN file', 'run_downloader_specific_sequences': 'run the python downloader script to download specific sequences by name from a CDN file', 'run_downloader_specific_data_types': 'run the python downloader script to download specific data types by index from a CDN file', 'run_downloader_overwrite': 'run the python downloader script with overwrite flag to redownload previously downloaded sequences', 'review_parse_args': 'review the python parse_args function that defines CLI arguments for CDN file, output folder, and data types'}
```

## File: facebookresearch_egocentricsplats/scripts/extract_aria_vrs.py

Prompts

```
['undistort a raw Aria camera frame using fisheye624 calibration to linear or spherical output', 'process an Aria frame by undistorting the image and saving it to an output folder with metadata', 'interpolate a closed-loop trajectory pose at a given capture timestamp using bisection search', 'read and parse frame metadata from a transforms JSON file into a list of AriaFrame objects', 'store 3D point cloud data with xyz coordinates, normals, and rgb colors to a PLY file', 'run the python downloader script to download all sequences and data types from a CDN file', 'run the python downloader script to download specific sequences by name from a CDN file', 'run the python downloader script to download specific data types by index from a CDN file', 'run the python downloader script with overwrite flag to redownload previously downloaded sequences', 'review the python parse_args function that defines CLI arguments for CDN file, output folder, and data types', 'extract Aria VRS frames with camera poses and calibration into JSON format using the CLI', 'run a single Aria VRS recording extraction with trajectory and semi-dense point cloud inputs', 'convert raw Aria VRS sensor data into structured image frames with rolling shutter timestamps', 'create sparse depth maps for SLAM camera frames using semi-dense point cloud observations', 'fetch and project sparse depth points from SLAM cameras into the RGB camera frustum']
```

Usage

```
{'extract_aria_vrs_frames': 'extract Aria VRS frames with camera poses and calibration into JSON format using the CLI', 'run_single_sequence': 'run a single Aria VRS recording extraction with trajectory and semi-dense point cloud inputs', 'to_aria_image_frame': 'convert raw Aria VRS sensor data into structured image frames with rolling shutter timestamps', 'create_visible_depth_map': 'create sparse depth maps for SLAM camera frames using semi-dense point cloud observations', 'fetch_visible_depth_map_for_RGB': 'fetch and project sparse depth points from SLAM cameras into the RGB camera frustum'}
```


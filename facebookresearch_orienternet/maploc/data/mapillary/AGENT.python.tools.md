# Agent Python Tools

- repo: facebookresearch/orienternet
- repo_uri: https://github.com/facebookresearch/orienternet

## File: facebookresearch_orienternet/maploc/data/mapillary/dataset.py

Prompts

```
['create numpy arrays from dump dictionary points, views, and camera params for efficient memory sharing', 'build a PyTorch Lightning data module for Mapillary street-level imagery with configurable scenes and splits', 'test the MapillaryDataModule setup method to load tile managers, dumps, and validate camera models', 'refactor the filter_elements method to filter images by ground plane height or point cloud observations', 'run a sequence dataloader that chunks and shuffles Mapillary image sequences for training', 'create a MapillaryDownloader instance with an API token to fetch Mapillary image data asynchronously', 'download image pixels from a Mapillary URL and save them to a local file path', 'fetch metadata for multiple image IDs concurrently using the MapillaryDownloader with caching support', 'create an OpenSfM Camera object from a Mapillary image info dictionary with perspective or fisheye support', 'create an OpenSfM Shot with camera and pose from a Mapillary image info dict and projection', 'run process_location to download and prepare Mapillary images for a given city location', 'run process_sequence to undistort and select keyframes from a list of image IDs', 'run process_shot to undistort a single camera shot and save the output image', 'run get_pano_offset to compute a deterministic random panorama offset from image metadata', 'run pack_shot_dict to serialize a Shot object with GPS and pose data into a dictionary', 'select keyframes from a list of shots based on minimum distance between camera centers', 'create a perspective camera from a panorama camera with a specified output size', 'scale a camera width and height down to fit within a maximum size', 'undistort a panorama image into four perspective views using PanoramaUndistorter and render_panorama', 'undistort a shot image handling panorama, perspective, or fisheye projection types with undistort_shot']
```

Usage

```
{'create_pack_dump_dict': 'create numpy arrays from dump dictionary points, views, and camera params for efficient memory sharing', 'build_mapillary_datamodule': 'build a PyTorch Lightning data module for Mapillary street-level imagery with configurable scenes and splits', 'test_mapillary_datamodule_setup': 'test the MapillaryDataModule setup method to load tile managers, dumps, and validate camera models', 'refactor_filter_elements': 'refactor the filter_elements method to filter images by ground plane height or point cloud observations', 'run_sequence_dataloader': 'run a sequence dataloader that chunks and shuffles Mapillary image sequences for training'}
```

## File: facebookresearch_orienternet/maploc/data/mapillary/download.py

Prompts

```
['create numpy arrays from dump dictionary points, views, and camera params for efficient memory sharing', 'build a PyTorch Lightning data module for Mapillary street-level imagery with configurable scenes and splits', 'test the MapillaryDataModule setup method to load tile managers, dumps, and validate camera models', 'refactor the filter_elements method to filter images by ground plane height or point cloud observations', 'run a sequence dataloader that chunks and shuffles Mapillary image sequences for training', 'create a MapillaryDownloader instance with an API token to fetch Mapillary image data asynchronously', 'download image pixels from a Mapillary URL and save them to a local file path', 'fetch metadata for multiple image IDs concurrently using the MapillaryDownloader with caching support', 'create an OpenSfM Camera object from a Mapillary image info dictionary with perspective or fisheye support', 'create an OpenSfM Shot with camera and pose from a Mapillary image info dict and projection', 'run process_location to download and prepare Mapillary images for a given city location', 'run process_sequence to undistort and select keyframes from a list of image IDs', 'run process_shot to undistort a single camera shot and save the output image', 'run get_pano_offset to compute a deterministic random panorama offset from image metadata', 'run pack_shot_dict to serialize a Shot object with GPS and pose data into a dictionary', 'select keyframes from a list of shots based on minimum distance between camera centers', 'create a perspective camera from a panorama camera with a specified output size', 'scale a camera width and height down to fit within a maximum size', 'undistort a panorama image into four perspective views using PanoramaUndistorter and render_panorama', 'undistort a shot image handling panorama, perspective, or fisheye projection types with undistort_shot']
```

Usage

```
{'create_MapillaryDownloader': 'create a MapillaryDownloader instance with an API token to fetch Mapillary image data asynchronously', 'download_image_pixels': 'download image pixels from a Mapillary URL and save them to a local file path', 'fetch_image_infos': 'fetch metadata for multiple image IDs concurrently using the MapillaryDownloader with caching support', 'opensfm_camera_from_info': 'create an OpenSfM Camera object from a Mapillary image info dictionary with perspective or fisheye support', 'opensfm_shot_from_info': 'create an OpenSfM Shot with camera and pose from a Mapillary image info dict and projection'}
```

## File: facebookresearch_orienternet/maploc/data/mapillary/prepare.py

Prompts

```
['create numpy arrays from dump dictionary points, views, and camera params for efficient memory sharing', 'build a PyTorch Lightning data module for Mapillary street-level imagery with configurable scenes and splits', 'test the MapillaryDataModule setup method to load tile managers, dumps, and validate camera models', 'refactor the filter_elements method to filter images by ground plane height or point cloud observations', 'run a sequence dataloader that chunks and shuffles Mapillary image sequences for training', 'create a MapillaryDownloader instance with an API token to fetch Mapillary image data asynchronously', 'download image pixels from a Mapillary URL and save them to a local file path', 'fetch metadata for multiple image IDs concurrently using the MapillaryDownloader with caching support', 'create an OpenSfM Camera object from a Mapillary image info dictionary with perspective or fisheye support', 'create an OpenSfM Shot with camera and pose from a Mapillary image info dict and projection', 'run process_location to download and prepare Mapillary images for a given city location', 'run process_sequence to undistort and select keyframes from a list of image IDs', 'run process_shot to undistort a single camera shot and save the output image', 'run get_pano_offset to compute a deterministic random panorama offset from image metadata', 'run pack_shot_dict to serialize a Shot object with GPS and pose data into a dictionary', 'select keyframes from a list of shots based on minimum distance between camera centers', 'create a perspective camera from a panorama camera with a specified output size', 'scale a camera width and height down to fit within a maximum size', 'undistort a panorama image into four perspective views using PanoramaUndistorter and render_panorama', 'undistort a shot image handling panorama, perspective, or fisheye projection types with undistort_shot']
```

Usage

```
{'run_process_location': 'run process_location to download and prepare Mapillary images for a given city location', 'run_process_sequence': 'run process_sequence to undistort and select keyframes from a list of image IDs', 'run_process_shot': 'run process_shot to undistort a single camera shot and save the output image', 'run_get_pano_offset': 'run get_pano_offset to compute a deterministic random panorama offset from image metadata', 'run_pack_shot_dict': 'run pack_shot_dict to serialize a Shot object with GPS and pose data into a dictionary'}
```

## File: facebookresearch_orienternet/maploc/data/mapillary/utils.py

Prompts

```
['create numpy arrays from dump dictionary points, views, and camera params for efficient memory sharing', 'build a PyTorch Lightning data module for Mapillary street-level imagery with configurable scenes and splits', 'test the MapillaryDataModule setup method to load tile managers, dumps, and validate camera models', 'refactor the filter_elements method to filter images by ground plane height or point cloud observations', 'run a sequence dataloader that chunks and shuffles Mapillary image sequences for training', 'create a MapillaryDownloader instance with an API token to fetch Mapillary image data asynchronously', 'download image pixels from a Mapillary URL and save them to a local file path', 'fetch metadata for multiple image IDs concurrently using the MapillaryDownloader with caching support', 'create an OpenSfM Camera object from a Mapillary image info dictionary with perspective or fisheye support', 'create an OpenSfM Shot with camera and pose from a Mapillary image info dict and projection', 'run process_location to download and prepare Mapillary images for a given city location', 'run process_sequence to undistort and select keyframes from a list of image IDs', 'run process_shot to undistort a single camera shot and save the output image', 'run get_pano_offset to compute a deterministic random panorama offset from image metadata', 'run pack_shot_dict to serialize a Shot object with GPS and pose data into a dictionary', 'select keyframes from a list of shots based on minimum distance between camera centers', 'create a perspective camera from a panorama camera with a specified output size', 'scale a camera width and height down to fit within a maximum size', 'undistort a panorama image into four perspective views using PanoramaUndistorter and render_panorama', 'undistort a shot image handling panorama, perspective, or fisheye projection types with undistort_shot']
```

Usage

```
{'select_keyframes_from_shots': 'select keyframes from a list of shots based on minimum distance between camera centers', 'create_perspective_camera_from_pano': 'create a perspective camera from a panorama camera with a specified output size', 'scale_camera_dimensions': 'scale a camera width and height down to fit within a maximum size', 'undistort_panorama_images': 'undistort a panorama image into four perspective views using PanoramaUndistorter and render_panorama', 'undistort_shot_images': 'undistort a shot image handling panorama, perspective, or fisheye projection types with undistort_shot'}
```


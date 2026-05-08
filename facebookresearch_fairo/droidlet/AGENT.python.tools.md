# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/base_util.py

Prompts

```
['convert a numpy array to a list of block tuples with xyz coordinates and id meta', 'convert a list of block tuples with xyz coordinates and id meta to a numpy array', 'compute the euclidean distance between two 3D position tuples', 'compute the manhattan distance between two 3D position tuples', 'perform depth-first search on a 3D block array starting from a given position', 'create a BackgroundTask with an init function and process function for multiprocessing', 'start a BackgroundTask process with an optional exec_empty flag for idle execution', 'put arguments into a BackgroundTask send queue and get results from the receive queue', 'create a PropagatingThread that propagates exceptions back to the parent thread on join', 'create a Process subclass that returns child exceptions to the parent via a Pipe', 'create an RGBDepth object from robot RGB image, depth map, and point cloud arrays', 'encode an RGBDepth object to a base64 struct with webp compressed RGB and depth images', 'get the axis-aligned bounding box coordinates for all points matching a given mask', 'convert a pixel point to canonical world coordinates using the RGBDepth point cloud', 'use a PriorityQueue that supports push, pop, contains, and replace operations with mutable priorities', 'download a single test asset file from an S3 bucket to a local folder', 'download multiple test asset files from an S3 bucket with caching to avoid re-downloads', 'skip a unittest test function if required test assets cannot be downloaded from S3', 'force re-download of cached test assets by passing refresh=True to download_assets', 'review the skipIfOfflineDecorator function that wraps test functions with asset download logic']
```

Usage

```
{'convert_numpy_to_blocks_list': 'convert a numpy array to a list of block tuples with xyz coordinates and id meta', 'convert_blocks_list_to_numpy': 'convert a list of block tuples with xyz coordinates and id meta to a numpy array', 'compute_euclidean_distance': 'compute the euclidean distance between two 3D position tuples', 'compute_manhattan_distance': 'compute the manhattan distance between two 3D position tuples', 'perform_depth_first_search': 'perform depth-first search on a 3D block array starting from a given position'}
```

## File: facebookresearch_fairo/droidlet/parallel.py

Prompts

```
['convert a numpy array to a list of block tuples with xyz coordinates and id meta', 'convert a list of block tuples with xyz coordinates and id meta to a numpy array', 'compute the euclidean distance between two 3D position tuples', 'compute the manhattan distance between two 3D position tuples', 'perform depth-first search on a 3D block array starting from a given position', 'create a BackgroundTask with an init function and process function for multiprocessing', 'start a BackgroundTask process with an optional exec_empty flag for idle execution', 'put arguments into a BackgroundTask send queue and get results from the receive queue', 'create a PropagatingThread that propagates exceptions back to the parent thread on join', 'create a Process subclass that returns child exceptions to the parent via a Pipe', 'create an RGBDepth object from robot RGB image, depth map, and point cloud arrays', 'encode an RGBDepth object to a base64 struct with webp compressed RGB and depth images', 'get the axis-aligned bounding box coordinates for all points matching a given mask', 'convert a pixel point to canonical world coordinates using the RGBDepth point cloud', 'use a PriorityQueue that supports push, pop, contains, and replace operations with mutable priorities', 'download a single test asset file from an S3 bucket to a local folder', 'download multiple test asset files from an S3 bucket with caching to avoid re-downloads', 'skip a unittest test function if required test assets cannot be downloaded from S3', 'force re-download of cached test assets by passing refresh=True to download_assets', 'review the skipIfOfflineDecorator function that wraps test functions with asset download logic']
```

Usage

```
{'create_background_task': 'create a BackgroundTask with an init function and process function for multiprocessing', 'start_background_task': 'start a BackgroundTask process with an optional exec_empty flag for idle execution', 'put_get_background_task': 'put arguments into a BackgroundTask send queue and get results from the receive queue', 'create_propagating_thread': 'create a PropagatingThread that propagates exceptions back to the parent thread on join', 'create_exception_process': 'create a Process subclass that returns child exceptions to the parent via a Pipe'}
```

## File: facebookresearch_fairo/droidlet/shared_data_structs.py

Prompts

```
['convert a numpy array to a list of block tuples with xyz coordinates and id meta', 'convert a list of block tuples with xyz coordinates and id meta to a numpy array', 'compute the euclidean distance between two 3D position tuples', 'compute the manhattan distance between two 3D position tuples', 'perform depth-first search on a 3D block array starting from a given position', 'create a BackgroundTask with an init function and process function for multiprocessing', 'start a BackgroundTask process with an optional exec_empty flag for idle execution', 'put arguments into a BackgroundTask send queue and get results from the receive queue', 'create a PropagatingThread that propagates exceptions back to the parent thread on join', 'create a Process subclass that returns child exceptions to the parent via a Pipe', 'create an RGBDepth object from robot RGB image, depth map, and point cloud arrays', 'encode an RGBDepth object to a base64 struct with webp compressed RGB and depth images', 'get the axis-aligned bounding box coordinates for all points matching a given mask', 'convert a pixel point to canonical world coordinates using the RGBDepth point cloud', 'use a PriorityQueue that supports push, pop, contains, and replace operations with mutable priorities', 'download a single test asset file from an S3 bucket to a local folder', 'download multiple test asset files from an S3 bucket with caching to avoid re-downloads', 'skip a unittest test function if required test assets cannot be downloaded from S3', 'force re-download of cached test assets by passing refresh=True to download_assets', 'review the skipIfOfflineDecorator function that wraps test functions with asset download logic']
```

Usage

```
{'create_RGBDepth_from_robot_data': 'create an RGBDepth object from robot RGB image, depth map, and point cloud arrays', 'encode_RGBDepth_to_base64_struct': 'encode an RGBDepth object to a base64 struct with webp compressed RGB and depth images', 'get_bounding_box_for_mask': 'get the axis-aligned bounding box coordinates for all points matching a given mask', 'convert_point_to_world_coords': 'convert a pixel point to canonical world coordinates using the RGBDepth point cloud', 'use_PriorityQueue_with_mutable_priorities': 'use a PriorityQueue that supports push, pop, contains, and replace operations with mutable priorities'}
```

## File: facebookresearch_fairo/droidlet/test_utils.py

Prompts

```
['convert a numpy array to a list of block tuples with xyz coordinates and id meta', 'convert a list of block tuples with xyz coordinates and id meta to a numpy array', 'compute the euclidean distance between two 3D position tuples', 'compute the manhattan distance between two 3D position tuples', 'perform depth-first search on a 3D block array starting from a given position', 'create a BackgroundTask with an init function and process function for multiprocessing', 'start a BackgroundTask process with an optional exec_empty flag for idle execution', 'put arguments into a BackgroundTask send queue and get results from the receive queue', 'create a PropagatingThread that propagates exceptions back to the parent thread on join', 'create a Process subclass that returns child exceptions to the parent via a Pipe', 'create an RGBDepth object from robot RGB image, depth map, and point cloud arrays', 'encode an RGBDepth object to a base64 struct with webp compressed RGB and depth images', 'get the axis-aligned bounding box coordinates for all points matching a given mask', 'convert a pixel point to canonical world coordinates using the RGBDepth point cloud', 'use a PriorityQueue that supports push, pop, contains, and replace operations with mutable priorities', 'download a single test asset file from an S3 bucket to a local folder', 'download multiple test asset files from an S3 bucket with caching to avoid re-downloads', 'skip a unittest test function if required test assets cannot be downloaded from S3', 'force re-download of cached test assets by passing refresh=True to download_assets', 'review the skipIfOfflineDecorator function that wraps test functions with asset download logic']
```

Usage

```
{'download_asset_from_s3': 'download a single test asset file from an S3 bucket to a local folder', 'download_multiple_assets': 'download multiple test asset files from an S3 bucket with caching to avoid re-downloads', 'skip_test_if_offline': 'skip a unittest test function if required test assets cannot be downloaded from S3', 'refresh_downloaded_assets': 'force re-download of cached test assets by passing refresh=True to download_assets', 'review_skipIfOfflineDecorator': 'review the skipIfOfflineDecorator function that wraps test functions with asset download logic'}
```


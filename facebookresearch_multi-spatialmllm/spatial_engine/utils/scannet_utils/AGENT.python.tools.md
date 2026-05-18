# Agent Python Tools

- repo: facebookresearch/multi-spatialmllm
- repo_uri: https://github.com/facebookresearch/multi-spatialmllm

## File: facebookresearch_multi-spatialmllm/spatial_engine/utils/scannet_utils/batch_load_scannet_data.py

Prompts

```
['run batch_export to process multiple Scannet scans in parallel and save aligned points and labels as numpy files', 'call export to load a single Scannet scene and return vertices, semantic labels, instance labels, and bounding boxes', 'run export_one_scan to process one Scannet scan with optional point sampling and save results to an output folder', 'use worker as a multiprocessing target to process individual Scannet scans in parallel via Pool.map', 'run main to parse CLI arguments and batch export both train and test Scannet datasets', 'run the script to extract RGB-D images, poses, and intrinsics from ScanNet .sens files', 'run process_directory to parallel-extract posed images from all ScanNet scenes in a folder', 'create a SensorData instance to load and parse a ScanNet .sens binary file with frame skipping', 'export color images, depth images, camera poses, and intrinsics from a SensorData object', 'decompress depth data with zlib or color data with jpeg from an RGBDFrame instance', 'run a split of ScanNet scenes to generate visibility info mapping images to 3D points in parallel', 'process a single ScanNet scene to compute which points each image sees and invert the mapping', 'convert a previously saved pickle visibility info file to a parquet file for efficient storage', 'create a bidirectional mapping between images and visible 3D points for all scenes in a ScanNet split', 'generate visibility information for train and val ScanNet splits and save as parquet files', 'read a ScanNet aggregation JSON file and return object-to-segments and label-to-segments mappings', 'read a ScanNet segmentation JSON file and return segment-to-vertices mapping with vertex count', 'extract bounding boxes and point clouds for each instance from mesh vertices and segment data', 'read a tab-delimited label mapping CSV file and return a category-to-NYU40 ID dictionary', 'read a PLY mesh file and return XYZ and RGB values for each vertex']
```

Usage

```
{'batch_export_scannet_scenes': 'run batch_export to process multiple Scannet scans in parallel and save aligned points and labels as numpy files', 'export_single_scan': 'call export to load a single Scannet scene and return vertices, semantic labels, instance labels, and bounding boxes', 'export_one_scan_with_sampling': 'run export_one_scan to process one Scannet scan with optional point sampling and save results to an output folder', 'worker_multiprocessing': 'use worker as a multiprocessing target to process individual Scannet scans in parallel via Pool.map', 'main_cli_entry': 'run main to parse CLI arguments and batch export both train and test Scannet datasets'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/utils/scannet_utils/extract_posed_images.py

Prompts

```
['run batch_export to process multiple Scannet scans in parallel and save aligned points and labels as numpy files', 'call export to load a single Scannet scene and return vertices, semantic labels, instance labels, and bounding boxes', 'run export_one_scan to process one Scannet scan with optional point sampling and save results to an output folder', 'use worker as a multiprocessing target to process individual Scannet scans in parallel via Pool.map', 'run main to parse CLI arguments and batch export both train and test Scannet datasets', 'run the script to extract RGB-D images, poses, and intrinsics from ScanNet .sens files', 'run process_directory to parallel-extract posed images from all ScanNet scenes in a folder', 'create a SensorData instance to load and parse a ScanNet .sens binary file with frame skipping', 'export color images, depth images, camera poses, and intrinsics from a SensorData object', 'decompress depth data with zlib or color data with jpeg from an RGBDFrame instance', 'run a split of ScanNet scenes to generate visibility info mapping images to 3D points in parallel', 'process a single ScanNet scene to compute which points each image sees and invert the mapping', 'convert a previously saved pickle visibility info file to a parquet file for efficient storage', 'create a bidirectional mapping between images and visible 3D points for all scenes in a ScanNet split', 'generate visibility information for train and val ScanNet splits and save as parquet files', 'read a ScanNet aggregation JSON file and return object-to-segments and label-to-segments mappings', 'read a ScanNet segmentation JSON file and return segment-to-vertices mapping with vertex count', 'extract bounding boxes and point clouds for each instance from mesh vertices and segment data', 'read a tab-delimited label mapping CSV file and return a category-to-NYU40 ID dictionary', 'read a PLY mesh file and return XYZ and RGB values for each vertex']
```

Usage

```
{'run_extract_posed_images': 'run the script to extract RGB-D images, poses, and intrinsics from ScanNet .sens files', 'run_process_directory': 'run process_directory to parallel-extract posed images from all ScanNet scenes in a folder', 'create_SensorData': 'create a SensorData instance to load and parse a ScanNet .sens binary file with frame skipping', 'export_SensorData_images': 'export color images, depth images, camera poses, and intrinsics from a SensorData object', 'decompress_RGBDFrame': 'decompress depth data with zlib or color data with jpeg from an RGBDFrame instance'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/utils/scannet_utils/make_visibility_info.py

Prompts

```
['run batch_export to process multiple Scannet scans in parallel and save aligned points and labels as numpy files', 'call export to load a single Scannet scene and return vertices, semantic labels, instance labels, and bounding boxes', 'run export_one_scan to process one Scannet scan with optional point sampling and save results to an output folder', 'use worker as a multiprocessing target to process individual Scannet scans in parallel via Pool.map', 'run main to parse CLI arguments and batch export both train and test Scannet datasets', 'run the script to extract RGB-D images, poses, and intrinsics from ScanNet .sens files', 'run process_directory to parallel-extract posed images from all ScanNet scenes in a folder', 'create a SensorData instance to load and parse a ScanNet .sens binary file with frame skipping', 'export color images, depth images, camera poses, and intrinsics from a SensorData object', 'decompress depth data with zlib or color data with jpeg from an RGBDFrame instance', 'run a split of ScanNet scenes to generate visibility info mapping images to 3D points in parallel', 'process a single ScanNet scene to compute which points each image sees and invert the mapping', 'convert a previously saved pickle visibility info file to a parquet file for efficient storage', 'create a bidirectional mapping between images and visible 3D points for all scenes in a ScanNet split', 'generate visibility information for train and val ScanNet splits and save as parquet files', 'read a ScanNet aggregation JSON file and return object-to-segments and label-to-segments mappings', 'read a ScanNet segmentation JSON file and return segment-to-vertices mapping with vertex count', 'extract bounding boxes and point clouds for each instance from mesh vertices and segment data', 'read a tab-delimited label mapping CSV file and return a category-to-NYU40 ID dictionary', 'read a PLY mesh file and return XYZ and RGB values for each vertex']
```

Usage

```
{'run_split': 'run a split of ScanNet scenes to generate visibility info mapping images to 3D points in parallel', 'process_scene': 'process a single ScanNet scene to compute which points each image sees and invert the mapping', 'convert_pkl_to_parquet': 'convert a previously saved pickle visibility info file to a parquet file for efficient storage', 'create_visibility_mapping': 'create a bidirectional mapping between images and visible 3D points for all scenes in a ScanNet split', 'generate_scene_visibility': 'generate visibility information for train and val ScanNet splits and save as parquet files'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/utils/scannet_utils/scannet_utils.py

Prompts

```
['run batch_export to process multiple Scannet scans in parallel and save aligned points and labels as numpy files', 'call export to load a single Scannet scene and return vertices, semantic labels, instance labels, and bounding boxes', 'run export_one_scan to process one Scannet scan with optional point sampling and save results to an output folder', 'use worker as a multiprocessing target to process individual Scannet scans in parallel via Pool.map', 'run main to parse CLI arguments and batch export both train and test Scannet datasets', 'run the script to extract RGB-D images, poses, and intrinsics from ScanNet .sens files', 'run process_directory to parallel-extract posed images from all ScanNet scenes in a folder', 'create a SensorData instance to load and parse a ScanNet .sens binary file with frame skipping', 'export color images, depth images, camera poses, and intrinsics from a SensorData object', 'decompress depth data with zlib or color data with jpeg from an RGBDFrame instance', 'run a split of ScanNet scenes to generate visibility info mapping images to 3D points in parallel', 'process a single ScanNet scene to compute which points each image sees and invert the mapping', 'convert a previously saved pickle visibility info file to a parquet file for efficient storage', 'create a bidirectional mapping between images and visible 3D points for all scenes in a ScanNet split', 'generate visibility information for train and val ScanNet splits and save as parquet files', 'read a ScanNet aggregation JSON file and return object-to-segments and label-to-segments mappings', 'read a ScanNet segmentation JSON file and return segment-to-vertices mapping with vertex count', 'extract bounding boxes and point clouds for each instance from mesh vertices and segment data', 'read a tab-delimited label mapping CSV file and return a category-to-NYU40 ID dictionary', 'read a PLY mesh file and return XYZ and RGB values for each vertex']
```

Usage

```
{'read_aggregation': 'read a ScanNet aggregation JSON file and return object-to-segments and label-to-segments mappings', 'read_segmentation': 'read a ScanNet segmentation JSON file and return segment-to-vertices mapping with vertex count', 'extract_bbox': 'extract bounding boxes and point clouds for each instance from mesh vertices and segment data', 'read_label_mapping': 'read a tab-delimited label mapping CSV file and return a category-to-NYU40 ID dictionary', 'read_mesh_vertices_rgb': 'read a PLY mesh file and return XYZ and RGB values for each vertex'}
```


# Agent Python Tools

- repo: facebookresearch/ego4d
- repo_uri: https://github.com/facebookresearch/ego4d

## File: facebookresearch_ego4d/ego4d/internal/download/cli.py

Prompts

```
['run the egoexo internal download CLI to download dataset parts from S3 to a local output directory', 'run the egoexo download CLI with filters for specific uids, benchmarks, splits, views, or universities', 'run the egoexo download CLI with the force flag to re-download all files regardless of existing state', 'run the egoexo download CLI with the delete flag to remove unused files from the output directory', 'run the egoexo download CLI to download specific parts like annotations, takes, or point clouds', 'create a PathSpecification dataclass instance with source_path, relative_path, and optional views, universities, file_type, size, and checksum fields', 'create a ManifestEntry dataclass instance with a uid, list of PathSpecification paths, and optional splits and benchmarks', 'serialize a list of ManifestEntry objects into a JSON string using manifest_dumps for storage or transmission', 'deserialize a JSON string back into a list of ManifestEntry objects using manifest_loads', 'review the PathSpecification and ManifestEntry frozen dataclasses to understand the Ego4d download manifest schema structure', 'generate manifest JSON files for all Ego-Exo4D dataset parts including takes, captures, annotations, and features', 'map take metadata to PathSpecification entries for frame-aligned videos, VRS files, trajectory, and eye gaze data', 'list and catalog all downscaled 448px take videos across S3 buckets into manifest entries', 'print a markdown table summarizing each manifest part name, size in GB, and description', 'run a function over a list of items in parallel using ThreadPoolExecutor with progress tracking']
```

Usage

```
{'run_egoexo_download_cli': 'run the egoexo internal download CLI to download dataset parts from S3 to a local output directory', 'run_download_with_filters': 'run the egoexo download CLI with filters for specific uids, benchmarks, splits, views, or universities', 'run_download_force_redownload': 'run the egoexo download CLI with the force flag to re-download all files regardless of existing state', 'run_download_with_cleanup': 'run the egoexo download CLI with the delete flag to remove unused files from the output directory', 'run_download_specific_parts': 'run the egoexo download CLI to download specific parts like annotations, takes, or point clouds'}
```

## File: facebookresearch_ego4d/ego4d/internal/download/manifest.py

Prompts

```
['run the egoexo internal download CLI to download dataset parts from S3 to a local output directory', 'run the egoexo download CLI with filters for specific uids, benchmarks, splits, views, or universities', 'run the egoexo download CLI with the force flag to re-download all files regardless of existing state', 'run the egoexo download CLI with the delete flag to remove unused files from the output directory', 'run the egoexo download CLI to download specific parts like annotations, takes, or point clouds', 'create a PathSpecification dataclass instance with source_path, relative_path, and optional views, universities, file_type, size, and checksum fields', 'create a ManifestEntry dataclass instance with a uid, list of PathSpecification paths, and optional splits and benchmarks', 'serialize a list of ManifestEntry objects into a JSON string using manifest_dumps for storage or transmission', 'deserialize a JSON string back into a list of ManifestEntry objects using manifest_loads', 'review the PathSpecification and ManifestEntry frozen dataclasses to understand the Ego4d download manifest schema structure', 'generate manifest JSON files for all Ego-Exo4D dataset parts including takes, captures, annotations, and features', 'map take metadata to PathSpecification entries for frame-aligned videos, VRS files, trajectory, and eye gaze data', 'list and catalog all downscaled 448px take videos across S3 buckets into manifest entries', 'print a markdown table summarizing each manifest part name, size in GB, and description', 'run a function over a list of items in parallel using ThreadPoolExecutor with progress tracking']
```

Usage

```
{'create_PathSpecification': 'create a PathSpecification dataclass instance with source_path, relative_path, and optional views, universities, file_type, size, and checksum fields', 'create_ManifestEntry': 'create a ManifestEntry dataclass instance with a uid, list of PathSpecification paths, and optional splits and benchmarks', 'serialize_manifest_dumps': 'serialize a list of ManifestEntry objects into a JSON string using manifest_dumps for storage or transmission', 'deserialize_manifest_loads': 'deserialize a JSON string back into a list of ManifestEntry objects using manifest_loads', 'review_PathSpecification_ManifestEntry': 'review the PathSpecification and ManifestEntry frozen dataclasses to understand the Ego4d download manifest schema structure'}
```

## File: facebookresearch_ego4d/ego4d/internal/download/manifest_gen.py

Prompts

```
['run the egoexo internal download CLI to download dataset parts from S3 to a local output directory', 'run the egoexo download CLI with filters for specific uids, benchmarks, splits, views, or universities', 'run the egoexo download CLI with the force flag to re-download all files regardless of existing state', 'run the egoexo download CLI with the delete flag to remove unused files from the output directory', 'run the egoexo download CLI to download specific parts like annotations, takes, or point clouds', 'create a PathSpecification dataclass instance with source_path, relative_path, and optional views, universities, file_type, size, and checksum fields', 'create a ManifestEntry dataclass instance with a uid, list of PathSpecification paths, and optional splits and benchmarks', 'serialize a list of ManifestEntry objects into a JSON string using manifest_dumps for storage or transmission', 'deserialize a JSON string back into a list of ManifestEntry objects using manifest_loads', 'review the PathSpecification and ManifestEntry frozen dataclasses to understand the Ego4d download manifest schema structure', 'generate manifest JSON files for all Ego-Exo4D dataset parts including takes, captures, annotations, and features', 'map take metadata to PathSpecification entries for frame-aligned videos, VRS files, trajectory, and eye gaze data', 'list and catalog all downscaled 448px take videos across S3 buckets into manifest entries', 'print a markdown table summarizing each manifest part name, size in GB, and description', 'run a function over a list of items in parallel using ThreadPoolExecutor with progress tracking']
```

Usage

```
{'generate_dataset_manifests': 'generate manifest JSON files for all Ego-Exo4D dataset parts including takes, captures, annotations, and features', 'map_take_entries': 'map take metadata to PathSpecification entries for frame-aligned videos, VRS files, trajectory, and eye gaze data', 'list_downscaled_takes': 'list and catalog all downscaled 448px take videos across S3 buckets into manifest entries', 'print_manifest_stats': 'print a markdown table summarizing each manifest part name, size in GB, and description', 'local_map_parallel': 'run a function over a list of items in parallel using ThreadPoolExecutor with progress tracking'}
```


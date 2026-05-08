# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/data_processing/aggregate_metadata.py

Prompts

```
['load a pairwise overlap matrix numpy file from a scene folder covisibility directory', 'convert a dense overlap matrix into an adjacency list dictionary with neighbor indices', 'process a single scene overlap matrix by normalizing, thresholding, and converting to adjacency list', 'aggregate pairwise overlap matrices across multiple scenes into a single npz metadata file', 'aggregate dataset scenes into train val and test splits with covisibility adjacency metadata', 'aggregate dataset scenes into train and val splits using random scene selection by ratio', 'run the CLI script to aggregate scene names for MapAnything datasets into train val and test splits', 'run the script with --print_stats to print scene count statistics for each dataset split', 'create a DatasetAggregator subclass to aggregate scene lists for a custom dataset with train val and test splits', 'create a RandomSplitAggregator to split dataset scenes into train and val splits using a random val ratio', 'create a function to save a list of scene names as a numpy array to a given output path', 'download the MapAnything benchmarking dataset from HuggingFace Hub to a specified output directory', 'extract all zip files from a download directory in parallel with configurable worker count', 'extract a single zip file to a target directory with optional deletion after extraction', 'run the CLI with --download and --output_dir flags to download the benchmarking dataset', 'run the CLI with --extract and --output_dir flags to extract downloaded zip files', 'run viz_wai_rgbd_data to visualize WAI format RGBD scene data in Rerun', 'run viz_wai_rgbd_data with load_skymask to mask sky regions from depth data', 'run viz_wai_rgbd_data with confidence_key to filter depth by confidence threshold', 'run viz_wai_rgbd_data with local_frame to visualize frames in local camera coordinates', 'run the CLI with --dataset flag to visualize RGBD data for a specific dataset']
```

Usage

```
{'load_overlap_data': 'load a pairwise overlap matrix numpy file from a scene folder covisibility directory', 'preprocess_to_adjacency_list': 'convert a dense overlap matrix into an adjacency list dictionary with neighbor indices', 'process_single_scene': 'process a single scene overlap matrix by normalizing, thresholding, and converting to adjacency list', 'aggregate_scenes': 'aggregate pairwise overlap matrices across multiple scenes into a single npz metadata file', 'DatasetAggregator_class': 'aggregate dataset scenes into train val and test splits with covisibility adjacency metadata', 'RandomSplitAggregator_class': 'aggregate dataset scenes into train and val splits using random scene selection by ratio'}
```

## File: facebookresearch_map-anything/data_processing/aggregate_scene_names.py

Prompts

```
['load a pairwise overlap matrix numpy file from a scene folder covisibility directory', 'convert a dense overlap matrix into an adjacency list dictionary with neighbor indices', 'process a single scene overlap matrix by normalizing, thresholding, and converting to adjacency list', 'aggregate pairwise overlap matrices across multiple scenes into a single npz metadata file', 'aggregate dataset scenes into train val and test splits with covisibility adjacency metadata', 'aggregate dataset scenes into train and val splits using random scene selection by ratio', 'run the CLI script to aggregate scene names for MapAnything datasets into train val and test splits', 'run the script with --print_stats to print scene count statistics for each dataset split', 'create a DatasetAggregator subclass to aggregate scene lists for a custom dataset with train val and test splits', 'create a RandomSplitAggregator to split dataset scenes into train and val splits using a random val ratio', 'create a function to save a list of scene names as a numpy array to a given output path', 'download the MapAnything benchmarking dataset from HuggingFace Hub to a specified output directory', 'extract all zip files from a download directory in parallel with configurable worker count', 'extract a single zip file to a target directory with optional deletion after extraction', 'run the CLI with --download and --output_dir flags to download the benchmarking dataset', 'run the CLI with --extract and --output_dir flags to extract downloaded zip files', 'run viz_wai_rgbd_data to visualize WAI format RGBD scene data in Rerun', 'run viz_wai_rgbd_data with load_skymask to mask sky regions from depth data', 'run viz_wai_rgbd_data with confidence_key to filter depth by confidence threshold', 'run viz_wai_rgbd_data with local_frame to visualize frames in local camera coordinates', 'run the CLI with --dataset flag to visualize RGBD data for a specific dataset']
```

Usage

```
{'run_aggregate_scene_names': 'run the CLI script to aggregate scene names for MapAnything datasets into train val and test splits', 'run_print_dataset_stats': 'run the script with --print_stats to print scene count statistics for each dataset split', 'create_DatasetAggregator': 'create a DatasetAggregator subclass to aggregate scene lists for a custom dataset with train val and test splits', 'create_RandomSplitAggregator': 'create a RandomSplitAggregator to split dataset scenes into train and val splits using a random val ratio', 'create_save_scene_lists': 'create a function to save a list of scene names as a numpy array to a given output path'}
```

## File: facebookresearch_map-anything/data_processing/download_and_extract_benchmarking_data.py

Prompts

```
['load a pairwise overlap matrix numpy file from a scene folder covisibility directory', 'convert a dense overlap matrix into an adjacency list dictionary with neighbor indices', 'process a single scene overlap matrix by normalizing, thresholding, and converting to adjacency list', 'aggregate pairwise overlap matrices across multiple scenes into a single npz metadata file', 'aggregate dataset scenes into train val and test splits with covisibility adjacency metadata', 'aggregate dataset scenes into train and val splits using random scene selection by ratio', 'run the CLI script to aggregate scene names for MapAnything datasets into train val and test splits', 'run the script with --print_stats to print scene count statistics for each dataset split', 'create a DatasetAggregator subclass to aggregate scene lists for a custom dataset with train val and test splits', 'create a RandomSplitAggregator to split dataset scenes into train and val splits using a random val ratio', 'create a function to save a list of scene names as a numpy array to a given output path', 'download the MapAnything benchmarking dataset from HuggingFace Hub to a specified output directory', 'extract all zip files from a download directory in parallel with configurable worker count', 'extract a single zip file to a target directory with optional deletion after extraction', 'run the CLI with --download and --output_dir flags to download the benchmarking dataset', 'run the CLI with --extract and --output_dir flags to extract downloaded zip files', 'run viz_wai_rgbd_data to visualize WAI format RGBD scene data in Rerun', 'run viz_wai_rgbd_data with load_skymask to mask sky regions from depth data', 'run viz_wai_rgbd_data with confidence_key to filter depth by confidence threshold', 'run viz_wai_rgbd_data with local_frame to visualize frames in local camera coordinates', 'run the CLI with --dataset flag to visualize RGBD data for a specific dataset']
```

Usage

```
{'download_benchmarking_dataset': 'download the MapAnything benchmarking dataset from HuggingFace Hub to a specified output directory', 'extract_all_zips': 'extract all zip files from a download directory in parallel with configurable worker count', 'extract_single_zip': 'extract a single zip file to a target directory with optional deletion after extraction', 'run_download_cli': 'run the CLI with --download and --output_dir flags to download the benchmarking dataset', 'run_extract_cli': 'run the CLI with --extract and --output_dir flags to extract downloaded zip files'}
```

## File: facebookresearch_map-anything/data_processing/viz_data.py

Prompts

```
['load a pairwise overlap matrix numpy file from a scene folder covisibility directory', 'convert a dense overlap matrix into an adjacency list dictionary with neighbor indices', 'process a single scene overlap matrix by normalizing, thresholding, and converting to adjacency list', 'aggregate pairwise overlap matrices across multiple scenes into a single npz metadata file', 'aggregate dataset scenes into train val and test splits with covisibility adjacency metadata', 'aggregate dataset scenes into train and val splits using random scene selection by ratio', 'run the CLI script to aggregate scene names for MapAnything datasets into train val and test splits', 'run the script with --print_stats to print scene count statistics for each dataset split', 'create a DatasetAggregator subclass to aggregate scene lists for a custom dataset with train val and test splits', 'create a RandomSplitAggregator to split dataset scenes into train and val splits using a random val ratio', 'create a function to save a list of scene names as a numpy array to a given output path', 'download the MapAnything benchmarking dataset from HuggingFace Hub to a specified output directory', 'extract all zip files from a download directory in parallel with configurable worker count', 'extract a single zip file to a target directory with optional deletion after extraction', 'run the CLI with --download and --output_dir flags to download the benchmarking dataset', 'run the CLI with --extract and --output_dir flags to extract downloaded zip files', 'run viz_wai_rgbd_data to visualize WAI format RGBD scene data in Rerun', 'run viz_wai_rgbd_data with load_skymask to mask sky regions from depth data', 'run viz_wai_rgbd_data with confidence_key to filter depth by confidence threshold', 'run viz_wai_rgbd_data with local_frame to visualize frames in local camera coordinates', 'run the CLI with --dataset flag to visualize RGBD data for a specific dataset']
```

Usage

```
{'run_viz_wai_rgbd_data': 'run viz_wai_rgbd_data to visualize WAI format RGBD scene data in Rerun', 'run_viz_wai_rgbd_data_with_skymask': 'run viz_wai_rgbd_data with load_skymask to mask sky regions from depth data', 'run_viz_wai_rgbd_data_with_confidence': 'run viz_wai_rgbd_data with confidence_key to filter depth by confidence threshold', 'run_viz_wai_rgbd_data_local_frame': 'run viz_wai_rgbd_data with local_frame to visualize frames in local camera coordinates', 'run_viz_wai_rgbd_data_cli': 'run the CLI with --dataset flag to visualize RGBD data for a specific dataset'}
```


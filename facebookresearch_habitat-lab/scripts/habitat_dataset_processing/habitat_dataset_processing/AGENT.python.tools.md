# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/scripts/habitat_dataset_processing/habitat_dataset_processing/asset_pipeline.py

Prompts

```
['run the AssetPipeline to process Habitat datasets and output processed 3D assets to a directory', 'create an AssetDatabase instance to register and track assets by their Habitat template names', 'register an asset into the AssetDatabase by parsing its object or stage config JSON file', 'find all files with a given extension recursively within a directory tree', 'remove all assets from the AssetDatabase that do not appear in any scene', 'create a metadata JSON file from asset groups dict and output directory path', 'get the preferred operation for a 3D model file path based on its extension', 'transform a COLLADA file to use Y_UP axis orientation for Habitat compatibility', 'process a single 3D model job by decimating, copying, or ignoring it', 'batch process multiple 3D model jobs with optional multiprocessing support', 'run the magnum decimation tool to simplify 3D mesh triangles in an input scene file', 'run the decimation tool in quiet mode to suppress output logs during mesh processing', 'run the decimation tool in verbose mode to see detailed mesh simplification statistics', 'refactor the decimate function to adjust the simplify target error threshold for finer mesh detail', 'review the meshoptimizer configuration settings including simplifyTargetError and simplifyTargetIndexCountThreshold', 'recursively find all dependencies for a URDF, OBJ, MTL, or DAE asset file up to a given depth', 'normalize a file path by removing dot and double-dot components without escaping the data folder', 'strip trailing wildcards and slashes from a path then resolve dot and double-dot components', 'check whether a given file path has a COLLADA .dae extension', 'extract referenced asset file paths from a URDF file excluding Xacro macros']
```

Usage

```
{'run_asset_pipeline': 'run the AssetPipeline to process Habitat datasets and output processed 3D assets to a directory', 'create_asset_database': 'create an AssetDatabase instance to register and track assets by their Habitat template names', 'register_asset_from_config': 'register an asset into the AssetDatabase by parsing its object or stage config JSON file', 'find_files_with_extension': 'find all files with a given extension recursively within a directory tree', 'remove_orphan_assets': 'remove all assets from the AssetDatabase that do not appear in any scene'}
```

## File: facebookresearch_habitat-lab/scripts/habitat_dataset_processing/habitat_dataset_processing/asset_processor.py

Prompts

```
['run the AssetPipeline to process Habitat datasets and output processed 3D assets to a directory', 'create an AssetDatabase instance to register and track assets by their Habitat template names', 'register an asset into the AssetDatabase by parsing its object or stage config JSON file', 'find all files with a given extension recursively within a directory tree', 'remove all assets from the AssetDatabase that do not appear in any scene', 'create a metadata JSON file from asset groups dict and output directory path', 'get the preferred operation for a 3D model file path based on its extension', 'transform a COLLADA file to use Y_UP axis orientation for Habitat compatibility', 'process a single 3D model job by decimating, copying, or ignoring it', 'batch process multiple 3D model jobs with optional multiprocessing support', 'run the magnum decimation tool to simplify 3D mesh triangles in an input scene file', 'run the decimation tool in quiet mode to suppress output logs during mesh processing', 'run the decimation tool in verbose mode to see detailed mesh simplification statistics', 'refactor the decimate function to adjust the simplify target error threshold for finer mesh detail', 'review the meshoptimizer configuration settings including simplifyTargetError and simplifyTargetIndexCountThreshold', 'recursively find all dependencies for a URDF, OBJ, MTL, or DAE asset file up to a given depth', 'normalize a file path by removing dot and double-dot components without escaping the data folder', 'strip trailing wildcards and slashes from a path then resolve dot and double-dot components', 'check whether a given file path has a COLLADA .dae extension', 'extract referenced asset file paths from a URDF file excluding Xacro macros']
```

Usage

```
{'create_metadata_file': 'create a metadata JSON file from asset groups dict and output directory path', 'get_preferred_operation': 'get the preferred operation for a 3D model file path based on its extension', 'transform_collada': 'transform a COLLADA file to use Y_UP axis orientation for Habitat compatibility', 'process_model': 'process a single 3D model job by decimating, copying, or ignoring it', 'process_models': 'batch process multiple 3D model jobs with optional multiprocessing support'}
```

## File: facebookresearch_habitat-lab/scripts/habitat_dataset_processing/habitat_dataset_processing/magnum_decimation.py

Prompts

```
['run the AssetPipeline to process Habitat datasets and output processed 3D assets to a directory', 'create an AssetDatabase instance to register and track assets by their Habitat template names', 'register an asset into the AssetDatabase by parsing its object or stage config JSON file', 'find all files with a given extension recursively within a directory tree', 'remove all assets from the AssetDatabase that do not appear in any scene', 'create a metadata JSON file from asset groups dict and output directory path', 'get the preferred operation for a 3D model file path based on its extension', 'transform a COLLADA file to use Y_UP axis orientation for Habitat compatibility', 'process a single 3D model job by decimating, copying, or ignoring it', 'batch process multiple 3D model jobs with optional multiprocessing support', 'run the magnum decimation tool to simplify 3D mesh triangles in an input scene file', 'run the decimation tool in quiet mode to suppress output logs during mesh processing', 'run the decimation tool in verbose mode to see detailed mesh simplification statistics', 'refactor the decimate function to adjust the simplify target error threshold for finer mesh detail', 'review the meshoptimizer configuration settings including simplifyTargetError and simplifyTargetIndexCountThreshold', 'recursively find all dependencies for a URDF, OBJ, MTL, or DAE asset file up to a given depth', 'normalize a file path by removing dot and double-dot components without escaping the data folder', 'strip trailing wildcards and slashes from a path then resolve dot and double-dot components', 'check whether a given file path has a COLLADA .dae extension', 'extract referenced asset file paths from a URDF file excluding Xacro macros']
```

Usage

```
{'run_decimate_meshes': 'run the magnum decimation tool to simplify 3D mesh triangles in an input scene file', 'run_decimate_quiet': 'run the decimation tool in quiet mode to suppress output logs during mesh processing', 'run_decimate_verbose': 'run the decimation tool in verbose mode to see detailed mesh simplification statistics', 'refactor_decimate_simplify': 'refactor the decimate function to adjust the simplify target error threshold for finer mesh detail', 'review_meshoptimizer_config': 'review the meshoptimizer configuration settings including simplifyTargetError and simplifyTargetIndexCountThreshold'}
```

## File: facebookresearch_habitat-lab/scripts/habitat_dataset_processing/habitat_dataset_processing/util.py

Prompts

```
['run the AssetPipeline to process Habitat datasets and output processed 3D assets to a directory', 'create an AssetDatabase instance to register and track assets by their Habitat template names', 'register an asset into the AssetDatabase by parsing its object or stage config JSON file', 'find all files with a given extension recursively within a directory tree', 'remove all assets from the AssetDatabase that do not appear in any scene', 'create a metadata JSON file from asset groups dict and output directory path', 'get the preferred operation for a 3D model file path based on its extension', 'transform a COLLADA file to use Y_UP axis orientation for Habitat compatibility', 'process a single 3D model job by decimating, copying, or ignoring it', 'batch process multiple 3D model jobs with optional multiprocessing support', 'run the magnum decimation tool to simplify 3D mesh triangles in an input scene file', 'run the decimation tool in quiet mode to suppress output logs during mesh processing', 'run the decimation tool in verbose mode to see detailed mesh simplification statistics', 'refactor the decimate function to adjust the simplify target error threshold for finer mesh detail', 'review the meshoptimizer configuration settings including simplifyTargetError and simplifyTargetIndexCountThreshold', 'recursively find all dependencies for a URDF, OBJ, MTL, or DAE asset file up to a given depth', 'normalize a file path by removing dot and double-dot components without escaping the data folder', 'strip trailing wildcards and slashes from a path then resolve dot and double-dot components', 'check whether a given file path has a COLLADA .dae extension', 'extract referenced asset file paths from a URDF file excluding Xacro macros']
```

Usage

```
{'get_dependencies': 'recursively find all dependencies for a URDF, OBJ, MTL, or DAE asset file up to a given depth', 'resolve_relative_path': 'normalize a file path by removing dot and double-dot components without escaping the data folder', 'resolve_relative_path_with_wildcard': 'strip trailing wildcards and slashes from a path then resolve dot and double-dot components', 'is_file_collada': 'check whether a given file path has a COLLADA .dae extension', 'get_dependencies_urdf': 'extract referenced asset file paths from a URDF file excluding Xacro macros'}
```


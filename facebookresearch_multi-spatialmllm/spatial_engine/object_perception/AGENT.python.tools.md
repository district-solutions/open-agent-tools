# Agent Python Tools

- repo: facebookresearch/multi-spatialmllm
- repo_uri: https://github.com/facebookresearch/multi-spatialmllm

## File: facebookresearch_multi-spatialmllm/spatial_engine/object_perception/compute_object_visibility.py

Prompts

```
['load a parquet file and convert it to a dictionary mapping scene image keys to point index lists', 'process a single scene to compute object visibility across all valid images and return object-to-image mappings', 'process a train or val split by computing object visibility for all scenes and saving results to a pickle file', 'run the main function to compute object visibility for both train and val splits using configured paths', 'compute the visibility percentage of each object in all valid images for a given scene using point-level visibility data', 'merge pickle files across subdirectories for a given split and dimension into a combined dictionary', 'merge object coverage pickle files for height length and width dimensions and save results', 'run the script to merge object coverage results for train and val splits', 'review the merge_dimension function to understand how it parses directory names and loads pickle files', 'refactor merge_split to support additional dimensions beyond height length and width', 'run the script to find minimal image combinations covering object height length and width dimensions', 'run find_minimal_combinations to get minimal image sets that cover a target dimension using BFS search', 'run process_object to compute minimal image combinations for height length and width of a single object', 'run process_scene_for_coverage to compute object coverage results for all objects in a given scene', 'run load_visibility_dict to load a parquet file and convert it to a key value dictionary', 'build QA samples for object dimension estimation from merged pickle info files into JSONL format', 'convert a training format sample dict to evaluation format by extracting the first conversation text', 'build both training and validation datasets for object perception height length and width estimation', 'run the main entry point to build train and val datasets for single object perception', 'refactor build_lwh_qa_samples to support additional dimension types beyond height length and width']
```

Usage

```
{'load_visibility_dict': 'load a parquet file and convert it to a dictionary mapping scene image keys to point index lists', 'process_scene': 'process a single scene to compute object visibility across all valid images and return object-to-image mappings', 'process_split': 'process a train or val split by computing object visibility for all scenes and saving results to a pickle file', 'run_main': 'run the main function to compute object visibility for both train and val splits using configured paths', 'compute_object_visibility': 'compute the visibility percentage of each object in all valid images for a given scene using point-level visibility data'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/object_perception/merge_object_coverage.py

Prompts

```
['load a parquet file and convert it to a dictionary mapping scene image keys to point index lists', 'process a single scene to compute object visibility across all valid images and return object-to-image mappings', 'process a train or val split by computing object visibility for all scenes and saving results to a pickle file', 'run the main function to compute object visibility for both train and val splits using configured paths', 'compute the visibility percentage of each object in all valid images for a given scene using point-level visibility data', 'merge pickle files across subdirectories for a given split and dimension into a combined dictionary', 'merge object coverage pickle files for height length and width dimensions and save results', 'run the script to merge object coverage results for train and val splits', 'review the merge_dimension function to understand how it parses directory names and loads pickle files', 'refactor merge_split to support additional dimensions beyond height length and width', 'run the script to find minimal image combinations covering object height length and width dimensions', 'run find_minimal_combinations to get minimal image sets that cover a target dimension using BFS search', 'run process_object to compute minimal image combinations for height length and width of a single object', 'run process_scene_for_coverage to compute object coverage results for all objects in a given scene', 'run load_visibility_dict to load a parquet file and convert it to a key value dictionary', 'build QA samples for object dimension estimation from merged pickle info files into JSONL format', 'convert a training format sample dict to evaluation format by extracting the first conversation text', 'build both training and validation datasets for object perception height length and width estimation', 'run the main entry point to build train and val datasets for single object perception', 'refactor build_lwh_qa_samples to support additional dimension types beyond height length and width']
```

Usage

```
{'merge_dimension': 'merge pickle files across subdirectories for a given split and dimension into a combined dictionary', 'merge_split': 'merge object coverage pickle files for height length and width dimensions and save results', 'run_merge_object_coverage': 'run the script to merge object coverage results for train and val splits', 'review_merge_dimension': 'review the merge_dimension function to understand how it parses directory names and loads pickle files', 'refactor_merge_split': 'refactor merge_split to support additional dimensions beyond height length and width'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/object_perception/single_object_coverage_finder.py

Prompts

```
['load a parquet file and convert it to a dictionary mapping scene image keys to point index lists', 'process a single scene to compute object visibility across all valid images and return object-to-image mappings', 'process a train or val split by computing object visibility for all scenes and saving results to a pickle file', 'run the main function to compute object visibility for both train and val splits using configured paths', 'compute the visibility percentage of each object in all valid images for a given scene using point-level visibility data', 'merge pickle files across subdirectories for a given split and dimension into a combined dictionary', 'merge object coverage pickle files for height length and width dimensions and save results', 'run the script to merge object coverage results for train and val splits', 'review the merge_dimension function to understand how it parses directory names and loads pickle files', 'refactor merge_split to support additional dimensions beyond height length and width', 'run the script to find minimal image combinations covering object height length and width dimensions', 'run find_minimal_combinations to get minimal image sets that cover a target dimension using BFS search', 'run process_object to compute minimal image combinations for height length and width of a single object', 'run process_scene_for_coverage to compute object coverage results for all objects in a given scene', 'run load_visibility_dict to load a parquet file and convert it to a key value dictionary', 'build QA samples for object dimension estimation from merged pickle info files into JSONL format', 'convert a training format sample dict to evaluation format by extracting the first conversation text', 'build both training and validation datasets for object perception height length and width estimation', 'run the main entry point to build train and val datasets for single object perception', 'refactor build_lwh_qa_samples to support additional dimension types beyond height length and width']
```

Usage

```
{'run_object_coverage_finder': 'run the script to find minimal image combinations covering object height length and width dimensions', 'run_find_minimal_combinations': 'run find_minimal_combinations to get minimal image sets that cover a target dimension using BFS search', 'run_process_object': 'run process_object to compute minimal image combinations for height length and width of a single object', 'run_process_scene_for_coverage': 'run process_scene_for_coverage to compute object coverage results for all objects in a given scene', 'run_load_visibility_dict': 'run load_visibility_dict to load a parquet file and convert it to a key value dictionary'}
```

## File: facebookresearch_multi-spatialmllm/spatial_engine/object_perception/single_object_perception_engine.py

Prompts

```
['load a parquet file and convert it to a dictionary mapping scene image keys to point index lists', 'process a single scene to compute object visibility across all valid images and return object-to-image mappings', 'process a train or val split by computing object visibility for all scenes and saving results to a pickle file', 'run the main function to compute object visibility for both train and val splits using configured paths', 'compute the visibility percentage of each object in all valid images for a given scene using point-level visibility data', 'merge pickle files across subdirectories for a given split and dimension into a combined dictionary', 'merge object coverage pickle files for height length and width dimensions and save results', 'run the script to merge object coverage results for train and val splits', 'review the merge_dimension function to understand how it parses directory names and loads pickle files', 'refactor merge_split to support additional dimensions beyond height length and width', 'run the script to find minimal image combinations covering object height length and width dimensions', 'run find_minimal_combinations to get minimal image sets that cover a target dimension using BFS search', 'run process_object to compute minimal image combinations for height length and width of a single object', 'run process_scene_for_coverage to compute object coverage results for all objects in a given scene', 'run load_visibility_dict to load a parquet file and convert it to a key value dictionary', 'build QA samples for object dimension estimation from merged pickle info files into JSONL format', 'convert a training format sample dict to evaluation format by extracting the first conversation text', 'build both training and validation datasets for object perception height length and width estimation', 'run the main entry point to build train and val datasets for single object perception', 'refactor build_lwh_qa_samples to support additional dimension types beyond height length and width']
```

Usage

```
{'build_lwh_qa_samples': 'build QA samples for object dimension estimation from merged pickle info files into JSONL format', 'convert_train_sample_to_eval_sample': 'convert a training format sample dict to evaluation format by extracting the first conversation text', 'build_train_and_val_datasets': 'build both training and validation datasets for object perception height length and width estimation', 'main': 'run the main entry point to build train and val datasets for single object perception', 'refactor_build_lwh_qa_samples': 'refactor build_lwh_qa_samples to support additional dimension types beyond height length and width'}
```


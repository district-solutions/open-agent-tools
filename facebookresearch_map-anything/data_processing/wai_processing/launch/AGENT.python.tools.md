# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/data_processing/wai_processing/launch/launch_utils.py

Prompts

```
['import a function from a Python module given its file path and function name', "parse a string like '{key: [val1, val2]}' into a Python dictionary", 'escape a list of scene names into a JSON-style quoted string array', 'review the import_function_from_path function that dynamically loads a function from a file path', 'refactor the parse_string_to_dict function to support multiple key-value pairs', 'run a SLURM job pipeline for WAI processing stages like undistort or conversion using argconf config', 'run a dry run of slurm_stage.py to preview jobs without launching on SLURM', 'check access to an S3 bucket using boto3 head_bucket before the copy_to_s3 stage', 'run pre-launch sanity checks to verify git state and S3 access before submitting SLURM jobs', 'run SLURM jobs with a locked codebase copy to ensure version consistency across all jobs']
```

Usage

```
{'import_function_from_path': 'import a function from a Python module given its file path and function name', 'parse_string_to_dict': "parse a string like '{key: [val1, val2]}' into a Python dictionary", 'escape_scene_names': 'escape a list of scene names into a JSON-style quoted string array', 'review_import_function_from_path': 'review the import_function_from_path function that dynamically loads a function from a file path', 'refactor_parse_string_to_dict': 'refactor the parse_string_to_dict function to support multiple key-value pairs'}
```

## File: facebookresearch_map-anything/data_processing/wai_processing/launch/slurm_stage.py

Prompts

```
['import a function from a Python module given its file path and function name', "parse a string like '{key: [val1, val2]}' into a Python dictionary", 'escape a list of scene names into a JSON-style quoted string array', 'review the import_function_from_path function that dynamically loads a function from a file path', 'refactor the parse_string_to_dict function to support multiple key-value pairs', 'run a SLURM job pipeline for WAI processing stages like undistort or conversion using argconf config', 'run a dry run of slurm_stage.py to preview jobs without launching on SLURM', 'check access to an S3 bucket using boto3 head_bucket before the copy_to_s3 stage', 'run pre-launch sanity checks to verify git state and S3 access before submitting SLURM jobs', 'run SLURM jobs with a locked codebase copy to ensure version consistency across all jobs']
```

Usage

```
{'run_slurm_stage_pipeline': 'run a SLURM job pipeline for WAI processing stages like undistort or conversion using argconf config', 'run_slurm_dry_run': 'run a dry run of slurm_stage.py to preview jobs without launching on SLURM', 'check_s3_bucket_access': 'check access to an S3 bucket using boto3 head_bucket before the copy_to_s3 stage', 'pre_launch_sanity_check': 'run pre-launch sanity checks to verify git state and S3 access before submitting SLURM jobs', 'run_slurm_locked_version': 'run SLURM jobs with a locked codebase copy to ensure version consistency across all jobs'}
```


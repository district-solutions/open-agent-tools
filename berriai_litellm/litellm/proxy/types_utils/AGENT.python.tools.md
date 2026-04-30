# Agent Python Tools

- repo: berriai/litellm
- repo_uri: https://github.com/berriai/litellm

## File: berriai_litellm/litellm/proxy/types_utils/utils.py

Prompts

```
["load a Python module instance from a dotted path string like 'module.submodule.ClassName'", "load a custom logger instance from an S3 URL with format 's3://bucket/path/to/module.instance_name'", "load a custom logger instance from a GCS URL with format 'gcs://bucket/path/to/module.instance_name'", 'download a Python file from Google Cloud Storage to a local path asynchronously', 'validate that a custom validator function is annotated to return Literal[True]']
```

Usage

```
{'load_custom_module_instance': "load a Python module instance from a dotted path string like 'module.submodule.ClassName'", 'load_instance_from_s3': "load a custom logger instance from an S3 URL with format 's3://bucket/path/to/module.instance_name'", 'load_instance_from_gcs': "load a custom logger instance from a GCS URL with format 'gcs://bucket/path/to/module.instance_name'", 'download_gcs_file': 'download a Python file from Google Cloud Storage to a local path asynchronously', 'validate_custom_validator': 'validate that a custom validator function is annotated to return Literal[True]'}
```


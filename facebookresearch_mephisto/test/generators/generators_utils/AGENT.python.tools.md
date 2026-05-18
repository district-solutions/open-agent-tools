# Agent Python Tools

- repo: facebookresearch/mephisto
- repo_uri: https://github.com/facebookresearch/mephisto

## File: facebookresearch_mephisto/test/generators/generators_utils/test_remote_procedures.py

Prompts

```
['test the _get_presigned_url function that generates a presigned S3 URL for a given object key', 'test the _get_presigned_url_for_thread function that safely presigns a single S3 URL with error handling', 'test the _get_multiple_presigned_urls function that concurrently presigns a list of S3 URLs using threads', 'test error handling when _get_presigned_url_for_thread receives a non-S3 URL or encounters an exception', 'test that _get_multiple_presigned_urls raises a ValueError when any URL fails to presign']
```

Usage

```
{'test_get_presigned_url': 'test the _get_presigned_url function that generates a presigned S3 URL for a given object key', 'test_get_presigned_url_for_thread': 'test the _get_presigned_url_for_thread function that safely presigns a single S3 URL with error handling', 'test_get_multiple_presigned_urls': 'test the _get_multiple_presigned_urls function that concurrently presigns a list of S3 URLs using threads', 'test_presigned_url_error_handling': 'test error handling when _get_presigned_url_for_thread receives a non-S3 URL or encounters an exception', 'test_multiple_presigned_urls_errors': 'test that _get_multiple_presigned_urls raises a ValueError when any URL fails to presign'}
```


# Agent Python Tools

- repo: huggingface/datasets
- repo_uri: https://github.com/huggingface/datasets

## File: huggingface_datasets/src/datasets/download/download_config.py

Prompts

```
['create a DownloadConfig instance with a custom cache directory for storing downloaded dataset files', 'create a DownloadConfig that forces re-download of already cached files by setting force_download to True', 'create a DownloadConfig that automatically extracts compressed zip or tar files after downloading them', 'call the copy method on a DownloadConfig instance to get a deep-copied independent configuration object', 'set the token attribute on a DownloadConfig to auto-populate HuggingFace storage options with the auth token', 'download files from URLs and return local cached paths using DownloadManager', 'extract downloaded archive files and return the extracted directory paths', 'download URLs and extract archives in one step using DownloadManager', 'iterate over files within a downloaded archive yielding path and file objects', 'get the recorded sizes and checksums of all downloaded files', 'normalize URLs for streaming data from remote files without actually downloading them', 'add extraction protocol to URLs for streaming from compressed archives like zip files', 'combine download and extract in one step to prepare URLs for streaming data', 'iterate over files within a tar or zip archive yielding file paths and binary objects', 'iterate over file URL paths from a root directory or list of paths']
```

Usage

```
{'create_download_config_with_cache_dir': 'create a DownloadConfig instance with a custom cache directory for storing downloaded dataset files', 'create_download_config_with_force_download': 'create a DownloadConfig that forces re-download of already cached files by setting force_download to True', 'create_download_config_with_extraction': 'create a DownloadConfig that automatically extracts compressed zip or tar files after downloading them', 'copy_download_config': 'call the copy method on a DownloadConfig instance to get a deep-copied independent configuration object', 'set_download_config_token': 'set the token attribute on a DownloadConfig to auto-populate HuggingFace storage options with the auth token'}
```

## File: huggingface_datasets/src/datasets/download/download_manager.py

Prompts

```
['create a DownloadConfig instance with a custom cache directory for storing downloaded dataset files', 'create a DownloadConfig that forces re-download of already cached files by setting force_download to True', 'create a DownloadConfig that automatically extracts compressed zip or tar files after downloading them', 'call the copy method on a DownloadConfig instance to get a deep-copied independent configuration object', 'set the token attribute on a DownloadConfig to auto-populate HuggingFace storage options with the auth token', 'download files from URLs and return local cached paths using DownloadManager', 'extract downloaded archive files and return the extracted directory paths', 'download URLs and extract archives in one step using DownloadManager', 'iterate over files within a downloaded archive yielding path and file objects', 'get the recorded sizes and checksums of all downloaded files', 'normalize URLs for streaming data from remote files without actually downloading them', 'add extraction protocol to URLs for streaming from compressed archives like zip files', 'combine download and extract in one step to prepare URLs for streaming data', 'iterate over files within a tar or zip archive yielding file paths and binary objects', 'iterate over file URL paths from a root directory or list of paths']
```

Usage

```
{'download_urls': 'download files from URLs and return local cached paths using DownloadManager', 'extract_archives': 'extract downloaded archive files and return the extracted directory paths', 'download_and_extract': 'download URLs and extract archives in one step using DownloadManager', 'iter_archive': 'iterate over files within a downloaded archive yielding path and file objects', 'get_recorded_checksums': 'get the recorded sizes and checksums of all downloaded files'}
```

## File: huggingface_datasets/src/datasets/download/streaming_download_manager.py

Prompts

```
['create a DownloadConfig instance with a custom cache directory for storing downloaded dataset files', 'create a DownloadConfig that forces re-download of already cached files by setting force_download to True', 'create a DownloadConfig that automatically extracts compressed zip or tar files after downloading them', 'call the copy method on a DownloadConfig instance to get a deep-copied independent configuration object', 'set the token attribute on a DownloadConfig to auto-populate HuggingFace storage options with the auth token', 'download files from URLs and return local cached paths using DownloadManager', 'extract downloaded archive files and return the extracted directory paths', 'download URLs and extract archives in one step using DownloadManager', 'iterate over files within a downloaded archive yielding path and file objects', 'get the recorded sizes and checksums of all downloaded files', 'normalize URLs for streaming data from remote files without actually downloading them', 'add extraction protocol to URLs for streaming from compressed archives like zip files', 'combine download and extract in one step to prepare URLs for streaming data', 'iterate over files within a tar or zip archive yielding file paths and binary objects', 'iterate over file URL paths from a root directory or list of paths']
```

Usage

```
{'download_streaming_urls': 'normalize URLs for streaming data from remote files without actually downloading them', 'extract_archive_streaming': 'add extraction protocol to URLs for streaming from compressed archives like zip files', 'download_and_extract_streaming': 'combine download and extract in one step to prepare URLs for streaming data', 'iter_archive_files': 'iterate over files within a tar or zip archive yielding file paths and binary objects', 'iter_files_from_paths': 'iterate over file URL paths from a root directory or list of paths'}
```


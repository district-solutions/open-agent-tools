# Agent Python Tools

- repo: facebookresearch/hot3d
- repo_uri: https://github.com/facebookresearch/hot3d

## File: facebookresearch_hot3d/hot3d/data_downloader/dataset_download_status_manager.py

Prompts

```
['create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load the download status for all data groups from an existing JSON status file', 'save the current download status dictionary to a JSON file for persistence', 'set the download completion status of a specific data type to true or false', 'get the current download completion status boolean for a specific data type', 'create a DatasetDownloaderBase instance and call download_data to download HOT3D dataset sequences to an output folder', 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'build a requests session with retry logic for HTTP 429, 500, 502, 503, 504 errors when downloading data', 'extract a downloaded ZIP file and reorganize MPS data types into their designated subdirectories', 'use DatasetDownloadStatusManager to track and skip already downloaded data types unless overwrite is enabled', 'run the dataset downloader CLI with a CDN file and output folder to download sequences', 'run the dataset downloader CLI to download all sequences from a CDN file to a local folder', 'run the dataset downloader CLI with specific data type indices to download selected data types', 'run the dataset downloader CLI with the overwrite flag to re-download previously downloaded sequences', 'run the dataset downloader CLI with specific sequence names to download only selected sequences', 'load a list of sequence names from a CDN JSON file using load_sequences_list_from_cdn', 'load data group name to file mappings from a CDN JSON file using load_data_groups_from_cdn', 'review the MPS eye gaze and SLAM file constants and folder definitions', 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor load_sequences_list_from_cdn to return a sorted list of sequence names']
```

Usage

```
{'create_download_status_manager': 'create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load_status_from_json': 'load the download status for all data groups from an existing JSON status file', 'save_status_to_json': 'save the current download status dictionary to a JSON file for persistence', 'set_download_status': 'set the download completion status of a specific data type to true or false', 'get_download_status': 'get the current download completion status boolean for a specific data type'}
```

## File: facebookresearch_hot3d/hot3d/data_downloader/dataset_downloader_base.py

Prompts

```
['create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load the download status for all data groups from an existing JSON status file', 'save the current download status dictionary to a JSON file for persistence', 'set the download completion status of a specific data type to true or false', 'get the current download completion status boolean for a specific data type', 'create a DatasetDownloaderBase instance and call download_data to download HOT3D dataset sequences to an output folder', 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'build a requests session with retry logic for HTTP 429, 500, 502, 503, 504 errors when downloading data', 'extract a downloaded ZIP file and reorganize MPS data types into their designated subdirectories', 'use DatasetDownloadStatusManager to track and skip already downloaded data types unless overwrite is enabled', 'run the dataset downloader CLI with a CDN file and output folder to download sequences', 'run the dataset downloader CLI to download all sequences from a CDN file to a local folder', 'run the dataset downloader CLI with specific data type indices to download selected data types', 'run the dataset downloader CLI with the overwrite flag to re-download previously downloaded sequences', 'run the dataset downloader CLI with specific sequence names to download only selected sequences', 'load a list of sequence names from a CDN JSON file using load_sequences_list_from_cdn', 'load data group name to file mappings from a CDN JSON file using load_data_groups_from_cdn', 'review the MPS eye gaze and SLAM file constants and folder definitions', 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor load_sequences_list_from_cdn to return a sorted list of sequence names']
```

Usage

```
{'download_dataset_sequences': 'create a DatasetDownloaderBase instance and call download_data to download HOT3D dataset sequences to an output folder', 'calculate_file_sha1': 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'download_data_with_retry': 'build a requests session with retry logic for HTTP 429, 500, 502, 503, 504 errors when downloading data', 'extract_and_reorganize_zip': 'extract a downloaded ZIP file and reorganize MPS data types into their designated subdirectories', 'check_download_status': 'use DatasetDownloadStatusManager to track and skip already downloaded data types unless overwrite is enabled'}
```

## File: facebookresearch_hot3d/hot3d/data_downloader/dataset_downloader_base_main.py

Prompts

```
['create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load the download status for all data groups from an existing JSON status file', 'save the current download status dictionary to a JSON file for persistence', 'set the download completion status of a specific data type to true or false', 'get the current download completion status boolean for a specific data type', 'create a DatasetDownloaderBase instance and call download_data to download HOT3D dataset sequences to an output folder', 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'build a requests session with retry logic for HTTP 429, 500, 502, 503, 504 errors when downloading data', 'extract a downloaded ZIP file and reorganize MPS data types into their designated subdirectories', 'use DatasetDownloadStatusManager to track and skip already downloaded data types unless overwrite is enabled', 'run the dataset downloader CLI with a CDN file and output folder to download sequences', 'run the dataset downloader CLI to download all sequences from a CDN file to a local folder', 'run the dataset downloader CLI with specific data type indices to download selected data types', 'run the dataset downloader CLI with the overwrite flag to re-download previously downloaded sequences', 'run the dataset downloader CLI with specific sequence names to download only selected sequences', 'load a list of sequence names from a CDN JSON file using load_sequences_list_from_cdn', 'load data group name to file mappings from a CDN JSON file using load_data_groups_from_cdn', 'review the MPS eye gaze and SLAM file constants and folder definitions', 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor load_sequences_list_from_cdn to return a sorted list of sequence names']
```

Usage

```
{'run_dataset_downloader_cli': 'run the dataset downloader CLI with a CDN file and output folder to download sequences', 'run_download_all_sequences': 'run the dataset downloader CLI to download all sequences from a CDN file to a local folder', 'run_download_specific_data_types': 'run the dataset downloader CLI with specific data type indices to download selected data types', 'run_download_with_overwrite': 'run the dataset downloader CLI with the overwrite flag to re-download previously downloaded sequences', 'run_download_specific_sequences': 'run the dataset downloader CLI with specific sequence names to download only selected sequences'}
```

## File: facebookresearch_hot3d/hot3d/data_downloader/utils.py

Prompts

```
['create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load the download status for all data groups from an existing JSON status file', 'save the current download status dictionary to a JSON file for persistence', 'set the download completion status of a specific data type to true or false', 'get the current download completion status boolean for a specific data type', 'create a DatasetDownloaderBase instance and call download_data to download HOT3D dataset sequences to an output folder', 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'build a requests session with retry logic for HTTP 429, 500, 502, 503, 504 errors when downloading data', 'extract a downloaded ZIP file and reorganize MPS data types into their designated subdirectories', 'use DatasetDownloadStatusManager to track and skip already downloaded data types unless overwrite is enabled', 'run the dataset downloader CLI with a CDN file and output folder to download sequences', 'run the dataset downloader CLI to download all sequences from a CDN file to a local folder', 'run the dataset downloader CLI with specific data type indices to download selected data types', 'run the dataset downloader CLI with the overwrite flag to re-download previously downloaded sequences', 'run the dataset downloader CLI with specific sequence names to download only selected sequences', 'load a list of sequence names from a CDN JSON file using load_sequences_list_from_cdn', 'load data group name to file mappings from a CDN JSON file using load_data_groups_from_cdn', 'review the MPS eye gaze and SLAM file constants and folder definitions', 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor load_sequences_list_from_cdn to return a sorted list of sequence names']
```

Usage

```
{'load_sequences_from_cdn': 'load a list of sequence names from a CDN JSON file using load_sequences_list_from_cdn', 'load_data_groups_from_cdn': 'load data group name to file mappings from a CDN JSON file using load_data_groups_from_cdn', 'review_MPS_constants': 'review the MPS eye gaze and SLAM file constants and folder definitions', 'summarize_MPS_DATA_GROUP_FILES': 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor_load_sequences_list_from_cdn': 'refactor load_sequences_list_from_cdn to return a sorted list of sequence names'}
```


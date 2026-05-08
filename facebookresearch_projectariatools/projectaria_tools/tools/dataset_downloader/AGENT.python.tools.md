# Agent Python Tools

- repo: facebookresearch/projectariatools
- repo_uri: https://github.com/facebookresearch/projectaria_tools

## File: facebookresearch_projectariatools/projectaria_tools/tools/dataset_downloader/dataset_download_status_manager.py

Prompts

```
['create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load the download status for data groups from an existing JSON status file into the manager', 'save the current download status dictionary to a JSON file for persistence across sessions', 'set the download completion status of a specific data type to true or false', 'get the current download completion status boolean for a specific data type', 'create a DatasetDownloader instance and call download_data to download dataset sequences from CDN to an output folder', 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'build a DatasetDownloader that downloads data with automatic retry on 429, 500, 502, 503, 504 status codes', 'run the DatasetDownloader with overwrite set to false to skip already downloaded data types', 'create a DatasetDownloader that downloads zip files and extracts MPS data types into organized subdirectories', 'run the dataset downloader CLI with a CDN file and output folder to download ProjectARIA dataset sequences', 'run the dataset downloader with data types set to all to download every available data type', 'run the dataset downloader with specific sequence names to download only selected sequences', 'run the dataset downloader with the overwrite flag to redownload and overwrite previously downloaded sequences', 'review the parse_args function that defines CLI arguments for CDN file, output folder, data types, and sequence names', 'load the list of sequence names from a Project Aria CDN JSON file', 'load data group name to file mappings from a Project Aria CDN JSON file', 'review the MPS eye gaze, SLAM, and hand tracking file and folder constants', 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor load_sequences_list_from_cdn to return a sorted list instead of dict keys']
```

Usage

```
{'create_download_status_manager': 'create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load_status_from_json': 'load the download status for data groups from an existing JSON status file into the manager', 'save_status_to_json': 'save the current download status dictionary to a JSON file for persistence across sessions', 'set_download_status': 'set the download completion status of a specific data type to true or false', 'get_download_status': 'get the current download completion status boolean for a specific data type'}
```

## File: facebookresearch_projectariatools/projectaria_tools/tools/dataset_downloader/dataset_downloader.py

Prompts

```
['create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load the download status for data groups from an existing JSON status file into the manager', 'save the current download status dictionary to a JSON file for persistence across sessions', 'set the download completion status of a specific data type to true or false', 'get the current download completion status boolean for a specific data type', 'create a DatasetDownloader instance and call download_data to download dataset sequences from CDN to an output folder', 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'build a DatasetDownloader that downloads data with automatic retry on 429, 500, 502, 503, 504 status codes', 'run the DatasetDownloader with overwrite set to false to skip already downloaded data types', 'create a DatasetDownloader that downloads zip files and extracts MPS data types into organized subdirectories', 'run the dataset downloader CLI with a CDN file and output folder to download ProjectARIA dataset sequences', 'run the dataset downloader with data types set to all to download every available data type', 'run the dataset downloader with specific sequence names to download only selected sequences', 'run the dataset downloader with the overwrite flag to redownload and overwrite previously downloaded sequences', 'review the parse_args function that defines CLI arguments for CDN file, output folder, data types, and sequence names', 'load the list of sequence names from a Project Aria CDN JSON file', 'load data group name to file mappings from a Project Aria CDN JSON file', 'review the MPS eye gaze, SLAM, and hand tracking file and folder constants', 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor load_sequences_list_from_cdn to return a sorted list instead of dict keys']
```

Usage

```
{'download_dataset_sequences': 'create a DatasetDownloader instance and call download_data to download dataset sequences from CDN to an output folder', 'calculate_file_sha1': 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'download_data_with_retry': 'build a DatasetDownloader that downloads data with automatic retry on 429, 500, 502, 503, 504 status codes', 'download_with_resume': 'run the DatasetDownloader with overwrite set to false to skip already downloaded data types', 'extract_and_reorganize_zip': 'create a DatasetDownloader that downloads zip files and extracts MPS data types into organized subdirectories'}
```

## File: facebookresearch_projectariatools/projectaria_tools/tools/dataset_downloader/dataset_downloader_main.py

Prompts

```
['create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load the download status for data groups from an existing JSON status file into the manager', 'save the current download status dictionary to a JSON file for persistence across sessions', 'set the download completion status of a specific data type to true or false', 'get the current download completion status boolean for a specific data type', 'create a DatasetDownloader instance and call download_data to download dataset sequences from CDN to an output folder', 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'build a DatasetDownloader that downloads data with automatic retry on 429, 500, 502, 503, 504 status codes', 'run the DatasetDownloader with overwrite set to false to skip already downloaded data types', 'create a DatasetDownloader that downloads zip files and extracts MPS data types into organized subdirectories', 'run the dataset downloader CLI with a CDN file and output folder to download ProjectARIA dataset sequences', 'run the dataset downloader with data types set to all to download every available data type', 'run the dataset downloader with specific sequence names to download only selected sequences', 'run the dataset downloader with the overwrite flag to redownload and overwrite previously downloaded sequences', 'review the parse_args function that defines CLI arguments for CDN file, output folder, data types, and sequence names', 'load the list of sequence names from a Project Aria CDN JSON file', 'load data group name to file mappings from a Project Aria CDN JSON file', 'review the MPS eye gaze, SLAM, and hand tracking file and folder constants', 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor load_sequences_list_from_cdn to return a sorted list instead of dict keys']
```

Usage

```
{'run_dataset_downloader': 'run the dataset downloader CLI with a CDN file and output folder to download ProjectARIA dataset sequences', 'run_dataset_downloader_all_types': 'run the dataset downloader with data types set to all to download every available data type', 'run_dataset_downloader_specific_sequences': 'run the dataset downloader with specific sequence names to download only selected sequences', 'run_dataset_downloader_overwrite': 'run the dataset downloader with the overwrite flag to redownload and overwrite previously downloaded sequences', 'review_parse_args': 'review the parse_args function that defines CLI arguments for CDN file, output folder, data types, and sequence names'}
```

## File: facebookresearch_projectariatools/projectaria_tools/tools/dataset_downloader/dataset_downloader_utils.py

Prompts

```
['create a DatasetDownloadStatusManager instance with a list of data group names to track download status', 'load the download status for data groups from an existing JSON status file into the manager', 'save the current download status dictionary to a JSON file for persistence across sessions', 'set the download completion status of a specific data type to true or false', 'get the current download completion status boolean for a specific data type', 'create a DatasetDownloader instance and call download_data to download dataset sequences from CDN to an output folder', 'create a function that calculates the SHA1 checksum of a file by reading it in 4KB chunks', 'build a DatasetDownloader that downloads data with automatic retry on 429, 500, 502, 503, 504 status codes', 'run the DatasetDownloader with overwrite set to false to skip already downloaded data types', 'create a DatasetDownloader that downloads zip files and extracts MPS data types into organized subdirectories', 'run the dataset downloader CLI with a CDN file and output folder to download ProjectARIA dataset sequences', 'run the dataset downloader with data types set to all to download every available data type', 'run the dataset downloader with specific sequence names to download only selected sequences', 'run the dataset downloader with the overwrite flag to redownload and overwrite previously downloaded sequences', 'review the parse_args function that defines CLI arguments for CDN file, output folder, data types, and sequence names', 'load the list of sequence names from a Project Aria CDN JSON file', 'load data group name to file mappings from a Project Aria CDN JSON file', 'review the MPS eye gaze, SLAM, and hand tracking file and folder constants', 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor load_sequences_list_from_cdn to return a sorted list instead of dict keys']
```

Usage

```
{'load_sequences_from_cdn': 'load the list of sequence names from a Project Aria CDN JSON file', 'load_data_groups_from_cdn': 'load data group name to file mappings from a Project Aria CDN JSON file', 'review_MPS_constants': 'review the MPS eye gaze, SLAM, and hand tracking file and folder constants', 'summarize_MPS_DATA_GROUP_FILES': 'summarize the MPS data group files dictionary mapping group names to file lists', 'refactor_load_sequences_list_from_cdn': 'refactor load_sequences_list_from_cdn to return a sorted list instead of dict keys'}
```


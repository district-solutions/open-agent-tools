# Agent Python Tools

- repo: facebookresearch/earsdataset
- repo_uri: https://github.com/facebookresearch/ears_dataset

## File: facebookresearch_earsdataset/download_blind_testset.py

Prompts

```
['create a function that downloads a file from a URL and saves it to a specified filename', 'create a function that extracts a zip file to a specified directory', 'run the script to download and extract the 1.4GB blind testset dataset from GitHub', 'refactor the download_file function to add progress reporting for large file downloads', 'review the unzip_file function to ensure safe extraction and proper error handling', 'run the script to download and extract all 107 speakers of the EARS dataset', 'create a function that downloads a file from a URL and saves it to a local filename', 'create a function that extracts a zip file to a specified directory creating it if needed']
```

Usage

```
{'download_file': 'create a function that downloads a file from a URL and saves it to a specified filename', 'unzip_file': 'create a function that extracts a zip file to a specified directory', 'run_download_blind_testset': 'run the script to download and extract the 1.4GB blind testset dataset from GitHub', 'refactor_download_file': 'refactor the download_file function to add progress reporting for large file downloads', 'review_unzip_file': 'review the unzip_file function to ensure safe extraction and proper error handling'}
```

## File: facebookresearch_earsdataset/download_ears.py

Prompts

```
['create a function that downloads a file from a URL and saves it to a specified filename', 'create a function that extracts a zip file to a specified directory', 'run the script to download and extract the 1.4GB blind testset dataset from GitHub', 'refactor the download_file function to add progress reporting for large file downloads', 'review the unzip_file function to ensure safe extraction and proper error handling', 'run the script to download and extract all 107 speakers of the EARS dataset', 'create a function that downloads a file from a URL and saves it to a local filename', 'create a function that extracts a zip file to a specified directory creating it if needed']
```

Usage

```
{'download_EARS_dataset': 'run the script to download and extract all 107 speakers of the EARS dataset', 'create_download_file_function': 'create a function that downloads a file from a URL and saves it to a local filename', 'create_unzip_file_function': 'create a function that extracts a zip file to a specified directory creating it if needed', 'refactor_download_file': 'refactor the download_file function to add retry logic and progress reporting for large files', 'review_unzip_file': 'review the unzip_file function to ensure it safely extracts archives without path traversal vulnerabilities'}
```


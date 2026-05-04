# Agent Python Tools

- repo: facebookresearch/dynamicstereo
- repo_uri: https://github.com/facebookresearch/dynamic_stereo

## File: facebookresearch_dynamicstereo/scripts/checksum_check.py

Prompts

```
['run the checksum checker on a folder of zip files against expected SHA256 hashes', 'run the checksum tool with dump mode to generate a new SHA256 hashes JSON file', 'check a single zip file SHA256 hash against expected values from a JSON file', 'compute the SHA256 hash digest of any file using chunked reading', 'load expected SHA256 hash values from a JSON file for dataset verification', 'download and unpack a dataset from a JSON link list file using parallel workers', 'build an argument parser for downloading a named dataset with configurable splits and workers', 'unpack a downloaded archive file into a split-specific folder within the download directory', 'download a single dataset file with optional SHA256 checksum verification and skip logic', 'download a file from a URL with a tqdm progress bar showing transfer speed']
```

Usage

```
{'run_checksum_verification': 'run the checksum checker on a folder of zip files against expected SHA256 hashes', 'run_dump_sha256s': 'run the checksum tool with dump mode to generate a new SHA256 hashes JSON file', 'check_single_file_sha256': 'check a single zip file SHA256 hash against expected values from a JSON file', 'compute_file_sha256': 'compute the SHA256 hash digest of any file using chunked reading', 'load_expected_sha256s': 'load expected SHA256 hash values from a JSON file for dataset verification'}
```

## File: facebookresearch_dynamicstereo/scripts/download_utils.py

Prompts

```
['run the checksum checker on a folder of zip files against expected SHA256 hashes', 'run the checksum tool with dump mode to generate a new SHA256 hashes JSON file', 'check a single zip file SHA256 hash against expected values from a JSON file', 'compute the SHA256 hash digest of any file using chunked reading', 'load expected SHA256 hash values from a JSON file for dataset verification', 'download and unpack a dataset from a JSON link list file using parallel workers', 'build an argument parser for downloading a named dataset with configurable splits and workers', 'unpack a downloaded archive file into a split-specific folder within the download directory', 'download a single dataset file with optional SHA256 checksum verification and skip logic', 'download a file from a URL with a tqdm progress bar showing transfer speed']
```

Usage

```
{'download_dataset_parallel': 'download and unpack a dataset from a JSON link list file using parallel workers', 'build_arg_parser_download': 'build an argument parser for downloading a named dataset with configurable splits and workers', 'unpack_split_file': 'unpack a downloaded archive file into a split-specific folder within the download directory', 'download_split_file': 'download a single dataset file with optional SHA256 checksum verification and skip logic', 'download_with_progress_bar': 'download a file from a URL with a tqdm progress bar showing transfer speed'}
```


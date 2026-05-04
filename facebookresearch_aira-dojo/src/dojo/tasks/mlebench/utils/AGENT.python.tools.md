# Agent Python Tools

- repo: facebookresearch/aira-dojo
- repo_uri: https://github.com/facebookresearch/aira-dojo

## File: facebookresearch_aira-dojo/src/dojo/tasks/mlebench/utils/data.py

Prompts

```
['extract all compressed files from a directory path supporting 7z, zip, and tar.gz formats recursively', 'create a tar archive from a directory tree and write it to a specified output file path', 'read a split text file and return a list of competition IDs for the given split identifier', 'recursively extract nested compressed archives from a directory with optional force and delete options', 'check if a file is a supported compressed format including 7z, zip, gz, and tar.gz', 'generate a YAML file with manual overrides for MLEBench competition IDs from a split text file', 'run the script to generate mlebench manual overrides YAML for a given split name like low_dev', 'create a mlebench split YAML file containing competition IDs from a split text file in the splits directory', 'review the generate_manual_overrides function that reads split text files and writes YAML override configurations', 'refactor generate_manual_overrides to accept a custom output path instead of writing to the current working directory']
```

Usage

```
{'extract_compressed_files': 'extract all compressed files from a directory path supporting 7z, zip, and tar.gz formats recursively', 'create_tarball_from_directory': 'create a tar archive from a directory tree and write it to a specified output file path', 'get_competition_ids_in_split': 'read a split text file and return a list of competition IDs for the given split identifier', 'extract_nested_archives': 'recursively extract nested compressed archives from a directory with optional force and delete options', 'check_compression_format': 'check if a file is a supported compressed format including 7z, zip, gz, and tar.gz'}
```

## File: facebookresearch_aira-dojo/src/dojo/tasks/mlebench/utils/generate_manual_overrides.py

Prompts

```
['extract all compressed files from a directory path supporting 7z, zip, and tar.gz formats recursively', 'create a tar archive from a directory tree and write it to a specified output file path', 'read a split text file and return a list of competition IDs for the given split identifier', 'recursively extract nested compressed archives from a directory with optional force and delete options', 'check if a file is a supported compressed format including 7z, zip, gz, and tar.gz', 'generate a YAML file with manual overrides for MLEBench competition IDs from a split text file', 'run the script to generate mlebench manual overrides YAML for a given split name like low_dev', 'create a mlebench split YAML file containing competition IDs from a split text file in the splits directory', 'review the generate_manual_overrides function that reads split text files and writes YAML override configurations', 'refactor generate_manual_overrides to accept a custom output path instead of writing to the current working directory']
```

Usage

```
{'generate_yaml_manual_overrides': 'generate a YAML file with manual overrides for MLEBench competition IDs from a split text file', 'run_generate_manual_overrides': 'run the script to generate mlebench manual overrides YAML for a given split name like low_dev', 'create_mlebench_split_yaml': 'create a mlebench split YAML file containing competition IDs from a split text file in the splits directory', 'review_generate_manual_overrides': 'review the generate_manual_overrides function that reads split text files and writes YAML override configurations', 'refactor_generate_manual_overrides': 'refactor generate_manual_overrides to accept a custom output path instead of writing to the current working directory'}
```

